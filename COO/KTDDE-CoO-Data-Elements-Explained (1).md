# KTDDE Certificate of Origin (CoO) — Data Elements Explained (Non-Expert Guide)

This document explains, **data element by data element**, what a **KTDDE Certificate of Origin (CoO)** contains and **how / why** the information is modeled in the **KTDDE CoO SHACL Shape**.

It is written for:
- business stakeholders (trade, logistics, compliance)
- public authorities (customs, chambers of commerce)
- technical implementers who do **not** want to read RDF/Turtle

---

## 1) What is a Certificate of Origin (CoO)?

A **Certificate of Origin (CoO)** is an official trade document stating **where the goods originate from** (the origin of the product), typically used for:
- customs clearance and tariff treatment (preferential / non-preferential origin)
- import compliance and documentary requirements
- risk, sanctions, and due diligence controls
- trade finance documentary checking (when required)

In KTDDE, the CoO is modeled as a machine-readable data structure that can be used for:
- **Verifiable Credentials (VCs)** (e.g., in EU Business Wallets)
- automated checks (“is this shipment eligible for origin-based treatment?”)
- cross-border interoperability across systems and actors

---

## 2) How to read the SHACL paths

Each data element below includes:
- **Meaning in CoO context**
- **Full SHACL path** (including intermediate classes whenever the structure is nested)
- **Why it is modeled that way**
- **Practical example** (realistic values)

### Path notation (always complete)
- `Class > property` = direct value on the class
- `Class > property > RangeClass > property` = nested value on a linked object
- Where needed, paths go deeper (e.g., `... > Quantity > quantityValue`)

---

## 3) CoO data elements (explained)

> The following list follows the KTDDE CoO trade document data elements.

---

### 3.1 Document Identifier

**Meaning (business):**  
A general identifier for the CoO document in an information system. This can be an internal document ID, registry ID, or other tracking key.

**Full SHACL path:**  
`dsicoc:CertificateOfOrigin > ktddecv:documentIdentifier`

**Why modeled this way:**  
This is a simple text identifier and does not need a separate object structure.

**Practical example:**  
`"COO-2026-000183"`

---

### 3.2 Purchase Order number

**Meaning:**  
A reference to the buyer’s order that triggered the shipment.

**Full SHACL path:**  
`dsicoc:CertificateOfOrigin > ktddecv:purchaseOrderNumber`

**Why modeled this way:**  
Purchase Orders connect the CoO to procurement and contractual trade flows.

**Example:**  
`"PO-8872331"`

---

### 3.3 Documentary credit identifier

**Meaning:**  
If the shipment is paid under a **Letter of Credit / Documentary Credit**, this identifies it.

**Full SHACL path:**  
`dsicoc:CertificateOfOrigin > ktddecv:creditIdentifier`

**Why modeled this way:**  
Trade finance workflows often require a CoO as a supporting document; this supports automatic matching.

**Example:**  
`"LC-DBFI-2026-00491"`

---

### 3.4 Transport Contract Document / Bill of Lading number

**Meaning:**  
The transport contract reference (often the **Bill of Lading** in sea freight).

**Full SHACL path:**  
`dsicoc:CertificateOfOrigin > ktddecv:transportDocumentNumber`

**Why modeled this way:**  
The CoO must be linkable to the shipment transport documentation stack.

**Example:**  
`"MAEU123456789"`

---

### 3.5 Contract number

**Meaning:**  
Reference to a sales contract or framework agreement between exporter and importer.

**Full SHACL path:**  
`dsicoc:CertificateOfOrigin > ktddecv:contractNumber`

**Why modeled this way:**  
Some trade flows require contract traceability for audit/origin evidence.

**Example:**  
`"FRAME-2025-JP-GLULAM-01"`

---

### 3.6 Invoice number

**Meaning:**  
The commercial invoice reference related to the goods.

**Full SHACL path:**  
`dsicoc:CertificateOfOrigin > ktddecv:invoiceNumber`

**Why modeled this way:**  
Customs clearance and payment controls often require invoice-to-CoO linkage.

**Example:**  
`"INV-2026-12049"`

---

### 3.7 Certificate of origin number

**Meaning:**  
The official number printed on the issued CoO.

**Full SHACL path:**  
`dsicoc:CertificateOfOrigin > ktddecv:certificateNumber`

**Why modeled this way:**  
This is the primary reference used by humans and systems when verifying the certificate.

**Example:**  
`"FI-CC-2026-0000198"`

---

### 3.8 Issue date

**Meaning:**  
Date/time when the certificate was issued.

**Full SHACL path:**  
`dsicoc:CertificateOfOrigin > ktddecv:issueDate`

**Why modeled this way:**  
The issue date is essential for validity checks and regulatory timing requirements.

**Example:**  
`"2026-02-02T09:10:00+02:00"`

---

## 4) Parties (who is involved)

Parties are modeled as linked objects (Party nodes), because party data in trade is reusable across many documents.

---

### 4.1 Importer

**Meaning:**  
The company that imports/buys the goods (in destination country).

**Full SHACL path:**  
`dsicoc:CertificateOfOrigin > ktddecv:importerParty`

**Why modeled this way:**  
Importer identity supports customs matching and compliance checks.

**Example:**  
`"Tokyo Timber Trading Co., Ltd."`

---

### 4.2 Exporter

**Meaning:**  
The company exporting the goods (typically in the origin country).

**Full SHACL path:**  
`dsicoc:CertificateOfOrigin > ktddecv:exporterParty`

**Why modeled this way:**  
The exporter is the responsible declarant of origin in many schemes.

**Example:**  
`"Finnish Gluelam Mills Oy"`

---

### 4.3 Consignee

**Meaning:**  
The party receiving the goods (may differ from the importer).

**Full SHACL path:**  
`dsicoc:CertificateOfOrigin > ktddecv:consigneeParty`

**Why modeled this way:**  
Consignee is operationally important in logistics, warehousing, and delivery chains.

**Example:**  
`"Yokohama Distribution Center Ltd."`

---

### 4.4 Consignor

**Meaning:**  
The party sending the goods (may differ from exporter in operational terms).

**Full SHACL path:**  
`dsicoc:CertificateOfOrigin > ktddecv:consignorParty`

**Why modeled this way:**  
Supports freight-forwarder or third-party shipper scenarios.

**Example:**  
`"Nordic Freight Forwarding Oy"`

---

### 4.5 Permit/Certificate/Carnet issuer

**Meaning:**  
The party that issues the certificate (e.g., Chamber of Commerce).

**Full SHACL path:**  
`dsicoc:CertificateOfOrigin > ktddecv:issuerParty`

**Why modeled this way:**  
Issuance actor is a trust anchor in VC and digital compliance workflows.

**Example:**  
`"Helsinki Chamber of Commerce"`

---

### 4.6 Management/Competent Authority (Issuing Authority)

**Meaning:**  
The competent authority responsible for issuing/confirming origin.

**Full SHACL path:**  
`dsicoc:CertificateOfOrigin > ktddecv:issuingAuthorityParty`

**Why modeled this way:**  
A CoO is credible only when the issuing authority is identifiable and trusted.

**Example:**  
`"Finnish Chamber Network – Export Certification Unit"`

---

## 5) Shipment-level information (Consignment)

The CoO includes shipment-level facts via a nested **Consignment** structure.

---

### 5.1 Place of departure

**Meaning:**  
Where the shipment departs from (port, terminal, facility).

**Full SHACL path:**  
`dsicoc:CertificateOfOrigin > ktddecv:hasConsignment > dsicoc:Consignment > ktddecv:departurePlace`

**Why modeled this way:**  
Departure is part of the shipment context, not a property of the certificate itself.

**Example:**  
`"FIHEL" (Port of Helsinki)`

---

### 5.2 Origin country

**Meaning:**  
The declared origin country of the goods.

**Full SHACL path:**  
`dsicoc:CertificateOfOrigin > ktddecv:hasConsignment > dsicoc:Consignment > ktddecv:originCountry`

**Why modeled this way:**  
This is the core purpose of the CoO and belongs in the consignment context.

**Example:**  
`"FI" (Finland)`

---

### 5.3 Gross weight

**Meaning:**  
Total gross weight of the shipment (goods + packaging).

**Full SHACL path:**  
`dsicoc:CertificateOfOrigin > ktddecv:hasConsignment > dsicoc:Consignment > ktddecv:totalGrossWeight > ktddecv:Quantity > ktddecv:quantityValue`  
and  
`dsicoc:CertificateOfOrigin > ktddecv:hasConsignment > dsicoc:Consignment > ktddecv:totalGrossWeight > ktddecv:Quantity > ktddecv:unitCode`

**Why modeled this way:**  
Weight is modeled as a `Quantity` object so numeric value and unit are always unambiguous.

**Example:**  
- quantityValue: `18000.0`  
- unitCode: `"KGM"`

---

### 5.4 Net weight

**Meaning:**  
Net weight of the goods excluding packaging.

**Full SHACL path:**  
`dsicoc:CertificateOfOrigin > ktddecv:hasConsignment > dsicoc:Consignment > ktddecv:totalNetWeight > ktddecv:Quantity > ktddecv:quantityValue`  
and  
`dsicoc:CertificateOfOrigin > ktddecv:hasConsignment > dsicoc:Consignment > ktddecv:totalNetWeight > ktddecv:Quantity > ktddecv:unitCode`

**Why modeled this way:**  
Some regulatory/tariff logic depends on net weight, which must be machine-checkable.

**Example:**  
- quantityValue: `17520.0`  
- unitCode: `"KGM"`

---

### 5.5 Number of packages

**Meaning:**  
How many packages/handling units are shipped.

**Full SHACL path:**  
`dsicoc:CertificateOfOrigin > ktddecv:hasConsignment > dsicoc:Consignment > ktddecv:totalPackageCount > ktddecv:Quantity > ktddecv:quantityValue`  
and  
`dsicoc:CertificateOfOrigin > ktddecv:hasConsignment > dsicoc:Consignment > ktddecv:totalPackageCount > ktddecv:Quantity > ktddecv:unitCode`

**Why modeled this way:**  
Counts are also quantities in KTDDE; this keeps a single modeling pattern across documents.

**Example:**  
- quantityValue: `24`  
- unitCode: `"CT"` (cartons) or `"PK"` (packages)

---

### 5.6 Mode of transport

**Meaning:**  
The transport mode: sea, road, rail, air, etc.

**Full SHACL path:**  
`dsicoc:CertificateOfOrigin > ktddecv:hasConsignment > dsicoc:Consignment > ktddecv:transportModeCode`

**Why modeled this way:**  
Mode codes are typically controlled values (code lists), enabling automated logic (“sea freight” vs “air freight”).

**Example:**  
`"SEA"`

---

### 5.7 Shipping marks

**Meaning:**  
Marks/numbers printed on packages used to identify them.

**Full SHACL path:**  
`dsicoc:CertificateOfOrigin > ktddecv:hasConsignment > dsicoc:Consignment > ktddecv:shippingMarks`

**Why modeled this way:**  
Shipping marks support matching physical goods with documentation.

**Example:**  
`"TTT-JP / GLULAM / LOT 2026-02"`

---

## 6) Packaging details (Package)

Packaging details are modeled using a **Package object**, enabling reuse across multiple KTDDE trade documents.

---

### 6.1 Type of packaging (UN/CEFACT coded)

**Meaning:**  
Package type such as pallet, crate, box, drum (ideally from a controlled code list).

**Full SHACL path:**  
`dsicoc:CertificateOfOrigin > ktddecv:hasConsignment > dsicoc:Consignment > ktddecv:hasPackage > ktddecv:Package > ktddecv:packageTypeCode`

**Why modeled this way:**  
Package type is a property of the **package itself**, and KTDDE OWL explicitly provides a `Package` class for this.

**Example:**  
`"PLT"` (pallet)

---

## 7) Goods and product information

CoO must describe *what* goods the origin applies to. This is represented through `GoodsItem` and `TradeProduct`.

---

### 7.1 Description of goods

**Meaning:**  
Human-readable description of the goods.

**Full SHACL path:**  
`dsicoc:CertificateOfOrigin > ktddecv:hasConsignment > dsicoc:Consignment > ktddecv:hasGoodsItem > dsicoc:GoodsItem > ktddecv:descriptionOfGoodsText`

**Why modeled this way:**  
CoO forms always include a goods description section; it is the primary human-readable anchor.

**Example:**  
`"Glued laminated timber beams (spruce), strength class GL28c"`

---

### 7.2 Product identifier

**Meaning:**  
Identifier for the product (SKU, GTIN, internal product ID).

**Full SHACL path:**  
`dsicoc:CertificateOfOrigin > ktddecv:hasConsignment > dsicoc:Consignment > ktddecv:hasGoodsItem > dsicoc:GoodsItem > ktddecv:hasProduct > ktddecv:TradeProduct > ktddecv:productIdentifier`

**Why modeled this way:**  
Identifiers belong to the product itself, not the shipment, enabling reuse across invoices, packing lists, etc.

**Example:**  
`"GLB-GL28C-120x360-12m"`

---

### 7.3 HS code / commodity code

**Meaning:**  
Customs classification code for the product.

**Full SHACL path:**  
`dsicoc:CertificateOfOrigin > ktddecv:hasConsignment > dsicoc:Consignment > ktddecv:hasGoodsItem > dsicoc:GoodsItem > ktddecv:hasProduct > ktddecv:TradeProduct > ktddecv:commodityCode`

**Why modeled this way:**  
Classification is a property of the product and should remain consistent across documents (invoice lines, packing lists, etc).

**Example:**  
`"4418.90"`

---

## 8) Transport means and transport equipment (optional)

Transport details are optional in many CoO layouts but often present in digital trade stacks.

---

### 8.1 Vehicle registration number

**Meaning:**  
Registration ID of the vehicle (road transport scenario).

**Full SHACL path:**  
`dsicoc:CertificateOfOrigin > ktddecv:hasConsignment > dsicoc:Consignment > ktddecv:usesTransportMeans > ktddecv:TransportMeans > ktddecv:vehicleRegistrationIdentifier`

**Why modeled this way:**  
Transport means identifiers belong to the transport means object.

**Example:**  
`"ABC-123"`

---

### 8.2 Transport equipment identifier (e.g., container)

**Meaning:**  
Identifier for transport equipment such as an ISO container.

**Full SHACL path:**  
`dsicoc:CertificateOfOrigin > ktddecv:hasConsignment > dsicoc:Consignment > ktddecv:hasTransportEquipment > ktddecv:TransportEquipment > ktddecv:containerNumber`

**Why modeled this way:**  
Container numbers are globally standardized and crucial for matching shipment tracking and documentation.

**Example:**  
`"MSCU1234567"`

---

## 9) Summary: why KTDDE models CoO this way

The KTDDE CoO SHACL uses a layered structure to match real trade reality:

- **CertificateOfOrigin** = the document itself (issuance, references, parties)
- **Consignment** = shipment context (origin, weights, transport mode, marks)
- **Package** = packaging type (reusable across documents)
- **GoodsItem** = goods lines being certified
- **TradeProduct** = product identity/classification
- **TransportMeans / TransportEquipment** = optional transport objects

This makes the model:
- reusable across the wider KTDDE ecosystem
- suitable for automation-first processing (validation and business rules)
- semantically interoperable (KTDDE OWL + SHACL alignment)

---

## 10) Suggested GitHub publication bundle

Recommended companion artifacts:
- the SHACL Turtle file (`.ttl`)
- a JSON Schema rendering (for non-RDF developers)
- a JSON-LD example instance (credentialSubject-style)
- a W3C VC wrapper example (wallet presentation)
