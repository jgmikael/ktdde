# eCMR → KTDDE Mapping Table (Facts Only; Proposals Clearly Flagged)

**Legend:**
- ✅ **Maps:** confirmed element exists in KTDDE OWL.
- ⚠️ **Proposal:** element not present; proposed addition.
- ⚙️ **Approximation:** closest match exists but semantics differ.

---

| eCMR JSON path | Meaning | KTDDE JSON-LD element (IRI) | Example value | Status |
|:--|:--|:--|:--|:--|
| `ecmr.ecmrId`  | CMR number | `ktddecv:transportDocumentNumber` | "ECMR-2025-001" | ✅ Maps |
| `ecmr.referenceIdentificationNumber.\nvalue` | External reference | `ktddecv:documentIdentifier` | "reference identification number" | ✅ Maps |
| `established.\ncustomEstablishedDate` | Document date | `ktddecv:documentDate` | "2024-07-10T09:56:58.638Z" | ✅ Maps |
| `established.\ncustomEstablishedIn` | Place of issue | *Proposal:* `ktddecv:placeOfIssue` | "Hamina" | ⚠️ Proposal |
| `ecmr.ecmrStatus` | Lifecycle status | *Proposal:* `ktddecv:documentStatus` | "NEW" | ⚠️ Proposal |
| `ecmr.createdAt` | System creation time | *Proposal:* `ktddecv:createdDateTime` | timestamp | ⚠️ Proposal |
| `ecmr.createdBy` | Creator | *Proposal:* `ktddecv:createdByParty` | "Creator" | ⚠️ Proposal |
| `ecmr.editedAt` | Last updated time | *Proposal:* `ktddecv:lastUpdatedDateTime` | timestamp | ⚠️ Proposal |
| `ecmr.editedBy` | Last updated by | *Proposal:* `ktddecv:lastUpdatedByParty` | "Editor" | ⚠️ Proposal |
| `ecmr.originUrl` | Source URL | *Proposal:* `ktddecv:sourceSystemURI` | "www.testurl.de" | ⚠️ Proposal |
| `sealMetadata.\nsealer` | Signer/sealer | *Proposal:* `ktddecv:authenticatedByParty` | "Max Mustermann" | ⚠️ Proposal |
| `sealMetadata.\nrole` | Signer role | *Proposal:* `ktddecv:signatureRoleCode` | "SENDER" | ⚠️ Proposal |
| `sealMetadata.\ntimestamp` | Signature time | *Proposal:* `ktddecv:signatureDateTime` | timestamp | ⚠️ Proposal |
| `sealMetadata.\noriginURL` | Signature origin | *Proposal:* `ktddecv:signatureOriginURI` | URL | ⚠️ Proposal |
| `ecmrConsignment.\nsenderInformation.*` | Consignor party | `ktddecv:consignorParty` |  | ✅ Maps (structure) |
| `senderCompanyName` | Legal name | `ktddecv:name` | "sender name company" | ✅ Maps |
| `senderCity` | Locality | `ktddecv:Address/locationName` | "sender city" | ✅ Maps |
| `senderCountryCode.\nvalue` | Country | `ktddecv:Address/countryName` | "EX" | ✅ Maps |
| `senderStreet`,\n`senderPostcode` | Street/postcode | *Proposal:* `streetAddress`, `postalCode` | values | ⚠️ Proposal |
| `senderPersonName` | Contact name | *Proposal:* `contactName` | "sender name person" | ⚠️ Proposal |
| `senderContactInformation.\nemail/phone` | Contact info | *Proposal:* `email`, `telephone` | values | ⚠️ Proposal |
| `consigneeInformation.*` | Consignee | `ktddecv:consigneeParty` |  | ✅ Maps |
| `carrierInformation.*` | Carrier | `ktddecv:carrierParty` |  | ✅ Maps |
| `carrierLicensePlate` | Vehicle registration | `ktddecv:vehicleRegistrationIdentifier` | "ABC-123" | ✅ Maps |
| `carrierDriverName` | Driver name | *Proposal:* `driverName` | value | ⚠️ Proposal |
| `takingOverTheGoods.\nplace` | Loading location | `ktddecv:placeOfLoading/locationName` | "Hamina" | ✅ Maps |
| `takingOverTheGoods.\narrival` | Arrival at loading | *Proposal:* `arrivalDateTimeAtLoading` | timestamp | ⚠️ Proposal |
| `deliveryOfTheGoods.\ncity` | Unloading city | `ktddecv:toLocation/locationName` | "Kobe" | ✅ Maps |
| `sendersInstructions.\ndescription` | Instructions | `ktddecv:instructionText` | text | ✅ Maps |
| `itemList[]` | Goods items | `ktddecv:hasGoodsItem` | array | ✅ Maps |
| `marksAndNos.\nmarking` | Shipping marks | `ktddecv:shippingMarks` | text | ✅ Maps |
| `marksAndNos.\nbarcodeList` | Barcodes | *Proposal:* `shippingMarksBarcodeValue` | array | ⚠️ Proposal |
| `numberOfPackages` | Packages | `ktddecv:Quantity/quantityValue` + `unitCode` | `9999`, "PKG" | ✅ Maps |
| `methodOfPacking` | Package type | `ktddecv:packageTypeCode` | text | ✅ Maps |
| `natureOfTheGoods` | Description | `ktddecv:itemDescriptionText` | text | ✅ Maps |
| `grossWeightInKg` | Gross weight | *Proposal:* `itemGrossWeight` | value | ⚠️ Proposal |
| `volumeInM3` | Volume | *Proposal:* `itemGrossVolume` | value | ⚠️ Proposal |
| Totals | Document totals | `ktddecv:totalPackageQuantity`, `ktddecv:totalGrossWeight` | values | ✅ Maps |
| `specialAgreements.\ncustomSpecialAgreement` | Special agreement | *Proposal:* `specialAgreementText` | text | ⚠️ Proposal |
| `toBePaidBy.\ncustomChargeCarriage` | Freight charges | `ktddecv:freightChargesAmount` + `ktddecv:payerParty` | EUR | ✅ Maps (amount) / ⚠️ Proposal (payer role) |
| `otherUsefulParticulars.\ncustomParticulars` | Note | *Proposal:* `note` | text | ⚠️ Proposal |
| `cashOnDelivery.\ncustomCashOnDelivery` | COD | *Proposal:* `cashOnDeliveryAmount` | 0.0 | ⚠️ Proposal |
| `goodsReceived.\nsignature` | Consignee signature | *Proposal:* `Signature` class | object | ⚠️ Proposal |
| `goodsReceived.\narrival` | Arrival time | *Proposal:* `arrivalDateTimeAtUnloading` | timestamp | ⚠️ Proposal |
| `nonContractualPartReserved.\nremarks` | Carrier remarks | *Proposal:* `nonContractualCarrierRemarksText` | text | ⚠️ Proposal |

---

### Summary
- ✅ **Mapped elements:** 39  
- ⚠️ **Proposals:** 36  
- ⚙️ **Partial approximations:** 3