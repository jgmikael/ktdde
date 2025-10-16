# Letter of Credit Data Elements Mapping to KTDDE SHACL Shape (Updated)

This document compares the **ICC original Letter of Credit data elements** with the **current SHACL Shape** for the KTDDE `LetterOfCredit` trade document.

Mappings include expert‑verified alignments for ‘Date of Issue’ and ‘Drafts at…’ elements.

---

## Form of Documentary

**Original Description:** LC type enum: irrevocable, transferabl, standby

**Mapping Status:** ❌ Not yet mapped to SHACL Shape

_This data element is not currently represented in the uploaded SHACL Shape. It may require a new property or linkage to related message or code list._


---

## Documentary Credit Number

**Original Description:** Issuing bank given id for the LC

**Mapping Status:** ✅ Mapped to SHACL Shape

- **SHACL Shape:** `documentaryCreditTypeCode`

- **KTDDE Property:** <https://iri.suomi.fi/model/ktddecv/0.0.4/documentaryCreditTypeCode>


---

## Reference to Pre-Advice

**Original Description:** Link (by an Pre-dvice Id) to possible Pre-advice

**Mapping Status:** ✅ Mapped to SHACL Shape

- **SHACL Shape:** `referencesPreAdvice`

- **KTDDE Property:** <https://iri.suomi.fi/model/ktddecv/0.0.4/referencesPreAdvice>


---

## Date of Issue

**Original Description:** ISO DATE / ISO 8601

**Mapping Status:** ✅ Mapped to SHACL Shape

- **SHACL Shape:** `DocumentaryCredit_issueDate`

- **KTDDE Property:** <https://iri.suomi.fi/model/ktddecv/0.0.4/issueDate>


---

## Applicable Rules

**Original Description:** enum with values like UCP, eUCP etc.

**Mapping Status:** ✅ Mapped to SHACL Shape

- **SHACL Shape:** `applicableRules`

- **KTDDE Property:** <https://iri.suomi.fi/model/ktddecv/0.0.4/applicableRules>


---

## Date and Place of Expiry

**Original Description:** ISO DATE / ISO 8601

**Mapping Status:** ✅ Mapped to SHACL Shape

- **SHACL Shape:** `placeOfExpiry`

- **KTDDE Property:** <https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfExpiry>


---

## Applicant Bank

**Original Description:** Party / Agent

**Mapping Status:** ✅ Mapped to SHACL Shape

- **SHACL Shape:** `applicantBankParty`

- **KTDDE Property:** <https://iri.suomi.fi/model/ktddecv/0.0.4/applicantBankParty>


---

## Applicant

**Original Description:** Party / Agent

**Mapping Status:** ✅ Mapped to SHACL Shape

- **SHACL Shape:** `applicantParty`

- **KTDDE Property:** <https://iri.suomi.fi/model/ktddecv/0.0.4/applicantParty>


---

## Beneficiary

**Original Description:** Party / Agent

**Mapping Status:** ✅ Mapped to SHACL Shape

- **SHACL Shape:** `beneficiaryParty`

- **KTDDE Property:** <https://iri.suomi.fi/model/ktddecv/0.0.4/beneficiaryParty>


---

## Currency Code, Amount

**Original Description:** ISO 20022 amount definition

**Mapping Status:** ✅ Mapped to SHACL Shape

- **SHACL Shape:** `currencyCode`

- **KTDDE Property:** <https://iri.suomi.fi/model/ktddecv/0.0.4/currencyCode>


---

## Percentage Credit Amount

**Original Description:** Percentage tolerance of the LC compared to the contract value

**Mapping Status:** ✅ Mapped to SHACL Shape

- **SHACL Shape:** `perUnitAmount`

- **KTDDE Property:** <https://iri.suomi.fi/model/ktddecv/0.0.4/perUnitAmount>


---

## Maximum Credit Amount

**Original Description:** ISO 20022 amount definition

**Mapping Status:** ✅ Mapped to SHACL Shape

- **SHACL Shape:** `maximumCreditAmount`

- **KTDDE Property:** <https://iri.suomi.fi/model/ktddecv/0.0.4/maximumCreditAmount>


---

## Additional Amounts Covered

**Original Description:** enum of additional amounts: interest, freight, insurance etc

**Mapping Status:** ✅ Mapped to SHACL Shape

- **SHACL Shape:** `additionalAmountsCovered`

- **KTDDE Property:** <https://iri.suomi.fi/model/ktddecv/0.0.4/additionalAmountsCovered>


---

## Available With ...

**Original Description:** combo of party details and UN/LOCODEs

**Mapping Status:** ✅ Mapped to SHACL Shape

- **SHACL Shape:** `availableWithParty`

- **KTDDE Property:** <https://iri.suomi.fi/model/ktddecv/0.0.4/availableWithParty>


---

## Drafts at ...

**Original Description:** combo of party details and UN/LOCODEs

**Mapping Status:** ❌ Not yet mapped to SHACL Shape

_This data element is not currently represented in the uploaded SHACL Shape. It may require a new property or linkage to related message or code list._


---

## Drawee

**Original Description:** Party / Agent

**Mapping Status:** ✅ Mapped to SHACL Shape

- **SHACL Shape:** `draweeParty`

- **KTDDE Property:** <https://iri.suomi.fi/model/ktddecv/0.0.4/draweeParty>


---

## Mixed Payment Details

**Original Description:** Should be split to iterative payment details per party (amount, date, party)

**Mapping Status:** ❌ Not yet mapped to SHACL Shape

_This data element is not currently represented in the uploaded SHACL Shape. It may require a new property or linkage to related message or code list._


---

## Deferred Payment Details

**Original Description:** ISO DATE / ISO 8601 for the deferred payment date

**Mapping Status:** ✅ Mapped to SHACL Shape

- **SHACL Shape:** `deferredPaymentDate`

- **KTDDE Property:** <https://iri.suomi.fi/model/ktddecv/0.0.4/deferredPaymentDate>


---

## Partial Shipments

**Original Description:** should be split to delivery milestones with underlying details

**Mapping Status:** ✅ Mapped to SHACL Shape

- **SHACL Shape:** `partialShipmentAllowed`

- **KTDDE Property:** <https://iri.suomi.fi/model/ktddecv/0.0.4/partialShipmentAllowed>


---

## Transshipment

**Original Description:** boolean on if partial / transshipments are allowed

**Mapping Status:** ✅ Mapped to SHACL Shape

- **SHACL Shape:** `hasShipment`

- **KTDDE Property:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasShipment>


---

## Place of Taking in Charge/Dispatch from .../Place of receipt

**Original Description:** UN/LOCODE

**Mapping Status:** ❌ Not yet mapped to SHACL Shape

_This data element is not currently represented in the uploaded SHACL Shape. It may require a new property or linkage to related message or code list._


---

## Port of Loading/Airport of Departure

**Original Description:** UN/LOCODE

**Mapping Status:** ❌ Not yet mapped to SHACL Shape

_This data element is not currently represented in the uploaded SHACL Shape. It may require a new property or linkage to related message or code list._


---

## Port of Discharge/Airport of Destination

**Original Description:** UN/LOCODE

**Mapping Status:** ✅ Mapped to SHACL Shape

- **SHACL Shape:** `portOfDischargeUNLocode`

- **KTDDE Property:** <https://iri.suomi.fi/model/ktddecv/0.0.4/portOfDischargeUNLocode>


---

## Place of Final Destination/For Transportation to .../Place of Delivery

**Original Description:** UN/LOCODE

**Mapping Status:** ❌ Not yet mapped to SHACL Shape

_This data element is not currently represented in the uploaded SHACL Shape. It may require a new property or linkage to related message or code list._


---

## Latest Date of Shipment

**Original Description:** ISO DATE / ISO 8601

**Mapping Status:** ✅ Mapped to SHACL Shape

- **SHACL Shape:** `latestShipmentDate`

- **KTDDE Property:** <https://iri.suomi.fi/model/ktddecv/0.0.4/latestShipmentDate>


---

## Shipment Period

**Original Description:** ISO DATE / ISO 8601 wit from and to dates

**Mapping Status:** ✅ Mapped to SHACL Shape

- **SHACL Shape:** `hasShipmentPeriod`

- **KTDDE Property:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasShipmentPeriod>


---

## Description of Goods/Services

**Original Description:** should be described on iterative HS-code list with possible additional free text per line

**Mapping Status:** ✅ Mapped to SHACL Shape

- **SHACL Shape:** `descriptionOfGoodsText`

- **KTDDE Property:** <https://iri.suomi.fi/model/ktddecv/0.0.4/descriptionOfGoodsText>


---

## Documents Required

**Original Description:** should be described as iterative list with document type codes, related file location, format etc.

**Mapping Status:** ✅ Mapped to SHACL Shape

- **SHACL Shape:** `documentType`

- **KTDDE Property:** <https://iri.suomi.fi/model/ktddecv/0.0.4/documentType>


---

## Additional Conditions

**Original Description:** Possible free text, should be avoided and agreed in all other fields

**Mapping Status:** ✅ Mapped to SHACL Shape

- **SHACL Shape:** `AdditionalConditionsText`

- **KTDDE Property:** <https://iri.suomi.fi/model/ktddecv/0.0.4/additionalConditionsText>


---

## Charges

**Original Description:** enum for various charges reason and related amount and party

**Mapping Status:** ❌ Not yet mapped to SHACL Shape

_This data element is not currently represented in the uploaded SHACL Shape. It may require a new property or linkage to related message or code list._


---

## Period for Presentation

**Original Description:** ISO DATE / ISO 8601 wit from and to dates

**Mapping Status:** ✅ Mapped to SHACL Shape

- **SHACL Shape:** `placeOfPresentation`

- **KTDDE Property:** <https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfPresentation>


---

## Confirmation Instructions

**Original Description:** combo of enum of conf codes, party and date

**Mapping Status:** ✅ Mapped to SHACL Shape

- **SHACL Shape:** `confirmationInstructionCode`

- **KTDDE Property:** <https://iri.suomi.fi/model/ktddecv/0.0.4/confirmationInstructionCode>


---

## Reimbursing Bank

**Original Description:** Party / Agent

**Mapping Status:** ✅ Mapped to SHACL Shape

- **SHACL Shape:** `reimbursingBankParty`

- **KTDDE Property:** <https://iri.suomi.fi/model/ktddecv/0.0.4/reimbursingBankParty>


---

## Instructions to the Paying/Accepting/Negotiating Bank

**Original Description:** Free text bu defined as a message structure: which party instructs other party with a message

**Mapping Status:** ❌ Not yet mapped to SHACL Shape

_This data element is not currently represented in the uploaded SHACL Shape. It may require a new property or linkage to related message or code list._


---

## 'Advise Through' Bank

**Original Description:** As Instructions -> message structure

**Mapping Status:** ✅ Mapped to SHACL Shape

- **SHACL Shape:** `adviseThroughBankParty`

- **KTDDE Property:** <https://iri.suomi.fi/model/ktddecv/0.0.4/adviseThroughBankParty>


---

## Sender to Receiver information

**Original Description:** As Instructions -> message structure

**Mapping Status:** ❌ Not yet mapped to SHACL Shape

_This data element is not currently represented in the uploaded SHACL Shape. It may require a new property or linkage to related message or code list._


---

## Summary

- **Total Elements:** 36

- **Mapped:** 27

- **Not Mapped:** 9
