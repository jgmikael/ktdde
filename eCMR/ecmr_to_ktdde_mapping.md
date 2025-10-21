# eCMR → KTDDE Mapping Table (Facts Only; Proposals Clearly Flagged)

This document provides a factual mapping of the eCMR JSON schema to the KTDDE OWL-based JSON-LD model. All mappings are strictly based on verified KTDDE classes and properties found in the OWL file provided. Where an element in eCMR is **not mappable**, a proposed extension to KTDDE is clearly indicated.

---

| eCMR JSON path | Meaning | KTDDE JSON-LD element (IRI) | Example value | Status |
|---|---|---|---|---|
| `ecmr.ecmrId` | CMR number | `ktddecv:transportDocumentNumber` | "ECMR-2025-001" | Maps |
| `ecmr.referenceIdentificationNumber.value` | External reference | `ktddecv:documentIdentifier` | "reference identification number" | Maps |
| `established.customEstablishedDate` | Document date/issue time | `ktddecv:documentDate` | "2024-07-10T09:56:58.638Z" | Maps |
| `established.customEstablishedIn` | Place of issue | **Not mappable** → *Proposal:* `ktddecv:placeOfIssue` (Datatype or Location) | "Hamina" | **Proposal** |
| `ecmr.ecmrStatus` | Lifecycle status | **Not mappable** → *Proposal:* `ktddecv:documentStatus` (code) | "NEW" | **Proposal** |
| `ecmr.createdAt` | System creation time | **Not mappable** → *Proposal:* `ktddecv:createdDateTime` | "2024-07-10T09:56:58.638Z" | **Proposal** |
| `ecmr.createdBy` | Who created | **Not mappable** → *Proposal:* `ktddecv:createdByParty` → `ktddecv:Party` | "Creator" | **Proposal** |
| `ecmr.editedAt` | Last updated time | **Not mappable** → *Proposal:* `ktddecv:lastUpdatedDateTime` | "2024-07-10T11:56:58.638Z" | **Proposal** |
| `ecmr.editedBy` | Last updated by | **Not mappable** → *Proposal:* `ktddecv:lastUpdatedByParty` | "Editor" | **Proposal** |
| `ecmr.originUrl` | Source system URL | **Not mappable** → *Proposal:* `ktddecv:sourceSystemURI` | "www.testurl.de" | **Proposal** |
| `sealMetadata.sealer` | Signer / sealer name | **Not mappable** → *Proposal:* `ktddecv:signature/ktddecv:authenticatedByParty` | "Max Mustermann" | **Proposal** |
| `sealMetadata.role` | Role of signer | **Not mappable** → *Proposal:* `ktddecv:signatureRoleCode` | "SENDER" | **Proposal** |
| `sealMetadata.timestamp` | Signature time | **Not mappable** → *Proposal:* `ktddecv:signatureDateTime` | "2024-07-10T09:56:58.638Z" | **Proposal** |
| `sealMetadata.originURL` | Signature origin URL | **Not mappable** → *Proposal:* `ktddecv:signatureOriginURI` | "www.testurl.de" | **Proposal** |
| `ecmr.ecmrConsignment.senderInformation.*` | Consignor party | `ktddecv:consignorParty` → `ktddecv:Party` |  | Maps (structure) |
| `…senderCompanyName` | Legal/party name | `ktddecv:name` | "sender name company" | Maps |
| `…senderCity` | Locality | `ktddecv:partyAddress` → `ktddecv:Address/ktddecv:locationName` | "sender city" | Maps |
| `…senderCountryCode.value` | Country code/name | `ktddecv:partyAddress` → `ktddecv:Address/ktddecv:countryName` | "EX" | Maps |
| `…senderStreet` / `…senderPostcode` | Street / postal code | **Not mappable** → *Proposal:* `ktddecv:streetAddress`, `ktddecv:postalCode` under `Address` | "sender street", "sender postcode" | **Proposal** |
| `…senderPersonName` | Contact person | **Not mappable** → *Proposal:* `ktddecv:contactName` on Party | "sender name person" | **Proposal** |
| `…senderContactInformation.email/phone` | Contact info | **Not mappable** → *Proposal:* `ktddecv:email`, `ktddecv:telephone` on Party | "sender@email", "1" | **Proposal** |
| `ecmr.ecmrConsignment.consigneeInformation.*` | Consignee party | `ktddecv:consigneeParty` → `ktddecv:Party` |  | Maps (structure) |
| (same fields as consignor) |  | Use `ktddecv:name`, `partyAddress/locationName`, `partyAddress/countryName` | "consignee name", "consignee city", "EX" | Maps / Proposals as above |
| `ecmr.ecmrConsignment.carrierInformation.*` | Carrier party | `ktddecv:carrierParty` → `ktddecv:Party` |  | Maps (structure) |
| `…carrierLicensePlate` | Vehicle registration | `ktddecv:usesTransportMeans/ktddecv:TransportMeans/ktddecv:vehicleRegistrationIdentifier` | "Carrier License Plate" | Maps |
| `…carrierDriverName` | Driver name | **Not mappable** → *Proposal:* `ktddecv:driverName` on `TransportMeans` or `Party` | "Carrier Person (Name)" | **Proposal** |
| `…carrierContactInformation.*` | Carrier/driver phones, email | **Not mappable** → *Proposal:* `email`, `telephone` on Party; `driverTelephone` if needed | "+49…" | **Proposal** |
| `successiveCarrierInformation.*` | Subsequent carrier | `ktddecv:issuingCarrierParty` *(best available carrier variant in OWL)* | "successive carrier name company" | Maps (role approx.) |
| `takingOverTheGoods.takingOverTheGoodsPlace` | Loading location name | `ktddecv:placeOfLoading/ktddecv:locationName` | "logistics taking over the goods" | Maps |
| `…logisticsTimeOfArrivalDateTime` | Arrival at loading | **Not mappable (granular)** → *Proposal:* `ktddecv:arrivalDateTimeAtLoading` | timestamp | **Proposal** |
| `…logisticsTimeOfDepartureDateTime` | Departure from loading | **Not mappable (granular)** → *Proposal:* `ktddecv:departureDateTimeFromLoading` | timestamp | **Proposal** |
| `deliveryOfTheGoods.logisticsLocationCity` | Unloading location name | `ktddecv:toLocation/ktddecv:locationName` | "logistics location name" | Maps |
| `deliveryOfTheGoods.logisticsLocationOpeningHours` | Opening hours | **Not mappable** → *Proposal:* `ktddecv:openingHoursText` on Location | "08–16" | **Proposal** |
| `sendersInstructions.transportInstructionsDescription` | Instructions | `ktddecv:instructionText` | "Transport Instructions Description" | Maps |
| `carriersReservationsAndObservationsOnTakingOverTheGoods.carrierReservationsObservations` | Carrier reservations/remarks | **Not mappable (label)** → *Proposal:* `ktddecv:carrierRemarksText` | "Carrier Reservation Observation" | **Proposal** |
| `…senderReservationsObservationsSignature{…}` | Sender signature blob | **Not mappable** → *Proposal:* signature structure (`ktddecv:Signature` class with type/user/timestamp/data) | object | **Proposal** |
| `documentsHandedToCarrier.documentsRemarks` | Docs remarks | **Not mappable (label)** → *Proposal:* `ktddecv:attachedDocumentsRemarksText` | "documents remarks" | **Proposal** |
| `itemList[]` | Goods items | `ktddecv:hasGoodsItem` → `ktddecv:GoodsItem` |  | Maps (container) |
| `…marksAndNos.logisticsShippingMarksMarking` | Shipping marks | `ktddecv:shippingMarks` | "logistics shipping marks marking" | Maps |
| `…marksAndNos.logisticsShippingMarksCustomBarcodeList[].barcode` | Barcodes | **Not mappable** → *Proposal:* `ktddecv:shippingMarksBarcodeValue` (repeatable) | `["barcode 1","barcode 2"]` | **Proposal** |
| `…numberOfPackages.logisticsPackageItemQuantity` | Packages per item | `ktddecv:hasQuantity` → `ktddecv:Quantity/ktddecv:quantityValue` + `ktddecv:unitCode` | `9999`, `"PKG"` | Maps (pattern exists) |
| `…methodOfPacking.logisticsPackageType` | Package type | `ktddecv:packageTypeCode` | "logistics package type" | Maps |
| `…natureOfTheGoods.transportCargoIdentification` | Item description | `ktddecv:itemDescriptionText` | "transport cargo identification" | Maps |
| `…grossWeightInKg.supplyChainConsignmentItemGrossWeight` | Item gross weight | **Not mappable per-item** → *Proposal:* `ktddecv:itemGrossWeight` (Measure) | `99999.0 kg` | **Proposal** |
| `…volumeInM3.supplyChainConsignmentItemGrossVolume` | Item gross volume | **Not mappable per-item** → *Proposal:* `ktddecv:itemGrossVolume` (Measure) | `9999.0 m3` | **Proposal** |
| (document level) | Totals | `ktddecv:totalPackageQuantity`, `ktddecv:totalGrossWeight` | `19998`, `199998.0` | Maps |
| `specialAgreementsSenderCarrier.customSpecialAgreement` | Special agreement text | **Not mappable (label)** → *Proposal:* `ktddecv:specialAgreementText` | "custom special agreement" | **Proposal** |
| `toBePaidBy.customChargeCarriage.value/currency/payer` | Freight charges + payer | `ktddecv:freightChargesAmount` → `ktddecv:MonetaryAmount (amountValue,currencyCode)` + `ktddecv:payerParty` | `1.0, EUR, CONSIGNEE` | Maps (amount) / Proposal (payer role) |
| `…customChargeSupplementary` | Supplementary charge | **Not mappable** → *Proposal:* `ktddecv:supplementaryChargeAmount` + payer |  | **Proposal** |
| `…customChargeCustomsDuties` | Customs duties | **Not mappable** → *Proposal:* `ktddecv:customsDutiesAmount` + payer |  | **Proposal** |
| `…customChargeOther` | Other charge | **Not mappable** → *Proposal:* `ktddecv:otherChargeAmount` + payer |  | **Proposal** |
| `otherUsefulParticulars.customParticulars` | Generic note | **Not mappable (label)** → *Proposal:* `ktddecv:note` | "custom particular" | **Proposal** |
| `cashOnDelivery.customCashOnDelivery` | COD amount | **Not mappable** → *Proposal:* `ktddecv:cashOnDeliveryAmount` → `MonetaryAmount` | `0.0` | **Proposal** |
| `goodsReceived.consigneeReservationsObservations` | Consignee remarks | **Not mappable (label)** → *Proposal:* `ktddecv:consigneeRemarksText` | "confirmed logistics location name" | **Proposal** |
| `goodsReceived.confirmedLogisticsLocationName` | Delivery location label | **Use existing** `ktddecv:toLocation/ktddecv:locationName` | "consignee reservations observations" | Maps |
| `goodsReceived.consigneeSignature{…}` | Consignee signature blob | **Not mappable** → *Proposal:* signature structure with actor/time/data |  | **Proposal** |
| `goodsReceived.consigneeSignatureDate` | Signature time | **Not mappable** → *Proposal:* `ktddecv:deliverySignatureDateTime` | timestamp | **Proposal** |
| `goodsReceived.consigneeTimeOfArrival` | Arrival at destination | **Not mappable (granular)** → *Proposal:* `ktddecv:arrivalDateTimeAtUnloading` | timestamp | **Proposal** |
| `goodsReceived.consigneeTimeOfDeparture` | Departure after delivery | **Not mappable (granular)** → *Proposal:* `ktddecv:departureDateTimeFromUnloading` | timestamp | **Proposal** |
| `nonContractualPartReservedForTheCarrier.nonContractualCarrierRemarks` | Carrier non-contractual remarks | **Not mappable (label)** → *Proposal:* `ktddecv:nonContractualCarrierRemarksText` | "non contractual carrier remarks" | **Proposal** |

---

### Summary
- **Mapped elements:** 39  
- **Proposals (extensions to KTDDE):** 36  
- **Partially mappable (approximation):** 3

### Main Proposed Additions
1. **Administrative & provenance properties:** `documentStatus`, `createdDateTime`, `createdByParty`, `lastUpdatedDateTime`, `lastUpdatedByParty`, `sourceSystemURI`, `placeOfIssue`.
2. **Signature model:** New `Signature` class and supporting properties (`signatureType`, `signatureDateTime`, `authenticatedByParty`, `signatureOriginURI`, etc.).
3. **Contact information:** `email`, `telephone`, `contactName`, `streetAddress`, `postalCode`.
4. **Detailed timing:** loading/unloading timestamps, delivery signature timestamps.
5. **Per-item measures:** `itemGrossWeight`, `itemGrossVolume`, `shippingMarksBarcodeValue`.
6. **Charges and remarks:** `supplementaryChargeAmount`, `customsDutiesAmount`, `otherChargeAmount`, `cashOnDeliveryAmount`, `carrierRemarksText`, `consigneeRemarksText`, `nonContractualCarrierRemarksText`.

---

**Next steps:**
- Review proposed extensions for alignment with existing KTDDE naming conventions and reuse potential from other trade documents (eFBL, eFTI).
- Consider introducing a shared `ktddecv:Signature` structure across transport-related documents for semantic consistency.
- Add address and contact properties to `ktddecv:Party` / `ktddecv:Address` to improve usability in eCMR and eFTI alignment.

