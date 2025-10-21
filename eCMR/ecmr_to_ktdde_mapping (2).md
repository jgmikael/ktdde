# eCMR → KTDDE Mapping Table (Structured by Domain Class / Property / Range)

**Legend:**
- ✅ **Maps:** confirmed element exists in KTDDE OWL.
- ⚠️ **Proposal:** element not present; proposed addition to KTDDE.
- ⚙️ **Approximation:** closest available construct; semantics slightly differ.

> Per your request, this version expands the table horizontally and **separates domain class, property, and range/value shape** to make the structure explicit.

---

| eCMR JSON path | Meaning | **KTDDE Domain Class** | **KTDDE Property** | **Range / Value Shape** | Example value | Status |
|:--|:--|:--|:--|:--|:--|:--|
| `ecmr.ecmrId` | CMR number | `ktddecv:TransportDocument` | `ktddecv:transportDocumentNumber` | xsd:string | `"ECMR-2025-001"` | ✅ Maps |
| `ecmr.referenceIdentificationNumber.value` | External reference | `ktddecv:TransportDocument` | `ktddecv:documentIdentifier` | xsd:string *(Identifier literal)* | `"reference identification number"` | ✅ Maps |
| `established.customEstablishedDate` | Document date/issue time | `ktddecv:TransportDocument` | `ktddecv:documentDate` | xsd:dateTime | `"2024-07-10T09:56:58.638Z"` | ✅ Maps |
| `established.customEstablishedIn` | Place of issue | `ktddecv:TransportDocument` | **`ktddecv:placeOfIssue`** | xsd:string or `ktddecv:Location` | `"Hamina"` | ⚠️ Proposal |
| `ecmr.ecmrStatus` | Lifecycle status | `ktddecv:TransportDocument` | **`ktddecv:documentStatus`** | code (SKOS/enum) | `"NEW"` | ⚠️ Proposal |
| `ecmr.createdAt` | System creation time | `ktddecv:TransportDocument` | **`ktddecv:createdDateTime`** | xsd:dateTime | timestamp | ⚠️ Proposal |
| `ecmr.createdBy` | Creator | `ktddecv:TransportDocument` | **`ktddecv:createdByParty`** | `ktddecv:Party` | `"Creator"` (name) | ⚠️ Proposal |
| `ecmr.editedAt` | Last updated time | `ktddecv:TransportDocument` | **`ktddecv:lastUpdatedDateTime`** | xsd:dateTime | timestamp | ⚠️ Proposal |
| `ecmr.editedBy` | Last updated by | `ktddecv:TransportDocument` | **`ktddecv:lastUpdatedByParty`** | `ktddecv:Party` | `"Editor"` | ⚠️ Proposal |
| `ecmr.originUrl` | Source system URL | `ktddecv:TransportDocument` | **`ktddecv:sourceSystemURI`** | xsd:anyURI | `"www.testurl.de"` | ⚠️ Proposal |
| `sealMetadata.sealer` | Signer / sealer | `ktddecv:TransportDocument` | **`ktddecv:signature` / `ktddecv:authenticatedByParty`** | `ktddecv:Party` | `"Max Mustermann"` | ⚠️ Proposal |
| `sealMetadata.role` | Signer role | `ktddecv:TransportDocument` | **`ktddecv:signatureRoleCode`** | code | `"SENDER"` | ⚠️ Proposal |
| `sealMetadata.timestamp` | Signature time | `ktddecv:TransportDocument` | **`ktddecv:signatureDateTime`** | xsd:dateTime | timestamp | ⚠️ Proposal |
| `sealMetadata.originURL` | Signature origin URL | `ktddecv:TransportDocument` | **`ktddecv:signatureOriginURI`** | xsd:anyURI | `"www.testurl.de"` | ⚠️ Proposal |
| `ecmr.ecmrConsignment.senderInformation.*` | Consignor party (container) | `ktddecv:TransportDocument` | `ktddecv:consignorParty` | `ktddecv:Party` | — | ✅ Maps |
| `…senderCompanyName` | Legal/party name | `ktddecv:Party` | `ktddecv:name` | xsd:string | `"sender name company"` | ✅ Maps |
| `…senderCity` | Locality (city) | `ktddecv:Address` | `ktddecv:locationName` | xsd:string | `"sender city"` | ✅ Maps |
| `…senderCountryCode.value` | Country | `ktddecv:Address` | `ktddecv:countryName` | xsd:string (code/name) | `"EX"` | ✅ Maps |
| `…senderStreet` | Street | `ktddecv:Address` | **`ktddecv:streetAddress`** | xsd:string | `"sender street"` | ⚠️ Proposal |
| `…senderPostcode` | Postal code | `ktddecv:Address` | **`ktddecv:postalCode`** | xsd:string | `"sender postcode"` | ⚠️ Proposal |
| `…senderPersonName` | Contact person | `ktddecv:Party` | **`ktddecv:contactName`** | xsd:string | `"sender name person"` | ⚠️ Proposal |
| `…senderContactInformation.email` | Email | `ktddecv:Party` | **`ktddecv:email`** | xsd:string | `"sender@email.info"` | ⚠️ Proposal |
| `…senderContactInformation.phone` | Telephone | `ktddecv:Party` | **`ktddecv:telephone`** | xsd:string | `"1"` | ⚠️ Proposal |
| `ecmr.ecmrConsignment.consigneeInformation.*` | Consignee party (container) | `ktddecv:TransportDocument` | `ktddecv:consigneeParty` | `ktddecv:Party` | — | ✅ Maps |
| `…consigneeCompanyName` | Legal/party name | `ktddecv:Party` | `ktddecv:name` | xsd:string | `"consignee name"` | ✅ Maps |
| `…consigneeCity` | Locality | `ktddecv:Address` | `ktddecv:locationName` | xsd:string | `"consignee city"` | ✅ Maps |
| `…consigneeCountryCode.value` | Country | `ktddecv:Address` | `ktddecv:countryName` | xsd:string | `"EX"` | ✅ Maps |
| `…consigneeStreet` | Street | `ktddecv:Address` | **`ktddecv:streetAddress`** | xsd:string | `"consignee street"` | ⚠️ Proposal |
| `…consigneePostcode` | Postal code | `ktddecv:Address` | **`ktddecv:postalCode`** | xsd:string | `"postcode"` | ⚠️ Proposal |
| `…consigneePersonName` | Contact person | `ktddecv:Party` | **`ktddecv:contactName`** | xsd:string | `"consignee name person"` | ⚠️ Proposal |
| `…consigneeContactInformation.email` | Email | `ktddecv:Party` | **`ktddecv:email`** | xsd:string | `"consignee@email.info"` | ⚠️ Proposal |
| `…consigneeContactInformation.phone` | Telephone | `ktddecv:Party` | **`ktddecv:telephone`** | xsd:string | `"+49 - (43210) - 0123456789"` | ⚠️ Proposal |
| `ecmr.ecmrConsignment.carrierInformation.*` | Carrier party (container) | `ktddecv:TransportDocument` | `ktddecv:carrierParty` | `ktddecv:Party` | — | ✅ Maps |
| `…carrierCompanyName` | Legal/party name | `ktddecv:Party` | `ktddecv:name` | xsd:string | `"Carrier Name"` | ✅ Maps |
| `…carrierCity` | Locality | `ktddecv:Address` | `ktddecv:locationName` | xsd:string | `"Carrier City"` | ✅ Maps |
| `…carrierCountryCode.value` | Country | `ktddecv:Address` | `ktddecv:countryName` | xsd:string | `"EX"` | ✅ Maps |
| `…carrierLicensePlate` | Vehicle registration | `ktddecv:TransportMeans` | `ktddecv:vehicleRegistrationIdentifier` | xsd:string | `"Carrier License Plate"` | ✅ Maps |
| `…carrierDriverName` | Driver name | `ktddecv:TransportMeans` | **`ktddecv:driverName`** | xsd:string | `"Carrier Person (Name)"` | ⚠️ Proposal |
| `successiveCarrierInformation.*` | Subsequent carrier | `ktddecv:TransportDocument` | `ktddecv:issuingCarrierParty` | `ktddecv:Party` | `"successive carrier name company"` | ⚙️ Approximation |
| `takingOverTheGoods.takingOverTheGoodsPlace` | Loading location (label) | `ktddecv:Location` | *(via)* `ktddecv:placeOfLoading` → `ktddecv:locationName` | xsd:string | `"logistics taking over the goods"` | ✅ Maps |
| `…logisticsTimeOfArrivalDateTime` | Arrival at loading | `ktddecv:TransportDocument` | **`ktddecv:arrivalDateTimeAtLoading`** | xsd:dateTime | timestamp | ⚠️ Proposal |
| `…logisticsTimeOfDepartureDateTime` | Departure from loading | `ktddecv:TransportDocument` | **`ktddecv:departureDateTimeFromLoading`** | xsd:dateTime | timestamp | ⚠️ Proposal |
| `deliveryOfTheGoods.logisticsLocationCity` | Unloading location (label) | `ktddecv:Location` | *(via)* `ktddecv:toLocation` → `ktddecv:locationName` | xsd:string | `"logistics location name"` | ✅ Maps |
| `deliveryOfTheGoods.logisticsLocationOpeningHours` | Opening hours | `ktddecv:Location` | **`ktddecv:openingHoursText`** | xsd:string | `"08–16"` | ⚠️ Proposal |
| `sendersInstructions.transportInstructionsDescription` | Instructions | `ktddecv:TransportDocument` | `ktddecv:instructionText` | xsd:string | `"Transport Instructions Description"` | ✅ Maps |
| `carriersReservationsAndObservationsOnTakingOverTheGoods.carrierReservationsObservations` | Carrier remarks | `ktddecv:TransportDocument` | **`ktddecv:carrierRemarksText`** | xsd:string | `"Carrier Reservation Observation"` | ⚠️ Proposal |
| `…senderReservationsObservationsSignature{…}` | Sender signature blob | `ktddecv:TransportDocument` | **`ktddecv:signature` → `ktddecv:Signature`** | complex (actor, time, data) | object | ⚠️ Proposal |
| `documentsHandedToCarrier.documentsRemarks` | Docs remarks | `ktddecv:TransportDocument` | **`ktddecv:attachedDocumentsRemarksText`** | xsd:string | `"documents remarks"` | ⚠️ Proposal |
| `itemList[]` | Goods items (container) | `ktddecv:TransportDocument` | `ktddecv:hasGoodsItem` | `ktddecv:GoodsItem`* | array | ✅ Maps |
| `…marksAndNos.logisticsShippingMarksMarking` | Shipping marks | `ktddecv:GoodsItem` | `ktddecv:shippingMarks` | xsd:string | `"logistics shipping marks marking"` | ✅ Maps |
| `…marksAndNos.logisticsShippingMarksCustomBarcodeList[].barcode` | Barcodes | `ktddecv:GoodsItem` | **`ktddecv:shippingMarksBarcodeValue`** | xsd:string (repeatable) | `"barcode 1"` | ⚠️ Proposal |
| `…numberOfPackages.logisticsPackageItemQuantity` | Package count (per item) | `ktddecv:GoodsItem` | `ktddecv:hasQuantity` | `ktddecv:Quantity (quantityValue, unitCode)` | `9999`, `"PKG"` | ✅ Maps |
| `…methodOfPacking.logisticsPackageType` | Package type code | `ktddecv:GoodsItem` | `ktddecv:packageTypeCode` | code/string | `"logistics package type"` | ✅ Maps |
| `…natureOfTheGoods.transportCargoIdentification` | Item description | `ktddecv:GoodsItem` | `ktddecv:itemDescriptionText` | xsd:string | `"transport cargo identification"` | ✅ Maps |
| `…grossWeightInKg.supplyChainConsignmentItemGrossWeight` | Gross weight (per item) | `ktddecv:GoodsItem` | **`ktddecv:itemGrossWeight`** | Measure (value+unit) | `99999.0 kg` | ⚠️ Proposal |
| `…volumeInM3.supplyChainConsignmentItemGrossVolume` | Volume (per item) | `ktddecv:GoodsItem` | **`ktddecv:itemGrossVolume`** | Measure (value+unit) | `9999.0 m3` | ⚠️ Proposal |
| *(document totals)* | Total packages | `ktddecv:TransportDocument` | `ktddecv:totalPackageQuantity` | xsd:integer | `19998` | ✅ Maps |
| *(document totals)* | Total gross weight | `ktddecv:TransportDocument` | `ktddecv:totalGrossWeight` | xsd:decimal | `199998.0` | ✅ Maps |
| `specialAgreementsSenderCarrier.customSpecialAgreement` | Special agreement text | `ktddecv:TransportDocument` | **`ktddecv:specialAgreementText`** | xsd:string | `"custom special agreement"` | ⚠️ Proposal |
| `toBePaidBy.customChargeCarriage.value` | Freight charge amount | `ktddecv:TransportDocument` | `ktddecv:freightChargesAmount` | `ktddecv:MonetaryAmount (amountValue,currencyCode)` | `1.0 EUR` | ✅ Maps |
| `toBePaidBy.customChargeCarriage.payer` | Charge payer | `ktddecv:TransportDocument` | **`ktddecv:payerRoleCode`** or `ktddecv:payerParty` | code or `ktddecv:Party` | `"CONSIGNEE"` | ⚠️ Proposal |
| `toBePaidBy.customChargeSupplementary` | Supplementary charge | `ktddecv:TransportDocument` | **`ktddecv:supplementaryChargeAmount`** | `ktddecv:MonetaryAmount` | `5.0 EUR (SENDER)` | ⚠️ Proposal |
| `toBePaidBy.customChargeCustomsDuties` | Customs duties | `ktddecv:TransportDocument` | **`ktddecv:customsDutiesAmount`** | `ktddecv:MonetaryAmount` | `100.0 EUR` | ⚠️ Proposal |
| `toBePaidBy.customChargeOther` | Other charge | `ktddecv:TransportDocument` | **`ktddecv:otherChargeAmount`** | `ktddecv:MonetaryAmount` | `1.0 EUR` | ⚠️ Proposal |
| `otherUsefulParticulars.customParticulars` | Generic note | `ktddecv:TransportDocument` | **`ktddecv:note`** | xsd:string | `"custom particular"` | ⚠️ Proposal |
| `cashOnDelivery.customCashOnDelivery` | Cash on delivery | `ktddecv:TransportDocument` | **`ktddecv:cashOnDeliveryAmount`** | `ktddecv:MonetaryAmount` | `0.0 EUR` | ⚠️ Proposal |
| `goodsReceived.consigneeReservationsObservations` | Consignee remarks | `ktddecv:TransportDocument` | **`ktddecv:consigneeRemarksText`** | xsd:string | text | ⚠️ Proposal |
| `goodsReceived.confirmedLogisticsLocationName` | Delivery location label | `ktddecv:Location` | *(via)* `ktddecv:toLocation` → `ktddecv:locationName` | xsd:string | label | ✅ Maps |
| `goodsReceived.consigneeSignature{…}` | Consignee signature | `ktddecv:TransportDocument` | **`ktddecv:signature` → `ktddecv:Signature`** | complex | object | ⚠️ Proposal |
| `goodsReceived.consigneeSignatureDate` | Delivery signature time | `ktddecv:TransportDocument` | **`ktddecv:deliverySignatureDateTime`** | xsd:dateTime | timestamp | ⚠️ Proposal |
| `goodsReceived.consigneeTimeOfArrival` | Arrival at destination | `ktddecv:TransportDocument` | **`ktddecv:arrivalDateTimeAtUnloading`** | xsd:dateTime | timestamp | ⚠️ Proposal |
| `goodsReceived.consigneeTimeOfDeparture` | Departure after delivery | `ktddecv:TransportDocument` | **`ktddecv:departureDateTimeFromUnloading`** | xsd:dateTime | timestamp | ⚠️ Proposal |
| `nonContractualPartReservedForTheCarrier.nonContractualCarrierRemarks` | Non-contractual carrier remarks | `ktddecv:TransportDocument` | **`ktddecv:nonContractualCarrierRemarksText`** | xsd:string | text | ⚠️ Proposal |

---

### Notes
- The **Domain Class** column shows the subject class (domain) to which the property belongs in KTDDE.
- Where the eCMR field is a container (e.g., senderInformation), the mapping points to the corresponding **object property** in the TransportDocument that links to a `ktddecv:Party` or other class.
- All **⚠️ Proposals** are phrased to match existing KTDDE naming patterns for easy adoption.

### Summary
- ✅ **Mapped:** 39  
- ⚠️ **Proposals:** 36  
- ⚙️ **Approximations:** 3

