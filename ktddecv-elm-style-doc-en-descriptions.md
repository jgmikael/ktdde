# KTDDE Core Vocabulary — Documentation (EN-only descriptive text)

## Ontology Overview
- **Ontology IRI:** <https://iri.suomi.fi/model/ktddecv/>
- **Title:** Key Trade Documents and Data Elements (KTDDE) Core Vocabulary
- **Created:** 2024-11-04T12:43:11.269000+00:00
- **Modified:** 2025-09-16T06:48:54.019000+00:00

An OWL Ontology (Vocabulary if you wish) based on the KTDDE Data Elements, mapped to UBL, UN/CEFACT BSP and the GS1 Web Vocabulary (where possible & applicable).

- **See also:** <N623207c315e24f0c93a5e12b480abbae>

## Namespaces
- **xml:** <http://www.w3.org/XML/1998/namespace>
- **rdf:** <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
- **rdfs:** <http://www.w3.org/2000/01/rdf-schema#>
- **xsd:** <http://www.w3.org/2001/XMLSchema#>
- **gs1:** <https://gs1.org/voc/>
- **ktddu:** <https://iri.suomi.fi/model/ktddu/0.0.1/>
- **busdoc:** <https://iri.suomi.fi/model/busdoc/1.0.2/>
- **ktddecv:** <https://iri.suomi.fi/model/ktddecv/>
- **dcterms:** <http://purl.org/dc/terms/>
- **owl:** <http://www.w3.org/2002/07/owl#>
- **http:** <http://www.w3.org/2011/http#>
- **suomi-meta:** <https://iri.suomi.fi/model/suomi-meta/>
- **skos:** <http://www.w3.org/2004/02/skos/core#>
- **unece:** <https://vocabulary.uncefact.org/>
- **geo:** <http://www.opengis.net/ont/geosparql#>
- **sh:** <http://www.w3.org/ns/shacl#>
- **dcap:** <http://purl.org/ws-mmi-dc/terms/>
- **j.0:** <http://xmlns.com/foaf/0.1/>

## Index
- [Classes](#classes)
- [Object Properties](#object-properties)
- [Datatype Properties](#datatype-properties)

<a id="classes"></a>
## Classes

### Additional Amount Category
- **IRI:** <https://iri.suomi.fi/model/ktddecv/AdditionalAmountCategory>
- **Identifier:** AdditionalAmountCategory
- **Created:** 2025-08-25T11:44:51.993000+00:00
- **Modified:** 2025-08-25T11:44:51.993000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2004/02/skos/core#Concept>

### Address
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Address>
- **Identifier:** Address
- **Created:** 2025-06-05T13:14:44.596000+00:00
- **Modified:** 2025-06-05T13:14:44.596000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Equivalent to:** <https://vocabulary.uncefact.org/TradeAddress>, <https://gs1.org/voc/PostalAddress>, <https://iri.suomi.fi/model/busdoc/1.0.2/Address>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Advance Ruling Application
- **IRI:** <https://iri.suomi.fi/model/ktddecv/AdvanceRulingApplication>
- **Identifier:** AdvanceRulingApplication
- **Created:** 2025-09-05T11:46:34.770000+00:00
- **Modified:** 2025-09-05T11:46:34.770000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Air Cargo Manifest
- **IRI:** <https://iri.suomi.fi/model/ktddecv/AirCargoManifest>
- **Identifier:** AirCargoManifest
- **Created:** 2025-09-05T11:42:25.679000+00:00
- **Modified:** 2025-09-05T11:42:25.679000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Air Waybill
- **IRI:** <https://iri.suomi.fi/model/ktddecv/AirWaybill>
- **Description:**
  - The air transport contract document for carriage of goods by air. May be a master (MAWB) or house (HAWB) waybill; identifies the shipment, parties, flight/route and charges.
- **Identifier:** AirWaybill
- **Created:** 2025-09-05T11:41:35.534000+00:00
- **Modified:** 2025-09-08T07:11:04.056000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <https://iri.suomi.fi/model/ktddecv/TransportDocument>

- **Object properties with this class as domain:**
  - **issuing carrier party** (<https://iri.suomi.fi/model/ktddecv/issuingCarrierParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **shipper party** (<https://iri.suomi.fi/model/ktddecv/shipperParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **consignee party** (<https://iri.suomi.fi/model/ktddecv/consigneeParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party> — The party to whom the goods are to be delivered.
  - **notify party** (<https://iri.suomi.fi/model/ktddecv/notifyParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **airport of departure** (<https://iri.suomi.fi/model/ktddecv/airportOfDeparture>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>
  - **airport of destination** (<https://iri.suomi.fi/model/ktddecv/airportOfDestination>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>
  - **place of issue** (<https://iri.suomi.fi/model/ktddecv/placeOfIssue>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>
  - **has goods item** (<https://iri.suomi.fi/model/ktddecv/hasGoodsItem>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/GoodsItem>
  - **has package** (<https://iri.suomi.fi/model/ktddecv/hasPackage>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Package>
  - **has transport equipment** (<https://iri.suomi.fi/model/ktddecv/hasTransportEquipment>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/TransportEquipment>
  - **total gross weight** (<https://iri.suomi.fi/model/ktddecv/totalGrossWeight>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Quantity>
  - **chargeable weight** (<https://iri.suomi.fi/model/ktddecv/chargeableWeight>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Quantity>
  - **has dangerous goods** (<https://iri.suomi.fi/model/ktddecv/hasDangerousGoods>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/DangerousGoods>
  - **declared value for carriage** (<https://iri.suomi.fi/model/ktddecv/declaredValueForCarriage>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
  - **other charges amount** (<https://iri.suomi.fi/model/ktddecv/otherChargesAmount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>

- **Datatype properties with this class as domain:**
  - **Master Air Waybill Number** (<https://iri.suomi.fi/model/ktddecv/masterAirWaybillNumber>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal> — The MAWB number identifying the air consignment at master level (e.g., &#x27;123-45678901&#x27;).
  - **House Air Waybill Number** (<https://iri.suomi.fi/model/ktddecv/houseAirWaybillNumber>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal> — The HAWB number identifying a consolidated shipment at house level, when applicable.
  - **Issue Date** (<https://iri.suomi.fi/model/ktddecv/issueDate>) — some/all values from: <http://www.w3.org/2001/XMLSchema#dateTime>
  - **Flight Number** (<https://iri.suomi.fi/model/ktddecv/flightNumber>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Flight Date** (<https://iri.suomi.fi/model/ktddecv/flightDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Handling Information** (<https://iri.suomi.fi/model/ktddecv/handlingInformation>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Allowance Charge
- **IRI:** <https://iri.suomi.fi/model/ktddecv/AllowanceCharge>
- **Identifier:** AllowanceCharge
- **Created:** 2025-08-04T12:50:10.300000+00:00
- **Modified:** 2025-08-04T12:51:26.608000+00:00
- **Subject:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-108>
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Object properties with this class as domain:**
  - **has amount** (<https://iri.suomi.fi/model/ktddecv/hasAmount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
  - **base amount** (<https://iri.suomi.fi/model/ktddecv/baseAmount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
  - **per unit amount** (<https://iri.suomi.fi/model/ktddecv/perUnitAmount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
  - **charged by party** (<https://iri.suomi.fi/model/ktddecv/chargedByParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **charged to party** (<https://iri.suomi.fi/model/ktddecv/chargedToParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>

- **Datatype properties with this class as domain:**
  - **Charge Indicator** (<https://iri.suomi.fi/model/ktddecv/chargeIndicator>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Allowance Charge Reason Code** (<https://iri.suomi.fi/model/ktddecv/allowanceChargeReasonCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal> — Enumerated “charge reason” code list (e.g., ADVISE, CONFIRMATION, AMENDMENT, NEGOTIATION, DISCREPANCY, COURIER, SWIFT, HANDLING, OTHER).
  - **Multiplier Factor Percent** (<https://iri.suomi.fi/model/ktddecv/multiplierFactorPercent>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal> — A percentage rate used to compute an additional or reduced monetary amount from a specified base amount. The calculated amount equals the base amount multiplied by this percentage divided by 100.
  - **Calculation Percent** (<https://iri.suomi.fi/model/ktddecv/calculationPercent>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal> — Percentage when the charge is calculated from a base amount.

### Amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Amount>
- **Identifier:** Amount
- **Created:** 2025-06-27T10:53:24.068000+00:00
- **Modified:** 2025-06-27T10:53:24.068000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Datatype properties with this class as domain:**
  - **Amount Value** (<https://iri.suomi.fi/model/ktddecv/amountValue>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Unit Code** (<https://iri.suomi.fi/model/ktddecv/unitCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal> — Unit of measure for non-monetary amounts (UCUM or UN/ECE Rec 20). Not used for money.

### ATA Carnet
- **IRI:** <https://iri.suomi.fi/model/ktddecv/ATACarnet>
- **Identifier:** ATACarnet
- **Created:** 2025-09-05T11:45:47.837000+00:00
- **Modified:** 2025-09-05T11:45:47.837000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Availability Method
- **IRI:** <https://iri.suomi.fi/model/ktddecv/AvailabilityMethod>
- **Identifier:** AvailabilityMethod
- **Created:** 2025-08-25T12:18:03.176000+00:00
- **Modified:** 2025-08-25T12:20:09.840000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2004/02/skos/core#Concept>

### Availability Qualifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/AvailabilityQualifier>
- **Identifier:** AvailabilityQualifier
- **Created:** 2025-08-28T11:01:23.402000+00:00
- **Modified:** 2025-08-28T11:01:23.402000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2004/02/skos/core#Concept>

### Bank
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Bank>
- **Identifier:** Bank
- **Created:** 2025-06-05T13:25:42.164000+00:00
- **Modified:** 2025-06-05T13:25:42.164000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/FinancialInstitution>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Bank Account
- **IRI:** <https://iri.suomi.fi/model/ktddecv/BankAccount>
- **Identifier:** BankAccount
- **Created:** 2025-06-09T14:09:58.142000+00:00
- **Modified:** 2025-06-09T14:09:58.142000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Datatype properties with this class as domain:**
  - **Bank Account Identifier** (<https://iri.suomi.fi/model/ktddecv/bankAccountIdentifier>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Bank Instruction
- **IRI:** <https://iri.suomi.fi/model/ktddecv/BankInstruction>
- **Description:**
  - An instruction directed to a bank in the context of trade finance (e.g., documentary credit).
- **Identifier:** BankInstruction
- **Created:** 2025-09-16T11:08:02.695000+00:00
- **Modified:** 2025-09-16T11:08:02.695000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <https://iri.suomi.fi/model/ktddecv/Instruction>

### Bill of Exchange
- **IRI:** <https://iri.suomi.fi/model/ktddecv/BillOfExchange>
- **Identifier:** BillOfExchange
- **Created:** 2025-09-05T11:47:29.001000+00:00
- **Modified:** 2025-09-05T11:47:29.001000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Object properties with this class as domain:**
  - **has tenor** (<https://iri.suomi.fi/model/ktddecv/hasTenor>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Tenor>

### Bill of Lading
- **IRI:** <https://iri.suomi.fi/model/ktddecv/BillOfLading>
- **Identifier:** BillOfLading
- **Created:** 2024-11-04T15:07:07.783000+00:00
- **Modified:** 2024-11-04T15:07:07.783000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Business Document
- **IRI:** <https://iri.suomi.fi/model/ktddecv/BusinessDocument>
- **Description:**
  - An information artifact exchanged in trade, transport, customs, finance, or insurance processes.
- **Identifier:** BusinessDocument
- **Created:** 2025-09-16T11:20:57.897000+00:00
- **Modified:** 2025-09-16T11:27:08.821000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <https://iri.suomi.fi/model/ktddecv/CommunicationEntity>

- **Object properties with this class as domain:**
  - **document type** (<https://iri.suomi.fi/model/ktddecv/documentType>) — some/all values from: <http://www.w3.org/2004/02/skos/core#Concept>
  - **has message** (<https://iri.suomi.fi/model/ktddecv/hasMessage>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Message>

### Business Event
- **IRI:** <https://iri.suomi.fi/model/ktddecv/BusinessEvent>
- **Identifier:** BusinessEvent
- **Created:** 2025-09-16T14:42:43.654000+00:00
- **Modified:** 2025-09-16T14:42:43.654000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Certificate of Origin
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CertificateOfOrigin>
- **Identifier:** CertificateOfOrigin
- **Created:** 2025-09-01T12:36:43.837000+00:00
- **Modified:** 2025-09-01T12:36:43.837000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Object properties with this class as domain:**
  - **certificate number** (<https://iri.suomi.fi/model/ktddecv/certificateNumber>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Identifier>
  - **issuing authority party** (<https://iri.suomi.fi/model/ktddecv/issuingAuthorityParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **preference criterion code** (<https://iri.suomi.fi/model/ktddecv/preferenceCriterionCode>) — some/all values from: <http://www.w3.org/2004/02/skos/core#Concept>
  - **has goods item** (<https://iri.suomi.fi/model/ktddecv/hasGoodsItem>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/GoodsItem>

- **Datatype properties with this class as domain:**
  - **Issue Date** (<https://iri.suomi.fi/model/ktddecv/issueDate>) — some/all values from: <http://www.w3.org/2001/XMLSchema#dateTime>

### Characteristic
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Characteristic>
- **Identifier:** Characteristic
- **Created:** 2025-08-29T12:00:29.445000+00:00
- **Modified:** 2025-08-29T12:00:29.445000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Equivalent to:** <https://vocabulary.uncefact.org/ProductCharacteristic>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### CITES Permit
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CITESPermit>
- **Identifier:** CITESPermit
- **Created:** 2025-09-05T11:44:49.663000+00:00
- **Modified:** 2025-09-09T08:22:12.724000+00:00
- **Subject:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-233>
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Object properties with this class as domain:**
  - **validity period** (<https://iri.suomi.fi/model/ktddecv/validityPeriod>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/PeriodOfTime>

- **Datatype properties with this class as domain:**
  - **Issue Date** (<https://iri.suomi.fi/model/ktddecv/issueDate>) — some/all values from: <http://www.w3.org/2001/XMLSchema#dateTime>
  - **Issuing Authority** (<https://iri.suomi.fi/model/ktddecv/issuingAuthority>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Classification Scheme
- **IRI:** <https://iri.suomi.fi/model/ktddecv/ClassificationScheme>
- **Identifier:** ClassificationScheme
- **Created:** 2025-08-29T12:05:27.512000+00:00
- **Modified:** 2025-08-29T12:05:27.512000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2004/02/skos/core#Concept>

### CODEX Official Certificate
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CODEXOfficialCertificate>
- **Identifier:** CODEXOfficialCertificate
- **Created:** 2025-09-05T11:45:22.704000+00:00
- **Modified:** 2025-09-05T11:45:22.704000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Commercial Invoice
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CommercialInvoice>
- **Identifier:** CommercialInvoice
- **Created:** 2024-11-04T15:04:05.855000+00:00
- **Modified:** 2024-11-04T15:04:38.334000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Object properties with this class as domain:**
  - **has invoicee** (<https://iri.suomi.fi/model/ktddecv/hasInvoicee>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **invoice document** (<https://iri.suomi.fi/model/ktddecv/invoiceDocument>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Document>
  - **total amount** (<https://iri.suomi.fi/model/ktddecv/totalAmount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Amount>
  - **invoice payment terms** (<https://iri.suomi.fi/model/ktddecv/invoicePaymentTerms>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/PaymentTerms>
  - **invoicee party** (<https://iri.suomi.fi/model/ktddecv/invoiceeParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **has invoice line** (<https://iri.suomi.fi/model/ktddecv/hasInvoiceLine>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/InvoiceLine>
  - **has delivery** (<https://iri.suomi.fi/model/ktddecv/hasDelivery>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Delivery>

- **Datatype properties with this class as domain:**
  - **Invoice Number** (<https://iri.suomi.fi/model/ktddecv/invoiceNumber>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Invoice Date** (<https://iri.suomi.fi/model/ktddecv/invoiceDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Payment Due Date** (<https://iri.suomi.fi/model/ktddecv/paymentDueDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Commodity Classification
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CommodityClassification>
- **Identifier:** CommodityClassification
- **Created:** 2025-06-27T11:32:55.329000+00:00
- **Modified:** 2025-06-27T11:32:55.329000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/CommodityClassification>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Object properties with this class as domain:**
  - **has classification scheme** (<https://iri.suomi.fi/model/ktddecv/hasClassificationScheme>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/ClassificationScheme>

- **Datatype properties with this class as domain:**
  - **Commodity Code** (<https://iri.suomi.fi/model/ktddecv/commodityCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Classification Code** (<https://iri.suomi.fi/model/ktddecv/classificationCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Communication Entity
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CommunicationEntity>
- **Description:**
  - Thing that can carry sender/receiver party context (e.g., a BusinessDocument or a Message).
- **Identifier:** CommunicationEntity
- **Created:** 2025-09-16T11:26:31.846000+00:00
- **Modified:** 2025-09-16T11:26:31.846000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Object properties with this class as domain:**
  - **sender party** (<https://iri.suomi.fi/model/ktddecv/senderParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **receiver party** (<https://iri.suomi.fi/model/ktddecv/receiverParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>

### Consignment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Consignment>
- **Description:**
  - The grouping of goods for transport, under a single transport contract, from a consignor to a consignee.
- **Identifier:** Consignment
- **Created:** 2024-11-04T15:51:24.756000+00:00
- **Modified:** 2025-08-15T08:16:02.246000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Equivalent to:** <https://vocabulary.uncefact.org/Consignment>, <https://iri.suomi.fi/model/busdoc/1.0.2/Consignment>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Object properties with this class as domain:**
  - **delivered to** (<https://iri.suomi.fi/model/ktddecv/deliveredTo>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **place of delivery** (<https://iri.suomi.fi/model/ktddecv/placeOfDelivery>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>
  - **place of loading** (<https://iri.suomi.fi/model/ktddecv/placeOfLoading>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>
  - **has transport event** (<https://iri.suomi.fi/model/ktddecv/hasTransportEvent>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/TransportEvent>
  - **consignment identifier** (<https://iri.suomi.fi/model/ktddecv/consignmentIdentifier>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Identifier>
  - **total gross weight** (<https://iri.suomi.fi/model/ktddecv/totalGrossWeight>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Quantity>
  - **total net weight** (<https://iri.suomi.fi/model/ktddecv/totalNetWeight>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Quantity>
  - **total package count** (<https://iri.suomi.fi/model/ktddecv/totalPackageCount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Quantity>
  - **has goods item** (<https://iri.suomi.fi/model/ktddecv/hasGoodsItem>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/GoodsItem>
  - **has package** (<https://iri.suomi.fi/model/ktddecv/hasPackage>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Package>
  - **place of receipt** (<https://iri.suomi.fi/model/ktddecv/placeOfReceipt>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>
  - **transshipment place** (<https://iri.suomi.fi/model/ktddecv/transshipmentPlace>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>
  - **final destination place** (<https://iri.suomi.fi/model/ktddecv/finalDestinationPlace>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>
  - **place of discharge** (<https://iri.suomi.fi/model/ktddecv/placeOfDischarge>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location> — The location where goods are taken off a means of transport.

- **Datatype properties with this class as domain:**
  - **Despatch Date** (<https://iri.suomi.fi/model/ktddecv/despatchDate>) — some/all values from: <http://www.w3.org/2001/XMLSchema#dateTime>
  - **Delivery Date** (<https://iri.suomi.fi/model/ktddecv/deliveryDate>) — some/all values from: <http://www.w3.org/2001/XMLSchema#dateTime>

### Consignment Security Declaration
- **IRI:** <https://iri.suomi.fi/model/ktddecv/ConsignmentSecurityDeclaration>
- **Identifier:** ConsignmentSecurityDeclaration
- **Created:** 2025-09-05T11:43:35.376000+00:00
- **Modified:** 2025-09-05T11:43:35.376000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Contract
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Contract>
- **Identifier:** Contract
- **Created:** 2025-06-09T14:50:23.922000+00:00
- **Modified:** 2025-06-09T14:50:23.922000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Datatype properties with this class as domain:**
  - **Contract Identifier** (<https://iri.suomi.fi/model/ktddecv/contractIdentifier>) — some/all values from: <http://www.w3.org/2001/XMLSchema#string>

### Country
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Country>
- **Identifier:** Country
- **Created:** 2024-11-07T07:54:19.657000+00:00
- **Modified:** 2025-09-09T09:11:06.916000+00:00
- **Subject:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-208>
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Equivalent to:** <https://gs1.org/voc/Country>, <https://vocabulary.uncefact.org/Country>, <https://iri.suomi.fi/model/busdoc/1.0.2/Country>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Datatype properties with this class as domain:**
  - **Country Name** (<https://iri.suomi.fi/model/ktddecv/countryName>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Country Code** (<https://iri.suomi.fi/model/ktddecv/countryCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Credit Availability
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CreditAvailability>
- **Description:**
  - A structured statement of where (party/place) and how (method/conditions) a documentary credit is available.
- **Identifier:** CreditAvailability
- **Created:** 2025-08-28T10:45:59.868000+00:00
- **Modified:** 2025-08-28T10:45:59.868000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Object properties with this class as domain:**
  - **has availability method** (<https://iri.suomi.fi/model/ktddecv/hasAvailabilityMethod>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/AvailabilityMethod>
  - **available with party** (<https://iri.suomi.fi/model/ktddecv/availableWithParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **available with qualifier** (<https://iri.suomi.fi/model/ktddecv/availableWithQualifier>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/AvailabilityQualifier>
  - **available at place** (<https://iri.suomi.fi/model/ktddecv/availableAtPlace>) — some/all values from: <https://iri.suomi.fi/model/ktddu/0.0.1/Place>
  - **drawee party** (<https://iri.suomi.fi/model/ktddecv/draweeParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party> — Party on whom a demand for payment is drawn and who is ordered to pay (e.g., in a bill of exchange/draft/cheque).
  - **obligor party** (<https://iri.suomi.fi/model/ktddecv/obligorParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party> — Party that bears a duty to perform an obligation (e.g., pay money, deliver goods, perform a service) under a business commitment.
  - **payee party** (<https://iri.suomi.fi/model/ktddecv/payeeParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party> — Party to whom a payment is to be made under an obligation or instrument.
  - **has amount** (<https://iri.suomi.fi/model/ktddecv/hasAmount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>

- **Datatype properties with this class as domain:**
  - **Maturity Date** (<https://iri.suomi.fi/model/ktddecv/maturityDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal> — The actual deferred payment due date, when determinable.

### Customs Bond
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CustomsBond>
- **Identifier:** CustomsBond
- **Created:** 2025-09-05T11:45:35.600000+00:00
- **Modified:** 2025-09-05T11:45:35.600000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Object properties with this class as domain:**
  - **surety party** (<https://iri.suomi.fi/model/ktddecv/suretyParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>

- **Datatype properties with this class as domain:**
  - **Bond Number** (<https://iri.suomi.fi/model/ktddecv/bondNumber>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Customs Declaration
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CustomsDeclaration>
- **Description:**
  - Summary declaration for export/import; links declared goods lines, values and duties/taxes.
- **Identifier:** CustomsDeclaration
- **Created:** 2025-09-01T14:48:00.827000+00:00
- **Modified:** 2025-09-09T09:12:30.301000+00:00
- **Subject:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-237>
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Object properties with this class as domain:**
  - **declaration number** (<https://iri.suomi.fi/model/ktddecv/declarationNumber>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Identifier> — National MRN or declaration number as Identifier node.
  - **declarant party** (<https://iri.suomi.fi/model/ktddecv/declarantParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **exporter party** (<https://iri.suomi.fi/model/ktddecv/exporterParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **importer party** (<https://iri.suomi.fi/model/ktddecv/importerParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **consignee party** (<https://iri.suomi.fi/model/ktddecv/consigneeParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party> — The party to whom the goods are to be delivered.
  - **customs procedure code** (<https://iri.suomi.fi/model/ktddecv/customsProcedureCode>) — some/all values from: <http://www.w3.org/2004/02/skos/core#Concept>
  - **total invoice amount** (<https://iri.suomi.fi/model/ktddecv/totalInvoiceAmount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
  - **statistical value amount** (<https://iri.suomi.fi/model/ktddecv/statisticalValueAmount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
  - **relates to invoice** (<https://iri.suomi.fi/model/ktddecv/relatesToInvoice>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/CommercialInvoice>
  - **relates to transport document** (<https://iri.suomi.fi/model/ktddecv/relatesToTransportDocument>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/TransportDocument>
  - **has goods item** (<https://iri.suomi.fi/model/ktddecv/hasGoodsItem>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/GoodsItem>
  - **includes allowance charge** (<https://iri.suomi.fi/model/ktddecv/includesAllowanceCharge>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/AllowanceCharge>
  - **includes duty tax fee** (<https://iri.suomi.fi/model/ktddecv/includesDutyTaxFee>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/DutyTaxFee>

- **Datatype properties with this class as domain:**
  - **Customs Office Code** (<https://iri.suomi.fi/model/ktddecv/customsOfficeCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Declaration Date** (<https://iri.suomi.fi/model/ktddecv/declarationDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Dangerous Goods
- **IRI:** <https://iri.suomi.fi/model/ktddecv/DangerousGoods>
- **Identifier:** DangerousGoods
- **Created:** 2024-11-07T07:42:50.636000+00:00
- **Modified:** 2025-09-09T08:20:27.947000+00:00
- **Subject:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-217>
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Equivalent to:** <https://vocabulary.uncefact.org/DangerousGoods>, <https://iri.suomi.fi/model/busdoc/1.0.2/HazardousGoodsTransit>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Object properties with this class as domain:**
  - **net quantity per package** (<https://iri.suomi.fi/model/ktddecv/netQuantityPerPackage>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Quantity>
  - **inner packaging quantity** (<https://iri.suomi.fi/model/ktddecv/innerPackagingQuantity>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Quantity>

- **Datatype properties with this class as domain:**
  - **UN Number** (<https://iri.suomi.fi/model/ktddecv/unNumber>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Proper Shipping Name** (<https://iri.suomi.fi/model/ktddecv/properShippingName>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Technical Name** (<https://iri.suomi.fi/model/ktddecv/technicalName>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Hazard Class Code** (<https://iri.suomi.fi/model/ktddecv/hazardClassCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Subsidiary Hazard Code** (<https://iri.suomi.fi/model/ktddecv/subsidiaryHazardCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Packing Group Code** (<https://iri.suomi.fi/model/ktddecv/packingGroupCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Limited Quantity Indicator** (<https://iri.suomi.fi/model/ktddecv/limitedQuantityIndicator>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Excepted Quantity Indicator** (<https://iri.suomi.fi/model/ktddecv/exceptedQuantityIndicator>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Marine Pollutant Indicator** (<https://iri.suomi.fi/model/ktddecv/marinePollutantIndicator>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Flash Point Temperature** (<https://iri.suomi.fi/model/ktddecv/flashPointTemperature>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Packing Instruction Code** (<https://iri.suomi.fi/model/ktddecv/packingInstructionCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Special Provision Code** (<https://iri.suomi.fi/model/ktddecv/specialProvisionCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Hazard Label Code** (<https://iri.suomi.fi/model/ktddecv/hazardLabelCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Dangerous Goods Declaration
- **IRI:** <https://iri.suomi.fi/model/ktddecv/DangerousGoodsDeclaration>
- **Identifier:** DangerousGoodsDeclaration
- **Created:** 2025-09-01T13:06:30.055000+00:00
- **Modified:** 2025-09-01T13:06:30.055000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Object properties with this class as domain:**
  - **declaration number** (<https://iri.suomi.fi/model/ktddecv/declarationNumber>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Identifier> — National MRN or declaration number as Identifier node.
  - **declarant party** (<https://iri.suomi.fi/model/ktddecv/declarantParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **has goods item** (<https://iri.suomi.fi/model/ktddecv/hasGoodsItem>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/GoodsItem>

- **Datatype properties with this class as domain:**
  - **Declaration Date** (<https://iri.suomi.fi/model/ktddecv/declarationDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Delivery
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Delivery>
- **Identifier:** Delivery
- **Created:** 2025-08-04T11:49:44.330000+00:00
- **Modified:** 2025-08-04T11:49:44.330000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Object properties with this class as domain:**
  - **delivery terms** (<https://iri.suomi.fi/model/ktddecv/deliveryTerms>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/TradeDeliveryTerms>
  - **has shipment** (<https://iri.suomi.fi/model/ktddecv/hasShipment>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Shipment>

### Delivery Milestone
- **IRI:** <https://iri.suomi.fi/model/ktddecv/DeliveryMilestone>
- **Identifier:** DeliveryMilestone
- **Created:** 2025-08-28T12:00:17.492000+00:00
- **Modified:** 2025-08-28T12:00:17.492000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Object properties with this class as domain:**
  - **has shipment period** (<https://iri.suomi.fi/model/ktddecv/hasShipmentPeriod>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/PeriodOfTime>

### Document
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Document>
- **Identifier:** Document
- **Created:** 2025-06-27T10:37:31.201000+00:00
- **Modified:** 2025-06-27T10:37:31.201000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Equivalent to:** <https://vocabulary.uncefact.org/Document>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Datatype properties with this class as domain:**
  - **Document Identifier** (<https://iri.suomi.fi/model/ktddecv/documentIdentifier>) — some/all values from: <http://www.w3.org/2001/XMLSchema#string>
  - **Document Date** (<https://iri.suomi.fi/model/ktddecv/documentDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Document Requirement
- **IRI:** <https://iri.suomi.fi/model/ktddecv/DocumentRequirement>
- **Identifier:** DocumentRequirement
- **Created:** 2025-08-12T12:55:30.287000+00:00
- **Modified:** 2025-08-12T12:55:30.287000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Object properties with this class as domain:**
  - **required document type** (<https://iri.suomi.fi/model/ktddecv/requiredDocumentType>) — some/all values from: <http://www.w3.org/2004/02/skos/core#Concept>
  - **issuer party** (<https://iri.suomi.fi/model/ktddecv/issuerParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>

- **Datatype properties with this class as domain:**
  - **Number of Originals** (<https://iri.suomi.fi/model/ktddecv/numberOfOriginals>) — some/all values from: <http://www.w3.org/2001/XMLSchema#integer>
  - **Number of Copies** (<https://iri.suomi.fi/model/ktddecv/numberOfCopies>) — some/all values from: <http://www.w3.org/2001/XMLSchema#integer>

### Documentary Credit
- **IRI:** <https://iri.suomi.fi/model/ktddecv/DocumentaryCredit>
- **Identifier:** DocumentaryCredit
- **Created:** 2025-06-09T14:52:37.067000+00:00
- **Modified:** 2025-09-09T09:11:38.135000+00:00
- **Subject:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-239>
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <https://iri.suomi.fi/model/ktddu/0.0.1/LegalConstruct>, <https://iri.suomi.fi/model/ktddu/0.0.1/InformationObject>

- **Object properties with this class as domain:**
  - **has shipment** (<https://iri.suomi.fi/model/ktddecv/hasShipment>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Shipment>
  - **applicant party** (<https://iri.suomi.fi/model/ktddecv/applicantParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **applicant bank party** (<https://iri.suomi.fi/model/ktddecv/applicantBankParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **applicable rules** (<https://iri.suomi.fi/model/ktddecv/applicableRules>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/RuleSet>
  - **maximum credit amount** (<https://iri.suomi.fi/model/ktddecv/maximumCreditAmount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Amount> — An instruction on a Documentary Credit that the stated credit amount is an absolute ceiling: the total of drawings/claims under the credit must not exceed the stated amount. It is used to cap drawings even where tolerances or qualifying words (e.g., “about/approximately”) might otherwise allow variation.
  - **issuing bank party** (<https://iri.suomi.fi/model/ktddecv/issuingBankParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **advising bank party** (<https://iri.suomi.fi/model/ktddecv/advisingBankParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party> — Association from a documentary credit (letter of credit) to the bank that advises the credit (and any amendments) to the beneficiary.
  - **references pre advice** (<https://iri.suomi.fi/model/ktddecv/referencesPreAdvice>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Document>
  - **place of expiry** (<https://iri.suomi.fi/model/ktddecv/placeOfExpiry>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location> — The place of presentation for the credit (typically “at the counters of … [named bank/branch/location]”). In eUCP contexts, the “place” may be physical (bank/location) and/or an electronic address/system designated for presentation.
  - **covers additional charge** (<https://iri.suomi.fi/model/ktddecv/coversAdditionalCharge>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/AllowanceCharge>
  - **additional amounts covered** (<https://iri.suomi.fi/model/ktddecv/additionalAmountsCovered>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/AdditionalAmountCategory>
  - **has availability method** (<https://iri.suomi.fi/model/ktddecv/hasAvailabilityMethod>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/AvailabilityMethod>
  - **drawee party** (<https://iri.suomi.fi/model/ktddecv/draweeParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party> — Party on whom a demand for payment is drawn and who is ordered to pay (e.g., in a bill of exchange/draft/cheque).
  - **has payment line** (<https://iri.suomi.fi/model/ktddecv/hasPaymentLine>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/PaymentLine>
  - **instruction to bank** (<https://iri.suomi.fi/model/ktddecv/instructionToBank>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/BankInstruction>
  - **advise through bank party** (<https://iri.suomi.fi/model/ktddecv/adviseThroughBankParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **includes allowance charge** (<https://iri.suomi.fi/model/ktddecv/includesAllowanceCharge>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/AllowanceCharge>
  - **has credit availability** (<https://iri.suomi.fi/model/ktddecv/hasCreditAvailability>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/CreditAvailability>
  - **has delivery milestone** (<https://iri.suomi.fi/model/ktddecv/hasDeliveryMilestone>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/DeliveryMilestone>
  - **has shipment period** (<https://iri.suomi.fi/model/ktddecv/hasShipmentPeriod>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/PeriodOfTime>
  - **has presentation period** (<https://iri.suomi.fi/model/ktddecv/hasPresentationPeriod>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/PeriodOfTime>
  - **presentation base event** (<https://iri.suomi.fi/model/ktddecv/presentationBaseEvent>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/ShipmentBasis>
  - **confirmation instruction code** (<https://iri.suomi.fi/model/ktddecv/confirmationInstructionCode>) — some/all values from: <http://www.w3.org/2004/02/skos/core#Concept> — Code indicating whether confirmation is requested, may be added, or is without confirmation.
  - **confirming party** (<https://iri.suomi.fi/model/ktddecv/confirmingParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party> — Party that actually added confirmation.
  - **requested confirmation party** (<https://iri.suomi.fi/model/ktddecv/requestedConfirmationParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party> — Party requested to add confirmation.
  - **has payment terms** (<https://iri.suomi.fi/model/ktddecv/hasPaymentTerms>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/PaymentTerms>
  - **requires document** (<https://iri.suomi.fi/model/ktddecv/requiresDocument>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/DocumentRequirement>
  - **place of presentation** (<https://iri.suomi.fi/model/ktddecv/placeOfPresentation>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location> — The location at which a document, good, declaration, or other required item is formally presented to a designated party or authority.

In the context of a Documentary Credit, the location specified for the presentation of documents by the beneficiary to the nominated bank, confirming bank, or issuing bank for examination and payment.
  - **reimbursing bank party** (<https://iri.suomi.fi/model/ktddecv/reimbursingBankParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **drafts at tenor** (<https://iri.suomi.fi/model/ktddecv/draftsAtTenor>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Tenor>

- **Datatype properties with this class as domain:**
  - **Issue Date** (<https://iri.suomi.fi/model/ktddecv/issueDate>) — some/all values from: <http://www.w3.org/2001/XMLSchema#dateTime>
  - **Credit Identifier** (<https://iri.suomi.fi/model/ktddecv/creditIdentifier>) — some/all values from: <http://www.w3.org/2001/XMLSchema#string>
  - **Expiry Date** (<https://iri.suomi.fi/model/ktddecv/expiryDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal> — The last calendar date on which a complying presentation must be made at the place where the credit expires (i.e., with the bank with which the credit is available, or as otherwise specified in the credit). Express as a calendar date (not a period or free text).
  - **Latest Shipment Date** (<https://iri.suomi.fi/model/ktddecv/latestShipmentDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Partial Shipment Allowed** (<https://iri.suomi.fi/model/ktddecv/partialShipmentAllowed>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Transshipment Allowed** (<https://iri.suomi.fi/model/ktddecv/transshipmentAllowed>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Documentary Credit Type Code** (<https://iri.suomi.fi/model/ktddecv/documentaryCreditTypeCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Presentation Period Days** (<https://iri.suomi.fi/model/ktddecv/presentationPeriodDays>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal> — Number of calendar days after the shipment date within which presentation must be made (SWIFT MT700 :48 is expressed as days).
  - **Latest Presentation Date** (<https://iri.suomi.fi/model/ktddecv/latestPresentationDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal> — Last date on which presentation is permitted under the credit.
  - **Confirmation Added Date** (<https://iri.suomi.fi/model/ktddecv/confirmationAddedDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal> — Date on which confirmation became effective.
  - **Credit Amount Tolerance Percentage** (<https://iri.suomi.fi/model/ktddecv/creditAmountTolerancePercentage>) — some/all values from: <http://www.w3.org/2001/XMLSchema#decimal> — A percentage tolerance applied to the stated credit amount, expressed as a decimal value (e.g. ±10). This indicates by how much drawings may exceed or fall short of the stated amount, without affecting the unit price of goods.
  - **Additional Conditions Text** (<https://iri.suomi.fi/model/ktddecv/additionalConditionsText>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Duty/Tax/Fee
- **IRI:** <https://iri.suomi.fi/model/ktddecv/DutyTaxFee>
- **Description:**
  - Breakdown element for customs duties, taxes, or fees with basis and computed amount.
- **Identifier:** DutyTaxFee
- **Created:** 2025-09-02T06:36:34.156000+00:00
- **Modified:** 2025-09-02T06:36:34.156000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### EMCS Document
- **IRI:** <https://iri.suomi.fi/model/ktddecv/EMCSDocument>
- **Identifier:** EMCSDocument
- **Created:** 2025-09-05T11:46:59.244000+00:00
- **Modified:** 2025-09-05T11:46:59.244000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Excise Guarantee
- **IRI:** <https://iri.suomi.fi/model/ktddecv/ExciseGuarantee>
- **Identifier:** ExciseGuarantee
- **Created:** 2025-09-05T11:46:46.720000+00:00
- **Modified:** 2025-09-05T11:46:46.720000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Export Import License
- **IRI:** <https://iri.suomi.fi/model/ktddecv/ExportImportLicense>
- **Identifier:** ExportImportLicense
- **Created:** 2025-09-05T11:43:48.794000+00:00
- **Modified:** 2025-09-05T11:43:48.794000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Financial Document
- **IRI:** <https://iri.suomi.fi/model/ktddecv/FinancialDocument>
- **Identifier:** FinancialDocument
- **Created:** 2025-09-05T12:02:12.823000+00:00
- **Modified:** 2025-09-05T12:02:18.422000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Goods Item
- **IRI:** <https://iri.suomi.fi/model/ktddecv/GoodsItem>
- **Description:**
  - Use only for logistics/consignment context: physical goods as packed/shipped (quantities, weights, marks &amp; numbers, packaging, DG info, etc.).
- **Identifier:** GoodsItem
- **Created:** 2025-06-09T16:45:16.449000+00:00
- **Modified:** 2025-09-09T08:21:45.743000+00:00
- **Subject:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-198>
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/GoodsItem>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Object properties with this class as domain:**
  - **has country of origin** (<https://iri.suomi.fi/model/ktddecv/hasCountryOfOrigin>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Country>
  - **has quantity** (<https://iri.suomi.fi/model/ktddecv/hasQuantity>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Quantity>
  - **applied commodity classification** (<https://iri.suomi.fi/model/ktddecv/appliedCommodityClassification>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/CommodityClassification>
  - **has dangerous goods details** (<https://iri.suomi.fi/model/ktddecv/hasDangerousGoodsDetails>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/DangerousGoods>

- **Datatype properties with this class as domain:**
  - **Product Identifier** (<https://iri.suomi.fi/model/ktddecv/productIdentifier>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Item Description Text** (<https://iri.suomi.fi/model/ktddecv/itemDescriptionText>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal> — Narrative description of the goods/services at item level, usable across all trade documents.
  - **Description of Goods Text** (<https://iri.suomi.fi/model/ktddecv/descriptionOfGoodsText>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Identifier>
- **Description:**
  - subclass of adms:Identifier
- **Identifier:** Identifier
- **Created:** 2025-08-05T11:34:08.381000+00:00
- **Modified:** 2025-09-09T08:21:03.288000+00:00
- **Subject:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-221>
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <https://iri.suomi.fi/model/ktddu/0.0.1/Identifier>

### Instruction
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Instruction>
- **Description:**
  - A directive expressed in a message context, issued by one party to another.

or

A message conveying directives or requests from sender to receiver.
- **Identifier:** Instruction
- **Created:** 2025-08-28T08:40:29.223000+00:00
- **Modified:** 2025-09-16T11:06:42.029000+00:00
- **Subject:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-354>
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <https://iri.suomi.fi/model/ktddecv/Message>

- **Object properties with this class as domain:**
  - **instructing party** (<https://iri.suomi.fi/model/ktddecv/instructingParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **instructed party** (<https://iri.suomi.fi/model/ktddecv/instructedParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>

- **Datatype properties with this class as domain:**
  - **Instruction Text** (<https://iri.suomi.fi/model/ktddecv/instructionText>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Insurance Certificate
- **IRI:** <https://iri.suomi.fi/model/ktddecv/InsuranceCertificate>
- **Identifier:** InsuranceCertificate
- **Created:** 2025-09-01T12:44:09.350000+00:00
- **Modified:** 2025-09-01T12:44:09.350000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Object properties with this class as domain:**
  - **insurer party** (<https://iri.suomi.fi/model/ktddecv/insurerParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **insured party** (<https://iri.suomi.fi/model/ktddecv/insuredParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **beneficiary party** (<https://iri.suomi.fi/model/ktddecv/beneficiaryParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **insured amount** (<https://iri.suomi.fi/model/ktddecv/insuredAmount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
  - **coverage amount** (<https://iri.suomi.fi/model/ktddecv/coverageAmount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
  - **coverage type code** (<https://iri.suomi.fi/model/ktddecv/coverageTypeCode>) — some/all values from: <http://www.w3.org/2004/02/skos/core#Concept>
  - **claims payable at place** (<https://iri.suomi.fi/model/ktddecv/claimsPayableAtPlace>) — some/all values from: <https://iri.suomi.fi/model/ktddu/0.0.1/Place>

- **Datatype properties with this class as domain:**
  - **Insurance Terms Text** (<https://iri.suomi.fi/model/ktddecv/insuranceTermsText>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Insurance Policy Number** (<https://iri.suomi.fi/model/ktddecv/insurancePolicyNumber>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Invoice Line
- **IRI:** <https://iri.suomi.fi/model/ktddecv/InvoiceLine>
- **Identifier:** InvoiceLine
- **Created:** 2025-06-27T11:53:46.227000+00:00
- **Modified:** 2025-09-05T11:52:15.882000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Equivalent to:** <https://vocabulary.uncefact.org/LineTradeSettlement>, <https://iri.suomi.fi/model/busdoc/1.0.2/InvoiceLine>
- **Subclass of:** <https://iri.suomi.fi/model/ktddecv/TradeLineItem>

- **Object properties with this class as domain:**
  - **describes trade product** (<https://iri.suomi.fi/model/ktddecv/describesTradeProduct>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/TradeProduct>
  - **invoiced quantity** (<https://iri.suomi.fi/model/ktddecv/invoicedQuantity>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Quantity>
  - **describes item** (<https://iri.suomi.fi/model/ktddecv/describesItem>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/TradeItem>

### Legal Entity
- **IRI:** <https://iri.suomi.fi/model/ktddecv/LegalEntity>
- **Identifier:** LegalEntity
- **Created:** 2025-08-15T11:03:32.339000+00:00
- **Modified:** 2025-08-15T11:03:32.339000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Location
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Location>
- **Identifier:** Location
- **Created:** 2024-11-07T07:26:48.612000+00:00
- **Modified:** 2025-08-26T14:32:47.206000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Equivalent to:** <https://vocabulary.uncefact.org/Location>, <https://iri.suomi.fi/model/busdoc/1.0.2/Location>
- **Subclass of:** <https://iri.suomi.fi/model/ktddu/0.0.1/Place>

- **Object properties with this class as domain:**
  - **location country** (<https://iri.suomi.fi/model/ktddecv/locationCountry>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Country>
  - **has identifier** (<https://iri.suomi.fi/model/ktddecv/hasIdentifier>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Identifier>
  - **has Address** (<https://iri.suomi.fi/model/ktddecv/hasAddress>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/PostalAddress>

- **Datatype properties with this class as domain:**
  - **Location ID** (<https://iri.suomi.fi/model/ktddecv/locationID>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Location Name** (<https://iri.suomi.fi/model/ktddecv/locationName>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Alternate Name** (<https://iri.suomi.fi/model/ktddecv/alternateName>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Description** (<https://iri.suomi.fi/model/ktddecv/description>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **UN Locode** (<https://iri.suomi.fi/model/ktddecv/unlocode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **IATA Code** (<https://iri.suomi.fi/model/ktddecv/iataCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **ICAO Airport Code** (<https://iri.suomi.fi/model/ktddecv/icaoAirportCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **UIC Station Code** (<https://iri.suomi.fi/model/ktddecv/uicStationCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Customs Office Code** (<https://iri.suomi.fi/model/ktddecv/customsOfficeCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Port Facility Code** (<https://iri.suomi.fi/model/ktddecv/portFacilityCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Terminal Code** (<https://iri.suomi.fi/model/ktddecv/terminalCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Warehouse GLN** (<https://iri.suomi.fi/model/ktddecv/warehouseGLN>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Border Crossing Point Code** (<https://iri.suomi.fi/model/ktddecv/borderCrossingPointCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Post Code** (<https://iri.suomi.fi/model/ktddecv/postCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Latitude** (<https://iri.suomi.fi/model/ktddecv/latitude>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Longitude** (<https://iri.suomi.fi/model/ktddecv/longitude>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Geo WKT** (<https://iri.suomi.fi/model/ktddecv/geoWKT>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Elevation Meters** (<https://iri.suomi.fi/model/ktddecv/elevationMeters>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Time Zone** (<https://iri.suomi.fi/model/ktddecv/timeZone>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Message
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Message>
- **Description:**
  - A sender-to-receiver communication related to a business document, which may carry unstructured text and/or structured qualifiers.
- **Identifier:** Message
- **Created:** 2025-08-12T12:57:00.394000+00:00
- **Modified:** 2025-09-16T11:27:35.498000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <https://iri.suomi.fi/model/ktddecv/CommunicationEntity>

- **Datatype properties with this class as domain:**
  - **Message Subject** (<https://iri.suomi.fi/model/ktddecv/messageSubject>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Message Text** (<https://iri.suomi.fi/model/ktddecv/messageText>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal> — Unstructured content of the message (language-tagged).

### Monetary Amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
- **Identifier:** MonetaryAmount
- **Created:** 2025-08-27T06:16:21.054000+00:00
- **Modified:** 2025-08-27T06:16:37.104000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <https://iri.suomi.fi/model/ktddecv/Amount>

- **Datatype properties with this class as domain:**
  - **Amount Value** (<https://iri.suomi.fi/model/ktddecv/amountValue>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Currency Code** (<https://iri.suomi.fi/model/ktddecv/currencyCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Organic Inspection Certificate
- **IRI:** <https://iri.suomi.fi/model/ktddecv/OrganicInspectionCertificate>
- **Identifier:** OrganicInspectionCertificate
- **Created:** 2025-09-05T11:45:06.431000+00:00
- **Modified:** 2025-09-05T11:45:06.431000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Datatype properties with this class as domain:**
  - **Issue Date** (<https://iri.suomi.fi/model/ktddecv/issueDate>) — some/all values from: <http://www.w3.org/2001/XMLSchema#dateTime>

### Package
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Package>
- **Identifier:** Package
- **Created:** 2025-09-01T09:03:40.569000+00:00
- **Modified:** 2025-09-01T09:03:40.569000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Object properties with this class as domain:**
  - **package type code** (<https://iri.suomi.fi/model/ktddecv/packageTypeCode>) — some/all values from: <http://www.w3.org/2004/02/skos/core#Concept>
  - **sscc** (<https://iri.suomi.fi/model/ktddecv/sscc>) — some/all values from: <http://www.w3.org/2004/02/skos/core#Concept>
  - **seal identifier** (<https://iri.suomi.fi/model/ktddecv/sealIdentifier>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Identifier>
  - **has dangerous goods details** (<https://iri.suomi.fi/model/ktddecv/hasDangerousGoodsDetails>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/DangerousGoods>
  - **has package item** (<https://iri.suomi.fi/model/ktddecv/hasPackageItem>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/PackageItem>

- **Datatype properties with this class as domain:**
  - **Package Count** (<https://iri.suomi.fi/model/ktddecv/packageCount>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Marks and Numbers Text** (<https://iri.suomi.fi/model/ktddecv/marksAndNumbersText>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Sealed Indicator** (<https://iri.suomi.fi/model/ktddecv/sealedIndicator>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Package Item
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PackageItem>
- **Description:**
  - A content record inside a package referencing a GoodsItem and the quantity/attributes of that portion.
- **Identifier:** PackageItem
- **Created:** 2025-09-08T09:37:02.487000+00:00
- **Modified:** 2025-09-08T09:37:02.487000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Object properties with this class as domain:**
  - **for goods item** (<https://iri.suomi.fi/model/ktddecv/forGoodsItem>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/GoodsItem>

### Packing List
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PackingList>
- **Identifier:** PackingList
- **Created:** 2025-09-01T12:10:53.760000+00:00
- **Modified:** 2025-09-09T08:21:59.271000+00:00
- **Subject:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-229>
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Object properties with this class as domain:**
  - **packing list number** (<https://iri.suomi.fi/model/ktddecv/packingListNumber>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Identifier>
  - **has package** (<https://iri.suomi.fi/model/ktddecv/hasPackage>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Package>
  - **total package count** (<https://iri.suomi.fi/model/ktddecv/totalPackageCount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Quantity>
  - **total gross weight** (<https://iri.suomi.fi/model/ktddecv/totalGrossWeight>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Quantity>
  - **total net weight** (<https://iri.suomi.fi/model/ktddecv/totalNetWeight>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Quantity>
  - **relates to invoice** (<https://iri.suomi.fi/model/ktddecv/relatesToInvoice>)

### Party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Party>
- **Identifier:** Party
- **Created:** 2024-11-04T12:43:37.414000+00:00
- **Modified:** 2025-08-26T14:29:32.959000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Equivalent to:** <https://vocabulary.uncefact.org/TradeParty>, <https://iri.suomi.fi/model/busdoc/1.0.2/Party>
- **Subclass of:** <https://iri.suomi.fi/model/ktddu/0.0.1/Actor>

- **Object properties with this class as domain:**
  - **party address** (<https://iri.suomi.fi/model/ktddecv/partyAddress>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Address>
  - **party identifier** (<https://iri.suomi.fi/model/ktddecv/partyIdentifier>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Identifier>
  - **party legal entity** (<https://iri.suomi.fi/model/ktddecv/partyLegalEntity>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/LegalEntity>

- **Datatype properties with this class as domain:**
  - **Name** (<https://iri.suomi.fi/model/ktddecv/name>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Payment Confirmation
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PaymentConfirmation>
- **Identifier:** PaymentConfirmation
- **Created:** 2025-09-05T11:47:14.150000+00:00
- **Modified:** 2025-09-05T11:47:14.150000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Payment Line
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PaymentLine>
- **Description:**
  - One tranche/portion of payment under a mixed-payment documentary credit.
- **Identifier:** PaymentLine
- **Created:** 2025-08-25T12:48:49.110000+00:00
- **Modified:** 2025-08-25T12:48:49.110000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Object properties with this class as domain:**
  - **has amount** (<https://iri.suomi.fi/model/ktddecv/hasAmount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Amount>
  - **payee party** (<https://iri.suomi.fi/model/ktddecv/payeeParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party> — Party to whom a payment is to be made under an obligation or instrument.
  - **payment settlement method** (<https://iri.suomi.fi/model/ktddecv/paymentSettlementMethod>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/AvailabilityMethod>

- **Datatype properties with this class as domain:**
  - **Payment Due Date** (<https://iri.suomi.fi/model/ktddecv/paymentDueDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Payment Schedule Line
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PaymentScheduleLine>
- **Identifier:** PaymentScheduleLine
- **Created:** 2025-08-29T13:03:38.611000+00:00
- **Modified:** 2025-08-29T13:03:38.611000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Object properties with this class as domain:**
  - **has amount** (<https://iri.suomi.fi/model/ktddecv/hasAmount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
  - **base amount** (<https://iri.suomi.fi/model/ktddecv/baseAmount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>

- **Datatype properties with this class as domain:**
  - **Amount Percent Of Base** (<https://iri.suomi.fi/model/ktddecv/amountPercentOfBase>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Payment Due Date** (<https://iri.suomi.fi/model/ktddecv/paymentDueDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Deferred Payment Date** (<https://iri.suomi.fi/model/ktddecv/deferredPaymentDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Payment Terms
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PaymentTerms>
- **Identifier:** PaymentTerms
- **Created:** 2025-06-27T11:13:35.023000+00:00
- **Modified:** 2025-09-09T09:11:51.431000+00:00
- **Subject:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-148>
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/PaymentTerms>, <https://vocabulary.uncefact.org/PaymentTerms>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Object properties with this class as domain:**
  - **has payment schedule line** (<https://iri.suomi.fi/model/ktddecv/hasPaymentScheduleLine>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/PaymentScheduleLine>

- **Datatype properties with this class as domain:**
  - **Payment Term Code** (<https://iri.suomi.fi/model/ktddecv/paymentTermCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Period of Time
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PeriodOfTime>
- **Identifier:** PeriodOfTime
- **Created:** 2025-06-27T11:16:48.589000+00:00
- **Modified:** 2025-06-27T11:16:48.589000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Datatype properties with this class as domain:**
  - **Start Date** (<https://iri.suomi.fi/model/ktddecv/startDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **End Date** (<https://iri.suomi.fi/model/ktddecv/endDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Phytosanitary Certificate
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PhytosanitaryCertificate>
- **Identifier:** PhytosanitaryCertificate
- **Created:** 2025-09-05T11:44:00.331000+00:00
- **Modified:** 2025-09-05T11:44:00.331000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Datatype properties with this class as domain:**
  - **Botanical Details** (<https://iri.suomi.fi/model/ktddecv/botanicalDetails>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Postal Address
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PostalAddress>
- **Identifier:** PostalAddress
- **Created:** 2025-09-05T12:47:40.679000+00:00
- **Modified:** 2025-09-05T12:47:40.679000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Presentation
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Presentation>
- **Identifier:** Presentation
- **Created:** 2025-08-12T12:56:16.266000+00:00
- **Modified:** 2025-08-12T12:56:16.266000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Promissory Note
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PromissoryNote>
- **Identifier:** PromissoryNote
- **Created:** 2025-09-05T11:47:59.433000+00:00
- **Modified:** 2025-09-05T11:47:59.433000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Object properties with this class as domain:**
  - **drawer party** (<https://iri.suomi.fi/model/ktddecv/drawerParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **drawee party** (<https://iri.suomi.fi/model/ktddecv/draweeParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party> — Party on whom a demand for payment is drawn and who is ordered to pay (e.g., in a bill of exchange/draft/cheque).

- **Datatype properties with this class as domain:**
  - **Note Number** (<https://iri.suomi.fi/model/ktddecv/noteNumber>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Maturity Date** (<https://iri.suomi.fi/model/ktddecv/maturityDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal> — The actual deferred payment due date, when determinable.

### Purchase Order
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PurchaseOrder>
- **Identifier:** PurchaseOrder
- **Created:** 2024-11-04T15:03:37.952000+00:00
- **Modified:** 2025-09-09T09:11:25.220000+00:00
- **Subject:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-228>
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Object properties with this class as domain:**
  - **buyer party** (<https://iri.suomi.fi/model/ktddecv/buyerParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **delivery party** (<https://iri.suomi.fi/model/ktddecv/deliveryParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **has delivery** (<https://iri.suomi.fi/model/ktddecv/hasDelivery>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Delivery>
  - **invoicee party** (<https://iri.suomi.fi/model/ktddecv/invoiceeParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **order amount** (<https://iri.suomi.fi/model/ktddecv/orderAmount>)
  - **seller party** (<https://iri.suomi.fi/model/ktddecv/sellerParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **includes allowance charge** (<https://iri.suomi.fi/model/ktddecv/includesAllowanceCharge>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/AllowanceCharge>
  - **defines payment terms** (<https://iri.suomi.fi/model/ktddecv/definesPaymentTerms>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/PaymentTerms>

- **Datatype properties with this class as domain:**
  - **Order Identifier** (<https://iri.suomi.fi/model/ktddecv/orderIdentifier>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Order Date** (<https://iri.suomi.fi/model/ktddecv/orderDate>) — some/all values from: <http://www.w3.org/2001/XMLSchema#dateTime>

### Purchase Order Line
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PurchaseOrderLine>
- **Identifier:** PurchaseOrderLine
- **Created:** 2025-09-05T11:51:24.828000+00:00
- **Modified:** 2025-09-05T11:51:24.828000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <https://iri.suomi.fi/model/ktddecv/TradeLineItem>

### Quantity
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Quantity>
- **Identifier:** Quantity
- **Created:** 2025-06-27T12:12:20.457000+00:00
- **Modified:** 2025-06-27T12:12:20.457000+00:00
- **Subject:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-112>
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Equivalent to:** <https://vocabulary.uncefact.org/QuantityType>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Datatype properties with this class as domain:**
  - **Unit Code** (<https://iri.suomi.fi/model/ktddecv/unitCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal> — Unit of measure for non-monetary amounts (UCUM or UN/ECE Rec 20). Not used for money.
  - **Quantity Value** (<https://iri.suomi.fi/model/ktddecv/quantityValue>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Rail Consignment Note CIM
- **IRI:** <https://iri.suomi.fi/model/ktddecv/RailConsignmentNoteCIM>
- **Identifier:** RailConsignmentNoteCIM
- **Created:** 2025-09-05T11:42:40.845000+00:00
- **Modified:** 2025-09-05T11:42:40.845000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Regulatory Certificate
- **IRI:** <https://iri.suomi.fi/model/ktddecv/RegulatoryCertificate>
- **Identifier:** RegulatoryCertificate
- **Created:** 2025-09-05T12:02:43.113000+00:00
- **Modified:** 2025-09-05T12:02:43.113000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Road Consignment Note CMR
- **IRI:** <https://iri.suomi.fi/model/ktddecv/RoadConsignmentNoteCMR>
- **Identifier:** RoadConsignmentNoteCMR
- **Created:** 2025-09-05T11:42:53.994000+00:00
- **Modified:** 2025-09-05T11:42:53.994000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Rule Set
- **IRI:** <https://iri.suomi.fi/model/ktddecv/RuleSet>
- **Identifier:** RuleSet
- **Created:** 2025-08-12T12:55:50.509000+00:00
- **Modified:** 2025-08-12T12:55:50.509000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Object properties with this class as domain:**
  - **publisher** (<https://iri.suomi.fi/model/ktddecv/publisher>)

- **Datatype properties with this class as domain:**
  - **Rule Set Identifier** (<https://iri.suomi.fi/model/ktddecv/ruleSetIdentifier>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Title** (<https://iri.suomi.fi/model/ktddecv/title>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Version Identifier** (<https://iri.suomi.fi/model/ktddecv/versionIdentifier>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Publication Date** (<https://iri.suomi.fi/model/ktddecv/publicationDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Sea Cargo Manifest
- **IRI:** <https://iri.suomi.fi/model/ktddecv/SeaCargoManifest>
- **Identifier:** SeaCargoManifest
- **Created:** 2025-09-05T11:42:09.413000+00:00
- **Modified:** 2025-09-05T11:42:09.413000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Sea Waybill
- **IRI:** <https://iri.suomi.fi/model/ktddecv/SeaWaybill>
- **Description:**
  - Non-negotiable sea transport document serving as a receipt and evidence of the contract of carriage; identifies shipment, parties, vessel/voyage and routing.
- **Identifier:** SeaWaybill
- **Created:** 2025-09-05T11:41:19.092000+00:00
- **Modified:** 2025-09-08T09:04:29.549000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <https://iri.suomi.fi/model/ktddecv/TransportDocument>

- **Object properties with this class as domain:**
  - **carrier party** (<https://iri.suomi.fi/model/ktddecv/carrierParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party> — For Sea Waybill: The ocean carrier issuing or responsible for the carriage.
  - **shipper party** (<https://iri.suomi.fi/model/ktddecv/shipperParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **consignee party** (<https://iri.suomi.fi/model/ktddecv/consigneeParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party> — The party to whom the goods are to be delivered.
  - **notify party** (<https://iri.suomi.fi/model/ktddecv/notifyParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **place of receipt** (<https://iri.suomi.fi/model/ktddecv/placeOfReceipt>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>
  - **place of loading** (<https://iri.suomi.fi/model/ktddecv/placeOfLoading>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>
  - **place of discharge** (<https://iri.suomi.fi/model/ktddecv/placeOfDischarge>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location> — The location where goods are taken off a means of transport.
  - **freight payable at place** (<https://iri.suomi.fi/model/ktddecv/freightPayableAtPlace>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>
  - **place of issue** (<https://iri.suomi.fi/model/ktddecv/placeOfIssue>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>
  - **has goods item** (<https://iri.suomi.fi/model/ktddecv/hasGoodsItem>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/GoodsItem>
  - **has package** (<https://iri.suomi.fi/model/ktddecv/hasPackage>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Package>
  - **has transport equipment** (<https://iri.suomi.fi/model/ktddecv/hasTransportEquipment>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/TransportEquipment>
  - **has dangerous goods** (<https://iri.suomi.fi/model/ktddecv/hasDangerousGoods>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/DangerousGoods>
  - **total gross weight** (<https://iri.suomi.fi/model/ktddecv/totalGrossWeight>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Quantity>
  - **freight charges amount** (<https://iri.suomi.fi/model/ktddecv/freightChargesAmount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
  - **other charges amount** (<https://iri.suomi.fi/model/ktddecv/otherChargesAmount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>

- **Datatype properties with this class as domain:**
  - **Sea Waybill Number** (<https://iri.suomi.fi/model/ktddecv/seaWaybillNumber>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Vessel Name** (<https://iri.suomi.fi/model/ktddecv/vesselName>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Voyage Number** (<https://iri.suomi.fi/model/ktddecv/voyageNumber>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Issue Date** (<https://iri.suomi.fi/model/ktddecv/issueDate>) — some/all values from: <http://www.w3.org/2001/XMLSchema#dateTime>

### Seal
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Seal>
- **Identifier:** Seal
- **Created:** 2025-09-05T12:01:51.618000+00:00
- **Modified:** 2025-09-09T09:12:45.757000+00:00
- **Subject:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-244>
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Shipment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Shipment>
- **Description:**
  - The set of goods that are the subject of a single sales contract (and usually a single invoice) between a seller and a buyer.
- **Identifier:** Shipment
- **Created:** 2025-08-05T15:02:06.516000+00:00
- **Modified:** 2025-08-26T14:31:38.515000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <https://iri.suomi.fi/model/ktddu/0.0.1/Activity>

- **Object properties with this class as domain:**
  - **is realized by consignment** (<https://iri.suomi.fi/model/ktddecv/isRealizedByConsignment>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Consignment>
  - **seller party** (<https://iri.suomi.fi/model/ktddecv/sellerParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **buyer party** (<https://iri.suomi.fi/model/ktddecv/buyerParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **related order** (<https://iri.suomi.fi/model/ktddecv/relatedOrder>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/PurchaseOrder>
  - **invoice document** (<https://iri.suomi.fi/model/ktddecv/invoiceDocument>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Document>
  - **delivery terms** (<https://iri.suomi.fi/model/ktddecv/deliveryTerms>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/TradeDeliveryTerms>
  - **total goods item quantity** (<https://iri.suomi.fi/model/ktddecv/totalGoodsItemQuantity>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Quantity>
  - **total package quantity** (<https://iri.suomi.fi/model/ktddecv/totalPackageQuantity>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Quantity>
  - **total transport handling unit quantity** (<https://iri.suomi.fi/model/ktddecv/totalTransportHandlingUnitQuantity>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Quantity>
  - **requested delivery period** (<https://iri.suomi.fi/model/ktddecv/requestedDeliveryPeriod>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/PeriodOfTime>
  - **declared customs value amount** (<https://iri.suomi.fi/model/ktddecv/declaredCustomsValueAmount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Amount>
  - **insurance value amount** (<https://iri.suomi.fi/model/ktddecv/insuranceValueAmount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Amount>
  - **has goods item** (<https://iri.suomi.fi/model/ktddecv/hasGoodsItem>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/TradeItem>
  - **has shipment period** (<https://iri.suomi.fi/model/ktddecv/hasShipmentPeriod>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/PeriodOfTime>

- **Datatype properties with this class as domain:**
  - **Contract Number** (<https://iri.suomi.fi/model/ktddecv/contractNumber>) — some/all values from: <http://www.w3.org/2001/XMLSchema#string>
  - **Shipment Identifier** (<https://iri.suomi.fi/model/ktddecv/shipmentIdentifier>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Hazardous Risk Indicator** (<https://iri.suomi.fi/model/ktddecv/hazardousRiskIndicator>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Place of Receipt UN Locode** (<https://iri.suomi.fi/model/ktddecv/placeOfReceiptUNLocode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Port of Loading UN Locode** (<https://iri.suomi.fi/model/ktddecv/portOfLoadingUNLocode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Port Of Discharge UN Locode** (<https://iri.suomi.fi/model/ktddecv/portOfDischargeUNLocode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Place of Delivery UN Locode** (<https://iri.suomi.fi/model/ktddecv/placeOfDeliveryUNLocode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Final Destination UN Locode** (<https://iri.suomi.fi/model/ktddecv/finalDestinationUNLocode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Shipment Basis
- **IRI:** <https://iri.suomi.fi/model/ktddecv/ShipmentBasis>
- **Identifier:** ShipmentBasis
- **Created:** 2025-08-29T08:54:21.055000+00:00
- **Modified:** 2025-08-29T08:54:21.055000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2004/02/skos/core#Concept>

### Ships Delivery Order
- **IRI:** <https://iri.suomi.fi/model/ktddecv/ShipsDeliveryOrder>
- **Description:**
  - A document issued by a carrier or its agent authorizing delivery of the goods to the consignee or other named party. Used after arrival of a vessel to release cargo covered by a bill of lading or sea waybill.
- **Identifier:** ShipsDeliveryOrder
- **Created:** 2025-09-05T11:41:52.380000+00:00
- **Modified:** 2025-09-08T09:55:19.061000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <https://iri.suomi.fi/model/ktddecv/TransportDocument>

- **Object properties with this class as domain:**
  - **carrier party** (<https://iri.suomi.fi/model/ktddecv/carrierParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party> — For Sea Waybill: The ocean carrier issuing or responsible for the carriage.
  - **consignee party** (<https://iri.suomi.fi/model/ktddecv/consigneeParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party> — The party to whom the goods are to be delivered.
  - **notify party** (<https://iri.suomi.fi/model/ktddecv/notifyParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **relates to transport document** (<https://iri.suomi.fi/model/ktddecv/relatesToTransportDocument>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/TransportDocument>

- **Datatype properties with this class as domain:**
  - **Ships Delivery Order Number** (<https://iri.suomi.fi/model/ktddecv/shipsDeliveryOrderNumber>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Status
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Status>
- **Identifier:** Status
- **Created:** 2025-08-12T12:56:32.661000+00:00
- **Modified:** 2025-08-12T12:56:32.661000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Tenor
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Tenor>
- **Description:**
  - Rule that determines when a payment/obligation under a negotiable or deferred-payment instrument becomes due.
- **Identifier:** Tenor
- **Created:** 2025-09-16T14:41:53.453000+00:00
- **Modified:** 2025-09-16T14:41:53.453000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### TIR Carnet
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TIRCarnet>
- **Identifier:** TIRCarnet
- **Created:** 2025-09-05T11:46:04.093000+00:00
- **Modified:** 2025-09-05T11:46:04.093000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Trade Delivery Terms
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TradeDeliveryTerms>
- **Identifier:** TradeDeliveryTerms
- **Created:** 2025-08-04T11:51:27.712000+00:00
- **Modified:** 2025-08-04T11:51:27.712000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Object properties with this class as domain:**
  - **incoterms code** (<https://iri.suomi.fi/model/ktddecv/incotermsCode>) — some/all values from: <http://www.w3.org/2004/02/skos/core#Concept>
  - **applicable rules** (<https://iri.suomi.fi/model/ktddecv/applicableRules>) — some/all values from: <http://www.w3.org/2004/02/skos/core#Concept>
  - **place of loading** (<https://iri.suomi.fi/model/ktddecv/placeOfLoading>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>
  - **place of delivery** (<https://iri.suomi.fi/model/ktddecv/placeOfDelivery>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>
  - **includes allowance charge** (<https://iri.suomi.fi/model/ktddecv/includesAllowanceCharge>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/AllowanceCharge>
  - **relates to consignment** (<https://iri.suomi.fi/model/ktddecv/relatesToConsignment>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Consignment>
  - **has delivery period** (<https://iri.suomi.fi/model/ktddecv/hasDeliveryPeriod>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/PeriodOfTime>
  - **place of discharge** (<https://iri.suomi.fi/model/ktddecv/placeOfDischarge>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location> — The location where goods are taken off a means of transport.

- **Datatype properties with this class as domain:**
  - **Delivery Terms Text** (<https://iri.suomi.fi/model/ktddecv/deliveryTermsText>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Trade Item
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TradeItem>
- **Identifier:** TradeItem
- **Created:** 2025-08-05T11:47:58.905000+00:00
- **Modified:** 2025-08-29T11:34:54.224000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Equivalent to:** <https://iri.suomi.fi/model/ktddecv/TradeProduct>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Trade Line Item
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TradeLineItem>
- **Description:**
  - A distinct line item in a trade transaction, representing an ordered, invoiced, shipped, or declared good or service, including its quantity, price, and related references.
- **Identifier:** TradeLineItem
- **Created:** 2025-09-05T11:50:47.047000+00:00
- **Modified:** 2025-09-05T11:50:47.047000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Trade Product
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TradeProduct>
- **Description:**
  - A product or service offered or supplied in trade, identified and classified for commercial, fiscal or regulatory purposes.
- **Identifier:** TradeProduct
- **Created:** 2025-06-27T11:37:39.984000+00:00
- **Modified:** 2025-09-09T09:10:07.535000+00:00
- **Subject:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-264>
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Equivalent to:** <https://vocabulary.uncefact.org/TradeProduct>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Object properties with this class as domain:**
  - **origin country** (<https://iri.suomi.fi/model/ktddecv/originCountry>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Country>
  - **applicable commodity classification** (<https://iri.suomi.fi/model/ktddecv/applicableCommodityClassification>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/CommodityClassification>
  - **has characteristic** (<https://iri.suomi.fi/model/ktddecv/hasCharacteristic>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Characteristic>

- **Datatype properties with this class as domain:**
  - **Product Name** (<https://iri.suomi.fi/model/ktddecv/productName>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Product Description** (<https://iri.suomi.fi/model/ktddecv/productDescription>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Transit Accompanying Document
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TransitAccompanyingDocument>
- **Description:**
  - The Transit Accompanying Document (TAD) used in the EU Common Transit procedure, identified by an MRN and containing information about offices of departure, destination, and transit.
- **Identifier:** TransitAccompanyingDocument
- **Created:** 2025-09-05T11:46:20.426000+00:00
- **Modified:** 2025-09-05T13:56:11.539000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <https://iri.suomi.fi/model/ktddecv/Document>

- **Object properties with this class as domain:**
  - **office of departure** (<https://iri.suomi.fi/model/ktddecv/officeOfDeparture>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location> — The customs office of departure where the transit procedure begins.
  - **office of destination** (<https://iri.suomi.fi/model/ktddecv/officeOfDestination>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>
  - **transit office** (<https://iri.suomi.fi/model/ktddecv/transitOffice>)

- **Datatype properties with this class as domain:**
  - **MRN** (<https://iri.suomi.fi/model/ktddecv/mrn>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal> — The Movement Reference Number (MRN) uniquely identifying the Transit Accompanying Document.

### Transport Document
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TransportDocument>
- **Identifier:** TransportDocument
- **Created:** 2025-09-01T09:03:14.071000+00:00
- **Modified:** 2025-09-09T09:10:24.215000+00:00
- **Subject:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-226>
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Object properties with this class as domain:**
  - **transport document type code** (<https://iri.suomi.fi/model/ktddecv/transportDocumentTypeCode>) — some/all values from: <http://www.w3.org/2004/02/skos/core#Concept>
  - **carrier party** (<https://iri.suomi.fi/model/ktddecv/carrierParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party> — For Sea Waybill: The ocean carrier issuing or responsible for the carriage.
  - **shipper party** (<https://iri.suomi.fi/model/ktddecv/shipperParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **consignee party** (<https://iri.suomi.fi/model/ktddecv/consigneeParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party> — The party to whom the goods are to be delivered.
  - **notify party** (<https://iri.suomi.fi/model/ktddecv/notifyParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **place of issue** (<https://iri.suomi.fi/model/ktddecv/placeOfIssue>) — some/all values from: <https://iri.suomi.fi/model/ktddu/0.0.1/Place>
  - **freight payable at place** (<https://iri.suomi.fi/model/ktddecv/freightPayableAtPlace>) — some/all values from: <https://iri.suomi.fi/model/ktddu/0.0.1/Place>
  - **relates to consignment** (<https://iri.suomi.fi/model/ktddecv/relatesToConsignment>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Consignment>
  - **has package** (<https://iri.suomi.fi/model/ktddecv/hasPackage>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Package>
  - **has goods item** (<https://iri.suomi.fi/model/ktddecv/hasGoodsItem>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/GoodsItem>
  - **place of loading** (<https://iri.suomi.fi/model/ktddecv/placeOfLoading>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>
  - **place of delivery** (<https://iri.suomi.fi/model/ktddecv/placeOfDelivery>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>

- **Datatype properties with this class as domain:**
  - **Issue Date** (<https://iri.suomi.fi/model/ktddecv/issueDate>) — some/all values from: <http://www.w3.org/2001/XMLSchema#dateTime>
  - **Number of Originals** (<https://iri.suomi.fi/model/ktddecv/numberOfOriginals>) — some/all values from: <http://www.w3.org/2001/XMLSchema#integer>
  - **On Board Date** (<https://iri.suomi.fi/model/ktddecv/onBoardDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Vessel Name** (<https://iri.suomi.fi/model/ktddecv/vesselName>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Voyage Number** (<https://iri.suomi.fi/model/ktddecv/voyageNumber>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Transport Document Number** (<https://iri.suomi.fi/model/ktddecv/transportDocumentNumber>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Freight Payment Term Code** (<https://iri.suomi.fi/model/ktddecv/freightPaymentTermCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Transport Equipment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TransportEquipment>
- **Identifier:** TransportEquipment
- **Created:** 2025-09-01T09:06:29.499000+00:00
- **Modified:** 2025-09-01T09:06:29.499000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Object properties with this class as domain:**
  - **equipment identifier** (<https://iri.suomi.fi/model/ktddecv/equipmentIdentifier>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Identifier>

### Transport Event
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TransportEvent>
- **Identifier:** TransportEvent
- **Created:** 2025-08-15T08:27:54.751000+00:00
- **Modified:** 2025-09-09T09:10:40.651000+00:00
- **Subject:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-207>
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Equivalent to:** <https://vocabulary.uncefact.org/TransportEvent>, <https://iri.suomi.fi/model/busdoc/1.0.2/TransportEvent>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Object properties with this class as domain:**
  - **uses transport means** (<https://iri.suomi.fi/model/ktddecv/usesTransportMeans>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/TransportMeans>
  - **event identifier** (<https://iri.suomi.fi/model/ktddecv/eventIdentifier>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Identifier>
  - **event type code** (<https://iri.suomi.fi/model/ktddecv/eventTypeCode>) — some/all values from: <http://www.w3.org/2004/02/skos/core#Concept>
  - **event place** (<https://iri.suomi.fi/model/ktddecv/eventPlace>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>
  - **reported by party** (<https://iri.suomi.fi/model/ktddecv/reportedByParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
  - **relates to consignment** (<https://iri.suomi.fi/model/ktddecv/relatesToConsignment>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Consignment>
  - **relates to transport document** (<https://iri.suomi.fi/model/ktddecv/relatesToTransportDocument>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/TransportDocument>
  - **observed transport means** (<https://iri.suomi.fi/model/ktddecv/observedTransportMeans>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/TransportMeans>
  - **relates to package** (<https://iri.suomi.fi/model/ktddecv/relatesToPackage>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Package>
  - **relates to goods item** (<https://iri.suomi.fi/model/ktddecv/relatesToGoodsItem>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/GoodsItem>
  - **transport mode code** (<https://iri.suomi.fi/model/ktddecv/transportModeCode>) — some/all values from: <http://www.w3.org/2004/02/skos/core#Concept>

- **Datatype properties with this class as domain:**
  - **Event Date Time** (<https://iri.suomi.fi/model/ktddecv/eventDateTime>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Event Note Text** (<https://iri.suomi.fi/model/ktddecv/eventNoteText>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Transport Leg
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TransportLeg>
- **Identifier:** TransportLeg
- **Created:** 2025-09-01T09:05:21.386000+00:00
- **Modified:** 2025-09-01T09:05:21.386000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Object properties with this class as domain:**
  - **uses transport equipment** (<https://iri.suomi.fi/model/ktddecv/usesTransportEquipment>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/TransportEquipment>
  - **departure place** (<https://iri.suomi.fi/model/ktddecv/departurePlace>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>
  - **arrival place** (<https://iri.suomi.fi/model/ktddecv/arrivalPlace>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>

- **Datatype properties with this class as domain:**
  - **Departure Date Time** (<https://iri.suomi.fi/model/ktddecv/departureDateTime>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Arrival Date Time** (<https://iri.suomi.fi/model/ktddecv/arrivalDateTime>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Transport Means
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TransportMeans>
- **Identifier:** TransportMeans
- **Created:** 2025-08-05T12:57:28.169000+00:00
- **Modified:** 2025-09-09T08:20:41.875000+00:00
- **Subject:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-209>
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Datatype properties with this class as domain:**
  - **Vehicle Name** (<https://iri.suomi.fi/model/ktddecv/vehicleName>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **IMO Ship ID** (<https://iri.suomi.fi/model/ktddecv/iMOShipID>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
  - **Flight Number** (<https://iri.suomi.fi/model/ktddecv/flightNumber>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Veterinary Certificate
- **IRI:** <https://iri.suomi.fi/model/ktddecv/VeterinaryCertificate>
- **Identifier:** VeterinaryCertificate
- **Created:** 2025-09-05T11:44:13.692000+00:00
- **Modified:** 2025-09-09T09:12:12.387000+00:00
- **Subject:** <https://iri.suomi.fi/terminology/a89c6af7a/concept-232>
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

- **Datatype properties with this class as domain:**
  - **Origin Establishment** (<https://iri.suomi.fi/model/ktddecv/originEstablishment>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Warehouse
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Warehouse>
- **Identifier:** Warehouse
- **Created:** 2025-09-05T12:02:01.909000+00:00
- **Modified:** 2025-09-05T12:02:01.909000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

### Warehouse Receipt
- **IRI:** <https://iri.suomi.fi/model/ktddecv/WarehouseReceipt>
- **Identifier:** WarehouseReceipt
- **Created:** 2025-09-05T11:43:06.492000+00:00
- **Modified:** 2025-09-05T11:43:06.492000+00:00
- **isDefinedBy:** <https://iri.suomi.fi/model/ktddecv/>
- **Subclass of:** <http://www.w3.org/2002/07/owl#Thing>

<a id="object-properties"></a>
## Object Properties

### additional amounts covered
- **IRI:** <https://iri.suomi.fi/model/ktddecv/additionalAmountsCovered>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### advise through bank party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/adviseThroughBankParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### advising bank party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/advisingBankParty>
- **Description:**
  - Association from a documentary credit (letter of credit) to the bank that advises the credit (and any amendments) to the beneficiary.
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### airport of departure
- **IRI:** <https://iri.suomi.fi/model/ktddecv/airportOfDeparture>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### airport of destination
- **IRI:** <https://iri.suomi.fi/model/ktddecv/airportOfDestination>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### applicable commodity classification
- **IRI:** <https://iri.suomi.fi/model/ktddecv/applicableCommodityClassification>
- **Subproperty of:** <https://iri.suomi.fi/model/ktddecv/hasCommodityClassification>

### applicable rules
- **IRI:** <https://iri.suomi.fi/model/ktddecv/applicableRules>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### applicant bank party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/applicantBankParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### applicant party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/applicantParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### applied commodity classification
- **IRI:** <https://iri.suomi.fi/model/ktddecv/appliedCommodityClassification>
- **Subproperty of:** <https://iri.suomi.fi/model/ktddecv/hasCommodityClassification>

### arrival place
- **IRI:** <https://iri.suomi.fi/model/ktddecv/arrivalPlace>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### available at place
- **IRI:** <https://iri.suomi.fi/model/ktddecv/availableAtPlace>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### available with party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/availableWithParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### available with qualifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/availableWithQualifier>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### base amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/baseAmount>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### beneficiary party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/beneficiaryParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### buyer party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/buyerParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### carrier party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/carrierParty>
- **Description:**
  - For Sea Waybill: The ocean carrier issuing or responsible for the carriage.
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### certificate number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/certificateNumber>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### chargeable weight
- **IRI:** <https://iri.suomi.fi/model/ktddecv/chargeableWeight>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### charged by party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/chargedByParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### charged to party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/chargedToParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### claims payable at place
- **IRI:** <https://iri.suomi.fi/model/ktddecv/claimsPayableAtPlace>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### confirmation instruction code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/confirmationInstructionCode>
- **Description:**
  - Code indicating whether confirmation is requested, may be added, or is without confirmation.
- **Range:** <http://www.w3.org/2004/02/skos/core#Concept>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### confirming bank party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/confirmingBankParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### confirming party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/confirmingParty>
- **Description:**
  - Party that actually added confirmation.
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### consignee party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/consigneeParty>
- **Description:**
  - The party to whom the goods are to be delivered.
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### consignment identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/consignmentIdentifier>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### consignor party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/consignorParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### country of origin code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/countryOfOriginCode>
- **Description:**
  - Country of non-preferential or preferential origin for the goods line, as an ISO 3166-1 code concept.
- **Range:** <http://www.w3.org/2004/02/skos/core#Concept>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### coverage amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/coverageAmount>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### coverage type code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/coverageTypeCode>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### covered shipment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/coveredShipment>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### covers additional charge
- **IRI:** <https://iri.suomi.fi/model/ktddecv/coversAdditionalCharge>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### covers contract
- **IRI:** <https://iri.suomi.fi/model/ktddecv/coversContract>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### creditor specified financial institution
- **IRI:** <https://iri.suomi.fi/model/ktddecv/creditorSpecifiedFinancialInstitution>
- **Subproperty of:** <https://vocabulary.uncefact.org/creditorSpecifiedFinancialInstitution>

### customs procedure code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/customsProcedureCode>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### declarant party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/declarantParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### declaration number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/declarationNumber>
- **Description:**
  - National MRN or declaration number as Identifier node.
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### declared customs value amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/declaredCustomsValueAmount>
- **Range:** <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### declared value for carriage
- **IRI:** <https://iri.suomi.fi/model/ktddecv/declaredValueForCarriage>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### defines payment terms
- **IRI:** <https://iri.suomi.fi/model/ktddecv/definesPaymentTerms>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### delivered to
- **IRI:** <https://iri.suomi.fi/model/ktddecv/deliveredTo>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### delivery location
- **IRI:** <https://iri.suomi.fi/model/ktddecv/deliveryLocation>
- **Range:** <https://iri.suomi.fi/model/ktddecv/Location>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### delivery party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/deliveryParty>
- **Subproperty of:** <https://vocabulary.uncefact.org/deliveryParty>
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/deliveryParty_>

### delivery terms
- **IRI:** <https://iri.suomi.fi/model/ktddecv/deliveryTerms>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### departure place
- **IRI:** <https://iri.suomi.fi/model/ktddecv/departurePlace>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### describes item
- **IRI:** <https://iri.suomi.fi/model/ktddecv/describesItem>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### describes trade product
- **IRI:** <https://iri.suomi.fi/model/ktddecv/describesTradeProduct>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### document type
- **IRI:** <https://iri.suomi.fi/model/ktddecv/documentType>
- **Range:** <http://www.w3.org/2004/02/skos/core#Concept>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### drafts at tenor
- **IRI:** <https://iri.suomi.fi/model/ktddecv/draftsAtTenor>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### drawee party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/draweeParty>
- **Description:**
  - Party on whom a demand for payment is drawn and who is ordered to pay (e.g., in a bill of exchange/draft/cheque).
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### drawer party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/drawerParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### equipment identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/equipmentIdentifier>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### event identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/eventIdentifier>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### event place
- **IRI:** <https://iri.suomi.fi/model/ktddecv/eventPlace>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### event type code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/eventTypeCode>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### exporter party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/exporterParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/exporterParty>, <https://vocabulary.uncefact.org/exporterParty>

### final destination place
- **IRI:** <https://iri.suomi.fi/model/ktddecv/finalDestinationPlace>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### first place of receipt
- **IRI:** <https://iri.suomi.fi/model/ktddecv/firstPlaceOfReceipt>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### for goods item
- **IRI:** <https://iri.suomi.fi/model/ktddecv/forGoodsItem>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### freight charges amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/freightChargesAmount>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### freight payable at place
- **IRI:** <https://iri.suomi.fi/model/ktddecv/freightPayableAtPlace>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### from location
- **IRI:** <https://iri.suomi.fi/model/ktddecv/fromLocation>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### governed by rule set
- **IRI:** <https://iri.suomi.fi/model/ktddecv/governedByRuleSet>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has Address
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasAddress>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasAmount>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has applicant
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasApplicant>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has applicant bank
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasApplicantBank>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has availability method
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasAvailabilityMethod>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has beneficiary
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasBeneficiary>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has buyer
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasBuyer>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has characteristic
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasCharacteristic>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has classification scheme
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasClassificationScheme>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has commodity classification
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasCommodityClassification>
- **Description:**
  - Associates an item line with a commodity/service classification entry.
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has consignment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasConsignment>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has country of origin
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasCountryOfOrigin>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has credit availability
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasCreditAvailability>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has dangerous goods
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasDangerousGoods>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has dangerous goods details
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasDangerousGoodsDetails>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has delivery
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasDelivery>
- **Range:** <https://iri.suomi.fi/model/ktddecv/Delivery>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has delivery milestone
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasDeliveryMilestone>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has delivery period
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasDeliveryPeriod>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has drawee
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasDrawee>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has goods item
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasGoodsItem>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasIdentifier>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has invoice line
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasInvoiceLine>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has invoicee
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasInvoicee>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has message
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasMessage>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has package
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasPackage>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has package item
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasPackageItem>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has payment line
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasPaymentLine>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has payment schedule line
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasPaymentScheduleLine>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has payment terms
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasPaymentTerms>
- **Range:** <https://iri.suomi.fi/model/ktddecv/PaymentTerms>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has presentation
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasPresentation>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has presentation period
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasPresentationPeriod>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has product
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasProduct>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has quantity
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasQuantity>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has seller
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasSeller>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has shipment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasShipment>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has shipment period
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasShipmentPeriod>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has status
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasStatus>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has tenor
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasTenor>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has transport equipment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasTransportEquipment>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### has transport event
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasTransportEvent>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### importer party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/importerParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/importerParty>, <https://vocabulary.uncefact.org/importerParty>

### includes allowance charge
- **IRI:** <https://iri.suomi.fi/model/ktddecv/includesAllowanceCharge>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### includes duty tax fee
- **IRI:** <https://iri.suomi.fi/model/ktddecv/includesDutyTaxFee>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### incoterms code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/incotermsCode>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### incoterms location
- **IRI:** <https://iri.suomi.fi/model/ktddecv/incotermsLocation>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### inner packaging quantity
- **IRI:** <https://iri.suomi.fi/model/ktddecv/innerPackagingQuantity>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### instructed party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/instructedParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### instructing party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/instructingParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### instruction to bank
- **IRI:** <https://iri.suomi.fi/model/ktddecv/instructionToBank>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### insurance value amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/insuranceValueAmount>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### insured amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/insuredAmount>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### insured party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/insuredParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### insurer party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/insurerParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### invoice document
- **IRI:** <https://iri.suomi.fi/model/ktddecv/invoiceDocument>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/invoiceDocumentReference>, <https://vocabulary.uncefact.org/invoiceDocument>

### invoice payment terms
- **IRI:** <https://iri.suomi.fi/model/ktddecv/invoicePaymentTerms>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### invoiced quantity
- **IRI:** <https://iri.suomi.fi/model/ktddecv/invoicedQuantity>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### invoicee party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/invoiceeParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### is realized by consignment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/isRealizedByConsignment>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### issuer party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/issuerParty>
- **Range:** <https://iri.suomi.fi/model/ktddecv/Party>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### issuing authority party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/issuingAuthorityParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### issuing bank party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/issuingBankParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### issuing carrier party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/issuingCarrierParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### location country
- **IRI:** <https://iri.suomi.fi/model/ktddecv/locationCountry>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### maximum credit amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/maximumCreditAmount>
- **Description:**
  - An instruction on a Documentary Credit that the stated credit amount is an absolute ceiling: the total of drawings/claims under the credit must not exceed the stated amount. It is used to cap drawings even where tolerances or qualifying words (e.g., “about/approximately”) might otherwise allow variation.
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### net quantity per package
- **IRI:** <https://iri.suomi.fi/model/ktddecv/netQuantityPerPackage>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### nominated bank party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/nominatedBankParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### notify party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/notifyParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### obligee party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/obligeeParty>
- **Description:**
  - Party entitled to receive the performance of an obligation (a payment, delivery, or service).
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### obligor party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/obligorParty>
- **Description:**
  - Party that bears a duty to perform an obligation (e.g., pay money, deliver goods, perform a service) under a business commitment.
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### observed transport means
- **IRI:** <https://iri.suomi.fi/model/ktddecv/observedTransportMeans>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### office of departure
- **IRI:** <https://iri.suomi.fi/model/ktddecv/officeOfDeparture>
- **Description:**
  - The customs office of departure where the transit procedure begins.
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### office of destination
- **IRI:** <https://iri.suomi.fi/model/ktddecv/officeOfDestination>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### order amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/orderAmount>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### origin country
- **IRI:** <https://iri.suomi.fi/model/ktddecv/originCountry>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>
- **Equivalent to:** <https://gs1.org/voc/countryOfOrigin>, <https://iri.suomi.fi/model/busdoc/1.0.2/originCountry>, <https://vocabulary.uncefact.org/originCountry>

### other charges amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/otherChargesAmount>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### package type code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/packageTypeCode>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### packing list number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/packingListNumber>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### party address
- **IRI:** <https://iri.suomi.fi/model/ktddecv/partyAddress>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### party identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/partyIdentifier>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### party legal entity
- **IRI:** <https://iri.suomi.fi/model/ktddecv/partyLegalEntity>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### payee party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/payeeParty>
- **Description:**
  - Party to whom a payment is to be made under an obligation or instrument.
- **Subproperty of:** <https://iri.suomi.fi/model/ktddecv/obligeeParty>

### payer party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/payerParty>
- **Subproperty of:** <https://iri.suomi.fi/model/ktddecv/obligorParty>

### payment location
- **IRI:** <https://iri.suomi.fi/model/ktddecv/paymentLocation>
- **Subproperty of:** <https://vocabulary.uncefact.org/paymentPlaceLocation>

### payment settlement method
- **IRI:** <https://iri.suomi.fi/model/ktddecv/paymentSettlementMethod>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### per unit amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/perUnitAmount>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### place of delivery
- **IRI:** <https://iri.suomi.fi/model/ktddecv/placeOfDelivery>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### place of discharge
- **IRI:** <https://iri.suomi.fi/model/ktddecv/placeOfDischarge>
- **Description:**
  - The location where goods are taken off a means of transport.
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### place of expiry
- **IRI:** <https://iri.suomi.fi/model/ktddecv/placeOfExpiry>
- **Description:**
  - The place of presentation for the credit (typically “at the counters of … [named bank/branch/location]”). In eUCP contexts, the “place” may be physical (bank/location) and/or an electronic address/system designated for presentation.
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### place of issue
- **IRI:** <https://iri.suomi.fi/model/ktddecv/placeOfIssue>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### place of loading
- **IRI:** <https://iri.suomi.fi/model/ktddecv/placeOfLoading>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### place of presentation
- **IRI:** <https://iri.suomi.fi/model/ktddecv/placeOfPresentation>
- **Description:**
  - The location at which a document, good, declaration, or other required item is formally presented to a designated party or authority.

In the context of a Documentary Credit, the location specified for the presentation of documents by the beneficiary to the nominated bank, confirming bank, or issuing bank for examination and payment.
- **Range:** <https://iri.suomi.fi/model/ktddecv/Location>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### place of receipt
- **IRI:** <https://iri.suomi.fi/model/ktddecv/placeOfReceipt>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### place of taking in charge
- **IRI:** <https://iri.suomi.fi/model/ktddecv/placeOfTakingInCharge>
- **Description:**
  - The location at which a carrier or other responsible party takes goods, consignments, or transport equipment into their charge for further carriage, handling, or responsibility in the transport chain.
- **Range:** <https://iri.suomi.fi/model/ktddecv/Location>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### preference criterion code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/preferenceCriterionCode>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### presentation base event
- **IRI:** <https://iri.suomi.fi/model/ktddecv/presentationBaseEvent>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### publisher
- **IRI:** <https://iri.suomi.fi/model/ktddecv/publisher>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### receiver party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/receiverParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### references letter of credit
- **IRI:** <https://iri.suomi.fi/model/ktddecv/referencesLetterOfCredit>
- **Range:** <https://iri.suomi.fi/model/ktddecv/DocumentaryCredit>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### references pre advice
- **IRI:** <https://iri.suomi.fi/model/ktddecv/referencesPreAdvice>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### reimbursing bank party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/reimbursingBankParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### related order
- **IRI:** <https://iri.suomi.fi/model/ktddecv/relatedOrder>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### relates to consignment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/relatesToConsignment>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### relates to goods item
- **IRI:** <https://iri.suomi.fi/model/ktddecv/relatesToGoodsItem>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### relates to invoice
- **IRI:** <https://iri.suomi.fi/model/ktddecv/relatesToInvoice>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### relates to package
- **IRI:** <https://iri.suomi.fi/model/ktddecv/relatesToPackage>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### relates to transport document
- **IRI:** <https://iri.suomi.fi/model/ktddecv/relatesToTransportDocument>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### reported by party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/reportedByParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### requested confirmation party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/requestedConfirmationParty>
- **Description:**
  - Party requested to add confirmation.
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### requested delivery period
- **IRI:** <https://iri.suomi.fi/model/ktddecv/requestedDeliveryPeriod>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### required document type
- **IRI:** <https://iri.suomi.fi/model/ktddecv/requiredDocumentType>
- **Range:** <http://www.w3.org/2004/02/skos/core#Concept>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### requires document
- **IRI:** <https://iri.suomi.fi/model/ktddecv/requiresDocument>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### seal identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/sealIdentifier>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### seller party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/sellerParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### sender party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/senderParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### shipper party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/shipperParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### sscc
- **IRI:** <https://iri.suomi.fi/model/ktddecv/sscc>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### statistical value amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/statisticalValueAmount>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### surety party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/suretyParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### tenor period
- **IRI:** <https://iri.suomi.fi/model/ktddecv/tenorPeriod>
- **Range:** <https://iri.suomi.fi/model/ktddecv/PeriodOfTime>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### to location
- **IRI:** <https://iri.suomi.fi/model/ktddecv/toLocation>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### total amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/totalAmount>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>
- **Equivalent to:** <https://vocabulary.uncefact.org/totalInvoiceAmount>

### total goods item quantity
- **IRI:** <https://iri.suomi.fi/model/ktddecv/totalGoodsItemQuantity>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### total gross weight
- **IRI:** <https://iri.suomi.fi/model/ktddecv/totalGrossWeight>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### total invoice amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/totalInvoiceAmount>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### total net weight
- **IRI:** <https://iri.suomi.fi/model/ktddecv/totalNetWeight>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### total package count
- **IRI:** <https://iri.suomi.fi/model/ktddecv/totalPackageCount>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### total package quantity
- **IRI:** <https://iri.suomi.fi/model/ktddecv/totalPackageQuantity>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### total transport handling unit quantity
- **IRI:** <https://iri.suomi.fi/model/ktddecv/totalTransportHandlingUnitQuantity>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### transit office
- **IRI:** <https://iri.suomi.fi/model/ktddecv/transitOffice>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### transport document type code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/transportDocumentTypeCode>
- **Range:** <http://www.w3.org/2004/02/skos/core#Concept>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### transport mode code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/transportModeCode>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### transshipment place
- **IRI:** <https://iri.suomi.fi/model/ktddecv/transshipmentPlace>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### uses transport equipment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/usesTransportEquipment>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### uses transport means
- **IRI:** <https://iri.suomi.fi/model/ktddecv/usesTransportMeans>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

### validity period
- **IRI:** <https://iri.suomi.fi/model/ktddecv/validityPeriod>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="datatype-properties"></a>
## Datatype Properties

### Actual Arrival Date Time
- **IRI:** <https://iri.suomi.fi/model/ktddecv/actualArrivalDateTime>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Actual Departure Date Time
- **IRI:** <https://iri.suomi.fi/model/ktddecv/actualDepartureDateTime>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Additional Conditions Text
- **IRI:** <https://iri.suomi.fi/model/ktddecv/additionalConditionsText>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Airport of Departure IATA Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/airportOfDepartureIATACode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Airport of Destination IATA Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/airportOfDestinationIATACode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Allowance Charge Reason Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/allowanceChargeReasonCode>
- **Description:**
  - Enumerated “charge reason” code list (e.g., ADVISE, CONFIRMATION, AMENDMENT, NEGOTIATION, DISCREPANCY, COURIER, SWIFT, HANDLING, OTHER).
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Alternate Name
- **IRI:** <https://iri.suomi.fi/model/ktddecv/alternateName>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Amount Percent Of Base
- **IRI:** <https://iri.suomi.fi/model/ktddecv/amountPercentOfBase>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Amount Tolerance Percent
- **IRI:** <https://iri.suomi.fi/model/ktddecv/amountTolerancePercent>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Amount Value
- **IRI:** <https://iri.suomi.fi/model/ktddecv/amountValue>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Arrival Date Time
- **IRI:** <https://iri.suomi.fi/model/ktddecv/arrivalDateTime>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Available At Locode
- **IRI:** <https://iri.suomi.fi/model/ktddecv/availableAtLocode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Available With By
- **IRI:** <https://iri.suomi.fi/model/ktddecv/availableWithBy>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Bank Account Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/bankAccountIdentifier>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Bond Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/bondNumber>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Border Crossing Point Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/borderCrossingPointCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Botanical Details
- **IRI:** <https://iri.suomi.fi/model/ktddecv/botanicalDetails>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Calculation Percent
- **IRI:** <https://iri.suomi.fi/model/ktddecv/calculationPercent>
- **Description:**
  - Percentage when the charge is calculated from a base amount.
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Charge Indicator
- **IRI:** <https://iri.suomi.fi/model/ktddecv/chargeIndicator>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Classification Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/classificationCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Commodity Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/commodityCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/commodityCode>

### Confirmation Added Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/confirmationAddedDate>
- **Description:**
  - Date on which confirmation became effective.
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Confirmation Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/confirmationDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Container Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/containerNumber>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Contract Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/contractIdentifier>
- **Range:** <http://www.w3.org/2001/XMLSchema#string>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Contract Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/contractNumber>
- **Range:** <http://www.w3.org/2001/XMLSchema#string>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Country Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/countryCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>
- **Equivalent to:** <https://gs1.org/voc/countryCode>

### Country Name
- **IRI:** <https://iri.suomi.fi/model/ktddecv/countryName>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Credit Amount Tolerance Percentage
- **IRI:** <https://iri.suomi.fi/model/ktddecv/creditAmountTolerancePercentage>
- **Description:**
  - A percentage tolerance applied to the stated credit amount, expressed as a decimal value (e.g. ±10). This indicates by how much drawings may exceed or fall short of the stated amount, without affecting the unit price of goods.
- **Range:** <http://www.w3.org/2001/XMLSchema#decimal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Credit Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/creditIdentifier>
- **Range:** <http://www.w3.org/2001/XMLSchema#string>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Currency Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/currencyCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/currencyCode>, <https://gs1.org/voc/priceCurrency>

### Customs Office Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/customsOfficeCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Declaration Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/declarationDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Deferred Payment Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/deferredPaymentDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Delivery Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/deliveryDate>
- **Range:** <http://www.w3.org/2001/XMLSchema#dateTime>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/actualDeliveryDate>

### Delivery Terms Text
- **IRI:** <https://iri.suomi.fi/model/ktddecv/deliveryTermsText>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Delivery Type Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/deliveryTypeCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Departure Date Time
- **IRI:** <https://iri.suomi.fi/model/ktddecv/departureDateTime>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Description
- **IRI:** <https://iri.suomi.fi/model/ktddecv/description>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Description of Goods Text
- **IRI:** <https://iri.suomi.fi/model/ktddecv/descriptionOfGoodsText>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <https://iri.suomi.fi/model/ktddecv/itemDescriptionText>

### Despatch Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/despatchDate>
- **Range:** <http://www.w3.org/2001/XMLSchema#dateTime>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Document Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/documentDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Document Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/documentIdentifier>
- **Range:** <http://www.w3.org/2001/XMLSchema#string>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Documentary Credit Type Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/documentaryCreditTypeCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Drafts At Locode
- **IRI:** <https://iri.suomi.fi/model/ktddecv/draftsAtLocode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Elevation Meters
- **IRI:** <https://iri.suomi.fi/model/ktddecv/elevationMeters>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### End Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/endDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### EORI Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/eORINumber>
- **Range:** <http://www.w3.org/2001/XMLSchema#string>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Estimated Time of Departure
- **IRI:** <https://iri.suomi.fi/model/ktddecv/estimatedTimeOfDeparture>
- **Range:** <http://www.w3.org/2001/XMLSchema#dateTime>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Event Date Time
- **IRI:** <https://iri.suomi.fi/model/ktddecv/eventDateTime>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Event Note Text
- **IRI:** <https://iri.suomi.fi/model/ktddecv/eventNoteText>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Excepted Quantity Indicator
- **IRI:** <https://iri.suomi.fi/model/ktddecv/exceptedQuantityIndicator>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Expiry Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/expiryDate>
- **Description:**
  - The last calendar date on which a complying presentation must be made at the place where the credit expires (i.e., with the bank with which the credit is available, or as otherwise specified in the credit). Express as a calendar date (not a period or free text).
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Expiry Place Name
- **IRI:** <https://iri.suomi.fi/model/ktddecv/expiryPlaceName>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Final Destination UN Locode
- **IRI:** <https://iri.suomi.fi/model/ktddecv/finalDestinationUNLocode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Flash Point Temperature
- **IRI:** <https://iri.suomi.fi/model/ktddecv/flashPointTemperature>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Flight Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/flightDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Flight Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/flightNumber>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Freight Payment Term Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/freightPaymentTermCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Geo WKT
- **IRI:** <https://iri.suomi.fi/model/ktddecv/geoWKT>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Handling Information
- **IRI:** <https://iri.suomi.fi/model/ktddecv/handlingInformation>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Hazard Class Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hazardClassCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Hazard Label Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hazardLabelCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Hazardous Risk Indicator
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hazardousRiskIndicator>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### House Air Waybill Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/houseAirWaybillNumber>
- **Description:**
  - The HAWB number identifying a consolidated shipment at house level, when applicable.
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### House Waybill Document Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/houseWaybillDocumentIdentifier>
- **Range:** <http://www.w3.org/2001/XMLSchema#string>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### HS Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hSCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### IATA Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/iataCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### ICAO Airport Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/icaoAirportCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### IMO Ship ID
- **IRI:** <https://iri.suomi.fi/model/ktddecv/iMOShipID>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Instruction Text
- **IRI:** <https://iri.suomi.fi/model/ktddecv/instructionText>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Insurance Policy Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/insurancePolicyNumber>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Insurance Terms Text
- **IRI:** <https://iri.suomi.fi/model/ktddecv/insuranceTermsText>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Invoice Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/invoiceDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Invoice Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/invoiceNumber>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Issue Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/issueDate>
- **Range:** <http://www.w3.org/2001/XMLSchema#dateTime>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/issueDate>

### Issuing Authority
- **IRI:** <https://iri.suomi.fi/model/ktddecv/issuingAuthority>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Item Description Text
- **IRI:** <https://iri.suomi.fi/model/ktddecv/itemDescriptionText>
- **Description:**
  - Narrative description of the goods/services at item level, usable across all trade documents.
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Latest Presentation Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/latestPresentationDate>
- **Description:**
  - Last date on which presentation is permitted under the credit.
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Latest Shipment Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/latestShipmentDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Latitude
- **IRI:** <https://iri.suomi.fi/model/ktddecv/latitude>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Limited Quantity Indicator
- **IRI:** <https://iri.suomi.fi/model/ktddecv/limitedQuantityIndicator>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Location ID
- **IRI:** <https://iri.suomi.fi/model/ktddecv/locationID>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Location Name
- **IRI:** <https://iri.suomi.fi/model/ktddecv/locationName>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Longitude
- **IRI:** <https://iri.suomi.fi/model/ktddecv/longitude>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Marine Pollutant Indicator
- **IRI:** <https://iri.suomi.fi/model/ktddecv/marinePollutantIndicator>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Marks and Numbers Text
- **IRI:** <https://iri.suomi.fi/model/ktddecv/marksAndNumbersText>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Master Air Waybill Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/masterAirWaybillNumber>
- **Description:**
  - The MAWB number identifying the air consignment at master level (e.g., &#x27;123-45678901&#x27;).
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Maturity Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/maturityDate>
- **Description:**
  - The actual deferred payment due date, when determinable.
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Message Subject
- **IRI:** <https://iri.suomi.fi/model/ktddecv/messageSubject>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Message Text
- **IRI:** <https://iri.suomi.fi/model/ktddecv/messageText>
- **Description:**
  - Unstructured content of the message (language-tagged).
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Message To Receiver Text
- **IRI:** <https://iri.suomi.fi/model/ktddecv/messageToReceiverText>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### MRN
- **IRI:** <https://iri.suomi.fi/model/ktddecv/mrn>
- **Description:**
  - The Movement Reference Number (MRN) uniquely identifying the Transit Accompanying Document.
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Multiplier Factor Percent
- **IRI:** <https://iri.suomi.fi/model/ktddecv/multiplierFactorPercent>
- **Description:**
  - A percentage rate used to compute an additional or reduced monetary amount from a specified base amount. The calculated amount equals the base amount multiplied by this percentage divided by 100.
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Name
- **IRI:** <https://iri.suomi.fi/model/ktddecv/name>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/name>

### Negotiable Indicator
- **IRI:** <https://iri.suomi.fi/model/ktddecv/negotiableIndicator>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Note Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/noteNumber>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Number of Copies
- **IRI:** <https://iri.suomi.fi/model/ktddecv/numberOfCopies>
- **Range:** <http://www.w3.org/2001/XMLSchema#integer>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Number of Originals
- **IRI:** <https://iri.suomi.fi/model/ktddecv/numberOfOriginals>
- **Range:** <http://www.w3.org/2001/XMLSchema#integer>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### On Board Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/onBoardDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Order Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/orderDate>
- **Range:** <http://www.w3.org/2001/XMLSchema#dateTime>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Order Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/orderIdentifier>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Origin Establishment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/originEstablishment>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Package Count
- **IRI:** <https://iri.suomi.fi/model/ktddecv/packageCount>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Package Length
- **IRI:** <https://iri.suomi.fi/model/ktddecv/packageLength>
- **Range:** <http://www.w3.org/2001/XMLSchema#decimal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/loadingLengthMeasure>

### Packing Group Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/packingGroupCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Packing Instruction Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/packingInstructionCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Partial Shipment Allowed
- **IRI:** <https://iri.suomi.fi/model/ktddecv/partialShipmentAllowed>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Payment Due Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/paymentDueDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/paymentDueDate>

### Payment Method
- **IRI:** <https://iri.suomi.fi/model/ktddecv/paymentMethod>
- **Range:** <http://www.w3.org/2001/XMLSchema#string>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/paymentMeansCode>

### Payment Term Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/paymentTermCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Place of Delivery UN Locode
- **IRI:** <https://iri.suomi.fi/model/ktddecv/placeOfDeliveryUNLocode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Place of Receipt UN Locode
- **IRI:** <https://iri.suomi.fi/model/ktddecv/placeOfReceiptUNLocode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Planned Arrival Date Time
- **IRI:** <https://iri.suomi.fi/model/ktddecv/plannedArrivalDateTime>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Planned Departure Date Time
- **IRI:** <https://iri.suomi.fi/model/ktddecv/plannedDepartureDateTime>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Port Facility Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/portFacilityCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Port Of Discharge UN Locode
- **IRI:** <https://iri.suomi.fi/model/ktddecv/portOfDischargeUNLocode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Port of Loading UN Locode
- **IRI:** <https://iri.suomi.fi/model/ktddecv/portOfLoadingUNLocode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Post Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/postCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Presentation Period Days
- **IRI:** <https://iri.suomi.fi/model/ktddecv/presentationPeriodDays>
- **Description:**
  - Number of calendar days after the shipment date within which presentation must be made (SWIFT MT700 :48 is expressed as days).
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Product Description
- **IRI:** <https://iri.suomi.fi/model/ktddecv/productDescription>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Product Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/productIdentifier>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Product Name
- **IRI:** <https://iri.suomi.fi/model/ktddecv/productName>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Proper Shipping Name
- **IRI:** <https://iri.suomi.fi/model/ktddecv/properShippingName>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Publication Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/publicationDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Purchase Order Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/purchaseOrderNumber>
- **Range:** <http://www.w3.org/2001/XMLSchema#string>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Quantity Value
- **IRI:** <https://iri.suomi.fi/model/ktddecv/quantityValue>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Rail Station Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/railStationCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Rail Wagon Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/railWagonIdentifier>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Rule Set Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/ruleSetIdentifier>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Sea Waybill Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/seaWaybillNumber>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Sealed Indicator
- **IRI:** <https://iri.suomi.fi/model/ktddecv/sealedIndicator>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Shipment Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/shipmentIdentifier>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Shipping Marks
- **IRI:** <https://iri.suomi.fi/model/ktddecv/shippingMarks>
- **Range:** <http://www.w3.org/2001/XMLSchema#string>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/shippingMarks>

### Ships Delivery Order Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/shipsDeliveryOrderNumber>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Special Provision Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/specialProvisionCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Start Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/startDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Subsidiary Hazard Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/subsidiaryHazardCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Technical Name
- **IRI:** <https://iri.suomi.fi/model/ktddecv/technicalName>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Terminal Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/terminalCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Time Zone
- **IRI:** <https://iri.suomi.fi/model/ktddecv/timeZone>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Title
- **IRI:** <https://iri.suomi.fi/model/ktddecv/title>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Total Collect Charges
- **IRI:** <https://iri.suomi.fi/model/ktddecv/totalCollectCharges>
- **Range:** <http://www.w3.org/2001/XMLSchema#decimal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Trailer Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/trailerIdentifier>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Transport Document Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/transportDocumentNumber>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Transport Temperature
- **IRI:** <https://iri.suomi.fi/model/ktddecv/transportTemperature>
- **Range:** <http://www.w3.org/2001/XMLSchema#decimal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Transshipment Allowed
- **IRI:** <https://iri.suomi.fi/model/ktddecv/transshipmentAllowed>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### UIC Station Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/uicStationCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### UN Locode
- **IRI:** <https://iri.suomi.fi/model/ktddecv/unlocode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### UN Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/unNumber>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Unit Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/unitCode>
- **Description:**
  - Unit of measure for non-monetary amounts (UCUM or UN/ECE Rec 20). Not used for money.
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Unit Price
- **IRI:** <https://iri.suomi.fi/model/ktddecv/unitPrice>
- **Range:** <http://www.w3.org/2001/XMLSchema#float>
- **Subproperty of:** <https://gs1.org/voc/price>

### Value
- **IRI:** <https://iri.suomi.fi/model/ktddecv/value>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/value>

### Vehicle Name
- **IRI:** <https://iri.suomi.fi/model/ktddecv/vehicleName>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Vehicle Registration Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/vehicleRegistrationIdentifier>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Version Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/versionIdentifier>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Vessel Name
- **IRI:** <https://iri.suomi.fi/model/ktddecv/vesselName>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Voyage Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/voyageNumber>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

### Warehouse GLN
- **IRI:** <https://iri.suomi.fi/model/ktddecv/warehouseGLN>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

## Unlinked Properties
Properties without an explicit rdfs:domain (even if referenced via class restrictions).

### Object Properties (no declared domain)
- **additional amounts covered** (<https://iri.suomi.fi/model/ktddecv/additionalAmountsCovered>)
- **advise through bank party** (<https://iri.suomi.fi/model/ktddecv/adviseThroughBankParty>)
- **advising bank party** (<https://iri.suomi.fi/model/ktddecv/advisingBankParty>) — Association from a documentary credit (letter of credit) to the bank that advises the credit (and any amendments) to the beneficiary.
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
- **carrier party** (<https://iri.suomi.fi/model/ktddecv/carrierParty>) — For Sea Waybill: The ocean carrier issuing or responsible for the carriage.
- **certificate number** (<https://iri.suomi.fi/model/ktddecv/certificateNumber>)
- **chargeable weight** (<https://iri.suomi.fi/model/ktddecv/chargeableWeight>)
- **charged by party** (<https://iri.suomi.fi/model/ktddecv/chargedByParty>)
- **charged to party** (<https://iri.suomi.fi/model/ktddecv/chargedToParty>)
- **claims payable at place** (<https://iri.suomi.fi/model/ktddecv/claimsPayableAtPlace>)
- **confirmation instruction code** (<https://iri.suomi.fi/model/ktddecv/confirmationInstructionCode>) — Range: <http://www.w3.org/2004/02/skos/core#Concept> — Code indicating whether confirmation is requested, may be added, or is without confirmation.
- **confirming bank party** (<https://iri.suomi.fi/model/ktddecv/confirmingBankParty>)
- **confirming party** (<https://iri.suomi.fi/model/ktddecv/confirmingParty>) — Party that actually added confirmation.
- **consignee party** (<https://iri.suomi.fi/model/ktddecv/consigneeParty>) — The party to whom the goods are to be delivered.
- **consignment identifier** (<https://iri.suomi.fi/model/ktddecv/consignmentIdentifier>)
- **consignor party** (<https://iri.suomi.fi/model/ktddecv/consignorParty>)
- **country of origin code** (<https://iri.suomi.fi/model/ktddecv/countryOfOriginCode>) — Range: <http://www.w3.org/2004/02/skos/core#Concept> — Country of non-preferential or preferential origin for the goods line, as an ISO 3166-1 code concept.
- **coverage amount** (<https://iri.suomi.fi/model/ktddecv/coverageAmount>)
- **coverage type code** (<https://iri.suomi.fi/model/ktddecv/coverageTypeCode>)
- **covered shipment** (<https://iri.suomi.fi/model/ktddecv/coveredShipment>)
- **covers additional charge** (<https://iri.suomi.fi/model/ktddecv/coversAdditionalCharge>)
- **covers contract** (<https://iri.suomi.fi/model/ktddecv/coversContract>)
- **creditor specified financial institution** (<https://iri.suomi.fi/model/ktddecv/creditorSpecifiedFinancialInstitution>)
- **customs procedure code** (<https://iri.suomi.fi/model/ktddecv/customsProcedureCode>)
- **declarant party** (<https://iri.suomi.fi/model/ktddecv/declarantParty>)
- **declaration number** (<https://iri.suomi.fi/model/ktddecv/declarationNumber>) — National MRN or declaration number as Identifier node.
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
- **drawee party** (<https://iri.suomi.fi/model/ktddecv/draweeParty>) — Party on whom a demand for payment is drawn and who is ordered to pay (e.g., in a bill of exchange/draft/cheque).
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
- **has commodity classification** (<https://iri.suomi.fi/model/ktddecv/hasCommodityClassification>) — Associates an item line with a commodity/service classification entry.
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
- **maximum credit amount** (<https://iri.suomi.fi/model/ktddecv/maximumCreditAmount>) — An instruction on a Documentary Credit that the stated credit amount is an absolute ceiling: the total of drawings/claims under the credit must not exceed the stated amount. It is used to cap drawings even where tolerances or qualifying words (e.g., “about/approximately”) might otherwise allow variation.
- **net quantity per package** (<https://iri.suomi.fi/model/ktddecv/netQuantityPerPackage>)
- **nominated bank party** (<https://iri.suomi.fi/model/ktddecv/nominatedBankParty>)
- **notify party** (<https://iri.suomi.fi/model/ktddecv/notifyParty>)
- **obligee party** (<https://iri.suomi.fi/model/ktddecv/obligeeParty>) — Party entitled to receive the performance of an obligation (a payment, delivery, or service).
- **obligor party** (<https://iri.suomi.fi/model/ktddecv/obligorParty>) — Party that bears a duty to perform an obligation (e.g., pay money, deliver goods, perform a service) under a business commitment.
- **observed transport means** (<https://iri.suomi.fi/model/ktddecv/observedTransportMeans>)
- **office of departure** (<https://iri.suomi.fi/model/ktddecv/officeOfDeparture>) — The customs office of departure where the transit procedure begins.
- **office of destination** (<https://iri.suomi.fi/model/ktddecv/officeOfDestination>)
- **order amount** (<https://iri.suomi.fi/model/ktddecv/orderAmount>)
- **origin country** (<https://iri.suomi.fi/model/ktddecv/originCountry>)
- **other charges amount** (<https://iri.suomi.fi/model/ktddecv/otherChargesAmount>)
- **package type code** (<https://iri.suomi.fi/model/ktddecv/packageTypeCode>)
- **packing list number** (<https://iri.suomi.fi/model/ktddecv/packingListNumber>)
- **party address** (<https://iri.suomi.fi/model/ktddecv/partyAddress>)
- **party identifier** (<https://iri.suomi.fi/model/ktddecv/partyIdentifier>)
- **party legal entity** (<https://iri.suomi.fi/model/ktddecv/partyLegalEntity>)
- **payee party** (<https://iri.suomi.fi/model/ktddecv/payeeParty>) — Party to whom a payment is to be made under an obligation or instrument.
- **payer party** (<https://iri.suomi.fi/model/ktddecv/payerParty>)
- **payment location** (<https://iri.suomi.fi/model/ktddecv/paymentLocation>)
- **payment settlement method** (<https://iri.suomi.fi/model/ktddecv/paymentSettlementMethod>)
- **per unit amount** (<https://iri.suomi.fi/model/ktddecv/perUnitAmount>)
- **place of delivery** (<https://iri.suomi.fi/model/ktddecv/placeOfDelivery>)
- **place of discharge** (<https://iri.suomi.fi/model/ktddecv/placeOfDischarge>) — The location where goods are taken off a means of transport.
- **place of expiry** (<https://iri.suomi.fi/model/ktddecv/placeOfExpiry>) — The place of presentation for the credit (typically “at the counters of … [named bank/branch/location]”). In eUCP contexts, the “place” may be physical (bank/location) and/or an electronic address/system designated for presentation.
- **place of issue** (<https://iri.suomi.fi/model/ktddecv/placeOfIssue>)
- **place of loading** (<https://iri.suomi.fi/model/ktddecv/placeOfLoading>)
- **place of presentation** (<https://iri.suomi.fi/model/ktddecv/placeOfPresentation>) — Range: <https://iri.suomi.fi/model/ktddecv/Location> — The location at which a document, good, declaration, or other required item is formally presented to a designated party or authority.

In the context of a Documentary Credit, the location specified for the presentation of documents by the beneficiary to the nominated bank, confirming bank, or issuing bank for examination and payment.
- **place of receipt** (<https://iri.suomi.fi/model/ktddecv/placeOfReceipt>)
- **place of taking in charge** (<https://iri.suomi.fi/model/ktddecv/placeOfTakingInCharge>) — Range: <https://iri.suomi.fi/model/ktddecv/Location> — The location at which a carrier or other responsible party takes goods, consignments, or transport equipment into their charge for further carriage, handling, or responsibility in the transport chain.
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
- **requested confirmation party** (<https://iri.suomi.fi/model/ktddecv/requestedConfirmationParty>) — Party requested to add confirmation.
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
- **Allowance Charge Reason Code** (<https://iri.suomi.fi/model/ktddecv/allowanceChargeReasonCode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal> — Enumerated “charge reason” code list (e.g., ADVISE, CONFIRMATION, AMENDMENT, NEGOTIATION, DISCREPANCY, COURIER, SWIFT, HANDLING, OTHER).
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
- **Calculation Percent** (<https://iri.suomi.fi/model/ktddecv/calculationPercent>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal> — Percentage when the charge is calculated from a base amount.
- **Charge Indicator** (<https://iri.suomi.fi/model/ktddecv/chargeIndicator>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Classification Code** (<https://iri.suomi.fi/model/ktddecv/classificationCode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Commodity Code** (<https://iri.suomi.fi/model/ktddecv/commodityCode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Confirmation Added Date** (<https://iri.suomi.fi/model/ktddecv/confirmationAddedDate>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal> — Date on which confirmation became effective.
- **Confirmation Date** (<https://iri.suomi.fi/model/ktddecv/confirmationDate>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Container Number** (<https://iri.suomi.fi/model/ktddecv/containerNumber>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Contract Identifier** (<https://iri.suomi.fi/model/ktddecv/contractIdentifier>) — Range: <http://www.w3.org/2001/XMLSchema#string>
- **Contract Number** (<https://iri.suomi.fi/model/ktddecv/contractNumber>) — Range: <http://www.w3.org/2001/XMLSchema#string>
- **Country Code** (<https://iri.suomi.fi/model/ktddecv/countryCode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Country Name** (<https://iri.suomi.fi/model/ktddecv/countryName>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Credit Amount Tolerance Percentage** (<https://iri.suomi.fi/model/ktddecv/creditAmountTolerancePercentage>) — Range: <http://www.w3.org/2001/XMLSchema#decimal> — A percentage tolerance applied to the stated credit amount, expressed as a decimal value (e.g. ±10). This indicates by how much drawings may exceed or fall short of the stated amount, without affecting the unit price of goods.
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
- **Expiry Date** (<https://iri.suomi.fi/model/ktddecv/expiryDate>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal> — The last calendar date on which a complying presentation must be made at the place where the credit expires (i.e., with the bank with which the credit is available, or as otherwise specified in the credit). Express as a calendar date (not a period or free text).
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
- **House Air Waybill Number** (<https://iri.suomi.fi/model/ktddecv/houseAirWaybillNumber>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal> — The HAWB number identifying a consolidated shipment at house level, when applicable.
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
- **Item Description Text** (<https://iri.suomi.fi/model/ktddecv/itemDescriptionText>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal> — Narrative description of the goods/services at item level, usable across all trade documents.
- **Latest Presentation Date** (<https://iri.suomi.fi/model/ktddecv/latestPresentationDate>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal> — Last date on which presentation is permitted under the credit.
- **Latest Shipment Date** (<https://iri.suomi.fi/model/ktddecv/latestShipmentDate>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Latitude** (<https://iri.suomi.fi/model/ktddecv/latitude>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Limited Quantity Indicator** (<https://iri.suomi.fi/model/ktddecv/limitedQuantityIndicator>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Location ID** (<https://iri.suomi.fi/model/ktddecv/locationID>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Location Name** (<https://iri.suomi.fi/model/ktddecv/locationName>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Longitude** (<https://iri.suomi.fi/model/ktddecv/longitude>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Marine Pollutant Indicator** (<https://iri.suomi.fi/model/ktddecv/marinePollutantIndicator>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Marks and Numbers Text** (<https://iri.suomi.fi/model/ktddecv/marksAndNumbersText>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Master Air Waybill Number** (<https://iri.suomi.fi/model/ktddecv/masterAirWaybillNumber>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal> — The MAWB number identifying the air consignment at master level (e.g., &#x27;123-45678901&#x27;).
- **Maturity Date** (<https://iri.suomi.fi/model/ktddecv/maturityDate>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal> — The actual deferred payment due date, when determinable.
- **Message Subject** (<https://iri.suomi.fi/model/ktddecv/messageSubject>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Message Text** (<https://iri.suomi.fi/model/ktddecv/messageText>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal> — Unstructured content of the message (language-tagged).
- **Message To Receiver Text** (<https://iri.suomi.fi/model/ktddecv/messageToReceiverText>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **MRN** (<https://iri.suomi.fi/model/ktddecv/mrn>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal> — The Movement Reference Number (MRN) uniquely identifying the Transit Accompanying Document.
- **Multiplier Factor Percent** (<https://iri.suomi.fi/model/ktddecv/multiplierFactorPercent>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal> — A percentage rate used to compute an additional or reduced monetary amount from a specified base amount. The calculated amount equals the base amount multiplied by this percentage divided by 100.
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
- **Package Length** (<https://iri.suomi.fi/model/ktddecv/packageLength>) — Range: <http://www.w3.org/2001/XMLSchema#decimal>
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
- **Presentation Period Days** (<https://iri.suomi.fi/model/ktddecv/presentationPeriodDays>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal> — Number of calendar days after the shipment date within which presentation must be made (SWIFT MT700 :48 is expressed as days).
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
- **Unit Code** (<https://iri.suomi.fi/model/ktddecv/unitCode>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal> — Unit of measure for non-monetary amounts (UCUM or UN/ECE Rec 20). Not used for money.
- **Unit Price** (<https://iri.suomi.fi/model/ktddecv/unitPrice>) — Range: <http://www.w3.org/2001/XMLSchema#float>
- **Value** (<https://iri.suomi.fi/model/ktddecv/value>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Vehicle Name** (<https://iri.suomi.fi/model/ktddecv/vehicleName>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Vehicle Registration Identifier** (<https://iri.suomi.fi/model/ktddecv/vehicleRegistrationIdentifier>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Version Identifier** (<https://iri.suomi.fi/model/ktddecv/versionIdentifier>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Vessel Name** (<https://iri.suomi.fi/model/ktddecv/vesselName>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Voyage Number** (<https://iri.suomi.fi/model/ktddecv/voyageNumber>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Warehouse GLN** (<https://iri.suomi.fi/model/ktddecv/warehouseGLN>) — Range: <http://www.w3.org/2000/01/rdf-schema#Literal>