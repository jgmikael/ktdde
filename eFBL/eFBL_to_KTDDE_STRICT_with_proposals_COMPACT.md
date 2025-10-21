# eFBL → KTDDE OWL Mapping (STRICT; proposals flagged)
Only terms actually present in the uploaded KTDDE OWL are filled; others are flagged under **Proposal = Yes**.

<div style='font-size: 13px; line-height: 1.3em; white-space: normal;'>

Only terms actually present in the uploaded KTDDE OWL are filled; others are flagged under **Proposal=Yes**.

| eFBL Class | eFBL Element | Type | KTDDE Label | KTDDE URI | Range (if object) | Proposal |
|---|---|---|---|---|---|---|
| Supply Chain Consignment | — | class |  |  |  | Yes |
| Supply Chain Consignment | cargoInsuranceProvidedByCTO | datatype |  |  |  | Yes |
| Supply Chain Consignment | declaredValueForCarriageAmount | datatype |  |  |  | Yes |
| Supply Chain Consignment | insurancePolicyCompany | datatype |  |  |  | Yes |
| Supply Chain Consignment | insurancePolicyNumber | datatype | Insurance Policy Number | https://iri.suomi.fi/model/ktddecv/insurancePolicyNumber |  | No |
| Supply Chain Consignment | numberOfPackages | datatype |  |  |  | Yes |
| Supply Chain Consignment | totalChargeAmount | datatype |  |  |  | Yes |
| Supply Chain Consignment | applicableServiceCharge | object |  |  |  | Yes |
| Supply Chain Consignment | carrierAcceptanceLocation | object |  |  |  | Yes |
| Supply Chain Consignment | consignee | object | consignee party | https://iri.suomi.fi/model/ktddecv/consigneeParty |  | No |
| Supply Chain Consignment | consigneeReceiptLocation | object |  |  |  | Yes |
| Supply Chain Consignment | consignor | object | consignor party | https://iri.suomi.fi/model/ktddecv/consignorParty |  | No |
| Supply Chain Consignment | cto | object | carrier party | https://iri.suomi.fi/model/ktddecv/carrierParty |  | No |
| Supply Chain Consignment | ctoAgent | object |  |  |  | Yes |
| Supply Chain Consignment | handling | object | total transport handling unit quantity | https://iri.suomi.fi/model/ktddecv/totalTransportHandlingUnitQuantity |  | No |
| Supply Chain Consignment | includedConsignmentItem | object |  |  |  | Yes |
| Supply Chain Consignment | loadingBaseportLocation | object |  |  |  | Yes |
| Supply Chain Consignment | mainCarriageTransportMovement | object |  |  |  | Yes |
| Supply Chain Consignment | notifiedParty | object |  |  |  | Yes |
| Supply Chain Consignment | unloadingBaseportLocation | object |  |  |  | Yes |
| consignmentItem | — | class |  |  |  | Yes |
| consignmentItem | declaredValueForCarriageAmount | datatype |  |  |  | Yes |
| consignmentItem | goodsTypeCode | datatype |  |  |  | Yes |
| consignmentItem | grossVolume | datatype |  |  |  | Yes |
| consignmentItem | grossWeight | datatype | total gross weight | https://iri.suomi.fi/model/ktddecv/totalGrossWeight |  | No |
| consignmentItem | insuranceValueAmount | datatype | insurance value amount | https://iri.suomi.fi/model/ktddecv/insuranceValueAmount |  | No |
| consignmentItem | originTradeCountry | datatype |  |  |  | Yes |
| consignmentItem | associatedTransportEquipment | object |  |  |  | Yes |
| consignmentItem | cargoNatureIdentification | object |  |  |  | Yes |
| consignmentItem | transportDangerousGoods | object |  |  |  | Yes |
| consignmentItem | transportPackage | object |  |  |  | Yes |
| consignmentItem | usedTransportEquipment | object |  |  |  | Yes |
| governmentRegistration | — | class |  |  |  | Yes |
| governmentRegistration | countryCode | datatype | Country Code | https://iri.suomi.fi/model/ktddecv/countryCode |  | No |
| governmentRegistration | typeCode | datatype | event type code | https://iri.suomi.fi/model/ktddecv/eventTypeCode |  | No |
| governmentRegistration | id | object | has identifier | https://iri.suomi.fi/model/ktddecv/hasIdentifier |  | No |
| handling | — | class |  |  |  | Yes |
| handling | handlingInstructions | object |  |  |  | Yes |
| handlingInstruction | — | class |  |  |  | Yes |
| handlingInstruction | temperatureSetting.maximumValue | datatype |  |  |  | Yes |
| handlingInstruction | temperatureSetting.minimumValue | datatype |  |  |  | Yes |
| logisticsPackage | — | class |  |  |  | Yes |
| logisticsPackage | itemQuantity | datatype | total goods item quantity | https://iri.suomi.fi/model/ktddecv/totalGoodsItemQuantity |  | No |
| logisticsPackage | shippingMarks | datatype | Shipping Marks | https://iri.suomi.fi/model/ktddecv/shippingMarks |  | No |
| logisticsPackage | typeCode | datatype | event type code | https://iri.suomi.fi/model/ktddecv/eventTypeCode |  | No |
| logisticsPackage | typeText | datatype |  |  |  | Yes |
| logisticsTransportMeans | — | class |  |  |  | Yes |
| logisticsTransportMeans | id | datatype_or_identifier | IMO Ship ID | https://iri.suomi.fi/model/ktddecv/iMOShipID |  | No |
| logisticsTransportMeans | name | datatype | Name | https://iri.suomi.fi/model/ktddecv/name |  | No |
| logisticsTransportMeans | stageCode | datatype |  |  |  | Yes |
| logisticsTransportMeans | typeCode | datatype | event type code | https://iri.suomi.fi/model/ktddecv/eventTypeCode |  | No |
| logisticsTransportMeans | typeText | datatype |  |  |  | Yes |
| logisticsTransportMeans | voyageNumber | datatype_or_identifier | Voyage Number | https://iri.suomi.fi/model/ktddecv/voyageNumber |  | No |
| serviceCharge | — | class |  |  |  | Yes |
| serviceCharge | paymentArrangementCode | datatype |  |  |  | Yes |
| serviceCharge | paymentPlace | object |  |  |  | Yes |
| simpleTradeContact | — | class |  |  |  | Yes |
| simpleTradeContact | emailAddress | datatype |  |  |  | Yes |
| simpleTradeContact | mobileTelephone | datatype |  |  |  | Yes |
| simpleTradeContact | note | datatype | Note Number | https://iri.suomi.fi/model/ktddecv/noteNumber |  | No |
| simpleTradeContact | personName | datatype |  |  |  | Yes |
| simpleTradeContact | telephone | datatype |  |  |  | Yes |
| simpleTradeParty | — | class |  |  |  | Yes |
| simpleTradeParty | languageCode | datatype |  |  |  | Yes |
| simpleTradeParty | name | datatype | Name | https://iri.suomi.fi/model/ktddecv/name |  | No |
| simpleTradeParty | definedContactDetails | object |  |  |  | Yes |
| simpleTradeParty | governmentRegistration | object |  |  |  | Yes |
| simpleTradeParty | id | object | has identifier | https://iri.suomi.fi/model/ktddecv/hasIdentifier |  | No |
| simpleTradeParty | postalAddress | object |  |  |  | Yes |
| simpleTradeParty | taxRegistration | object |  |  |  | Yes |
| tradeAddress | — | class |  |  |  | Yes |
| tradeAddress | cityName | datatype |  |  |  | Yes |
| tradeAddress | countryCode | datatype | Country Code | https://iri.suomi.fi/model/ktddecv/countryCode |  | No |
| tradeAddress | countryName | datatype | Country Name | https://iri.suomi.fi/model/ktddecv/countryName |  | No |
| tradeAddress | countrySubDivisionName | datatype |  |  |  | Yes |
| tradeAddress | postcode | datatype | Post Code | https://iri.suomi.fi/model/ktddecv/postCode |  | No |
| tradeAddress | streetName | datatype |  |  |  | Yes |
| tradeAddress | id | object | has identifier | https://iri.suomi.fi/model/ktddecv/hasIdentifier |  | No |
| tradeContact | — | class |  |  |  | Yes |
| tradeContact | emailAddress | datatype |  |  |  | Yes |
| tradeContact | mobileTelephone | datatype |  |  |  | Yes |
| tradeContact | note | datatype | Note Number | https://iri.suomi.fi/model/ktddecv/noteNumber |  | No |
| tradeContact | personName | datatype |  |  |  | Yes |
| tradeContact | telephone | datatype |  |  |  | Yes |
| tradeParty | — | class |  |  |  | Yes |
| tradeParty | languageCode | datatype |  |  |  | Yes |
| tradeParty | name | datatype | Name | https://iri.suomi.fi/model/ktddecv/name |  | No |
| tradeParty | definedContactDetails | object |  |  |  | Yes |
| tradeParty | governmentRegistration | object |  |  |  | Yes |
| tradeParty | id | object | has identifier | https://iri.suomi.fi/model/ktddecv/hasIdentifier |  | No |
| tradeParty | postalAddress | object |  |  |  | Yes |
| tradeParty | taxRegistration | object |  |  |  | Yes |
| transportCargo | — | class |  |  |  | Yes |
| transportCargo | identificationText | datatype |  |  |  | Yes |
| transportCargo | typeCode | datatype | event type code | https://iri.suomi.fi/model/ktddecv/eventTypeCode |  | No |
| transportDangerousCode | — | class |  |  |  | Yes |
| transportDangerousCode | hazardClassificationId | datatype |  |  |  | Yes |
| transportDangerousCode | undgId | datatype |  |  |  | Yes |
| transportEquipment | — | class | Transport Equipment | https://iri.suomi.fi/model/ktddecv/TransportEquipment |  | No |
| transportEquipment | id | datatype_or_identifier | IMO Ship ID | https://iri.suomi.fi/model/ktddecv/iMOShipID |  | No |
| transportEquipment | sealQuantity | datatype |  |  |  | Yes |
| transportEquipment | tareWeight | datatype |  |  |  | Yes |
| transportEquipment | affixedSeal | object |  |  |  | Yes |

</div>
