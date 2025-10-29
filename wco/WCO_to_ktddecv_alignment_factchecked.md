# Alignment between WCO Data Model (v4.2.0) and KTDDE Core Vocabulary (ktddecv:)

This document summarizes factual correspondences found between the
**World Customs Organization (WCO) Data Model v4.2.0**
and the uploaded **KTDDE Core Vocabulary (ktddecv:) RDF v13**.

Only entities that exist in the current ontology are referenced.
All others are listed as *unmapped*.

---

## 1  WCO Classes → Existing `ktddecv:` Classes

| WCO Class | Matching `ktddecv:` Class (confirmed IRI) | Notes |
|------------|---------------------------------------------|-------|
| Consignment | [`ktddecv:Consignment`](https://iri.suomi.fi/model/ktddecv/Consignment) | Core shipment entity |
| GoodsItem | [`ktddecv:GoodsItem`](https://iri.suomi.fi/model/ktddecv/GoodsItem) | Item belonging to a consignment |
| Package | [`ktddecv:Package`](https://iri.suomi.fi/model/ktddecv/Package) | Packaging unit |
| TransportEquipment | [`ktddecv:TransportEquipment`](https://iri.suomi.fi/model/ktddecv/TransportEquipment) | Physical transport equipment |
| TransportMeans | [`ktddecv:TransportMeans`](https://iri.suomi.fi/model/ktddecv/TransportMeans) | Vehicle / vessel used for transport |
| Location | [`ktddecv:Location`](https://iri.suomi.fi/model/ktddecv/Location) | Any geographic or functional place |
| Address | [`ktddecv:Address`](https://iri.suomi.fi/model/ktddecv/Address) | Structured postal address |
| Bank | [`ktddecv:Bank`](https://iri.suomi.fi/model/ktddecv/Bank) | Financial institution |
| Characteristic | [`ktddecv:Characteristic`](https://iri.suomi.fi/model/ktddecv/Characteristic) | Descriptive property of goods |
| Document | [`ktddecv:Document`](https://iri.suomi.fi/model/ktddecv/Document) | Generic document super-class |
| Warehouse | [`ktddecv:Warehouse`](https://iri.suomi.fi/model/ktddecv/Warehouse) | Storage location |

*(All above IRIs verified in the RDF v13.)*

---

## 2  WCO “Role” Classes → Existing `ktddecv:` Object Properties

WCO models many business actors as independent classes;  
KTDDE represents them as object properties linking a document or consignment to a `Party`.

| WCO Role Class | Matching `ktddecv:` Object Property | Typical Usage |
|----------------|--------------------------------------|---------------|
| Applicant | [`ktddecv:applicantParty`](https://iri.suomi.fi/model/ktddecv/applicantParty) | Application → Party |
| Buyer | [`ktddecv:buyerParty`](https://iri.suomi.fi/model/ktddecv/buyerParty) | Document → Party |
| Seller | [`ktddecv:sellerParty`](https://iri.suomi.fi/model/ktddecv/sellerParty) | Document → Party |
| Consignor | [`ktddecv:consignorParty`](https://iri.suomi.fi/model/ktddecv/consignorParty) | Consignment → Party |
| Consignee | [`ktddecv:consigneeParty`](https://iri.suomi.fi/model/ktddecv/consigneeParty) | Consignment → Party |
| Exporter | [`ktddecv:exporterParty`](https://iri.suomi.fi/model/ktddecv/exporterParty) | Document → Party |
| Importer | [`ktddecv:importerParty`](https://iri.suomi.fi/model/ktddecv/importerParty) | Document → Party |
| Declarant | [`ktddecv:declarantParty`](https://iri.suomi.fi/model/ktddecv/declarantParty) | Declaration → Party |
| Carrier | [`ktddecv:carrierParty`](https://iri.suomi.fi/model/ktddecv/carrierParty) | Transport → Party |
| FreightForwarder | [`ktddecv:freightForwarderParty`](https://iri.suomi.fi/model/ktddecv/freightForwarderParty) | Transport → Party |
| Issuer | [`ktddecv:issuerParty`](https://iri.suomi.fi/model/ktddecv/issuerParty) | Document → Party |
| NotifyParty | [`ktddecv:notifyParty`](https://iri.suomi.fi/model/ktddecv/notifyParty) | Consignment → Party |
| Payer | [`ktddecv:payerParty`](https://iri.suomi.fi/model/ktddecv/payerParty) | Payment → Party |
| Sender | [`ktddecv:senderParty`](https://iri.suomi.fi/model/ktddecv/senderParty) | Message → Party |
| Surety | [`ktddecv:suretyParty`](https://iri.suomi.fi/model/ktddecv/suretyParty) | Guarantee → Party |
| TransitOffice | [`ktddecv:transitOffice`](https://iri.suomi.fi/model/ktddecv/transitOffice) | Movement → Location |

*(Each property verified in the ontology.)*

---

## 3  WCO Classes Currently Unmapped in `ktddecv:`

The following WCO entities were found in the Excel but have no direct counterpart in the current ontology.
They could later be introduced as new classes or represented via generic `Authority` or `Office` structures.

| WCO Class | Remarks |
|------------|----------|
| AppealOffice | No matching class; might extend an Authority pattern |
| DeclarationOffice | Customs administrative office |
| ControlOffice | Inspection authority |
| EntryOffice | Border entry point |
| ExitOffice | Border exit point |
| ExportOffice | Export customs office |
| GuaranteeOffice | Bond or guarantee office |
| PresentationOffice | Document submission office |
| ReleaseOffice | Release point in customs procedure |
| ResponsibleGovernmentAgency | General administrative entity |
| PaymentOffice | Financial administration |
| SupervisingOffice | Oversight authority |
| MasterDataOffice | Registry or data-exchange governance |
| ItineraryOffice | Transport network reference |
| TransitOperationStartOffice | Transit start location |
| TransitOperationTerminationOffice | Transit end location |

*(Complete list in `wco_unmappable_classes.csv`.)*

---

## 4  Summary Findings

- 11 WCO entity types directly match existing `ktddecv:` classes.  
- 15 WCO role types map cleanly to existing `ktddecv:` object properties.  
- Roughly 240 remaining WCO entries have no current match and belong mostly to the **Customs Office / Authority / Control** domain.

---

## 5  Next Steps (Technical Work Recommendations)

1. Group unmapped concepts into extension domains:  
  • Administrative / Authority Offices  
  • Control and Inspection Authorities  
  • Valuation and Guarantee Structures  

2. Decide for each whether a new `ktddecv:` **class** or **object property** is more appropriate.  
3. Document these proposals for discussion in WE BUILD WP4 Semantic Group.

---

*Data sources:*   
 • WCO Data Model v4.2.0 Library (Excel)  
 • KTDDE Core Vocabulary `ktddecv:` RDF v13  
 • Mapping performed by GPT-5 (Oct 2025) using actual RDF classes and properties
