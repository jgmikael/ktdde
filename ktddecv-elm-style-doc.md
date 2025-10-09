# KTDDE Core Vocabulary — Documentation

## Overview

- **Ontology IRI:** <https://iri.suomi.fi/model/ktddecv/>
- **Created:** 2024-11-04T12:43:11.269000+00:00
- **Modified:** 2025-09-16T06:48:54.019000+00:00

An OWL Ontology (Vocabulary if you wish) based on the KTDDE Data Elements, mapped to UBL, UN/CEFACT BSP and the GS1 Web Vocabulary (where possible &amp; applicable).

- **See also:** <Nd0845e3012644c5f9d8cdd4fae0bfef8>

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

<a id="additional-amount-category"></a>
### Additional Amount Category
- **IRI:** <https://iri.suomi.fi/model/ktddecv/AdditionalAmountCategory>
- **Subclass of:** [Concept](#concept)

<a id="address"></a>
### Address
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Address>
- **Subclass of:** [Thing](#thing)
- **Equivalent to:** <https://vocabulary.uncefact.org/TradeAddress>, <https://gs1.org/voc/PostalAddress>, <https://iri.suomi.fi/model/busdoc/1.0.2/Address>

<a id="advance-ruling-application"></a>
### Advance Ruling Application
- **IRI:** <https://iri.suomi.fi/model/ktddecv/AdvanceRulingApplication>
- **Subclass of:** [Thing](#thing)

<a id="air-cargo-manifest"></a>
### Air Cargo Manifest
- **IRI:** <https://iri.suomi.fi/model/ktddecv/AirCargoManifest>
- **Subclass of:** [Thing](#thing)

<a id="air-waybill"></a>
### Air Waybill
- **IRI:** <https://iri.suomi.fi/model/ktddecv/AirWaybill>
- **Description:** The air transport contract document for carriage of goods by air. May be a master (MAWB) or house (HAWB) waybill; identifies the shipment, parties, flight/route and charges.
- **Subclass of:** [Transport Document](#transport-document)

<a id="allowance-charge"></a>
### Allowance Charge
- **IRI:** <https://iri.suomi.fi/model/ktddecv/AllowanceCharge>
- **Subclass of:** [Thing](#thing)

<a id="amount"></a>
### Amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Amount>
- **Subclass of:** [Thing](#thing)

<a id="ata-carnet"></a>
### ATA Carnet
- **IRI:** <https://iri.suomi.fi/model/ktddecv/ATACarnet>
- **Subclass of:** [Thing](#thing)

<a id="availability-method"></a>
### Availability Method
- **IRI:** <https://iri.suomi.fi/model/ktddecv/AvailabilityMethod>
- **Subclass of:** [Concept](#concept)

<a id="availability-qualifier"></a>
### Availability Qualifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/AvailabilityQualifier>
- **Subclass of:** [Concept](#concept)

<a id="bank"></a>
### Bank
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Bank>
- **Subclass of:** [Thing](#thing)
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/FinancialInstitution>

<a id="bank-account"></a>
### Bank Account
- **IRI:** <https://iri.suomi.fi/model/ktddecv/BankAccount>
- **Subclass of:** [Thing](#thing)

<a id="bank-instruction"></a>
### Bank Instruction
- **IRI:** <https://iri.suomi.fi/model/ktddecv/BankInstruction>
- **Description:** An instruction directed to a bank in the context of trade finance (e.g., documentary credit).
- **Subclass of:** [Instruction](#instruction)

<a id="bill-of-exchange"></a>
### Bill of Exchange
- **IRI:** <https://iri.suomi.fi/model/ktddecv/BillOfExchange>
- **Subclass of:** [Thing](#thing)

<a id="bill-of-lading"></a>
### Bill of Lading
- **IRI:** <https://iri.suomi.fi/model/ktddecv/BillOfLading>
- **Subclass of:** [Thing](#thing)

<a id="business-document"></a>
### Business Document
- **IRI:** <https://iri.suomi.fi/model/ktddecv/BusinessDocument>
- **Description:** An information artifact exchanged in trade, transport, customs, finance, or insurance processes.
- **Subclass of:** [Communication Entity](#communication-entity)

<a id="business-event"></a>
### Business Event
- **IRI:** <https://iri.suomi.fi/model/ktddecv/BusinessEvent>
- **Subclass of:** [Thing](#thing)

<a id="certificate-of-origin"></a>
### Certificate of Origin
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CertificateOfOrigin>
- **Subclass of:** [Thing](#thing)

<a id="characteristic"></a>
### Characteristic
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Characteristic>
- **Subclass of:** [Thing](#thing)
- **Equivalent to:** <https://vocabulary.uncefact.org/ProductCharacteristic>

<a id="cites-permit"></a>
### CITES Permit
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CITESPermit>
- **Subclass of:** [Thing](#thing)

<a id="classification-scheme"></a>
### Classification Scheme
- **IRI:** <https://iri.suomi.fi/model/ktddecv/ClassificationScheme>
- **Subclass of:** [Concept](#concept)

<a id="codex-official-certificate"></a>
### CODEX Official Certificate
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CODEXOfficialCertificate>
- **Subclass of:** [Thing](#thing)

<a id="commercial-invoice"></a>
### Commercial Invoice
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CommercialInvoice>
- **Subclass of:** [Thing](#thing)

<a id="commodity-classification"></a>
### Commodity Classification
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CommodityClassification>
- **Subclass of:** [Thing](#thing)
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/CommodityClassification>

<a id="communication-entity"></a>
### Communication Entity
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CommunicationEntity>
- **Description:** Thing that can carry sender/receiver party context (e.g., a BusinessDocument or a Message).
- **Subclass of:** [Thing](#thing)

<a id="consignment"></a>
### Consignment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Consignment>
- **Description:** The grouping of goods for transport, under a single transport contract, from a consignor to a consignee.
- **Subclass of:** [Thing](#thing)
- **Equivalent to:** <https://vocabulary.uncefact.org/Consignment>, <https://iri.suomi.fi/model/busdoc/1.0.2/Consignment>

<a id="consignment-security-declaration"></a>
### Consignment Security Declaration
- **IRI:** <https://iri.suomi.fi/model/ktddecv/ConsignmentSecurityDeclaration>
- **Subclass of:** [Thing](#thing)

<a id="contract"></a>
### Contract
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Contract>
- **Subclass of:** [Thing](#thing)

<a id="country"></a>
### Country
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Country>
- **Subclass of:** [Thing](#thing)
- **Equivalent to:** <https://gs1.org/voc/Country>, <https://vocabulary.uncefact.org/Country>, <https://iri.suomi.fi/model/busdoc/1.0.2/Country>

<a id="credit-availability"></a>
### Credit Availability
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CreditAvailability>
- **Description:** A structured statement of where (party/place) and how (method/conditions) a documentary credit is available.
- **Subclass of:** [Thing](#thing)

<a id="customs-bond"></a>
### Customs Bond
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CustomsBond>
- **Subclass of:** [Thing](#thing)

<a id="customs-declaration"></a>
### Customs Declaration
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CustomsDeclaration>
- **Description:** Summary declaration for export/import; links declared goods lines, values and duties/taxes.
- **Subclass of:** [Thing](#thing)

<a id="dangerous-goods"></a>
### Dangerous Goods
- **IRI:** <https://iri.suomi.fi/model/ktddecv/DangerousGoods>
- **Subclass of:** [Thing](#thing)
- **Equivalent to:** <https://vocabulary.uncefact.org/DangerousGoods>, <https://iri.suomi.fi/model/busdoc/1.0.2/HazardousGoodsTransit>

<a id="dangerous-goods-declaration"></a>
### Dangerous Goods Declaration
- **IRI:** <https://iri.suomi.fi/model/ktddecv/DangerousGoodsDeclaration>
- **Subclass of:** [Thing](#thing)

<a id="delivery"></a>
### Delivery
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Delivery>
- **Subclass of:** [Thing](#thing)

<a id="delivery-milestone"></a>
### Delivery Milestone
- **IRI:** <https://iri.suomi.fi/model/ktddecv/DeliveryMilestone>
- **Subclass of:** [Thing](#thing)

<a id="document"></a>
### Document
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Document>
- **Subclass of:** [Thing](#thing)
- **Equivalent to:** <https://vocabulary.uncefact.org/Document>

<a id="document-requirement"></a>
### Document Requirement
- **IRI:** <https://iri.suomi.fi/model/ktddecv/DocumentRequirement>
- **Subclass of:** [Thing](#thing)

<a id="documentary-credit"></a>
### Documentary Credit
- **IRI:** <https://iri.suomi.fi/model/ktddecv/DocumentaryCredit>
- **Subclass of:** [LegalConstruct](#legalconstruct), [InformationObject](#informationobject)

<a id="dutytaxfee"></a>
### Duty/Tax/Fee
- **IRI:** <https://iri.suomi.fi/model/ktddecv/DutyTaxFee>
- **Description:** Breakdown element for customs duties, taxes, or fees with basis and computed amount.
- **Subclass of:** [Thing](#thing)

<a id="emcs-document"></a>
### EMCS Document
- **IRI:** <https://iri.suomi.fi/model/ktddecv/EMCSDocument>
- **Subclass of:** [Thing](#thing)

<a id="excise-guarantee"></a>
### Excise Guarantee
- **IRI:** <https://iri.suomi.fi/model/ktddecv/ExciseGuarantee>
- **Subclass of:** [Thing](#thing)

<a id="export-import-license"></a>
### Export Import License
- **IRI:** <https://iri.suomi.fi/model/ktddecv/ExportImportLicense>
- **Subclass of:** [Thing](#thing)

<a id="financial-document"></a>
### Financial Document
- **IRI:** <https://iri.suomi.fi/model/ktddecv/FinancialDocument>
- **Subclass of:** [Thing](#thing)

<a id="goods-item"></a>
### Goods Item
- **IRI:** <https://iri.suomi.fi/model/ktddecv/GoodsItem>
- **Description:** Use only for logistics/consignment context: physical goods as packed/shipped (quantities, weights, marks &amp; numbers, packaging, DG info, etc.).
- **Subclass of:** [Thing](#thing)
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/GoodsItem>

<a id="identifier"></a>
### Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Identifier>
- **Description:** subclass of adms:Identifier
- **Subclass of:** [Identifier](#identifier)

<a id="instruction"></a>
### Instruction
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Instruction>
- **Description:** A directive expressed in a message context, issued by one party to another.

or

A message conveying directives or requests from sender to receiver.
- **Subclass of:** [Message](#message)

<a id="insurance-certificate"></a>
### Insurance Certificate
- **IRI:** <https://iri.suomi.fi/model/ktddecv/InsuranceCertificate>
- **Subclass of:** [Thing](#thing)

<a id="invoice-line"></a>
### Invoice Line
- **IRI:** <https://iri.suomi.fi/model/ktddecv/InvoiceLine>
- **Subclass of:** [Trade Line Item](#trade-line-item)
- **Equivalent to:** <https://vocabulary.uncefact.org/LineTradeSettlement>, <https://iri.suomi.fi/model/busdoc/1.0.2/InvoiceLine>

<a id="legal-entity"></a>
### Legal Entity
- **IRI:** <https://iri.suomi.fi/model/ktddecv/LegalEntity>
- **Subclass of:** [Thing](#thing)

<a id="location"></a>
### Location
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Location>
- **Subclass of:** [Place](#place)
- **Equivalent to:** <https://vocabulary.uncefact.org/Location>, <https://iri.suomi.fi/model/busdoc/1.0.2/Location>

<a id="message"></a>
### Message
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Message>
- **Description:** A sender-to-receiver communication related to a business document, which may carry unstructured text and/or structured qualifiers.
- **Subclass of:** [Communication Entity](#communication-entity)

<a id="monetary-amount"></a>
### Monetary Amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
- **Subclass of:** [Amount](#amount)

<a id="organic-inspection-certificate"></a>
### Organic Inspection Certificate
- **IRI:** <https://iri.suomi.fi/model/ktddecv/OrganicInspectionCertificate>
- **Subclass of:** [Thing](#thing)

<a id="package"></a>
### Package
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Package>
- **Subclass of:** [Thing](#thing)

<a id="package-item"></a>
### Package Item
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PackageItem>
- **Description:** A content record inside a package referencing a GoodsItem and the quantity/attributes of that portion.
- **Subclass of:** [Thing](#thing)

<a id="packing-list"></a>
### Packing List
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PackingList>
- **Subclass of:** [Thing](#thing)

<a id="party"></a>
### Party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Party>
- **Subclass of:** [Actor](#actor)
- **Equivalent to:** <https://vocabulary.uncefact.org/TradeParty>, <https://iri.suomi.fi/model/busdoc/1.0.2/Party>

<a id="payment-confirmation"></a>
### Payment Confirmation
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PaymentConfirmation>
- **Subclass of:** [Thing](#thing)

<a id="payment-line"></a>
### Payment Line
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PaymentLine>
- **Description:** One tranche/portion of payment under a mixed-payment documentary credit.
- **Subclass of:** [Thing](#thing)

<a id="payment-schedule-line"></a>
### Payment Schedule Line
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PaymentScheduleLine>
- **Subclass of:** [Thing](#thing)

<a id="payment-terms"></a>
### Payment Terms
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PaymentTerms>
- **Subclass of:** [Thing](#thing)
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/PaymentTerms>, <https://vocabulary.uncefact.org/PaymentTerms>

<a id="period-of-time"></a>
### Period of Time
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PeriodOfTime>
- **Subclass of:** [Thing](#thing)

<a id="phytosanitary-certificate"></a>
### Phytosanitary Certificate
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PhytosanitaryCertificate>
- **Subclass of:** [Thing](#thing)

<a id="postal-address"></a>
### Postal Address
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PostalAddress>
- **Subclass of:** [Thing](#thing)

<a id="presentation"></a>
### Presentation
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Presentation>
- **Subclass of:** [Thing](#thing)

<a id="promissory-note"></a>
### Promissory Note
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PromissoryNote>
- **Subclass of:** [Thing](#thing)

<a id="purchase-order"></a>
### Purchase Order
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PurchaseOrder>
- **Subclass of:** [Thing](#thing)

<a id="purchase-order-line"></a>
### Purchase Order Line
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PurchaseOrderLine>
- **Subclass of:** [Trade Line Item](#trade-line-item)

<a id="quantity"></a>
### Quantity  
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Quantity>
- **Subclass of:** [Thing](#thing)
- **Equivalent to:** <https://vocabulary.uncefact.org/QuantityType>

<a id="rail-consignment-note-cim"></a>
### Rail Consignment Note CIM
- **IRI:** <https://iri.suomi.fi/model/ktddecv/RailConsignmentNoteCIM>
- **Subclass of:** [Thing](#thing)

<a id="regulatory-certificate"></a>
### Regulatory Certificate
- **IRI:** <https://iri.suomi.fi/model/ktddecv/RegulatoryCertificate>
- **Subclass of:** [Thing](#thing)

<a id="road-consignment-note-cmr"></a>
### Road Consignment Note CMR
- **IRI:** <https://iri.suomi.fi/model/ktddecv/RoadConsignmentNoteCMR>
- **Subclass of:** [Thing](#thing)

<a id="rule-set"></a>
### Rule Set
- **IRI:** <https://iri.suomi.fi/model/ktddecv/RuleSet>
- **Subclass of:** [Thing](#thing)

<a id="sea-cargo-manifest"></a>
### Sea Cargo Manifest
- **IRI:** <https://iri.suomi.fi/model/ktddecv/SeaCargoManifest>
- **Subclass of:** [Thing](#thing)

<a id="sea-waybill"></a>
### Sea Waybill
- **IRI:** <https://iri.suomi.fi/model/ktddecv/SeaWaybill>
- **Description:** Non-negotiable sea transport document serving as a receipt and evidence of the contract of carriage; identifies shipment, parties, vessel/voyage and routing.
- **Subclass of:** [Transport Document](#transport-document)

<a id="seal"></a>
### Seal
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Seal>
- **Subclass of:** [Thing](#thing)

<a id="shipment"></a>
### Shipment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Shipment>
- **Description:** The set of goods that are the subject of a single sales contract (and usually a single invoice) between a seller and a buyer.
- **Subclass of:** [Activity](#activity)

<a id="shipment-basis"></a>
### Shipment Basis
- **IRI:** <https://iri.suomi.fi/model/ktddecv/ShipmentBasis>
- **Subclass of:** [Concept](#concept)

<a id="ships-delivery-order"></a>
### Ships Delivery Order
- **IRI:** <https://iri.suomi.fi/model/ktddecv/ShipsDeliveryOrder>
- **Description:** A document issued by a carrier or its agent authorizing delivery of the goods to the consignee or other named party. Used after arrival of a vessel to release cargo covered by a bill of lading or sea waybill.
- **Subclass of:** [Transport Document](#transport-document)

<a id="status"></a>
### Status
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Status>
- **Subclass of:** [Thing](#thing)

<a id="tenor"></a>
### Tenor
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Tenor>
- **Description:** Rule that determines when a payment/obligation under a negotiable or deferred-payment instrument becomes due.
- **Subclass of:** [Thing](#thing)

<a id="tir-carnet"></a>
### TIR Carnet
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TIRCarnet>
- **Subclass of:** [Thing](#thing)

<a id="trade-delivery-terms"></a>
### Trade Delivery Terms
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TradeDeliveryTerms>
- **Subclass of:** [Thing](#thing)

<a id="trade-item"></a>
### Trade Item
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TradeItem>
- **Subclass of:** [Thing](#thing)
- **Equivalent to:** <https://iri.suomi.fi/model/ktddecv/TradeProduct>

<a id="trade-line-item"></a>
### Trade Line Item
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TradeLineItem>
- **Description:** A distinct line item in a trade transaction, representing an ordered, invoiced, shipped, or declared good or service, including its quantity, price, and related references.
- **Subclass of:** [Thing](#thing)

<a id="trade-product"></a>
### Trade Product
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TradeProduct>
- **Description:** A product or service offered or supplied in trade, identified and classified for commercial, fiscal or regulatory purposes.
- **Subclass of:** [Thing](#thing)
- **Equivalent to:** <https://vocabulary.uncefact.org/TradeProduct>

<a id="transit-accompanying-document"></a>
### Transit Accompanying Document
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TransitAccompanyingDocument>
- **Description:** The Transit Accompanying Document (TAD) used in the EU Common Transit procedure, identified by an MRN and containing information about offices of departure, destination, and transit.
- **Subclass of:** [Document](#document)

<a id="transport-document"></a>
### Transport Document
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TransportDocument>
- **Subclass of:** [Thing](#thing)

<a id="transport-equipment"></a>
### Transport Equipment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TransportEquipment>
- **Subclass of:** [Thing](#thing)

<a id="transport-event"></a>
### Transport Event
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TransportEvent>
- **Subclass of:** [Thing](#thing)
- **Equivalent to:** <https://vocabulary.uncefact.org/TransportEvent>, <https://iri.suomi.fi/model/busdoc/1.0.2/TransportEvent>

<a id="transport-leg"></a>
### Transport Leg
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TransportLeg>
- **Subclass of:** [Thing](#thing)

<a id="transport-means"></a>
### Transport Means
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TransportMeans>
- **Subclass of:** [Thing](#thing)

<a id="veterinary-certificate"></a>
### Veterinary Certificate
- **IRI:** <https://iri.suomi.fi/model/ktddecv/VeterinaryCertificate>
- **Subclass of:** [Thing](#thing)

<a id="warehouse"></a>
### Warehouse
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Warehouse>
- **Subclass of:** [Thing](#thing)

<a id="warehouse-receipt"></a>
### Warehouse Receipt
- **IRI:** <https://iri.suomi.fi/model/ktddecv/WarehouseReceipt>
- **Subclass of:** [Thing](#thing)

<a id="object-properties"></a>
## Object Properties

<a id="additional-amounts-covered"></a>
### additional amounts covered
- **IRI:** <https://iri.suomi.fi/model/ktddecv/additionalAmountsCovered>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="advise-through-bank-party"></a>
### advise through bank party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/adviseThroughBankParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="advising-bank-party"></a>
### advising bank party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/advisingBankParty>
- **Description:** Association from a documentary credit (letter of credit) to the bank that advises the credit (and any amendments) to the beneficiary.
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="airport-of-departure"></a>
### airport of departure
- **IRI:** <https://iri.suomi.fi/model/ktddecv/airportOfDeparture>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="airport-of-destination"></a>
### airport of destination
- **IRI:** <https://iri.suomi.fi/model/ktddecv/airportOfDestination>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="applicable-commodity-classification"></a>
### applicable commodity classification
- **IRI:** <https://iri.suomi.fi/model/ktddecv/applicableCommodityClassification>
- **Subproperty of:** <https://iri.suomi.fi/model/ktddecv/hasCommodityClassification>

<a id="applicable-rules"></a>
### applicable rules
- **IRI:** <https://iri.suomi.fi/model/ktddecv/applicableRules>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="applicant-bank-party"></a>
### applicant bank party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/applicantBankParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="applicant-party"></a>
### applicant party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/applicantParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="applied-commodity-classification"></a>
### applied commodity classification
- **IRI:** <https://iri.suomi.fi/model/ktddecv/appliedCommodityClassification>
- **Subproperty of:** <https://iri.suomi.fi/model/ktddecv/hasCommodityClassification>

<a id="arrival-place"></a>
### arrival place
- **IRI:** <https://iri.suomi.fi/model/ktddecv/arrivalPlace>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="available-at-place"></a>
### available at place
- **IRI:** <https://iri.suomi.fi/model/ktddecv/availableAtPlace>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="available-with-party"></a>
### available with party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/availableWithParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="available-with-qualifier"></a>
### available with qualifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/availableWithQualifier>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="base-amount"></a>
### base amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/baseAmount>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="beneficiary-party"></a>
### beneficiary party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/beneficiaryParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="buyer-party"></a>
### buyer party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/buyerParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="carrier-party"></a>
### carrier party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/carrierParty>
- **Description:** For Sea Waybill: The ocean carrier issuing or responsible for the carriage.
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="certificate-number"></a>
### certificate number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/certificateNumber>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="chargeable-weight"></a>
### chargeable weight
- **IRI:** <https://iri.suomi.fi/model/ktddecv/chargeableWeight>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="charged-by-party"></a>
### charged by party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/chargedByParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="charged-to-party"></a>
### charged to party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/chargedToParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="claims-payable-at-place"></a>
### claims payable at place
- **IRI:** <https://iri.suomi.fi/model/ktddecv/claimsPayableAtPlace>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="confirmation-instruction-code"></a>
### confirmation instruction code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/confirmationInstructionCode>
- **Description:** Code indicating whether confirmation is requested, may be added, or is without confirmation.
- **Range:** <http://www.w3.org/2004/02/skos/core#Concept>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="confirming-bank-party"></a>
### confirming bank party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/confirmingBankParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="confirming-party"></a>
### confirming party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/confirmingParty>
- **Description:** Party that actually added confirmation.
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="consignee-party"></a>
### consignee party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/consigneeParty>
- **Description:** The party to whom the goods are to be delivered.
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="consignment-identifier"></a>
### consignment identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/consignmentIdentifier>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="consignor-party"></a>
### consignor party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/consignorParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="country-of-origin-code"></a>
### country of origin code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/countryOfOriginCode>
- **Description:** Country of non-preferential or preferential origin for the goods line, as an ISO 3166-1 code concept.
- **Range:** <http://www.w3.org/2004/02/skos/core#Concept>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="coverage-amount"></a>
### coverage amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/coverageAmount>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="coverage-type-code"></a>
### coverage type code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/coverageTypeCode>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="covered-shipment"></a>
### covered shipment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/coveredShipment>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="covers-additional-charge"></a>
### covers additional charge
- **IRI:** <https://iri.suomi.fi/model/ktddecv/coversAdditionalCharge>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="covers-contract"></a>
### covers contract
- **IRI:** <https://iri.suomi.fi/model/ktddecv/coversContract>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="creditor-specified-financial-institution"></a>
### creditor specified financial institution
- **IRI:** <https://iri.suomi.fi/model/ktddecv/creditorSpecifiedFinancialInstitution>
- **Subproperty of:** <https://vocabulary.uncefact.org/creditorSpecifiedFinancialInstitution>

<a id="customs-procedure-code"></a>
### customs procedure code 
- **IRI:** <https://iri.suomi.fi/model/ktddecv/customsProcedureCode>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="declarant-party"></a>
### declarant party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/declarantParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="declaration-number"></a>
### declaration number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/declarationNumber>
- **Description:** National MRN or declaration number as Identifier node.
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="declared-customs-value-amount"></a>
### declared customs value amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/declaredCustomsValueAmount>
- **Range:** [Monetary Amount](#monetary-amount)
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="declared-value-for-carriage"></a>
### declared value for carriage
- **IRI:** <https://iri.suomi.fi/model/ktddecv/declaredValueForCarriage>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="defines-payment-terms"></a>
### defines payment terms
- **IRI:** <https://iri.suomi.fi/model/ktddecv/definesPaymentTerms>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="delivered-to"></a>
### delivered to
- **IRI:** <https://iri.suomi.fi/model/ktddecv/deliveredTo>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="delivery-location"></a>
### delivery location
- **IRI:** <https://iri.suomi.fi/model/ktddecv/deliveryLocation>
- **Range:** [Location](#location)
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="delivery-party"></a>
### delivery party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/deliveryParty>
- **Subproperty of:** <https://vocabulary.uncefact.org/deliveryParty>
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/deliveryParty_>

<a id="delivery-terms"></a>
### delivery terms
- **IRI:** <https://iri.suomi.fi/model/ktddecv/deliveryTerms>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="departure-place"></a>
### departure place
- **IRI:** <https://iri.suomi.fi/model/ktddecv/departurePlace>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="describes-item"></a>
### describes item
- **IRI:** <https://iri.suomi.fi/model/ktddecv/describesItem>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="describes-trade-product"></a>
### describes trade product
- **IRI:** <https://iri.suomi.fi/model/ktddecv/describesTradeProduct>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="document-type"></a>
### document type
- **IRI:** <https://iri.suomi.fi/model/ktddecv/documentType>
- **Range:** <http://www.w3.org/2004/02/skos/core#Concept>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="drafts-at-tenor"></a>
### drafts at tenor
- **IRI:** <https://iri.suomi.fi/model/ktddecv/draftsAtTenor>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="drawee-party"></a>
### drawee party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/draweeParty>
- **Description:** Party on whom a demand for payment is drawn and who is ordered to pay (e.g., in a bill of exchange/draft/cheque).
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="drawer-party"></a>
### drawer party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/drawerParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="equipment-identifier"></a>
### equipment identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/equipmentIdentifier>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="event-identifier"></a>
### event identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/eventIdentifier>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="event-place"></a>
### event place
- **IRI:** <https://iri.suomi.fi/model/ktddecv/eventPlace>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="event-type-code"></a>
### event type code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/eventTypeCode>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="exporter-party"></a>
### exporter party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/exporterParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/exporterParty>, <https://vocabulary.uncefact.org/exporterParty>

<a id="final-destination-place"></a>
### final destination place
- **IRI:** <https://iri.suomi.fi/model/ktddecv/finalDestinationPlace>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="first-place-of-receipt"></a>
### first place of receipt
- **IRI:** <https://iri.suomi.fi/model/ktddecv/firstPlaceOfReceipt>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="for-goods-item"></a>
### for goods item
- **IRI:** <https://iri.suomi.fi/model/ktddecv/forGoodsItem>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="freight-charges-amount"></a>
### freight charges amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/freightChargesAmount>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="freight-payable-at-place"></a>
### freight payable at place
- **IRI:** <https://iri.suomi.fi/model/ktddecv/freightPayableAtPlace>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="from-location"></a>
### from location
- **IRI:** <https://iri.suomi.fi/model/ktddecv/fromLocation>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="governed-by-rule-set"></a>
### governed by rule set
- **IRI:** <https://iri.suomi.fi/model/ktddecv/governedByRuleSet>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-address"></a>
### has Address
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasAddress>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-amount"></a>
### has amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasAmount>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-applicant"></a>
### has applicant
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasApplicant>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-applicant-bank"></a>
### has applicant bank
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasApplicantBank>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-availability-method"></a>
### has availability method
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasAvailabilityMethod>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-beneficiary"></a>
### has beneficiary
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasBeneficiary>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-buyer"></a>
### has buyer
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasBuyer>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-characteristic"></a>
### has characteristic
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasCharacteristic>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-classification-scheme"></a>
### has classification scheme
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasClassificationScheme>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-commodity-classification"></a>
### has commodity classification
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasCommodityClassification>
- **Description:** Associates an item line with a commodity/service classification entry.
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-consignment"></a>
### has consignment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasConsignment>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-country-of-origin"></a>
### has country of origin
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasCountryOfOrigin>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-credit-availability"></a>
### has credit availability
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasCreditAvailability>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-dangerous-goods"></a>
### has dangerous goods
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasDangerousGoods>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-dangerous-goods-details"></a>
### has dangerous goods details
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasDangerousGoodsDetails>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-delivery"></a>
### has delivery
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasDelivery>
- **Range:** [Delivery](#delivery)
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-delivery-milestone"></a>
### has delivery milestone
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasDeliveryMilestone>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-delivery-period"></a>
### has delivery period
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasDeliveryPeriod>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-drawee"></a>
### has drawee
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasDrawee>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-goods-item"></a>
### has goods item
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasGoodsItem>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-identifier"></a>
### has identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasIdentifier>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-invoice-line"></a>
### has invoice line
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasInvoiceLine>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-invoicee"></a>
### has invoicee
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasInvoicee>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-message"></a>
### has message
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasMessage>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-package"></a>
### has package
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasPackage>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-package-item"></a>
### has package item
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasPackageItem>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-payment-line"></a>
### has payment line
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasPaymentLine>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-payment-schedule-line"></a>
### has payment schedule line
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasPaymentScheduleLine>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-payment-terms"></a>
### has payment terms
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasPaymentTerms>
- **Range:** [Payment Terms](#payment-terms)
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-presentation"></a>
### has presentation
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasPresentation>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-presentation-period"></a>
### has presentation period
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasPresentationPeriod>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-product"></a>
### has product
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasProduct>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-quantity"></a>
### has quantity
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasQuantity>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-seller"></a>
### has seller
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasSeller>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-shipment"></a>
### has shipment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasShipment>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-shipment-period"></a>
### has shipment period
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasShipmentPeriod>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-status"></a>
### has status
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasStatus>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-tenor"></a>
### has tenor
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasTenor>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-transport-equipment"></a>
### has transport equipment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasTransportEquipment>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="has-transport-event"></a>
### has transport event
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hasTransportEvent>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="importer-party"></a>
### importer party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/importerParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/importerParty>, <https://vocabulary.uncefact.org/importerParty>

<a id="includes-allowance-charge"></a>
### includes allowance charge
- **IRI:** <https://iri.suomi.fi/model/ktddecv/includesAllowanceCharge>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="includes-duty-tax-fee"></a>
### includes duty tax fee
- **IRI:** <https://iri.suomi.fi/model/ktddecv/includesDutyTaxFee>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="incoterms-code"></a>
### incoterms code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/incotermsCode>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="incoterms-location"></a>
### incoterms location
- **IRI:** <https://iri.suomi.fi/model/ktddecv/incotermsLocation>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="inner-packaging-quantity"></a>
### inner packaging quantity
- **IRI:** <https://iri.suomi.fi/model/ktddecv/innerPackagingQuantity>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="instructed-party"></a>
### instructed party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/instructedParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="instructing-party"></a>
### instructing party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/instructingParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="instruction-to-bank"></a>
### instruction to bank
- **IRI:** <https://iri.suomi.fi/model/ktddecv/instructionToBank>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="insurance-value-amount"></a>
### insurance value amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/insuranceValueAmount>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="insured-amount"></a>
### insured amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/insuredAmount>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="insured-party"></a>
### insured party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/insuredParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="insurer-party"></a>
### insurer party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/insurerParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="invoice-document"></a>
### invoice document
- **IRI:** <https://iri.suomi.fi/model/ktddecv/invoiceDocument>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/invoiceDocumentReference>, <https://vocabulary.uncefact.org/invoiceDocument>

<a id="invoice-payment-terms"></a>
### invoice payment terms
- **IRI:** <https://iri.suomi.fi/model/ktddecv/invoicePaymentTerms>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="invoiced-quantity"></a>
### invoiced quantity
- **IRI:** <https://iri.suomi.fi/model/ktddecv/invoicedQuantity>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="invoicee-party"></a>
### invoicee party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/invoiceeParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="is-realized-by-consignment"></a>
### is realized by consignment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/isRealizedByConsignment>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="issuer-party"></a>
### issuer party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/issuerParty>
- **Range:** [Party](#party)
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="issuing-authority-party"></a>
### issuing authority party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/issuingAuthorityParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="issuing-bank-party"></a>
### issuing bank party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/issuingBankParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="issuing-carrier-party"></a>
### issuing carrier party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/issuingCarrierParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="location-country"></a>
### location country
- **IRI:** <https://iri.suomi.fi/model/ktddecv/locationCountry>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="maximum-credit-amount"></a>
### maximum credit amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/maximumCreditAmount>
- **Description:** An instruction on a Documentary Credit that the stated credit amount is an absolute ceiling: the total of drawings/claims under the credit must not exceed the stated amount. It is used to cap drawings even where tolerances or qualifying words (e.g., “about/approximately”) might otherwise allow variation.
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="net-quantity-per-package"></a>
### net quantity per package
- **IRI:** <https://iri.suomi.fi/model/ktddecv/netQuantityPerPackage>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="nominated-bank-party"></a>
### nominated bank party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/nominatedBankParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="notify-party"></a>
### notify party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/notifyParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="obligee-party"></a>
### obligee party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/obligeeParty>
- **Description:** Party entitled to receive the performance of an obligation (a payment, delivery, or service).
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="obligor-party"></a>
### obligor party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/obligorParty>
- **Description:** Party that bears a duty to perform an obligation (e.g., pay money, deliver goods, perform a service) under a business commitment.
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="observed-transport-means"></a>
### observed transport means
- **IRI:** <https://iri.suomi.fi/model/ktddecv/observedTransportMeans>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="office-of-departure"></a>
### office of departure
- **IRI:** <https://iri.suomi.fi/model/ktddecv/officeOfDeparture>
- **Description:** The customs office of departure where the transit procedure begins.
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="office-of-destination"></a>
### office of destination
- **IRI:** <https://iri.suomi.fi/model/ktddecv/officeOfDestination>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="order-amount"></a>
### order amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/orderAmount>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="origin-country"></a>
### origin country
- **IRI:** <https://iri.suomi.fi/model/ktddecv/originCountry>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>
- **Equivalent to:** <https://gs1.org/voc/countryOfOrigin>, <https://iri.suomi.fi/model/busdoc/1.0.2/originCountry>, <https://vocabulary.uncefact.org/originCountry>

<a id="other-charges-amount"></a>
### other charges amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/otherChargesAmount>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="package-type-code"></a>
### package type code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/packageTypeCode>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="packing-list-number"></a>
### packing list number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/packingListNumber>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="party-address"></a>
### party address
- **IRI:** <https://iri.suomi.fi/model/ktddecv/partyAddress>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="party-identifier"></a>
### party identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/partyIdentifier>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="party-legal-entity"></a>
### party legal entity
- **IRI:** <https://iri.suomi.fi/model/ktddecv/partyLegalEntity>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="payee-party"></a>
### payee party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/payeeParty>
- **Description:** Party to whom a payment is to be made under an obligation or instrument.
- **Subproperty of:** <https://iri.suomi.fi/model/ktddecv/obligeeParty>

<a id="payer-party"></a>
### payer party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/payerParty>
- **Subproperty of:** <https://iri.suomi.fi/model/ktddecv/obligorParty>

<a id="payment-location"></a>
### payment location
- **IRI:** <https://iri.suomi.fi/model/ktddecv/paymentLocation>
- **Subproperty of:** <https://vocabulary.uncefact.org/paymentPlaceLocation>

<a id="payment-settlement-method"></a>
### payment settlement method
- **IRI:** <https://iri.suomi.fi/model/ktddecv/paymentSettlementMethod>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="per-unit-amount"></a>
### per unit amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/perUnitAmount>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="place-of-delivery"></a>
### place of delivery
- **IRI:** <https://iri.suomi.fi/model/ktddecv/placeOfDelivery>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="place-of-discharge"></a>
### place of discharge
- **IRI:** <https://iri.suomi.fi/model/ktddecv/placeOfDischarge>
- **Description:** The location where goods are taken off a means of transport.
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="place-of-expiry"></a>
### place of expiry
- **IRI:** <https://iri.suomi.fi/model/ktddecv/placeOfExpiry>
- **Description:** The place of presentation for the credit (typically “at the counters of … [named bank/branch/location]”). In eUCP contexts, the “place” may be physical (bank/location) and/or an electronic address/system designated for presentation.
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="place-of-issue"></a>
### place of issue
- **IRI:** <https://iri.suomi.fi/model/ktddecv/placeOfIssue>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="place-of-loading"></a>
### place of loading
- **IRI:** <https://iri.suomi.fi/model/ktddecv/placeOfLoading>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="place-of-presentation"></a>
### place of presentation
- **IRI:** <https://iri.suomi.fi/model/ktddecv/placeOfPresentation>
- **Description:** The location at which a document, good, declaration, or other required item is formally presented to a designated party or authority.

In the context of a Documentary Credit, the location specified for the presentation of documents by the beneficiary to the nominated bank, confirming bank, or issuing bank for examination and payment.
- **Range:** [Location](#location)
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="place-of-receipt"></a>
### place of receipt
- **IRI:** <https://iri.suomi.fi/model/ktddecv/placeOfReceipt>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="place-of-taking-in-charge"></a>
### place of taking in charge
- **IRI:** <https://iri.suomi.fi/model/ktddecv/placeOfTakingInCharge>
- **Description:** The location at which a carrier or other responsible party takes goods, consignments, or transport equipment into their charge for further carriage, handling, or responsibility in the transport chain.
- **Range:** [Location](#location)
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="preference-criterion-code"></a>
### preference criterion code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/preferenceCriterionCode>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="presentation-base-event"></a>
### presentation base event
- **IRI:** <https://iri.suomi.fi/model/ktddecv/presentationBaseEvent>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="publisher"></a>
### publisher
- **IRI:** <https://iri.suomi.fi/model/ktddecv/publisher>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="receiver-party"></a>
### receiver party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/receiverParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="references-letter-of-credit"></a>
### references letter of credit
- **IRI:** <https://iri.suomi.fi/model/ktddecv/referencesLetterOfCredit>
- **Range:** [Documentary Credit](#documentary-credit)
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="references-pre-advice"></a>
### references pre advice
- **IRI:** <https://iri.suomi.fi/model/ktddecv/referencesPreAdvice>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="reimbursing-bank-party"></a>
### reimbursing bank party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/reimbursingBankParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="related-order"></a>
### related order
- **IRI:** <https://iri.suomi.fi/model/ktddecv/relatedOrder>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="relates-to-consignment"></a>
### relates to consignment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/relatesToConsignment>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="relates-to-goods-item"></a>
### relates to goods item
- **IRI:** <https://iri.suomi.fi/model/ktddecv/relatesToGoodsItem>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="relates-to-invoice"></a>
### relates to invoice
- **IRI:** <https://iri.suomi.fi/model/ktddecv/relatesToInvoice>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="relates-to-package"></a>
### relates to package
- **IRI:** <https://iri.suomi.fi/model/ktddecv/relatesToPackage>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="relates-to-transport-document"></a>
### relates to transport document
- **IRI:** <https://iri.suomi.fi/model/ktddecv/relatesToTransportDocument>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="reported-by-party"></a>
### reported by party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/reportedByParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="requested-confirmation-party"></a>
### requested confirmation party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/requestedConfirmationParty>
- **Description:** Party requested to add confirmation.
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="requested-delivery-period"></a>
### requested delivery period
- **IRI:** <https://iri.suomi.fi/model/ktddecv/requestedDeliveryPeriod>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="required-document-type"></a>
### required document type
- **IRI:** <https://iri.suomi.fi/model/ktddecv/requiredDocumentType>
- **Range:** <http://www.w3.org/2004/02/skos/core#Concept>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="requires-document"></a>
### requires document
- **IRI:** <https://iri.suomi.fi/model/ktddecv/requiresDocument>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="seal-identifier"></a>
### seal identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/sealIdentifier>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="seller-party"></a>
### seller party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/sellerParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="sender-party"></a>
### sender party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/senderParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="shipper-party"></a>
### shipper party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/shipperParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="sscc"></a>
### sscc
- **IRI:** <https://iri.suomi.fi/model/ktddecv/sscc>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="statistical-value-amount"></a>
### statistical value amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/statisticalValueAmount>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="surety-party"></a>
### surety party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/suretyParty>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="tenor-period"></a>
### tenor period
- **IRI:** <https://iri.suomi.fi/model/ktddecv/tenorPeriod>
- **Range:** [Period of Time](#period-of-time)
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="to-location"></a>
### to location
- **IRI:** <https://iri.suomi.fi/model/ktddecv/toLocation>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="total-amount"></a>
### total amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/totalAmount>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>
- **Equivalent to:** <https://vocabulary.uncefact.org/totalInvoiceAmount>

<a id="total-goods-item-quantity"></a>
### total goods item quantity
- **IRI:** <https://iri.suomi.fi/model/ktddecv/totalGoodsItemQuantity>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="total-gross-weight"></a>
### total gross weight
- **IRI:** <https://iri.suomi.fi/model/ktddecv/totalGrossWeight>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="total-invoice-amount"></a>
### total invoice amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/totalInvoiceAmount>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="total-net-weight"></a>
### total net weight
- **IRI:** <https://iri.suomi.fi/model/ktddecv/totalNetWeight>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="total-package-count"></a>
### total package count
- **IRI:** <https://iri.suomi.fi/model/ktddecv/totalPackageCount>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="total-package-quantity"></a>
### total package quantity
- **IRI:** <https://iri.suomi.fi/model/ktddecv/totalPackageQuantity>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="total-transport-handling-unit-quantity"></a>
### total transport handling unit quantity
- **IRI:** <https://iri.suomi.fi/model/ktddecv/totalTransportHandlingUnitQuantity>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="transit-office"></a>
### transit office
- **IRI:** <https://iri.suomi.fi/model/ktddecv/transitOffice>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="transport-document-type-code"></a>
### transport document type code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/transportDocumentTypeCode>
- **Range:** <http://www.w3.org/2004/02/skos/core#Concept>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="transport-mode-code"></a>
### transport mode code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/transportModeCode>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="transshipment-place"></a>
### transshipment place
- **IRI:** <https://iri.suomi.fi/model/ktddecv/transshipmentPlace>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="uses-transport-equipment"></a>
### uses transport equipment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/usesTransportEquipment>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="uses-transport-means"></a>
### uses transport means
- **IRI:** <https://iri.suomi.fi/model/ktddecv/usesTransportMeans>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="validity-period"></a>
### validity period
- **IRI:** <https://iri.suomi.fi/model/ktddecv/validityPeriod>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topObjectProperty>

<a id="datatype-properties"></a>
## Datatype Properties

<a id="actual-arrival-date-time"></a>
### Actual Arrival Date Time
- **IRI:** <https://iri.suomi.fi/model/ktddecv/actualArrivalDateTime>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="actual-departure-date-time"></a>
### Actual Departure Date Time
- **IRI:** <https://iri.suomi.fi/model/ktddecv/actualDepartureDateTime>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="additional-conditions-text"></a>
### Additional Conditions Text
- **IRI:** <https://iri.suomi.fi/model/ktddecv/additionalConditionsText>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="airport-of-departure-iata-code"></a>
### Airport of Departure IATA Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/airportOfDepartureIATACode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="airport-of-destination-iata-code"></a>
### Airport of Destination IATA Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/airportOfDestinationIATACode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="allowance-charge-reason-code"></a>
### Allowance Charge Reason Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/allowanceChargeReasonCode>
- **Description:** Enumerated “charge reason” code list (e.g., ADVISE, CONFIRMATION, AMENDMENT, NEGOTIATION, DISCREPANCY, COURIER, SWIFT, HANDLING, OTHER).
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="alternate-name"></a>
### Alternate Name
- **IRI:** <https://iri.suomi.fi/model/ktddecv/alternateName>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="amount-percent-of-base"></a>
### Amount Percent Of Base
- **IRI:** <https://iri.suomi.fi/model/ktddecv/amountPercentOfBase>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="amount-tolerance-percent"></a>
### Amount Tolerance Percent
- **IRI:** <https://iri.suomi.fi/model/ktddecv/amountTolerancePercent>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="amount-value"></a>
### Amount Value
- **IRI:** <https://iri.suomi.fi/model/ktddecv/amountValue>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="arrival-date-time"></a>
### Arrival Date Time
- **IRI:** <https://iri.suomi.fi/model/ktddecv/arrivalDateTime>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="available-at-locode"></a>
### Available At Locode
- **IRI:** <https://iri.suomi.fi/model/ktddecv/availableAtLocode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="available-with-by"></a>
### Available With By
- **IRI:** <https://iri.suomi.fi/model/ktddecv/availableWithBy>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="bank-account-identifier"></a>
### Bank Account Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/bankAccountIdentifier>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="bond-number"></a>
### Bond Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/bondNumber>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="border-crossing-point-code"></a>
### Border Crossing Point Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/borderCrossingPointCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="botanical-details"></a>
### Botanical Details
- **IRI:** <https://iri.suomi.fi/model/ktddecv/botanicalDetails>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="calculation-percent"></a>
### Calculation Percent
- **IRI:** <https://iri.suomi.fi/model/ktddecv/calculationPercent>
- **Description:** Percentage when the charge is calculated from a base amount.
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="charge-indicator"></a>
### Charge Indicator
- **IRI:** <https://iri.suomi.fi/model/ktddecv/chargeIndicator>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="classification-code"></a>
### Classification Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/classificationCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="commodity-code"></a>
### Commodity Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/commodityCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/commodityCode>

<a id="confirmation-added-date"></a>
### Confirmation Added Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/confirmationAddedDate>
- **Description:** Date on which confirmation became effective.
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="confirmation-date"></a>
### Confirmation Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/confirmationDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="container-number"></a>
### Container Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/containerNumber>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="contract-identifier"></a>
### Contract Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/contractIdentifier>
- **Range:** <http://www.w3.org/2001/XMLSchema#string>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="contract-number"></a>
### Contract Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/contractNumber>
- **Range:** <http://www.w3.org/2001/XMLSchema#string>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="country-code"></a>
### Country Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/countryCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>
- **Equivalent to:** <https://gs1.org/voc/countryCode>

<a id="country-name"></a>
### Country Name
- **IRI:** <https://iri.suomi.fi/model/ktddecv/countryName>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="credit-amount-tolerance-percentage"></a>
### Credit Amount Tolerance Percentage
- **IRI:** <https://iri.suomi.fi/model/ktddecv/creditAmountTolerancePercentage>
- **Description:** A percentage tolerance applied to the stated credit amount, expressed as a decimal value (e.g. ±10). This indicates by how much drawings may exceed or fall short of the stated amount, without affecting the unit price of goods.
- **Range:** <http://www.w3.org/2001/XMLSchema#decimal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="credit-identifier"></a>
### Credit Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/creditIdentifier>
- **Range:** <http://www.w3.org/2001/XMLSchema#string>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="currency-code"></a>
### Currency Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/currencyCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/currencyCode>, <https://gs1.org/voc/priceCurrency>

<a id="customs-office-code"></a>
### Customs Office Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/customsOfficeCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="declaration-date"></a>
### Declaration Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/declarationDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="deferred-payment-date"></a>
### Deferred Payment Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/deferredPaymentDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="delivery-date"></a>
### Delivery Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/deliveryDate>
- **Range:** <http://www.w3.org/2001/XMLSchema#dateTime>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/actualDeliveryDate>

<a id="delivery-terms-text"></a>
### Delivery Terms Text
- **IRI:** <https://iri.suomi.fi/model/ktddecv/deliveryTermsText>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="delivery-type-code"></a>
### Delivery Type Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/deliveryTypeCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="departure-date-time"></a>
### Departure Date Time
- **IRI:** <https://iri.suomi.fi/model/ktddecv/departureDateTime>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="description"></a>
### Description
- **IRI:** <https://iri.suomi.fi/model/ktddecv/description>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="description-of-goods-text"></a>
### Description of Goods Text
- **IRI:** <https://iri.suomi.fi/model/ktddecv/descriptionOfGoodsText>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <https://iri.suomi.fi/model/ktddecv/itemDescriptionText>

<a id="despatch-date"></a>
### Despatch Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/despatchDate>
- **Range:** <http://www.w3.org/2001/XMLSchema#dateTime>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="document-date"></a>
### Document Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/documentDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="document-identifier"></a>
### Document Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/documentIdentifier>
- **Range:** <http://www.w3.org/2001/XMLSchema#string>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="documentary-credit-type-code"></a>
### Documentary Credit Type Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/documentaryCreditTypeCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="drafts-at-locode"></a>
### Drafts At Locode
- **IRI:** <https://iri.suomi.fi/model/ktddecv/draftsAtLocode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="elevation-meters"></a>
### Elevation Meters
- **IRI:** <https://iri.suomi.fi/model/ktddecv/elevationMeters>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="end-date"></a>
### End Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/endDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="eori-number"></a>
### EORI Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/eORINumber>
- **Range:** <http://www.w3.org/2001/XMLSchema#string>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="estimated-time-of-departure"></a>
### Estimated Time of Departure
- **IRI:** <https://iri.suomi.fi/model/ktddecv/estimatedTimeOfDeparture>
- **Range:** <http://www.w3.org/2001/XMLSchema#dateTime>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="event-date-time"></a>
### Event Date Time
- **IRI:** <https://iri.suomi.fi/model/ktddecv/eventDateTime>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="event-note-text"></a>
### Event Note Text
- **IRI:** <https://iri.suomi.fi/model/ktddecv/eventNoteText>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="excepted-quantity-indicator"></a>
### Excepted Quantity Indicator
- **IRI:** <https://iri.suomi.fi/model/ktddecv/exceptedQuantityIndicator>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="expiry-date"></a>
### Expiry Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/expiryDate>
- **Description:** The last calendar date on which a complying presentation must be made at the place where the credit expires (i.e., with the bank with which the credit is available, or as otherwise specified in the credit). Express as a calendar date (not a period or free text).
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="expiry-place-name"></a>
### Expiry Place Name
- **IRI:** <https://iri.suomi.fi/model/ktddecv/expiryPlaceName>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="final-destination-un-locode"></a>
### Final Destination UN Locode
- **IRI:** <https://iri.suomi.fi/model/ktddecv/finalDestinationUNLocode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="flash-point-temperature"></a>
### Flash Point Temperature
- **IRI:** <https://iri.suomi.fi/model/ktddecv/flashPointTemperature>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="flight-date"></a>
### Flight Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/flightDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="flight-number"></a>
### Flight Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/flightNumber>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="freight-payment-term-code"></a>
### Freight Payment Term Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/freightPaymentTermCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="geo-wkt"></a>
### Geo WKT
- **IRI:** <https://iri.suomi.fi/model/ktddecv/geoWKT>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="handling-information"></a>
### Handling Information
- **IRI:** <https://iri.suomi.fi/model/ktddecv/handlingInformation>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="hazard-class-code"></a>
### Hazard Class Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hazardClassCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="hazard-label-code"></a>
### Hazard Label Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hazardLabelCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="hazardous-risk-indicator"></a>
### Hazardous Risk Indicator
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hazardousRiskIndicator>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="house-air-waybill-number"></a>
### House Air Waybill Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/houseAirWaybillNumber>
- **Description:** The HAWB number identifying a consolidated shipment at house level, when applicable.
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="house-waybill-document-identifier"></a>
### House Waybill Document Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/houseWaybillDocumentIdentifier>
- **Range:** <http://www.w3.org/2001/XMLSchema#string>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="hs-code"></a>
### HS Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/hSCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="iata-code"></a>
### IATA Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/iataCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="icao-airport-code"></a>
### ICAO Airport Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/icaoAirportCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="imo-ship-id"></a>
### IMO Ship ID
- **IRI:** <https://iri.suomi.fi/model/ktddecv/iMOShipID>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="instruction-text"></a>
### Instruction Text
- **IRI:** <https://iri.suomi.fi/model/ktddecv/instructionText>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="insurance-policy-number"></a>
### Insurance Policy Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/insurancePolicyNumber>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="insurance-terms-text"></a>
### Insurance Terms Text
- **IRI:** <https://iri.suomi.fi/model/ktddecv/insuranceTermsText>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="invoice-date"></a>
### Invoice Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/invoiceDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="invoice-number"></a>
### Invoice Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/invoiceNumber>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="issue-date"></a>
### Issue Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/issueDate>
- **Range:** <http://www.w3.org/2001/XMLSchema#dateTime>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/issueDate>

<a id="issuing-authority"></a>
### Issuing Authority
- **IRI:** <https://iri.suomi.fi/model/ktddecv/issuingAuthority>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="item-description-text"></a>
### Item Description Text
- **IRI:** <https://iri.suomi.fi/model/ktddecv/itemDescriptionText>
- **Description:** Narrative description of the goods/services at item level, usable across all trade documents.
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="latest-presentation-date"></a>
### Latest Presentation Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/latestPresentationDate>
- **Description:** Last date on which presentation is permitted under the credit.
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="latest-shipment-date"></a>
### Latest Shipment Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/latestShipmentDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="latitude"></a>
### Latitude
- **IRI:** <https://iri.suomi.fi/model/ktddecv/latitude>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="limited-quantity-indicator"></a>
### Limited Quantity Indicator
- **IRI:** <https://iri.suomi.fi/model/ktddecv/limitedQuantityIndicator>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="location-id"></a>
### Location ID
- **IRI:** <https://iri.suomi.fi/model/ktddecv/locationID>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="location-name"></a>
### Location Name
- **IRI:** <https://iri.suomi.fi/model/ktddecv/locationName>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="longitude"></a>
### Longitude
- **IRI:** <https://iri.suomi.fi/model/ktddecv/longitude>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="marine-pollutant-indicator"></a>
### Marine Pollutant Indicator
- **IRI:** <https://iri.suomi.fi/model/ktddecv/marinePollutantIndicator>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="marks-and-numbers-text"></a>
### Marks and Numbers Text
- **IRI:** <https://iri.suomi.fi/model/ktddecv/marksAndNumbersText>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="master-air-waybill-number"></a>
### Master Air Waybill Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/masterAirWaybillNumber>
- **Description:** The MAWB number identifying the air consignment at master level (e.g., &#x27;123-45678901&#x27;).
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="maturity-date"></a>
### Maturity Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/maturityDate>
- **Description:** The actual deferred payment due date, when determinable.
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="message-subject"></a>
### Message Subject
- **IRI:** <https://iri.suomi.fi/model/ktddecv/messageSubject>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="message-text"></a>
### Message Text
- **IRI:** <https://iri.suomi.fi/model/ktddecv/messageText>
- **Description:** Unstructured content of the message (language-tagged).
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="message-to-receiver-text"></a>
### Message To Receiver Text
- **IRI:** <https://iri.suomi.fi/model/ktddecv/messageToReceiverText>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="mrn"></a>
### MRN
- **IRI:** <https://iri.suomi.fi/model/ktddecv/mrn>
- **Description:** The Movement Reference Number (MRN) uniquely identifying the Transit Accompanying Document.
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="multiplier-factor-percent"></a>
### Multiplier Factor Percent
- **IRI:** <https://iri.suomi.fi/model/ktddecv/multiplierFactorPercent>
- **Description:** A percentage rate used to compute an additional or reduced monetary amount from a specified base amount. The calculated amount equals the base amount multiplied by this percentage divided by 100.
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="name"></a>
### Name
- **IRI:** <https://iri.suomi.fi/model/ktddecv/name>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/name>

<a id="negotiable-indicator"></a>
### Negotiable Indicator
- **IRI:** <https://iri.suomi.fi/model/ktddecv/negotiableIndicator>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="note-number"></a>
### Note Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/noteNumber>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="number-of-copies"></a>
### Number of Copies
- **IRI:** <https://iri.suomi.fi/model/ktddecv/numberOfCopies>
- **Range:** <http://www.w3.org/2001/XMLSchema#integer>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="number-of-originals"></a>
### Number of Originals
- **IRI:** <https://iri.suomi.fi/model/ktddecv/numberOfOriginals>
- **Range:** <http://www.w3.org/2001/XMLSchema#integer>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="on-board-date"></a>
### On Board Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/onBoardDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="order-date"></a>
### Order Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/orderDate>
- **Range:** <http://www.w3.org/2001/XMLSchema#dateTime>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="order-identifier"></a>
### Order Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/orderIdentifier>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="origin-establishment"></a>
### Origin Establishment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/originEstablishment>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="package-count"></a>
### Package Count
- **IRI:** <https://iri.suomi.fi/model/ktddecv/packageCount>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="package-length"></a>
### Package Length 
- **IRI:** <https://iri.suomi.fi/model/ktddecv/packageLength>
- **Range:** <http://www.w3.org/2001/XMLSchema#decimal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/loadingLengthMeasure>

<a id="packing-group-code"></a>
### Packing Group Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/packingGroupCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="packing-instruction-code"></a>
### Packing Instruction Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/packingInstructionCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="partial-shipment-allowed"></a>
### Partial Shipment Allowed
- **IRI:** <https://iri.suomi.fi/model/ktddecv/partialShipmentAllowed>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="payment-due-date"></a>
### Payment Due Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/paymentDueDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/paymentDueDate>

<a id="payment-method"></a>
### Payment Method
- **IRI:** <https://iri.suomi.fi/model/ktddecv/paymentMethod>
- **Range:** <http://www.w3.org/2001/XMLSchema#string>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/paymentMeansCode>

<a id="payment-term-code"></a>
### Payment Term Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/paymentTermCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="place-of-delivery-un-locode"></a>
### Place of Delivery UN Locode
- **IRI:** <https://iri.suomi.fi/model/ktddecv/placeOfDeliveryUNLocode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="place-of-receipt-un-locode"></a>
### Place of Receipt UN Locode
- **IRI:** <https://iri.suomi.fi/model/ktddecv/placeOfReceiptUNLocode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="planned-arrival-date-time"></a>
### Planned Arrival Date Time
- **IRI:** <https://iri.suomi.fi/model/ktddecv/plannedArrivalDateTime>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="planned-departure-date-time"></a>
### Planned Departure Date Time
- **IRI:** <https://iri.suomi.fi/model/ktddecv/plannedDepartureDateTime>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="port-facility-code"></a>
### Port Facility Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/portFacilityCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="port-of-discharge-un-locode"></a>
### Port Of Discharge UN Locode
- **IRI:** <https://iri.suomi.fi/model/ktddecv/portOfDischargeUNLocode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="port-of-loading-un-locode"></a>
### Port of Loading UN Locode
- **IRI:** <https://iri.suomi.fi/model/ktddecv/portOfLoadingUNLocode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="post-code"></a>
### Post Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/postCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="presentation-period-days"></a>
### Presentation Period Days
- **IRI:** <https://iri.suomi.fi/model/ktddecv/presentationPeriodDays>
- **Description:** Number of calendar days after the shipment date within which presentation must be made (SWIFT MT700 :48 is expressed as days).
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="product-description"></a>
### Product Description
- **IRI:** <https://iri.suomi.fi/model/ktddecv/productDescription>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="product-identifier"></a>
### Product Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/productIdentifier>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="product-name"></a>
### Product Name
- **IRI:** <https://iri.suomi.fi/model/ktddecv/productName>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="proper-shipping-name"></a>
### Proper Shipping Name
- **IRI:** <https://iri.suomi.fi/model/ktddecv/properShippingName>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="publication-date"></a>
### Publication Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/publicationDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="purchase-order-number"></a>
### Purchase Order Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/purchaseOrderNumber>
- **Range:** <http://www.w3.org/2001/XMLSchema#string>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="quantity-value"></a>
### Quantity Value
- **IRI:** <https://iri.suomi.fi/model/ktddecv/quantityValue>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="rail-station-code"></a>
### Rail Station Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/railStationCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="rail-wagon-identifier"></a>
### Rail Wagon Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/railWagonIdentifier>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="rule-set-identifier"></a>
### Rule Set Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/ruleSetIdentifier>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="sea-waybill-number"></a>
### Sea Waybill Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/seaWaybillNumber>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="sealed-indicator"></a>
### Sealed Indicator
- **IRI:** <https://iri.suomi.fi/model/ktddecv/sealedIndicator>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="shipment-identifier"></a>
### Shipment Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/shipmentIdentifier>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="shipping-marks"></a>
### Shipping Marks
- **IRI:** <https://iri.suomi.fi/model/ktddecv/shippingMarks>
- **Range:** <http://www.w3.org/2001/XMLSchema#string>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/shippingMarks>

<a id="ships-delivery-order-number"></a>
### Ships Delivery Order Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/shipsDeliveryOrderNumber>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="special-provision-code"></a>
### Special Provision Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/specialProvisionCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="start-date"></a>
### Start Date
- **IRI:** <https://iri.suomi.fi/model/ktddecv/startDate>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="subsidiary-hazard-code"></a>
### Subsidiary Hazard Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/subsidiaryHazardCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="technical-name"></a>
### Technical Name
- **IRI:** <https://iri.suomi.fi/model/ktddecv/technicalName>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="terminal-code"></a>
### Terminal Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/terminalCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="time-zone"></a>
### Time Zone
- **IRI:** <https://iri.suomi.fi/model/ktddecv/timeZone>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="title"></a>
### Title
- **IRI:** <https://iri.suomi.fi/model/ktddecv/title>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="total-collect-charges"></a>
### Total Collect Charges
- **IRI:** <https://iri.suomi.fi/model/ktddecv/totalCollectCharges>
- **Range:** <http://www.w3.org/2001/XMLSchema#decimal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="trailer-identifier"></a>
### Trailer Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/trailerIdentifier>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="transport-document-number"></a>
### Transport Document Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/transportDocumentNumber>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="transport-temperature"></a>
### Transport Temperature
- **IRI:** <https://iri.suomi.fi/model/ktddecv/transportTemperature>
- **Range:** <http://www.w3.org/2001/XMLSchema#decimal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="transshipment-allowed"></a>
### Transshipment Allowed
- **IRI:** <https://iri.suomi.fi/model/ktddecv/transshipmentAllowed>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="uic-station-code"></a>
### UIC Station Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/uicStationCode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="un-locode"></a>
### UN Locode
- **IRI:** <https://iri.suomi.fi/model/ktddecv/unlocode>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="un-number"></a>
### UN Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/unNumber>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="unit-code"></a>
### Unit Code
- **IRI:** <https://iri.suomi.fi/model/ktddecv/unitCode>
- **Description:** Unit of measure for non-monetary amounts (UCUM or UN/ECE Rec 20). Not used for money.
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="unit-price"></a>
### Unit Price
- **IRI:** <https://iri.suomi.fi/model/ktddecv/unitPrice>
- **Range:** <http://www.w3.org/2001/XMLSchema#float>
- **Subproperty of:** <https://gs1.org/voc/price>

<a id="value"></a>
### Value
- **IRI:** <https://iri.suomi.fi/model/ktddecv/value>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>
- **Equivalent to:** <https://iri.suomi.fi/model/busdoc/1.0.2/value>

<a id="vehicle-name"></a>
### Vehicle Name
- **IRI:** <https://iri.suomi.fi/model/ktddecv/vehicleName>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="vehicle-registration-identifier"></a>
### Vehicle Registration Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/vehicleRegistrationIdentifier>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="version-identifier"></a>
### Version Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/versionIdentifier>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="vessel-name"></a>
### Vessel Name
- **IRI:** <https://iri.suomi.fi/model/ktddecv/vesselName>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="voyage-number"></a>
### Voyage Number
- **IRI:** <https://iri.suomi.fi/model/ktddecv/voyageNumber>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>

<a id="warehouse-gln"></a>
### Warehouse GLN
- **IRI:** <https://iri.suomi.fi/model/ktddecv/warehouseGLN>
- **Range:** <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Subproperty of:** <http://www.w3.org/2002/07/owl#topDataProperty>
