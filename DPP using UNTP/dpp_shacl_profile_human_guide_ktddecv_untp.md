# Digital Product Passport (DPP) — SHACL Profile Guide

This guide explains the **DPP SHACL profile** you received, in human‑friendly terms. It’s intended for non‑experts who need to understand what each node (thing) and property (field) means and how to populate it. Examples use the **Finnish gluelam → Japan** test case.

---

## Contents
1. [What is this?](#what-is-this)
2. [Validation scope](#validation-scope)
3. [Nodes (data blocks)](#nodes-data-blocks)
   - [VC: Verifiable Credential](#vc-verifiable-credential)
   - [TradeLineItem (credentialSubject)](#tradelineitem-credentialsubject)
   - [Consignment](#consignment)
   - [Quantity](#quantity)
   - [SeaWaybill](#seawaybill)
   - [Classification (UNTP)](#classification-untp)
   - [Party (UNTP)](#party-untp)
   - [ConformitySchemeVocabulary (UNTP SVC)](#conformityschemevocabulary-untp-svc)
   - [ConformityScheme (UNTP)](#conformityscheme-untp)
   - [Criterion (UNTP)](#criterion-untp)
   - [ThresholdValue (UNTP)](#thresholdvalue-untp)
   - [MetricValue (UNTP)](#metricvalue-untp)
   - [Regulation (UNTP)](#regulation-untp)
4. [Code lists & constraints](#code-lists--constraints)
5. [Tips for implementers](#tips-for-implementers)
6. [Appendix: Mini JSON examples](#appendix-mini-json-examples)

[⬆️ Back to top](#digital-product-passport-dpp--shacl-profile-guide)

---

## What is this?
A **SHACL profile** is a set of validation rules for RDF/JSON‑LD data. Here we validate a **DPP** expressed as a **W3C Verifiable Credential (VC)**. The payload uses:

- **ktddecv:** native terms (trade/transport/logistics) from the KTDDE Core Vocabulary
- **UNTP (untp-core / untp-svc):** sustainability & conformity structures

This hybrid ("dual‑context") profile maximizes **ktddecv** adoption while keeping **UNTP** compatibility.

[⬆️ Back to top](#digital-product-passport-dpp--shacl-profile-guide)

---

## Validation scope
- The **top‑level** object is a `vc:VerifiableCredential` with a **credentialSubject** that is a `ktddecv:TradeLineItem`.
- Nested blocks: **Consignment**, **SeaWaybill**, **Quantity**, **Classification**, **Party**, and **Conformity/Regulation** structures from UNTP.

[⬆️ Back to top](#digital-product-passport-dpp--shacl-profile-guide)

---

## Nodes (data blocks)

### VC: Verifiable Credential
**Purpose:** Wraps the DPP content with an issuer and issuance time.

| Property | Required | Type | Constraint | Example |
|---|---|---|---|---|
| `vc:issuer` | ✅ | string/URI | should be a DID/URI | `did:org:FI-1234567-8` |
| `vc:validFrom` | ✅ | dateTime | ISO 8601 | `2025-10-13T13:00:00Z` |
| `vc:credentialSubject` | ✅ | node | must follow **TradeLineItem** shape | *(see below)* |

[⬆️ Back to top](#digital-product-passport-dpp--shacl-profile-guide)

---

### TradeLineItem (credentialSubject)
**IRI:** `ktddecv:TradeLineItem`  
**Purpose:** The specific product/line item that the DPP describes.

| Property | Required | Type | Constraint | Example (Gluelam) |
|---|---|---|---|---|
| `ktddecv:productName` | ✅ | string | — | `"Glued Laminated Timber (Gluelam) Beam"` |
| `ktddecv:productIdentifier` | ✅ | string | Unique per item/batch | `"GLU-200x600-GL28h-2025-10-001"` |
| `ktddecv:productDescription` | ◻️ | string | — | `"GL28h; 200×600×12000 mm; MUF; E1"` |
| `ktddecv:appliedCommodityClassification` | ✅ | node | **UNTP Classification** shape | HS 4418 (see below) |
| `ktddecv:forConsignment` | ✅ | node | **Consignment** shape | Shipment FI→JP |
| `ktddecv:governedByRuleSet` | ◻️ | node | **ConformitySchemeVocabulary** | EN 14080, CPR, JP BSL |

[⬆️ Back to top](#digital-product-passport-dpp--shacl-profile-guide)

---

### Consignment
**IRI:** `ktddecv:Consignment`  
**Purpose:** Shipment details for the line item.

| Property | Required | Type | Constraint | Example |
|---|---|---|---|---|
| `ktddecv:documentDate` | ✅ | date | `YYYY-MM-DD` | `2025-10-01` |
| `ktddecv:consignorParty` | ✅ | node | **UNTP Party** | Nordic Glulam Oy |
| `ktddecv:consigneeParty` | ✅ | node | **UNTP Party** | Tokyo Structural Timber KK |
| `ktddecv:portOfLoadingUNLocode` | ✅ | string | `^[A-Z]{5}$` | `FIHEL` (Helsinki) |
| `ktddecv:portOfDischargeUNLocode` | ✅ | string | `^[A-Z]{5}$` | `JPTYO` (Tokyo) |
| `ktddecv:incotermsCode` | ✅ | code | one of Incoterms® | `CIF` |
| `ktddecv:incotermsLocation` | ◻️ | string | — | `"Tokyo"` |
| `ktddecv:packageCount` | ✅ | integer | ≥ 1 | `6` |
| `ktddecv:totalGoodsItemQuantity` | ✅ | node | **Quantity** | `7.8 TNE` total mass |
| `ktddecv:relatesToTransportDocument` | ✅ | node | **SeaWaybill** | `MAEU-1234567890` |

[⬆️ Back to top](#digital-product-passport-dpp--shacl-profile-guide)

---

### Quantity
**IRI:** `ktddecv:Quantity`  
**Purpose:** A measured amount (value + unit).

| Property | Required | Type | Constraint | Example |
|---|---|---|---|---|
| `ktddecv:value` | ✅ | decimal | — | `7.8` |
| `ktddecv:unitCode` | ✅ | string | UN/CEFACT code | `"TNE"` (tonne) |

[⬆️ Back to top](#digital-product-passport-dpp--shacl-profile-guide)

---

### SeaWaybill
**IRI:** `ktddecv:SeaWaybill`  
**Purpose:** The non‑negotiable sea transport document used in the shipment.

| Property | Required | Type | Constraint | Example |
|---|---|---|---|---|
| `ktddecv:transportDocumentNumber` | ✅ | string | — | `"MAEU-1234567890"` |

[⬆️ Back to top](#digital-product-passport-dpp--shacl-profile-guide)

---

### Classification (UNTP)
**IRI:** `untp-core:Classification`  
**Purpose:** Commodity classification such as HS.

| Property | Required | Type | Constraint | Example |
|---|---|---|---|---|
| `untp-core:code` | ✅ | string | HS pattern `^[0-9]{2,10}$` | `"4418"` |
| `schemaorg:name` | ◻️ | string | — | `"Builders' joinery and carpentry of wood"` |
| `untp-core:schemeID` | ✅ | string | identifies the scheme | `"HS-2022"` |
| `untp-core:schemeName` | ◻️ | string | human label | `"Harmonized System 2022"` |

[⬆️ Back to top](#digital-product-passport-dpp--shacl-profile-guide)

---

### Party (UNTP)
**IRI:** `untp-core:Party`  
**Purpose:** Organizations involved (consignor/consignee, scheme owners, regulators).

| Property | Required | Type | Constraint | Example |
|---|---|---|---|---|
| `schemaorg:name` | ✅ | string | — | `"Nordic Glulam Oy"` |
| `untp-core:registeredId` | ◻️ | string | registration number | `"FI12345678"` |
| `untp-core:idScheme` | ◻️ | IRI or literal | scheme identifier | `urn:scheme:VAT` |
| `untp-core:registrationCountry` | ◻️ | IRI | `CountryId#CC` | `…/CountryId#FI` |
| `untp-core:organisationWebsite` | ◻️ | anyURI | — | `https://www.nordic-glulam.example` |

[⬆️ Back to top](#digital-product-passport-dpp--shacl-profile-guide)

---

### ConformitySchemeVocabulary (UNTP SVC)
**IRI:** `untp-svc:ConformitySchemeVocabulary`  
**Purpose:** Describes the conformity/sustainability rule set governing the product.

| Property | Required | Type | Constraint | Example |
|---|---|---|---|---|
| `untp-core:scheme` | ✅ | node | **ConformityScheme** | EN 14080 |
| `untp-core:conformityCriterion` | ◻️ | node (repeatable) | **Criterion** | E1 emissions, FSC/PEFC |
| `untp-core:regulatoryAlignment` | ◻️ | node (repeatable) | **Regulation** | CPR; JP BSL |
| `untp-core:industryScope` | ◻️ | IRI/literal | — | NACE C16.23 |
| `untp-core:geographicScope` | ◻️ | IRI | `CountryId#CC` | `…/CountryId#JP` |

[⬆️ Back to top](#digital-product-passport-dpp--shacl-profile-guide)

---

### ConformityScheme (UNTP)
**IRI:** `untp-core:ConformityScheme`  
**Purpose:** The named scheme that defines criteria, ownership, and dates.

| Property | Required | Type | Constraint | Example |
|---|---|---|---|---|
| `schemaorg:name` | ✅ | string | — | `"EN 14080 — Glued Laminated Timber"` |
| `schemaorg:description` | ◻️ | string | — | `"Harmonized standard under CPR"` |
| `untp-core:version` | ◻️ | string | — | `"2013"` |
| `untp-core:validFrom` | ◻️ | string/date | decide profile | `"2013-08-01"` |
| `untp-core:owner` | ◻️ | node | **Party** | CEN |

[⬆️ Back to top](#digital-product-passport-dpp--shacl-profile-guide)

---

### Criterion (UNTP)
**IRI:** `untp-core:Criterion`  
**Purpose:** Each rule/metric that the product meets (e.g., emissions, sourcing).

| Property | Required | Type | Constraint | Example |
|---|---|---|---|---|
| `schemaorg:name` | ✅ | string | — | `"Formaldehyde emission limit"` |
| `schemaorg:description` | ◻️ | string | — | `"Class E1 per EN 717-1"` |
| `untp-core:conformityTopic` | ◻️ | IRI | code list IRI | `…/conformityTopicCode#emissions` |
| `untp-core:status` | ◻️ | IRI | code list IRI | `…/statusCode#compliant` |
| `untp-core:thresholdValue` | ◻️ | node | **ThresholdValue** | 0.1 PPM |
| `untp-core:performanceLevel` | ◻️ | string | — | `"E1"` |

[⬆️ Back to top](#digital-product-passport-dpp--shacl-profile-guide)

---

### ThresholdValue (UNTP)
**Purpose:** Holds a metric name, value+unit, and optional scoring.

| Property | Required | Type | Constraint | Example |
|---|---|---|---|---|
| `untp-core:metricName` | ✅ | string | — | `"Formaldehyde concentration"` |
| `untp-core:metricValue` | ✅ | node | **MetricValue** | *(see next)* |
| `untp-core:score` | ◻️ | string | — | `"Pass"` |
| `untp-core:accuracy` | ◻️ | double | — | `0.95` |

[⬆️ Back to top](#digital-product-passport-dpp--shacl-profile-guide)

---

### MetricValue (UNTP)
**Purpose:** A numeric value and a unit from the UN/CEFACT UnitMeasureCode list.

| Property | Required | Type | Constraint | Example |
|---|---|---|---|---|
| `untp-core:value` | ✅ | double | — | `0.1` |
| `untp-core:unit` | ✅ | IRI | `UnitMeasureCode#…` | `…/UnitMeasureCode#PPM` |

[⬆️ Back to top](#digital-product-passport-dpp--shacl-profile-guide)

---

### Regulation (UNTP)
**IRI:** `untp-core:Regulation`  
**Purpose:** A law/regulation aligned with the scheme (e.g., CPR, JP BSL).

| Property | Required | Type | Constraint | Example |
|---|---|---|---|---|
| `schemaorg:name` | ✅ | string | — | `"EU Construction Products Regulation (CPR) No 305/2011"` |
| `untp-core:jurisdictionCountry` | ✅ | IRI | `CountryId#CC` | `…/CountryId#EU` / `…/CountryId#JP` |
| `untp-core:effectiveDate` | ◻️ | string/date | decide profile | `"2011-04-04"` |
| `untp-core:administeredBy` | ◻️ | node | **Party** | European Commission / MLIT |

[⬆️ Back to top](#digital-product-passport-dpp--shacl-profile-guide)

---

## Code lists & constraints
- **UN/LOCODE**: 5 uppercase letters (e.g., `FIHEL`, `JPTYO`).
- **Incoterms®**: use official three‑letter codes (`EXW`, `FCA`, …, `DDP`).
- **Units**: UN/CEFACT UnitMeasureCode IRIs (e.g., `…/UnitMeasureCode#TNE`, `#PPM`).
- **Countries**: UN/CEFACT CountryId IRIs (e.g., `…/CountryId#FI`, `#JP`).

> In production, prefer **SKOS code lists** with `sh:in` or `sh:hasValue` where feasible, or remote resolvable IRIs.

[⬆️ Back to top](#digital-product-passport-dpp--shacl-profile-guide)

---

## Tips for implementers
- Keep **ktddecv** predicates for logistics/trade to enable strict SHACL and governance.
- Represent sustainability programs and metrics with **UNTP** structures for wider interoperability.
- If you already have a GS1/Schema.org profile, keep a parallel **JSON‑LD context** for aliasing to those terms without changing the graph.
- Lock datatypes early (e.g., `xsd:date` vs `xsd:dateTime`) and be consistent across issuers.

[⬆️ Back to top](#digital-product-passport-dpp--shacl-profile-guide)

---

## Appendix: Mini JSON examples

### A) Consignment snippet
```json
{
  "ktddecv:documentDate": "2025-10-01",
  "ktddecv:portOfLoadingUNLocode": "FIHEL",
  "ktddecv:portOfDischargeUNLocode": "JPTYO",
  "ktddecv:incotermsCode": "CIF",
  "ktddecv:packageCount": 6,
  "ktddecv:totalGoodsItemQuantity": {
    "ktddecv:value": 7.8,
    "ktddecv:unitCode": "TNE"
  },
  "ktddecv:relatesToTransportDocument": {
    "@type": "ktddecv:SeaWaybill",
    "ktddecv:transportDocumentNumber": "MAEU-1234567890"
  }
}
```

### B) Classification snippet (UNTP)
```json
{
  "@type": "untp-core:Classification",
  "untp-core:code": "4418",
  "schemaorg:name": "Builders' joinery and carpentry of wood",
  "untp-core:schemeID": "HS-2022",
  "untp-core:schemeName": "Harmonized System 2022"
}
```

### C) Party snippets (UNTP)
```json
{
  "@type": "untp-core:Party",
  "schemaorg:name": "Nordic Glulam Oy",
  "untp-core:registeredId": "FI12345678",
  "untp-core:idScheme": "urn:scheme:VAT",
  "untp-core:registrationCountry": "https://vocabulary.uncefact.org/CountryId#FI",
  "untp-core:organisationWebsite": "https://www.nordic-glulam.example"
}
```

[⬆️ Back to top](#digital-product-passport-dpp--shacl-profile-guide)

