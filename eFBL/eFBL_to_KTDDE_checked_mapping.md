# eFBL → KTDDE OWL Mapping (Checked Against Uploaded RDF)
_Status column shows EXACT/CLOSE, WEAK, or PROPOSAL (not found in RDF)._ 

| eFBL Class | eFBL Element | Type | KTDDE Match Label | KTDDE URI | Match | Notes |
|---|---|---|---|---|---|---|
| Supply Chain Consignment | — | class | Consignment | https://iri.suomi.fi/model/ktddecv/Consignment | EXACT/CLOSE |  |
| Supply Chain Consignment | cargoInsuranceProvidedByCTO | datatype | **PROPOSAL** cargoInsuranceProvidedByCTO | https://iri.suomi.fi/model/ktddecv/cargoInsuranceProvidedByCTO | PROPOSAL |  |
| Supply Chain Consignment | declaredValueForCarriageAmount | datatype | **PROPOSAL** declaredValueForCarriageAmount | https://iri.suomi.fi/model/ktddecv/declaredValueForCarriageAmount | PROPOSAL |  |
| Supply Chain Consignment | insurancePolicyCompany | datatype | **PROPOSAL** insurancePolicyCompany | https://iri.suomi.fi/model/ktddecv/insurancePolicyCompany | PROPOSAL |  |
| Supply Chain Consignment | insurancePolicyNumber | datatype | Insurance Policy Number | https://iri.suomi.fi/model/ktddecv/insurancePolicyNumber | EXACT/CLOSE |  |
| Supply Chain Consignment | numberOfPackages | datatype | **PROPOSAL** numberOfPackages | https://iri.suomi.fi/model/ktddecv/numberOfPackages | PROPOSAL |  |
| Supply Chain Consignment | totalChargeAmount | datatype | **PROPOSAL** totalChargeAmount | https://iri.suomi.fi/model/ktddecv/totalChargeAmount | PROPOSAL |  |
| Supply Chain Consignment | applicableServiceCharge | object | **PROPOSAL** applicableServiceCharge | https://iri.suomi.fi/model/ktddecv/applicableServiceCharge | PROPOSAL | Range hint: serviceCharge[] |
| Supply Chain Consignment | carrierAcceptanceLocation | object | **PROPOSAL** carrierAcceptanceLocation | https://iri.suomi.fi/model/ktddecv/carrierAcceptanceLocation | PROPOSAL | Range hint: logistics-location |
| Supply Chain Consignment | consignee | object | consignee party | https://iri.suomi.fi/model/ktddecv/consigneeParty | EXACT/CLOSE | Range hint: simpleTradeParty |
| Supply Chain Consignment | consigneeReceiptLocation | object | **PROPOSAL** consigneeReceiptLocation | https://iri.suomi.fi/model/ktddecv/consigneeReceiptLocation | PROPOSAL | Range hint: logistics-location |
| Supply Chain Consignment | consignor | object | consignor party | https://iri.suomi.fi/model/ktddecv/consignorParty | EXACT/CLOSE | Range hint: tradeParty |
| Supply Chain Consignment | cto | object | Multiplier Factor Percent | https://iri.suomi.fi/model/ktddecv/multiplierFactorPercent | EXACT/CLOSE | Range hint: tradeParty |
| Supply Chain Consignment | ctoAgent | object | **PROPOSAL** ctoAgent | https://iri.suomi.fi/model/ktddecv/ctoAgent | PROPOSAL | Range hint: simpleTradeParty |
| Supply Chain Consignment | handling | object | total transport handling unit quantity | https://iri.suomi.fi/model/ktddecv/totalTransportHandlingUnitQuantity | EXACT/CLOSE | Range hint: handling |
| Supply Chain Consignment | includedConsignmentItem | object | **PROPOSAL** includedConsignmentItem | https://iri.suomi.fi/model/ktddecv/includedConsignmentItem | PROPOSAL | Range hint: consignmentItem[] |
| Supply Chain Consignment | loadingBaseportLocation | object | **PROPOSAL** loadingBaseportLocation | https://iri.suomi.fi/model/ktddecv/loadingBaseportLocation | PROPOSAL | Range hint: logistics-location |
| Supply Chain Consignment | mainCarriageTransportMovement | object | **PROPOSAL** mainCarriageTransportMovement | https://iri.suomi.fi/model/ktddecv/mainCarriageTransportMovement | PROPOSAL | Range hint: logisticsTransportMeans |
| Supply Chain Consignment | notifiedParty | object | **PROPOSAL** notifiedParty | https://iri.suomi.fi/model/ktddecv/notifiedParty | PROPOSAL | Range hint: simpleTradeParty[] |
| Supply Chain Consignment | unloadingBaseportLocation | object | **PROPOSAL** unloadingBaseportLocation | https://iri.suomi.fi/model/ktddecv/unloadingBaseportLocation | PROPOSAL | Range hint: logistics-location |
| consignmentItem | — | class | **PROPOSAL** consignmentItem | https://iri.suomi.fi/model/ktddecv/Consignmentitem | PROPOSAL | No class with a reasonably close label found in KTDDE OWL. |
| consignmentItem | declaredValueForCarriageAmount | datatype | **PROPOSAL** declaredValueForCarriageAmount | https://iri.suomi.fi/model/ktddecv/declaredValueForCarriageAmount | PROPOSAL |  |
| consignmentItem | goodsTypeCode | datatype | **PROPOSAL** goodsTypeCode | https://iri.suomi.fi/model/ktddecv/goodsTypeCode | PROPOSAL |  |
| consignmentItem | grossVolume | datatype | **PROPOSAL** grossVolume | https://iri.suomi.fi/model/ktddecv/grossVolume | PROPOSAL |  |
| consignmentItem | grossWeight | datatype | total gross weight | https://iri.suomi.fi/model/ktddecv/totalGrossWeight | WEAK |  |
| consignmentItem | insuranceValueAmount | datatype | insurance value amount | https://iri.suomi.fi/model/ktddecv/insuranceValueAmount | WEAK |  |
| consignmentItem | originTradeCountry | datatype | **PROPOSAL** originTradeCountry | https://iri.suomi.fi/model/ktddecv/originTradeCountry | PROPOSAL |  |
| consignmentItem | associatedTransportEquipment | object | **PROPOSAL** associatedTransportEquipment | https://iri.suomi.fi/model/ktddecv/associatedTransportEquipment | PROPOSAL | Range hint: transportEquipment[] |
| consignmentItem | cargoNatureIdentification | object | **PROPOSAL** cargoNatureIdentification | https://iri.suomi.fi/model/ktddecv/cargoNatureIdentification | PROPOSAL | Range hint: transportCargo |
| consignmentItem | transportDangerousGoods | object | **PROPOSAL** transportDangerousGoods | https://iri.suomi.fi/model/ktddecv/transportDangerousGoods | PROPOSAL | Range hint: transportDangerousCode[] |
| consignmentItem | transportPackage | object | **PROPOSAL** transportPackage | https://iri.suomi.fi/model/ktddecv/transportPackage | PROPOSAL | Range hint: logisticsPackage[] |
| consignmentItem | usedTransportEquipment | object | **PROPOSAL** usedTransportEquipment | https://iri.suomi.fi/model/ktddecv/usedTransportEquipment | PROPOSAL | Range hint: transportEquipment[] |
| governmentRegistration | — | class | **PROPOSAL** governmentRegistration | https://iri.suomi.fi/model/ktddecv/Governmentregistration | PROPOSAL | No class with a reasonably close label found in KTDDE OWL. |
| governmentRegistration | countryCode | datatype | Country Code | https://iri.suomi.fi/model/ktddecv/countryCode | EXACT/CLOSE |  |
| governmentRegistration | typeCode | datatype | Delivery Type Code | https://iri.suomi.fi/model/ktddecv/deliveryTypeCode | EXACT/CLOSE |  |
| governmentRegistration | id | object | consignment identifier | https://iri.suomi.fi/model/ktddecv/consignmentIdentifier | EXACT/CLOSE | Range hint: Identifier |
| handling | — | class | Handling Information | https://iri.suomi.fi/model/ktddecv/handlingInformation | EXACT/CLOSE |  |
| handling | handlingInstructions | object | **PROPOSAL** handlingInstructions | https://iri.suomi.fi/model/ktddecv/handlingInstructions | PROPOSAL | Range hint: handlingInstruction[] |
| handlingInstruction | — | class | **PROPOSAL** handlingInstruction | https://iri.suomi.fi/model/ktddecv/Handlinginstruction | PROPOSAL | No class with a reasonably close label found in KTDDE OWL. |
| handlingInstruction | temperatureSetting.maximumValue | datatype | **PROPOSAL** temperatureSetting.maximumValue | https://iri.suomi.fi/model/ktddecv/temperatureSettingmaximumValue | PROPOSAL |  |
| handlingInstruction | temperatureSetting.minimumValue | datatype | **PROPOSAL** temperatureSetting.minimumValue | https://iri.suomi.fi/model/ktddecv/temperatureSettingminimumValue | PROPOSAL |  |
| logisticsPackage | — | class | **PROPOSAL** logisticsPackage | https://iri.suomi.fi/model/ktddecv/Logisticspackage | PROPOSAL | No class with a reasonably close label found in KTDDE OWL. |
| logisticsPackage | itemQuantity | datatype | total goods item quantity | https://iri.suomi.fi/model/ktddecv/totalGoodsItemQuantity | WEAK |  |
| logisticsPackage | shippingMarks | datatype | Shipping Marks | https://iri.suomi.fi/model/ktddecv/shippingMarks | EXACT/CLOSE |  |
| logisticsPackage | typeCode | datatype | Delivery Type Code | https://iri.suomi.fi/model/ktddecv/deliveryTypeCode | EXACT/CLOSE |  |
| logisticsPackage | typeText | datatype | **PROPOSAL** typeText | https://iri.suomi.fi/model/ktddecv/typeText | PROPOSAL |  |
| logisticsTransportMeans | — | class | **PROPOSAL** logisticsTransportMeans | https://iri.suomi.fi/model/ktddecv/Logisticstransportmeans | PROPOSAL | No class with a reasonably close label found in KTDDE OWL. |
| logisticsTransportMeans | id | datatype_or_identifier | Bank Account Identifier | https://iri.suomi.fi/model/ktddecv/bankAccountIdentifier | EXACT/CLOSE |  |
| logisticsTransportMeans | name | datatype | Alternate Name | https://iri.suomi.fi/model/ktddecv/alternateName | EXACT/CLOSE |  |
| logisticsTransportMeans | stageCode | datatype | **PROPOSAL** stageCode | https://iri.suomi.fi/model/ktddecv/stageCode | PROPOSAL |  |
| logisticsTransportMeans | typeCode | datatype | Delivery Type Code | https://iri.suomi.fi/model/ktddecv/deliveryTypeCode | EXACT/CLOSE |  |
| logisticsTransportMeans | typeText | datatype | **PROPOSAL** typeText | https://iri.suomi.fi/model/ktddecv/typeText | PROPOSAL |  |
| logisticsTransportMeans | voyageNumber | datatype_or_identifier | Voyage Number | https://iri.suomi.fi/model/ktddecv/voyageNumber | EXACT/CLOSE |  |
| serviceCharge | — | class | **PROPOSAL** serviceCharge | https://iri.suomi.fi/model/ktddecv/Servicecharge | PROPOSAL | No class with a reasonably close label found in KTDDE OWL. |
| serviceCharge | paymentArrangementCode | datatype | **PROPOSAL** paymentArrangementCode | https://iri.suomi.fi/model/ktddecv/paymentArrangementCode | PROPOSAL |  |
| serviceCharge | paymentPlace | object | **PROPOSAL** paymentPlace | https://iri.suomi.fi/model/ktddecv/paymentPlace | PROPOSAL | Range hint: logistics-location |
| simpleTradeContact | — | class | **PROPOSAL** simpleTradeContact | https://iri.suomi.fi/model/ktddecv/Simpletradecontact | PROPOSAL | No class with a reasonably close label found in KTDDE OWL. |
| simpleTradeContact | emailAddress | datatype | **PROPOSAL** emailAddress | https://iri.suomi.fi/model/ktddecv/emailAddress | PROPOSAL |  |
| simpleTradeContact | mobileTelephone | datatype | **PROPOSAL** mobileTelephone | https://iri.suomi.fi/model/ktddecv/mobileTelephone | PROPOSAL |  |
| simpleTradeContact | note | datatype | Event Note Text | https://iri.suomi.fi/model/ktddecv/eventNoteText | EXACT/CLOSE |  |
| simpleTradeContact | personName | datatype | **PROPOSAL** personName | https://iri.suomi.fi/model/ktddecv/personName | PROPOSAL |  |
| simpleTradeContact | telephone | datatype | **PROPOSAL** telephone | https://iri.suomi.fi/model/ktddecv/telephone | PROPOSAL |  |
| simpleTradeParty | — | class | **PROPOSAL** simpleTradeParty | https://iri.suomi.fi/model/ktddecv/Simpletradeparty | PROPOSAL | No class with a reasonably close label found in KTDDE OWL. |
| simpleTradeParty | languageCode | datatype | **PROPOSAL** languageCode | https://iri.suomi.fi/model/ktddecv/languageCode | PROPOSAL |  |
| simpleTradeParty | name | datatype | Alternate Name | https://iri.suomi.fi/model/ktddecv/alternateName | EXACT/CLOSE |  |
| simpleTradeParty | definedContactDetails | object | **PROPOSAL** definedContactDetails | https://iri.suomi.fi/model/ktddecv/definedContactDetails | PROPOSAL | Range hint: simpleTradeContact |
| simpleTradeParty | governmentRegistration | object | **PROPOSAL** governmentRegistration | https://iri.suomi.fi/model/ktddecv/governmentRegistration | PROPOSAL | Range hint: governmentRegistration[] |
| simpleTradeParty | id | object | consignment identifier | https://iri.suomi.fi/model/ktddecv/consignmentIdentifier | EXACT/CLOSE | Range hint: Identifier[] |
| simpleTradeParty | postalAddress | object | Postal Address | https://iri.suomi.fi/model/ktddecv/PostalAddress | WEAK | Range hint: tradeAddress |
| simpleTradeParty | taxRegistration | object | **PROPOSAL** taxRegistration | https://iri.suomi.fi/model/ktddecv/taxRegistration | PROPOSAL | Range hint: Identifier[] |
| tradeAddress | — | class | **PROPOSAL** tradeAddress | https://iri.suomi.fi/model/ktddecv/Tradeaddress | PROPOSAL | No class with a reasonably close label found in KTDDE OWL. |
| tradeAddress | cityName | datatype | **PROPOSAL** cityName | https://iri.suomi.fi/model/ktddecv/cityName | PROPOSAL |  |
| tradeAddress | countryCode | datatype | Country Code | https://iri.suomi.fi/model/ktddecv/countryCode | EXACT/CLOSE |  |
| tradeAddress | countryName | datatype | Country Name | https://iri.suomi.fi/model/ktddecv/countryName | EXACT/CLOSE |  |
| tradeAddress | countrySubDivisionName | datatype | **PROPOSAL** countrySubDivisionName | https://iri.suomi.fi/model/ktddecv/countrySubDivisionName | PROPOSAL |  |
| tradeAddress | postcode | datatype | Post Code | https://iri.suomi.fi/model/ktddecv/postCode | EXACT/CLOSE |  |
| tradeAddress | streetName | datatype | **PROPOSAL** streetName | https://iri.suomi.fi/model/ktddecv/streetName | PROPOSAL |  |
| tradeAddress | id | object | consignment identifier | https://iri.suomi.fi/model/ktddecv/consignmentIdentifier | EXACT/CLOSE | Range hint: Identifier |
| tradeContact | — | class | **PROPOSAL** tradeContact | https://iri.suomi.fi/model/ktddecv/Tradecontact | PROPOSAL | No class with a reasonably close label found in KTDDE OWL. |
| tradeContact | emailAddress | datatype | **PROPOSAL** emailAddress | https://iri.suomi.fi/model/ktddecv/emailAddress | PROPOSAL |  |
| tradeContact | mobileTelephone | datatype | **PROPOSAL** mobileTelephone | https://iri.suomi.fi/model/ktddecv/mobileTelephone | PROPOSAL |  |
| tradeContact | note | datatype | Event Note Text | https://iri.suomi.fi/model/ktddecv/eventNoteText | EXACT/CLOSE |  |
| tradeContact | personName | datatype | **PROPOSAL** personName | https://iri.suomi.fi/model/ktddecv/personName | PROPOSAL |  |
| tradeContact | telephone | datatype | **PROPOSAL** telephone | https://iri.suomi.fi/model/ktddecv/telephone | PROPOSAL |  |
| tradeParty | — | class | **PROPOSAL** tradeParty | https://iri.suomi.fi/model/ktddecv/Tradeparty | PROPOSAL | No class with a reasonably close label found in KTDDE OWL. |
| tradeParty | languageCode | datatype | **PROPOSAL** languageCode | https://iri.suomi.fi/model/ktddecv/languageCode | PROPOSAL |  |
| tradeParty | name | datatype | Alternate Name | https://iri.suomi.fi/model/ktddecv/alternateName | EXACT/CLOSE |  |
| tradeParty | definedContactDetails | object | **PROPOSAL** definedContactDetails | https://iri.suomi.fi/model/ktddecv/definedContactDetails | PROPOSAL | Range hint: tradeContact |
| tradeParty | governmentRegistration | object | **PROPOSAL** governmentRegistration | https://iri.suomi.fi/model/ktddecv/governmentRegistration | PROPOSAL | Range hint: governmentRegistration[] |
| tradeParty | id | object | consignment identifier | https://iri.suomi.fi/model/ktddecv/consignmentIdentifier | EXACT/CLOSE | Range hint: Identifier[] |
| tradeParty | postalAddress | object | Postal Address | https://iri.suomi.fi/model/ktddecv/PostalAddress | WEAK | Range hint: tradeAddress |
| tradeParty | taxRegistration | object | **PROPOSAL** taxRegistration | https://iri.suomi.fi/model/ktddecv/taxRegistration | PROPOSAL | Range hint: Identifier[] |
| transportCargo | — | class | **PROPOSAL** transportCargo | https://iri.suomi.fi/model/ktddecv/Transportcargo | PROPOSAL | No class with a reasonably close label found in KTDDE OWL. |
| transportCargo | identificationText | datatype | **PROPOSAL** identificationText | https://iri.suomi.fi/model/ktddecv/identificationText | PROPOSAL |  |
| transportCargo | typeCode | datatype | Delivery Type Code | https://iri.suomi.fi/model/ktddecv/deliveryTypeCode | EXACT/CLOSE |  |
| transportDangerousCode | — | class | **PROPOSAL** transportDangerousCode | https://iri.suomi.fi/model/ktddecv/Transportdangerouscode | PROPOSAL | No class with a reasonably close label found in KTDDE OWL. |
| transportDangerousCode | hazardClassificationId | datatype | **PROPOSAL** hazardClassificationId | https://iri.suomi.fi/model/ktddecv/hazardClassificationId | PROPOSAL |  |
| transportDangerousCode | undgId | datatype | **PROPOSAL** undgId | https://iri.suomi.fi/model/ktddecv/undgId | PROPOSAL |  |
| transportEquipment | — | class | Transport Equipment | https://iri.suomi.fi/model/ktddecv/TransportEquipment | EXACT/CLOSE |  |
| transportEquipment | id | datatype_or_identifier | Bank Account Identifier | https://iri.suomi.fi/model/ktddecv/bankAccountIdentifier | EXACT/CLOSE |  |
| transportEquipment | sealQuantity | datatype | **PROPOSAL** sealQuantity | https://iri.suomi.fi/model/ktddecv/sealQuantity | PROPOSAL |  |
| transportEquipment | tareWeight | datatype | **PROPOSAL** tareWeight | https://iri.suomi.fi/model/ktddecv/tareWeight | PROPOSAL |  |
| transportEquipment | affixedSeal | object | **PROPOSAL** affixedSeal | https://iri.suomi.fi/model/ktddecv/affixedSeal | PROPOSAL | Range hint: Identifier[] |
