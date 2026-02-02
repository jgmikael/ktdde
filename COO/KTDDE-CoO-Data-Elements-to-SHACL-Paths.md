# KTDDE Certificate of Origin (CoO) — Data Elements to SHACL Paths (Table)

This table lists the **KTDDE CoO trade document data elements** and the **equivalent SHACL path** used in the CoO SHACL model.

Notes:
- Paths use the shorthand prefixes used in your artifacts (e.g., `dsicoc:` and `ktddecv:`).
- For nested structures, the full chain is shown: `Class > property > RangeClass > property`.
- When one CSV row contains two distinct elements, the table shows two paths separated by `|`.

---

| KTDDE data element (CSV) | Equivalent SHACL path |
|---|---|
| Document Identifier | dsicoc:CertificateOfOrigin > ktddecv:documentIdentifier |
| Purchase Order number | dsicoc:CertificateOfOrigin > ktddecv:purchaseOrderNumber |
| Documentary credit identifier | dsicoc:CertificateOfOrigin > ktddecv:creditIdentifier |
| Transport Contract Document / Bill of Lading number | dsicoc:CertificateOfOrigin > ktddecv:transportDocumentNumber |
| Contract number | dsicoc:CertificateOfOrigin > ktddecv:contractNumber |
| Invoice number | dsicoc:CertificateOfOrigin > ktddecv:invoiceNumber |
| Certificate of origin number | dsicoc:CertificateOfOrigin > ktddecv:certificateNumber |
| Issue date | dsicoc:CertificateOfOrigin > ktddecv:issueDate |
| Importer | dsicoc:CertificateOfOrigin > ktddecv:importerParty > ktddecv:Party |
| Exporter | dsicoc:CertificateOfOrigin > ktddecv:exporterParty > ktddecv:Party |
| Consignee | dsicoc:CertificateOfOrigin > ktddecv:consigneeParty > ktddecv:Party |
| Consignor | dsicoc:CertificateOfOrigin > ktddecv:consignorParty > ktddecv:Party |
| Permit/Certificate/Carnet issuer | dsicoc:CertificateOfOrigin > ktddecv:issuerParty > ktddecv:Party |
| Management/Competent Authority | dsicoc:CertificateOfOrigin > ktddecv:issuingAuthorityParty > ktddecv:Party |
| Place or departure | dsicoc:CertificateOfOrigin > ktddecv:hasConsignment > dsicoc:Consignment > ktddecv:departurePlace > ktddecv:Location |
| Origin country | dsicoc:CertificateOfOrigin > ktddecv:hasConsignment > dsicoc:Consignment > ktddecv:originCountry > ktddecv:Country |
| Gross weight | dsicoc:CertificateOfOrigin > ktddecv:hasConsignment > dsicoc:Consignment > ktddecv:totalGrossWeight > ktddecv:Quantity > ktddecv:quantityValue / ktddecv:unitCode |
| Net weight | dsicoc:CertificateOfOrigin > ktddecv:hasConsignment > dsicoc:Consignment > ktddecv:totalNetWeight > ktddecv:Quantity > ktddecv:quantityValue / ktddecv:unitCode |
| Transport Means, gross weight | dsicoc:CertificateOfOrigin > ktddecv:hasConsignment > dsicoc:Consignment > ktddecv:usesTransportMeans > ktddecv:TransportMeans > ktddecv:transportMeansGrossWeight > ktddecv:Quantity > ktddecv:quantityValue / ktddecv:unitCode |
| Description of Goods | dsicoc:CertificateOfOrigin > ktddecv:hasConsignment > dsicoc:Consignment > ktddecv:hasGoodsItem > dsicoc:GoodsItem > ktddecv:descriptionOfGoodsText |
| Number of Packages | dsicoc:CertificateOfOrigin > ktddecv:hasConsignment > dsicoc:Consignment > ktddecv:totalPackageCount > ktddecv:Quantity > ktddecv:quantityValue / ktddecv:unitCode |
| Type of Packaging (UNCEFACT coded) and shipping marks | dsicoc:CertificateOfOrigin > ktddecv:hasConsignment > dsicoc:Consignment > ktddecv:hasPackage > ktddecv:Package > ktddecv:packageTypeCode  |  dsicoc:... > ktddecv:hasPackage > ktddecv:Package > ktddecv:shippingMarks |
| Shipping Marks | dsicoc:CertificateOfOrigin > ktddecv:hasConsignment > dsicoc:Consignment > ktddecv:shippingMarks |
| Product identifier | dsicoc:CertificateOfOrigin > ktddecv:hasConsignment > dsicoc:Consignment > ktddecv:hasGoodsItem > dsicoc:GoodsItem > ktddecv:hasProduct > ktddecv:TradeProduct > ktddecv:productIdentifier |
| HS Code (Commodity Code) | dsicoc:CertificateOfOrigin > ktddecv:hasConsignment > dsicoc:Consignment > ktddecv:hasGoodsItem > dsicoc:GoodsItem > ktddecv:hasProduct > ktddecv:TradeProduct > ktddecv:commodityCode |
| Mode of Transport | dsicoc:CertificateOfOrigin > ktddecv:hasConsignment > dsicoc:Consignment > ktddecv:transportModeCode |
| Container size and type | dsicoc:CertificateOfOrigin > ktddecv:hasConsignment > dsicoc:Consignment > ktddecv:hasTransportEquipment > ktddecv:TransportEquipment > ktddecv:containerSizeTypeCode |
| Transport means identifier | dsicoc:CertificateOfOrigin > ktddecv:hasConsignment > dsicoc:Consignment > ktddecv:usesTransportMeans > ktddecv:TransportMeans > ktddecv:transportMeansIdentifier |
| Vehicle registration number | dsicoc:CertificateOfOrigin > ktddecv:hasConsignment > dsicoc:Consignment > ktddecv:usesTransportMeans > ktddecv:TransportMeans > ktddecv:vehicleRegistrationIdentifier |
| Transport Equipment Identifier | dsicoc:CertificateOfOrigin > ktddecv:hasConsignment > dsicoc:Consignment > ktddecv:hasTransportEquipment > ktddecv:TransportEquipment > ktddecv:equipmentIdentifier > ktddecv:Identifier > ktddecv:value  (or ktddecv:containerNumber) |
