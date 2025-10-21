# Mapping between eFBL JSON Schema and KTDDE JSON-LD Example

This table aligns the *eFBL (FIATA Bill of Lading) JSON Schema* elements with their corresponding *KTDDE/ktddecv JSON‑LD instance* elements used in the realistic export scenario (Finnish glulam → Japan).

| eFBL JSON element (title + schema structure) | KTDDE JSON‑LD example (instance data) |
|----------------------------------------------|--------------------------------------|
| ```json
"Supply Chain Consignment": {
  "title": "Supply Chain Consignment",
  "description": "Collection of goods items transported from consignor to consignee."
}
``` | ```json
{
  "id": "urn:uuid:9f2bc09a-b0ab-4c7a-8b36-4f7b3a6e2db7",
  "type": "ktddecv:Consignment"
}
``` |
| ```json
"consignor": {
  "title": "Consignor",
  "description": "The consignor party for this supply chain consignment."
}
``` | ```json
"consignor": {
  "type": "ktddecv:Party",
  "legalName": "Stora Enso Wood Products Oy Ltd",
  "hasIdentifier": [
    {"identifierValue": "FI1234567-8", "identifierScheme": "EORI"}
  ]
}
``` |
| ```json
"consignee": {
  "title": "Consignee",
  "description": "Consigned to order of. The consignee party for this supply chain consignment."
}
``` | ```json
"consignee": {
  "type": "ktddecv:Party",
  "legalName": "Yamato Trading Co., Ltd.",
  "postalAddress": {"addressCountry": "JP"}
}
``` |
| ```json
"notifiedParty": {
  "title": "Notified Party",
  "description": "A party who will be notified about this supply chain consignment."
}
``` | ```json
"notifiedParty": [{
  "type": "ktddecv:Party",
  "legalName": "Nihon Logistics K.K."
}]
``` |
| ```json
"carrierAcceptanceLocation": {
  "title": "Carrier Acceptance Location",
  "description": "Place of delivery. The location where this supply chain consignment will be accepted by the carrier."
}
``` | ```json
"placeOfReceipt": {
  "type": "ktddecv:Location",
  "locationName": "Vantaa, FI"
}
``` |
| ```json
"loadingBaseportLocation": {
  "title": "Loading Baseport Location",
  "description": "Port of loading. The baseport where consignment is loaded."
}
``` | ```json
"portOfLoading": {
  "type": "ktddecv:Location",
  "unLocode": {"codeValue": "FIHEL"},
  "locationName": "Helsinki"
}
``` |
| ```json
"unloadingBaseportLocation": {
  "title": "Unloading Baseport Location",
  "description": "Port of discharge. The baseport location for unloading."
}
``` | ```json
"portOfDischarge": {
  "type": "ktddecv:Location",
  "unLocode": {"codeValue": "JPYOK"},
  "locationName": "Yokohama"
}
``` |
| ```json
"includedConsignmentItem": {
  "title": "Include Consignment Item",
  "description": "A consignment item included in this supply chain consignment."
}
``` | ```json
"consignmentItem": [{
  "type": "ktddecv:ConsignmentItem",
  "goodsDescription": "Glued laminated timber beams (glulam)"
}]
``` |
| ```json
"numberOfPackages": {
  "title": "Number Of Packages",
  "description": "The number of packages within this supply chain consignment."
}
``` | ```json
"numberOfPackages": 20
``` |
| ```json
"declaredValueForCarriageAmount": {
  "title": "Declared Value For Carriage Amount",
  "description": "Declared value for ad valorem rate."
}
``` | ```json
"declaredValueForCarriage": {
  "type": "ktddecv:MonetaryAmount",
  "value": 125000.00,
  "currency": "EUR"
}
``` |
| ```json
"totalChargeAmount": {
  "title": "Total Charge Amount",
  "description": "Freight and service charges."
}
``` | ```json
"totalChargeAmount": {
  "type": "ktddecv:MonetaryAmount",
  "value": 4850.00,
  "currency": "EUR"
}
``` |
| ```json
"mainCarriageTransportMovement": {
  "title": "Main Carriage Transport Movement",
  "description": "A main carriage logistics transport movement for this supply chain consignment."
}
``` | ```json
"mainCarriageTransportMovement": {
  "type": "ktddecv:TransportMovement",
  "transportMeans": {
    "transportMeansName": "MAERSK EDITH",
    "voyageNumber": {"identifierValue": "ME123W"}
  }
}
``` |
| ```json
"applicableServiceCharge": {
  "title": "Applicable Service Charge",
  "description": "Freight payable at. Logistics service charge applicable to this consignment."
}
``` | ```json
"applicableServiceCharge": [{
  "type": "ktddecv:ServiceCharge",
  "paymentArrangementCode": {"codeValue": "PP"},
  "paymentPlace": {"locationName": "Helsinki"}
}]
``` |
| ```json
"handling": {
  "title": "Handling",
  "description": "Handling of goods details and instructions."
}
``` | ```json
"handling": {
  "type": "ktddecv:Handling",
  "handlingInstructions": [{
    "temperatureSetting": {"minimumValue": 5, "maximumValue": 25}
  }]
}
``` |
| ```json
"transportEquipment": {
  "title": "Transport Equipment",
  "description": "Container or equipment associated with consignment."
}
``` | ```json
"associatedTransportEquipment": [{
  "type": "ktddecv:TransportEquipment",
  "equipmentId": {"identifierValue": "MSCU1234567"},
  "tareWeight": {"value": 2350, "unitCode": "KGM"}
}]
``` |