# eCMR → KTDDE Mapping (Inline List Version)

**Legend:** ✅ Maps • ⚠️ Proposal (not in OWL) • ⚙️ Approximation (closest existing)

This version avoids a wide table. Each eCMR JSON class/property is shown inline, followed by the mapped (or proposed) KTDDE OWL structure.

---

## Root document
- `ecmr.ecmrId` — CMR number → **KTDDE:** `TransportDocument.transportDocumentNumber` — ✅ Maps
- `ecmr.referenceIdentificationNumber.value` — External reference → **KTDDE:** `TransportDocument.documentIdentifier` — ✅ Maps
- `established.customEstablishedDate` — Document date/issue time → **KTDDE:** `TransportDocument.documentDate (xsd:dateTime)` — ✅ Maps
- `established.customEstablishedIn` — Place of issue → **KTDDE:** `TransportDocument.placeOfIssue` — ⚠️ Proposal
- `ecmr.ecmrStatus` — Lifecycle status (e.g., NEW) → **KTDDE:** `TransportDocument.documentStatus (code)` — ⚠️ Proposal
- `ecmr.createdAt` — System creation time → **KTDDE:** `TransportDocument.createdDateTime (xsd:dateTime)` — ⚠️ Proposal
- `ecmr.createdBy` — Creator (user/system) → **KTDDE:** `TransportDocument.createdByParty → Party` — ⚠️ Proposal
- `ecmr.editedAt` — Last updated time → **KTDDE:** `TransportDocument.lastUpdatedDateTime (xsd:dateTime)` — ⚠️ Proposal
- `ecmr.editedBy` — Last updated by → **KTDDE:** `TransportDocument.lastUpdatedByParty → Party` — ⚠️ Proposal
- `ecmr.originUrl` — Source system URL → **KTDDE:** `TransportDocument.sourceSystemURI (anyURI)` — ⚠️ Proposal

## Seal metadata (electronic signature/seal)
- `sealMetadata.sealer` — Sealer name → **KTDDE:** `TransportDocument.signature/authenticatedByParty → Party` — ⚠️ Proposal
- `sealMetadata.role` — Sealer role (SENDER) → **KTDDE:** `TransportDocument.signatureRoleCode (code)` — ⚠️ Proposal
- `sealMetadata.timestamp` — Seal timestamp → **KTDDE:** `TransportDocument.signatureDateTime (xsd:dateTime)` — ⚠️ Proposal
- `sealMetadata.originURL` — Origin URL → **KTDDE:** `TransportDocument.signatureOriginURI (anyURI)` — ⚠️ Proposal

## Consignment (parties)
### Consignor
- `ecmrConsignment.senderInformation` — Consignor container → **KTDDE:** `TransportDocument.consignorParty → Party` — ✅ Maps
  - `senderCompanyName` → **KTDDE:** `Party.name` — ✅ Maps
  - `senderPersonName` → **KTDDE:** `Party.contactName` — ⚠️ Proposal
  - `senderStreet` → **KTDDE:** `Address.streetAddress` — ⚠️ Proposal
  - `senderPostcode` → **KTDDE:** `Address.postalCode` — ⚠️ Proposal
  - `senderCity` → **KTDDE:** `Address.locationName` — ✅ Maps
  - `senderCountryCode.value` → **KTDDE:** `Address.countryName` — ✅ Maps
  - `senderContactInformation.email` → **KTDDE:** `Party.email` — ⚠️ Proposal
  - `senderContactInformation.phone` → **KTDDE:** `Party.telephone` — ⚠️ Proposal

### Consignee
- `ecmrConsignment.consigneeInformation` — Consignee container → **KTDDE:** `TransportDocument.consigneeParty → Party` — ✅ Maps
  - `consigneeCompanyName` → **KTDDE:** `Party.name` — ✅ Maps
  - `consigneePersonName` → **KTDDE:** `Party.contactName` — ⚠️ Proposal
  - `consigneeStreet` → **KTDDE:** `Address.streetAddress` — ⚠️ Proposal
  - `consigneePostcode` → **KTDDE:** `Address.postalCode` — ⚠️ Proposal
  - `consigneeCity` → **KTDDE:** `Address.locationName` — ✅ Maps
  - `consigneeCountryCode.value` → **KTDDE:** `Address.countryName` — ✅ Maps
  - `consigneeContactInformation.email` → **KTDDE:** `Party.email` — ⚠️ Proposal
  - `consigneeContactInformation.phone` → **KTDDE:** `Party.telephone` — ⚠️ Proposal

### Carrier (+ successive carrier)
- `ecmrConsignment.carrierInformation` — Carrier container → **KTDDE:** `TransportDocument.carrierParty → Party` — ✅ Maps
  - `carrierCompanyName` → **KTDDE:** `Party.name` — ✅ Maps
  - `carrierCity` → **KTDDE:** `Address.locationName` — ✅ Maps
  - `carrierCountryCode.value` → **KTDDE:** `Address.countryName` — ✅ Maps
  - `carrierLicensePlate` → **KTDDE:** `TransportMeans.vehicleRegistrationIdentifier` — ✅ Maps
  - `carrierDriverName` → **KTDDE:** `TransportMeans.driverName` — ⚠️ Proposal
  - `carrierContactInformation.email/driverPhone/carrierPhone` → **KTDDE:** `Party.email` / `Party.telephone` — ⚠️ Proposal

- `successiveCarrierInformation` — Successive carrier container → **KTDDE:** `TransportDocument.issuingCarrierParty → Party` — ⚙️ Approximation

## Locations & times
- `takingOverTheGoods.takingOverTheGoodsPlace` — Loading location (label) → **KTDDE:** `TransportDocument.placeOfLoading → Location.locationName` — ✅ Maps
- `takingOverTheGoods.logisticsTimeOfArrivalDateTime` — Arrival at loading → **KTDDE:** `TransportDocument.arrivalDateTimeAtLoading (xsd:dateTime)` — ⚠️ Proposal
- `takingOverTheGoods.logisticsTimeOfDepartureDateTime` — Departure from loading → **KTDDE:** `TransportDocument.departureDateTimeFromLoading (xsd:dateTime)` — ⚠️ Proposal
- `deliveryOfTheGoods.logisticsLocationCity` — Unloading location (label) → **KTDDE:** `TransportDocument.toLocation → Location.locationName` — ✅ Maps
- `deliveryOfTheGoods.logisticsLocationOpeningHours` — Opening hours → **KTDDE:** `Location.openingHoursText` — ⚠️ Proposal

## Instructions & remarks
- `sendersInstructions.transportInstructionsDescription` — Transport instructions → **KTDDE:** `TransportDocument.instructionText` — ✅ Maps
- `carriersReservationsAndObservationsOnTakingOverTheGoods.carrierReservationsObservations` — Carrier remarks at pickup → **KTDDE:** `TransportDocument.carrierRemarksText` — ⚠️ Proposal
- `documentsHandedToCarrier.documentsRemarks` — Remarks on handed docs → **KTDDE:** `TransportDocument.attachedDocumentsRemarksText` — ⚠️ Proposal

## Goods
- `itemList[]` — Goods items array → **KTDDE:** `TransportDocument.hasGoodsItem → GoodsItem` — ✅ Maps
  - `marksAndNos.logisticsShippingMarksMarking` → **KTDDE:** `GoodsItem.shippingMarks` — ✅ Maps
  - `marksAndNos.logisticsShippingMarksCustomBarcodeList[].barcode` → **KTDDE:** `GoodsItem.shippingMarksBarcodeValue` — ⚠️ Proposal
  - `numberOfPackages.logisticsPackageItemQuantity` → **KTDDE:** `GoodsItem.hasQuantity → Quantity.quantityValue` (+ `unitCode`) — ✅ Maps
  - `methodOfPacking.logisticsPackageType` → **KTDDE:** `GoodsItem.packageTypeCode` — ✅ Maps
  - `natureOfTheGoods.transportCargoIdentification` → **KTDDE:** `GoodsItem.itemDescriptionText` — ✅ Maps
  - `grossWeightInKg.supplyChainConsignmentItemGrossWeight` → **KTDDE:** `GoodsItem.itemGrossWeight (Measure)` — ⚠️ Proposal
  - `volumeInM3.supplyChainConsignmentItemGrossVolume` → **KTDDE:** `GoodsItem.itemGrossVolume (Measure)` — ⚠️ Proposal

- **Totals (document level)**
  - (computed from items) → **KTDDE:** `TransportDocument.totalPackageQuantity` — ✅ Maps
  - (computed from items) → **KTDDE:** `TransportDocument.totalGrossWeight` — ✅ Maps

## Transport means
- (from carrier) `carrierLicensePlate` → **KTDDE:** `TransportMeans.vehicleRegistrationIdentifier` — ✅ Maps
- (optional) driver attachment → **KTDDE:** `TransportMeans.driverName` — ⚠️ Proposal

## Charges & payment
- `toBePaidBy.customChargeCarriage.value/currency/payer` — Freight charges & payer → **KTDDE:** `TransportDocument.freightChargesAmount → MonetaryAmount (amountValue, currencyCode)` + `payerRoleCode`/**or**`payerParty` — ✅ Maps (amount) • ⚠️ Proposal (payer role)
- `toBePaidBy.customChargeSupplementary` — Supplementary charge → **KTDDE:** `TransportDocument.supplementaryChargeAmount → MonetaryAmount` — ⚠️ Proposal
- `toBePaidBy.customChargeCustomsDuties` — Customs duties → **KTDDE:** `TransportDocument.customsDutiesAmount → MonetaryAmount` — ⚠️ Proposal
- `toBePaidBy.customChargeOther` — Other charge → **KTDDE:** `TransportDocument.otherChargeAmount → MonetaryAmount` — ⚠️ Proposal

## Other particulars
- `specialAgreementsSenderCarrier.customSpecialAgreement` — Special agreement text → **KTDDE:** `TransportDocument.specialAgreementText` — ⚠️ Proposal
- `otherUsefulParticulars.customParticulars` — Generic note → **KTDDE:** `TransportDocument.note` — ⚠️ Proposal
- `cashOnDelivery.customCashOnDelivery` — Cash on delivery amount → **KTDDE:** `TransportDocument.cashOnDeliveryAmount → MonetaryAmount` — ⚠️ Proposal

## Delivery confirmation (goods received)
- `goodsReceived.confirmedLogisticsLocationName` — Delivery location label → **KTDDE:** `TransportDocument.toLocation → Location.locationName` — ✅ Maps
- `goodsReceived.consigneeReservationsObservations` — Consignee remarks → **KTDDE:** `TransportDocument.consigneeRemarksText` — ⚠️ Proposal
- `goodsReceived.consigneeSignature{…}` — Consignee signature blob → **KTDDE:** `TransportDocument.signature → Signature` (actor/time/data) — ⚠️ Proposal
- `goodsReceived.consigneeSignatureDate` — Delivery signature time → **KTDDE:** `TransportDocument.deliverySignatureDateTime (xsd:dateTime)` — ⚠️ Proposal
- `goodsReceived.consigneeTimeOfArrival` — Arrival at destination → **KTDDE:** `TransportDocument.arrivalDateTimeAtUnloading (xsd:dateTime)` — ⚠️ Proposal
- `goodsReceived.consigneeTimeOfDeparture` — Departure after delivery → **KTDDE:** `TransportDocument.departureDateTimeFromUnloading (xsd:dateTime)` — ⚠️ Proposal

## Non-contractual remarks
- `nonContractualPartReservedForTheCarrier.nonContractualCarrierRemarks` — Non-contractual remarks → **KTDDE:** `TransportDocument.nonContractualCarrierRemarksText` — ⚠️ Proposal

---

### Notes
- All **✅** lines use properties/classes present in the OWL you provided.
- All **⚠️** lines are proposed extensions, named to align with KTDDE conventions.
- **⚙️** indicates we used the closest available role/property where an exact role was missing (e.g., successive carrier).

### Optional next step
If helpful, I can append a **compact JSON-LD skeleton** that includes only the ✅ mappable parts for immediate serialization, and a second skeleton that adds all ⚠️ proposals behind a feature flag section.

