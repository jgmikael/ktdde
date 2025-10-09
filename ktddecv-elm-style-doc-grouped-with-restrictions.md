# KTDDE Core Vocabulary — Documentation (Domain & Restriction Grouping)

## Classes and their Properties

### Additional Amount Category
- **IRI:** <https://iri.suomi.fi/model/ktddecv/AdditionalAmountCategory>

### Address
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Address>

### Advance Ruling Application
- **IRI:** <https://iri.suomi.fi/model/ktddecv/AdvanceRulingApplication>

### Air Cargo Manifest
- **IRI:** <https://iri.suomi.fi/model/ktddecv/AirCargoManifest>

### Air Waybill
- **IRI:** <https://iri.suomi.fi/model/ktddecv/AirWaybill>

#### Object Properties
_From OWL restrictions on this class:_
- **issuing carrier party** (<https://iri.suomi.fi/model/ktddecv/issuingCarrierParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **shipper party** (<https://iri.suomi.fi/model/ktddecv/shipperParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **consignee party** (<https://iri.suomi.fi/model/ktddecv/consigneeParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
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

#### Datatype Properties
_From OWL restrictions on this class:_
- **Master Air Waybill Number** (<https://iri.suomi.fi/model/ktddecv/masterAirWaybillNumber>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **House Air Waybill Number** (<https://iri.suomi.fi/model/ktddecv/houseAirWaybillNumber>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Issue Date** (<https://iri.suomi.fi/model/ktddecv/issueDate>) — some/all values from: <http://www.w3.org/2001/XMLSchema#dateTime>
- **Flight Number** (<https://iri.suomi.fi/model/ktddecv/flightNumber>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Flight Date** (<https://iri.suomi.fi/model/ktddecv/flightDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Handling Information** (<https://iri.suomi.fi/model/ktddecv/handlingInformation>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Allowance Charge
- **IRI:** <https://iri.suomi.fi/model/ktddecv/AllowanceCharge>

#### Object Properties
_From OWL restrictions on this class:_
- **has amount** (<https://iri.suomi.fi/model/ktddecv/hasAmount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
- **base amount** (<https://iri.suomi.fi/model/ktddecv/baseAmount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
- **per unit amount** (<https://iri.suomi.fi/model/ktddecv/perUnitAmount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
- **charged by party** (<https://iri.suomi.fi/model/ktddecv/chargedByParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **charged to party** (<https://iri.suomi.fi/model/ktddecv/chargedToParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Charge Indicator** (<https://iri.suomi.fi/model/ktddecv/chargeIndicator>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Allowance Charge Reason Code** (<https://iri.suomi.fi/model/ktddecv/allowanceChargeReasonCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Multiplier Factor Percent** (<https://iri.suomi.fi/model/ktddecv/multiplierFactorPercent>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Calculation Percent** (<https://iri.suomi.fi/model/ktddecv/calculationPercent>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Amount>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Amount Value** (<https://iri.suomi.fi/model/ktddecv/amountValue>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Unit Code** (<https://iri.suomi.fi/model/ktddecv/unitCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### ATA Carnet
- **IRI:** <https://iri.suomi.fi/model/ktddecv/ATACarnet>

### Availability Method
- **IRI:** <https://iri.suomi.fi/model/ktddecv/AvailabilityMethod>

### Availability Qualifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/AvailabilityQualifier>

### Bank
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Bank>

### Bank Account
- **IRI:** <https://iri.suomi.fi/model/ktddecv/BankAccount>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Bank Account Identifier** (<https://iri.suomi.fi/model/ktddecv/bankAccountIdentifier>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Bank Instruction
- **IRI:** <https://iri.suomi.fi/model/ktddecv/BankInstruction>

### Bill of Exchange
- **IRI:** <https://iri.suomi.fi/model/ktddecv/BillOfExchange>

#### Object Properties
_From OWL restrictions on this class:_
- **has tenor** (<https://iri.suomi.fi/model/ktddecv/hasTenor>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Tenor>

### Bill of Lading
- **IRI:** <https://iri.suomi.fi/model/ktddecv/BillOfLading>

### Business Document
- **IRI:** <https://iri.suomi.fi/model/ktddecv/BusinessDocument>

#### Object Properties
_From OWL restrictions on this class:_
- **document type** (<https://iri.suomi.fi/model/ktddecv/documentType>) — some/all values from: <http://www.w3.org/2004/02/skos/core#Concept>
- **has message** (<https://iri.suomi.fi/model/ktddecv/hasMessage>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Message>

### Business Event
- **IRI:** <https://iri.suomi.fi/model/ktddecv/BusinessEvent>

### Certificate of Origin
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CertificateOfOrigin>

#### Object Properties
_From OWL restrictions on this class:_
- **certificate number** (<https://iri.suomi.fi/model/ktddecv/certificateNumber>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Identifier>
- **issuing authority party** (<https://iri.suomi.fi/model/ktddecv/issuingAuthorityParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **preference criterion code** (<https://iri.suomi.fi/model/ktddecv/preferenceCriterionCode>) — some/all values from: <http://www.w3.org/2004/02/skos/core#Concept>
- **has goods item** (<https://iri.suomi.fi/model/ktddecv/hasGoodsItem>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/GoodsItem>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Issue Date** (<https://iri.suomi.fi/model/ktddecv/issueDate>) — some/all values from: <http://www.w3.org/2001/XMLSchema#dateTime>

### Characteristic
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Characteristic>

### CITES Permit
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CITESPermit>

#### Object Properties
_From OWL restrictions on this class:_
- **validity period** (<https://iri.suomi.fi/model/ktddecv/validityPeriod>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/PeriodOfTime>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Issue Date** (<https://iri.suomi.fi/model/ktddecv/issueDate>) — some/all values from: <http://www.w3.org/2001/XMLSchema#dateTime>
- **Issuing Authority** (<https://iri.suomi.fi/model/ktddecv/issuingAuthority>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Classification Scheme
- **IRI:** <https://iri.suomi.fi/model/ktddecv/ClassificationScheme>

### CODEX Official Certificate
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CODEXOfficialCertificate>

### Commercial Invoice
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CommercialInvoice>

#### Object Properties
_From OWL restrictions on this class:_
- **has invoicee** (<https://iri.suomi.fi/model/ktddecv/hasInvoicee>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **invoice document** (<https://iri.suomi.fi/model/ktddecv/invoiceDocument>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Document>
- **total amount** (<https://iri.suomi.fi/model/ktddecv/totalAmount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Amount>
- **invoice payment terms** (<https://iri.suomi.fi/model/ktddecv/invoicePaymentTerms>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/PaymentTerms>
- **invoicee party** (<https://iri.suomi.fi/model/ktddecv/invoiceeParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **has invoice line** (<https://iri.suomi.fi/model/ktddecv/hasInvoiceLine>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/InvoiceLine>
- **has delivery** (<https://iri.suomi.fi/model/ktddecv/hasDelivery>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Delivery>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Invoice Number** (<https://iri.suomi.fi/model/ktddecv/invoiceNumber>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Invoice Date** (<https://iri.suomi.fi/model/ktddecv/invoiceDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Payment Due Date** (<https://iri.suomi.fi/model/ktddecv/paymentDueDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Commodity Classification
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CommodityClassification>

#### Object Properties
_From OWL restrictions on this class:_
- **has classification scheme** (<https://iri.suomi.fi/model/ktddecv/hasClassificationScheme>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/ClassificationScheme>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Commodity Code** (<https://iri.suomi.fi/model/ktddecv/commodityCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Classification Code** (<https://iri.suomi.fi/model/ktddecv/classificationCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Communication Entity
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CommunicationEntity>

#### Object Properties
_From OWL restrictions on this class:_
- **sender party** (<https://iri.suomi.fi/model/ktddecv/senderParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **receiver party** (<https://iri.suomi.fi/model/ktddecv/receiverParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>

### Consignment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Consignment>

#### Object Properties
_From OWL restrictions on this class:_
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
- **place of discharge** (<https://iri.suomi.fi/model/ktddecv/placeOfDischarge>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Despatch Date** (<https://iri.suomi.fi/model/ktddecv/despatchDate>) — some/all values from: <http://www.w3.org/2001/XMLSchema#dateTime>
- **Delivery Date** (<https://iri.suomi.fi/model/ktddecv/deliveryDate>) — some/all values from: <http://www.w3.org/2001/XMLSchema#dateTime>

### Consignment Security Declaration
- **IRI:** <https://iri.suomi.fi/model/ktddecv/ConsignmentSecurityDeclaration>

### Contract
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Contract>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Contract Identifier** (<https://iri.suomi.fi/model/ktddecv/contractIdentifier>) — some/all values from: <http://www.w3.org/2001/XMLSchema#string>

### Country
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Country>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Country Name** (<https://iri.suomi.fi/model/ktddecv/countryName>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Country Code** (<https://iri.suomi.fi/model/ktddecv/countryCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Credit Availability
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CreditAvailability>

#### Object Properties
_From OWL restrictions on this class:_
- **has availability method** (<https://iri.suomi.fi/model/ktddecv/hasAvailabilityMethod>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/AvailabilityMethod>
- **available with party** (<https://iri.suomi.fi/model/ktddecv/availableWithParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **available with qualifier** (<https://iri.suomi.fi/model/ktddecv/availableWithQualifier>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/AvailabilityQualifier>
- **available at place** (<https://iri.suomi.fi/model/ktddecv/availableAtPlace>) — some/all values from: <https://iri.suomi.fi/model/ktddu/0.0.1/Place>
- **drawee party** (<https://iri.suomi.fi/model/ktddecv/draweeParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **obligor party** (<https://iri.suomi.fi/model/ktddecv/obligorParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **payee party** (<https://iri.suomi.fi/model/ktddecv/payeeParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **has amount** (<https://iri.suomi.fi/model/ktddecv/hasAmount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Maturity Date** (<https://iri.suomi.fi/model/ktddecv/maturityDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Customs Bond
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CustomsBond>

#### Object Properties
_From OWL restrictions on this class:_
- **surety party** (<https://iri.suomi.fi/model/ktddecv/suretyParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Bond Number** (<https://iri.suomi.fi/model/ktddecv/bondNumber>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Customs Declaration
- **IRI:** <https://iri.suomi.fi/model/ktddecv/CustomsDeclaration>

#### Object Properties
_From OWL restrictions on this class:_
- **declaration number** (<https://iri.suomi.fi/model/ktddecv/declarationNumber>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Identifier>
- **declarant party** (<https://iri.suomi.fi/model/ktddecv/declarantParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **exporter party** (<https://iri.suomi.fi/model/ktddecv/exporterParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **importer party** (<https://iri.suomi.fi/model/ktddecv/importerParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **consignee party** (<https://iri.suomi.fi/model/ktddecv/consigneeParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **customs procedure code ** (<https://iri.suomi.fi/model/ktddecv/customsProcedureCode>) — some/all values from: <http://www.w3.org/2004/02/skos/core#Concept>
- **total invoice amount** (<https://iri.suomi.fi/model/ktddecv/totalInvoiceAmount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
- **statistical value amount** (<https://iri.suomi.fi/model/ktddecv/statisticalValueAmount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
- **relates to invoice** (<https://iri.suomi.fi/model/ktddecv/relatesToInvoice>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/CommercialInvoice>
- **relates to transport document** (<https://iri.suomi.fi/model/ktddecv/relatesToTransportDocument>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/TransportDocument>
- **has goods item** (<https://iri.suomi.fi/model/ktddecv/hasGoodsItem>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/GoodsItem>
- **includes allowance charge** (<https://iri.suomi.fi/model/ktddecv/includesAllowanceCharge>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/AllowanceCharge>
- **includes duty tax fee** (<https://iri.suomi.fi/model/ktddecv/includesDutyTaxFee>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/DutyTaxFee>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Customs Office Code** (<https://iri.suomi.fi/model/ktddecv/customsOfficeCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Declaration Date** (<https://iri.suomi.fi/model/ktddecv/declarationDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Dangerous Goods
- **IRI:** <https://iri.suomi.fi/model/ktddecv/DangerousGoods>

#### Object Properties
_From OWL restrictions on this class:_
- **net quantity per package** (<https://iri.suomi.fi/model/ktddecv/netQuantityPerPackage>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Quantity>
- **inner packaging quantity** (<https://iri.suomi.fi/model/ktddecv/innerPackagingQuantity>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Quantity>

#### Datatype Properties
_From OWL restrictions on this class:_
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

#### Object Properties
_From OWL restrictions on this class:_
- **declaration number** (<https://iri.suomi.fi/model/ktddecv/declarationNumber>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Identifier>
- **declarant party** (<https://iri.suomi.fi/model/ktddecv/declarantParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **has goods item** (<https://iri.suomi.fi/model/ktddecv/hasGoodsItem>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/GoodsItem>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Declaration Date** (<https://iri.suomi.fi/model/ktddecv/declarationDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Delivery
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Delivery>

#### Object Properties
_From OWL restrictions on this class:_
- **delivery terms** (<https://iri.suomi.fi/model/ktddecv/deliveryTerms>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/TradeDeliveryTerms>
- **has shipment** (<https://iri.suomi.fi/model/ktddecv/hasShipment>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Shipment>

### Delivery Milestone
- **IRI:** <https://iri.suomi.fi/model/ktddecv/DeliveryMilestone>

#### Object Properties
_From OWL restrictions on this class:_
- **has shipment period** (<https://iri.suomi.fi/model/ktddecv/hasShipmentPeriod>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/PeriodOfTime>

### Document
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Document>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Document Identifier** (<https://iri.suomi.fi/model/ktddecv/documentIdentifier>) — some/all values from: <http://www.w3.org/2001/XMLSchema#string>
- **Document Date** (<https://iri.suomi.fi/model/ktddecv/documentDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Document Requirement
- **IRI:** <https://iri.suomi.fi/model/ktddecv/DocumentRequirement>

#### Object Properties
_From OWL restrictions on this class:_
- **required document type** (<https://iri.suomi.fi/model/ktddecv/requiredDocumentType>) — some/all values from: <http://www.w3.org/2004/02/skos/core#Concept>
- **issuer party** (<https://iri.suomi.fi/model/ktddecv/issuerParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Number of Originals** (<https://iri.suomi.fi/model/ktddecv/numberOfOriginals>) — some/all values from: <http://www.w3.org/2001/XMLSchema#integer>
- **Number of Copies** (<https://iri.suomi.fi/model/ktddecv/numberOfCopies>) — some/all values from: <http://www.w3.org/2001/XMLSchema#integer>

### Documentary Credit
- **IRI:** <https://iri.suomi.fi/model/ktddecv/DocumentaryCredit>

#### Object Properties
_From OWL restrictions on this class:_
- **has shipment** (<https://iri.suomi.fi/model/ktddecv/hasShipment>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Shipment>
- **applicant party** (<https://iri.suomi.fi/model/ktddecv/applicantParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **applicant bank party** (<https://iri.suomi.fi/model/ktddecv/applicantBankParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **applicable rules** (<https://iri.suomi.fi/model/ktddecv/applicableRules>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/RuleSet>
- **maximum credit amount** (<https://iri.suomi.fi/model/ktddecv/maximumCreditAmount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Amount>
- **issuing bank party** (<https://iri.suomi.fi/model/ktddecv/issuingBankParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **advising bank party** (<https://iri.suomi.fi/model/ktddecv/advisingBankParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **references pre advice** (<https://iri.suomi.fi/model/ktddecv/referencesPreAdvice>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Document>
- **place of expiry** (<https://iri.suomi.fi/model/ktddecv/placeOfExpiry>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>
- **covers additional charge** (<https://iri.suomi.fi/model/ktddecv/coversAdditionalCharge>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/AllowanceCharge>
- **additional amounts covered** (<https://iri.suomi.fi/model/ktddecv/additionalAmountsCovered>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/AdditionalAmountCategory>
- **has availability method** (<https://iri.suomi.fi/model/ktddecv/hasAvailabilityMethod>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/AvailabilityMethod>
- **drawee party** (<https://iri.suomi.fi/model/ktddecv/draweeParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **has payment line** (<https://iri.suomi.fi/model/ktddecv/hasPaymentLine>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/PaymentLine>
- **instruction to bank** (<https://iri.suomi.fi/model/ktddecv/instructionToBank>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/BankInstruction>
- **advise through bank party** (<https://iri.suomi.fi/model/ktddecv/adviseThroughBankParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **includes allowance charge** (<https://iri.suomi.fi/model/ktddecv/includesAllowanceCharge>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/AllowanceCharge>
- **has credit availability** (<https://iri.suomi.fi/model/ktddecv/hasCreditAvailability>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/CreditAvailability>
- **has delivery milestone** (<https://iri.suomi.fi/model/ktddecv/hasDeliveryMilestone>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/DeliveryMilestone>
- **has shipment period** (<https://iri.suomi.fi/model/ktddecv/hasShipmentPeriod>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/PeriodOfTime>
- **has presentation period** (<https://iri.suomi.fi/model/ktddecv/hasPresentationPeriod>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/PeriodOfTime>
- **presentation base event** (<https://iri.suomi.fi/model/ktddecv/presentationBaseEvent>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/ShipmentBasis>
- **confirmation instruction code** (<https://iri.suomi.fi/model/ktddecv/confirmationInstructionCode>) — some/all values from: <http://www.w3.org/2004/02/skos/core#Concept>
- **confirming party** (<https://iri.suomi.fi/model/ktddecv/confirmingParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **requested confirmation party** (<https://iri.suomi.fi/model/ktddecv/requestedConfirmationParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **has payment terms** (<https://iri.suomi.fi/model/ktddecv/hasPaymentTerms>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/PaymentTerms>
- **requires document** (<https://iri.suomi.fi/model/ktddecv/requiresDocument>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/DocumentRequirement>
- **place of presentation** (<https://iri.suomi.fi/model/ktddecv/placeOfPresentation>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>
- **reimbursing bank party** (<https://iri.suomi.fi/model/ktddecv/reimbursingBankParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **drafts at tenor** (<https://iri.suomi.fi/model/ktddecv/draftsAtTenor>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Tenor>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Issue Date** (<https://iri.suomi.fi/model/ktddecv/issueDate>) — some/all values from: <http://www.w3.org/2001/XMLSchema#dateTime>
- **Credit Identifier** (<https://iri.suomi.fi/model/ktddecv/creditIdentifier>) — some/all values from: <http://www.w3.org/2001/XMLSchema#string>
- **Expiry Date** (<https://iri.suomi.fi/model/ktddecv/expiryDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Latest Shipment Date** (<https://iri.suomi.fi/model/ktddecv/latestShipmentDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Partial Shipment Allowed** (<https://iri.suomi.fi/model/ktddecv/partialShipmentAllowed>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Transshipment Allowed** (<https://iri.suomi.fi/model/ktddecv/transshipmentAllowed>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Documentary Credit Type Code** (<https://iri.suomi.fi/model/ktddecv/documentaryCreditTypeCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Presentation Period Days** (<https://iri.suomi.fi/model/ktddecv/presentationPeriodDays>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Latest Presentation Date** (<https://iri.suomi.fi/model/ktddecv/latestPresentationDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Confirmation Added Date** (<https://iri.suomi.fi/model/ktddecv/confirmationAddedDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Credit Amount Tolerance Percentage** (<https://iri.suomi.fi/model/ktddecv/creditAmountTolerancePercentage>) — some/all values from: <http://www.w3.org/2001/XMLSchema#decimal>
- **Additional Conditions Text** (<https://iri.suomi.fi/model/ktddecv/additionalConditionsText>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Duty/Tax/Fee
- **IRI:** <https://iri.suomi.fi/model/ktddecv/DutyTaxFee>

### EMCS Document
- **IRI:** <https://iri.suomi.fi/model/ktddecv/EMCSDocument>

### Excise Guarantee
- **IRI:** <https://iri.suomi.fi/model/ktddecv/ExciseGuarantee>

### Export Import License
- **IRI:** <https://iri.suomi.fi/model/ktddecv/ExportImportLicense>

### Financial Document
- **IRI:** <https://iri.suomi.fi/model/ktddecv/FinancialDocument>

### Goods Item
- **IRI:** <https://iri.suomi.fi/model/ktddecv/GoodsItem>

#### Object Properties
_From OWL restrictions on this class:_
- **has country of origin** (<https://iri.suomi.fi/model/ktddecv/hasCountryOfOrigin>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Country>
- **has quantity** (<https://iri.suomi.fi/model/ktddecv/hasQuantity>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Quantity>
- **applied commodity classification** (<https://iri.suomi.fi/model/ktddecv/appliedCommodityClassification>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/CommodityClassification>
- **has dangerous goods details** (<https://iri.suomi.fi/model/ktddecv/hasDangerousGoodsDetails>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/DangerousGoods>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Product Identifier** (<https://iri.suomi.fi/model/ktddecv/productIdentifier>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Item Description Text** (<https://iri.suomi.fi/model/ktddecv/itemDescriptionText>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Description of Goods Text** (<https://iri.suomi.fi/model/ktddecv/descriptionOfGoodsText>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Identifier
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Identifier>

### Instruction
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Instruction>

#### Object Properties
_From OWL restrictions on this class:_
- **instructing party** (<https://iri.suomi.fi/model/ktddecv/instructingParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **instructed party** (<https://iri.suomi.fi/model/ktddecv/instructedParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Instruction Text** (<https://iri.suomi.fi/model/ktddecv/instructionText>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Insurance Certificate
- **IRI:** <https://iri.suomi.fi/model/ktddecv/InsuranceCertificate>

#### Object Properties
_From OWL restrictions on this class:_
- **insurer party** (<https://iri.suomi.fi/model/ktddecv/insurerParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **insured party** (<https://iri.suomi.fi/model/ktddecv/insuredParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **beneficiary party** (<https://iri.suomi.fi/model/ktddecv/beneficiaryParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **insured amount** (<https://iri.suomi.fi/model/ktddecv/insuredAmount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
- **coverage amount** (<https://iri.suomi.fi/model/ktddecv/coverageAmount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
- **coverage type code** (<https://iri.suomi.fi/model/ktddecv/coverageTypeCode>) — some/all values from: <http://www.w3.org/2004/02/skos/core#Concept>
- **claims payable at place** (<https://iri.suomi.fi/model/ktddecv/claimsPayableAtPlace>) — some/all values from: <https://iri.suomi.fi/model/ktddu/0.0.1/Place>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Insurance Terms Text** (<https://iri.suomi.fi/model/ktddecv/insuranceTermsText>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Insurance Policy Number** (<https://iri.suomi.fi/model/ktddecv/insurancePolicyNumber>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Invoice Line
- **IRI:** <https://iri.suomi.fi/model/ktddecv/InvoiceLine>

#### Object Properties
_From OWL restrictions on this class:_
- **describes trade product** (<https://iri.suomi.fi/model/ktddecv/describesTradeProduct>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/TradeProduct>
- **invoiced quantity** (<https://iri.suomi.fi/model/ktddecv/invoicedQuantity>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Quantity>
- **describes item** (<https://iri.suomi.fi/model/ktddecv/describesItem>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/TradeItem>

### Legal Entity
- **IRI:** <https://iri.suomi.fi/model/ktddecv/LegalEntity>

### Location
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Location>

#### Object Properties
_From OWL restrictions on this class:_
- **location country** (<https://iri.suomi.fi/model/ktddecv/locationCountry>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Country>
- **has identifier** (<https://iri.suomi.fi/model/ktddecv/hasIdentifier>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Identifier>
- **has Address** (<https://iri.suomi.fi/model/ktddecv/hasAddress>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/PostalAddress>

#### Datatype Properties
_From OWL restrictions on this class:_
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

#### Datatype Properties
_From OWL restrictions on this class:_
- **Message Subject** (<https://iri.suomi.fi/model/ktddecv/messageSubject>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Message Text** (<https://iri.suomi.fi/model/ktddecv/messageText>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Monetary Amount
- **IRI:** <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Amount Value** (<https://iri.suomi.fi/model/ktddecv/amountValue>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Currency Code** (<https://iri.suomi.fi/model/ktddecv/currencyCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Organic Inspection Certificate
- **IRI:** <https://iri.suomi.fi/model/ktddecv/OrganicInspectionCertificate>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Issue Date** (<https://iri.suomi.fi/model/ktddecv/issueDate>) — some/all values from: <http://www.w3.org/2001/XMLSchema#dateTime>

### Package
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Package>

#### Object Properties
_From OWL restrictions on this class:_
- **package type code** (<https://iri.suomi.fi/model/ktddecv/packageTypeCode>) — some/all values from: <http://www.w3.org/2004/02/skos/core#Concept>
- **sscc** (<https://iri.suomi.fi/model/ktddecv/sscc>) — some/all values from: <http://www.w3.org/2004/02/skos/core#Concept>
- **seal identifier** (<https://iri.suomi.fi/model/ktddecv/sealIdentifier>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Identifier>
- **has dangerous goods details** (<https://iri.suomi.fi/model/ktddecv/hasDangerousGoodsDetails>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/DangerousGoods>
- **has package item** (<https://iri.suomi.fi/model/ktddecv/hasPackageItem>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/PackageItem>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Package Count** (<https://iri.suomi.fi/model/ktddecv/packageCount>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Marks and Numbers Text** (<https://iri.suomi.fi/model/ktddecv/marksAndNumbersText>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Sealed Indicator** (<https://iri.suomi.fi/model/ktddecv/sealedIndicator>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Package Item
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PackageItem>

#### Object Properties
_From OWL restrictions on this class:_
- **for goods item** (<https://iri.suomi.fi/model/ktddecv/forGoodsItem>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/GoodsItem>

### Packing List
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PackingList>

#### Object Properties
_From OWL restrictions on this class:_
- **packing list number** (<https://iri.suomi.fi/model/ktddecv/packingListNumber>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Identifier>
- **has package** (<https://iri.suomi.fi/model/ktddecv/hasPackage>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Package>
- **total package count** (<https://iri.suomi.fi/model/ktddecv/totalPackageCount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Quantity>
- **total gross weight** (<https://iri.suomi.fi/model/ktddecv/totalGrossWeight>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Quantity>
- **total net weight** (<https://iri.suomi.fi/model/ktddecv/totalNetWeight>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Quantity>
- **relates to invoice** (<https://iri.suomi.fi/model/ktddecv/relatesToInvoice>)

### Party
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Party>

#### Object Properties
_From OWL restrictions on this class:_
- **party address** (<https://iri.suomi.fi/model/ktddecv/partyAddress>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Address>
- **party identifier** (<https://iri.suomi.fi/model/ktddecv/partyIdentifier>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Identifier>
- **party legal entity** (<https://iri.suomi.fi/model/ktddecv/partyLegalEntity>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/LegalEntity>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Name** (<https://iri.suomi.fi/model/ktddecv/name>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Payment Confirmation
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PaymentConfirmation>

### Payment Line
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PaymentLine>

#### Object Properties
_From OWL restrictions on this class:_
- **has amount** (<https://iri.suomi.fi/model/ktddecv/hasAmount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Amount>
- **payee party** (<https://iri.suomi.fi/model/ktddecv/payeeParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **payment settlement method** (<https://iri.suomi.fi/model/ktddecv/paymentSettlementMethod>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/AvailabilityMethod>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Payment Due Date** (<https://iri.suomi.fi/model/ktddecv/paymentDueDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Payment Schedule Line
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PaymentScheduleLine>

#### Object Properties
_From OWL restrictions on this class:_
- **has amount** (<https://iri.suomi.fi/model/ktddecv/hasAmount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
- **base amount** (<https://iri.suomi.fi/model/ktddecv/baseAmount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Amount Percent Of Base** (<https://iri.suomi.fi/model/ktddecv/amountPercentOfBase>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Payment Due Date** (<https://iri.suomi.fi/model/ktddecv/paymentDueDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Deferred Payment Date** (<https://iri.suomi.fi/model/ktddecv/deferredPaymentDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Payment Terms
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PaymentTerms>

#### Object Properties
_From OWL restrictions on this class:_
- **has payment schedule line** (<https://iri.suomi.fi/model/ktddecv/hasPaymentScheduleLine>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/PaymentScheduleLine>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Payment Term Code** (<https://iri.suomi.fi/model/ktddecv/paymentTermCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Period of Time
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PeriodOfTime>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Start Date** (<https://iri.suomi.fi/model/ktddecv/startDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **End Date** (<https://iri.suomi.fi/model/ktddecv/endDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Phytosanitary Certificate
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PhytosanitaryCertificate>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Botanical Details** (<https://iri.suomi.fi/model/ktddecv/botanicalDetails>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Postal Address
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PostalAddress>

### Presentation
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Presentation>

### Promissory Note
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PromissoryNote>

#### Object Properties
_From OWL restrictions on this class:_
- **drawer party** (<https://iri.suomi.fi/model/ktddecv/drawerParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **drawee party** (<https://iri.suomi.fi/model/ktddecv/draweeParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Note Number** (<https://iri.suomi.fi/model/ktddecv/noteNumber>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Maturity Date** (<https://iri.suomi.fi/model/ktddecv/maturityDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Purchase Order
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PurchaseOrder>

#### Object Properties
_From OWL restrictions on this class:_
- **buyer party** (<https://iri.suomi.fi/model/ktddecv/buyerParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **delivery party** (<https://iri.suomi.fi/model/ktddecv/deliveryParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **has delivery** (<https://iri.suomi.fi/model/ktddecv/hasDelivery>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Delivery>
- **invoicee party** (<https://iri.suomi.fi/model/ktddecv/invoiceeParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **order amount** (<https://iri.suomi.fi/model/ktddecv/orderAmount>)
- **seller party** (<https://iri.suomi.fi/model/ktddecv/sellerParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **includes allowance charge** (<https://iri.suomi.fi/model/ktddecv/includesAllowanceCharge>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/AllowanceCharge>
- **defines payment terms** (<https://iri.suomi.fi/model/ktddecv/definesPaymentTerms>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/PaymentTerms>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Order Identifier** (<https://iri.suomi.fi/model/ktddecv/orderIdentifier>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Order Date** (<https://iri.suomi.fi/model/ktddecv/orderDate>) — some/all values from: <http://www.w3.org/2001/XMLSchema#dateTime>

### Purchase Order Line
- **IRI:** <https://iri.suomi.fi/model/ktddecv/PurchaseOrderLine>

### Quantity  
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Quantity>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Unit Code** (<https://iri.suomi.fi/model/ktddecv/unitCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Quantity Value** (<https://iri.suomi.fi/model/ktddecv/quantityValue>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Rail Consignment Note CIM
- **IRI:** <https://iri.suomi.fi/model/ktddecv/RailConsignmentNoteCIM>

### Regulatory Certificate
- **IRI:** <https://iri.suomi.fi/model/ktddecv/RegulatoryCertificate>

### Road Consignment Note CMR
- **IRI:** <https://iri.suomi.fi/model/ktddecv/RoadConsignmentNoteCMR>

### Rule Set
- **IRI:** <https://iri.suomi.fi/model/ktddecv/RuleSet>

#### Object Properties
_From OWL restrictions on this class:_
- **publisher** (<https://iri.suomi.fi/model/ktddecv/publisher>)

#### Datatype Properties
_From OWL restrictions on this class:_
- **Rule Set Identifier** (<https://iri.suomi.fi/model/ktddecv/ruleSetIdentifier>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Title** (<https://iri.suomi.fi/model/ktddecv/title>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Version Identifier** (<https://iri.suomi.fi/model/ktddecv/versionIdentifier>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Publication Date** (<https://iri.suomi.fi/model/ktddecv/publicationDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Sea Cargo Manifest
- **IRI:** <https://iri.suomi.fi/model/ktddecv/SeaCargoManifest>

### Sea Waybill
- **IRI:** <https://iri.suomi.fi/model/ktddecv/SeaWaybill>

#### Object Properties
_From OWL restrictions on this class:_
- **carrier party** (<https://iri.suomi.fi/model/ktddecv/carrierParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **shipper party** (<https://iri.suomi.fi/model/ktddecv/shipperParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **consignee party** (<https://iri.suomi.fi/model/ktddecv/consigneeParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **notify party** (<https://iri.suomi.fi/model/ktddecv/notifyParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **place of receipt** (<https://iri.suomi.fi/model/ktddecv/placeOfReceipt>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>
- **place of loading** (<https://iri.suomi.fi/model/ktddecv/placeOfLoading>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>
- **place of discharge** (<https://iri.suomi.fi/model/ktddecv/placeOfDischarge>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>
- **freight payable at place** (<https://iri.suomi.fi/model/ktddecv/freightPayableAtPlace>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>
- **place of issue** (<https://iri.suomi.fi/model/ktddecv/placeOfIssue>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>
- **has goods item** (<https://iri.suomi.fi/model/ktddecv/hasGoodsItem>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/GoodsItem>
- **has package** (<https://iri.suomi.fi/model/ktddecv/hasPackage>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Package>
- **has transport equipment** (<https://iri.suomi.fi/model/ktddecv/hasTransportEquipment>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/TransportEquipment>
- **has dangerous goods** (<https://iri.suomi.fi/model/ktddecv/hasDangerousGoods>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/DangerousGoods>
- **total gross weight** (<https://iri.suomi.fi/model/ktddecv/totalGrossWeight>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Quantity>
- **freight charges amount** (<https://iri.suomi.fi/model/ktddecv/freightChargesAmount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>
- **other charges amount** (<https://iri.suomi.fi/model/ktddecv/otherChargesAmount>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/MonetaryAmount>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Sea Waybill Number** (<https://iri.suomi.fi/model/ktddecv/seaWaybillNumber>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Vessel Name** (<https://iri.suomi.fi/model/ktddecv/vesselName>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Voyage Number** (<https://iri.suomi.fi/model/ktddecv/voyageNumber>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Issue Date** (<https://iri.suomi.fi/model/ktddecv/issueDate>) — some/all values from: <http://www.w3.org/2001/XMLSchema#dateTime>

### Seal
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Seal>

### Shipment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Shipment>

#### Object Properties
_From OWL restrictions on this class:_
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

#### Datatype Properties
_From OWL restrictions on this class:_
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

### Ships Delivery Order
- **IRI:** <https://iri.suomi.fi/model/ktddecv/ShipsDeliveryOrder>

#### Object Properties
_From OWL restrictions on this class:_
- **carrier party** (<https://iri.suomi.fi/model/ktddecv/carrierParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **consignee party** (<https://iri.suomi.fi/model/ktddecv/consigneeParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **notify party** (<https://iri.suomi.fi/model/ktddecv/notifyParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **relates to transport document** (<https://iri.suomi.fi/model/ktddecv/relatesToTransportDocument>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/TransportDocument>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Ships Delivery Order Number** (<https://iri.suomi.fi/model/ktddecv/shipsDeliveryOrderNumber>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Status
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Status>

### Tenor
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Tenor>

### TIR Carnet
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TIRCarnet>

### Trade Delivery Terms
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TradeDeliveryTerms>

#### Object Properties
_From OWL restrictions on this class:_
- **incoterms code** (<https://iri.suomi.fi/model/ktddecv/incotermsCode>) — some/all values from: <http://www.w3.org/2004/02/skos/core#Concept>
- **applicable rules** (<https://iri.suomi.fi/model/ktddecv/applicableRules>) — some/all values from: <http://www.w3.org/2004/02/skos/core#Concept>
- **place of loading** (<https://iri.suomi.fi/model/ktddecv/placeOfLoading>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>
- **place of delivery** (<https://iri.suomi.fi/model/ktddecv/placeOfDelivery>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>
- **includes allowance charge** (<https://iri.suomi.fi/model/ktddecv/includesAllowanceCharge>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/AllowanceCharge>
- **relates to consignment** (<https://iri.suomi.fi/model/ktddecv/relatesToConsignment>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Consignment>
- **has delivery period** (<https://iri.suomi.fi/model/ktddecv/hasDeliveryPeriod>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/PeriodOfTime>
- **place of discharge** (<https://iri.suomi.fi/model/ktddecv/placeOfDischarge>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Delivery Terms Text** (<https://iri.suomi.fi/model/ktddecv/deliveryTermsText>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Trade Item
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TradeItem>

### Trade Line Item
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TradeLineItem>

### Trade Product
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TradeProduct>

#### Object Properties
_From OWL restrictions on this class:_
- **origin country** (<https://iri.suomi.fi/model/ktddecv/originCountry>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Country>
- **applicable commodity classification** (<https://iri.suomi.fi/model/ktddecv/applicableCommodityClassification>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/CommodityClassification>
- **has characteristic** (<https://iri.suomi.fi/model/ktddecv/hasCharacteristic>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Characteristic>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Product Name** (<https://iri.suomi.fi/model/ktddecv/productName>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Product Description** (<https://iri.suomi.fi/model/ktddecv/productDescription>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Transit Accompanying Document
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TransitAccompanyingDocument>

#### Object Properties
_From OWL restrictions on this class:_
- **office of departure** (<https://iri.suomi.fi/model/ktddecv/officeOfDeparture>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>
- **office of destination** (<https://iri.suomi.fi/model/ktddecv/officeOfDestination>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>
- **transit office** (<https://iri.suomi.fi/model/ktddecv/transitOffice>)

#### Datatype Properties
_From OWL restrictions on this class:_
- **MRN** (<https://iri.suomi.fi/model/ktddecv/mrn>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Transport Document
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TransportDocument>

#### Object Properties
_From OWL restrictions on this class:_
- **transport document type code** (<https://iri.suomi.fi/model/ktddecv/transportDocumentTypeCode>) — some/all values from: <http://www.w3.org/2004/02/skos/core#Concept>
- **carrier party** (<https://iri.suomi.fi/model/ktddecv/carrierParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **shipper party** (<https://iri.suomi.fi/model/ktddecv/shipperParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **consignee party** (<https://iri.suomi.fi/model/ktddecv/consigneeParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **notify party** (<https://iri.suomi.fi/model/ktddecv/notifyParty>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Party>
- **place of issue** (<https://iri.suomi.fi/model/ktddecv/placeOfIssue>) — some/all values from: <https://iri.suomi.fi/model/ktddu/0.0.1/Place>
- **freight payable at place** (<https://iri.suomi.fi/model/ktddecv/freightPayableAtPlace>) — some/all values from: <https://iri.suomi.fi/model/ktddu/0.0.1/Place>
- **relates to consignment** (<https://iri.suomi.fi/model/ktddecv/relatesToConsignment>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Consignment>
- **has package** (<https://iri.suomi.fi/model/ktddecv/hasPackage>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Package>
- **has goods item** (<https://iri.suomi.fi/model/ktddecv/hasGoodsItem>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/GoodsItem>
- **place of loading** (<https://iri.suomi.fi/model/ktddecv/placeOfLoading>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>
- **place of delivery** (<https://iri.suomi.fi/model/ktddecv/placeOfDelivery>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Issue Date** (<https://iri.suomi.fi/model/ktddecv/issueDate>) — some/all values from: <http://www.w3.org/2001/XMLSchema#dateTime>
- **Number of Originals** (<https://iri.suomi.fi/model/ktddecv/numberOfOriginals>) — some/all values from: <http://www.w3.org/2001/XMLSchema#integer>
- **On Board Date** (<https://iri.suomi.fi/model/ktddecv/onBoardDate>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Vessel Name** (<https://iri.suomi.fi/model/ktddecv/vesselName>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Voyage Number** (<https://iri.suomi.fi/model/ktddecv/voyageNumber>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Transport Document Number** (<https://iri.suomi.fi/model/ktddecv/transportDocumentNumber>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Freight Payment Term Code** (<https://iri.suomi.fi/model/ktddecv/freightPaymentTermCode>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Transport Equipment
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TransportEquipment>

#### Object Properties
_From OWL restrictions on this class:_
- **equipment identifier** (<https://iri.suomi.fi/model/ktddecv/equipmentIdentifier>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Identifier>

### Transport Event
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TransportEvent>

#### Object Properties
_From OWL restrictions on this class:_
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

#### Datatype Properties
_From OWL restrictions on this class:_
- **Event Date Time** (<https://iri.suomi.fi/model/ktddecv/eventDateTime>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Event Note Text** (<https://iri.suomi.fi/model/ktddecv/eventNoteText>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Transport Leg
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TransportLeg>

#### Object Properties
_From OWL restrictions on this class:_
- **uses transport equipment** (<https://iri.suomi.fi/model/ktddecv/usesTransportEquipment>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/TransportEquipment>
- **departure place** (<https://iri.suomi.fi/model/ktddecv/departurePlace>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>
- **arrival place** (<https://iri.suomi.fi/model/ktddecv/arrivalPlace>) — some/all values from: <https://iri.suomi.fi/model/ktddecv/Location>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Departure Date Time** (<https://iri.suomi.fi/model/ktddecv/departureDateTime>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Arrival Date Time** (<https://iri.suomi.fi/model/ktddecv/arrivalDateTime>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Transport Means
- **IRI:** <https://iri.suomi.fi/model/ktddecv/TransportMeans>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Vehicle Name** (<https://iri.suomi.fi/model/ktddecv/vehicleName>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **IMO Ship ID** (<https://iri.suomi.fi/model/ktddecv/iMOShipID>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>
- **Flight Number** (<https://iri.suomi.fi/model/ktddecv/flightNumber>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Veterinary Certificate
- **IRI:** <https://iri.suomi.fi/model/ktddecv/VeterinaryCertificate>

#### Datatype Properties
_From OWL restrictions on this class:_
- **Origin Establishment** (<https://iri.suomi.fi/model/ktddecv/originEstablishment>) — some/all values from: <http://www.w3.org/2000/01/rdf-schema#Literal>

### Warehouse
- **IRI:** <https://iri.suomi.fi/model/ktddecv/Warehouse>

### Warehouse Receipt
- **IRI:** <https://iri.suomi.fi/model/ktddecv/WarehouseReceipt>

## Unlinked Properties
Properties without an explicit rdfs:domain (not counting their appearance in class restrictions).

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