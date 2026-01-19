# UNVTD Bill of Lading → KTDDE (ktddecv) mappings and SHACL blueprint
Based on analysis of the **latest uploaded** `ktddecv` Turtle (Jan 19, 2026 upload) plus your BoL-marked KTDDE Data Glossary CSV.

## Direct matches (high confidence)
| UNVTD term                   | Kind     | UNVTD IRI                               | KTDDE Data Glossary (BoL)                           | ktddecv candidates               | Verification / notes                                      |
|:-----------------------------|:---------|:----------------------------------------|:----------------------------------------------------|:---------------------------------|:----------------------------------------------------------|
| BillOfLading                 | class    | trade:TransportDocument                 |                                                     | ktddecv:BillOfLading             | Document class present                                    |
| documentIdentifier           | datatype | trade:ID                                | Document Identifier (UID 1004, M)                   | ktddecv:documentIdentifier       | Exact property present                                    |
| contractNumber               | datatype | trade:ContractReferencedDocument        | Contract number (UID 1296, M)                       | ktddecv:contractNumber           | Exact property present                                    |
| issueDate                    | datatype | trade:IssueDateTime                     | Issue date (UID 2007, M)                            | ktddecv:issueDate                | Exact property present                                    |
| estimatedTimeOfDeparture     | datatype | trade:EstimatedDepartureDateTime        | Estimated time of departure (UID 2195, O)           | ktddecv:estimatedTimeOfDeparture | Exact property present                                    |
| consignor                    | object   | trade:ConsignorTradeParty               | Consignor (UID 3336, M)                             | ktddecv:consignorParty           | Role property present                                     |
| consignee                    | object   | trade:ConsigneeTradeParty               | Consignee (UID 3132, C)                             | ktddecv:consigneeParty           | Role property present (CSV marks C)                       |
| notifyParty                  | object   | trade:NotifyParty                       |                                                     | ktddecv:notifyParty              | Role property present                                     |
| carrier                      | object   | trade:CarrierTradeParty                 | Carrier (Transport Services Provider) (UID 3126, M) | ktddecv:carrierParty             | Role property present                                     |
| deliveryLocation             | object   | trade:FinalDestinationLogisticsLocation |                                                     | ktddecv:deliveryLocation         | Location role property present                            |
| paymentLocation              | object   | trade:PaymentLogisticsLocation          |                                                     | ktddecv:paymentLocation          | Location role property present                            |
| placeOfIssue                 | object   | trade:IssueLogisticsLocation            |                                                     | ktddecv:placeOfIssue             | Place of issue present                                    |
| transportEquipmentIdentifier | datatype | trade:ID                                |                                                     | ktddecv:equipmentIdentifier      | Equipment identifier present                              |
| sealIdentifier               | datatype | trade:SealID                            |                                                     | ktddecv:sealIdentifier           | Seal identifier present                                   |
| grossWeight                  | datatype | trade:GrossWeightMeasure                |                                                     | ktddecv:totalGrossWeight         | Best match for gross weight at document/consignment level |
| shippingMarks                | datatype | trade:ShippingMark                      |                                                     | ktddecv:shippingMarks            | Exact property present                                    |
| descriptionOfGoods           | datatype | trade:Description                       | Description of Goods (UID 7002, M)                  | ktddecv:descriptionOfGoodsText   | Exact-ish property present                                |
| collectCharges               | object   | trade:CollectAmount                     |                                                     | ktddecv:totalCollectCharges      | Collect charges aggregate present                         |
| packagingType                | datatype | trade:TypeCode                          |                                                     | ktddecv:packageTypeCode          | Package type code present                                 |

## Strong candidates (high confidence but modelling choice)
| UNVTD term                  | Kind     | UNVTD IRI                                | KTDDE Data Glossary (BoL)   | ktddecv candidates                                                                                            | Verification / notes                                                               |
|:----------------------------|:---------|:-----------------------------------------|:----------------------------|:--------------------------------------------------------------------------------------------------------------|:-----------------------------------------------------------------------------------|
| freightPayer                | object   | trade:FreightPayerTradeParty             |                             | ktddecv:payerParty; ktddecv:freightPayableAtPlace; ktddecv:freightPaymentTermCode                             | Closest existing pattern; verify role vs payment terms                             |
| originalLoadingLocation     | object   | trade:LoadingLogisticsLocation           |                             | ktddecv:placeOfLoading; ktddecv:portOfLoadingUNLocode; ktddecv:placeOfReceipt; ktddecv:placeOfReceiptUNLocode | KTDDE distinguishes place/port of loading and place of receipt; choose             |
| baseportUnloadingLocation   | object   | trade:UnloadingLogisticsLocation         |                             | ktddecv:placeOfDischarge; ktddecv:portOfDischargeUNLocode                                                     | Discharge/port of discharge present; choose                                        |
| placeOfDeparture            | object   | trade:DepartureLogisticsLocation         |                             | ktddecv:departurePlace; ktddecv:officeOfDeparture; ktddecv:placeOfReceipt                                     | DeparturePlace exists but may be generic; verify in BoL context                    |
| arrivalLocation             | object   | trade:ArrivalLogisticsLocation           |                             | ktddecv:arrivalPlace; ktddecv:finalDestinationUNLocode; ktddecv:placeOfDeliveryUNLocode                       | Arrival vs final destination vs place of delivery; choose                          |
| conveyanceReferenceNumber   | datatype | trade:TransportMovementID                |                             | ktddecv:voyageNumber                                                                                          | For sea BoL, voyage number may be the movement reference; verify broader meaning   |
| transportMeansIdentifier    | datatype | trade:ID                                 |                             | ktddecv:vesselName                                                                                            | UNVTD uses ID; KTDDE has vesselName, transport means class; verify identifier need |
| transportMeansRegistration  | datatype | trade:RegistrationID                     |                             | ktddecv:vehicleRegistrationIdentifier                                                                         | Vehicle registration exists; sea vessel IMO not found                              |
| numberOfPackages            | datatype | trade:PackageQuantity                    |                             | ktddecv:totalPackageCount; ktddecv:totalPackageQuantity; ktddecv:packageCount                                 | Multiple package count terms exist; confirm which matches BoL need                 |
| transportContractConditions | datatype | trade:ContractTermsDescription           |                             | ktddecv:deliveryTermsText                                                                                     | Closest free-text terms property; verify contract-terms scope                      |
| prepaidAmount               | object   | trade:PrepaidAmount                      |                             | ktddecv:freightChargesAmount                                                                                  | KTDDE has freight charges amount; verify prepaid semantics                         |
| goods                       | object   | trade:IncludedSupplyChainConsignmentItem |                             | ktddecv:hasGoodsItem; ktddecv:hasConsignment; ktddecv:relatesToConsignment                                    | Goods items and consignment constructs exist; choose modelling pattern             |

## Needs verification or missing in ktddecv
| UNVTD term                    | Kind     | UNVTD IRI                          | KTDDE Data Glossary (BoL)                                         | ktddecv candidates   | Verification / notes                                                       |
|:------------------------------|:---------|:-----------------------------------|:------------------------------------------------------------------|:---------------------|:---------------------------------------------------------------------------|
| billOfLadingNumber            | datatype | trade:ID                           | Transport Contract Document / Bill of Lading number (UID 1188, O) |                      | No dedicated BoL number property detected                                  |
| bookingReferenceNumber        | datatype | trade:BookingReferencedDocument    | Booking reference number (UID 1016, O)                            |                      | No booking reference property detected                                     |
| consignmentLoadingDate        | datatype | trade:LoadingDateTime              | Consignment loading date (UID 2347, M)                            |                      | No consignment loading date property detected                              |
| estimatedTimeOfArrival        | datatype | trade:EstimatedArrivalDateTime     | Estimated time of arrival (UID 2349, O)                           |                      | No estimated arrival property detected; candidates planned/arrivalDateTime |
| ucr                           | datatype | trade:UniqueConsignmentReferenceID |                                                                   |                      | No UCR property detected                                                   |
| containerSizeAndType          | datatype | trade:CharacteristicCode           |                                                                   |                      | No ISO size/type code property detected                                    |
| fullOrEmptyContainer          | datatype | trade:FullnessCode                 |                                                                   |                      | No container fullness code property detected                               |
| volume                        | datatype | trade:GrossVolumeMeasure           | Volume (Cube) (UID 6322, M)                                       |                      | No gross volume / volume measure property detected                         |
| consignmentSummaryDescription | datatype | trade:SummaryDescription           |                                                                   |                      | No summary description property detected                                   |
| hsCode                        | datatype | trade:ClassificationID             |                                                                   |                      | No explicit HS code property detected (search did not find)                |

## Proposed KTDDE Bill of Lading SHACL: included ktddecv nodes and properties
This is a **node-centric** proposal: what you should include in a `ktddecv`-native BoL shape, and where you likely need `ktddecv` extensions.

### Document node
- **Node / targetClass:** `ktddecv:BillOfLading`
- **Core datatype properties (existing):** `ktddecv:documentIdentifier` (M), `ktddecv:issueDate` (M), `ktddecv:contractNumber` (M), `ktddecv:estimatedTimeOfDeparture` (O), `ktddecv:shippingMarks` (O), `ktddecv:descriptionOfGoodsText` (O), `ktddecv:totalGrossWeight` (O), `ktddecv:freightChargesAmount` (O), `ktddecv:totalCollectCharges` (O), `ktddecv:packageTypeCode` (O).
- **Core object properties (existing):** `ktddecv:consignorParty` (M) → Party node, `ktddecv:consigneeParty` (C) → Party node, `ktddecv:notifyParty` (O) → Party node, `ktddecv:carrierParty` (O) → Party node, `ktddecv:deliveryLocation` (O) → Location node, `ktddecv:paymentLocation` (O) → Location node, `ktddecv:placeOfIssue` (O) → Location node.
- **Consignment / goods pattern (existing, choose one):**
  - Option A: link BoL directly to `ktddecv:hasGoodsItem` (0..n) → `ktddecv:GoodsItem`
  - Option B: link BoL to `ktddecv:hasConsignment` / `ktddecv:relatesToConsignment` and nest goods under the consignment (preferred if you want UCR and consignment-level attributes).

### Party node
- **Node class:** (your choice; KTDDE uses many role properties like `...Party`, plus `ktddecv:LegalEntity` and `ktddecv:partyLegalEntity`).
- **Include (existing):** `ktddecv:hasAddress` → `ktddecv:Address`/`ktddecv:PostalAddress`; `ktddecv:hasIdentifier` → Identifier; plus whichever name/legal-name property you standardize on (needs your confirmation, as it is not evident from UNVTD context).

### Location node
- **Node class:** `ktddecv:Location`
- **Include (existing):** `ktddecv:locationName`, `ktddecv:unlocode` (or specific UN/LOCODE properties such as `ktddecv:portOfLoadingUNLocode`, `ktddecv:portOfDischargeUNLocode`, `ktddecv:placeOfReceiptUNLocode`, `ktddecv:placeOfDeliveryUNLocode`), `ktddecv:locationCountry`, `ktddecv:locationID`.

### Transport equipment node
- **Node class:** `ktddecv:TransportEquipment`
- **Include (existing):** `ktddecv:equipmentIdentifier` (and, for containers, also `ktddecv:containerNumber` if you model ISO 6346 container numbers explicitly); `ktddecv:sealIdentifier` (confirm whether domain should be equipment vs document).

### Transport means node
- **Node class:** `ktddecv:TransportMeans`
- **Include (existing candidates):** `ktddecv:vesselName`, `ktddecv:voyageNumber`, `ktddecv:vehicleRegistrationIdentifier` (road).
- **Likely extension:** a generic `transportMeansIdentifier` that can carry IMO/MMSI/aircraft registration etc. (UNVTD models it as `ID`).

### Goods item / package node
- **Node class:** `ktddecv:GoodsItem`
- **Include (existing):** `ktddecv:hasPackageItem` / `ktddecv:relatesToPackage` patterns; package counts (`ktddecv:packageCount` / `ktddecv:totalPackageCount` / `ktddecv:totalPackageQuantity` — choose).
- **Likely extension:** explicit HS code property (if you want direct HS at item level) and gross volume at item/consignment level (if required).

## Suggested additions to ktddecv (missing terms)
These are the terms that are either absent in the TTL or too underspecified for the UNVTD BoL requirements. I list them as **recommended new terms** with suggested domain/range.

| Proposed ktddecv term                   | Type             | Suggested domain → range                                      | Rationale                                                                                                                |
|:----------------------------------------|:-----------------|:--------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------|
| ktddecv:billOfLadingNumber              | DatatypeProperty | ktddecv:BillOfLading → xsd:string (or Identifier model)       | KTDDE glossary UID 1188 exists; keep distinct from generic documentIdentifier.                                           |
| ktddecv:bookingReferenceNumber          | DatatypeProperty | ktddecv:BillOfLading/Consignment → xsd:string                 | Glossary UID 1016; used widely in shipping/booking flows.                                                                |
| ktddecv:consignmentLoadingDate          | DatatypeProperty | ktddecv:Consignment or ktddecv:BillOfLading → xsd:date        | Glossary UID 2347 marked M for BoL.                                                                                      |
| ktddecv:estimatedTimeOfArrival          | DatatypeProperty | ktddecv:TransportMovement or BoL → xsd:dateTime               | Glossary UID 2349; align with existing planned/arrival date-time family.                                                 |
| ktddecv:uniqueConsignmentReference      | DatatypeProperty | ktddecv:Consignment → xsd:string (or Identifier)              | UNVTD UCR; common in customs/security contexts.                                                                          |
| ktddecv:grossVolume                     | DatatypeProperty | ktddecv:Consignment/GoodsItem/BoL → QuantitativeValue/Measure | Glossary UID 6322 is M for BoL, but no volume term detected.                                                             |
| ktddecv:containerSizeAndTypeCode        | DatatypeProperty | ktddecv:TransportEquipment → xsd:string (code)                | UNVTD `CharacteristicCode`; typically ISO 6346 size/type.                                                                |
| ktddecv:containerFullnessCode           | DatatypeProperty | ktddecv:TransportEquipment → xsd:string (code)                | UNVTD `FullnessCode` (full/empty/partly laden).                                                                          |
| ktddecv:consignmentSummaryDescription   | DatatypeProperty | ktddecv:Consignment/BoL → xsd:string                          | UNVTD summary description; distinct from goods description.                                                              |
| ktddecv:transportContractConditionsText | DatatypeProperty | ktddecv:BillOfLading → xsd:string                             | If `deliveryTermsText` is too narrow (Incoterms-oriented) for BoL contract terms.                                        |
| ktddecv:hsCode                          | DatatypeProperty | ktddecv:GoodsItem/Product → xsd:string (code)                 | UNVTD `ClassificationID`; consider aligning with existing product classification approach if present elsewhere in KTDDE. |
| ktddecv:transportMovementIdentifier     | DatatypeProperty | ktddecv:TransportMovement → xsd:string                        | UNVTD `TransportMovementID` is broader than voyage number.                                                               |