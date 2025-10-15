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

```json
{
  "@context": {
    "ktddecv": "https://iri.suomi.fi/model/ktddecv/0.0.4/",
    "skos": "http://www.w3.org/2004/02/skos/core#"
  },
  "type": ["VerifiableCredential", "ktddecv:DocumentaryCredit"],
  "id": "urn:uuid:LC-2025-000123",
  "issuer": "https://nordea.fi/organization/issuer",
  "issuanceDate": "2025-09-30",
  "credentialSubject": {
    "ktddecv:creditIdentifier": "LC-2025-000123",
    "ktddecv:documentDate": "2025-09-30",
    "ktddecv:expiryDate": "2025-12-31",
    "ktddecv:latestShipmentDate": "2025-11-15",
    "ktddecv:documentaryCreditTypeCode": "IRREVOCABLE",
    "ktddecv:confirmationInstructionCode": "CONFIRM",
    "ktddecv:confirmationAddedDate": "2025-09-30",
    "ktddecv:partialShipmentAllowed": false,
    "ktddecv:transshipmentAllowed": true,
    "ktddecv:presentationPeriodDays": 21,
    "ktddecv:hasPresentationPeriod": {
      "ktddecv:startDate": "2025-09-30",
      "ktddecv:endDate": "2025-12-21"
    },
    "ktddecv:latestPresentationDate": "2025-12-21",
    "ktddecv:placeOfExpiry": {"ktddecv:name": "Tokyo, Japan", "ktddecv:identifier": "JPTYO"},
    "ktddecv:placeOfPresentation": {"ktddecv:name": "Mitsui Bank Ltd., Tokyo", "ktddecv:identifier": "JP-TOKYO-MITSUI-MARUNOUCHI"},
    "ktddecv:applicantParty": {
      "ktddecv:name": "Tokyo Builders Ltd.",
      "ktddecv:partyAddress": {
        "ktddecv:streetName": "Marunouchi 2-17-1",
        "ktddecv:cityName": "Chiyoda-ku",
        "ktddecv:postalZone": "100-0005",
        "ktddecv:countryCode": "JP"
      },
      "ktddecv:partyIdentifier": [
        {"ktddecv:schemeName": "EUID", "ktddecv:identifierValue": "JP-TBLDRS-2025-0001"},
        {"ktddecv:schemeName": "LEI",  "ktddecv:identifierValue": "5493001KJTIIGC8Y1R12"}
      ]
    },
    "ktddecv:beneficiaryParty": {
      "ktddecv:name": "FinnLam Oy",
      "ktddecv:partyAddress": {
        "ktddecv:streetName": "Puusepänkatu 12",
        "ktddecv:cityName": "Jyväskylä",
        "ktddecv:postalZone": "40520",
        "ktddecv:countryCode": "FI"
      },
      "ktddecv:partyIdentifier": [
        {"ktddecv:schemeName": "EUID", "ktddecv:identifierValue": "FI-1234567-8"},
        {"ktddecv:schemeName": "LEI",  "ktddecv:identifierValue": "743700T6Y2Q7Z5Q9QZ11"}
      ]
    },
    "ktddecv:issuingBankParty": {"ktddecv:name": "Nordea Bank Finland Plc", "ktddecv:partyIdentifier": [{"ktddecv:schemeName": "BIC", "ktddecv:identifierValue": "NDEAFIHH"}]},
    "ktddecv:advisingBankParty": {"ktddecv:name": "Mitsui Bank Ltd., Tokyo", "ktddecv:partyIdentifier": [{"ktddecv:schemeName": "BIC", "ktddecv:identifierValue": "MITSJPJT"}]},
    "ktddecv:confirmingParty": {"ktddecv:name": "Mitsui Bank Ltd., Tokyo"},
    "ktddecv:requestedConfirmationParty": {"ktddecv:name": "Mitsui Bank Ltd., Tokyo"},
    "ktddecv:reimbursingBankParty": {"ktddecv:name": "Nordea Bank Finland Plc"},
    "ktddecv:adviseThroughBankParty": {"ktddecv:name": "Mitsui Bank Ltd., Tokyo"},
    "ktddecv:applicantBankParty": {"ktddecv:name": "Mitsui Bank Ltd., Tokyo"},

    "ktddecv:hasCreditAvailability": {
      "ktddecv:tenor": "AT SIGHT",
      "ktddecv:maturityDate": "2025-12-21",
      "ktddecv:draweeParty": {"ktddecv:name": "Mitsui Bank Ltd., Tokyo"},
      "ktddecv:availableWithParty": {"ktddecv:name": "Mitsui Bank Ltd., Tokyo"},
      "ktddecv:availableAtPlace": {"ktddecv:name": "Tokyo, Japan", "ktddecv:identifier": "JPTYO"},
      "ktddecv:hasAmount": {"ktddecv:value": 250000, "ktddecv:currencyCode": "EUR"}
    },

    "ktddecv:maximumCreditAmount": {"ktddecv:value": 250000, "ktddecv:currencyCode": "EUR"},
    "ktddecv:creditAmountTolerancePercentage": 10.0,

    "ktddecv:hasPaymentTerms": {
      "ktddecv:paymentTermCode": "LC",
      "ktddecv:tenor": "AT SIGHT",
      "ktddecv:tenorPeriod": {"ktddecv:startDate": "2025-09-30", "ktddecv:endDate": "2025-12-21"},
      "ktddecv:hasPaymentScheduleLine": [
        {
          "ktddecv:hasAmount": {"ktddecv:value": 250000, "ktddecv:currencyCode": "EUR"},
          "ktddecv:paymentDueDate": "2025-12-21",
          "ktddecv:payeeParty": {"ktddecv:name": "FinnLam Oy"},
          "ktddecv:tenor": "AT SIGHT"
        }
      ]
    },

    "ktddecv:hasPaymentLine": [
      {
        "ktddecv:hasAmount": {"ktddecv:value": 250000, "ktddecv:currencyCode": "EUR"},
        "ktddecv:paymentSettlementMethod": "BANK_PAYMENT",
        "ktddecv:paymentDueDate": "2025-12-21",
        "ktddecv:payeeParty": {"ktddecv:name": "FinnLam Oy"},
        "ktddecv:tenor": "AT SIGHT"
      }
    ],

    "ktddecv:requiresDocument": [
      {"ktddecv:documentTypeCode": "COMMERCIAL_INVOICE", "ktddecv:numberOfCopies": 1},
      {"ktddecv:documentTypeCode": "PACKING_LIST", "ktddecv:numberOfCopies": 1},
      {"ktddecv:documentTypeCode": "CERTIFICATE_OF_ORIGIN", "ktddecv:numberOfCopies": 1},
      {"ktddecv:documentTypeCode": "INSURANCE_POLICY", "ktddecv:numberOfCopies": 1},
      {"ktddecv:documentTypeCode": "TRANSPORT_DOCUMENT", "ktddecv:numberOfCopies": 1}
    ],

    "ktddecv:hasShipment": {
      "ktddecv:sellerParty": {"ktddecv:name": "FinnLam Oy"},
      "ktddecv:buyerParty": {"ktddecv:name": "Tokyo Builders Ltd."},
      "ktddecv:applicableRules": {"ktddecv:ruleSetName": "UCP 600 (ICC)"},
      "ktddecv:incotermsCode": "CIF",
      "ktddecv:placeOfLoading": {"ktddecv:name": "Port of Helsinki", "ktddecv:identifier": "FIHEL"},
      "ktddecv:placeOfDischarge": {"ktddecv:name": "Port of Tokyo", "ktddecv:identifier": "JPTYO"},
      "ktddecv:hasDeliveryPeriod": {"ktddecv:startDate": "2025-10-15", "ktddecv:endDate": "2025-11-15"},
      "ktddecv:includesAllowanceCharge": [
        {"ktddecv:allowanceChargeReasonCode": "FREIGHT", "ktddecv:chargeIndicator": true,
         "ktddecv:amount": {"ktddecv:value": 4200, "ktddecv:currencyCode": "EUR"}},
        {"ktddecv:allowanceChargeReasonCode": "INSURANCE", "ktddecv:chargeIndicator": true,
         "ktddecv:amount": {"ktddecv:value": 900, "ktddecv:currencyCode": "EUR"}}
      ],
      "ktddecv:hasGoodsItem": [
        {
          "ktddecv:goodsDescription": "Glued laminated timber beams, spruce, planed",
          "ktddecv:quantity": "12 m³",
          "ktddecv:netWeightMeasure": "9600 kg",
          "ktddecv:classificationCode": "HS 4418.99"
        }
      ]
    },

    "ktddecv:coversAdditionalCharge": [
      {"ktddecv:allowanceChargeReasonCode": "BANK_CHARGES", "ktddecv:chargeIndicator": true,
       "ktddecv:amount": {"ktddecv:value": 350, "ktddecv:currencyCode": "EUR"}}
    ],

    "ktddecv:AdditionalConditionsText": "All documents must state LC number LC-2025-000123 and show Consignee: Tokyo Builders Ltd.",
    "ktddecv:instructionToBank": {"ktddecv:instructionText": "Advise by authenticated SWIFT; release documents against payment at sight."},

    "ktddecv:relatedPurchaseOrder": "PO-2025-00077",
    "ktddecv:relatedInvoice": "INV-2025-00077",
    "ktddecv:relatedTransportDocument": "SWB-2025-00231",
    "ktddecv:certificateOfOriginReference": "CO-FIN-2025-A321"
  }
}
```
