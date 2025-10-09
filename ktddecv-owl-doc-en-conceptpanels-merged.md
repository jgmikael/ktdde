# KTDDE Core Vocabulary — English Documentation with Concept Panels (Merged Domain + Restrictions)

## Ontology Overview
- **IRI:** <https://iri.suomi.fi/model/ktddecv/>
- **Title:** Key Trade Documents and Data Elements (KTDDE) Core Vocabulary
- **dcterms:created:** 2024-11-04T12:43:11.269000+00:00
- **dcterms:modified:** 2025-09-16T06:48:54.019000+00:00
- **Description:** An OWL Ontology (Vocabulary if you wish) based on the KTDDE Data Elements, mapped to UBL, UN/CEFACT BSP and the GS1 Web Vocabulary (where possible &amp; applicable).

## Classes

### Additional Amount Category
- **IRI:** <https://iri.suomi.fi/model/ktddecv/AdditionalAmountCategory>
- **Subclass of:** <http://www.w3.org/2004/02/skos/core#Concept>

### Address
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Address>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <https://vocabulary.uncefact.org/TradeAddress>, <https://gs1.org/voc/PostalAddress>, <https://iri.suomi.fi/model/busdoc/1.0.2/Address>

### Advance Ruling Application
- **IRI:** <https://iri.suomi.fi/model/ktddecv/AdvanceRulingApplication>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Air Cargo Manifest
- **IRI:** <https://iri.suomi.fi/model/ktddecv/AirCargoManifest>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Air Waybill
- **IRI:** <https://iri.suomi.fi/model/ktddecv/AirWaybill>
- **Description:** The air transport contract document for carriage of goods by air. May be a master (MAWB) or house (HAWB) waybill; identifies the shipment, parties, flight/route and charges.
- **Subclass of:** <https://iri.suomi.fi/model/ktddecv/TransportDocument>
- **Equivalent to:** <N7a6ec6e9983f4aa49a1b9294f7bf58e7>

**Object properties (domain = this class or via restriction):**
- **airport of departure** (<https://iri.suomi.fi/model/ktddecv/airportOfDeparture>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Location>
- **airport of destination** (<https://iri.suomi.fi/model/ktddecv/airportOfDestination>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Location>
- **chargeable weight** (<https://iri.suomi.fi/model/ktddecv/chargeableWeight>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Quantity>
- **consignee party** (<https://iri.suomi.fi/model/ktddecv/consigneeParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **declared value for carriage** (<https://iri.suomi.fi/model/ktddecv/declaredValueForCarriage>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
- **has dangerous goods** (<https://iri.suomi.fi/model/ktddecv/hasDangerousGoods>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/DangerousGoods>
- **has goods item** (<https://iri.suomi.fi/model/ktddecv/hasGoodsItem>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/GoodsItem>
- **has package** (<https://iri.suomi.fi/model/ktddecv/hasPackage>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Package>
- **has transport equipment** (<https://iri.suomi.fi/model/ktddecv/hasTransportEquipment>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/TransportEquipment>
- **issuing carrier party** (<https://iri.suomi.fi/model/ktddecv/issuingCarrierParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **notify party** (<https://iri.suomi.fi/model/ktddecv/notifyParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **other charges amount** (<https://iri.suomi.fi/model/ktddecv/otherChargesAmount>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
- **place of issue** (<https://iri.suomi.fi/model/ktddecv/placeOfIssue>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Location>
- **shipper party** (<https://iri.suomi.fi/model/ktddecv/shipperParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **total gross weight** (<https://iri.suomi.fi/model/ktddecv/totalGrossWeight>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Quantity>

**Datatype properties (domain = this class or via restriction):**
- **Flight Date** (<https://iri.suomi.fi/model/ktddecv/flightDate>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Flight Number** (<https://iri.suomi.fi/model/ktddecv/flightNumber>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Handling Information** (<https://iri.suomi.fi/model/ktddecv/handlingInformation>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **House Air Waybill Number** (<https://iri.suomi.fi/model/ktddecv/houseAirWaybillNumber>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Issue Date** (<https://iri.suomi.fi/model/ktddecv/issueDate>) (restriction) — Range: <http://www.w3.org/2001/XMLSchema#dateTime>
- **Master Air Waybill Number** (<https://iri.suomi.fi/model/ktddecv/masterAirWaybillNumber>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Allowance Charge
- **IRI:** <https://iri.suomi.fi/model/ktddecv/AllowanceCharge>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <Naf6a7c24e3924381bc458d8aea650e87>

**Object properties (domain = this class or via restriction):**
- **base amount** (<https://iri.suomi.fi/model/ktddecv/baseAmount>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
- **charged by party** (<https://iri.suomi.fi/model/ktddecv/chargedByParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **charged to party** (<https://iri.suomi.fi/model/ktddecv/chargedToParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **has amount** (<https://iri.suomi.fi/model/ktddecv/hasAmount>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
- **per unit amount** (<https://iri.suomi.fi/model/ktddecv/perUnitAmount>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>

**Datatype properties (domain = this class or via restriction):**
- **Allowance Charge Reason Code** (<https://iri.suomi.fi/model/ktddecv/allowanceChargeReasonCode>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Calculation Percent** (<https://iri.suomi.fi/model/ktddecv/calculationPercent>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Charge Indicator** (<https://iri.suomi.fi/model/ktddecv/chargeIndicator>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Multiplier Factor Percent** (<https://iri.suomi.fi/model/ktddecv/multiplierFactorPercent>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Amount>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <N7c9c592667884a4eba445859a374ada8>

**Datatype properties (domain = this class or via restriction):**
- **Amount Value** (<https://iri.suomi.fi/model/ktddecv/amountValue>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Unit Code** (<https://iri.suomi.fi/model/ktddecv/unitCode>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### ATA Carnet
- **IRI:** <https://iri.suomi.fi/model/ktddecv/ATACarnet>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Availability Method
- **IRI:** <https://iri.suomi.fi/model/ktddecv/AvailabilityMethod>
- **Subclass of:** <http://www.w3.org/2004/02/skos/core#Concept>

### Availability Qualifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/AvailabilityQualifier>
- **Subclass of:** <http://www.w3.org/2004/02/skos/core#Concept>

### Bank
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Bank>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/FinancialInstitution>

### Bank Account
- **IRI:** <https://iri.suomi.fi/model/ktddecv/BankAccount>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <N5ed865dcd7ad407485cd46efce367922>

**Datatype properties (domain = this class or via restriction):**
- **Bank Account Identifier** (<https://iri.suomi.fi/model/ktddecv/bankAccountIdentifier>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Bank Instruction
- **IRI:** <https://iri.suomi.fi/model/ktddecv/BankInstruction>
- **Description:** An instruction directed to a bank in the context of trade finance (e.g., documentary credit).
- **Subclass of:** <https://iri.suomi.fi/model/ktddecv/Instruction>

### Bill of Exchange
- **IRI:** <https://iri.suomi.fi/model/ktddecv/BillOfExchange>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <Na3ad777b8ccb4de5926cc44e432b5625>

**Object properties (domain = this class or via restriction):**
- **has tenor** (<https://iri.suomi.fi/model/ktddecv/hasTenor>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Tenor>

### Bill of Lading
- **IRI:** <https://iri.suomi.fi/model/ktddecv/BillOfLading>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Business Document
- **IRI:** <https://iri.suomi.fi/model/ktddecv/BusinessDocument>
- **Description:** An information artifact exchanged in trade, transport, customs, finance, or insurance processes.

- **Subclass of:** <https://iri.suomi.fi/model/ktddecv/CommunicationEntity>
- **Equivalent to:** <Ne98bdeebda6b4b349df9a9a1246df9c7>

**Object properties (domain = this class or via restriction):**
- **document type** (<https://iri.suomi.fi/model/ktddecv/documentType>) (restriction) — Range: <http://www.w3.org/2004/02/skos/core#Concept>
- **has message** (<https://iri.suomi.fi/model/ktddecv/hasMessage>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Message>

### Business Event
- **IRI:** <https://iri.suomi.fi/model/ktddecv/BusinessEvent>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Certificate of Origin
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CertificateOfOrigin>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <N58faef9e7abf41e896bba29228360001>

**Object properties (domain = this class or via restriction):**
- **certificate number** (<https://iri.suomi.fi/model/ktddecv/certificateNumber>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Identifier>
- **has goods item** (<https://iri.suomi.fi/model/ktddecv/hasGoodsItem>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/GoodsItem>
- **issuing authority party** (<https://iri.suomi.fi/model/ktddecv/issuingAuthorityParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **preference criterion code** (<https://iri.suomi.fi/model/ktddecv/preferenceCriterionCode>) (restriction) — Range: <http://www.w3.org/2004/02/skos/core#Concept>

**Datatype properties (domain = this class or via restriction):**
- **Issue Date** (<https://iri.suomi.fi/model/ktddecv/issueDate>) (restriction) — Range: <http://www.w3.org/2001/XMLSchema#dateTime>

### Characteristic
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Characteristic>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <https://vocabulary.uncefact.org/ProductCharacteristic>

### CITES Permit
**Concept:** *CITES permit* — *a permit required for the international trade of endangered species, issued under the Convention on International Trade in Endangered Species of Wild Fauna and Flora (CITES)*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-233>
**Hierarchy:** certificate ▶ CITES permit
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CITESPermit>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <N115906e47f2140e4a3239b55d54c9a62>

**Object properties (domain = this class or via restriction):**
- **validity period** (<https://iri.suomi.fi/model/ktddecv/validityPeriod>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/PeriodOfTime>

**Datatype properties (domain = this class or via restriction):**
- **Issue Date** (<https://iri.suomi.fi/model/ktddecv/issueDate>) (restriction) — Range: <http://www.w3.org/2001/XMLSchema#dateTime>
- **Issuing Authority** (<https://iri.suomi.fi/model/ktddecv/issuingAuthority>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Classification Scheme
- **IRI:** <https://iri.suomi.fi/model/ktddecv/ClassificationScheme>
- **Subclass of:** <http://www.w3.org/2004/02/skos/core#Concept>

### CODEX Official Certificate
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CODEXOfficialCertificate>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Commercial Invoice
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CommercialInvoice>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <Nd95b867ff6e4461a99a8b752a770f069>

**Object properties (domain = this class or via restriction):**
- **has delivery** (<https://iri.suomi.fi/model/ktddecv/hasDelivery>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Delivery>
- **has invoice line** (<https://iri.suomi.fi/model/ktddecv/hasInvoiceLine>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/InvoiceLine>
- **has invoicee** (<https://iri.suomi.fi/model/ktddecv/hasInvoicee>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **invoice document** (<https://iri.suomi.fi/model/ktddecv/invoiceDocument>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Document>
- **invoice payment terms** (<https://iri.suomi.fi/model/ktddecv/invoicePaymentTerms>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/PaymentTerms>
- **invoicee party** (<https://iri.suomi.fi/model/ktddecv/invoiceeParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **total amount** (<https://iri.suomi.fi/model/ktddecv/totalAmount>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Amount>

**Datatype properties (domain = this class or via restriction):**
- **Invoice Date** (<https://iri.suomi.fi/model/ktddecv/invoiceDate>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Invoice Number** (<https://iri.suomi.fi/model/ktddecv/invoiceNumber>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Payment Due Date** (<https://iri.suomi.fi/model/ktddecv/paymentDueDate>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Commodity Classification
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CommodityClassification>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <N27308cb4ef9248308b774c003702e0ef>, <https://iri.suomi.fi/model/busdoc/1.0.2/CommodityClassification>

**Object properties (domain = this class or via restriction):**
- **has classification scheme** (<https://iri.suomi.fi/model/ktddecv/hasClassificationScheme>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/ClassificationScheme>

**Datatype properties (domain = this class or via restriction):**
- **Classification Code** (<https://iri.suomi.fi/model/ktddecv/classificationCode>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Commodity Code** (<https://iri.suomi.fi/model/ktddecv/commodityCode>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Communication Entity
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CommunicationEntity>
- **Description:** Thing that can carry sender/receiver party context (e.g., a BusinessDocument or a Message).
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <N0e2d12e84a2d4095a4b51c350f61ca86>

**Object properties (domain = this class or via restriction):**
- **receiver party** (<https://iri.suomi.fi/model/ktddecv/receiverParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **sender party** (<https://iri.suomi.fi/model/ktddecv/senderParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>

### Consignment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Consignment>
- **Description:** The grouping of goods for transport, under a single transport contract, from a consignor to a consignee.
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <Ndb384a8bc0754d1caa164a625905a564>, <https://vocabulary.uncefact.org/Consignment>, <https://iri.suomi.fi/model/busdoc/1.0.2/Consignment>

**Object properties (domain = this class or via restriction):**
- **consignment identifier** (<https://iri.suomi.fi/model/ktddecv/consignmentIdentifier>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Identifier>
- **delivered to** (<https://iri.suomi.fi/model/ktddecv/deliveredTo>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **final destination place** (<https://iri.suomi.fi/model/ktddecv/finalDestinationPlace>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Location>
- **has goods item** (<https://iri.suomi.fi/model/ktddecv/hasGoodsItem>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/GoodsItem>
- **has package** (<https://iri.suomi.fi/model/ktddecv/hasPackage>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Package>
- **has transport event** (<https://iri.suomi.fi/model/ktddecv/hasTransportEvent>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/TransportEvent>
- **place of delivery** (<https://iri.suomi.fi/model/ktddecv/placeOfDelivery>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Location>
- **place of discharge** (<https://iri.suomi.fi/model/ktddecv/placeOfDischarge>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Location>
- **place of loading** (<https://iri.suomi.fi/model/ktddecv/placeOfLoading>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Location>
- **place of receipt** (<https://iri.suomi.fi/model/ktddecv/placeOfReceipt>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Location>
- **total gross weight** (<https://iri.suomi.fi/model/ktddecv/totalGrossWeight>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Quantity>
- **total net weight** (<https://iri.suomi.fi/model/ktddecv/totalNetWeight>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Quantity>
- **total package count** (<https://iri.suomi.fi/model/ktddecv/totalPackageCount>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Quantity>
- **transshipment place** (<https://iri.suomi.fi/model/ktddecv/transshipmentPlace>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Location>

**Datatype properties (domain = this class or via restriction):**
- **Delivery Date** (<https://iri.suomi.fi/model/ktddecv/deliveryDate>) (restriction) — Range: <http://www.w3.org/2001/XMLSchema#dateTime>
- **Despatch Date** (<https://iri.suomi.fi/model/ktddecv/despatchDate>) (restriction) — Range: <http://www.w3.org/2001/XMLSchema#dateTime>

### Consignment Security Declaration
- **IRI:** <https://iri.suomi.fi/model/ktddecv/ConsignmentSecurityDeclaration>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Contract
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Contract>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <Nf1f5ba9b20004171b907fdabbad109af>

**Datatype properties (domain = this class or via restriction):**
- **Contract Identifier** (<https://iri.suomi.fi/model/ktddecv/contractIdentifier>) (restriction) — Range: <http://www.w3.org/2001/XMLSchema#string>

### Country
**Concept:** *country* — *a national territory identified by ISO 3166 code, relevant in trade for origin, destination, and transit*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-208>
**Hierarchy:** Location ▶ country ▶ destination country
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Country>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <Nddaf4d0d95a74c91a9ab393dd77c26b3>, <https://gs1.org/voc/Country>, <https://vocabulary.uncefact.org/Country>, <https://iri.suomi.fi/model/busdoc/1.0.2/Country>

**Datatype properties (domain = this class or via restriction):**
- **Country Code** (<https://iri.suomi.fi/model/ktddecv/countryCode>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Country Name** (<https://iri.suomi.fi/model/ktddecv/countryName>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Credit Availability
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CreditAvailability>
- **Description:** A structured statement of where (party/place) and how (method/conditions) a documentary credit is available.
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <N050f6b7433da42cab175ac1db64cdc8c>

**Object properties (domain = this class or via restriction):**
- **available at place** (<https://iri.suomi.fi/model/ktddecv/availableAtPlace>) (restriction) — Range: <https://iri.suomi.fi/model/ktddu/0.0.1/Place>
- **available with party** (<https://iri.suomi.fi/model/ktddecv/availableWithParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **available with qualifier** (<https://iri.suomi.fi/model/ktddecv/availableWithQualifier>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/AvailabilityQualifier>
- **drawee party** (<https://iri.suomi.fi/model/ktddecv/draweeParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **has amount** (<https://iri.suomi.fi/model/ktddecv/hasAmount>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
- **has availability method** (<https://iri.suomi.fi/model/ktddecv/hasAvailabilityMethod>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/AvailabilityMethod>
- **obligor party** (<https://iri.suomi.fi/model/ktddecv/obligorParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **payee party** (<https://iri.suomi.fi/model/ktddecv/payeeParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>

**Datatype properties (domain = this class or via restriction):**
- **Maturity Date** (<https://iri.suomi.fi/model/ktddecv/maturityDate>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Customs Bond
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CustomsBond>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <Nc0dcda2e37484af4827b2846683cb71b>

**Object properties (domain = this class or via restriction):**
- **surety party** (<https://iri.suomi.fi/model/ktddecv/suretyParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>

**Datatype properties (domain = this class or via restriction):**
- **Bond Number** (<https://iri.suomi.fi/model/ktddecv/bondNumber>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Customs Declaration
**Concept:** *customs declaration* — *a statement made to customs authorities providing prescribed information on imported, exported, or transiting goods*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-237>
**Hierarchy:** customs document ▶ customs declaration
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CustomsDeclaration>
- **Description:** Summary declaration for export/import; links declared goods lines, values and duties/taxes.
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <N3a6c486db6514c64ab4eb7d9a5e16a55>

**Object properties (domain = this class or via restriction):**
- **consignee party** (<https://iri.suomi.fi/model/ktddecv/consigneeParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **customs procedure code ** (<https://iri.suomi.fi/model/ktddecv/customsProcedureCode>) (restriction) — Range: <http://www.w3.org/2004/02/skos/core#Concept>
- **declarant party** (<https://iri.suomi.fi/model/ktddecv/declarantParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **declaration number** (<https://iri.suomi.fi/model/ktddecv/declarationNumber>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Identifier>
- **exporter party** (<https://iri.suomi.fi/model/ktddecv/exporterParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **has goods item** (<https://iri.suomi.fi/model/ktddecv/hasGoodsItem>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/GoodsItem>
- **importer party** (<https://iri.suomi.fi/model/ktddecv/importerParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **includes allowance charge** (<https://iri.suomi.fi/model/ktddecv/includesAllowanceCharge>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/AllowanceCharge>
- **includes duty tax fee** (<https://iri.suomi.fi/model/ktddecv/includesDutyTaxFee>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/DutyTaxFee>
- **relates to invoice** (<https://iri.suomi.fi/model/ktddecv/relatesToInvoice>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/CommercialInvoice>
- **relates to transport document** (<https://iri.suomi.fi/model/ktddecv/relatesToTransportDocument>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/TransportDocument>
- **statistical value amount** (<https://iri.suomi.fi/model/ktddecv/statisticalValueAmount>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
- **total invoice amount** (<https://iri.suomi.fi/model/ktddecv/totalInvoiceAmount>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>

**Datatype properties (domain = this class or via restriction):**
- **Customs Office Code** (<https://iri.suomi.fi/model/ktddecv/customsOfficeCode>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Declaration Date** (<https://iri.suomi.fi/model/ktddecv/declarationDate>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Dangerous Goods
**Concept:** *Dangerous Goods* — *substances or articles posing risks during transport, classified under international regulations (e.g., UN numbers)*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-217>
**Hierarchy:** goods specification ▶ Dangerous Goods ▶ dangerous goods information
- **IRI:** <https://iri.suomi.fi/model/ktddecv/DangerousGoods>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <Ne6574ff918e54fbbbf27b0bddb82b225>, <https://vocabulary.uncefact.org/DangerousGoods>, <https://iri.suomi.fi/model/busdoc/1.0.2/HazardousGoodsTransit>

**Object properties (domain = this class or via restriction):**
- **inner packaging quantity** (<https://iri.suomi.fi/model/ktddecv/innerPackagingQuantity>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Quantity>
- **net quantity per package** (<https://iri.suomi.fi/model/ktddecv/netQuantityPerPackage>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Quantity>

**Datatype properties (domain = this class or via restriction):**
- **Excepted Quantity Indicator** (<https://iri.suomi.fi/model/ktddecv/exceptedQuantityIndicator>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Flash Point Temperature** (<https://iri.suomi.fi/model/ktddecv/flashPointTemperature>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Hazard Class Code** (<https://iri.suomi.fi/model/ktddecv/hazardClassCode>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Hazard Label Code** (<https://iri.suomi.fi/model/ktddecv/hazardLabelCode>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Limited Quantity Indicator** (<https://iri.suomi.fi/model/ktddecv/limitedQuantityIndicator>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Marine Pollutant Indicator** (<https://iri.suomi.fi/model/ktddecv/marinePollutantIndicator>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Packing Group Code** (<https://iri.suomi.fi/model/ktddecv/packingGroupCode>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Packing Instruction Code** (<https://iri.suomi.fi/model/ktddecv/packingInstructionCode>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Proper Shipping Name** (<https://iri.suomi.fi/model/ktddecv/properShippingName>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Special Provision Code** (<https://iri.suomi.fi/model/ktddecv/specialProvisionCode>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subsidiary Hazard Code** (<https://iri.suomi.fi/model/ktddecv/subsidiaryHazardCode>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Technical Name** (<https://iri.suomi.fi/model/ktddecv/technicalName>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **UN Number** (<https://iri.suomi.fi/model/ktddecv/unNumber>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Dangerous Goods Declaration
- **IRI:** <https://iri.suomi.fi/model/ktddecv/DangerousGoodsDeclaration>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <N4ac5906301d34ec08ea394bb7aed74c2>

**Object properties (domain = this class or via restriction):**
- **declarant party** (<https://iri.suomi.fi/model/ktddecv/declarantParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **declaration number** (<https://iri.suomi.fi/model/ktddecv/declarationNumber>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Identifier>
- **has goods item** (<https://iri.suomi.fi/model/ktddecv/hasGoodsItem>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/GoodsItem>

**Datatype properties (domain = this class or via restriction):**
- **Declaration Date** (<https://iri.suomi.fi/model/ktddecv/declarationDate>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Delivery
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Delivery>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <Nb607edc7d4b848338ff975e9c58e2b1b>

**Object properties (domain = this class or via restriction):**
- **delivery terms** (<https://iri.suomi.fi/model/ktddecv/deliveryTerms>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/TradeDeliveryTerms>
- **has shipment** (<https://iri.suomi.fi/model/ktddecv/hasShipment>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Shipment>

### Delivery Milestone
- **IRI:** <https://iri.suomi.fi/model/ktddecv/DeliveryMilestone>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <N947c766e60fc462ab5e3ce3c9ffd3ead>

**Object properties (domain = this class or via restriction):**
- **has shipment period** (<https://iri.suomi.fi/model/ktddecv/hasShipmentPeriod>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/PeriodOfTime>

### Document
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Document>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <https://vocabulary.uncefact.org/Document>, <N0425dd02e66848559411ada4c128ce0d>

**Datatype properties (domain = this class or via restriction):**
- **Document Date** (<https://iri.suomi.fi/model/ktddecv/documentDate>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Document Identifier** (<https://iri.suomi.fi/model/ktddecv/documentIdentifier>) (restriction) — Range: <http://www.w3.org/2001/XMLSchema#string>

### Document Requirement
- **IRI:** <https://iri.suomi.fi/model/ktddecv/DocumentRequirement>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <Ne497dfa0f5314d5eb1607f1e8d24e633>

**Object properties (domain = this class or via restriction):**
- **issuer party** (<https://iri.suomi.fi/model/ktddecv/issuerParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **required document type** (<https://iri.suomi.fi/model/ktddecv/requiredDocumentType>) (restriction) — Range: <http://www.w3.org/2004/02/skos/core#Concept>

**Datatype properties (domain = this class or via restriction):**
- **Number of Copies** (<https://iri.suomi.fi/model/ktddecv/numberOfCopies>) (restriction) — Range: <http://www.w3.org/2001/XMLSchema#integer>
- **Number of Originals** (<https://iri.suomi.fi/model/ktddecv/numberOfOriginals>) (restriction) — Range: <http://www.w3.org/2001/XMLSchema#integer>

### Documentary Credit
**Concept:** *documentary credit* — *a financial instrument by which a bank undertakes to pay the seller on behalf of the buyer upon presentation of compliant documents*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-239>
**Hierarchy:** financial document ▶ documentary credit
- **IRI:** <https://iri.suomi.fi/model/ktddecv/DocumentaryCredit>
- **Subclass of:** <https://iri.suomi.fi/model/ktddu/0.0.1/LegalConstruct>, <https://iri.suomi.fi/model/ktddu/0.0.1/InformationObject>
- **Equivalent to:** <Na53eb0dfadbc4411bb996b7ae2155fab>

**Object properties (domain = this class or via restriction):**
- **additional amounts covered** (<https://iri.suomi.fi/model/ktddecv/additionalAmountsCovered>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/AdditionalAmountCategory>
- **advise through bank party** (<https://iri.suomi.fi/model/ktddecv/adviseThroughBankParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **advising bank party** (<https://iri.suomi.fi/model/ktddecv/advisingBankParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **applicable rules** (<https://iri.suomi.fi/model/ktddecv/applicableRules>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/RuleSet>
- **applicant bank party** (<https://iri.suomi.fi/model/ktddecv/applicantBankParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **applicant party** (<https://iri.suomi.fi/model/ktddecv/applicantParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **confirmation instruction code** (<https://iri.suomi.fi/model/ktddecv/confirmationInstructionCode>) (restriction) — Range: <http://www.w3.org/2004/02/skos/core#Concept>
- **confirming party** (<https://iri.suomi.fi/model/ktddecv/confirmingParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **covers additional charge** (<https://iri.suomi.fi/model/ktddecv/coversAdditionalCharge>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/AllowanceCharge>
- **drafts at tenor** (<https://iri.suomi.fi/model/ktddecv/draftsAtTenor>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Tenor>
- **drawee party** (<https://iri.suomi.fi/model/ktddecv/draweeParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **has availability method** (<https://iri.suomi.fi/model/ktddecv/hasAvailabilityMethod>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/AvailabilityMethod>
- **has credit availability** (<https://iri.suomi.fi/model/ktddecv/hasCreditAvailability>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/CreditAvailability>
- **has delivery milestone** (<https://iri.suomi.fi/model/ktddecv/hasDeliveryMilestone>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/DeliveryMilestone>
- **has payment line** (<https://iri.suomi.fi/model/ktddecv/hasPaymentLine>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/PaymentLine>
- **has payment terms** (<https://iri.suomi.fi/model/ktddecv/hasPaymentTerms>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/PaymentTerms>
- **has presentation period** (<https://iri.suomi.fi/model/ktddecv/hasPresentationPeriod>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/PeriodOfTime>
- **has shipment** (<https://iri.suomi.fi/model/ktddecv/hasShipment>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Shipment>
- **has shipment period** (<https://iri.suomi.fi/model/ktddecv/hasShipmentPeriod>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/PeriodOfTime>
- **includes allowance charge** (<https://iri.suomi.fi/model/ktddecv/includesAllowanceCharge>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/AllowanceCharge>
- **instruction to bank** (<https://iri.suomi.fi/model/ktddecv/instructionToBank>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/BankInstruction>
- **issuing bank party** (<https://iri.suomi.fi/model/ktddecv/issuingBankParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **maximum credit amount** (<https://iri.suomi.fi/model/ktddecv/maximumCreditAmount>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Amount>
- **place of expiry** (<https://iri.suomi.fi/model/ktddecv/placeOfExpiry>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Location>
- **place of presentation** (<https://iri.suomi.fi/model/ktddecv/placeOfPresentation>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Location>
- **presentation base event** (<https://iri.suomi.fi/model/ktddecv/presentationBaseEvent>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/ShipmentBasis>
- **references pre advice** (<https://iri.suomi.fi/model/ktddecv/referencesPreAdvice>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Document>
- **reimbursing bank party** (<https://iri.suomi.fi/model/ktddecv/reimbursingBankParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **requested confirmation party** (<https://iri.suomi.fi/model/ktddecv/requestedConfirmationParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **requires document** (<https://iri.suomi.fi/model/ktddecv/requiresDocument>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/DocumentRequirement>

**Datatype properties (domain = this class or via restriction):**
- **Additional Conditions Text** (<https://iri.suomi.fi/model/ktddecv/additionalConditionsText>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Confirmation Added Date** (<https://iri.suomi.fi/model/ktddecv/confirmationAddedDate>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Credit Amount Tolerance Percentage** (<https://iri.suomi.fi/model/ktddecv/creditAmountTolerancePercentage>) (restriction) — Range: <http://www.w3.org/2001/XMLSchema#decimal>
- **Credit Identifier** (<https://iri.suomi.fi/model/ktddecv/creditIdentifier>) (restriction) — Range: <http://www.w3.org/2001/XMLSchema#string>
- **Documentary Credit Type Code** (<https://iri.suomi.fi/model/ktddecv/documentaryCreditTypeCode>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Expiry Date** (<https://iri.suomi.fi/model/ktddecv/expiryDate>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Issue Date** (<https://iri.suomi.fi/model/ktddecv/issueDate>) (restriction) — Range: <http://www.w3.org/2001/XMLSchema#dateTime>
- **Latest Presentation Date** (<https://iri.suomi.fi/model/ktddecv/latestPresentationDate>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Latest Shipment Date** (<https://iri.suomi.fi/model/ktddecv/latestShipmentDate>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Partial Shipment Allowed** (<https://iri.suomi.fi/model/ktddecv/partialShipmentAllowed>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Presentation Period Days** (<https://iri.suomi.fi/model/ktddecv/presentationPeriodDays>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Transshipment Allowed** (<https://iri.suomi.fi/model/ktddecv/transshipmentAllowed>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Duty/Tax/Fee
- **IRI:** <https://iri.suomi.fi/model/ktddecv/DutyTaxFee>
- **Description:** Breakdown element for customs duties, taxes, or fees with basis and computed amount.
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### EMCS Document
- **IRI:** <https://iri.suomi.fi/model/ktddecv/EMCSDocument>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Excise Guarantee
- **IRI:** <https://iri.suomi.fi/model/ktddecv/ExciseGuarantee>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Export Import License
- **IRI:** <https://iri.suomi.fi/model/ktddecv/ExportImportLicense>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Financial Document
- **IRI:** <https://iri.suomi.fi/model/ktddecv/FinancialDocument>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Goods Item
**Concept:** *goods item* — *a distinct product or commodity within a consignment or shipment, identified by description, code, and quantity*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-198>
**Hierarchy:** Trade Object ▶ goods item ▶ dangerous goods item
- **IRI:** <https://iri.suomi.fi/model/ktddecv/GoodsItem>
- **Description:** Use only for logistics/consignment context: physical goods as packed/shipped (quantities, weights, marks &amp; numbers, packaging, DG info, etc.).
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <N57a4d02853c247078e205f7764b5e877>, <https://iri.suomi.fi/model/busdoc/1.0.2/GoodsItem>

**Object properties (domain = this class or via restriction):**
- **applied commodity classification** (<https://iri.suomi.fi/model/ktddecv/appliedCommodityClassification>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/CommodityClassification>
- **has country of origin** (<https://iri.suomi.fi/model/ktddecv/hasCountryOfOrigin>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Country>
- **has dangerous goods details** (<https://iri.suomi.fi/model/ktddecv/hasDangerousGoodsDetails>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/DangerousGoods>
- **has quantity** (<https://iri.suomi.fi/model/ktddecv/hasQuantity>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Quantity>

**Datatype properties (domain = this class or via restriction):**
- **Description of Goods Text** (<https://iri.suomi.fi/model/ktddecv/descriptionOfGoodsText>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Item Description Text** (<https://iri.suomi.fi/model/ktddecv/itemDescriptionText>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Product Identifier** (<https://iri.suomi.fi/model/ktddecv/productIdentifier>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Identifier
**Concept:** *Identifier* — *a reference assigned to uniquely distinguish a document, consignment, shipment, or party*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-221>
**Hierarchy:** Identifier ▶ seal identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Identifier>
- **Description:** subclass of adms:Identifier
- **Subclass of:** <https://iri.suomi.fi/model/ktddu/0.0.1/Identifier>

### Instruction
**Concept:** *instruction* — *an operational directive provided to guide actions in a trade or logistics process*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-354>
**Hierarchy:** Process ▶ instruction ▶ delivery Instructions
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Instruction>
- **Description:** A directive expressed in a message context, issued by one party to another.

or

A message conveying directives or requests from sender to receiver.
- **Subclass of:** <https://iri.suomi.fi/model/ktddecv/Message>
- **Equivalent to:** <N4b66d3df2a524f0b8f3396cf87b82873>

**Object properties (domain = this class or via restriction):**
- **instructed party** (<https://iri.suomi.fi/model/ktddecv/instructedParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **instructing party** (<https://iri.suomi.fi/model/ktddecv/instructingParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>

**Datatype properties (domain = this class or via restriction):**
- **Instruction Text** (<https://iri.suomi.fi/model/ktddecv/instructionText>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Insurance Certificate
- **IRI:** <https://iri.suomi.fi/model/ktddecv/InsuranceCertificate>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <Naf8c8e7f50f2446baf00026f57bffc7e>

**Object properties (domain = this class or via restriction):**
- **beneficiary party** (<https://iri.suomi.fi/model/ktddecv/beneficiaryParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **claims payable at place** (<https://iri.suomi.fi/model/ktddecv/claimsPayableAtPlace>) (restriction) — Range: <https://iri.suomi.fi/model/ktddu/0.0.1/Place>
- **coverage amount** (<https://iri.suomi.fi/model/ktddecv/coverageAmount>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
- **coverage type code** (<https://iri.suomi.fi/model/ktddecv/coverageTypeCode>) (restriction) — Range: <http://www.w3.org/2004/02/skos/core#Concept>
- **insured amount** (<https://iri.suomi.fi/model/ktddecv/insuredAmount>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
- **insured party** (<https://iri.suomi.fi/model/ktddecv/insuredParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **insurer party** (<https://iri.suomi.fi/model/ktddecv/insurerParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>

**Datatype properties (domain = this class or via restriction):**
- **Insurance Policy Number** (<https://iri.suomi.fi/model/ktddecv/insurancePolicyNumber>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Insurance Terms Text** (<https://iri.suomi.fi/model/ktddecv/insuranceTermsText>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Invoice Line
- **IRI:** <https://iri.suomi.fi/model/ktddecv/InvoiceLine>
- **Subclass of:** <https://iri.suomi.fi/model/ktddecv/TradeLineItem>
- **Equivalent to:** <https://vocabulary.uncefact.org/LineTradeSettlement>, <Nacdf817504774f0a8e26360acc0ec556>, <https://iri.suomi.fi/model/busdoc/1.0.2/InvoiceLine>

**Object properties (domain = this class or via restriction):**
- **describes item** (<https://iri.suomi.fi/model/ktddecv/describesItem>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/TradeItem>
- **describes trade product** (<https://iri.suomi.fi/model/ktddecv/describesTradeProduct>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/TradeProduct>
- **invoiced quantity** (<https://iri.suomi.fi/model/ktddecv/invoicedQuantity>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Quantity>

### Legal Entity
- **IRI:** <https://iri.suomi.fi/model/ktddecv/LegalEntity>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Location
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Location>
- **Subclass of:** <https://iri.suomi.fi/model/ktddu/0.0.1/Place>
- **Equivalent to:** <https://vocabulary.uncefact.org/Location>, <https://iri.suomi.fi/model/busdoc/1.0.2/Location>, <N617f747fa8d248bbbf40d30ffaf27e22>

**Object properties (domain = this class or via restriction):**
- **has Address** (<https://iri.suomi.fi/model/ktddecv/hasAddress>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/PostalAddress>
- **has identifier** (<https://iri.suomi.fi/model/ktddecv/hasIdentifier>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Identifier>
- **location country** (<https://iri.suomi.fi/model/ktddecv/locationCountry>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Country>

**Datatype properties (domain = this class or via restriction):**
- **Alternate Name** (<https://iri.suomi.fi/model/ktddecv/alternateName>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Border Crossing Point Code** (<https://iri.suomi.fi/model/ktddecv/borderCrossingPointCode>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Customs Office Code** (<https://iri.suomi.fi/model/ktddecv/customsOfficeCode>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Description** (<https://iri.suomi.fi/model/ktddecv/description>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Elevation Meters** (<https://iri.suomi.fi/model/ktddecv/elevationMeters>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Geo WKT** (<https://iri.suomi.fi/model/ktddecv/geoWKT>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **IATA Code** (<https://iri.suomi.fi/model/ktddecv/iataCode>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **ICAO Airport Code** (<https://iri.suomi.fi/model/ktddecv/icaoAirportCode>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Latitude** (<https://iri.suomi.fi/model/ktddecv/latitude>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Location ID** (<https://iri.suomi.fi/model/ktddecv/locationID>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Location Name** (<https://iri.suomi.fi/model/ktddecv/locationName>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Longitude** (<https://iri.suomi.fi/model/ktddecv/longitude>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Port Facility Code** (<https://iri.suomi.fi/model/ktddecv/portFacilityCode>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Post Code** (<https://iri.suomi.fi/model/ktddecv/postCode>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Terminal Code** (<https://iri.suomi.fi/model/ktddecv/terminalCode>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Time Zone** (<https://iri.suomi.fi/model/ktddecv/timeZone>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **UIC Station Code** (<https://iri.suomi.fi/model/ktddecv/uicStationCode>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **UN Locode** (<https://iri.suomi.fi/model/ktddecv/unlocode>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Warehouse GLN** (<https://iri.suomi.fi/model/ktddecv/warehouseGLN>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Message
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Message>
- **Description:** A sender-to-receiver communication related to a business document, which may carry unstructured text and/or structured qualifiers.
- **Subclass of:** <https://iri.suomi.fi/model/ktddecv/CommunicationEntity>
- **Equivalent to:** <Nbb75ea36e3fe4f908a879b405f305304>

**Datatype properties (domain = this class or via restriction):**
- **Message Subject** (<https://iri.suomi.fi/model/ktddecv/messageSubject>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Message Text** (<https://iri.suomi.fi/model/ktddecv/messageText>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Monetary Amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
- **Subclass of:** <https://iri.suomi.fi/model/ktddecv/Amount>
- **Equivalent to:** <N9f816a62552e4d6f89b6d4e50394874f>

**Datatype properties (domain = this class or via restriction):**
- **Amount Value** (<https://iri.suomi.fi/model/ktddecv/amountValue>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Currency Code** (<https://iri.suomi.fi/model/ktddecv/currencyCode>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Organic Inspection Certificate
- **IRI:** <https://iri.suomi.fi/model/ktddecv/OrganicInspectionCertificate>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <N62985e85ff864cb0a16c1394404305f8>

**Datatype properties (domain = this class or via restriction):**
- **Issue Date** (<https://iri.suomi.fi/model/ktddecv/issueDate>) (restriction) — Range: <http://www.w3.org/2001/XMLSchema#dateTime>

### Package
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Package>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <Ncfac96a4315f4d0b99a3635a416bb830>

**Object properties (domain = this class or via restriction):**
- **has dangerous goods details** (<https://iri.suomi.fi/model/ktddecv/hasDangerousGoodsDetails>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/DangerousGoods>
- **has package item** (<https://iri.suomi.fi/model/ktddecv/hasPackageItem>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/PackageItem>
- **package type code** (<https://iri.suomi.fi/model/ktddecv/packageTypeCode>) (restriction) — Range: <http://www.w3.org/2004/02/skos/core#Concept>
- **seal identifier** (<https://iri.suomi.fi/model/ktddecv/sealIdentifier>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Identifier>
- **sscc** (<https://iri.suomi.fi/model/ktddecv/sscc>) (restriction) — Range: <http://www.w3.org/2004/02/skos/core#Concept>

**Datatype properties (domain = this class or via restriction):**
- **Marks and Numbers Text** (<https://iri.suomi.fi/model/ktddecv/marksAndNumbersText>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Package Count** (<https://iri.suomi.fi/model/ktddecv/packageCount>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Sealed Indicator** (<https://iri.suomi.fi/model/ktddecv/sealedIndicator>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Package Item
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PackageItem>
- **Description:** A content record inside a package referencing a GoodsItem and the quantity/attributes of that portion.
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <Nfe636ae74d0340efb39fe3ed13019b3b>

**Object properties (domain = this class or via restriction):**
- **for goods item** (<https://iri.suomi.fi/model/ktddecv/forGoodsItem>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/GoodsItem>

### Packing List
**Concept:** *packing list* — *a document detailing the contents, packaging, and marks of a consignment for identification and verification purposes*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-229>
**Hierarchy:** Document ▶ packing list
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PackingList>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <N2b79a69ab7ad4852a104d1370e795ceb>

**Object properties (domain = this class or via restriction):**
- **has package** (<https://iri.suomi.fi/model/ktddecv/hasPackage>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Package>
- **packing list number** (<https://iri.suomi.fi/model/ktddecv/packingListNumber>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Identifier>
- **relates to invoice** (<https://iri.suomi.fi/model/ktddecv/relatesToInvoice>) (restriction) — Range: (unspecified)
- **total gross weight** (<https://iri.suomi.fi/model/ktddecv/totalGrossWeight>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Quantity>
- **total net weight** (<https://iri.suomi.fi/model/ktddecv/totalNetWeight>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Quantity>
- **total package count** (<https://iri.suomi.fi/model/ktddecv/totalPackageCount>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Quantity>

### Party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Party>
- **Subclass of:** <https://iri.suomi.fi/model/ktddu/0.0.1/Actor>
- **Equivalent to:** <https://vocabulary.uncefact.org/TradeParty>, <https://iri.suomi.fi/model/busdoc/1.0.2/Party>, <N276b108dd12e4b55bf6399012c45f70f>

**Object properties (domain = this class or via restriction):**
- **party address** (<https://iri.suomi.fi/model/ktddecv/partyAddress>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Address>
- **party identifier** (<https://iri.suomi.fi/model/ktddecv/partyIdentifier>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Identifier>
- **party legal entity** (<https://iri.suomi.fi/model/ktddecv/partyLegalEntity>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/LegalEntity>

**Datatype properties (domain = this class or via restriction):**
- **Name** (<https://iri.suomi.fi/model/ktddecv/name>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Payment Confirmation
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PaymentConfirmation>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Payment Line
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PaymentLine>
- **Description:** One tranche/portion of payment under a mixed-payment documentary credit.
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <Nb5a370e97318440d9155f0fe0af1e5f3>

**Object properties (domain = this class or via restriction):**
- **has amount** (<https://iri.suomi.fi/model/ktddecv/hasAmount>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Amount>
- **payee party** (<https://iri.suomi.fi/model/ktddecv/payeeParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **payment settlement method** (<https://iri.suomi.fi/model/ktddecv/paymentSettlementMethod>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/AvailabilityMethod>

**Datatype properties (domain = this class or via restriction):**
- **Payment Due Date** (<https://iri.suomi.fi/model/ktddecv/paymentDueDate>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Payment Schedule Line
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PaymentScheduleLine>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <N26e8f23eec8148aca952ede15575ef83>

**Object properties (domain = this class or via restriction):**
- **base amount** (<https://iri.suomi.fi/model/ktddecv/baseAmount>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
- **has amount** (<https://iri.suomi.fi/model/ktddecv/hasAmount>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>

**Datatype properties (domain = this class or via restriction):**
- **Amount Percent Of Base** (<https://iri.suomi.fi/model/ktddecv/amountPercentOfBase>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Deferred Payment Date** (<https://iri.suomi.fi/model/ktddecv/deferredPaymentDate>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Payment Due Date** (<https://iri.suomi.fi/model/ktddecv/paymentDueDate>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Payment Terms
**Concept:** *payment term* — *identification of the terms of payment between the parties to a transaction (generic term)
or
the agreed conditions for the timing, method, and amount of payment for goods or services supplied.*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-148>
**Hierarchy:** contract term ▶ payment term
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PaymentTerms>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/PaymentTerms>, <N5cf6305645ff4907a3e3bc3ccf9df4d9>, <https://vocabulary.uncefact.org/PaymentTerms>

**Object properties (domain = this class or via restriction):**
- **has payment schedule line** (<https://iri.suomi.fi/model/ktddecv/hasPaymentScheduleLine>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/PaymentScheduleLine>

**Datatype properties (domain = this class or via restriction):**
- **Payment Term Code** (<https://iri.suomi.fi/model/ktddecv/paymentTermCode>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Period of Time
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PeriodOfTime>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <N422b47b7a60f43978c5be90e23a01c44>

**Datatype properties (domain = this class or via restriction):**
- **End Date** (<https://iri.suomi.fi/model/ktddecv/endDate>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Start Date** (<https://iri.suomi.fi/model/ktddecv/startDate>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Phytosanitary Certificate
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PhytosanitaryCertificate>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <Naf68cdec50d5448490cd0a886eafebc0>

**Datatype properties (domain = this class or via restriction):**
- **Botanical Details** (<https://iri.suomi.fi/model/ktddecv/botanicalDetails>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Postal Address
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PostalAddress>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Presentation
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Presentation>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Promissory Note
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PromissoryNote>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <N1d5e12975c3a43be84f9ae1f8929e449>

**Object properties (domain = this class or via restriction):**
- **drawee party** (<https://iri.suomi.fi/model/ktddecv/draweeParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **drawer party** (<https://iri.suomi.fi/model/ktddecv/drawerParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>

**Datatype properties (domain = this class or via restriction):**
- **Maturity Date** (<https://iri.suomi.fi/model/ktddecv/maturityDate>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Note Number** (<https://iri.suomi.fi/model/ktddecv/noteNumber>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Purchase Order
**Concept:** *purchase order* — *a document by which a buyer requests goods or services from a seller under specified terms*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-228>
**Hierarchy:** Document ▶ purchase order
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PurchaseOrder>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <N65fbf90ca58a4ea8acd946717ae86cb0>

**Object properties (domain = this class or via restriction):**
- **buyer party** (<https://iri.suomi.fi/model/ktddecv/buyerParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **defines payment terms** (<https://iri.suomi.fi/model/ktddecv/definesPaymentTerms>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/PaymentTerms>
- **delivery party** (<https://iri.suomi.fi/model/ktddecv/deliveryParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **has delivery** (<https://iri.suomi.fi/model/ktddecv/hasDelivery>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Delivery>
- **includes allowance charge** (<https://iri.suomi.fi/model/ktddecv/includesAllowanceCharge>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/AllowanceCharge>
- **invoicee party** (<https://iri.suomi.fi/model/ktddecv/invoiceeParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **order amount** (<https://iri.suomi.fi/model/ktddecv/orderAmount>) (restriction) — Range: (unspecified)
- **seller party** (<https://iri.suomi.fi/model/ktddecv/sellerParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>

**Datatype properties (domain = this class or via restriction):**
- **Order Date** (<https://iri.suomi.fi/model/ktddecv/orderDate>) (restriction) — Range: <http://www.w3.org/2001/XMLSchema#dateTime>
- **Order Identifier** (<https://iri.suomi.fi/model/ktddecv/orderIdentifier>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Purchase Order Line
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PurchaseOrderLine>
- **Subclass of:** <https://iri.suomi.fi/model/ktddecv/TradeLineItem>

### Quantity  
**Concept:** *Quantity* — *a numeric measure of count, weight, volume, or dimension expressed in a specified unit*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-112>
**Hierarchy:** Measure ▶ Quantity ▶ customs tariff quantity deduction
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Quantity>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <N815a4de4fc8248c6a51ed056206272d3>, <https://vocabulary.uncefact.org/QuantityType>

**Datatype properties (domain = this class or via restriction):**
- **Quantity Value** (<https://iri.suomi.fi/model/ktddecv/quantityValue>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Unit Code** (<https://iri.suomi.fi/model/ktddecv/unitCode>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Rail Consignment Note CIM
- **IRI:** <https://iri.suomi.fi/model/ktddecv/RailConsignmentNoteCIM>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Regulatory Certificate
- **IRI:** <https://iri.suomi.fi/model/ktddecv/RegulatoryCertificate>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Road Consignment Note CMR
- **IRI:** <https://iri.suomi.fi/model/ktddecv/RoadConsignmentNoteCMR>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Rule Set
- **IRI:** <https://iri.suomi.fi/model/ktddecv/RuleSet>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <N48404151fe0a406ab352bb7ac383215d>

**Object properties (domain = this class or via restriction):**
- **publisher** (<https://iri.suomi.fi/model/ktddecv/publisher>) (restriction) — Range: (unspecified)

**Datatype properties (domain = this class or via restriction):**
- **Publication Date** (<https://iri.suomi.fi/model/ktddecv/publicationDate>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Rule Set Identifier** (<https://iri.suomi.fi/model/ktddecv/ruleSetIdentifier>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Title** (<https://iri.suomi.fi/model/ktddecv/title>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Version Identifier** (<https://iri.suomi.fi/model/ktddecv/versionIdentifier>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Sea Cargo Manifest
- **IRI:** <https://iri.suomi.fi/model/ktddecv/SeaCargoManifest>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Sea Waybill
- **IRI:** <https://iri.suomi.fi/model/ktddecv/SeaWaybill>
- **Description:** Non-negotiable sea transport document serving as a receipt and evidence of the contract of carriage; identifies shipment, parties, vessel/voyage and routing.
- **Subclass of:** <https://iri.suomi.fi/model/ktddecv/TransportDocument>
- **Equivalent to:** <N426851b4df45453794ec719526fc0408>

**Object properties (domain = this class or via restriction):**
- **carrier party** (<https://iri.suomi.fi/model/ktddecv/carrierParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **consignee party** (<https://iri.suomi.fi/model/ktddecv/consigneeParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **freight charges amount** (<https://iri.suomi.fi/model/ktddecv/freightChargesAmount>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
- **freight payable at place** (<https://iri.suomi.fi/model/ktddecv/freightPayableAtPlace>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Location>
- **has dangerous goods** (<https://iri.suomi.fi/model/ktddecv/hasDangerousGoods>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/DangerousGoods>
- **has goods item** (<https://iri.suomi.fi/model/ktddecv/hasGoodsItem>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/GoodsItem>
- **has package** (<https://iri.suomi.fi/model/ktddecv/hasPackage>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Package>
- **has transport equipment** (<https://iri.suomi.fi/model/ktddecv/hasTransportEquipment>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/TransportEquipment>
- **notify party** (<https://iri.suomi.fi/model/ktddecv/notifyParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **other charges amount** (<https://iri.suomi.fi/model/ktddecv/otherChargesAmount>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
- **place of discharge** (<https://iri.suomi.fi/model/ktddecv/placeOfDischarge>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Location>
- **place of issue** (<https://iri.suomi.fi/model/ktddecv/placeOfIssue>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Location>
- **place of loading** (<https://iri.suomi.fi/model/ktddecv/placeOfLoading>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Location>
- **place of receipt** (<https://iri.suomi.fi/model/ktddecv/placeOfReceipt>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Location>
- **shipper party** (<https://iri.suomi.fi/model/ktddecv/shipperParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **total gross weight** (<https://iri.suomi.fi/model/ktddecv/totalGrossWeight>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Quantity>

**Datatype properties (domain = this class or via restriction):**
- **Issue Date** (<https://iri.suomi.fi/model/ktddecv/issueDate>) (restriction) — Range: <http://www.w3.org/2001/XMLSchema#dateTime>
- **Sea Waybill Number** (<https://iri.suomi.fi/model/ktddecv/seaWaybillNumber>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Vessel Name** (<https://iri.suomi.fi/model/ktddecv/vesselName>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Voyage Number** (<https://iri.suomi.fi/model/ktddecv/voyageNumber>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Seal
**Concept:** *seal* — *a device affixed to transport equipment or packages to prevent tampering and provide evidence of unauthorized access*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-244>
**Hierarchy:** logistics asset ▶ seal
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Seal>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Shipment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Shipment>
- **Description:** The set of goods that are the subject of a single sales contract (and usually a single invoice) between a seller and a buyer.
- **Subclass of:** <https://iri.suomi.fi/model/ktddu/0.0.1/Activity>
- **Equivalent to:** <N8e0fc11a4d994e51a5356dcf22fdafd1>

**Object properties (domain = this class or via restriction):**
- **buyer party** (<https://iri.suomi.fi/model/ktddecv/buyerParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **declared customs value amount** (<https://iri.suomi.fi/model/ktddecv/declaredCustomsValueAmount>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
- **delivery terms** (<https://iri.suomi.fi/model/ktddecv/deliveryTerms>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/TradeDeliveryTerms>
- **has goods item** (<https://iri.suomi.fi/model/ktddecv/hasGoodsItem>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/TradeItem>
- **has shipment period** (<https://iri.suomi.fi/model/ktddecv/hasShipmentPeriod>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/PeriodOfTime>
- **insurance value amount** (<https://iri.suomi.fi/model/ktddecv/insuranceValueAmount>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Amount>
- **invoice document** (<https://iri.suomi.fi/model/ktddecv/invoiceDocument>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Document>
- **is realized by consignment** (<https://iri.suomi.fi/model/ktddecv/isRealizedByConsignment>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Consignment>
- **related order** (<https://iri.suomi.fi/model/ktddecv/relatedOrder>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/PurchaseOrder>
- **requested delivery period** (<https://iri.suomi.fi/model/ktddecv/requestedDeliveryPeriod>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/PeriodOfTime>
- **seller party** (<https://iri.suomi.fi/model/ktddecv/sellerParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **total goods item quantity** (<https://iri.suomi.fi/model/ktddecv/totalGoodsItemQuantity>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Quantity>
- **total package quantity** (<https://iri.suomi.fi/model/ktddecv/totalPackageQuantity>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Quantity>
- **total transport handling unit quantity** (<https://iri.suomi.fi/model/ktddecv/totalTransportHandlingUnitQuantity>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Quantity>

**Datatype properties (domain = this class or via restriction):**
- **Contract Number** (<https://iri.suomi.fi/model/ktddecv/contractNumber>) (restriction) — Range: <http://www.w3.org/2001/XMLSchema#string>
- **Final Destination UN Locode** (<https://iri.suomi.fi/model/ktddecv/finalDestinationUNLocode>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Hazardous Risk Indicator** (<https://iri.suomi.fi/model/ktddecv/hazardousRiskIndicator>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Place of Delivery UN Locode** (<https://iri.suomi.fi/model/ktddecv/placeOfDeliveryUNLocode>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Place of Receipt UN Locode** (<https://iri.suomi.fi/model/ktddecv/placeOfReceiptUNLocode>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Port Of Discharge UN Locode** (<https://iri.suomi.fi/model/ktddecv/portOfDischargeUNLocode>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Port of Loading UN Locode** (<https://iri.suomi.fi/model/ktddecv/portOfLoadingUNLocode>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Shipment Identifier** (<https://iri.suomi.fi/model/ktddecv/shipmentIdentifier>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Shipment Basis
- **IRI:** <https://iri.suomi.fi/model/ktddecv/ShipmentBasis>
- **Subclass of:** <http://www.w3.org/2004/02/skos/core#Concept>

### Ships Delivery Order
- **IRI:** <https://iri.suomi.fi/model/ktddecv/ShipsDeliveryOrder>
- **Description:** A document issued by a carrier or its agent authorizing delivery of the goods to the consignee or other named party. Used after arrival of a vessel to release cargo covered by a bill of lading or sea waybill.
- **Subclass of:** <https://iri.suomi.fi/model/ktddecv/TransportDocument>
- **Equivalent to:** <N9cdb4d00301a40b482358a968a0cbd1a>

**Object properties (domain = this class or via restriction):**
- **carrier party** (<https://iri.suomi.fi/model/ktddecv/carrierParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **consignee party** (<https://iri.suomi.fi/model/ktddecv/consigneeParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **notify party** (<https://iri.suomi.fi/model/ktddecv/notifyParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **relates to transport document** (<https://iri.suomi.fi/model/ktddecv/relatesToTransportDocument>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/TransportDocument>

**Datatype properties (domain = this class or via restriction):**
- **Ships Delivery Order Number** (<https://iri.suomi.fi/model/ktddecv/shipsDeliveryOrderNumber>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Status
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Status>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Tenor
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Tenor>
- **Description:** Rule that determines when a payment/obligation under a negotiable or deferred-payment instrument becomes due.
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### TIR Carnet
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TIRCarnet>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Trade Delivery Terms
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TradeDeliveryTerms>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <Nf0a9a9b987974e2585ead2d81816d2e7>

**Object properties (domain = this class or via restriction):**
- **applicable rules** (<https://iri.suomi.fi/model/ktddecv/applicableRules>) (restriction) — Range: <http://www.w3.org/2004/02/skos/core#Concept>
- **has delivery period** (<https://iri.suomi.fi/model/ktddecv/hasDeliveryPeriod>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/PeriodOfTime>
- **includes allowance charge** (<https://iri.suomi.fi/model/ktddecv/includesAllowanceCharge>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/AllowanceCharge>
- **incoterms code** (<https://iri.suomi.fi/model/ktddecv/incotermsCode>) (restriction) — Range: <http://www.w3.org/2004/02/skos/core#Concept>
- **place of delivery** (<https://iri.suomi.fi/model/ktddecv/placeOfDelivery>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Location>
- **place of discharge** (<https://iri.suomi.fi/model/ktddecv/placeOfDischarge>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Location>
- **place of loading** (<https://iri.suomi.fi/model/ktddecv/placeOfLoading>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Location>
- **relates to consignment** (<https://iri.suomi.fi/model/ktddecv/relatesToConsignment>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Consignment>

**Datatype properties (domain = this class or via restriction):**
- **Delivery Terms Text** (<https://iri.suomi.fi/model/ktddecv/deliveryTermsText>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Trade Item
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TradeItem>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <https://iri.suomi.fi/model/ktddecv/TradeProduct>

### Trade Line Item
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TradeLineItem>
- **Description:** A distinct line item in a trade transaction, representing an ordered, invoiced, shipped, or declared good or service, including its quantity, price, and related references.
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Trade Product
**Concept:** *trade product* — *a product or service offered for commercial exchange in international trade, identified by its commercial, legal, or regulatory characteristics such as name, description, classification code, or digital product passport*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-264>
**Hierarchy:** Trade Object ▶ trade product ▶ goods item
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TradeProduct>
- **Description:** A product or service offered or supplied in trade, identified and classified for commercial, fiscal or regulatory purposes.
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <N0f848d1bf61a459b8b49ced478bf6efb>, <https://vocabulary.uncefact.org/TradeProduct>

**Object properties (domain = this class or via restriction):**
- **applicable commodity classification** (<https://iri.suomi.fi/model/ktddecv/applicableCommodityClassification>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/CommodityClassification>
- **has characteristic** (<https://iri.suomi.fi/model/ktddecv/hasCharacteristic>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Characteristic>
- **origin country** (<https://iri.suomi.fi/model/ktddecv/originCountry>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Country>

**Datatype properties (domain = this class or via restriction):**
- **Product Description** (<https://iri.suomi.fi/model/ktddecv/productDescription>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Product Name** (<https://iri.suomi.fi/model/ktddecv/productName>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Transit Accompanying Document
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TransitAccompanyingDocument>
- **Description:** The Transit Accompanying Document (TAD) used in the EU Common Transit procedure, identified by an MRN and containing information about offices of departure, destination, and transit.
- **Subclass of:** <https://iri.suomi.fi/model/ktddecv/Document>
- **Equivalent to:** <Nd7182b5b0ec24b2c862ba3365a0084d4>

**Object properties (domain = this class or via restriction):**
- **office of departure** (<https://iri.suomi.fi/model/ktddecv/officeOfDeparture>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Location>
- **office of destination** (<https://iri.suomi.fi/model/ktddecv/officeOfDestination>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Location>
- **transit office** (<https://iri.suomi.fi/model/ktddecv/transitOffice>) (restriction) — Range: (unspecified)

**Datatype properties (domain = this class or via restriction):**
- **MRN** (<https://iri.suomi.fi/model/ktddecv/mrn>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Transport Document
**Concept:** *transport document* — *a document evidencing a contract of carriage and receipt of goods by a carrier, such as a bill of lading, waybill, or consignment note*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-226>
**Hierarchy:** Document ▶ transport document ▶ negotiable transport document
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TransportDocument>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <Nac399b0a826d4c8f9c1b5299e36fcbcf>

**Object properties (domain = this class or via restriction):**
- **carrier party** (<https://iri.suomi.fi/model/ktddecv/carrierParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **consignee party** (<https://iri.suomi.fi/model/ktddecv/consigneeParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **freight payable at place** (<https://iri.suomi.fi/model/ktddecv/freightPayableAtPlace>) (restriction) — Range: <https://iri.suomi.fi/model/ktddu/0.0.1/Place>
- **has goods item** (<https://iri.suomi.fi/model/ktddecv/hasGoodsItem>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/GoodsItem>
- **has package** (<https://iri.suomi.fi/model/ktddecv/hasPackage>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Package>
- **notify party** (<https://iri.suomi.fi/model/ktddecv/notifyParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **place of delivery** (<https://iri.suomi.fi/model/ktddecv/placeOfDelivery>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Location>
- **place of issue** (<https://iri.suomi.fi/model/ktddecv/placeOfIssue>) (restriction) — Range: <https://iri.suomi.fi/model/ktddu/0.0.1/Place>
- **place of loading** (<https://iri.suomi.fi/model/ktddecv/placeOfLoading>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Location>
- **relates to consignment** (<https://iri.suomi.fi/model/ktddecv/relatesToConsignment>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Consignment>
- **shipper party** (<https://iri.suomi.fi/model/ktddecv/shipperParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **transport document type code** (<https://iri.suomi.fi/model/ktddecv/transportDocumentTypeCode>) (restriction) — Range: <http://www.w3.org/2004/02/skos/core#Concept>

**Datatype properties (domain = this class or via restriction):**
- **Freight Payment Term Code** (<https://iri.suomi.fi/model/ktddecv/freightPaymentTermCode>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Issue Date** (<https://iri.suomi.fi/model/ktddecv/issueDate>) (restriction) — Range: <http://www.w3.org/2001/XMLSchema#dateTime>
- **Number of Originals** (<https://iri.suomi.fi/model/ktddecv/numberOfOriginals>) (restriction) — Range: <http://www.w3.org/2001/XMLSchema#integer>
- **On Board Date** (<https://iri.suomi.fi/model/ktddecv/onBoardDate>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Transport Document Number** (<https://iri.suomi.fi/model/ktddecv/transportDocumentNumber>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Vessel Name** (<https://iri.suomi.fi/model/ktddecv/vesselName>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Voyage Number** (<https://iri.suomi.fi/model/ktddecv/voyageNumber>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Transport Equipment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TransportEquipment>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <N3e61fbcc908f4a2b88d897ead7fa0eb1>

**Object properties (domain = this class or via restriction):**
- **equipment identifier** (<https://iri.suomi.fi/model/ktddecv/equipmentIdentifier>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Identifier>

### Transport Event
**Concept:** *Transport Event* — *an event associated with the movement of goods or transport equipment*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-207>
**Hierarchy:** Event ▶ Transport Event ▶ arrival event
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TransportEvent>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <https://vocabulary.uncefact.org/TransportEvent>, <https://iri.suomi.fi/model/busdoc/1.0.2/TransportEvent>, <N32561195ce6445e7a345690958c5c232>

**Object properties (domain = this class or via restriction):**
- **event identifier** (<https://iri.suomi.fi/model/ktddecv/eventIdentifier>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Identifier>
- **event place** (<https://iri.suomi.fi/model/ktddecv/eventPlace>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Location>
- **event type code** (<https://iri.suomi.fi/model/ktddecv/eventTypeCode>) (restriction) — Range: <http://www.w3.org/2004/02/skos/core#Concept>
- **observed transport means** (<https://iri.suomi.fi/model/ktddecv/observedTransportMeans>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/TransportMeans>
- **relates to consignment** (<https://iri.suomi.fi/model/ktddecv/relatesToConsignment>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Consignment>
- **relates to goods item** (<https://iri.suomi.fi/model/ktddecv/relatesToGoodsItem>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/GoodsItem>
- **relates to package** (<https://iri.suomi.fi/model/ktddecv/relatesToPackage>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Package>
- **relates to transport document** (<https://iri.suomi.fi/model/ktddecv/relatesToTransportDocument>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/TransportDocument>
- **reported by party** (<https://iri.suomi.fi/model/ktddecv/reportedByParty>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **transport mode code** (<https://iri.suomi.fi/model/ktddecv/transportModeCode>) (restriction) — Range: <http://www.w3.org/2004/02/skos/core#Concept>
- **uses transport means** (<https://iri.suomi.fi/model/ktddecv/usesTransportMeans>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/TransportMeans>

**Datatype properties (domain = this class or via restriction):**
- **Event Date Time** (<https://iri.suomi.fi/model/ktddecv/eventDateTime>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Event Note Text** (<https://iri.suomi.fi/model/ktddecv/eventNoteText>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Transport Leg
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TransportLeg>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <Nf5aea5cb444f48fa8d20eabc7e5a9166>

**Object properties (domain = this class or via restriction):**
- **arrival place** (<https://iri.suomi.fi/model/ktddecv/arrivalPlace>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Location>
- **departure place** (<https://iri.suomi.fi/model/ktddecv/departurePlace>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/Location>
- **uses transport equipment** (<https://iri.suomi.fi/model/ktddecv/usesTransportEquipment>) (restriction) — Range: <https://iri.suomi.fi/model/ktddecv/TransportEquipment>

**Datatype properties (domain = this class or via restriction):**
- **Arrival Date Time** (<https://iri.suomi.fi/model/ktddecv/arrivalDateTime>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Departure Date Time** (<https://iri.suomi.fi/model/ktddecv/departureDateTime>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Transport Means
**Concept:** *transport means* — *a physical vehicle or vessel used to move goods (e.g., ship, aircraft, truck)*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-209>
**Hierarchy:** transport entity ▶ transport means ▶ vehicle registration number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TransportMeans>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <N8d2eab5203fe412bb0e2170b7491ec4a>

**Datatype properties (domain = this class or via restriction):**
- **Flight Number** (<https://iri.suomi.fi/model/ktddecv/flightNumber>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **IMO Ship ID** (<https://iri.suomi.fi/model/ktddecv/iMOShipID>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Vehicle Name** (<https://iri.suomi.fi/model/ktddecv/vehicleName>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Veterinary Certificate
**Concept:** *veterinary certificate* — *an official certificate verifying that animals or animal products meet the health requirements of the importing country*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-232>
**Hierarchy:** certificate ▶ veterinary certificate
- **IRI:** <https://iri.suomi.fi/model/ktddecv/VeterinaryCertificate>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>
- **Equivalent to:** <N09f6ef2620244348999e408a3a6aa698>

**Datatype properties (domain = this class or via restriction):**
- **Origin Establishment** (<https://iri.suomi.fi/model/ktddecv/originEstablishment>) (restriction) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Warehouse
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Warehouse>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Warehouse Receipt
- **IRI:** <https://iri.suomi.fi/model/ktddecv/WarehouseReceipt>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

## Object Properties

### additional amounts covered
- **IRI:** <https://iri.suomi.fi/model/ktddecv/additionalAmountsCovered>

### advise through bank party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/adviseThroughBankParty>

### advising bank party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/advisingBankParty>
- **Description:** Association from a documentary credit (letter of credit) to the bank that advises the credit (and any amendments) to the beneficiary.

### airport of departure
- **IRI:** <https://iri.suomi.fi/model/ktddecv/airportOfDeparture>

### airport of destination
- **IRI:** <https://iri.suomi.fi/model/ktddecv/airportOfDestination>

### applicable commodity classification
- **IRI:** <https://iri.suomi.fi/model/ktddecv/applicableCommodityClassification>

### applicable rules
- **IRI:** <https://iri.suomi.fi/model/ktddecv/applicableRules>

### applicant bank party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/applicantBankParty>

### applicant party
**Concept:** *documentary credit applicant* — *a party, usually the buyer/importer, that requests a bank to issue a documentary credit in favour of a beneficiary (seller/exporter) in order to secure payment for goods or services*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-92>
**Hierarchy:** applicant ▶ documentary credit applicant
- **IRI:** <https://iri.suomi.fi/model/ktddecv/applicantParty>

### applied commodity classification
- **IRI:** <https://iri.suomi.fi/model/ktddecv/appliedCommodityClassification>

### arrival place
- **IRI:** <https://iri.suomi.fi/model/ktddecv/arrivalPlace>

### available at place
- **IRI:** <https://iri.suomi.fi/model/ktddecv/availableAtPlace>

### available with party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/availableWithParty>

### available with qualifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/availableWithQualifier>

### base amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/baseAmount>

### beneficiary party
**Concept:** *documentary credit beneficiary* — *a party in whose favour a documentary credit is issued and who is entitled to claim payment from the issuing or confirming bank upon presentation of compliant documents*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-86>
**Hierarchy:** beneficiary ▶ documentary credit beneficiary
- **IRI:** <https://iri.suomi.fi/model/ktddecv/beneficiaryParty>

### buyer party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/buyerParty>

### carrier party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/carrierParty>
- **Description:** For Sea Waybill: The ocean carrier issuing or responsible for the carriage.


### certificate number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/certificateNumber>

### chargeable weight
- **IRI:** <https://iri.suomi.fi/model/ktddecv/chargeableWeight>

### charged by party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/chargedByParty>

### charged to party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/chargedToParty>

### claims payable at place
- **IRI:** <https://iri.suomi.fi/model/ktddecv/claimsPayableAtPlace>

### confirmation instruction code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/confirmationInstructionCode>
- **Description:** Code indicating whether confirmation is requested, may be added, or is without confirmation.
- **Range:** <http://www.w3.org/2004/02/skos/core#Concept>

### confirming bank party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/confirmingBankParty>

### confirming party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/confirmingParty>
- **Description:** Party that actually added confirmation.

### consignee party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/consigneeParty>
- **Description:** The party to whom the goods are to be delivered.

### consignment identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/consignmentIdentifier>

### consignor party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/consignorParty>

### country of origin code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/countryOfOriginCode>
- **Description:** Country of non-preferential or preferential origin for the goods line, as an ISO 3166-1 code concept.
- **Range:** <http://www.w3.org/2004/02/skos/core#Concept>

### coverage amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/coverageAmount>

### coverage type code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/coverageTypeCode>

### covered shipment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/coveredShipment>

### covers additional charge
- **IRI:** <https://iri.suomi.fi/model/ktddecv/coversAdditionalCharge>

### covers contract
- **IRI:** <https://iri.suomi.fi/model/ktddecv/coversContract>

### creditor specified financial institution
- **IRI:** <https://iri.suomi.fi/model/ktddecv/creditorSpecifiedFinancialInstitution>

### customs procedure code 
- **IRI:** <https://iri.suomi.fi/model/ktddecv/customsProcedureCode>

### declarant party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/declarantParty>

### declaration number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/declarationNumber>
- **Description:** National MRN or declaration number as Identifier node.

### declared customs value amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/declaredCustomsValueAmount>
- **Range:** <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>

### declared value for carriage
- **IRI:** <https://iri.suomi.fi/model/ktddecv/declaredValueForCarriage>

### defines payment terms
- **IRI:** <https://iri.suomi.fi/model/ktddecv/definesPaymentTerms>

### delivered to
**Concept:** *Ship to / Delivery Party* — *Party to which goods should be delivered, if not identical with consignee such as the place where a container is to be, or has been, positioned.*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-14>
**Hierarchy:** Ship to / Delivery Party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/deliveredTo>

### delivery location
- **IRI:** <https://iri.suomi.fi/model/ktddecv/deliveryLocation>
- **Range:** <https://iri.suomi.fi/model/ktddecv/Location>

### delivery party
**Concept:** *Ship to / Delivery Party* — *Party to which goods should be delivered, if not identical with consignee such as the place where a container is to be, or has been, positioned.*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-14>
**Hierarchy:** Ship to / Delivery Party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/deliveryParty>

### delivery terms
- **IRI:** <https://iri.suomi.fi/model/ktddecv/deliveryTerms>

### departure place
- **IRI:** <https://iri.suomi.fi/model/ktddecv/departurePlace>

### describes item
- **IRI:** <https://iri.suomi.fi/model/ktddecv/describesItem>

### describes trade product
- **IRI:** <https://iri.suomi.fi/model/ktddecv/describesTradeProduct>

### document type
- **IRI:** <https://iri.suomi.fi/model/ktddecv/documentType>
- **Range:** <http://www.w3.org/2004/02/skos/core#Concept>

### drafts at tenor
- **IRI:** <https://iri.suomi.fi/model/ktddecv/draftsAtTenor>

### drawee party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/draweeParty>
- **Description:** Party on whom a demand for payment is drawn and who is ordered to pay (e.g., in a bill of exchange/draft/cheque).

### drawer party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/drawerParty>

### equipment identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/equipmentIdentifier>

### event identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/eventIdentifier>

### event place
- **IRI:** <https://iri.suomi.fi/model/ktddecv/eventPlace>

### event type code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/eventTypeCode>

### exporter party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/exporterParty>

### final destination place
- **IRI:** <https://iri.suomi.fi/model/ktddecv/finalDestinationPlace>

### first place of receipt
- **IRI:** <https://iri.suomi.fi/model/ktddecv/firstPlaceOfReceipt>

### for goods item
- **IRI:** <https://iri.suomi.fi/model/ktddecv/forGoodsItem>

### freight charges amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/freightChargesAmount>

### freight payable at place
- **IRI:** <https://iri.suomi.fi/model/ktddecv/freightPayableAtPlace>

### from location
- **IRI:** <https://iri.suomi.fi/model/ktddecv/fromLocation>

### governed by rule set
- **IRI:** <https://iri.suomi.fi/model/ktddecv/governedByRuleSet>

### has Address
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasAddress>

### has amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasAmount>

### has applicant
**Concept:** *documentary credit applicant* — *a party, usually the buyer/importer, that requests a bank to issue a documentary credit in favour of a beneficiary (seller/exporter) in order to secure payment for goods or services*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-92>
**Hierarchy:** applicant ▶ documentary credit applicant
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasApplicant>

### has applicant bank
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasApplicantBank>

### has availability method
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasAvailabilityMethod>

### has beneficiary
**Concept:** *documentary credit beneficiary* — *a party in whose favour a documentary credit is issued and who is entitled to claim payment from the issuing or confirming bank upon presentation of compliant documents*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-86>
**Hierarchy:** beneficiary ▶ documentary credit beneficiary
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasBeneficiary>

### has buyer
**Concept:** *buyer* — *a party to which merchandise or services are sold
or
the party that purchases goods or services under a trade contract*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-38>
**Hierarchy:** party role ▶ buyer
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasBuyer>

### has characteristic
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasCharacteristic>

### has classification scheme
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasClassificationScheme>

### has commodity classification
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasCommodityClassification>
- **Description:** Associates an item line with a commodity/service classification entry.

### has consignment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasConsignment>

### has country of origin
**Concept:** *origin country* — *the country in which the goods have been produced or manufactured, according to criteria laid down for the application of the Customs tariff or quantitative restrictions, or any measure related to trade*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-62>
**Hierarchy:** country ▶ origin country
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasCountryOfOrigin>

### has credit availability
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasCreditAvailability>

### has dangerous goods
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasDangerousGoods>

### has dangerous goods details
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasDangerousGoodsDetails>

### has delivery
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasDelivery>
- **Range:** <https://iri.suomi.fi/model/ktddecv/Delivery>

### has delivery milestone
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasDeliveryMilestone>

### has delivery period
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasDeliveryPeriod>

### has drawee
**Concept:** *drawee* — *the party on whom a bill of exchange or similar negotiable instrument is drawn, and who is thereby ordered to pay*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-61>
**Hierarchy:** party role ▶ drawee
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasDrawee>

### has goods item
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasGoodsItem>

### has identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasIdentifier>

### has invoice line
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasInvoiceLine>

### has invoicee
**Concept:** *invoicee* — *a party to whom an invoice is issued*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-50>
**Hierarchy:** party role ▶ invoicee
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasInvoicee>

### has message
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasMessage>

### has package
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasPackage>

### has package item
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasPackageItem>

### has payment line
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasPaymentLine>

### has payment schedule line
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasPaymentScheduleLine>

### has payment terms
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasPaymentTerms>
- **Range:** <https://iri.suomi.fi/model/ktddecv/PaymentTerms>

### has presentation
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasPresentation>

### has presentation period
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasPresentationPeriod>

### has product
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasProduct>

### has quantity
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasQuantity>

### has seller
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasSeller>

### has shipment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasShipment>

### has shipment period
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasShipmentPeriod>

### has status
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasStatus>

### has tenor
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasTenor>

### has transport equipment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasTransportEquipment>

### has transport event
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasTransportEvent>

### importer party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/importerParty>

### includes allowance charge
- **IRI:** <https://iri.suomi.fi/model/ktddecv/includesAllowanceCharge>

### includes duty tax fee
- **IRI:** <https://iri.suomi.fi/model/ktddecv/includesDutyTaxFee>

### incoterms code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/incotermsCode>

### incoterms location
- **IRI:** <https://iri.suomi.fi/model/ktddecv/incotermsLocation>

### inner packaging quantity
- **IRI:** <https://iri.suomi.fi/model/ktddecv/innerPackagingQuantity>

### instructed party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/instructedParty>

### instructing party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/instructingParty>

### instruction to bank
- **IRI:** <https://iri.suomi.fi/model/ktddecv/instructionToBank>

### insurance value amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/insuranceValueAmount>

### insured amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/insuredAmount>

### insured party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/insuredParty>

### insurer party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/insurerParty>

### invoice document
- **IRI:** <https://iri.suomi.fi/model/ktddecv/invoiceDocument>

### invoice payment terms
- **IRI:** <https://iri.suomi.fi/model/ktddecv/invoicePaymentTerms>

### invoiced quantity
- **IRI:** <https://iri.suomi.fi/model/ktddecv/invoicedQuantity>

### invoicee party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/invoiceeParty>

### is realized by consignment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/isRealizedByConsignment>

### issuer party
**Concept:** *issuer* — *a competent authority or organization that formally issues a permit, certificate, carnet, financial instrument, or other official document, giving it legal validity*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-71>
**Hierarchy:** party role ▶ issuer
- **IRI:** <https://iri.suomi.fi/model/ktddecv/issuerParty>
- **Range:** <https://iri.suomi.fi/model/ktddecv/Party>

### issuing authority party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/issuingAuthorityParty>

### issuing bank party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/issuingBankParty>

### issuing carrier party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/issuingCarrierParty>

### location country
- **IRI:** <https://iri.suomi.fi/model/ktddecv/locationCountry>

### maximum credit amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/maximumCreditAmount>
- **Description:** An instruction on a Documentary Credit that the stated credit amount is an absolute ceiling: the total of drawings/claims under the credit must not exceed the stated amount. It is used to cap drawings even where tolerances or qualifying words (e.g., “about/approximately”) might otherwise allow variation.

### net quantity per package
- **IRI:** <https://iri.suomi.fi/model/ktddecv/netQuantityPerPackage>

### nominated bank party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/nominatedBankParty>

### notify party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/notifyParty>

### obligee party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/obligeeParty>
- **Description:** Party entitled to receive the performance of an obligation (a payment, delivery, or service).

### obligor party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/obligorParty>
- **Description:** Party that bears a duty to perform an obligation (e.g., pay money, deliver goods, perform a service) under a business commitment.

### observed transport means
- **IRI:** <https://iri.suomi.fi/model/ktddecv/observedTransportMeans>

### office of departure
- **IRI:** <https://iri.suomi.fi/model/ktddecv/officeOfDeparture>
- **Description:** The customs office of departure where the transit procedure begins.

### office of destination
- **IRI:** <https://iri.suomi.fi/model/ktddecv/officeOfDestination>

### order amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/orderAmount>

### origin country
**Concept:** *origin country* — *the country in which the goods have been produced or manufactured, according to criteria laid down for the application of the Customs tariff or quantitative restrictions, or any measure related to trade*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-62>
**Hierarchy:** country ▶ origin country
- **IRI:** <https://iri.suomi.fi/model/ktddecv/originCountry>

### other charges amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/otherChargesAmount>

### package type code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/packageTypeCode>

### packing list number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/packingListNumber>

### party address
- **IRI:** <https://iri.suomi.fi/model/ktddecv/partyAddress>

### party identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/partyIdentifier>

### party legal entity
- **IRI:** <https://iri.suomi.fi/model/ktddecv/partyLegalEntity>

### payee party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/payeeParty>
- **Description:** Party to whom a payment is to be made under an obligation or instrument.

### payer party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/payerParty>

### payment location
**Concept:** *place of payment* — *the location where payment is to be made or is legally enforceable, as specified in a financial document*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-77>
**Hierarchy:** Location ▶ place of payment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/paymentLocation>

### payment settlement method
- **IRI:** <https://iri.suomi.fi/model/ktddecv/paymentSettlementMethod>

### per unit amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/perUnitAmount>

### place of delivery
**Concept:** *place of delivery* — *the location at which the goods are handed over to the consignee or a designated party, marking the completion of the delivery obligation*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-57>
**Hierarchy:** Location ▶ place of delivery
- **IRI:** <https://iri.suomi.fi/model/ktddecv/placeOfDelivery>

### place of discharge
- **IRI:** <https://iri.suomi.fi/model/ktddecv/placeOfDischarge>
- **Description:** The location where goods are taken off a means of transport.

### place of expiry
- **IRI:** <https://iri.suomi.fi/model/ktddecv/placeOfExpiry>
- **Description:** The place of presentation for the credit (typically “at the counters of … [named bank/branch/location]”). In eUCP contexts, the “place” may be physical (bank/location) and/or an electronic address/system designated for presentation.

### place of issue
- **IRI:** <https://iri.suomi.fi/model/ktddecv/placeOfIssue>

### place of loading
**Concept:** *place of loading* — *TBD*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-98>
**Hierarchy:** Location ▶ place of loading
- **IRI:** <https://iri.suomi.fi/model/ktddecv/placeOfLoading>

### place of presentation
- **IRI:** <https://iri.suomi.fi/model/ktddecv/placeOfPresentation>
- **Description:** The location at which a document, good, declaration, or other required item is formally presented to a designated party or authority.

In the context of a Documentary Credit, the location specified for the presentation of documents by the beneficiary to the nominated bank, confirming bank, or issuing bank for examination and payment.
- **Range:** <https://iri.suomi.fi/model/ktddecv/Location>

### place of receipt
- **IRI:** <https://iri.suomi.fi/model/ktddecv/placeOfReceipt>

### place of taking in charge
- **IRI:** <https://iri.suomi.fi/model/ktddecv/placeOfTakingInCharge>
- **Description:** The location at which a carrier or other responsible party takes goods, consignments, or transport equipment into their charge for further carriage, handling, or responsibility in the transport chain.
- **Range:** <https://iri.suomi.fi/model/ktddecv/Location>

### preference criterion code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/preferenceCriterionCode>

### presentation base event
- **IRI:** <https://iri.suomi.fi/model/ktddecv/presentationBaseEvent>

### publisher
- **IRI:** <https://iri.suomi.fi/model/ktddecv/publisher>

### receiver party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/receiverParty>

### references letter of credit
- **IRI:** <https://iri.suomi.fi/model/ktddecv/referencesLetterOfCredit>
- **Range:** <https://iri.suomi.fi/model/ktddecv/DocumentaryCredit>

### references pre advice
- **IRI:** <https://iri.suomi.fi/model/ktddecv/referencesPreAdvice>

### reimbursing bank party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/reimbursingBankParty>

### related order
- **IRI:** <https://iri.suomi.fi/model/ktddecv/relatedOrder>

### relates to consignment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/relatesToConsignment>

### relates to goods item
- **IRI:** <https://iri.suomi.fi/model/ktddecv/relatesToGoodsItem>

### relates to invoice
- **IRI:** <https://iri.suomi.fi/model/ktddecv/relatesToInvoice>

### relates to package
- **IRI:** <https://iri.suomi.fi/model/ktddecv/relatesToPackage>

### relates to transport document
- **IRI:** <https://iri.suomi.fi/model/ktddecv/relatesToTransportDocument>

### reported by party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/reportedByParty>

### requested confirmation party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/requestedConfirmationParty>
- **Description:** Party requested to add confirmation.

### requested delivery period
- **IRI:** <https://iri.suomi.fi/model/ktddecv/requestedDeliveryPeriod>

### required document type
- **IRI:** <https://iri.suomi.fi/model/ktddecv/requiredDocumentType>
- **Range:** <http://www.w3.org/2004/02/skos/core#Concept>

### requires document
- **IRI:** <https://iri.suomi.fi/model/ktddecv/requiresDocument>

### seal identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/sealIdentifier>

### seller party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/sellerParty>

### sender party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/senderParty>

### shipper party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/shipperParty>

### sscc
- **IRI:** <https://iri.suomi.fi/model/ktddecv/sscc>

### statistical value amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/statisticalValueAmount>

### surety party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/suretyParty>

### tenor period
- **IRI:** <https://iri.suomi.fi/model/ktddecv/tenorPeriod>
- **Range:** <https://iri.suomi.fi/model/ktddecv/PeriodOfTime>

### to location
- **IRI:** <https://iri.suomi.fi/model/ktddecv/toLocation>

### total amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/totalAmount>

### total goods item quantity
- **IRI:** <https://iri.suomi.fi/model/ktddecv/totalGoodsItemQuantity>

### total gross weight
- **IRI:** <https://iri.suomi.fi/model/ktddecv/totalGrossWeight>

### total invoice amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/totalInvoiceAmount>

### total net weight
- **IRI:** <https://iri.suomi.fi/model/ktddecv/totalNetWeight>

### total package count
- **IRI:** <https://iri.suomi.fi/model/ktddecv/totalPackageCount>

### total package quantity
- **IRI:** <https://iri.suomi.fi/model/ktddecv/totalPackageQuantity>

### total transport handling unit quantity
- **IRI:** <https://iri.suomi.fi/model/ktddecv/totalTransportHandlingUnitQuantity>

### transit office
- **IRI:** <https://iri.suomi.fi/model/ktddecv/transitOffice>

### transport document type code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/transportDocumentTypeCode>
- **Range:** <http://www.w3.org/2004/02/skos/core#Concept>

### transport mode code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/transportModeCode>

### transshipment place
- **IRI:** <https://iri.suomi.fi/model/ktddecv/transshipmentPlace>

### uses transport equipment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/usesTransportEquipment>

### uses transport means
- **IRI:** <https://iri.suomi.fi/model/ktddecv/usesTransportMeans>

### validity period
- **IRI:** <https://iri.suomi.fi/model/ktddecv/validityPeriod>

## Datatype Properties

### Actual Arrival Date Time
- **IRI:** <https://iri.suomi.fi/model/ktddecv/actualArrivalDateTime>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Actual Departure Date Time
- **IRI:** <https://iri.suomi.fi/model/ktddecv/actualDepartureDateTime>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Additional Conditions Text
- **IRI:** <https://iri.suomi.fi/model/ktddecv/additionalConditionsText>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Airport of Departure IATA Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/airportOfDepartureIATACode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Airport of Destination IATA Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/airportOfDestinationIATACode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Allowance Charge Reason Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/allowanceChargeReasonCode>
- **Description:** Enumerated “charge reason” code list (e.g., ADVISE, CONFIRMATION, AMENDMENT, NEGOTIATION, DISCREPANCY, COURIER, SWIFT, HANDLING, OTHER).
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Alternate Name
- **IRI:** <https://iri.suomi.fi/model/ktddecv/alternateName>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Amount Percent Of Base
- **IRI:** <https://iri.suomi.fi/model/ktddecv/amountPercentOfBase>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Amount Tolerance Percent
- **IRI:** <https://iri.suomi.fi/model/ktddecv/amountTolerancePercent>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Amount Value
- **IRI:** <https://iri.suomi.fi/model/ktddecv/amountValue>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Arrival Date Time
- **IRI:** <https://iri.suomi.fi/model/ktddecv/arrivalDateTime>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Available At Locode
- **IRI:** <https://iri.suomi.fi/model/ktddecv/availableAtLocode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Available With By
- **IRI:** <https://iri.suomi.fi/model/ktddecv/availableWithBy>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Bank Account Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/bankAccountIdentifier>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Bond Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/bondNumber>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Border Crossing Point Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/borderCrossingPointCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Botanical Details
- **IRI:** <https://iri.suomi.fi/model/ktddecv/botanicalDetails>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Calculation Percent
- **IRI:** <https://iri.suomi.fi/model/ktddecv/calculationPercent>
- **Description:** Percentage when the charge is calculated from a base amount.
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Charge Indicator
- **IRI:** <https://iri.suomi.fi/model/ktddecv/chargeIndicator>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Classification Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/classificationCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Commodity Code
**Concept:** *HS code (commodity code)* — *a code specifying a type of goods for Customs, transport or statistical purposes (generic term)*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-188>
**Hierarchy:** code ▶ HS code (commodity code)
- **IRI:** <https://iri.suomi.fi/model/ktddecv/commodityCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Confirmation Added Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/confirmationAddedDate>
- **Description:** Date on which confirmation became effective.
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Confirmation Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/confirmationDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Container Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/containerNumber>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Contract Identifier
**Concept:** *contract identifier* — *a unique identifier assigned to a contract by the issuing party or by an agreed registration scheme*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-9>
**Hierarchy:** Identifier ▶ contract identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/contractIdentifier>
- **Range:** <http://www.w3.org/2001/XMLSchema#string>

### Contract Number
**Concept:** *contract identifier* — *a unique identifier assigned to a contract by the issuing party or by an agreed registration scheme*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-9>
**Hierarchy:** Identifier ▶ contract identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/contractNumber>
- **Range:** <http://www.w3.org/2001/XMLSchema#string>

### Country Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/countryCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Country Name
- **IRI:** <https://iri.suomi.fi/model/ktddecv/countryName>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Credit Amount Tolerance Percentage
- **IRI:** <https://iri.suomi.fi/model/ktddecv/creditAmountTolerancePercentage>
- **Description:** A percentage tolerance applied to the stated credit amount, expressed as a decimal value (e.g. ±10). This indicates by how much drawings may exceed or fall short of the stated amount, without affecting the unit price of goods.
- **Range:** <http://www.w3.org/2001/XMLSchema#decimal>

### Credit Identifier
**Concept:** *documentary credit identifier* — *a unique reference assigned by the issuing bank to a documentary credit, used to identify and trace the credit throughout its lifecycle and across related trade, transport, and financial documents*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-29>
**Hierarchy:** Identifier ▶ documentary credit identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/creditIdentifier>
- **Range:** <http://www.w3.org/2001/XMLSchema#string>

### Currency Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/currencyCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Customs Office Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/customsOfficeCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Declaration Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/declarationDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Deferred Payment Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/deferredPaymentDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Delivery Date
**Concept:** *delivery date (qualifier)* — *qualifier indicating that the date/time refers to delivery of goods*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-42>
**Hierarchy:** date/time qualifier ▶ delivery date (qualifier)
- **IRI:** <https://iri.suomi.fi/model/ktddecv/deliveryDate>
- **Range:** <http://www.w3.org/2001/XMLSchema#dateTime>

### Delivery Terms Text
- **IRI:** <https://iri.suomi.fi/model/ktddecv/deliveryTermsText>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Delivery Type Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/deliveryTypeCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Departure Date Time
- **IRI:** <https://iri.suomi.fi/model/ktddecv/departureDateTime>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Description
- **IRI:** <https://iri.suomi.fi/model/ktddecv/description>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Description of Goods Text
**Concept:** *description of goods* — *a human-readable textual description of the goods sufficient for identification, classification, and handling in trade, transport, and customs
OR
a clear textual statement that identifies and distinguishes the goods in trade, transport and customs documents*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-117>
**Hierarchy:** goods item ▶ description of goods ▶ consignment summary description
- **IRI:** <https://iri.suomi.fi/model/ktddecv/descriptionOfGoodsText>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Despatch Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/despatchDate>
- **Range:** <http://www.w3.org/2001/XMLSchema#dateTime>

### Document Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/documentDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Document Identifier
**Concept:** *document identifier* — *a reference number identifying a specific document*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-23>
**Hierarchy:** Identifier ▶ document identifier ▶ transport document identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/documentIdentifier>
- **Range:** <http://www.w3.org/2001/XMLSchema#string>

### Documentary Credit Type Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/documentaryCreditTypeCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Drafts At Locode
- **IRI:** <https://iri.suomi.fi/model/ktddecv/draftsAtLocode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Elevation Meters
- **IRI:** <https://iri.suomi.fi/model/ktddecv/elevationMeters>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### End Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/endDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### EORI Number
**Concept:** *EORI number* — *Economic Operators Registration and Identification number is a European Union registration and identification number for businesses which undertake the import or export of goods into or out of the EU*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-32>
**Hierarchy:** EORI number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/eORINumber>
- **Range:** <http://www.w3.org/2001/XMLSchema#string>

### Estimated Time of Departure
- **IRI:** <https://iri.suomi.fi/model/ktddecv/estimatedTimeOfDeparture>
- **Range:** <http://www.w3.org/2001/XMLSchema#dateTime>

### Event Date Time
- **IRI:** <https://iri.suomi.fi/model/ktddecv/eventDateTime>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Event Note Text
- **IRI:** <https://iri.suomi.fi/model/ktddecv/eventNoteText>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Excepted Quantity Indicator
- **IRI:** <https://iri.suomi.fi/model/ktddecv/exceptedQuantityIndicator>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Expiry Date
**Concept:** *documentary credit expiry date* — *the calendar date on which a documentary credit ceases to be available for the presentation of documents, as defined by ICC UCP rules*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-16>
**Hierarchy:** document expiry date ▶ documentary credit expiry date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/expiryDate>
- **Description:** The last calendar date on which a complying presentation must be made at the place where the credit expires (i.e., with the bank with which the credit is available, or as otherwise specified in the credit). Express as a calendar date (not a period or free text).
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Expiry Place Name
- **IRI:** <https://iri.suomi.fi/model/ktddecv/expiryPlaceName>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Final Destination UN Locode
- **IRI:** <https://iri.suomi.fi/model/ktddecv/finalDestinationUNLocode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Flash Point Temperature
- **IRI:** <https://iri.suomi.fi/model/ktddecv/flashPointTemperature>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Flight Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/flightDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Flight Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/flightNumber>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Freight Payment Term Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/freightPaymentTermCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Geo WKT
- **IRI:** <https://iri.suomi.fi/model/ktddecv/geoWKT>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Handling Information
- **IRI:** <https://iri.suomi.fi/model/ktddecv/handlingInformation>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Hazard Class Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hazardClassCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Hazard Label Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hazardLabelCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Hazardous Risk Indicator
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hazardousRiskIndicator>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### House Air Waybill Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/houseAirWaybillNumber>
- **Description:** The HAWB number identifying a consolidated shipment at house level, when applicable.
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### House Waybill Document Identifier
**Concept:** *house waybill document identifier* — *a reference number to identify a house waybill*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-3>
**Hierarchy:** Identifier ▶ house waybill document identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/houseWaybillDocumentIdentifier>
- **Range:** <http://www.w3.org/2001/XMLSchema#string>

### HS Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hSCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### IATA Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/iataCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### ICAO Airport Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/icaoAirportCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### IMO Ship ID
- **IRI:** <https://iri.suomi.fi/model/ktddecv/iMOShipID>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Instruction Text
- **IRI:** <https://iri.suomi.fi/model/ktddecv/instructionText>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Insurance Policy Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/insurancePolicyNumber>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Insurance Terms Text
- **IRI:** <https://iri.suomi.fi/model/ktddecv/insuranceTermsText>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Invoice Date
**Concept:** *invoice date (qualifier)* — *the calendar date on which a seller formally issues an invoice to a buyer, establishing the start of the payment obligation*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-1>
**Hierarchy:** date/time qualifier ▶ invoice date (qualifier)
- **IRI:** <https://iri.suomi.fi/model/ktddecv/invoiceDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Invoice Number
**Concept:** *Invoice number* — *Reference number to identify an invoice*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-37>
**Hierarchy:** Invoice number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/invoiceNumber>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Issue Date
**Concept:** *issue date (qualifier)* — *a date that a document was issued and when appropriate, signed or otherwise authenticated*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-41>
**Hierarchy:** date/time qualifier ▶ issue date (qualifier)
- **IRI:** <https://iri.suomi.fi/model/ktddecv/issueDate>
- **Range:** <http://www.w3.org/2001/XMLSchema#dateTime>

### Issuing Authority
- **IRI:** <https://iri.suomi.fi/model/ktddecv/issuingAuthority>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Item Description Text
- **IRI:** <https://iri.suomi.fi/model/ktddecv/itemDescriptionText>
- **Description:** Narrative description of the goods/services at item level, usable across all trade documents.
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Latest Presentation Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/latestPresentationDate>
- **Description:** Last date on which presentation is permitted under the credit.
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Latest Shipment Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/latestShipmentDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Latitude
- **IRI:** <https://iri.suomi.fi/model/ktddecv/latitude>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Limited Quantity Indicator
- **IRI:** <https://iri.suomi.fi/model/ktddecv/limitedQuantityIndicator>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Location ID
- **IRI:** <https://iri.suomi.fi/model/ktddecv/locationID>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Location Name
- **IRI:** <https://iri.suomi.fi/model/ktddecv/locationName>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Longitude
- **IRI:** <https://iri.suomi.fi/model/ktddecv/longitude>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Marine Pollutant Indicator
- **IRI:** <https://iri.suomi.fi/model/ktddecv/marinePollutantIndicator>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Marks and Numbers Text
- **IRI:** <https://iri.suomi.fi/model/ktddecv/marksAndNumbersText>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Master Air Waybill Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/masterAirWaybillNumber>
- **Description:** The MAWB number identifying the air consignment at master level (e.g., &#x27;123-45678901&#x27;).
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Maturity Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/maturityDate>
- **Description:** The actual deferred payment due date, when determinable.
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Message Subject
- **IRI:** <https://iri.suomi.fi/model/ktddecv/messageSubject>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Message Text
- **IRI:** <https://iri.suomi.fi/model/ktddecv/messageText>
- **Description:** Unstructured content of the message (language-tagged).
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Message To Receiver Text
- **IRI:** <https://iri.suomi.fi/model/ktddecv/messageToReceiverText>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### MRN
- **IRI:** <https://iri.suomi.fi/model/ktddecv/mrn>
- **Description:** The Movement Reference Number (MRN) uniquely identifying the Transit Accompanying Document.
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Multiplier Factor Percent
- **IRI:** <https://iri.suomi.fi/model/ktddecv/multiplierFactorPercent>
- **Description:** A percentage rate used to compute an additional or reduced monetary amount from a specified base amount. The calculated amount equals the base amount multiplied by this percentage divided by 100.
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Name
- **IRI:** <https://iri.suomi.fi/model/ktddecv/name>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Negotiable Indicator
- **IRI:** <https://iri.suomi.fi/model/ktddecv/negotiableIndicator>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Note Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/noteNumber>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Number of Copies
- **IRI:** <https://iri.suomi.fi/model/ktddecv/numberOfCopies>
- **Range:** <http://www.w3.org/2001/XMLSchema#integer>

### Number of Originals
- **IRI:** <https://iri.suomi.fi/model/ktddecv/numberOfOriginals>
- **Range:** <http://www.w3.org/2001/XMLSchema#integer>

### On Board Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/onBoardDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Order Date
**Concept:** *purchase order issue date/time* — *the date and time when a purchase order is issued*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-44>
**Hierarchy:** purchase order issue date/time
- **IRI:** <https://iri.suomi.fi/model/ktddecv/orderDate>
- **Range:** <http://www.w3.org/2001/XMLSchema#dateTime>

### Order Identifier
**Concept:** *purchase order number* — *an identifier assigned by the buyer to an order*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-18>
**Hierarchy:** Identifier ▶ purchase order number ▶ purchase order
- **IRI:** <https://iri.suomi.fi/model/ktddecv/orderIdentifier>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Origin Establishment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/originEstablishment>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Package Count
- **IRI:** <https://iri.suomi.fi/model/ktddecv/packageCount>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Package Length 
- **IRI:** <https://iri.suomi.fi/model/ktddecv/packageLength>
- **Range:** <http://www.w3.org/2001/XMLSchema#decimal>

### Packing Group Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/packingGroupCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Packing Instruction Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/packingInstructionCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Partial Shipment Allowed
- **IRI:** <https://iri.suomi.fi/model/ktddecv/partialShipmentAllowed>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Payment Due Date
**Concept:** *payment due date* — *the calendar date by which a payment obligation must be settled under the agreed terms of a trade transaction*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-26>
**Hierarchy:** payment term ▶ payment due date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/paymentDueDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Payment Method
**Concept:** *payment means* — *means or channel through which a payment obligation is settled (e.g., credit transfer, direct debit, card payment, cheque)*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-126>
**Hierarchy:** code ▶ payment means
- **IRI:** <https://iri.suomi.fi/model/ktddecv/paymentMethod>
- **Range:** <http://www.w3.org/2001/XMLSchema#string>

### Payment Term Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/paymentTermCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Place of Delivery UN Locode
- **IRI:** <https://iri.suomi.fi/model/ktddecv/placeOfDeliveryUNLocode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Place of Receipt UN Locode
- **IRI:** <https://iri.suomi.fi/model/ktddecv/placeOfReceiptUNLocode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Planned Arrival Date Time
- **IRI:** <https://iri.suomi.fi/model/ktddecv/plannedArrivalDateTime>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Planned Departure Date Time
- **IRI:** <https://iri.suomi.fi/model/ktddecv/plannedDepartureDateTime>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Port Facility Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/portFacilityCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Port Of Discharge UN Locode
- **IRI:** <https://iri.suomi.fi/model/ktddecv/portOfDischargeUNLocode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Port of Loading UN Locode
- **IRI:** <https://iri.suomi.fi/model/ktddecv/portOfLoadingUNLocode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Post Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/postCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Presentation Period Days
- **IRI:** <https://iri.suomi.fi/model/ktddecv/presentationPeriodDays>
- **Description:** Number of calendar days after the shipment date within which presentation must be made (SWIFT MT700 :48 is expressed as days).
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Product Description
- **IRI:** <https://iri.suomi.fi/model/ktddecv/productDescription>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Product Identifier
**Concept:** *product identifier* — *a value assigned to uniquely identify a product within a defined context, such as a company’s internal system, a global identification scheme, or a regulatory register*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-154>
**Hierarchy:** Identifier ▶ product identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/productIdentifier>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Product Name
- **IRI:** <https://iri.suomi.fi/model/ktddecv/productName>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Proper Shipping Name
- **IRI:** <https://iri.suomi.fi/model/ktddecv/properShippingName>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Publication Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/publicationDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Purchase Order Number
**Concept:** *purchase order number* — *an identifier assigned by the buyer to an order*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-18>
**Hierarchy:** Identifier ▶ purchase order number ▶ purchase order
- **IRI:** <https://iri.suomi.fi/model/ktddecv/purchaseOrderNumber>
- **Range:** <http://www.w3.org/2001/XMLSchema#string>

### Quantity Value
- **IRI:** <https://iri.suomi.fi/model/ktddecv/quantityValue>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Rail Station Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/railStationCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Rail Wagon Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/railWagonIdentifier>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Rule Set Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/ruleSetIdentifier>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Sea Waybill Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/seaWaybillNumber>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Sealed Indicator
- **IRI:** <https://iri.suomi.fi/model/ktddecv/sealedIndicator>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Shipment Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/shipmentIdentifier>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Shipping Marks
**Concept:** *shipping marks* — *identifying marks, numbers, and handling indications affixed to packages or handling units to facilitate identification, stowage, and delivery*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-139>
**Hierarchy:** package ▶ shipping marks
- **IRI:** <https://iri.suomi.fi/model/ktddecv/shippingMarks>
- **Range:** <http://www.w3.org/2001/XMLSchema#string>

### Ships Delivery Order Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/shipsDeliveryOrderNumber>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Special Provision Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/specialProvisionCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Start Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/startDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Subsidiary Hazard Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/subsidiaryHazardCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Technical Name
- **IRI:** <https://iri.suomi.fi/model/ktddecv/technicalName>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Terminal Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/terminalCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Time Zone
- **IRI:** <https://iri.suomi.fi/model/ktddecv/timeZone>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Title
- **IRI:** <https://iri.suomi.fi/model/ktddecv/title>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Total Collect Charges
**Concept:** *total collect charges* — *total amount of charges payable at destination by the consignee or another designated party, covering all freight and ancillary costs not prepaid at origin*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-149>
**Hierarchy:** charges information ▶ total collect charges
- **IRI:** <https://iri.suomi.fi/model/ktddecv/totalCollectCharges>
- **Range:** <http://www.w3.org/2001/XMLSchema#decimal>

### Trailer Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/trailerIdentifier>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Transport Document Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/transportDocumentNumber>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Transport Temperature
**Concept:** *transport temperature* — *temperature value required for a cargo during transport*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-136>
**Hierarchy:** Measure ▶ transport temperature
- **IRI:** <https://iri.suomi.fi/model/ktddecv/transportTemperature>
- **Range:** <http://www.w3.org/2001/XMLSchema#decimal>

### Transshipment Allowed
- **IRI:** <https://iri.suomi.fi/model/ktddecv/transshipmentAllowed>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### UIC Station Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/uicStationCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### UN Locode
- **IRI:** <https://iri.suomi.fi/model/ktddecv/unlocode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### UN Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/unNumber>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Unit Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/unitCode>
- **Description:** Unit of measure for non-monetary amounts (UCUM or UN/ECE Rec 20). Not used for money.
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Unit Price
**Concept:** *unit price* — *price amount expressed per one unit of quantity for a goods or service line, used to compute the line extension amount*
**URI:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-130>
**Hierarchy:** price ▶ unit price
- **IRI:** <https://iri.suomi.fi/model/ktddecv/unitPrice>
- **Range:** <http://www.w3.org/2001/XMLSchema#float>

### Value
- **IRI:** <https://iri.suomi.fi/model/ktddecv/value>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Vehicle Name
- **IRI:** <https://iri.suomi.fi/model/ktddecv/vehicleName>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Vehicle Registration Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/vehicleRegistrationIdentifier>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Version Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/versionIdentifier>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Vessel Name
- **IRI:** <https://iri.suomi.fi/model/ktddecv/vesselName>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Voyage Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/voyageNumber>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

### Warehouse GLN
- **IRI:** <https://iri.suomi.fi/model/ktddecv/warehouseGLN>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>

## Unlinked Properties

### Object Properties (no declared domain)
- **additional amounts covered** (<https://iri.suomi.fi/model/ktddecv/additionalAmountsCovered>)
- **advise through bank party** (<https://iri.suomi.fi/model/ktddecv/adviseThroughBankParty>)
- **advising bank party** (<https://iri.suomi.fi/model/ktddecv/advisingBankParty>)
- **airport of departure** (<https://iri.suomi.fi/model/ktddecv/airportOfDeparture>)
- **airport of destination** (<https://iri.suomi.fi/model/ktddecv/airportOfDestination>)
- **applicable commodity classification** (<https://iri.suomi.fi/model/ktddecv/applicableCommodityClassification>)
- **applicable rules** (<https://iri.suomi.fi/model/ktddecv/applicableRules>)
- **applicant bank party** (<https://iri.suomi.fi/model/ktddecv/applicantBankParty>)
- **applicant party** (<https://iri.suomi.fi/model/ktddecv/applicantParty>)
- **applied commodity classification** (<https://iri.suomi.fi/model/ktddecv/appliedCommodityClassification>)
- **arrival place** (<https://iri.suomi.fi/model/ktddecv/arrivalPlace>)
- **available at place** (<https://iri.suomi.fi/model/ktddecv/availableAtPlace>)
- **available with party** (<https://iri.suomi.fi/model/ktddecv/availableWithParty>)
- **available with qualifier** (<https://iri.suomi.fi/model/ktddecv/availableWithQualifier>)
- **base amount** (<https://iri.suomi.fi/model/ktddecv/baseAmount>)
- **beneficiary party** (<https://iri.suomi.fi/model/ktddecv/beneficiaryParty>)
- **buyer party** (<https://iri.suomi.fi/model/ktddecv/buyerParty>)
- **carrier party** (<https://iri.suomi.fi/model/ktddecv/carrierParty>)
- **certificate number** (<https://iri.suomi.fi/model/ktddecv/certificateNumber>)
- **chargeable weight** (<https://iri.suomi.fi/model/ktddecv/chargeableWeight>)
- **charged by party** (<https://iri.suomi.fi/model/ktddecv/chargedByParty>)
- **charged to party** (<https://iri.suomi.fi/model/ktddecv/chargedToParty>)
- **claims payable at place** (<https://iri.suomi.fi/model/ktddecv/claimsPayableAtPlace>)
- **confirmation instruction code** (<https://iri.suomi.fi/model/ktddecv/confirmationInstructionCode>) — Range: <http://www.w3.org/2004/02/skos/core#Concept>
- **confirming bank party** (<https://iri.suomi.fi/model/ktddecv/confirmingBankParty>)
- **confirming party** (<https://iri.suomi.fi/model/ktddecv/confirmingParty>)
- **consignee party** (<https://iri.suomi.fi/model/ktddecv/consigneeParty>)
- **consignment identifier** (<https://iri.suomi.fi/model/ktddecv/consignmentIdentifier>)
- **consignor party** (<https://iri.suomi.fi/model/ktddecv/consignorParty>)
- **country of origin code** (<https://iri.suomi.fi/model/ktddecv/countryOfOriginCode>) — Range: <http://www.w3.org/2004/02/skos/core#Concept>
- **coverage amount** (<https://iri.suomi.fi/model/ktddecv/coverageAmount>)
- **coverage type code** (<https://iri.suomi.fi/model/ktddecv/coverageTypeCode>)
- **covered shipment** (<https://iri.suomi.fi/model/ktddecv/coveredShipment>)
- **covers additional charge** (<https://iri.suomi.fi/model/ktddecv/coversAdditionalCharge>)
- **covers contract** (<https://iri.suomi.fi/model/ktddecv/coversContract>)
- **creditor specified financial institution** (<https://iri.suomi.fi/model/ktddecv/creditorSpecifiedFinancialInstitution>)
- **customs procedure code ** (<https://iri.suomi.fi/model/ktddecv/customsProcedureCode>)
- **declarant party** (<https://iri.suomi.fi/model/ktddecv/declarantParty>)
- **declaration number** (<https://iri.suomi.fi/model/ktddecv/declarationNumber>)
- **declared customs value amount** (<https://iri.suomi.fi/model/ktddecv/declaredCustomsValueAmount>) — Range: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
- **declared value for carriage** (<https://iri.suomi.fi/model/ktddecv/declaredValueForCarriage>)
- **defines payment terms** (<https://iri.suomi.fi/model/ktddecv/definesPaymentTerms>)
- **delivered to** (<https://iri.suomi.fi/model/ktddecv/deliveredTo>)
- **delivery location** (<https://iri.suomi.fi/model/ktddecv/deliveryLocation>) — Range: <https://iri.suomi.fi/model/ktddecv/Location>
- **delivery party** (<https://iri.suomi.fi/model/ktddecv/deliveryParty>)
- **delivery terms** (<https://iri.suomi.fi/model/ktddecv/deliveryTerms>)
- **departure place** (<https://iri.suomi.fi/model/ktddecv/departurePlace>)
- **describes item** (<https://iri.suomi.fi/model/ktddecv/describesItem>)
- **describes trade product** (<https://iri.suomi.fi/model/ktddecv/describesTradeProduct>)
- **document type** (<https://iri.suomi.fi/model/ktddecv/documentType>) — Range: <http://www.w3.org/2004/02/skos/core#Concept>
- **drafts at tenor** (<https://iri.suomi.fi/model/ktddecv/draftsAtTenor>)
- **drawee party** (<https://iri.suomi.fi/model/ktddecv/draweeParty>)
- **drawer party** (<https://iri.suomi.fi/model/ktddecv/drawerParty>)
- **equipment identifier** (<https://iri.suomi.fi/model/ktddecv/equipmentIdentifier>)
- **event identifier** (<https://iri.suomi.fi/model/ktddecv/eventIdentifier>)
- **event place** (<https://iri.suomi.fi/model/ktddecv/eventPlace>)
- **event type code** (<https://iri.suomi.fi/model/ktddecv/eventTypeCode>)
- **exporter party** (<https://iri.suomi.fi/model/ktddecv/exporterParty>)
- **final destination place** (<https://iri.suomi.fi/model/ktddecv/finalDestinationPlace>)
- **first place of receipt** (<https://iri.suomi.fi/model/ktddecv/firstPlaceOfReceipt>)
- **for goods item** (<https://iri.suomi.fi/model/ktddecv/forGoodsItem>)
- **freight charges amount** (<https://iri.suomi.fi/model/ktddecv/freightChargesAmount>)
- **freight payable at place** (<https://iri.suomi.fi/model/ktddecv/freightPayableAtPlace>)
- **from location** (<https://iri.suomi.fi/model/ktddecv/fromLocation>)
- **governed by rule set** (<https://iri.suomi.fi/model/ktddecv/governedByRuleSet>)
- **has Address** (<https://iri.suomi.fi/model/ktddecv/hasAddress>)
- **has amount** (<https://iri.suomi.fi/model/ktddecv/hasAmount>)
- **has applicant** (<https://iri.suomi.fi/model/ktddecv/hasApplicant>)
- **has applicant bank** (<https://iri.suomi.fi/model/ktddecv/hasApplicantBank>)
- **has availability method** (<https://iri.suomi.fi/model/ktddecv/hasAvailabilityMethod>)
- **has beneficiary** (<https://iri.suomi.fi/model/ktddecv/hasBeneficiary>)
- **has buyer** (<https://iri.suomi.fi/model/ktddecv/hasBuyer>)
- **has characteristic** (<https://iri.suomi.fi/model/ktddecv/hasCharacteristic>)
- **has classification scheme** (<https://iri.suomi.fi/model/ktddecv/hasClassificationScheme>)
- **has commodity classification** (<https://iri.suomi.fi/model/ktddecv/hasCommodityClassification>)
- **has consignment** (<https://iri.suomi.fi/model/ktddecv/hasConsignment>)
- **has country of origin** (<https://iri.suomi.fi/model/ktddecv/hasCountryOfOrigin>)
- **has credit availability** (<https://iri.suomi.fi/model/ktddecv/hasCreditAvailability>)
- **has dangerous goods** (<https://iri.suomi.fi/model/ktddecv/hasDangerousGoods>)
- **has dangerous goods details** (<https://iri.suomi.fi/model/ktddecv/hasDangerousGoodsDetails>)
- **has delivery** (<https://iri.suomi.fi/model/ktddecv/hasDelivery>) — Range: <https://iri.suomi.fi/model/ktddecv/Delivery>
- **has delivery milestone** (<https://iri.suomi.fi/model/ktddecv/hasDeliveryMilestone>)
- **has delivery period** (<https://iri.suomi.fi/model/ktddecv/hasDeliveryPeriod>)
- **has drawee** (<https://iri.suomi.fi/model/ktddecv/hasDrawee>)
- **has goods item** (<https://iri.suomi.fi/model/ktddecv/hasGoodsItem>)
- **has identifier** (<https://iri.suomi.fi/model/ktddecv/hasIdentifier>)
- **has invoice line** (<https://iri.suomi.fi/model/ktddecv/hasInvoiceLine>)
- **has invoicee** (<https://iri.suomi.fi/model/ktddecv/hasInvoicee>)
- **has message** (<https://iri.suomi.fi/model/ktddecv/hasMessage>)
- **has package** (<https://iri.suomi.fi/model/ktddecv/hasPackage>)
- **has package item** (<https://iri.suomi.fi/model/ktddecv/hasPackageItem>)
- **has payment line** (<https://iri.suomi.fi/model/ktddecv/hasPaymentLine>)
- **has payment schedule line** (<https://iri.suomi.fi/model/ktddecv/hasPaymentScheduleLine>)
- **has payment terms** (<https://iri.suomi.fi/model/ktddecv/hasPaymentTerms>) — Range: <https://iri.suomi.fi/model/ktddecv/PaymentTerms>
- **has presentation** (<https://iri.suomi.fi/model/ktddecv/hasPresentation>)
- **has presentation period** (<https://iri.suomi.fi/model/ktddecv/hasPresentationPeriod>)
- **has product** (<https://iri.suomi.fi/model/ktddecv/hasProduct>)
- **has quantity** (<https://iri.suomi.fi/model/ktddecv/hasQuantity>)
- **has seller** (<https://iri.suomi.fi/model/ktddecv/hasSeller>)
- **has shipment** (<https://iri.suomi.fi/model/ktddecv/hasShipment>)
- **has shipment period** (<https://iri.suomi.fi/model/ktddecv/hasShipmentPeriod>)
- **has status** (<https://iri.suomi.fi/model/ktddecv/hasStatus>)
- **has tenor** (<https://iri.suomi.fi/model/ktddecv/hasTenor>)
- **has transport equipment** (<https://iri.suomi.fi/model/ktddecv/hasTransportEquipment>)
- **has transport event** (<https://iri.suomi.fi/model/ktddecv/hasTransportEvent>)
- **importer party** (<https://iri.suomi.fi/model/ktddecv/importerParty>)
- **includes allowance charge** (<https://iri.suomi.fi/model/ktddecv/includesAllowanceCharge>)
- **includes duty tax fee** (<https://iri.suomi.fi/model/ktddecv/includesDutyTaxFee>)
- **incoterms code** (<https://iri.suomi.fi/model/ktddecv/incotermsCode>)
- **incoterms location** (<https://iri.suomi.fi/model/ktddecv/incotermsLocation>)
- **inner packaging quantity** (<https://iri.suomi.fi/model/ktddecv/innerPackagingQuantity>)
- **instructed party** (<https://iri.suomi.fi/model/ktddecv/instructedParty>)
- **instructing party** (<https://iri.suomi.fi/model/ktddecv/instructingParty>)
- **instruction to bank** (<https://iri.suomi.fi/model/ktddecv/instructionToBank>)
- **insurance value amount** (<https://iri.suomi.fi/model/ktddecv/insuranceValueAmount>)
- **insured amount** (<https://iri.suomi.fi/model/ktddecv/insuredAmount>)
- **insured party** (<https://iri.suomi.fi/model/ktddecv/insuredParty>)
- **insurer party** (<https://iri.suomi.fi/model/ktddecv/insurerParty>)
- **invoice document** (<https://iri.suomi.fi/model/ktddecv/invoiceDocument>)
- **invoice payment terms** (<https://iri.suomi.fi/model/ktddecv/invoicePaymentTerms>)
- **invoiced quantity** (<https://iri.suomi.fi/model/ktddecv/invoicedQuantity>)
- **invoicee party** (<https://iri.suomi.fi/model/ktddecv/invoiceeParty>)
- **is realized by consignment** (<https://iri.suomi.fi/model/ktddecv/isRealizedByConsignment>)
- **issuer party** (<https://iri.suomi.fi/model/ktddecv/issuerParty>) — Range: <https://iri.suomi.fi/model/ktddecv/Party>
- **issuing authority party** (<https://iri.suomi.fi/model/ktddecv/issuingAuthorityParty>)
- **issuing bank party** (<https://iri.suomi.fi/model/ktddecv/issuingBankParty>)
- **issuing carrier party** (<https://iri.suomi.fi/model/ktddecv/issuingCarrierParty>)
- **location country** (<https://iri.suomi.fi/model/ktddecv/locationCountry>)
- **maximum credit amount** (<https://iri.suomi.fi/model/ktddecv/maximumCreditAmount>)
- **net quantity per package** (<https://iri.suomi.fi/model/ktddecv/netQuantityPerPackage>)
- **nominated bank party** (<https://iri.suomi.fi/model/ktddecv/nominatedBankParty>)
- **notify party** (<https://iri.suomi.fi/model/ktddecv/notifyParty>)
- **obligee party** (<https://iri.suomi.fi/model/ktddecv/obligeeParty>)
- **obligor party** (<https://iri.suomi.fi/model/ktddecv/obligorParty>)
- **observed transport means** (<https://iri.suomi.fi/model/ktddecv/observedTransportMeans>)
- **office of departure** (<https://iri.suomi.fi/model/ktddecv/officeOfDeparture>)
- **office of destination** (<https://iri.suomi.fi/model/ktddecv/officeOfDestination>)
- **order amount** (<https://iri.suomi.fi/model/ktddecv/orderAmount>)
- **origin country** (<https://iri.suomi.fi/model/ktddecv/originCountry>)
- **other charges amount** (<https://iri.suomi.fi/model/ktddecv/otherChargesAmount>)
- **package type code** (<https://iri.suomi.fi/model/ktddecv/packageTypeCode>)
- **packing list number** (<https://iri.suomi.fi/model/ktddecv/packingListNumber>)
- **party address** (<https://iri.suomi.fi/model/ktddecv/partyAddress>)
- **party identifier** (<https://iri.suomi.fi/model/ktddecv/partyIdentifier>)
- **party legal entity** (<https://iri.suomi.fi/model/ktddecv/partyLegalEntity>)
- **payee party** (<https://iri.suomi.fi/model/ktddecv/payeeParty>)
- **payer party** (<https://iri.suomi.fi/model/ktddecv/payerParty>)
- **payment location** (<https://iri.suomi.fi/model/ktddecv/paymentLocation>)
- **payment settlement method** (<https://iri.suomi.fi/model/ktddecv/paymentSettlementMethod>)
- **per unit amount** (<https://iri.suomi.fi/model/ktddecv/perUnitAmount>)
- **place of delivery** (<https://iri.suomi.fi/model/ktddecv/placeOfDelivery>)
- **place of discharge** (<https://iri.suomi.fi/model/ktddecv/placeOfDischarge>)
- **place of expiry** (<https://iri.suomi.fi/model/ktddecv/placeOfExpiry>)
- **place of issue** (<https://iri.suomi.fi/model/ktddecv/placeOfIssue>)
- **place of loading** (<https://iri.suomi.fi/model/ktddecv/placeOfLoading>)
- **place of presentation** (<https://iri.suomi.fi/model/ktddecv/placeOfPresentation>) — Range: <https://iri.suomi.fi/model/ktddecv/Location>
- **place of receipt** (<https://iri.suomi.fi/model/ktddecv/placeOfReceipt>)
- **place of taking in charge** (<https://iri.suomi.fi/model/ktddecv/placeOfTakingInCharge>) — Range: <https://iri.suomi.fi/model/ktddecv/Location>
- **preference criterion code** (<https://iri.suomi.fi/model/ktddecv/preferenceCriterionCode>)
- **presentation base event** (<https://iri.suomi.fi/model/ktddecv/presentationBaseEvent>)
- **publisher** (<https://iri.suomi.fi/model/ktddecv/publisher>)
- **receiver party** (<https://iri.suomi.fi/model/ktddecv/receiverParty>)
- **references letter of credit** (<https://iri.suomi.fi/model/ktddecv/referencesLetterOfCredit>) — Range: <https://iri.suomi.fi/model/ktddecv/DocumentaryCredit>
- **references pre advice** (<https://iri.suomi.fi/model/ktddecv/referencesPreAdvice>)
- **reimbursing bank party** (<https://iri.suomi.fi/model/ktddecv/reimbursingBankParty>)
- **related order** (<https://iri.suomi.fi/model/ktddecv/relatedOrder>)
- **relates to consignment** (<https://iri.suomi.fi/model/ktddecv/relatesToConsignment>)
- **relates to goods item** (<https://iri.suomi.fi/model/ktddecv/relatesToGoodsItem>)
- **relates to invoice** (<https://iri.suomi.fi/model/ktddecv/relatesToInvoice>)
- **relates to package** (<https://iri.suomi.fi/model/ktddecv/relatesToPackage>)
- **relates to transport document** (<https://iri.suomi.fi/model/ktddecv/relatesToTransportDocument>)
- **reported by party** (<https://iri.suomi.fi/model/ktddecv/reportedByParty>)
- **requested confirmation party** (<https://iri.suomi.fi/model/ktddecv/requestedConfirmationParty>)
- **requested delivery period** (<https://iri.suomi.fi/model/ktddecv/requestedDeliveryPeriod>)
- **required document type** (<https://iri.suomi.fi/model/ktddecv/requiredDocumentType>) — Range: <http://www.w3.org/2004/02/skos/core#Concept>
- **requires document** (<https://iri.suomi.fi/model/ktddecv/requiresDocument>)
- **seal identifier** (<https://iri.suomi.fi/model/ktddecv/sealIdentifier>)
- **seller party** (<https://iri.suomi.fi/model/ktddecv/sellerParty>)
- **sender party** (<https://iri.suomi.fi/model/ktddecv/senderParty>)
- **shipper party** (<https://iri.suomi.fi/model/ktddecv/shipperParty>)
- **sscc** (<https://iri.suomi.fi/model/ktddecv/sscc>)
- **statistical value amount** (<https://iri.suomi.fi/model/ktddecv/statisticalValueAmount>)
- **surety party** (<https://iri.suomi.fi/model/ktddecv/suretyParty>)
- **tenor period** (<https://iri.suomi.fi/model/ktddecv/tenorPeriod>) — Range: <https://iri.suomi.fi/model/ktddecv/PeriodOfTime>
- **to location** (<https://iri.suomi.fi/model/ktddecv/toLocation>)
- **total amount** (<https://iri.suomi.fi/model/ktddecv/totalAmount>)
- **total goods item quantity** (<https://iri.suomi.fi/model/ktddecv/totalGoodsItemQuantity>)
- **total gross weight** (<https://iri.suomi.fi/model/ktddecv/totalGrossWeight>)
- **total invoice amount** (<https://iri.suomi.fi/model/ktddecv/totalInvoiceAmount>)
- **total net weight** (<https://iri.suomi.fi/model/ktddecv/totalNetWeight>)
- **total package count** (<https://iri.suomi.fi/model/ktddecv/totalPackageCount>)
- **total package quantity** (<https://iri.suomi.fi/model/ktddecv/totalPackageQuantity>)
- **total transport handling unit quantity** (<https://iri.suomi.fi/model/ktddecv/totalTransportHandlingUnitQuantity>)
- **transit office** (<https://iri.suomi.fi/model/ktddecv/transitOffice>)
- **transport document type code** (<https://iri.suomi.fi/model/ktddecv/transportDocumentTypeCode>) — Range: <http://www.w3.org/2004/02/skos/core#Concept>
- **transport mode code** (<https://iri.suomi.fi/model/ktddecv/transportModeCode>)
- **transshipment place** (<https://iri.suomi.fi/model/ktddecv/transshipmentPlace>)
- **uses transport equipment** (<https://iri.suomi.fi/model/ktddecv/usesTransportEquipment>)
- **uses transport means** (<https://iri.suomi.fi/model/ktddecv/usesTransportMeans>)
- **validity period** (<https://iri.suomi.fi/model/ktddecv/validityPeriod>)
### Datatype Properties (no declared domain)
- **Actual Arrival Date Time** (<https://iri.suomi.fi/model/ktddecv/actualArrivalDateTime>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Actual Departure Date Time** (<https://iri.suomi.fi/model/ktddecv/actualDepartureDateTime>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Additional Conditions Text** (<https://iri.suomi.fi/model/ktddecv/additionalConditionsText>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Airport of Departure IATA Code** (<https://iri.suomi.fi/model/ktddecv/airportOfDepartureIATACode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Airport of Destination IATA Code** (<https://iri.suomi.fi/model/ktddecv/airportOfDestinationIATACode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Allowance Charge Reason Code** (<https://iri.suomi.fi/model/ktddecv/allowanceChargeReasonCode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Alternate Name** (<https://iri.suomi.fi/model/ktddecv/alternateName>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Amount Percent Of Base** (<https://iri.suomi.fi/model/ktddecv/amountPercentOfBase>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Amount Tolerance Percent** (<https://iri.suomi.fi/model/ktddecv/amountTolerancePercent>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Amount Value** (<https://iri.suomi.fi/model/ktddecv/amountValue>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Arrival Date Time** (<https://iri.suomi.fi/model/ktddecv/arrivalDateTime>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Available At Locode** (<https://iri.suomi.fi/model/ktddecv/availableAtLocode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Available With By** (<https://iri.suomi.fi/model/ktddecv/availableWithBy>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Bank Account Identifier** (<https://iri.suomi.fi/model/ktddecv/bankAccountIdentifier>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Bond Number** (<https://iri.suomi.fi/model/ktddecv/bondNumber>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Border Crossing Point Code** (<https://iri.suomi.fi/model/ktddecv/borderCrossingPointCode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Botanical Details** (<https://iri.suomi.fi/model/ktddecv/botanicalDetails>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Calculation Percent** (<https://iri.suomi.fi/model/ktddecv/calculationPercent>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Charge Indicator** (<https://iri.suomi.fi/model/ktddecv/chargeIndicator>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Classification Code** (<https://iri.suomi.fi/model/ktddecv/classificationCode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Commodity Code** (<https://iri.suomi.fi/model/ktddecv/commodityCode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Confirmation Added Date** (<https://iri.suomi.fi/model/ktddecv/confirmationAddedDate>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Confirmation Date** (<https://iri.suomi.fi/model/ktddecv/confirmationDate>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Container Number** (<https://iri.suomi.fi/model/ktddecv/containerNumber>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Contract Identifier** (<https://iri.suomi.fi/model/ktddecv/contractIdentifier>) — Range: <http://www.w3.org/2001/XMLSchema#string>
- **Contract Number** (<https://iri.suomi.fi/model/ktddecv/contractNumber>) — Range: <http://www.w3.org/2001/XMLSchema#string>
- **Country Code** (<https://iri.suomi.fi/model/ktddecv/countryCode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Country Name** (<https://iri.suomi.fi/model/ktddecv/countryName>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Credit Amount Tolerance Percentage** (<https://iri.suomi.fi/model/ktddecv/creditAmountTolerancePercentage>) — Range: <http://www.w3.org/2001/XMLSchema#decimal>
- **Credit Identifier** (<https://iri.suomi.fi/model/ktddecv/creditIdentifier>) — Range: <http://www.w3.org/2001/XMLSchema#string>
- **Currency Code** (<https://iri.suomi.fi/model/ktddecv/currencyCode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Customs Office Code** (<https://iri.suomi.fi/model/ktddecv/customsOfficeCode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Declaration Date** (<https://iri.suomi.fi/model/ktddecv/declarationDate>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Deferred Payment Date** (<https://iri.suomi.fi/model/ktddecv/deferredPaymentDate>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Delivery Date** (<https://iri.suomi.fi/model/ktddecv/deliveryDate>) — Range: <http://www.w3.org/2001/XMLSchema#dateTime>
- **Delivery Terms Text** (<https://iri.suomi.fi/model/ktddecv/deliveryTermsText>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Delivery Type Code** (<https://iri.suomi.fi/model/ktddecv/deliveryTypeCode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Departure Date Time** (<https://iri.suomi.fi/model/ktddecv/departureDateTime>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Description** (<https://iri.suomi.fi/model/ktddecv/description>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Description of Goods Text** (<https://iri.suomi.fi/model/ktddecv/descriptionOfGoodsText>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Despatch Date** (<https://iri.suomi.fi/model/ktddecv/despatchDate>) — Range: <http://www.w3.org/2001/XMLSchema#dateTime>
- **Document Date** (<https://iri.suomi.fi/model/ktddecv/documentDate>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Document Identifier** (<https://iri.suomi.fi/model/ktddecv/documentIdentifier>) — Range: <http://www.w3.org/2001/XMLSchema#string>
- **Documentary Credit Type Code** (<https://iri.suomi.fi/model/ktddecv/documentaryCreditTypeCode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Drafts At Locode** (<https://iri.suomi.fi/model/ktddecv/draftsAtLocode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Elevation Meters** (<https://iri.suomi.fi/model/ktddecv/elevationMeters>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **End Date** (<https://iri.suomi.fi/model/ktddecv/endDate>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **EORI Number** (<https://iri.suomi.fi/model/ktddecv/eORINumber>) — Range: <http://www.w3.org/2001/XMLSchema#string>
- **Estimated Time of Departure** (<https://iri.suomi.fi/model/ktddecv/estimatedTimeOfDeparture>) — Range: <http://www.w3.org/2001/XMLSchema#dateTime>
- **Event Date Time** (<https://iri.suomi.fi/model/ktddecv/eventDateTime>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Event Note Text** (<https://iri.suomi.fi/model/ktddecv/eventNoteText>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Excepted Quantity Indicator** (<https://iri.suomi.fi/model/ktddecv/exceptedQuantityIndicator>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Expiry Date** (<https://iri.suomi.fi/model/ktddecv/expiryDate>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Expiry Place Name** (<https://iri.suomi.fi/model/ktddecv/expiryPlaceName>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Final Destination UN Locode** (<https://iri.suomi.fi/model/ktddecv/finalDestinationUNLocode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Flash Point Temperature** (<https://iri.suomi.fi/model/ktddecv/flashPointTemperature>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Flight Date** (<https://iri.suomi.fi/model/ktddecv/flightDate>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Flight Number** (<https://iri.suomi.fi/model/ktddecv/flightNumber>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Freight Payment Term Code** (<https://iri.suomi.fi/model/ktddecv/freightPaymentTermCode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Geo WKT** (<https://iri.suomi.fi/model/ktddecv/geoWKT>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Handling Information** (<https://iri.suomi.fi/model/ktddecv/handlingInformation>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Hazard Class Code** (<https://iri.suomi.fi/model/ktddecv/hazardClassCode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Hazard Label Code** (<https://iri.suomi.fi/model/ktddecv/hazardLabelCode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Hazardous Risk Indicator** (<https://iri.suomi.fi/model/ktddecv/hazardousRiskIndicator>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **House Air Waybill Number** (<https://iri.suomi.fi/model/ktddecv/houseAirWaybillNumber>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **House Waybill Document Identifier** (<https://iri.suomi.fi/model/ktddecv/houseWaybillDocumentIdentifier>) — Range: <http://www.w3.org/2001/XMLSchema#string>
- **HS Code** (<https://iri.suomi.fi/model/ktddecv/hSCode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **IATA Code** (<https://iri.suomi.fi/model/ktddecv/iataCode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **ICAO Airport Code** (<https://iri.suomi.fi/model/ktddecv/icaoAirportCode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **IMO Ship ID** (<https://iri.suomi.fi/model/ktddecv/iMOShipID>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Instruction Text** (<https://iri.suomi.fi/model/ktddecv/instructionText>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Insurance Policy Number** (<https://iri.suomi.fi/model/ktddecv/insurancePolicyNumber>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Insurance Terms Text** (<https://iri.suomi.fi/model/ktddecv/insuranceTermsText>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Invoice Date** (<https://iri.suomi.fi/model/ktddecv/invoiceDate>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Invoice Number** (<https://iri.suomi.fi/model/ktddecv/invoiceNumber>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Issue Date** (<https://iri.suomi.fi/model/ktddecv/issueDate>) — Range: <http://www.w3.org/2001/XMLSchema#dateTime>
- **Issuing Authority** (<https://iri.suomi.fi/model/ktddecv/issuingAuthority>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Item Description Text** (<https://iri.suomi.fi/model/ktddecv/itemDescriptionText>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Latest Presentation Date** (<https://iri.suomi.fi/model/ktddecv/latestPresentationDate>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Latest Shipment Date** (<https://iri.suomi.fi/model/ktddecv/latestShipmentDate>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Latitude** (<https://iri.suomi.fi/model/ktddecv/latitude>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Limited Quantity Indicator** (<https://iri.suomi.fi/model/ktddecv/limitedQuantityIndicator>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Location ID** (<https://iri.suomi.fi/model/ktddecv/locationID>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Location Name** (<https://iri.suomi.fi/model/ktddecv/locationName>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Longitude** (<https://iri.suomi.fi/model/ktddecv/longitude>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Marine Pollutant Indicator** (<https://iri.suomi.fi/model/ktddecv/marinePollutantIndicator>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Marks and Numbers Text** (<https://iri.suomi.fi/model/ktddecv/marksAndNumbersText>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Master Air Waybill Number** (<https://iri.suomi.fi/model/ktddecv/masterAirWaybillNumber>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Maturity Date** (<https://iri.suomi.fi/model/ktddecv/maturityDate>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Message Subject** (<https://iri.suomi.fi/model/ktddecv/messageSubject>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Message Text** (<https://iri.suomi.fi/model/ktddecv/messageText>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Message To Receiver Text** (<https://iri.suomi.fi/model/ktddecv/messageToReceiverText>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **MRN** (<https://iri.suomi.fi/model/ktddecv/mrn>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Multiplier Factor Percent** (<https://iri.suomi.fi/model/ktddecv/multiplierFactorPercent>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Name** (<https://iri.suomi.fi/model/ktddecv/name>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Negotiable Indicator** (<https://iri.suomi.fi/model/ktddecv/negotiableIndicator>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Note Number** (<https://iri.suomi.fi/model/ktddecv/noteNumber>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Number of Copies** (<https://iri.suomi.fi/model/ktddecv/numberOfCopies>) — Range: <http://www.w3.org/2001/XMLSchema#integer>
- **Number of Originals** (<https://iri.suomi.fi/model/ktddecv/numberOfOriginals>) — Range: <http://www.w3.org/2001/XMLSchema#integer>
- **On Board Date** (<https://iri.suomi.fi/model/ktddecv/onBoardDate>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Order Date** (<https://iri.suomi.fi/model/ktddecv/orderDate>) — Range: <http://www.w3.org/2001/XMLSchema#dateTime>
- **Order Identifier** (<https://iri.suomi.fi/model/ktddecv/orderIdentifier>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Origin Establishment** (<https://iri.suomi.fi/model/ktddecv/originEstablishment>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Package Count** (<https://iri.suomi.fi/model/ktddecv/packageCount>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Package Length ** (<https://iri.suomi.fi/model/ktddecv/packageLength>) — Range: <http://www.w3.org/2001/XMLSchema#decimal>
- **Packing Group Code** (<https://iri.suomi.fi/model/ktddecv/packingGroupCode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Packing Instruction Code** (<https://iri.suomi.fi/model/ktddecv/packingInstructionCode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Partial Shipment Allowed** (<https://iri.suomi.fi/model/ktddecv/partialShipmentAllowed>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Payment Due Date** (<https://iri.suomi.fi/model/ktddecv/paymentDueDate>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Payment Method** (<https://iri.suomi.fi/model/ktddecv/paymentMethod>) — Range: <http://www.w3.org/2001/XMLSchema#string>
- **Payment Term Code** (<https://iri.suomi.fi/model/ktddecv/paymentTermCode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Place of Delivery UN Locode** (<https://iri.suomi.fi/model/ktddecv/placeOfDeliveryUNLocode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Place of Receipt UN Locode** (<https://iri.suomi.fi/model/ktddecv/placeOfReceiptUNLocode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Planned Arrival Date Time** (<https://iri.suomi.fi/model/ktddecv/plannedArrivalDateTime>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Planned Departure Date Time** (<https://iri.suomi.fi/model/ktddecv/plannedDepartureDateTime>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Port Facility Code** (<https://iri.suomi.fi/model/ktddecv/portFacilityCode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Port Of Discharge UN Locode** (<https://iri.suomi.fi/model/ktddecv/portOfDischargeUNLocode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Port of Loading UN Locode** (<https://iri.suomi.fi/model/ktddecv/portOfLoadingUNLocode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Post Code** (<https://iri.suomi.fi/model/ktddecv/postCode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Presentation Period Days** (<https://iri.suomi.fi/model/ktddecv/presentationPeriodDays>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Product Description** (<https://iri.suomi.fi/model/ktddecv/productDescription>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Product Identifier** (<https://iri.suomi.fi/model/ktddecv/productIdentifier>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Product Name** (<https://iri.suomi.fi/model/ktddecv/productName>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Proper Shipping Name** (<https://iri.suomi.fi/model/ktddecv/properShippingName>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Publication Date** (<https://iri.suomi.fi/model/ktddecv/publicationDate>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Purchase Order Number** (<https://iri.suomi.fi/model/ktddecv/purchaseOrderNumber>) — Range: <http://www.w3.org/2001/XMLSchema#string>
- **Quantity Value** (<https://iri.suomi.fi/model/ktddecv/quantityValue>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Rail Station Code** (<https://iri.suomi.fi/model/ktddecv/railStationCode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Rail Wagon Identifier** (<https://iri.suomi.fi/model/ktddecv/railWagonIdentifier>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Rule Set Identifier** (<https://iri.suomi.fi/model/ktddecv/ruleSetIdentifier>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Sea Waybill Number** (<https://iri.suomi.fi/model/ktddecv/seaWaybillNumber>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Sealed Indicator** (<https://iri.suomi.fi/model/ktddecv/sealedIndicator>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Shipment Identifier** (<https://iri.suomi.fi/model/ktddecv/shipmentIdentifier>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Shipping Marks** (<https://iri.suomi.fi/model/ktddecv/shippingMarks>) — Range: <http://www.w3.org/2001/XMLSchema#string>
- **Ships Delivery Order Number** (<https://iri.suomi.fi/model/ktddecv/shipsDeliveryOrderNumber>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Special Provision Code** (<https://iri.suomi.fi/model/ktddecv/specialProvisionCode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Start Date** (<https://iri.suomi.fi/model/ktddecv/startDate>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subsidiary Hazard Code** (<https://iri.suomi.fi/model/ktddecv/subsidiaryHazardCode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Technical Name** (<https://iri.suomi.fi/model/ktddecv/technicalName>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Terminal Code** (<https://iri.suomi.fi/model/ktddecv/terminalCode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Time Zone** (<https://iri.suomi.fi/model/ktddecv/timeZone>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Title** (<https://iri.suomi.fi/model/ktddecv/title>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Total Collect Charges** (<https://iri.suomi.fi/model/ktddecv/totalCollectCharges>) — Range: <http://www.w3.org/2001/XMLSchema#decimal>
- **Trailer Identifier** (<https://iri.suomi.fi/model/ktddecv/trailerIdentifier>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Transport Document Number** (<https://iri.suomi.fi/model/ktddecv/transportDocumentNumber>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Transport Temperature** (<https://iri.suomi.fi/model/ktddecv/transportTemperature>) — Range: <http://www.w3.org/2001/XMLSchema#decimal>
- **Transshipment Allowed** (<https://iri.suomi.fi/model/ktddecv/transshipmentAllowed>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **UIC Station Code** (<https://iri.suomi.fi/model/ktddecv/uicStationCode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **UN Locode** (<https://iri.suomi.fi/model/ktddecv/unlocode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **UN Number** (<https://iri.suomi.fi/model/ktddecv/unNumber>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Unit Code** (<https://iri.suomi.fi/model/ktddecv/unitCode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Unit Price** (<https://iri.suomi.fi/model/ktddecv/unitPrice>) — Range: <http://www.w3.org/2001/XMLSchema#float>
- **Value** (<https://iri.suomi.fi/model/ktddecv/value>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Vehicle Name** (<https://iri.suomi.fi/model/ktddecv/vehicleName>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Vehicle Registration Identifier** (<https://iri.suomi.fi/model/ktddecv/vehicleRegistrationIdentifier>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Version Identifier** (<https://iri.suomi.fi/model/ktddecv/versionIdentifier>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Vessel Name** (<https://iri.suomi.fi/model/ktddecv/vesselName>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Voyage Number** (<https://iri.suomi.fi/model/ktddecv/voyageNumber>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Warehouse GLN** (<https://iri.suomi.fi/model/ktddecv/warehouseGLN>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>

## Global Concept Crosswalk

| OWL Entity | Predicate | SKOS Concept | prefLabel | Definition |
|-------------|------------|---------------|------------|-------------|
| <https://iri.suomi.fi/model/ktddecv/CITESPermit> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-233> | CITES permit | a permit required for the international trade of endangered species, issued under the Convention on International Trade in Endangered Species of Wild Fauna and Flora (CITES) |
| <https://iri.suomi.fi/model/ktddecv/Country> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-208> | country | a national territory identified by ISO 3166 code, relevant in trade for origin, destination, and transit |
| <https://iri.suomi.fi/model/ktddecv/CustomsDeclaration> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-237> | customs declaration | a statement made to customs authorities providing prescribed information on imported, exported, or transiting goods |
| <https://iri.suomi.fi/model/ktddecv/DangerousGoods> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-217> | Dangerous Goods | substances or articles posing risks during transport, classified under international regulations (e.g., UN numbers) |
| <https://iri.suomi.fi/model/ktddecv/DocumentaryCredit> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-239> | documentary credit | a financial instrument by which a bank undertakes to pay the seller on behalf of the buyer upon presentation of compliant documents |
| <https://iri.suomi.fi/model/ktddecv/GoodsItem> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-198> | goods item | a distinct product or commodity within a consignment or shipment, identified by description, code, and quantity |
| <https://iri.suomi.fi/model/ktddecv/Identifier> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-221> | Identifier | a reference assigned to uniquely distinguish a document, consignment, shipment, or party |
| <https://iri.suomi.fi/model/ktddecv/Instruction> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-354> | instruction | an operational directive provided to guide actions in a trade or logistics process |
| <https://iri.suomi.fi/model/ktddecv/PackingList> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-229> | packing list | a document detailing the contents, packaging, and marks of a consignment for identification and verification purposes |
| <https://iri.suomi.fi/model/ktddecv/PaymentTerms> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-148> | payment term | identification of the terms of payment between the parties to a transaction (generic term)
or
the agreed conditions for the timing, method, and amount of payment for goods or services supplied. |
| <https://iri.suomi.fi/model/ktddecv/PurchaseOrder> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-228> | purchase order | a document by which a buyer requests goods or services from a seller under specified terms |
| <https://iri.suomi.fi/model/ktddecv/Quantity> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-112> | Quantity | a numeric measure of count, weight, volume, or dimension expressed in a specified unit |
| <https://iri.suomi.fi/model/ktddecv/Seal> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-244> | seal | a device affixed to transport equipment or packages to prevent tampering and provide evidence of unauthorized access |
| <https://iri.suomi.fi/model/ktddecv/TradeProduct> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-264> | trade product | a product or service offered for commercial exchange in international trade, identified by its commercial, legal, or regulatory characteristics such as name, description, classification code, or digital product passport |
| <https://iri.suomi.fi/model/ktddecv/TransportDocument> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-226> | transport document | a document evidencing a contract of carriage and receipt of goods by a carrier, such as a bill of lading, waybill, or consignment note |
| <https://iri.suomi.fi/model/ktddecv/TransportEvent> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-207> | Transport Event | an event associated with the movement of goods or transport equipment |
| <https://iri.suomi.fi/model/ktddecv/TransportMeans> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-209> | transport means | a physical vehicle or vessel used to move goods (e.g., ship, aircraft, truck) |
| <https://iri.suomi.fi/model/ktddecv/VeterinaryCertificate> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-232> | veterinary certificate | an official certificate verifying that animals or animal products meet the health requirements of the importing country |
| <https://iri.suomi.fi/model/ktddecv/applicantParty> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-92> | documentary credit applicant | a party, usually the buyer/importer, that requests a bank to issue a documentary credit in favour of a beneficiary (seller/exporter) in order to secure payment for goods or services |
| <https://iri.suomi.fi/model/ktddecv/beneficiaryParty> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-86> | documentary credit beneficiary | a party in whose favour a documentary credit is issued and who is entitled to claim payment from the issuing or confirming bank upon presentation of compliant documents |
| <https://iri.suomi.fi/model/ktddecv/deliveredTo> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-14> | Ship to / Delivery Party | Party to which goods should be delivered, if not identical with consignee such as the place where a container is to be, or has been, positioned. |
| <https://iri.suomi.fi/model/ktddecv/deliveryParty> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-14> | Ship to / Delivery Party | Party to which goods should be delivered, if not identical with consignee such as the place where a container is to be, or has been, positioned. |
| <https://iri.suomi.fi/model/ktddecv/hasApplicant> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-92> | documentary credit applicant | a party, usually the buyer/importer, that requests a bank to issue a documentary credit in favour of a beneficiary (seller/exporter) in order to secure payment for goods or services |
| <https://iri.suomi.fi/model/ktddecv/hasBeneficiary> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-86> | documentary credit beneficiary | a party in whose favour a documentary credit is issued and who is entitled to claim payment from the issuing or confirming bank upon presentation of compliant documents |
| <https://iri.suomi.fi/model/ktddecv/hasBuyer> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-38> | buyer | a party to which merchandise or services are sold
or
the party that purchases goods or services under a trade contract |
| <https://iri.suomi.fi/model/ktddecv/hasCountryOfOrigin> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-62> | origin country | the country in which the goods have been produced or manufactured, according to criteria laid down for the application of the Customs tariff or quantitative restrictions, or any measure related to trade |
| <https://iri.suomi.fi/model/ktddecv/hasDrawee> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-61> | drawee | the party on whom a bill of exchange or similar negotiable instrument is drawn, and who is thereby ordered to pay |
| <https://iri.suomi.fi/model/ktddecv/hasInvoicee> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-50> | invoicee | a party to whom an invoice is issued |
| <https://iri.suomi.fi/model/ktddecv/issuerParty> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-71> | issuer | a competent authority or organization that formally issues a permit, certificate, carnet, financial instrument, or other official document, giving it legal validity |
| <https://iri.suomi.fi/model/ktddecv/originCountry> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-62> | origin country | the country in which the goods have been produced or manufactured, according to criteria laid down for the application of the Customs tariff or quantitative restrictions, or any measure related to trade |
| <https://iri.suomi.fi/model/ktddecv/paymentLocation> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-77> | place of payment | the location where payment is to be made or is legally enforceable, as specified in a financial document |
| <https://iri.suomi.fi/model/ktddecv/placeOfDelivery> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-57> | place of delivery | the location at which the goods are handed over to the consignee or a designated party, marking the completion of the delivery obligation |
| <https://iri.suomi.fi/model/ktddecv/placeOfLoading> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-98> | place of loading | TBD |
| <https://iri.suomi.fi/model/ktddecv/commodityCode> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-188> | HS code (commodity code) | a code specifying a type of goods for Customs, transport or statistical purposes (generic term) |
| <https://iri.suomi.fi/model/ktddecv/contractIdentifier> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-9> | contract identifier | a unique identifier assigned to a contract by the issuing party or by an agreed registration scheme |
| <https://iri.suomi.fi/model/ktddecv/contractNumber> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-9> | contract identifier | a unique identifier assigned to a contract by the issuing party or by an agreed registration scheme |
| <https://iri.suomi.fi/model/ktddecv/creditIdentifier> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-29> | documentary credit identifier | a unique reference assigned by the issuing bank to a documentary credit, used to identify and trace the credit throughout its lifecycle and across related trade, transport, and financial documents |
| <https://iri.suomi.fi/model/ktddecv/deliveryDate> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-42> | delivery date (qualifier) | qualifier indicating that the date/time refers to delivery of goods |
| <https://iri.suomi.fi/model/ktddecv/descriptionOfGoodsText> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-117> | description of goods | a human-readable textual description of the goods sufficient for identification, classification, and handling in trade, transport, and customs
OR
a clear textual statement that identifies and distinguishes the goods in trade, transport and customs documents |
| <https://iri.suomi.fi/model/ktddecv/documentIdentifier> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-23> | document identifier | a reference number identifying a specific document |
| <https://iri.suomi.fi/model/ktddecv/eORINumber> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-32> | EORI number | Economic Operators Registration and Identification number is a European Union registration and identification number for businesses which undertake the import or export of goods into or out of the EU |
| <https://iri.suomi.fi/model/ktddecv/expiryDate> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-16> | documentary credit expiry date | the calendar date on which a documentary credit ceases to be available for the presentation of documents, as defined by ICC UCP rules |
| <https://iri.suomi.fi/model/ktddecv/houseWaybillDocumentIdentifier> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-3> | house waybill document identifier | a reference number to identify a house waybill |
| <https://iri.suomi.fi/model/ktddecv/invoiceDate> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-1> | invoice date (qualifier) | the calendar date on which a seller formally issues an invoice to a buyer, establishing the start of the payment obligation |
| <https://iri.suomi.fi/model/ktddecv/invoiceNumber> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-37> | Invoice number | Reference number to identify an invoice |
| <https://iri.suomi.fi/model/ktddecv/issueDate> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-41> | issue date (qualifier) | a date that a document was issued and when appropriate, signed or otherwise authenticated |
| <https://iri.suomi.fi/model/ktddecv/orderDate> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-44> | purchase order issue date/time | the date and time when a purchase order is issued |
| <https://iri.suomi.fi/model/ktddecv/orderIdentifier> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-18> | purchase order number | an identifier assigned by the buyer to an order |
| <https://iri.suomi.fi/model/ktddecv/paymentDueDate> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-26> | payment due date | the calendar date by which a payment obligation must be settled under the agreed terms of a trade transaction |
| <https://iri.suomi.fi/model/ktddecv/paymentMethod> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-126> | payment means | means or channel through which a payment obligation is settled (e.g., credit transfer, direct debit, card payment, cheque) |
| <https://iri.suomi.fi/model/ktddecv/productIdentifier> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-154> | product identifier | a value assigned to uniquely identify a product within a defined context, such as a company’s internal system, a global identification scheme, or a regulatory register |
| <https://iri.suomi.fi/model/ktddecv/purchaseOrderNumber> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-18> | purchase order number | an identifier assigned by the buyer to an order |
| <https://iri.suomi.fi/model/ktddecv/shippingMarks> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-139> | shipping marks | identifying marks, numbers, and handling indications affixed to packages or handling units to facilitate identification, stowage, and delivery |
| <https://iri.suomi.fi/model/ktddecv/totalCollectCharges> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-149> | total collect charges | total amount of charges payable at destination by the consignee or another designated party, covering all freight and ancillary costs not prepaid at origin |
| <https://iri.suomi.fi/model/ktddecv/transportTemperature> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-136> | transport temperature | temperature value required for a cargo during transport |
| <https://iri.suomi.fi/model/ktddecv/unitPrice> | dcterms:subject | <https://iri.suomi.fi/terminology/a89c6af7a/concept-130> | unit price | price amount expressed per one unit of quantity for a goods or service line, used to compute the line extension amount |