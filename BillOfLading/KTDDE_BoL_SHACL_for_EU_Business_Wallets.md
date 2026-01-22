# KTDDE Bill of Lading (BoL) — What this SHACL Shape Means for EU Business Wallets

This document explains, in plain language, what the **KTDDE Bill of Lading (BoL) SHACL Shape** contains and why it matters when a Bill of Lading is carried in an **EU Business Wallet** as a **W3C Verifiable Credential (VC)**.

It also includes:
- a **W3C VC example** (JSON / JSON-LD-friendly structure), and
- a **plain JSON Schema example** you can use for simple validation outside the Linked Data stack.

---

## 1. What a Bill of Lading is (in business terms)

A **Bill of Lading** is a core shipping document that typically acts as:
- a **receipt** issued by the carrier (or its agent) acknowledging goods were received for carriage,
- evidence of the **contract of carriage** (depending on type and legal regime), and
- sometimes a **document of title** (depending on whether it is negotiable and the applicable rules).

In cross-border trade, many actors rely on BoL data:
- **Shippers and consignees** to track and claim goods,
- **Carriers and forwarders** to manage transport execution,
- **Banks and financiers** (trade finance) to match documents against documentary credit conditions,
- **Customs and regulators** for risk assessment and controls.

---

## 2. What the “KTDDE BoL SHACL Shape” is

Think of the SHACL Shape as a **data checklist** and a **validation rulebook**:

- It lists the **data items** a KTDDE-style Bill of Lading can contain.
- It defines the **structure** (what belongs inside what).
- It can enforce basic constraints such as:
  - “this field should be a date”
  - “this field should point to a Party object”
  - “this field may repeat (array)”

In other words: it turns “a BoL concept” into a **machine-checkable data model**.

---

## 3. Why this matters for EU Business Wallets and W3C Verifiable Credentials

When the BoL is packaged as a **Verifiable Credential**:
- the **issuer** (for example the carrier or an authorised platform operator) can cryptographically sign the BoL data,
- the **holder** (e.g., exporter, importer, forwarder, or logistics platform wallet) can present the credential to others,
- the **verifier** (e.g., bank, buyer, customs, insurer) can check:
  - the signature (authenticity),
  - the issuer identity / trust chain,
  - and the data structure (conformance with the BoL shape).

This is particularly useful in EU Business Wallet scenarios where:
- data must be **reused across many processes** (trade, finance, compliance),
- verification should be **automatable**, and
- sensitive details can be **selectively disclosed** (depending on the VC format and policy).

---

## 4. What the BoL Shape covers (content overview)

Below are the main information groups covered in the KTDDE BoL Shape.

### A) Document basics
Typical “header” fields:
- a **document identifier**
- the **issue date**
- optional references such as a **house waybill identifier** (when the BoL is linked to house-level movement documents)

### B) Parties (who is involved)
The BoL connects to Party objects for the common actors, such as:
- consignor (shipper)
- consignee
- carrier
- notify party
- freight payer
- buyer / exporter / importer (when relevant for the process or data pipeline)

> Note: The BoL shape focuses on linking to parties. Party “details” (like full legal name, address lines, identifier schemes) are typically handled via Party/Identifier/Address sub-shapes and/or via wallet-held legal-entity credentials.

### C) Transport movement and places
The BoL captures:
- ports (as UN/LOCODE strings in some fields),
- “places” modelled as Location objects (place of loading, discharge, delivery, issue),
- timing information such as:
  - estimated time of departure,
  - planned arrival,
  - actual departure and arrival timestamps.

### D) Goods and packaging
The BoL includes goods lines (GoodsItem), with data such as:
- description of goods,
- HS code,
- product identifiers/names (when available),
- quantities and units,
- packaging: count, packaging type codes, shipping marks.

### E) Containers / equipment and seals
For containerised shipments:
- transport equipment with container number and equipment identifiers,
- seals and seal identifiers (where used).

### F) Commercial / customs-related values and conditions
The BoL shape supports:
- freight charges (as a MonetaryAmount object with value + currency),
- declared customs value (MonetaryAmount),
- transport contract conditions and delivery terms text,
- payment terms codes (e.g., prepaid/collect).

---

## 5. Practical validation: what can be checked automatically

With the shape + VC packaging, a verifier can automate checks like:
- required fields exist (where mandated),
- dates are correctly typed,
- goods items are present and contain basic elements (description, quantity, etc.),
- locations and ports are present and consistently represented,
- monetary amounts contain both value and currency code,
- parties are present as references (and can be cross-checked against separate legal-entity credentials).

This enables “continuous validation” patterns in wallet ecosystems:
- validate **issuer and signature** (trust),
- validate **structure** (shape conformance),
- validate **business rules** (policy / workflow rules on top).

---

# 6. W3C Verifiable Credential example (BoL)

This example illustrates how a BoL can be carried as a VC.  
It is **not** a signed VC; it shows the typical payload structure.

```json
{
  "@context": [
    "https://www.w3.org/ns/credentials/v2",
    "https://iri.suomi.fi/model/dsibol/0.0.1/context" 
  ],
  "type": ["VerifiableCredential", "KTDDEBillOfLadingCredential"],
  "issuer": "did:web:carrier.example",
  "issuanceDate": "2026-01-22T10:00:00Z",
  "credentialSubject": {
    "type": "BillOfLading",
    "documentIdentifier": ["BOL-2026-000123"],
    "issueDate": ["2026-01-21"],
    "houseWaybillDocumentIdentifier": ["HWB-556677"],
    "shippingMarks": ["MARKS: ACME/HELSINKI/2026"],
    "descriptionOfGoodsText": ["Planed timber products, kiln-dried, wrapped"],
    "portOfLoadingUNLocode": ["FIHEL"],
    "portOfDischargeUNLocode": ["NLRTM"],
    "placeOfDeliveryUNLocode": ["NLRTM"],

    "estimatedTimeOfDeparture": ["2026-01-21T18:00:00Z"],
    "plannedArrivalDateTime": ["2026-01-24T08:00:00Z"],
    "actualDepartureDateTime": ["2026-01-21T18:35:00Z"],
    "actualArrivalDateTime": ["2026-01-24T07:50:00Z"],

    "consignorParty": [{
      "type": "Party",
      "partyIdentifier": [{ "type": "Identifier" }],
      "partyAddress": [{ "type": "Address" }]
    }],
    "consigneeParty": [{
      "type": "Party",
      "partyIdentifier": [{ "type": "Identifier" }],
      "partyAddress": [{ "type": "Address" }]
    }],
    "carrierParty": [{
      "type": "Party",
      "partyIdentifier": [{ "type": "Identifier" }]
    }],
    "notifyParty": [{
      "type": "Party",
      "partyIdentifier": [{ "type": "Identifier" }]
    }],
    "payerParty": [{
      "type": "Party",
      "partyIdentifier": [{ "type": "Identifier" }]
    }],

    "placeOfLoading": [{
      "type": "Location",
      "unlocode": ["FIHEL"],
      "locationName": ["Helsinki Port"],
      "locationCountry": [{
        "type": "Country",
        "countryCode": ["FI"],
        "countryName": ["Finland"]
      }]
    }],

    "placeOfDischarge": [{
      "type": "Location",
      "unlocode": ["NLRTM"],
      "locationName": ["Port of Rotterdam"],
      "locationCountry": [{
        "type": "Country",
        "countryCode": ["NL"],
        "countryName": ["Netherlands"]
      }]
    }],

    "usesTransportMeans": [{
      "type": "TransportMeans",
      "vesselName": ["MV Example Vessel"],
      "voyageNumber": ["VOY-2026-01"],
      "iMOShipID": ["1234567"]
    }],

    "usesTransportEquipment": [{
      "type": "TransportEquipment",
      "containerNumber": ["MSCU1234567"],
      "hasSeal": [{
        "type": "Seal",
        "sealedIndicator": [true],
        "sealIdentifier": [{ "type": "Identifier" }]
      }]
    }],

    "hasPaymentTerms": [{
      "type": "PaymentTerms",
      "freightPaymentTermCode": ["PREPAID"]
    }],

    "freightChargesAmount": [{
      "type": "MonetaryAmount",
      "amountValue": [1250.00],
      "currencyCode": ["EUR"]
    }],

    "declaredCustomsValueAmount": [{
      "type": "MonetaryAmount",
      "amountValue": [18500.00],
      "currencyCode": ["EUR"]
    }],

    "totalGrossWeight": [{
      "type": "Quantity",
      "quantityValue": ["12000"],
      "unitCode": ["KGM"]
    }],

    "totalPackageQuantity": [{
      "type": "Quantity",
      "quantityValue": ["24"],
      "unitCode": ["PKG"]
    }],

    "hasGoodsItem": [{
      "type": "GoodsItem",
      "descriptionOfGoodsText": ["Timber, planed, kiln-dried"],
      "hSCode": ["4407"],
      "productIdentifier": ["SKU-PLANK-44"],
      "productName": ["Planed Timber Planks"],
      "hasQuantity": [{
        "type": "Quantity",
        "quantityValue": ["24"],
        "unitCode": ["PKG"]
      }],
      "hasPackage": [{
        "type": "Package",
        "packageCount": [24],
        "shippingMarks": ["MARKS: ACME/HELSINKI/2026"]
      }]
    }]
  }
}
```

**What to notice**
- Many fields are arrays because the current schema/shape allows repeated values.
- Party and Identifier details are intentionally left minimal here; in wallet deployments, party identity is often proven via separate legal-entity credentials (company certificate, mandates, etc.).

---

# 7. Plain JSON Schema example (for the VC payload)

This is a **minimal** schema that validates the VC wrapper and a subset of the BoL content.  
It is not intended to replace the full generated schema; it is a human-friendly starting point.

```json
{
  "$schema": "https://json-schema.org/draft/2020-12/schema",
  "title": "KTDDE Bill of Lading VC (minimal)",
  "type": "object",
  "required": ["type", "issuer", "issuanceDate", "credentialSubject"],
  "properties": {
    "@context": { "type": "array", "items": { "type": ["string", "object"] } },
    "type": { "type": "array", "items": { "type": "string" } },
    "issuer": { "type": "string" },
    "issuanceDate": { "type": "string" },
    "credentialSubject": {
      "type": "object",
      "required": ["documentIdentifier", "issueDate", "portOfLoadingUNLocode", "portOfDischargeUNLocode"],
      "properties": {
        "documentIdentifier": { "type": "array", "items": { "type": "string" } },
        "issueDate": { "type": "array", "items": { "type": "string" } },

        "portOfLoadingUNLocode": { "type": "array", "items": { "type": "string" } },
        "portOfDischargeUNLocode": { "type": "array", "items": { "type": "string" } },

        "shippingMarks": { "type": "array", "items": { "type": "string" } },
        "descriptionOfGoodsText": { "type": "array", "items": { "type": "string" } },

        "freightChargesAmount": {
          "type": "array",
          "items": {
            "type": "object",
            "required": ["amountValue", "currencyCode"],
            "properties": {
              "amountValue": { "type": "array", "items": { "type": "number" } },
              "currencyCode": { "type": "array", "items": { "type": "string" } }
            }
          }
        },

        "hasGoodsItem": {
          "type": "array",
          "items": {
            "type": "object",
            "properties": {
              "descriptionOfGoodsText": { "type": "array", "items": { "type": "string" } },
              "hSCode": { "type": "array", "items": { "type": "string" } }
            }
          }
        }
      }
    }
  }
}
```

---

## 8. How to use these artifacts together (operational view)

In a wallet-enabled business ecosystem you typically use:
1. **The SHACL Shape** to define and validate *structure* of BoL data.
2. **The JSON-LD serialization** to enable consistent meaning across systems and for VC packaging.
3. **The JSON Schema** to support quick validation in mainstream tooling and APIs.
4. **The VC format** to ensure the BoL can be issued, held, and presented with cryptographic trust.

If you want, the next logical step is to document:
- which party roles are “mandatory” for your target process (trade finance, customs, procurement logistics),
- which fields are safe for selective disclosure,
- and how the BoL VC should be linked to related credentials (company certificates, mandates, purchase orders, invoices).
