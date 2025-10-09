# KTDDE — SHACL Shapes Documentation (Worked Example Edition)

This document presents only the *Worked Example* for the Finnish gluelam export to Japan scenario, based on the `ktddecv:` core vocabulary.


---

## Worked Example — Finnish gluelam exported to Japan (Comprehensive)

**Narrative summary (for non‑technical readers):**  
A Finnish exporter, *Suomi Wood Oy*, sells structural glulam beams to the Japanese buyer *Tokyo Build KK*. The transaction is secured by a **Letter of Credit** issued by *Mizuho Bank (Tokyo)* and advised by *OP Corporate Bank (Helsinki)*. Cargo departs the Port of Kotka on *MS Aurora Baltic* and arrives in Tokyo. The example below shows how concrete trade data is expressed using SHACL shapes and `ktddecv:` properties.


---

## Additional Amount Category — example instance
- **Target class:** ktddecv:AdditionalAmountCategory
- **Example subject:** <https://example.org/fi-jp/Additional_Amount_Category>


---

## Address — example instance
- **Target class:** ktddecv:Address
- **Example subject:** <https://example.org/fi-jp/Address>


---

## Allowance Charge — example instance
- **Target class:** ktddecv:AllowanceCharge
- **Example subject:** <https://example.org/fi-jp/Allowance_Charge>

### Datatype Properties
- **allowanceChargeReasonCode** (`ktddecv:allowanceChargeReasonCode`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **perUnitAmount** (`ktddecv:perUnitAmount`) — *Datatype property* (`xsd:string`):  
  *Example* "12500000"
- **chargeIndicator** (`ktddecv:chargeIndicator`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **calculationPercent** (`ktddecv:calculationPercent`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **multiplierFactorPercent** (`ktddecv:multiplierFactorPercent`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **chargedToParty** (`ktddecv:chargedToParty`) — *Datatype property* (`xsd:string`):  
  *Example* <https://example.org/fi-jp/Party_SuomiWoodOy>
- **chargedByParty** (`ktddecv:chargedByParty`) — *Datatype property* (`xsd:string`):  
  *Example* <https://example.org/fi-jp/Party_SuomiWoodOy>
- **hasAmount** (`ktddecv:hasAmount`) — *Datatype property* (`xsd:string`):  
  *Example* "12500000"
- **baseAmount** (`ktddecv:baseAmount`) — *Datatype property* (`xsd:string`):  
  *Example* "12500000"

---

## Availability Method — example instance
- **Target class:** ktddecv:AvailabilityMethod
- **Example subject:** <https://example.org/fi-jp/Availability_Method>


---

## Bank Instruction — example instance
- **Target class:** ktddecv:BankInstruction
- **Example subject:** <https://example.org/fi-jp/Bank_Instruction>


---

## Business Document — example instance
- **Target class:** ktddecv:BusinessDocument
- **Example subject:** <https://example.org/fi-jp/Business_Document>

### Datatype Properties
- **documentType** (`ktddecv:documentType`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **hasMessage** (`ktddecv:hasMessage`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"

---

## Country — example instance
- **Target class:** ktddecv:Country
- **Example subject:** <https://example.org/fi-jp/Country>

### Datatype Properties
- **countryCode** (`ktddecv:countryCode`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **countryName** (`ktddecv:countryName`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"

---

## Credit Availability — example instance
- **Target class:** ktddecv:CreditAvailability
- **Example subject:** <https://example.org/fi-jp/Credit_Availability>

### Datatype Properties
- **tenor** (`ktddecv:tenor`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **obligorParty** (`ktddecv:obligorParty`) — *Datatype property* (`xsd:string`):  
  *Example* <https://example.org/fi-jp/Party_SuomiWoodOy>
- **availableWithQualifier** (`ktddecv:availableWithQualifier`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **draweeParty** (`ktddecv:draweeParty`) — *Datatype property* (`xsd:string`):  
  *Example* <https://example.org/fi-jp/Party_SuomiWoodOy>
- **hasAvailabilityMethod** (`ktddecv:hasAvailabilityMethod`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **availableWithParty** (`ktddecv:availableWithParty`) — *Datatype property* (`xsd:string`):  
  *Example* <https://example.org/fi-jp/Party_SuomiWoodOy>
- **hasAmount** (`ktddecv:hasAmount`) — *Datatype property* (`xsd:string`):  
  *Example* "12500000"
- **availableAtPlace** (`ktddecv:availableAtPlace`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **maturityDate** (`ktddecv:maturityDate`) — *Datatype property* (`xsd:string`):  
  *Example* "2025-01-15"
- **payeeParty** (`ktddecv:payeeParty`) — *Datatype property* (`xsd:string`):  
  *Example* <https://example.org/fi-jp/Party_SuomiWoodOy>

---

## Delivery Milestone — example instance
- **Target class:** ktddecv:DeliveryMilestone
- **Example subject:** <https://example.org/fi-jp/Delivery_Milestone>

### Datatype Properties
- **hasShipmentPeriod** (`ktddecv:hasShipmentPeriod`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"

---

## Document — example instance
- **Target class:** ktddecv:Document
- **Example subject:** <https://example.org/fi-jp/Document>

### Datatype Properties
- **documentDate** (`ktddecv:documentDate`) — *Datatype property* (`xsd:string`):  
  *Example* "2025-01-15"
- **documentIdentifier** (`ktddecv:documentIdentifier`) — *Datatype property* (`xsd:string`):  
  *Example* "LC-2025-000123"

---

## Document Requirement — example instance
- **Target class:** ktddecv:DocumentRequirement
- **Example subject:** <https://example.org/fi-jp/Document_Requirement>

### Datatype Properties
- **requiredDocumentType** (`ktddecv:requiredDocumentType`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **issuerParty** (`ktddecv:issuerParty`) — *Datatype property* (`xsd:string`):  
  *Example* <https://example.org/fi-jp/Party_SuomiWoodOy>
- **numberOfCopies** (`ktddecv:numberOfCopies`) — *Datatype property* (`xsd:string`):  
  *Example* "LC-2025-000123"
- **numberOfOriginals** (`ktddecv:numberOfOriginals`) — *Datatype property* (`xsd:string`):  
  *Example* "LC-2025-000123"

---

## Documentary Credit — example instance
- **Target class:** ktddecv:DocumentaryCredit
- **Example subject:** <https://example.org/fi-jp/Documentary_Credit>

### Datatype Properties
- **confirmationAddedDate** (`ktddecv:confirmationAddedDate`) — *Datatype property* (`xsd:string`):  
  *Example* "2025-01-15"
- **hasPaymentTerms** (`ktddecv:hasPaymentTerms`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **hasAvailabilityMethod** (`ktddecv:hasAvailabilityMethod`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **additionalAmountsCovered** (`ktddecv:additionalAmountsCovered`) — *Datatype property* (`xsd:string`):  
  *Example* "12500000"
- **requestedConfirmationParty** (`ktddecv:requestedConfirmationParty`) — *Datatype property* (`xsd:string`):  
  *Example* <https://example.org/fi-jp/Party_SuomiWoodOy>
- **hasShipment** (`ktddecv:hasShipment`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **advisingBankParty** (`ktddecv:advisingBankParty`) — *Datatype property* (`xsd:string`):  
  *Example* <https://example.org/fi-jp/Party_SuomiWoodOy>
- **reimbursingBankParty** (`ktddecv:reimbursingBankParty`) — *Datatype property* (`xsd:string`):  
  *Example* <https://example.org/fi-jp/Party_SuomiWoodOy>
- **coversAdditionalCharge** (`ktddecv:coversAdditionalCharge`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **applicantParty** (`ktddecv:applicantParty`) — *Datatype property* (`xsd:string`):  
  *Example* <https://example.org/fi-jp/Party_SuomiWoodOy>
- **presentationPeriodDays** (`ktddecv:presentationPeriodDays`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **hasCreditAvailability** (`ktddecv:hasCreditAvailability`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **requiresDocument** (`ktddecv:requiresDocument`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **partialShipmentAllowed** (`ktddecv:partialShipmentAllowed`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **hasPresentationPeriod** (`ktddecv:hasPresentationPeriod`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **maximumCreditAmount** (`ktddecv:maximumCreditAmount`) — *Datatype property* (`xsd:string`):  
  *Example* "12500000"
- **referencesPreAdvice** (`ktddecv:referencesPreAdvice`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **includesAllowanceCharge** (`ktddecv:includesAllowanceCharge`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **expiryDate** (`ktddecv:expiryDate`) — *Datatype property* (`xsd:string`):  
  *Example* "2025-01-15"
- **latestShipmentDate** (`ktddecv:latestShipmentDate`) — *Datatype property* (`xsd:string`):  
  *Example* "2025-01-15"
- **issuingBankParty** (`ktddecv:issuingBankParty`) — *Datatype property* (`xsd:string`):  
  *Example* <https://example.org/fi-jp/Party_SuomiWoodOy>
- **hasDeliveryMilestone** (`ktddecv:hasDeliveryMilestone`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **applicableRules** (`ktddecv:applicableRules`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **issueDate** (`ktddecv:issueDate`) — *Datatype property* (`xsd:string`):  
  *Example* "2025-01-15"
- **hasShipmentPeriod** (`ktddecv:hasShipmentPeriod`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **presentationBaseEvent** (`ktddecv:presentationBaseEvent`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **beneficiaryParty** (`ktddecv:beneficiaryParty`) — *Datatype property* (`xsd:string`):  
  *Example* <https://example.org/fi-jp/Party_SuomiWoodOy>
- **hasPaymentLine** (`ktddecv:hasPaymentLine`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **additionalConditionsText** (`ktddecv:additionalConditionsText`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **confirmingParty** (`ktddecv:confirmingParty`) — *Datatype property* (`xsd:string`):  
  *Example* <https://example.org/fi-jp/Party_SuomiWoodOy>
- **confirmationInstructionCode** (`ktddecv:confirmationInstructionCode`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **creditAmountTolerancePercentage** (`ktddecv:creditAmountTolerancePercentage`) — *Datatype property* (`xsd:string`):  
  *Example* "12500000"
- **latestPresentationDate** (`ktddecv:latestPresentationDate`) — *Datatype property* (`xsd:string`):  
  *Example* "2025-01-15"
- **applicantBankParty** (`ktddecv:applicantBankParty`) — *Datatype property* (`xsd:string`):  
  *Example* <https://example.org/fi-jp/Party_SuomiWoodOy>
- **placeOfExpiry** (`ktddecv:placeOfExpiry`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **adviseThroughBankParty** (`ktddecv:adviseThroughBankParty`) — *Datatype property* (`xsd:string`):  
  *Example* <https://example.org/fi-jp/Party_SuomiWoodOy>
- **draweeParty** (`ktddecv:draweeParty`) — *Datatype property* (`xsd:string`):  
  *Example* <https://example.org/fi-jp/Party_SuomiWoodOy>
- **placeOfPresentation** (`ktddecv:placeOfPresentation`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **documentaryCreditTypeCode** (`ktddecv:documentaryCreditTypeCode`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **creditIdentifier** (`ktddecv:creditIdentifier`) — *Datatype property* (`xsd:string`):  
  *Example* "LC-2025-000123"
- **instructionToBank** (`ktddecv:instructionToBank`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **transshipmentAllowed** (`ktddecv:transshipmentAllowed`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"

---

## Duty/Tax/Fee — example instance
- **Target class:** ktddecv:DutyTaxFee
- **Example subject:** <https://example.org/fi-jp/Duty_Tax_Fee>


---

## Goods Item — example instance
- **Target class:** ktddecv:GoodsItem
- **Example subject:** <https://example.org/fi-jp/Goods_Item>

### Datatype Properties
- **descriptionOfGoodsText** (`ktddecv:descriptionOfGoodsText`) — *Datatype property* (`xsd:string`):  
  *Example* "Structural glued-laminated timber beams, GL28h"
- **hasQuantity** (`ktddecv:hasQuantity`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **hasDangerousGoodsDetails** (`ktddecv:hasDangerousGoodsDetails`) — *Datatype property* (`xsd:string`):  
  *Example* "Structural glued-laminated timber beams, GL28h"
- **productIdentifier** (`ktddecv:productIdentifier`) — *Datatype property* (`xsd:string`):  
  *Example* "LC-2025-000123"
- **itemDescriptionText** (`ktddecv:itemDescriptionText`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **appliedCommodityClassification** (`ktddecv:appliedCommodityClassification`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **hasCountryOfOrigin** (`ktddecv:hasCountryOfOrigin`) — *Datatype property* (`xsd:string`):  
  *Example* "FI"

---

## Identifier — example instance
- **Target class:** ktddecv:Identifier
- **Example subject:** <https://example.org/fi-jp/Identifier>


---

## Instruction — example instance
- **Target class:** ktddecv:Instruction
- **Example subject:** <https://example.org/fi-jp/Instruction>

### Datatype Properties
- **instructionText** (`ktddecv:instructionText`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **instructingParty** (`ktddecv:instructingParty`) — *Datatype property* (`xsd:string`):  
  *Example* <https://example.org/fi-jp/Party_SuomiWoodOy>
- **instructedParty** (`ktddecv:instructedParty`) — *Datatype property* (`xsd:string`):  
  *Example* <https://example.org/fi-jp/Party_SuomiWoodOy>

---

## Legal Entity — example instance
- **Target class:** ktddecv:LegalEntity
- **Example subject:** <https://example.org/fi-jp/Legal_Entity>


---

## Location — example instance
- **Target class:** ktddecv:Location
- **Example subject:** <https://example.org/fi-jp/Location>

### Datatype Properties
- **longitude** (`ktddecv:longitude`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **timeZone** (`ktddecv:timeZone`) — *Datatype property* (`xsd:string`):  
  *Example* "2025-02-15T14:05:00Z"
- **unlocode** (`ktddecv:unlocode`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **customsOfficeCode** (`ktddecv:customsOfficeCode`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **alternateName** (`ktddecv:alternateName`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **portFacilityCode** (`ktddecv:portFacilityCode`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **hasAddress** (`ktddecv:hasAddress`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **locationCountry** (`ktddecv:locationCountry`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **borderCrossingPointCode** (`ktddecv:borderCrossingPointCode`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **iataCode** (`ktddecv:iataCode`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **geoWKT** (`ktddecv:geoWKT`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **uicStationCode** (`ktddecv:uicStationCode`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **elevationMeters** (`ktddecv:elevationMeters`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **description** (`ktddecv:description`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **locationID** (`ktddecv:locationID`) — *Datatype property* (`xsd:string`):  
  *Example* "LC-2025-000123"
- **icaoAirportCode** (`ktddecv:icaoAirportCode`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **postCode** (`ktddecv:postCode`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **locationName** (`ktddecv:locationName`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **terminalCode** (`ktddecv:terminalCode`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **latitude** (`ktddecv:latitude`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **hasIdentifier** (`ktddecv:hasIdentifier`) — *Datatype property* (`xsd:string`):  
  *Example* "LC-2025-000123"
- **warehouseGLN** (`ktddecv:warehouseGLN`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"

---

## Monetary Amount — example instance
- **Target class:** ktddecv:MonetaryAmount
- **Example subject:** <https://example.org/fi-jp/Monetary_Amount>

### Datatype Properties
- **amountValue** (`ktddecv:amountValue`) — *Datatype property* (`xsd:string`):  
  *Example* "12500000"
- **currencyCode** (`ktddecv:currencyCode`) — *Datatype property* (`xsd:string`):  
  *Example* "JPY"

---

## Party — example instance
- **Target class:** ktddecv:Party
- **Example subject:** <https://example.org/fi-jp/Party>

### Datatype Properties
- **name** (`ktddecv:name`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **partyLegalEntity** (`ktddecv:partyLegalEntity`) — *Datatype property* (`xsd:string`):  
  *Example* <https://example.org/fi-jp/Party_SuomiWoodOy>
- **partyAddress** (`ktddecv:partyAddress`) — *Datatype property* (`xsd:string`):  
  *Example* <https://example.org/fi-jp/Party_SuomiWoodOy>
- **partyIdentifier** (`ktddecv:partyIdentifier`) — *Datatype property* (`xsd:string`):  
  *Example* "LC-2025-000123"

---

## Payment Line — example instance
- **Target class:** ktddecv:PaymentLine
- **Example subject:** <https://example.org/fi-jp/Payment_Line>

### Datatype Properties
- **hasAmount** (`ktddecv:hasAmount`) — *Datatype property* (`xsd:string`):  
  *Example* "12500000"
- **paymentSettlementMethod** (`ktddecv:paymentSettlementMethod`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **tenor** (`ktddecv:tenor`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **payeeParty** (`ktddecv:payeeParty`) — *Datatype property* (`xsd:string`):  
  *Example* <https://example.org/fi-jp/Party_SuomiWoodOy>
- **paymentDueDate** (`ktddecv:paymentDueDate`) — *Datatype property* (`xsd:string`):  
  *Example* "2025-01-15"

---

## Payment Schedule Line — example instance
- **Target class:** ktddecv:PaymentScheduleLine
- **Example subject:** <https://example.org/fi-jp/Payment_Schedule_Line>

### Datatype Properties
- **baseAmount** (`ktddecv:baseAmount`) — *Datatype property* (`xsd:string`):  
  *Example* "12500000"
- **paymentDueDate** (`ktddecv:paymentDueDate`) — *Datatype property* (`xsd:string`):  
  *Example* "2025-01-15"
- **deferredPaymentDate** (`ktddecv:deferredPaymentDate`) — *Datatype property* (`xsd:string`):  
  *Example* "2025-01-15"
- **hasAmount** (`ktddecv:hasAmount`) — *Datatype property* (`xsd:string`):  
  *Example* "12500000"
- **amountPercentOfBase** (`ktddecv:amountPercentOfBase`) — *Datatype property* (`xsd:string`):  
  *Example* "12500000"

---

## Payment Terms — example instance
- **Target class:** ktddecv:PaymentTerms
- **Example subject:** <https://example.org/fi-jp/Payment_Terms>

### Datatype Properties
- **paymentTermCode** (`ktddecv:paymentTermCode`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **tenor** (`ktddecv:tenor`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **hasPaymentScheduleLine** (`ktddecv:hasPaymentScheduleLine`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **tenorPeriod** (`ktddecv:tenorPeriod`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"

---

## Period of Time — example instance
- **Target class:** ktddecv:PeriodOfTime
- **Example subject:** <https://example.org/fi-jp/Period_of_Time>

### Datatype Properties
- **startDate** (`ktddecv:startDate`) — *Datatype property* (`xsd:string`):  
  *Example* "2025-01-15"
- **endDate** (`ktddecv:endDate`) — *Datatype property* (`xsd:string`):  
  *Example* "2025-01-15"

---

## Presentation — example instance
- **Target class:** ktddecv:Presentation
- **Example subject:** <https://example.org/fi-jp/Presentation>


---

## Rule Set — example instance
- **Target class:** ktddecv:RuleSet
- **Example subject:** <https://example.org/fi-jp/Rule_Set>

### Datatype Properties
- **publicationDate** (`ktddecv:publicationDate`) — *Datatype property* (`xsd:string`):  
  *Example* "2025-01-15"
- **title** (`ktddecv:title`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **ruleSetIdentifier** (`ktddecv:ruleSetIdentifier`) — *Datatype property* (`xsd:string`):  
  *Example* "LC-2025-000123"
- **versionIdentifier** (`ktddecv:versionIdentifier`) — *Datatype property* (`xsd:string`):  
  *Example* "LC-2025-000123"
- **publisher** (`ktddecv:publisher`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"

---

## Shipment — example instance
- **Target class:** ktddecv:Shipment
- **Example subject:** <https://example.org/fi-jp/Shipment>

### Datatype Properties
- **buyerParty** (`ktddecv:buyerParty`) — *Datatype property* (`xsd:string`):  
  *Example* <https://example.org/fi-jp/Party_SuomiWoodOy>
- **requestedDeliveryPeriod** (`ktddecv:requestedDeliveryPeriod`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **placeOfDeliveryUNLocode** (`ktddecv:placeOfDeliveryUNLocode`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **isRealizedByConsignment** (`ktddecv:isRealizedByConsignment`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **totalTransportHandlingUnitQuantity** (`ktddecv:totalTransportHandlingUnitQuantity`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **insuranceValueAmount** (`ktddecv:insuranceValueAmount`) — *Datatype property* (`xsd:string`):  
  *Example* "12500000"
- **finalDestinationUNLocode** (`ktddecv:finalDestinationUNLocode`) — *Datatype property* (`xsd:string`):  
  *Example* "JP TYOKO (Tokyo)"
- **portOfDischargeUNLocode** (`ktddecv:portOfDischargeUNLocode`) — *Datatype property* (`xsd:string`):  
  *Example* "JP TYOKO (Tokyo)"
- **relatedOrder** (`ktddecv:relatedOrder`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **invoiceDocument** (`ktddecv:invoiceDocument`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **hasGoodsItem** (`ktddecv:hasGoodsItem`) — *Datatype property* (`xsd:string`):  
  *Example* "Structural glued-laminated timber beams, GL28h"
- **declaredCustomsValueAmount** (`ktddecv:declaredCustomsValueAmount`) — *Datatype property* (`xsd:string`):  
  *Example* "12500000"
- **totalGoodsItemQuantity** (`ktddecv:totalGoodsItemQuantity`) — *Datatype property* (`xsd:string`):  
  *Example* "Structural glued-laminated timber beams, GL28h"
- **shipmentIdentifier** (`ktddecv:shipmentIdentifier`) — *Datatype property* (`xsd:string`):  
  *Example* "LC-2025-000123"
- **totalPackageQuantity** (`ktddecv:totalPackageQuantity`) — *Datatype property* (`xsd:string`):  
  *Example* "25"
- **portOfLoadingUNLocode** (`ktddecv:portOfLoadingUNLocode`) — *Datatype property* (`xsd:string`):  
  *Example* "FI KTK (Kotka)"
- **placeOfReceiptUNLocode** (`ktddecv:placeOfReceiptUNLocode`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **sellerParty** (`ktddecv:sellerParty`) — *Datatype property* (`xsd:string`):  
  *Example* <https://example.org/fi-jp/Party_SuomiWoodOy>
- **hazardousRiskIndicator** (`ktddecv:hazardousRiskIndicator`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **contractNumber** (`ktddecv:contractNumber`) — *Datatype property* (`xsd:string`):  
  *Example* "LC-2025-000123"
- **hasShipmentPeriod** (`ktddecv:hasShipmentPeriod`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **deliveryTerms** (`ktddecv:deliveryTerms`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"

---

## Shipment Basis — example instance
- **Target class:** ktddecv:ShipmentBasis
- **Example subject:** <https://example.org/fi-jp/Shipment_Basis>


---

## Trade Delivery Terms — example instance
- **Target class:** ktddecv:TradeDeliveryTerms
- **Example subject:** <https://example.org/fi-jp/Trade_Delivery_Terms>

### Datatype Properties
- **relatesToConsignment** (`ktddecv:relatesToConsignment`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **placeOfDischarge** (`ktddecv:placeOfDischarge`) — *Datatype property* (`xsd:string`):  
  *Example* "JP TYOKO (Tokyo)"
- **placeOfDelivery** (`ktddecv:placeOfDelivery`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **deliveryTermsText** (`ktddecv:deliveryTermsText`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **hasDeliveryPeriod** (`ktddecv:hasDeliveryPeriod`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **applicableRules** (`ktddecv:applicableRules`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **placeOfLoading** (`ktddecv:placeOfLoading`) — *Datatype property* (`xsd:string`):  
  *Example* "FI KTK (Kotka)"
- **incotermsCode** (`ktddecv:incotermsCode`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"
- **includesAllowanceCharge** (`ktddecv:includesAllowanceCharge`) — *Datatype property* (`xsd:string`):  
  *Example* "Example value"

---
