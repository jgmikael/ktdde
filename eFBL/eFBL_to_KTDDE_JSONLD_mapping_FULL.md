# Full Coverage Mapping: eFBL JSON Schema → KTDDE JSON‑LD Example
Each row maps **one** eFBL schema element to the **equivalent element** in the realistic KTDDE JSON‑LD example. Elements not present in the instance are marked **NPE**.

| eFBL JSON (schema element) | KTDDE JSON‑LD example (instance) |
|---|---|
| ```json
Supply Chain Consignment (root)
``` | ```json
{
  "id": "urn:uuid:9f2bc09a-b0ab-4c7a-8b36-4f7b3a6e2db7",
  "type": "Consignment"
}
``` |
| ```json
totalChargeAmount
``` | ```json
"totalChargeAmount": { "type": "MonetaryAmount", "value": 4850.00, "currency": "EUR" }
``` |
| ```json
cargoInsuranceProvidedByCTO
``` | Not present in the JSON‑LD example (NPE) |
| ```json
insurancePolicyNumber
``` | Not present in the JSON‑LD example (NPE) |
| ```json
insurancePolicyCompany
``` | Not present in the JSON‑LD example (NPE) |
| ```json
numberOfPackages
``` | ```json
"numberOfPackages": 20
``` |
| ```json
declaredValueForCarriageAmount
``` | ```json
"declaredValueForCarriage": { "type": "MonetaryAmount", "value": 125000.00, "currency": "EUR" }
``` |
| ```json
consignor
``` | ```json
"consignor": {
  "type": "Party",
  "legalName": "Stora Enso Wood Products Oy Ltd",
  "hasIdentifier": [
    { "type": "Identifier", "identifierValue": "FI1234567-8", "identifierScheme": "EORI", "identifierSchemeAgency": "EU" },
    { "type": "Identifier", "identifierValue": "549300JKU1X2G8Q1P957", "identifierScheme": "LEI", "identifierSchemeAgency": "GLEIF" }
  ],
  "postalAddress": { "type": "Address", "streetAddress": "Kanavaranta 1", "addressLocality": "Helsinki", "postcode": "00160", "addressCountry": "FI" },
  "hasContactPoint": { "type": "ContactPoint", "personName": "Aino Laine", "telephone": "+358 10 111 2222", "email": "shipping@storaenso.com" }
}
``` |
| ```json
consignee
``` | ```json
"consignee": {
  "type": "Party",
  "legalName": "Yamato Trading Co., Ltd.",
  "hasIdentifier": [{ "type": "Identifier", "identifierValue": "JP1234567890123", "identifierScheme": "CorporateNumber", "identifierSchemeAgency": "JP NTA" }],
  "postalAddress": { "type": "Address", "streetAddress": "3-1-1 Marunouchi, Chiyoda-ku", "addressLocality": "Tokyo", "postcode": "100-0005", "addressCountry": "JP" },
  "hasContactPoint": { "type": "ContactPoint", "personName": "Kenji Sato", "telephone": "+81 3 1234 5678", "email": "imports@yamato-trading.jp" }
}
``` |
| ```json
ctoAgent
``` | ```json
"agentParty": {
  "type": "Party",
  "legalName": "Maersk Finland Oy",
  "hasContactPoint": { "type": "ContactPoint", "personName": "Agent Desk", "telephone": "+358 9 123 4567", "email": "hel.ops@maersk.com" }
}
``` |
| ```json
cto
``` | ```json
"carrierParty": {
  "type": "Party",
  "legalName": "A.P. Møller – Mærsk A/S",
  "hasIdentifier": [
    { "type": "Identifier", "identifierValue": "MAEU", "identifierScheme": "SCAC", "identifierSchemeAgency": "NMFTA" },
    { "type": "Identifier", "identifierValue": "5493001KJTIIGC8Y1R12", "identifierScheme": "LEI", "identifierSchemeAgency": "GLEIF" }
  ]
}
``` |
| ```json
notifiedParty (array)
``` | ```json
"notifiedParty": [{
  "type": "Party",
  "legalName": "Nihon Logistics K.K.",
  "hasContactPoint": { "type": "ContactPoint", "personName": "Mika Tanaka", "telephone": "+81 45 987 6543", "email": "ops@ylog.jp" }
}]
``` |
| ```json
carrierAcceptanceLocation
``` | ```json
"placeOfReceipt": { "type": "Location", "locationName": "Vantaa, FI", "countryCode": "FI" }
``` |
| ```json
consigneeReceiptLocation
``` | ```json
"placeOfDelivery": { "type": "Location", "locationName": "Yokohama, JP", "countryCode": "JP" }
``` |
| ```json
loadingBaseportLocation
``` | ```json
"portOfLoading": { "type": "Location", "unLocode": { "type": "Code", "codeValue": "FIHEL" }, "locationName": "Helsinki" }
``` |
| ```json
unloadingBaseportLocation
``` | ```json
"portOfDischarge": { "type": "Location", "unLocode": { "type": "Code", "codeValue": "JPYOK" }, "locationName": "Yokohama" }
``` |
| ```json
includedConsignmentItem (array of consignmentItem)
``` | ```json
"consignmentItem": [ { "...": "see below per item properties" } ]
``` |
| ```json
mainCarriageTransportMovement
``` | ```json
"mainCarriageTransportMovement": {
  "type": "TransportMovement",
  "transportMeans": {
    "type": "TransportMeans",
    "transportMeansTypeText": "Sea (container ship)",
    "transportMeansId": { "type": "Identifier", "identifierValue": "9321483", "identifierScheme": "IMO", "identifierSchemeAgency": "IMO" },
    "transportMeansName": "MAERSK EDITH",
    "voyageNumber": { "type": "Identifier", "identifierValue": "ME123W", "identifierScheme": "VoyageNumber", "identifierSchemeAgency": "Carrier" },
    "stageCode": { "type": "Code", "codeValue": "M" }
  }
}
``` |
| ```json
applicableServiceCharge (array of serviceCharge)
``` | ```json
"applicableServiceCharge": [{
  "type": "ServiceCharge",
  "paymentArrangementCode": { "type": "Code", "codeValue": "PP" },
  "paymentPlace": { "type": "Location", "locationName": "Helsinki", "unLocode": { "type": "Code", "codeValue": "FIHEL" } }
}]
``` |
| ```json
handling
``` | ```json
"handling": {
  "type": "Handling",
  "handlingInstructions": [{
    "type": "HandlingInstruction",
    "temperatureSetting": {
      "minimumValue": { "type": "Measure", "value": 5, "unitCode": "CEL" },
      "maximumValue": { "type": "Measure", "value": 25, "unitCode": "CEL" }
    }
  },
  { "type": "HandlingInstruction", "ktddecv:instructionText": "Keep dry. Protect from direct rain and sea spray." }]
}
``` |
| ```json
$defs.tradeParty.id (array of standardized-identifier)
``` | ```json
Within Party.hasIdentifier entries, e.g. LEI / SCAC identifiers.
``` |
| ```json
$defs.tradeParty.name
``` | ```json
Party.legalName (e.g., "Stora Enso Wood Products Oy Ltd")
``` |
| ```json
$defs.tradeParty.languageCode
``` | Not present in the JSON‑LD example (NPE) |
| ```json
$defs.tradeParty.definedContactDetails ($defs.tradeContact)
``` | ```json
Party.hasContactPoint → ContactPoint (personName, telephone, email)
``` |
| ```json
$defs.tradeParty.postalAddress ($defs.tradeAddress)
``` | ```json
Party.postalAddress → Address (streetAddress, addressLocality, postcode, addressCountry)
``` |
| ```json
$defs.tradeParty.taxRegistration (array standardized-identifier)
``` | Not present in the JSON‑LD example (NPE) |
| ```json
$defs.tradeParty.governmentRegistration (array $defs.governmentRegistration)
``` | Not present in the JSON‑LD example (NPE) |
| ```json
$defs.simpleTradeParty.*
``` | ```json
Mapped identically to Party (reduced fields as needed).
``` |
| ```json
$defs.tradeContact.personName
``` | ```json
ContactPoint.personName
``` |
| ```json
$defs.tradeContact.telephone
``` | ```json
ContactPoint.telephone
``` |
| ```json
$defs.tradeContact.mobileTelephone
``` | Not present in the JSON‑LD example (NPE) |
| ```json
$defs.tradeContact.emailAddress
``` | ```json
ContactPoint.email
``` |
| ```json
$defs.tradeContact.note (array of text)
``` | Not present in the JSON‑LD example (NPE) |
| ```json
$defs.tradeAddress.id (standardized-identifier)
``` | Not present in the JSON‑LD example (NPE) |
| ```json
$defs.tradeAddress.postcode
``` | ```json
Address.postcode
``` |
| ```json
$defs.tradeAddress.streetName
``` | ```json
Address.streetAddress
``` |
| ```json
$defs.tradeAddress.cityName
``` | ```json
Address.addressLocality
``` |
| ```json
$defs.tradeAddress.countryCode
``` | ```json
Address.addressCountry
``` |
| ```json
$defs.tradeAddress.countryName
``` | Not present in the JSON‑LD example (NPE) |
| ```json
$defs.tradeAddress.countrySubDivisionName
``` | Not present in the JSON‑LD example (NPE) |
| ```json
$defs.governmentRegistration.id (standardized-identifier)
``` | Not present in the JSON‑LD example (NPE) |
| ```json
$defs.governmentRegistration.typeCode
``` | Not present in the JSON‑LD example (NPE) |
| ```json
$defs.governmentRegistration.countryCode
``` | Not present in the JSON‑LD example (NPE) |
| ```json
$defs.consignmentItem.goodsTypeCode
``` | ```json
ConsignmentItem.goodsTypeCode { "codeValue": "4407" }
``` |
| ```json
$defs.consignmentItem.declaredValueForCarriageAmount
``` | Not present in the JSON‑LD example (NPE) |
| ```json
$defs.consignmentItem.insuranceValueAmount
``` | ```json
ConsignmentItem.insuranceValueAmount { "type": "MonetaryAmount", "value": 125000.00, "currency": "EUR" }
``` |
| ```json
$defs.consignmentItem.grossWeight
``` | ```json
ConsignmentItem.grossWeight { "type": "Measure", "value": 22500, "unitCode": "KGM" }
``` |
| ```json
$defs.consignmentItem.grossVolume
``` | ```json
ConsignmentItem.grossVolume { "type": "Measure", "value": 35.0, "unitCode": "MTQ" }
``` |
| ```json
$defs.consignmentItem.cargoNatureIdentification ($defs.transportCargo)
``` | Not present in the JSON‑LD example (NPE) |
| ```json
$defs.consignmentItem.transportDangerousGoods (array $defs.transportDangerousCode)
``` | Not present in the JSON‑LD example (NPE) |
| ```json
$defs.consignmentItem.associatedTransportEquipment (array $defs.transportEquipment)
``` | ```json
ConsignmentItem.associatedTransportEquipment → TransportEquipment [...] (container MSCU1234567)
``` |
| ```json
$defs.consignmentItem.transportPackage (array $defs.logisticsPackage)
``` | ```json
ConsignmentItem.transportPackage → Package (itemQuantity 20, packageTypeCode "PAL", shippingMarks ...)
``` |
| ```json
$defs.consignmentItem.usedTransportEquipment (array $defs.transportEquipment)
``` | Not present in the JSON‑LD example (NPE) |
| ```json
$defs.consignmentItem.originTradeCountry
``` | ```json
ConsignmentItem.originCountry { "codeValue": "FI" }
``` |
| ```json
$defs.transportCargo.typeCode
``` | Not present in the JSON‑LD example (NPE) |
| ```json
$defs.transportCargo.identificationText (array)
``` | Not present in the JSON‑LD example (NPE) |
| ```json
$defs.transportDangerousCode.undgId
``` | Not present in the JSON‑LD example (NPE) |
| ```json
$defs.transportDangerousCode.hazardClassificationId
``` | Not present in the JSON‑LD example (NPE) |
| ```json
$defs.logisticsPackage.itemQuantity
``` | ```json
Package.itemQuantity { "type": "Quantity", "value": 20 }
``` |
| ```json
$defs.logisticsPackage.typeCode
``` | ```json
Package.packageTypeCode { "type": "Code", "codeValue": "PAL" }
``` |
| ```json
$defs.logisticsPackage.typeText
``` | ```json
Package.packageTypeText "Pallets"
``` |
| ```json
$defs.logisticsPackage.shippingMarks (array of strings)
``` | ```json
Package.shippingMarks "STORA ENSO / GLULAM / JPYOK / LOT 24-10-21"
``` |
| ```json
$defs.logisticsTransportMeans.typeCode
``` | Not present in the JSON‑LD example (NPE) |
| ```json
$defs.logisticsTransportMeans.typeText
``` | ```json
TransportMeans.transportMeansTypeText "Sea (container ship)"
``` |
| ```json
$defs.logisticsTransportMeans.id
``` | ```json
TransportMeans.transportMeansId { "identifierValue": "9321483", "identifierScheme": "IMO" }
``` |
| ```json
$defs.logisticsTransportMeans.name
``` | ```json
TransportMeans.transportMeansName "MAERSK EDITH"
``` |
| ```json
$defs.logisticsTransportMeans.voyageNumber
``` | ```json
TransportMeans.voyageNumber { "identifierValue": "ME123W" }
``` |
| ```json
$defs.logisticsTransportMeans.stageCode
``` | ```json
TransportMeans.stageCode { "codeValue": "M" }
``` |
| ```json
$defs.serviceCharge.paymentArrangementCode
``` | ```json
ServiceCharge.paymentArrangementCode { "codeValue": "PP" }
``` |
| ```json
$defs.serviceCharge.paymentPlace
``` | ```json
ServiceCharge.paymentPlace → Location { "locationName": "Helsinki", "unLocode": { "codeValue": "FIHEL" } }
``` |
| ```json
$defs.transportEquipment.id
``` | ```json
TransportEquipment.equipmentId { "identifierValue": "MSCU1234567" }
``` |
| ```json
$defs.transportEquipment.sealQuantity
``` | ```json
TransportEquipment.sealQuantity { "type": "Quantity", "value": 1 }
``` |
| ```json
$defs.transportEquipment.affixedSeal (array)
``` | ```json
TransportEquipment.affixedSeal [{ "type": "Identifier", "identifierValue": "SEAL-998877" }]
``` |
| ```json
$defs.transportEquipment.tareWeight
``` | ```json
TransportEquipment.tareWeight { "type": "Measure", "value": 2350, "unitCode": "KGM" }
``` |
| ```json
$defs.handlingInstruction.temperatureSetting.minimumValue
``` | ```json
HandlingInstruction.temperatureSetting.minimumValue { "type": "Measure", "value": 5, "unitCode": "CEL" }
``` |
| ```json
$defs.handlingInstruction.temperatureSetting.maximumValue
``` | ```json
HandlingInstruction.temperatureSetting.maximumValue { "type": "Measure", "value": 25, "unitCode": "CEL" }
``` |
| ```json
$defs.handling.handlingInstructions (array of handlingInstruction)
``` | ```json
Handling.handlingInstructions [ { "temperatureSetting": {...} }, { "ktddecv:instructionText": "Keep dry..." } ]
``` |