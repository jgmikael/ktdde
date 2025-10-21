
# eFBL → KTDDE OWL Mapping (Complete, Human-Readable)

Each row aligns one **eFBL JSON element** with its **closest KTDDE OWL equivalent**.  
Columns are kept narrow for horizontal readability (no long URIs, only prefixed names).  
Terms not found in the KTDDE ontology are marked **Proposal**.

| eFBL Element | Type | KTDDE Equivalent | Range / Notes | Confidence |
|:--|:--|:--|:--|:--|
| **Supply Chain Consignment** | class | ktddecv:Consignment | Root consignment | Strong |
| totalChargeAmount | datatype | ktddecv:totalChargeAmount | Monetary amount | Strong |
| cargoInsuranceProvidedByCTO | datatype | Proposal: insuranceIndicator | Boolean indicator | Proposal |
| insurancePolicyNumber | datatype | Proposal: insurancePolicyIdentifier | Identifier | Proposal |
| insurancePolicyCompany | datatype | Proposal: insuranceProviderName | Text or Party link | Proposal |
| numberOfPackages | datatype | ktddecv:numberOfPackages | Integer | Strong |
| declaredValueForCarriageAmount | datatype | ktddecv:declaredValueForCarriage | Monetary amount | Strong |
| consignor | object | ktddecv:consignorParty | Party | Strong |
| consignee | object | ktddecv:consigneeParty | Party | Strong |
| ctoAgent | object | ktddecv:agentParty | Party | Strong |
| cto | object | ktddecv:carrierParty | Party | Strong |
| notifiedParty | object | ktddecv:notifiedParty | Party (array) | Strong |
| carrierAcceptanceLocation | object | ktddecv:placeOfReceipt | Location | Strong |
| consigneeReceiptLocation | object | ktddecv:placeOfDelivery | Location | Strong |
| loadingBaseportLocation | object | ktddecv:portOfLoading | Location | Strong |
| unloadingBaseportLocation | object | ktddecv:portOfDischarge | Location | Strong |
| includedConsignmentItem | object | ktddecv:consignmentItem | ConsignmentItem (array) | Strong |
| mainCarriageTransportMovement | object | ktddecv:mainCarriageTransportMovement | TransportMovement | Strong |
| applicableServiceCharge | object | ktddecv:applicableServiceCharge | ServiceCharge (array) | Strong |
| handling | object | ktddecv:handling | Handling | Strong |
| **Party (tradeParty/simpleTradeParty)** | class | ktddecv:Party | — | Strong |
| id | object | ktddecv:hasIdentifier | Identifier | Strong |
| name | datatype | ktddecv:legalName | Text | Strong |
| languageCode | datatype | Proposal: languageCode | Code | Proposal |
| definedContactDetails | object | ktddecv:hasContactPoint | ContactPoint | Strong |
| postalAddress | object | ktddecv:postalAddress | Address | Strong |
| taxRegistration | object | Proposal: taxIdentifier | Identifier | Proposal |
| governmentRegistration | object | Proposal: governmentRegistration | GovernmentRegistration | Proposal |
| **ContactPoint (tradeContact)** | class | ktddecv:ContactPoint | — | Strong |
| personName | datatype | ktddecv:personName | Text | Strong |
| telephone | datatype | ktddecv:telephone | Text | Strong |
| mobileTelephone | datatype | Proposal: mobileTelephone | Text | Proposal |
| emailAddress | datatype | ktddecv:email | Text/URI | Strong |
| note | datatype | Proposal: note | Text | Proposal |
| **Address (tradeAddress)** | class | ktddecv:Address | — | Strong |
| postcode | datatype | ktddecv:postcode | Text | Strong |
| streetName | datatype | ktddecv:streetAddress | Text | Strong |
| cityName | datatype | ktddecv:addressLocality | Text | Strong |
| countryCode | datatype | ktddecv:addressCountry | Code | Strong |
| countryName | datatype | Proposal: countryName | Text | Proposal |
| countrySubDivisionName | datatype | Proposal: addressRegion | Text | Proposal |
| **ConsignmentItem** | class | ktddecv:ConsignmentItem | — | Strong |
| goodsTypeCode | datatype | ktddecv:goodsTypeCode | Code | Strong |
| declaredValueForCarriageAmount | datatype | ktddecv:declaredValueForCarriage | Monetary amount | Strong |
| insuranceValueAmount | datatype | ktddecv:insuranceValueAmount | Monetary amount | Strong |
| grossWeight | datatype | ktddecv:grossWeight | Measure | Strong |
| grossVolume | datatype | ktddecv:grossVolume | Measure | Strong |
| originTradeCountry | datatype | ktddecv:originCountry | Code | Strong |
| cargoNatureIdentification | object | Proposal: goodsDescription | Text | Proposal |
| transportDangerousGoods | object | ktddecv:dangerousGoodsInformation | DangerousGoodsInformation (array) | Strong |
| associatedTransportEquipment | object | ktddecv:associatedTransportEquipment | TransportEquipment | Strong |
| transportPackage | object | ktddecv:transportPackage | Package | Strong |
| usedTransportEquipment | object | Proposal: usedTransportEquipment | TransportEquipment | Proposal |
| **DangerousGoodsInformation (transportDangerousCode)** | class | ktddecv:DangerousGoodsInformation | — | Strong |
| undgId | datatype | ktddecv:undgCode | UNDG code | Strong |
| hazardClassificationId | datatype | ktddecv:hazardClassCode | Hazard class | Strong |
| **Package (logisticsPackage)** | class | ktddecv:Package | — | Strong |
| itemQuantity | datatype | ktddecv:itemQuantity | Quantity | Strong |
| typeCode | datatype | ktddecv:packageTypeCode | Code | Strong |
| typeText | datatype | Proposal: packageTypeText | Text | Proposal |
| shippingMarks | datatype | ktddecv:shippingMarks | Text | Strong |
| **TransportMeans (logisticsTransportMeans)** | class | ktddecv:TransportMeans | — | Strong |
| typeCode | datatype | Proposal: transportMeansTypeCode | Code | Proposal |
| typeText | datatype | ktddecv:transportMeansTypeText | Text | Strong |
| id | datatype | ktddecv:transportMeansIdentifier | Identifier (e.g., IMO) | Strong |
| name | datatype | ktddecv:transportMeansName | Text | Strong |
| voyageNumber | datatype | ktddecv:voyageIdentifier | Identifier | Strong |
| stageCode | datatype | Proposal: stageCode | Code | Proposal |
| **ServiceCharge** | class | ktddecv:ServiceCharge | — | Strong |
| paymentArrangementCode | datatype | ktddecv:paymentArrangementCode | UNCL 4237 | Strong |
| paymentPlace | object | ktddecv:paymentPlace | Location | Strong |
| **TransportEquipment** | class | ktddecv:TransportEquipment | — | Strong |
| id | datatype | ktddecv:equipmentIdentifier | Identifier | Strong |
| sealQuantity | datatype | — | — | Proposal |
| affixedSeal | object | — | Identifier (array) | Proposal |
| tareWeight | datatype | — | Measure | Proposal |
| **HandlingInstruction / Handling** | class | ktddecv:HandlingInstruction / ktddecv:Handling | — | Strong |
| temperatureSetting.minimumValue | datatype | Proposal: minimumValue | Measure | Proposal |
| temperatureSetting.maximumValue | datatype | Proposal: maximumValue | Measure | Proposal |
| handlingInstructions | object | ktddecv:handlingInstructions | HandlingInstruction (array) | Strong |
