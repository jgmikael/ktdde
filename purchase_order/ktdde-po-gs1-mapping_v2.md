# KTDDE Purchase Order Data Elements and GS1 Web Vocabulary Candidates

| Data element | KTDDE class (SHACL target) | KTDDE property (sh:path) | GS1 Web Vocabulary candidate(s) | Assessment of GS1 mapping | TDED UID |
|---|---|---|---|---|---|
| Purchase Order number | `ktddecv:PurchaseOrder` | `ktddecv:orderIdentifier` | No direct `gs1:` property; closest is `gs1:TransactionType-ON` | Weak/none – GS1 uses message type codes, not general identifiers | 1022 |
| Contract number | `ktddecv:Contract` | `ktddecv:contractIdentifier` | None in GS1; only `gs1:ContactRoleType-CONTRACT_CONTACT` | None – GS1 not modelling contract identifiers | 1296 |
| Order date | `ktddecv:PurchaseOrder` | `ktddecv:orderDate` | None; closest match via `schema:orderDate` | Close but via schema.org, not GS1 | 2011 |
| Delivery date | `ktddecv:Consignment` | `ktddecv:deliveryDate` | No explicit GS1 delivery date property | No direct GS1 mapping | 2138 |
| Buyer | `ktddecv:Party` (via buyerParty) | `ktddecv:buyerParty` | `gs1:Organization` + `gs1:OrganizationRoleType-ORDERING_PARTY` | Strong pattern-based alignment | 3002 |
| Invoicee | `ktddecv:Party` (via invoiceeParty) | `ktddecv:invoiceeParty` | `gs1:OrganizationRoleType-INVOICEE` | Strong pattern-based alignment | 3006 |
| Ship to / Delivery Party | `ktddecv:Party` (via deliveryParty) | `ktddecv:deliveryParty` | `gs1:OrganizationRoleType-DELIVERY_RECIPIENT_PARTY` | Strong pattern-based alignment | 3144 |
| Seller | `ktddecv:Party` (via sellerParty) | `ktddecv:sellerParty` | `gs1:OrganizationRoleType-SELLER` | Strong pattern-based alignment | 3346 |
| Place of delivery of the goods | `ktddecv:TradeDeliveryTerms` → `ktddecv:Location` | `ktddecv:deliveryLocation` | `gs1:location` + GLN location roles | Close alignment; GLN integration recommended | 3000 |
| Origin country | `ktddecv:GoodsItem` → `ktddecv:Country` | `ktddecv:hasCountryOfOrigin` | `gs1:countryOfOrigin`, `gs1:Country`, `gs1:countryCode` | Very strong equivalence | 3238 |
| Payment term | `ktddecv:PaymentTerms` | (missing in SHACL) | `gs1:paymentTerms` | Clear design opportunity | 4277 |
| Payment method | `ktddecv:PaymentTerms` | `ktddecv:paymentMethod` | `gs1:PaymentMethod`, `gs1:acceptedPaymentMethod` | Strong conceptual match | 4467 |
| Unit Price | `ktddecv:GoodsItem` | `ktddecv:unitPrice` | `gs1:PriceSpecification`, `gs1:price`, `gs1:priceCurrency` | Strong, structural alignment possible | 5110 |
| Allowance / Charge | `ktddecv:AllowanceCharge` | (structure missing) | `gs1:Discount` model | Strong concept but structure needed | 5189 |
| Order amount | `ktddecv:PurchaseOrder` → `ktddecv:Amount` | `ktddecv:orderAmount` | `gs1:PriceSpecification`, `gs1:price` | Close conceptual match | 5390 |
| Tax amount | (not modelled) | (not modelled) | `gs1:dutyFeeTaxAmount` | Strong if property added in KTDDE | 5490 |
| Quantity ordered | `ktddecv:GoodsItem` | (missing orderedQuantity property) | `gs1:eligibleQuantity` | Approximate match | 6024 |
| Product identifier | `ktddecv:GoodsItem` | `ktddecv:productIdentifier` | `gs1:gtin` | Very strong equivalence when GTIN used | 7135 |

