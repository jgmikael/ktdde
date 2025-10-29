# KTDDE → ktddecv Mapping for **Customs Declaration**

This table lists each data element found in the uploaded CSV as included in a *Customs Declaration* (CD = 'C'), and maps it to the present **ktddecv** OWL (uploaded RDF).

| Data Element | ktddecv: Class | Property | Property Type | Range Class | Status | Comment |
|---|---|---|---|---|---|---|
| Actual arrival date |  | actualArrivalDateTime | datatype | http://www.w3.org/2000/01/rdf-schema#Literal | Existing |  |
| Actual departure date |  | actualDepartureDateTime | datatype | http://www.w3.org/2000/01/rdf-schema#Literal | Existing |  |
| Allowance / Charge |  | includesAllowanceCharge | object |  | Existing |  |
| Arrival location |  |  |  |  | Missing | No property/class match found in the uploaded KTDDE OWL. |
| Authentication |  |  |  |  | Missing | No property/class match found in the uploaded KTDDE OWL. |
| Booking reference number |  |  |  |  | Missing | No property/class match found in the uploaded KTDDE OWL. |
| Buyer |  | hasBuyer | object |  | Existing |  |
| Carrier (Transport Services Provider) |  |  |  |  | Missing | No property/class match found in the uploaded KTDDE OWL. |
| Consignee |  | consigneeParty | object |  | Existing |  |
| Consignment loading date |  |  |  |  | Missing | No property/class match found in the uploaded KTDDE OWL. |
| Consignment route |  |  |  |  | Missing | No property/class match found in the uploaded KTDDE OWL. |
| Consignment summary description |  |  |  |  | Missing | No property/class match found in the uploaded KTDDE OWL. |
| Consignment. Exit Customs Office |  |  |  |  | Missing | No property/class match found in the uploaded KTDDE OWL. |
| Consignor |  | consignorParty | object |  | Existing |  |
| Conveyance reference number/Journey identifier |  |  |  |  | Missing | No property/class match found in the uploaded KTDDE OWL. |
| Customs Declaration Document, Trader Assigned |  |  |  |  | Missing | No property/class match found in the uploaded KTDDE OWL. |
| Customs Tariff Quantity Deduction |  |  |  |  | Missing | No property/class match found in the uploaded KTDDE OWL. |
| Customs office of entry |  |  |  |  | Missing | No property/class match found in the uploaded KTDDE OWL. |
| Customs value |  | declaredCustomsValueAmount | object | MonetaryAmount | Existing |  |
| Dangerous Goods Regulation Code |  |  |  |  | Missing | No property/class match found in the uploaded KTDDE OWL. |
| Dangerous Goods Technical Name |  |  |  |  | Missing | No property/class match found in the uploaded KTDDE OWL. |
| Dangerous goods class number |  |  |  |  | Missing | No property/class match found in the uploaded KTDDE OWL. |
| Description of Goods |  | descriptionOfGoodsText | datatype | http://www.w3.org/2000/01/rdf-schema#Literal | Existing |  |
| Document Identifier |  | documentIdentifier | datatype | http://www.w3.org/2001/XMLSchema#string | Existing |  |
| Estimated time of arrival |  |  |  |  | Missing | No property/class match found in the uploaded KTDDE OWL. |
| Estimated time of departure |  | estimatedTimeOfDeparture | datatype | http://www.w3.org/2001/XMLSchema#dateTime | Existing |  |
| Exportation country |  |  |  |  | Missing | No property/class match found in the uploaded KTDDE OWL. |
| Exporter |  | exporterParty | object |  | Existing |  |
| Flashpoint temperature |  | flashPointTemperature | datatype | http://www.w3.org/2000/01/rdf-schema#Literal | Existing |  |
| Freight and charges amount |  | freightChargesAmount | object |  | Existing |  |
| Full or empty container |  |  |  |  | Missing | No property/class match found in the uploaded KTDDE OWL. |
| Goods value |  |  |  |  | Missing | No property/class match found in the uploaded KTDDE OWL. |
| Gross weight |  | totalGrossWeight | object |  | Existing |  |
| HS Code (Commodity Code) |  |  |  |  | Missing | No property/class match found in the uploaded KTDDE OWL. |
| Importer |  | importerParty | object |  | Existing |  |
| Insurance amount |  | insuredAmount | object |  | Existing |  |
| Insurance company |  |  |  |  | Missing | No property/class match found in the uploaded KTDDE OWL. |
| Invoice date |  | invoiceDate | datatype | http://www.w3.org/2000/01/rdf-schema#Literal | Existing |  |
| Invoice number |  | invoiceNumber | datatype | http://www.w3.org/2000/01/rdf-schema#Literal | Existing |  |
| Issue date |  | issueDate | datatype | http://www.w3.org/2001/XMLSchema#dateTime | Existing |  |
| Notify party |  | notifyParty | object |  | Existing |  |
| Number of Packages |  | packageCount | datatype | http://www.w3.org/2000/01/rdf-schema#Literal | Existing |  |
| Origin country |  | originCountry | object |  | Existing |  |
| Package width |  |  |  |  | Missing | No property/class match found in the uploaded KTDDE OWL. |
| Payment Method |  | paymentMethod | datatype | http://www.w3.org/2001/XMLSchema#string | Existing |  |
| Place of issue |  | placeOfIssue | object |  | Existing |  |
| Product identifier |  | productIdentifier | datatype | http://www.w3.org/2000/01/rdf-schema#Literal | Existing |  |
| Seal Identifier |  | sealIdentifier | object |  | Existing |  |
| Seller |  | sellerParty | object |  | Existing |  |
| Ship to / Delivery Party |  |  |  |  | Missing | No property/class match found in the uploaded KTDDE OWL. |
| Shipping Marks |  | shippingMarks | datatype | http://www.w3.org/2001/XMLSchema#string | Existing |  |
| Statistical value |  | statisticalValueAmount | object |  | Existing |  |
| Tax Regime Type |  |  |  |  | Missing | No property/class match found in the uploaded KTDDE OWL. |
| Tax amount |  |  |  |  | Missing | No property/class match found in the uploaded KTDDE OWL. |
| Tax or fee assessment basis amount |  |  |  |  | Missing | No property/class match found in the uploaded KTDDE OWL. |
| Tax or fee type |  |  |  |  | Missing | No property/class match found in the uploaded KTDDE OWL. |
| Total invoice amount |  | totalInvoiceAmount | object |  | Existing |  |
| Trade terms conditions code |  |  |  |  | Missing | No property/class match found in the uploaded KTDDE OWL. |
| Trade terms conditions description |  |  |  |  | Missing | No property/class match found in the uploaded KTDDE OWL. |
| Transport Contract Document / Bill of Lading number |  |  |  |  | Missing | No property/class match found in the uploaded KTDDE OWL. |
| Transport Contract Document Conditions |  |  |  |  | Missing | No property/class match found in the uploaded KTDDE OWL. |
| Transport Equipment Identifier |  | hasTransportEquipment | object |  | Existing |  |
| Transport Temperature |  | transportTemperature | datatype | http://www.w3.org/2001/XMLSchema#decimal | Existing |  |
| Transport means at border crossing |  |  |  |  | Missing | No property/class match found in the uploaded KTDDE OWL. |
| Transport means identifier |  | usesTransportMeans | object |  | Existing |  |
| Type of Packaging (UNCEFACT coded) and shipping marks |  |  |  |  | Missing | No property/class match found in the uploaded KTDDE OWL. |
| UNDG Number |  | unNumber | datatype | http://www.w3.org/2000/01/rdf-schema#Literal | Existing |  |
| Unique Consignment Reference (UCR) |  |  |  |  | Missing | No property/class match found in the uploaded KTDDE OWL. |
| Volume (Cube) |  |  |  |  | Missing | No property/class match found in the uploaded KTDDE OWL. |
| Warehouse |  | warehouseGLN | datatype | http://www.w3.org/2000/01/rdf-schema#Literal | Existing |  |