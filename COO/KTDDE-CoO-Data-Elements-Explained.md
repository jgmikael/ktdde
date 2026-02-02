# KTDDE Certificate of Origin (CoO) — Data Elements Explained (Non‑Expert Guide)

This document explains, **data element by data element**, what a **KTDDE Certificate of Origin (CoO)** contains and **how / why** the information is modeled in the **KTDDE CoO SHACL Shape**.

It is written for:
- business stakeholders (trade, logistics, compliance)
- public authorities (customs, chambers of commerce)
- technical implementers who do **not** want to read RDF/Turtle

---

## 1. What is a Certificate of Origin (CoO)?

A **Certificate of Origin** is an official trade document stating **where the goods originate from** (the *origin* of the product), typically used for:
- customs clearance and tariff treatment (preferential / non-preferential origin)
- import compliance and documentary requirements
- risk and sanctions controls
- supply chain due diligence

In KTDDE, the CoO is modeled as a machine-readable data structure that can be used for:
- **Verifiable Credentials (VCs)** (e.g., in EU Business Wallets)
- automated checks (“is this shipment eligible for origin-based tariff reduction?”)
- cross-border interoperability across systems

---

## 2. How to read the modeling paths

Each data element below includes:
- **Meaning in CoO context**
- **How it is represented in the SHACL shape** (the “path”)
- **Why it is modeled that way**
- **Practical example** (realistic values)

Notation:
- `CertificateOfOrigin > property` = a direct field on the CoO
- `... > hasConsignment > Consignment > property` = nested information about the shipment
- `... > hasGoodsItem > GoodsItem > hasProduct > TradeProduct > property` = item/product-level detail

---

## 3. CoO Data elements (explained)

> The following list follows the KTDDE CoO trade document data elements.

---

### 3.1 Document Identifier

**What it means (business):**  
A general identifier for the CoO document in an information system. This can be an internal document ID, registry ID, or other tracking key.

**SHACL path:**  
`CertificateOfOrigin > ktddecv:documentIdentifier`

**Why modeled this way:**  
It’s a simple text-like identifier and does not need a separate object structure.

**Example:**  
`"COO-2026-000183"`

---

### 3.2 Purchase Order number

**What it means:**  
A reference to the buyer’s order that led to the shipment.

**SHACL path:**  
`CertificateOfOrigin > ktddecv:purchaseOrderNumber`

**Why modeled this way:**  
The PO number is an external reference that helps link the CoO to procurement and invoicing.

**Example:**  
`"PO-8872331"`

---

### 3.3 Documentary credit identifier

**What it means:**  
If the shipment is paid under a **Letter of Credit / Documentary Credit**, this identifies it.

**SHACL path:**  
`CertificateOfOrigin > ktddecv:creditIdentifier`

**Why modeled this way:**  
Trade finance workflows often require the CoO as a supporting document. Linking by ID enables automation.

**Example:**  
`"LC-DBFI-2026-00491"`

---

### 3.4 Transport Contract Document / Bill of Lading number

**What it means:**  
The transport contract reference (commonly the **Bill of Lading** in sea freight).

**SHACL path:**  
`CertificateOfOrigin > ktddecv:transportDocumentNumber`

**Why modeled this way:**  
The CoO often travels “with” the shipment documentation stack. This link is essential for tracking and compliance.

**Example:**  
`"MAEU123456789"`

---

### 3.5 Contract number

**What it means:**  
Reference to a sales contract or framework contract between exporter and importer.

**SHACL path:**  
`CertificateOfOrigin > ktddecv:contractNumber`

**Why modeled this way:**  
Some industries require the contract reference for audit and origin documentation.

**Example:**  
`"FRAME-2025-JP-GLULAM-01"`

---

### 3.6 Invoice number

**What it means:**  
The commercial invoice reference related to the goods.

**SHACL path:**  
`CertificateOfOrigin > ktddecv:invoiceNumber`

**Why modeled this way:**  
Import customs clearance frequently uses the invoice as the primary valuation document; CoO complements it.

**Example:**  
`"INV-2026-12049"`

---

### 3.7 Certificate of origin number

**What it means:**  
The official number on the issued CoO (often visible in the top header or reference box).

**SHACL path:**  
`CertificateOfOrigin > ktddecv:certificateNumber`

**Why modeled this way:**  
This is the primary “human-recognizable” identifier for the certificate.

**Example:**  
`"FI-CC-2026-0000198"`

---

### 3.8 Issue date

**What it means:**  
Date/time when the certificate was issued.

**SHACL path:**  
`CertificateOfOrigin > ktddecv:issueDate`

**Why modeled this way:**  
Validity and compliance checks depend on the issuance date (e.g., the certificate must be issued before export or within X days).

**Example:**  
`"2026-02-02T09:10:00+02:00"`

---

### 3.9 Importer

**What it means:**  
The company buying/importing the goods.

**SHACL path:**  
`CertificateOfOrigin > ktddecv:importerParty`

**Why modeled this way:**  
The CoO is typically presented by the importer at destination; linking the importer supports automated matching in customs systems.

**Example:**  
Importer name: `"Tokyo Timber Trading Co., Ltd."`

---

### 3.10 Exporter

**What it means:**  
The company exporting the goods (usually located in the origin country).

**SHACL path:**  
`CertificateOfOrigin > ktddecv:exporterParty`

**Why modeled this way:**  
Exporter identity is critical for trust and origin claim responsibility.

**Example:**  
Exporter name: `"Finnish Gluelam Mills Oy"`

---

### 3.11 Consignee

**What it means:**  
The party receiving the goods (may be different from importer, e.g., a warehouse operator).

**SHACL path:**  
`CertificateOfOrigin > ktddecv:consigneeParty`

**Why modeled this way:**  
In logistics, the consignee is often the operational receiver even when the importer is the legal declarant.

**Example:**  
`"Yokohama Distribution Center Ltd."`

---

### 3.12 Consignor

**What it means:**  
The party sending the goods (may be the exporter, or a logistics provider acting as shipper).

**SHACL path:**  
`CertificateOfOrigin > ktddecv:consignorParty`

**Why modeled this way:**  
It supports cases where the physical shipper differs from the contractual exporter.

**Example:**  
`"Nordic Freight Forwarding Oy"`

---

### 3.13 Permit/Certificate/Carnet issuer

**What it means:**  
The issuing party of the certificate in general terms (can overlap with issuing authority depending on the scheme).

**SHACL path:**  
`CertificateOfOrigin > ktddecv:issuerParty`

**Why modeled this way:**  
KTDDE models issuance as an explicit actor relationship, enabling credential trust chains.

**Example:**  
Issuer: `"Helsinki Chamber of Commerce"`

---

### 3.14 Management/Competent Authority (Issuing Authority)

**What it means:**  
The authority that has competence to issue/confirm origin.

**SHACL path:**  
`CertificateOfOrigin > ktddecv:issuingAuthorityParty`

**Why modeled this way:**  
A CoO is only credible when the authority is known and trusted.

**Example:**  
Authority: `"Finnish Chamber Network – Export Certification Unit"`

---

## 4. Shipment-level information (Consignment)

The CoO contains shipment-level facts via a nested **Consignment** structure.

---

### 4.1 Place of departure

**What it means:**  
Where the shipment leaves from (port, terminal, facility, etc.).

**SHACL path:**  
`CertificateOfOrigin > hasConsignment > Consignment > ktddecv:departurePlace`

**Why modeled this way:**  
Departure is part of the shipment context (not a property of the certificate itself).

**Example:**  
`"FIHEL" (Port of Helsinki)`

---

### 4.2 Origin country

**What it means:**  
The declared country of origin of the goods.

**SHACL path:**  
`CertificateOfOrigin > hasConsignment > Consignment > ktddecv:originCountry`

**Why modeled this way:**  
Origin is the core purpose of the CoO; it belongs to the consignment context.

**Example:**  
`"FI" (Finland)`

---

### 4.3 Gross weight

**What it means:**  
Total gross weight of the shipment (goods + packaging).

**SHACL path:**  
`... > Consignment > ktddecv:totalGrossWeight > Quantity > quantityValue / unitCode`

**Why modeled this way:**  
Weight is modeled as a **Quantity** object so that the numeric value and unit stay consistent and machine-checkable.

**Example:**  
- quantityValue: `18000.0`  
- unitCode: `"KGM"`

---

### 4.4 Net weight

**What it means:**  
Weight of the goods excluding packaging.

**SHACL path:**  
`... > Consignment > ktddecv:totalNetWeight > Quantity > quantityValue / unitCode`

**Why modeled this way:**  
Net weight is often required for customs or tariff calculations. Quantity modeling keeps units correct.

**Example:**  
- quantityValue: `17520.0`  
- unitCode: `"KGM"`

---

### 4.5 Number of packages

**What it means:**  
How many packages/handling units are shipped.

**SHACL path:**  
`... > Consignment > ktddecv:totalPackageCount > Quantity > quantityValue / unitCode`

**Why modeled this way:**  
Even counts are represented as Quantity for consistency across KTDDE.

**Example:**  
- quantityValue: `24`  
- unitCode: `"CT"` (cartons) or `"PK"`

---

### 4.6 Mode of transport

**What it means:**  
The transport mode used: sea, road, rail, air, etc.

**SHACL path:**  
`... > Consignment > ktddecv:transportModeCode`

**Why modeled this way:**  
This is typically a controlled code list concept (not free text), hence modeled as a “code” value.

**Example:**  
`"SEA"`

---

### 4.7 Shipping marks

**What it means:**  
Marks, numbers, labels printed on packages to identify them (often shown on cartons/pallets).

**SHACL path:**  
`... > Consignment > ktddecv:shippingMarks`

**Why modeled this way:**  
Shipping marks are logistics identifiers useful for matching physical goods to documentation.

**Example:**  
`"TTT-JP / GLULAM / LOT 2026-02"`

---

### 4.8 Type of packaging (UN/CEFACT coded)

**What it means:**  
The type of packaging used (e.g., pallet, crate, box, drum), ideally from a code list.

**SHACL path:**  
`... > Consignment > hasPackage > Package > ktddecv:packageTypeCode`

**Why modeled this way:**  
Packaging type belongs to a dedicated **Package** object, making it reusable across many KTDDE documents.

**Example:**  
`"PLT"` (pallet)

---

## 5. Goods line / item-level information

The CoO must describe what the goods actually are.

---

### 5.1 Description of goods

**What it means:**  
Human-readable description of the goods.

**SHACL path:**  
`... > Consignment > hasGoodsItem > GoodsItem > ktddecv:descriptionOfGoodsText`

**Why modeled this way:**  
CoO forms typically have a goods description section, often mandatory.

**Example:**  
`"Glued laminated timber beams (spruce), strength class GL28c"`

---

### 5.2 Product identifier

**What it means:**  
An identifier for the product (internal SKU, GTIN, etc.).

**SHACL path:**  
`... > GoodsItem > hasProduct > TradeProduct > ktddecv:productIdentifier`

**Why modeled this way:**  
Identifiers belong to the *product* itself, not the shipment. This supports reuse and automation.

**Example:**  
`"GLB-GL28C-120x360-12m"`

---

### 5.3 HS code / commodity code

**What it means:**  
The customs classification code for the product.

**SHACL path:**  
`... > GoodsItem > hasProduct > TradeProduct > ktddecv:commodityCode`

**Why modeled this way:**  
Commodity classification is a product property; this enables consistent classification across invoices, packing lists, etc.

**Example:**  
`"4418.90"`

---

## 6. Transport means and transport equipment (optional)

CoO sometimes includes transport details (especially in combined export documentation stacks).

---

### 6.1 Vehicle registration number

**What it means:**  
Registration ID of the vehicle carrying the shipment (typical in road transport).

**SHACL path:**  
`... > Consignment > usesTransportMeans > TransportMeans > ktddecv:vehicleRegistrationIdentifier`

**Why modeled this way:**  
Vehicle ID belongs to the transport means object.

**Example:**  
`"ABC-123"`

---

### 6.2 Transport equipment identifier

**What it means:**  
Identifier of transport equipment such as an ISO container.

**SHACL path (container-number approach):**  
`... > Consignment > hasTransportEquipment > TransportEquipment > ktddecv:containerNumber`

**Why modeled this way:**  
Container number is globally standardized and commonly used in international shipping.

**Example:**  
`"MSCU1234567"`

---

## 7. Summary: why the shape is structured this way

The KTDDE CoO SHACL uses a layered structure because it reflects real trade reality:

- **CertificateOfOrigin** = the document itself (issuance, references, parties)
- **Consignment** = the shipment context (origin, weights, packages, transport mode)
- **GoodsItem** = the goods lines being certified
- **TradeProduct** = the product identity/classification
- **TransportMeans / TransportEquipment / Package** = optional logistics detail objects

This makes the model:
- reusable across many KTDDE documents
- suitable for automation-first use cases (validation, risk checks, wallet-based presentation)
- semantically interoperable (KTDDE OWL + SHACL alignment)

---

## 8. Next steps (if you publish this on GitHub)

Recommended companion artifacts:
- the SHACL Turtle file (`.ttl`)
- a JSON Schema rendering (for non-RDF developers)
- a JSON-LD example instance (credentialSubject style)
- an SD-JWT or W3C VC wrapper example (depending on wallet architecture)

