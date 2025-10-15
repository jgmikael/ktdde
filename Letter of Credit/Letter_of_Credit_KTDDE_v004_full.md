# Letter of Credit (LoC) — KTDDE Application Profile  
**Version:** 0.0.4  
**Based on:** Key Trade Documents and Data Elements (KTDDE) Core Vocabulary  
**Profile type:** SHACL Application Profile  
**Scenario:** *FinnLam Oy (Finland) → Tokyo Builders Ltd. (Japan)*  

---

## 🧭 Overview

A **Letter of Credit (LoC)** is a secure financial commitment issued by a bank on behalf of a buyer to guarantee payment to a seller once agreed shipping and documentation conditions are met.  
Digitally expressed through the **KTDDE Ontology v0.0.4**, the LoC becomes a *semantically interoperable* document that can be automatically verified, shared, and stored — for example inside an **EU Business Wallet** as a verifiable credential.

This documentation describes the **KTDDE Application Profile** for the Letter of Credit using the *Finnish gluelam exports to Japan* scenario.

[↑ Back to top](#letter-of-credit-loc--ktdde-application-profile)

---

## 🌍 Scenario Overview

| Role | Party | Details |
|------|-------|----------|
| **Applicant (Importer)** | Tokyo Builders Ltd. | 2-17-1 Marunouchi, Chiyoda-ku, Tokyo, Japan |
| **Beneficiary (Exporter)** | FinnLam Oy | Kuokkala, Jyväskylä, Finland |
| **Issuing Bank** | Nordea Bank Finland Plc | Helsinki, Finland |
| **Advising / Confirming Bank** | Mitsui Bank Ltd. | Tokyo, Japan |
| **Goods** | Glued laminated timber beams, spruce, planed, 12 m³ |
| **Shipment** | Port of Helsinki (FIHEL) → Port of Tokyo (JPTYO) |
| **Incoterm** | CIF Tokyo (Incoterms® 2020) |
| **LoC Amount** | EUR 250 000 |
| **Date of Issue** | 2025-09-30 |
| **Expiry Date** | 2025-12-31 |

---

## 📄 1. Document Information

| Property | Description | Example | KTDDE Reference |
|-----------|--------------|----------|----------------|
| **Document Identifier** | Unique identifier assigned to this Letter of Credit. <br> *_(Hint: identifies a trade or transport document in a business transaction.)_* | LC-2025-000123 | `ktddecv:creditIdentifier` |
| **Documentary Credit Type** | Defines whether the LoC is irrevocable, revocable, transferable, etc. | IRREVOCABLE | `ktddecv:documentaryCreditTypeCode` |
| **Confirmation Instruction** | Specifies whether confirmation is required or added. | CONFIRM | `ktddecv:confirmationInstructionCode` |
| **Date of Issue** | Date when the LoC was issued. | 2025-09-30 | `ktddecv:documentDate` |
| **Expiry Date** | Date on which the LoC ceases to be valid. | 2025-12-31 | `ktddecv:expiryDate` |
| **Place of Expiry** | Location where credit expires. | Tokyo, Japan | `ktddecv:placeOfExpiry` |
| **Presentation Period (days)** | Number of days allowed for document presentation. | 21 | `ktddecv:presentationPeriodDays` |
| **Latest Presentation Date** | Latest date for presenting documents. | 2025-12-21 | `ktddecv:latestPresentationDate` |
| **Partial Shipments Allowed** | Indicates if partial shipments are accepted. | false | `ktddecv:partialShipmentAllowed` |
| **Transshipment Allowed** | Indicates if transshipment is accepted. | true | `ktddecv:transshipmentAllowed` |

---

## 👥 2. Parties Involved

| Property | Description | Example | KTDDE Reference |
|-----------|--------------|----------|----------------|
| **Applicant Party (Buyer)** | Party requesting issuance of the LoC. | Tokyo Builders Ltd. (JP) | `ktddecv:applicantParty` |
| **Beneficiary Party (Seller)** | Party in whose favour the LoC is issued. | FinnLam Oy (FI) | `ktddecv:beneficiaryParty` |
| **Issuing Bank** | Bank issuing the LoC. | Nordea Bank Finland Plc | `ktddecv:issuingBankParty` |
| **Advising / Confirming Bank** | Bank advising and confirming the LoC. | Mitsui Bank Ltd., Tokyo | `ktddecv:advisingBankParty` |
| **Reimbursing Bank** | Bank reimbursing the paying bank. | Nordea Bank Finland Plc | `ktddecv:reimbursingBankParty` |
| **Available With (Bank)** | Bank where LoC is available for drawing. | Mitsui Bank Ltd. | `ktddecv:availableWithParty` |
| **Drawee (Paying Bank)** | Party authorized to make payment. | Mitsui Bank Ltd., Tokyo | `ktddecv:draweeParty` |

---

## 🚢 3. Goods and Shipment

| Property | Description | Example | KTDDE Reference |
|-----------|--------------|----------|----------------|
| **Goods Description** | Description of goods financed under the LoC. | Glued laminated timber beams, spruce, planed | `ktddecv:goodsDescription` |
| **Quantity** | Quantity of goods covered. | 12 m³ | `ktddecv:quantity` |
| **Net Weight** | Net weight of goods. | 9600 kg | `ktddecv:netWeightMeasure` |
| **HS Classification Code** | Harmonized System (HS) code. | HS 4418.99 | `ktddecv:classificationCode` |
| **Port of Loading** | Port where goods are loaded. | FIHEL (Helsinki) | `ktddecv:placeOfLoading` |
| **Port of Discharge** | Port where goods are unloaded. | JPTYO (Tokyo) | `ktddecv:placeOfDischarge` |
| **Incoterm** | Delivery terms defining risk and cost division. | CIF | `ktddecv:incotermsCode` |
| **Applicable Rules** | Regulatory framework applied. | UCP 600 (ICC) | `ktddecv:applicableRules` |
| **Delivery Period** | Time frame for shipment delivery. | 2025-10-15 → 2025-11-15 | `ktddecv:hasDeliveryPeriod` |

---

## 💶 4. Financial and Credit Terms

| Property | Description | Example | KTDDE Reference |
|-----------|--------------|----------|----------------|
| **Credit Amount** | Maximum amount under the LoC. | EUR 250 000 | `ktddecv:maximumCreditAmount` |
| **Credit Tolerance** | Permissible tolerance in amount. | 10% | `ktddecv:creditAmountTolerancePercentage` |
| **Tenor** | Payment timing (sight/deferred). | AT SIGHT | `ktddecv:tenor` |
| **Maturity Date** | Expected payment date. | 2025-12-21 | `ktddecv:maturityDate` |
| **Charges Borne By** | Party responsible for charges. | Applicant | `ktddecv:charges` |
| **Freight Charge** | Shipping-related cost. | EUR 4 200 | `ktddecv:allowanceChargeReasonCode (FREIGHT)` |
| **Insurance Charge** | Insurance cost included in CIF. | EUR 900 | `ktddecv:allowanceChargeReasonCode (INSURANCE)` |
| **Bank Charges** | Financial service fee. | EUR 350 | `ktddecv:allowanceChargeReasonCode (BANK_CHARGES)` |

---

## 📑 5. Required Documents

| Property | Description | Example | KTDDE Reference |
|-----------|--------------|----------|----------------|
| **Commercial Invoice** | Evidence of sale and value. | 1 copy | `ktddecv:requiresDocument (COMMERCIAL_INVOICE)` |
| **Packing List** | Lists package contents. | 1 copy | `ktddecv:requiresDocument (PACKING_LIST)` |
| **Certificate of Origin** | Certifies Finnish origin. | 1 copy | `ktddecv:requiresDocument (CERTIFICATE_OF_ORIGIN)` |
| **Insurance Policy** | Proof of insurance coverage. | 1 copy | `ktddecv:requiresDocument (INSURANCE_POLICY)` |
| **Transport Document** | Bill of Lading or Sea Waybill. | 1 copy | `ktddecv:requiresDocument (TRANSPORT_DOCUMENT)` |

---

## 💡 6. Example JSON-LD Instance

*(Full version using almost all properties from the SHACL and OWL)*  

```json
(see extended JSON-LD provided in accompanying documentation)
```

---

## 🧩 7. Technical Appendix — SHACL → KTDDE OWL Mapping

This appendix aligns each SHACL property path with its corresponding ontology class or datatype in **KTDDE OWL v0.0.4**.

| Label | KTDDE Property | Class / Datatype | Example |
|--------|----------------|------------------|----------|
| Document Identifier | `ktddecv:creditIdentifier` | xsd:string | LC-2025-000123 |
| Documentary Credit Type | `ktddecv:documentaryCreditTypeCode` | skos:Concept | IRREVOCABLE |
| Applicant Party | `ktddecv:applicantParty` | ktddecv:Party | Tokyo Builders Ltd. |
| Beneficiary Party | `ktddecv:beneficiaryParty` | ktddecv:Party | FinnLam Oy |
| Issuing Bank | `ktddecv:issuingBankParty` | ktddecv:FinancialInstitution | Nordea Bank |
| Advising Bank | `ktddecv:advisingBankParty` | ktddecv:FinancialInstitution | Mitsui Bank |
| Port of Loading | `ktddecv:placeOfLoading` | skos:Concept | FIHEL |
| Port of Discharge | `ktddecv:placeOfDischarge` | skos:Concept | JPTYO |
| Credit Amount | `ktddecv:maximumCreditAmount` | ktddecv:MonetaryAmount | EUR 250 000 |
| Incoterm | `ktddecv:incotermsCode` | skos:Concept | CIF |
| Applicable Rules | `ktddecv:applicableRules` | xsd:string | UCP 600 |
| Presentation Period | `ktddecv:presentationPeriodDays` | xsd:integer | 21 |
| Latest Presentation Date | `ktddecv:latestPresentationDate` | xsd:date | 2025-12-21 |
| Delivery Period | `ktddecv:hasDeliveryPeriod` | ktddecv:Period | 2025-10-15 → 2025-11-15 |
| Freight / Insurance Charges | `ktddecv:allowanceChargeReasonCode` | skos:Concept | FREIGHT, INSURANCE |
| Bank Charges | `ktddecv:allowanceChargeReasonCode` | skos:Concept | BANK_CHARGES |

---

**© 2025 KTDDE Semantic Group — WE BUILD LSP / EU Business Wallet Initiative**
