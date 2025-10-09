# KTDDE — SHACL Shapes Documentation (with Worked Example)

This document presents the SHACL shapes for the KTDDE Letter of Credit model, beginning with a complete worked example of the *Finnish gluelam exported to Japan* trade scenario, followed by detailed technical documentation.


# Worked Example — Finnish gluelam exported to Japan (Comprehensive)
**Narrative summary (for non‑technical readers):**  
This example follows a real‑world trade flow in which a Finnish company, *Suomi Wood Oy*, exports structural glued‑laminated timber (glulam) beams to a Japanese construction firm, *Tokyo Build KK*. The transaction is financed through a **Letter of Credit** issued by *Mizuho Bank (Tokyo)* and advised by *OP Corporate Bank (Helsinki)*. The shipment leaves the Port of Kotka (Finland) by sea on the vessel *MS Aurora Baltic* and arrives at the Port of Tokyo. The example illustrates how each data element—banks, ports, quantities, invoices, documents, events—fits into the KTDDE semantic model through SHACL shapes and `ktddecv:` properties.


Each **Node Shape** below includes example instance data for **every attached property**. Values are realistic for the scenario and obey declared datatypes, value sets and node kinds. Predicates shown are the exact **`sh:path`** IRIs (i.e., `ktddecv:` properties).

## Additional Amount Category — example instance
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/AdditionalAmountCategory>
- **Example subject:** <https://example.org/fi-jp/Additional_Amount_Category>

_No property constraints attached to this node shape._

## Address — example instance
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Address>
- **Example subject:** <https://example.org/fi-jp/Address>

_No property constraints attached to this node shape._

## Allowance Charge — example instance
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/AllowanceCharge>
- **Example subject:** <https://example.org/fi-jp/Allowance_Charge>

**Property values (from example):**
- allowanceChargeReasonCode (`<https://iri.suomi.fi/model/ktddecv/0.0.4/allowanceChargeReasonCode>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- perUnitAmount (`<https://iri.suomi.fi/model/ktddecv/0.0.4/perUnitAmount>`): "12500000.0"^^<http://www.w3.org/2001/XMLSchema#decimal>
- chargeIndicator (`<https://iri.suomi.fi/model/ktddecv/0.0.4/chargeIndicator>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- calculationPercent (`<https://iri.suomi.fi/model/ktddecv/0.0.4/calculationPercent>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- multiplierFactorPercent (`<https://iri.suomi.fi/model/ktddecv/0.0.4/multiplierFactorPercent>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- chargedToParty (`<https://iri.suomi.fi/model/ktddecv/0.0.4/chargedToParty>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- chargedByParty (`<https://iri.suomi.fi/model/ktddecv/0.0.4/chargedByParty>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- hasAmount (`<https://iri.suomi.fi/model/ktddecv/0.0.4/hasAmount>`): "12500000.0"^^<http://www.w3.org/2001/XMLSchema#decimal>
- baseAmount (`<https://iri.suomi.fi/model/ktddecv/0.0.4/baseAmount>`): "12500000.0"^^<http://www.w3.org/2001/XMLSchema#decimal>

## Availability Method — example instance
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/AvailabilityMethod>
- **Example subject:** <https://example.org/fi-jp/Availability_Method>

_No property constraints attached to this node shape._

## Bank Instruction — example instance
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/BankInstruction>
- **Example subject:** <https://example.org/fi-jp/Bank_Instruction>

_No property constraints attached to this node shape._

## Business Document — example instance
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/BusinessDocument>
- **Example subject:** <https://example.org/fi-jp/Business_Document>

**Property values (from example):**
- documentType (`<https://iri.suomi.fi/model/ktddecv/0.0.4/documentType>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- hasMessage (`<https://iri.suomi.fi/model/ktddecv/0.0.4/hasMessage>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"

## Country — example instance
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Country>
- **Example subject:** <https://example.org/fi-jp/Country>

**Property values (from example):**
- countryCode (`<https://iri.suomi.fi/model/ktddecv/0.0.4/countryCode>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- countryName (`<https://iri.suomi.fi/model/ktddecv/0.0.4/countryName>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"

## Credit Availability — example instance
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/CreditAvailability>
- **Example subject:** <https://example.org/fi-jp/Credit_Availability>

**Property values (from example):**
- tenor (`<https://iri.suomi.fi/model/ktddecv/0.0.4/tenor>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- obligorParty (`<https://iri.suomi.fi/model/ktddecv/0.0.4/obligorParty>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- availableWithQualifier (`<https://iri.suomi.fi/model/ktddecv/0.0.4/availableWithQualifier>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- draweeParty (`<https://iri.suomi.fi/model/ktddecv/0.0.4/draweeParty>`): <https://example.org/fi-jp/Party> — **Example Party**
- hasAvailabilityMethod (`<https://iri.suomi.fi/model/ktddecv/0.0.4/hasAvailabilityMethod>`): <https://example.org/fi-jp/AvailabilityMethod> — **Example AvailabilityMethod**
- availableWithParty (`<https://iri.suomi.fi/model/ktddecv/0.0.4/availableWithParty>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- hasAmount (`<https://iri.suomi.fi/model/ktddecv/0.0.4/hasAmount>`): "12500000.0"^^<http://www.w3.org/2001/XMLSchema#decimal>
- availableAtPlace (`<https://iri.suomi.fi/model/ktddecv/0.0.4/availableAtPlace>`): "Tokyo (JP TYOKO)"
- maturityDate (`<https://iri.suomi.fi/model/ktddecv/0.0.4/maturityDate>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- payeeParty (`<https://iri.suomi.fi/model/ktddecv/0.0.4/payeeParty>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"

## Delivery Milestone — example instance
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/DeliveryMilestone>
- **Example subject:** <https://example.org/fi-jp/Delivery_Milestone>

**Property values (from example):**
- hasShipmentPeriod (`<https://iri.suomi.fi/model/ktddecv/0.0.4/hasShipmentPeriod>`): <https://example.org/fi-jp/PeriodOfTime> — **Example PeriodOfTime**

## Document — example instance
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Document>
- **Example subject:** <https://example.org/fi-jp/Document>

**Property values (from example):**
- documentDate (`<https://iri.suomi.fi/model/ktddecv/0.0.4/documentDate>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- documentIdentifier (`<https://iri.suomi.fi/model/ktddecv/0.0.4/documentIdentifier>`): "FI1234567-8"

## Document Requirement — example instance
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/DocumentRequirement>
- **Example subject:** <https://example.org/fi-jp/Document_Requirement>

**Property values (from example):**
- requiredDocumentType (`<https://iri.suomi.fi/model/ktddecv/0.0.4/requiredDocumentType>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- issuerParty (`<https://iri.suomi.fi/model/ktddecv/0.0.4/issuerParty>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- numberOfCopies (`<https://iri.suomi.fi/model/ktddecv/0.0.4/numberOfCopies>`): "FI1234567-8"
- numberOfOriginals (`<https://iri.suomi.fi/model/ktddecv/0.0.4/numberOfOriginals>`): "FI1234567-8"

## Documentary Credit — example instance
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/DocumentaryCredit>
- **Example subject:** <https://example.org/fi-jp/Documentary_Credit>

**Property values (from example):**
- confirmationAddedDate (`<https://iri.suomi.fi/model/ktddecv/0.0.4/confirmationAddedDate>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- hasPaymentTerms (`<https://iri.suomi.fi/model/ktddecv/0.0.4/hasPaymentTerms>`): <https://example.org/fi-jp/PaymentTerms> — **Example PaymentTerms**
- hasAvailabilityMethod (`<https://iri.suomi.fi/model/ktddecv/0.0.4/hasAvailabilityMethod>`): <https://example.org/fi-jp/AvailabilityMethod> — **Example AvailabilityMethod**
- additionalAmountsCovered (`<https://iri.suomi.fi/model/ktddecv/0.0.4/additionalAmountsCovered>`): <https://example.org/fi-jp/AdditionalAmountCategory> — **Example AdditionalAmountCategory**
- requestedConfirmationParty (`<https://iri.suomi.fi/model/ktddecv/0.0.4/requestedConfirmationParty>`): <https://example.org/fi-jp/Party> — **Example Party**
- hasShipment (`<https://iri.suomi.fi/model/ktddecv/0.0.4/hasShipment>`): <https://example.org/fi-jp/Shipment> — **Example Shipment**
- advisingBankParty (`<https://iri.suomi.fi/model/ktddecv/0.0.4/advisingBankParty>`): <https://example.org/fi-jp/Party> — **Example Party**
- reimbursingBankParty (`<https://iri.suomi.fi/model/ktddecv/0.0.4/reimbursingBankParty>`): <https://example.org/fi-jp/Party> — **Example Party**
- coversAdditionalCharge (`<https://iri.suomi.fi/model/ktddecv/0.0.4/coversAdditionalCharge>`): <https://example.org/fi-jp/AllowanceCharge> — **Example AllowanceCharge**
- applicantParty (`<https://iri.suomi.fi/model/ktddecv/0.0.4/applicantParty>`): <https://example.org/fi-jp/Party> — **Example Party**
- presentationPeriodDays (`<https://iri.suomi.fi/model/ktddecv/0.0.4/presentationPeriodDays>`): "21"^^<http://www.w3.org/2001/XMLSchema#integer>
- hasCreditAvailability (`<https://iri.suomi.fi/model/ktddecv/0.0.4/hasCreditAvailability>`): <https://example.org/fi-jp/CreditAvailability> — **Example CreditAvailability**
- requiresDocument (`<https://iri.suomi.fi/model/ktddecv/0.0.4/requiresDocument>`): <https://example.org/fi-jp/DocumentRequirement> — **Example DocumentRequirement**
- partialShipmentAllowed (`<https://iri.suomi.fi/model/ktddecv/0.0.4/partialShipmentAllowed>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- hasPresentationPeriod (`<https://iri.suomi.fi/model/ktddecv/0.0.4/hasPresentationPeriod>`): <https://example.org/fi-jp/PeriodOfTime> — **Example PeriodOfTime**
- maximumCreditAmount (`<https://iri.suomi.fi/model/ktddecv/0.0.4/maximumCreditAmount>`): <https://example.org/fi-jp/MonetaryAmount> — **Example MonetaryAmount**
- referencesPreAdvice (`<https://iri.suomi.fi/model/ktddecv/0.0.4/referencesPreAdvice>`): <https://example.org/fi-jp/Document> — **Example Document**
- includesAllowanceCharge (`<https://iri.suomi.fi/model/ktddecv/0.0.4/includesAllowanceCharge>`): <https://example.org/fi-jp/AllowanceCharge> — **Example AllowanceCharge**
- expiryDate (`<https://iri.suomi.fi/model/ktddecv/0.0.4/expiryDate>`): "2025-03-31"^^<http://www.w3.org/2001/XMLSchema#date>
- latestShipmentDate (`<https://iri.suomi.fi/model/ktddecv/0.0.4/latestShipmentDate>`): "2025-02-20"^^<http://www.w3.org/2001/XMLSchema#date>
- issuingBankParty (`<https://iri.suomi.fi/model/ktddecv/0.0.4/issuingBankParty>`): <https://example.org/fi-jp/Party> — **Example Party**
- hasDeliveryMilestone (`<https://iri.suomi.fi/model/ktddecv/0.0.4/hasDeliveryMilestone>`): <https://example.org/fi-jp/DeliveryMilestone> — **Example DeliveryMilestone**
- applicableRules (`<https://iri.suomi.fi/model/ktddecv/0.0.4/applicableRules>`): <https://example.org/fi-jp/RuleSet> — **Example RuleSet**
- issueDate (`<https://iri.suomi.fi/model/ktddecv/0.0.4/issueDate>`): "2025-01-15"^^<http://www.w3.org/2001/XMLSchema#date>
- hasShipmentPeriod (`<https://iri.suomi.fi/model/ktddecv/0.0.4/hasShipmentPeriod>`): <https://example.org/fi-jp/PeriodOfTime> — **Example PeriodOfTime**
- presentationBaseEvent (`<https://iri.suomi.fi/model/ktddecv/0.0.4/presentationBaseEvent>`): <https://example.org/fi-jp/ShipmentBasis> — **Example ShipmentBasis**
- beneficiaryParty (`<https://iri.suomi.fi/model/ktddecv/0.0.4/beneficiaryParty>`): <https://example.org/fi-jp/Party> — **Example Party**
- hasPaymentLine (`<https://iri.suomi.fi/model/ktddecv/0.0.4/hasPaymentLine>`): <https://example.org/fi-jp/PaymentLine> — **Example PaymentLine**
- additionalConditionsText (`<https://iri.suomi.fi/model/ktddecv/0.0.4/additionalConditionsText>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- confirmingParty (`<https://iri.suomi.fi/model/ktddecv/0.0.4/confirmingParty>`): <https://example.org/fi-jp/Party> — **Example Party**
- confirmationInstructionCode (`<https://iri.suomi.fi/model/ktddecv/0.0.4/confirmationInstructionCode>`): <https://example.org/fi-jp/Concept> — **Example Concept**
- creditAmountTolerancePercentage (`<https://iri.suomi.fi/model/ktddecv/0.0.4/creditAmountTolerancePercentage>`): "12500000.0"^^<http://www.w3.org/2001/XMLSchema#decimal>
- latestPresentationDate (`<https://iri.suomi.fi/model/ktddecv/0.0.4/latestPresentationDate>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- applicantBankParty (`<https://iri.suomi.fi/model/ktddecv/0.0.4/applicantBankParty>`): <https://example.org/fi-jp/Party> — **Example Party**
- placeOfExpiry (`<https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfExpiry>`): <https://example.org/fi-jp/Location> — **Example Location**
- adviseThroughBankParty (`<https://iri.suomi.fi/model/ktddecv/0.0.4/adviseThroughBankParty>`): <https://example.org/fi-jp/Party> — **Example Party**
- draweeParty (`<https://iri.suomi.fi/model/ktddecv/0.0.4/draweeParty>`): <https://example.org/fi-jp/Party> — **Example Party**
- placeOfPresentation (`<https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfPresentation>`): <https://example.org/fi-jp/Location> — **Example Location**
- documentaryCreditTypeCode (`<https://iri.suomi.fi/model/ktddecv/0.0.4/documentaryCreditTypeCode>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- creditIdentifier (`<https://iri.suomi.fi/model/ktddecv/0.0.4/creditIdentifier>`): "FI1234567-8"
- instructionToBank (`<https://iri.suomi.fi/model/ktddecv/0.0.4/instructionToBank>`): <https://example.org/fi-jp/BankInstruction> — **Example BankInstruction**
- transshipmentAllowed (`<https://iri.suomi.fi/model/ktddecv/0.0.4/transshipmentAllowed>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"

## Duty/Tax/Fee — example instance
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/DutyTaxFee>
- **Example subject:** <https://example.org/fi-jp/Duty_Tax_Fee>

_No property constraints attached to this node shape._

## Goods Item — example instance
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/GoodsItem>
- **Example subject:** <https://example.org/fi-jp/Goods_Item>

**Property values (from example):**
- descriptionOfGoodsText (`<https://iri.suomi.fi/model/ktddecv/0.0.4/descriptionOfGoodsText>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- hasQuantity (`<https://iri.suomi.fi/model/ktddecv/0.0.4/hasQuantity>`): "250"^^<http://www.w3.org/2001/XMLSchema#integer>
- hasDangerousGoodsDetails (`<https://iri.suomi.fi/model/ktddecv/0.0.4/hasDangerousGoodsDetails>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- productIdentifier (`<https://iri.suomi.fi/model/ktddecv/0.0.4/productIdentifier>`): "FI1234567-8"
- itemDescriptionText (`<https://iri.suomi.fi/model/ktddecv/0.0.4/itemDescriptionText>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- appliedCommodityClassification (`<https://iri.suomi.fi/model/ktddecv/0.0.4/appliedCommodityClassification>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- hasCountryOfOrigin (`<https://iri.suomi.fi/model/ktddecv/0.0.4/hasCountryOfOrigin>`): "FI"

## Identifier — example instance
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Identifier>
- **Example subject:** <https://example.org/fi-jp/Identifier>

_No property constraints attached to this node shape._

## Instruction — example instance
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Instruction>
- **Example subject:** <https://example.org/fi-jp/Instruction>

**Property values (from example):**
- instructionText (`<https://iri.suomi.fi/model/ktddecv/0.0.4/instructionText>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- instructingParty (`<https://iri.suomi.fi/model/ktddecv/0.0.4/instructingParty>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- instructedParty (`<https://iri.suomi.fi/model/ktddecv/0.0.4/instructedParty>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"

## Legal Entity — example instance
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/LegalEntity>
- **Example subject:** <https://example.org/fi-jp/Legal_Entity>

_No property constraints attached to this node shape._

## Location — example instance
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Location>
- **Example subject:** <https://example.org/fi-jp/Location>

**Property values (from example):**
- longitude (`<https://iri.suomi.fi/model/ktddecv/0.0.4/longitude>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- timeZone (`<https://iri.suomi.fi/model/ktddecv/0.0.4/timeZone>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- unlocode (`<https://iri.suomi.fi/model/ktddecv/0.0.4/unlocode>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- customsOfficeCode (`<https://iri.suomi.fi/model/ktddecv/0.0.4/customsOfficeCode>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- alternateName (`<https://iri.suomi.fi/model/ktddecv/0.0.4/alternateName>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- portFacilityCode (`<https://iri.suomi.fi/model/ktddecv/0.0.4/portFacilityCode>`): "Tokyo (JP TYOKO)"
- hasAddress (`<https://iri.suomi.fi/model/ktddecv/0.0.4/hasAddress>`): <https://example.org/fi-jp/Address> — **Example Address**
- locationCountry (`<https://iri.suomi.fi/model/ktddecv/0.0.4/locationCountry>`): <https://example.org/fi-jp/Country> — **Example Country**
- borderCrossingPointCode (`<https://iri.suomi.fi/model/ktddecv/0.0.4/borderCrossingPointCode>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- iataCode (`<https://iri.suomi.fi/model/ktddecv/0.0.4/iataCode>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- geoWKT (`<https://iri.suomi.fi/model/ktddecv/0.0.4/geoWKT>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- uicStationCode (`<https://iri.suomi.fi/model/ktddecv/0.0.4/uicStationCode>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- elevationMeters (`<https://iri.suomi.fi/model/ktddecv/0.0.4/elevationMeters>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- description (`<https://iri.suomi.fi/model/ktddecv/0.0.4/description>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- locationID (`<https://iri.suomi.fi/model/ktddecv/0.0.4/locationID>`): "FI1234567-8"
- icaoAirportCode (`<https://iri.suomi.fi/model/ktddecv/0.0.4/icaoAirportCode>`): "Tokyo (JP TYOKO)"
- postCode (`<https://iri.suomi.fi/model/ktddecv/0.0.4/postCode>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- locationName (`<https://iri.suomi.fi/model/ktddecv/0.0.4/locationName>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- terminalCode (`<https://iri.suomi.fi/model/ktddecv/0.0.4/terminalCode>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- latitude (`<https://iri.suomi.fi/model/ktddecv/0.0.4/latitude>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- hasIdentifier (`<https://iri.suomi.fi/model/ktddecv/0.0.4/hasIdentifier>`): <https://example.org/fi-jp/Identifier> — **Example Identifier**
- warehouseGLN (`<https://iri.suomi.fi/model/ktddecv/0.0.4/warehouseGLN>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"

## Monetary Amount — example instance
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/MonetaryAmount>
- **Example subject:** <https://example.org/fi-jp/Monetary_Amount>

**Property values (from example):**
- amountValue (`<https://iri.suomi.fi/model/ktddecv/0.0.4/amountValue>`): "12500000.0"^^<http://www.w3.org/2001/XMLSchema#decimal>
- currencyCode (`<https://iri.suomi.fi/model/ktddecv/0.0.4/currencyCode>`): "JPY"

## Party — example instance
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Party>
- **Example subject:** <https://example.org/fi-jp/Party>

**Property values (from example):**
- name (`<https://iri.suomi.fi/model/ktddecv/0.0.4/name>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- partyLegalEntity (`<https://iri.suomi.fi/model/ktddecv/0.0.4/partyLegalEntity>`): <https://example.org/fi-jp/LegalEntity> — **Example LegalEntity**
- partyAddress (`<https://iri.suomi.fi/model/ktddecv/0.0.4/partyAddress>`): <https://example.org/fi-jp/Address> — **Example Address**
- partyIdentifier (`<https://iri.suomi.fi/model/ktddecv/0.0.4/partyIdentifier>`): <https://example.org/fi-jp/Identifier> — **Example Identifier**

## Payment Line — example instance
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/PaymentLine>
- **Example subject:** <https://example.org/fi-jp/Payment_Line>

**Property values (from example):**
- hasAmount (`<https://iri.suomi.fi/model/ktddecv/0.0.4/hasAmount>`): "12500000.0"^^<http://www.w3.org/2001/XMLSchema#decimal>
- paymentSettlementMethod (`<https://iri.suomi.fi/model/ktddecv/0.0.4/paymentSettlementMethod>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- tenor (`<https://iri.suomi.fi/model/ktddecv/0.0.4/tenor>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- payeeParty (`<https://iri.suomi.fi/model/ktddecv/0.0.4/payeeParty>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- paymentDueDate (`<https://iri.suomi.fi/model/ktddecv/0.0.4/paymentDueDate>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"

## Payment Schedule Line — example instance
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/PaymentScheduleLine>
- **Example subject:** <https://example.org/fi-jp/Payment_Schedule_Line>

**Property values (from example):**
- baseAmount (`<https://iri.suomi.fi/model/ktddecv/0.0.4/baseAmount>`): "12500000.0"^^<http://www.w3.org/2001/XMLSchema#decimal>
- paymentDueDate (`<https://iri.suomi.fi/model/ktddecv/0.0.4/paymentDueDate>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- deferredPaymentDate (`<https://iri.suomi.fi/model/ktddecv/0.0.4/deferredPaymentDate>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- hasAmount (`<https://iri.suomi.fi/model/ktddecv/0.0.4/hasAmount>`): "12500000.0"^^<http://www.w3.org/2001/XMLSchema#decimal>
- amountPercentOfBase (`<https://iri.suomi.fi/model/ktddecv/0.0.4/amountPercentOfBase>`): "12500000.0"^^<http://www.w3.org/2001/XMLSchema#decimal>

## Payment Terms — example instance
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/PaymentTerms>
- **Example subject:** <https://example.org/fi-jp/Payment_Terms>

**Property values (from example):**
- paymentTermCode (`<https://iri.suomi.fi/model/ktddecv/0.0.4/paymentTermCode>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- tenor (`<https://iri.suomi.fi/model/ktddecv/0.0.4/tenor>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- hasPaymentScheduleLine (`<https://iri.suomi.fi/model/ktddecv/0.0.4/hasPaymentScheduleLine>`): <https://example.org/fi-jp/PaymentScheduleLine> — **Example PaymentScheduleLine**
- tenorPeriod (`<https://iri.suomi.fi/model/ktddecv/0.0.4/tenorPeriod>`): "21"^^<http://www.w3.org/2001/XMLSchema#integer>

## Period of Time — example instance
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/PeriodOfTime>
- **Example subject:** <https://example.org/fi-jp/Period_of_Time>

**Property values (from example):**
- startDate (`<https://iri.suomi.fi/model/ktddecv/0.0.4/startDate>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- endDate (`<https://iri.suomi.fi/model/ktddecv/0.0.4/endDate>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"

## Presentation — example instance
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Presentation>
- **Example subject:** <https://example.org/fi-jp/Presentation>

_No property constraints attached to this node shape._

## Rule Set — example instance
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/RuleSet>
- **Example subject:** <https://example.org/fi-jp/Rule_Set>

**Property values (from example):**
- publicationDate (`<https://iri.suomi.fi/model/ktddecv/0.0.4/publicationDate>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- title (`<https://iri.suomi.fi/model/ktddecv/0.0.4/title>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- ruleSetIdentifier (`<https://iri.suomi.fi/model/ktddecv/0.0.4/ruleSetIdentifier>`): "FI1234567-8"
- versionIdentifier (`<https://iri.suomi.fi/model/ktddecv/0.0.4/versionIdentifier>`): "FI1234567-8"
- publisher (`<https://iri.suomi.fi/model/ktddecv/0.0.4/publisher>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"

## Shipment — example instance
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Shipment>
- **Example subject:** <https://example.org/fi-jp/Shipment>

**Property values (from example):**
- buyerParty (`<https://iri.suomi.fi/model/ktddecv/0.0.4/buyerParty>`): <https://example.org/fi-jp/Party> — **Example Party**
- requestedDeliveryPeriod (`<https://iri.suomi.fi/model/ktddecv/0.0.4/requestedDeliveryPeriod>`): "21"^^<http://www.w3.org/2001/XMLSchema#integer>
- placeOfDeliveryUNLocode (`<https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfDeliveryUNLocode>`): "Tokyo (JP TYOKO)"
- isRealizedByConsignment (`<https://iri.suomi.fi/model/ktddecv/0.0.4/isRealizedByConsignment>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- totalTransportHandlingUnitQuantity (`<https://iri.suomi.fi/model/ktddecv/0.0.4/totalTransportHandlingUnitQuantity>`): "250"^^<http://www.w3.org/2001/XMLSchema#integer>
- insuranceValueAmount (`<https://iri.suomi.fi/model/ktddecv/0.0.4/insuranceValueAmount>`): <https://example.org/fi-jp/MonetaryAmount> — **Example MonetaryAmount**
- finalDestinationUNLocode (`<https://iri.suomi.fi/model/ktddecv/0.0.4/finalDestinationUNLocode>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- portOfDischargeUNLocode (`<https://iri.suomi.fi/model/ktddecv/0.0.4/portOfDischargeUNLocode>`): "Tokyo (JP TYOKO)"
- relatedOrder (`<https://iri.suomi.fi/model/ktddecv/0.0.4/relatedOrder>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- invoiceDocument (`<https://iri.suomi.fi/model/ktddecv/0.0.4/invoiceDocument>`): <https://example.org/fi-jp/Document> — **Example Document**
- hasGoodsItem (`<https://iri.suomi.fi/model/ktddecv/0.0.4/hasGoodsItem>`): <https://example.org/fi-jp/GoodsItem> — **Example GoodsItem**
- declaredCustomsValueAmount (`<https://iri.suomi.fi/model/ktddecv/0.0.4/declaredCustomsValueAmount>`): <https://example.org/fi-jp/MonetaryAmount> — **Example MonetaryAmount**
- totalGoodsItemQuantity (`<https://iri.suomi.fi/model/ktddecv/0.0.4/totalGoodsItemQuantity>`): "250"^^<http://www.w3.org/2001/XMLSchema#integer>
- shipmentIdentifier (`<https://iri.suomi.fi/model/ktddecv/0.0.4/shipmentIdentifier>`): "FI1234567-8"
- totalPackageQuantity (`<https://iri.suomi.fi/model/ktddecv/0.0.4/totalPackageQuantity>`): "250"^^<http://www.w3.org/2001/XMLSchema#integer>
- portOfLoadingUNLocode (`<https://iri.suomi.fi/model/ktddecv/0.0.4/portOfLoadingUNLocode>`): "Kotka (FI KTK)"
- placeOfReceiptUNLocode (`<https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfReceiptUNLocode>`): "Tokyo (JP TYOKO)"
- sellerParty (`<https://iri.suomi.fi/model/ktddecv/0.0.4/sellerParty>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- hazardousRiskIndicator (`<https://iri.suomi.fi/model/ktddecv/0.0.4/hazardousRiskIndicator>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- contractNumber (`<https://iri.suomi.fi/model/ktddecv/0.0.4/contractNumber>`): "FI1234567-8"
- hasShipmentPeriod (`<https://iri.suomi.fi/model/ktddecv/0.0.4/hasShipmentPeriod>`): <https://example.org/fi-jp/PeriodOfTime> — **Example PeriodOfTime**
- deliveryTerms (`<https://iri.suomi.fi/model/ktddecv/0.0.4/deliveryTerms>`): <https://example.org/fi-jp/TradeDeliveryTerms> — **Example TradeDeliveryTerms**

## Shipment Basis — example instance
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/ShipmentBasis>
- **Example subject:** <https://example.org/fi-jp/Shipment_Basis>

_No property constraints attached to this node shape._

## Trade Delivery Terms — example instance
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/TradeDeliveryTerms>
- **Example subject:** <https://example.org/fi-jp/Trade_Delivery_Terms>

**Property values (from example):**
- relatesToConsignment (`<https://iri.suomi.fi/model/ktddecv/0.0.4/relatesToConsignment>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- placeOfDischarge (`<https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfDischarge>`): "Tokyo (JP TYOKO)"
- placeOfDelivery (`<https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfDelivery>`): "Tokyo (JP TYOKO)"
- deliveryTermsText (`<https://iri.suomi.fi/model/ktddecv/0.0.4/deliveryTermsText>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- hasDeliveryPeriod (`<https://iri.suomi.fi/model/ktddecv/0.0.4/hasDeliveryPeriod>`): "21"^^<http://www.w3.org/2001/XMLSchema#integer>
- applicableRules (`<https://iri.suomi.fi/model/ktddecv/0.0.4/applicableRules>`): <https://example.org/fi-jp/RuleSet> — **Example RuleSet**
- placeOfLoading (`<https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfLoading>`): "Kotka (FI KTK)"
- incotermsCode (`<https://iri.suomi.fi/model/ktddecv/0.0.4/incotermsCode>`): "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h"
- includesAllowanceCharge (`<https://iri.suomi.fi/model/ktddecv/0.0.4/includesAllowanceCharge>`): <https://example.org/fi-jp/AllowanceCharge> — **Example AllowanceCharge**

---

# KTDDE — SHACL Shapes Documentation (English)

This document summarizes the SHACL shapes in the provided graph and makes the linkage to **KTDDE Core Vocabulary** explicit (targets and paths).

## Namespaces
- **xml:** <http://www.w3.org/XML/1998/namespace>
- **rdf:** <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
- **rdfs:** <http://www.w3.org/2000/01/rdf-schema#>
- **xsd:** <http://www.w3.org/2001/XMLSchema#>
- **dcterms:** <http://purl.org/dc/terms/>
- **owl:** <http://www.w3.org/2002/07/owl#>
- **http:** <http://www.w3.org/2011/http#>
- **dsilc:** <https://iri.suomi.fi/model/dsilc/>
- **suomi-meta:** <https://iri.suomi.fi/model/suomi-meta/>
- **skos:** <http://www.w3.org/2004/02/skos/core#>
- **geo:** <http://www.opengis.net/ont/geosparql#>
- **sh:** <http://www.w3.org/ns/shacl#>
- **ktddecv:** <https://iri.suomi.fi/model/ktddecv/0.0.4/>
- **dcap:** <http://purl.org/ws-mmi-dc/terms/>
- **gs1:** <https://gs1.org/voc/>
- **ktddu:** <https://iri.suomi.fi/model/ktddu/0.0.1/>
- **busdoc:** <https://iri.suomi.fi/model/busdoc/1.0.2/>
- **ktddecv:** <https://iri.suomi.fi/model/ktddecv/>
- **unece:** <https://vocabulary.uncefact.org/>
- **j.0:** <http://xmlns.com/foaf/0.1/>

## Index
- [Node Shapes](#node-shapes)
- [Property Shapes](#property-shapes)
- [Unreferenced Property Shapes](#unreferenced-property-shapes)
- [Crosswalk: Shapes → KTDDE](#crosswalk-shapes--ktdde)

<a id="node-shapes"></a>
## Node Shapes

### Additional Amount Category
- **IRI:** <https://iri.suomi.fi/model/dsilc/AdditionalAmountCategory>
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/AdditionalAmountCategory> — **AdditionalAmountCategory**
- **Name:** Additional Amount Category

### Address
- **IRI:** <https://iri.suomi.fi/model/dsilc/Address>
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Address> — **Address**
- **Name:** Address

### Allowance Charge
- **IRI:** <https://iri.suomi.fi/model/dsilc/AllowanceCharge>
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/AllowanceCharge> — **AllowanceCharge**
- **Name:** Allowance Charge

**Property constraints:**
- **Allowance Charge Reason Code** (<https://iri.suomi.fi/model/dsilc/allowanceChargeReasonCode>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/allowanceChargeReasonCode> — **allowanceChargeReasonCode**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **base amount** (<https://iri.suomi.fi/model/dsilc/baseAmount>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/baseAmount> — **baseAmount**
- **Calculation Percent** (<https://iri.suomi.fi/model/dsilc/calculationPercent>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/calculationPercent> — **calculationPercent**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#decimal>
- **Charge Indicator** (<https://iri.suomi.fi/model/dsilc/chargeIndicator>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/chargeIndicator> — **chargeIndicator**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#boolean>
- **charged by party** (<https://iri.suomi.fi/model/dsilc/chargedByParty>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/chargedByParty> — **chargedByParty**
- **charged to party** (<https://iri.suomi.fi/model/dsilc/chargedToParty>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/chargedToParty> — **chargedToParty**
- **has amount** (<https://iri.suomi.fi/model/dsilc/hasAmount>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasAmount> — **hasAmount**
- **Multiplier Factor Percent** (<https://iri.suomi.fi/model/dsilc/multiplierFactorPercent>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/multiplierFactorPercent> — **multiplierFactorPercent**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#decimal>
- **per unit amount** (<https://iri.suomi.fi/model/dsilc/perUnitAmount>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/perUnitAmount> — **perUnitAmount**

### Availability Method
- **IRI:** <https://iri.suomi.fi/model/dsilc/AvailabilityMethod>
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/AvailabilityMethod> — **AvailabilityMethod**
- **Name:** Availability Method

### Bank Instruction
- **IRI:** <https://iri.suomi.fi/model/dsilc/BankInstruction>
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/BankInstruction> — **BankInstruction**
- **Name:** Bank Instruction

### Business Document
- **IRI:** <https://iri.suomi.fi/model/dsilc/BusinessDocument>
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/BusinessDocument> — **BusinessDocument**
- **Name:** Business Document

**Property constraints:**
- **document type** (<https://iri.suomi.fi/model/dsilc/documentType>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/documentType> — **documentType**
- **has message** (<https://iri.suomi.fi/model/dsilc/hasMessage>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasMessage> — **hasMessage**

### Country
- **IRI:** <https://iri.suomi.fi/model/dsilc/Country>
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Country> — **Country**
- **Name:** Country

**Property constraints:**
- **Country Code** (<https://iri.suomi.fi/model/dsilc/countryCode>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/countryCode> — **countryCode**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Country Name** (<https://iri.suomi.fi/model/dsilc/countryName>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/countryName> — **countryName**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>

### Credit Availability
- **IRI:** <https://iri.suomi.fi/model/dsilc/CreditAvailability>
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/CreditAvailability> — **CreditAvailability**
- **Name:** Credit Availability

**Property constraints:**
- **available at place** (<https://iri.suomi.fi/model/dsilc/availableAtPlace>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/availableAtPlace> — **availableAtPlace**
- **available with party** (<https://iri.suomi.fi/model/dsilc/availableWithParty>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/availableWithParty> — **availableWithParty**
- **available with qualifier** (<https://iri.suomi.fi/model/dsilc/availableWithQualifier>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/availableWithQualifier> — **availableWithQualifier**
- **drawee party** (<https://iri.suomi.fi/model/dsilc/draweeParty>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/draweeParty> — **draweeParty**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Party> — **Party**
- **has amount** (<https://iri.suomi.fi/model/dsilc/hasAmount>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasAmount> — **hasAmount**
- **has availability method** (<https://iri.suomi.fi/model/dsilc/hasAvailabilityMethod>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasAvailabilityMethod> — **hasAvailabilityMethod**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/AvailabilityMethod> — **AvailabilityMethod**
- **Maturity Date** (<https://iri.suomi.fi/model/dsilc/maturityDate>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/maturityDate> — **maturityDate**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#date>
- **obligor party** (<https://iri.suomi.fi/model/dsilc/obligorParty>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/obligorParty> — **obligorParty**
- **payee party** (<https://iri.suomi.fi/model/dsilc/payeeParty>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/payeeParty> — **payeeParty**
- **Tenor** (<https://iri.suomi.fi/model/dsilc/tenor>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/tenor> — **tenor**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>

### Delivery Milestone
- **IRI:** <https://iri.suomi.fi/model/dsilc/DeliveryMilestone>
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/DeliveryMilestone> — **DeliveryMilestone**
- **Name:** Delivery Milestone

**Property constraints:**
- **has shipment period** (<https://iri.suomi.fi/model/dsilc/hasShipmentPeriod>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasShipmentPeriod> — **hasShipmentPeriod**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/PeriodOfTime> — **PeriodOfTime**

### Document
- **IRI:** <https://iri.suomi.fi/model/dsilc/Document>
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Document> — **Document**
- **Name:** Document

**Property constraints:**
- **Document Date** (<https://iri.suomi.fi/model/dsilc/documentDate>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/documentDate> — **documentDate**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#date>
- **Document Identifier** (<https://iri.suomi.fi/model/dsilc/documentIdentifier>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/documentIdentifier> — **documentIdentifier**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>

### Document Requirement
- **IRI:** <https://iri.suomi.fi/model/dsilc/DocumentRequirement>
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/DocumentRequirement> — **DocumentRequirement**
- **Name:** Document Requirement

**Property constraints:**
- **issuer party** (<https://iri.suomi.fi/model/dsilc/issuerParty>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/issuerParty> — **issuerParty**
- **Number of Copies** (<https://iri.suomi.fi/model/dsilc/numberOfCopies>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/numberOfCopies> — **numberOfCopies**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#integer>
- **Number of Originals** (<https://iri.suomi.fi/model/dsilc/numberOfOriginals>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/numberOfOriginals> — **numberOfOriginals**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#integer>
- **required document type** (<https://iri.suomi.fi/model/dsilc/requiredDocumentType>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/requiredDocumentType> — **requiredDocumentType**

### Documentary Credit
- **IRI:** <https://iri.suomi.fi/model/dsilc/DocumentaryCredit>
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/DocumentaryCredit> — **DocumentaryCredit**
- **Name:** Documentary Credit

**Property constraints:**
- **additional amounts covered** (<https://iri.suomi.fi/model/dsilc/additionalAmountsCovered>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/additionalAmountsCovered> — **additionalAmountsCovered**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/AdditionalAmountCategory> — **AdditionalAmountCategory**
- **Additional Conditions Text** (<https://iri.suomi.fi/model/dsilc/AdditionalConditionsText>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/additionalConditionsText> — **additionalConditionsText**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **advise through bank party** (<https://iri.suomi.fi/model/dsilc/adviseThroughBankParty>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/adviseThroughBankParty> — **adviseThroughBankParty**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Party> — **Party**
- **advising bank party** (<https://iri.suomi.fi/model/dsilc/advisingBankParty>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/advisingBankParty> — **advisingBankParty**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Party> — **Party**
- **applicable rules** (<https://iri.suomi.fi/model/dsilc/applicableRules>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/applicableRules> — **applicableRules**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/RuleSet> — **RuleSet**
- **applicant bank party** (<https://iri.suomi.fi/model/dsilc/applicantBankParty>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/applicantBankParty> — **applicantBankParty**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Party> — **Party**
- **applicant party** (<https://iri.suomi.fi/model/dsilc/applicantParty>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/applicantParty> — **applicantParty**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Party> — **Party**
- **beneficiary party** (<https://iri.suomi.fi/model/dsilc/beneficiaryParty>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/beneficiaryParty> — **beneficiaryParty**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Party> — **Party**
- **Confirmation Added Date** (<https://iri.suomi.fi/model/dsilc/confirmationAddedDate>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/confirmationAddedDate> — **confirmationAddedDate**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#date>
- **confirmation instruction code** (<https://iri.suomi.fi/model/dsilc/confirmationInstructionCode>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/confirmationInstructionCode> — **confirmationInstructionCode**
  - **Class:** <http://www.w3.org/2004/02/skos/core#Concept> 
- **confirming party** (<https://iri.suomi.fi/model/dsilc/confirmingParty>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/confirmingParty> — **confirmingParty**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Party> — **Party**
- **covers additional charge** (<https://iri.suomi.fi/model/dsilc/coversAdditionalCharge>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/coversAdditionalCharge> — **coversAdditionalCharge**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/AllowanceCharge> — **AllowanceCharge**
- **Credit Amount Tolerance Percentage** (<https://iri.suomi.fi/model/dsilc/creditAmountTolerancePercentage>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/creditAmountTolerancePercentage> — **creditAmountTolerancePercentage**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#decimal>
- **Credit Identifier** (<https://iri.suomi.fi/model/dsilc/creditIdentifier>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/creditIdentifier> — **creditIdentifier**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Documentary Credit Type Code** (<https://iri.suomi.fi/model/dsilc/documentaryCreditTypeCode>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/documentaryCreditTypeCode> — **documentaryCreditTypeCode**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **drawee party** (<https://iri.suomi.fi/model/dsilc/draweeParty>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/draweeParty> — **draweeParty**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Party> — **Party**
- **Expiry Date** (<https://iri.suomi.fi/model/dsilc/expiryDate>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/expiryDate> — **expiryDate**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#date>
- **has availability method** (<https://iri.suomi.fi/model/dsilc/hasAvailabilityMethod>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasAvailabilityMethod> — **hasAvailabilityMethod**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/AvailabilityMethod> — **AvailabilityMethod**
- **has credit availability** (<https://iri.suomi.fi/model/dsilc/hasCreditAvailability>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasCreditAvailability> — **hasCreditAvailability**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/CreditAvailability> — **CreditAvailability**
- **has delivery milestone** (<https://iri.suomi.fi/model/dsilc/hasDeliveryMilestone>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasDeliveryMilestone> — **hasDeliveryMilestone**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/DeliveryMilestone> — **DeliveryMilestone**
- **has payment line** (<https://iri.suomi.fi/model/dsilc/hasPaymentLine>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasPaymentLine> — **hasPaymentLine**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/PaymentLine> — **PaymentLine**
- **has payment terms** (<https://iri.suomi.fi/model/dsilc/hasPaymentTerms>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasPaymentTerms> — **hasPaymentTerms**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/PaymentTerms> — **PaymentTerms**
- **has presentation period** (<https://iri.suomi.fi/model/dsilc/hasPresentationPeriod>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasPresentationPeriod> — **hasPresentationPeriod**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/PeriodOfTime> — **PeriodOfTime**
- **has shipment** (<https://iri.suomi.fi/model/dsilc/hasShipment>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasShipment> — **hasShipment**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Shipment> — **Shipment**
- **has shipment period** (<https://iri.suomi.fi/model/dsilc/hasShipmentPeriod>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasShipmentPeriod> — **hasShipmentPeriod**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/PeriodOfTime> — **PeriodOfTime**
- **includes allowance charge** (<https://iri.suomi.fi/model/dsilc/includesAllowanceCharge>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/includesAllowanceCharge> — **includesAllowanceCharge**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/AllowanceCharge> — **AllowanceCharge**
- **instruction to bank** (<https://iri.suomi.fi/model/dsilc/instructionToBank>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/instructionToBank> — **instructionToBank**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/BankInstruction> — **BankInstruction**
- **Issue Date** (<https://iri.suomi.fi/model/dsilc/issueDate>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/issueDate> — **issueDate**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#date>
  - **minCount:** 1
  - **maxCount:** 1
- **issuing bank party** (<https://iri.suomi.fi/model/dsilc/issuingBankParty>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/issuingBankParty> — **issuingBankParty**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Party> — **Party**
- **Latest Presentation Date** (<https://iri.suomi.fi/model/dsilc/latestPresentationDate>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/latestPresentationDate> — **latestPresentationDate**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#date>
- **Latest Shipment Date** (<https://iri.suomi.fi/model/dsilc/latestShipmentDate>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/latestShipmentDate> — **latestShipmentDate**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#date>
- **maximum credit amount** (<https://iri.suomi.fi/model/dsilc/maximumCreditAmount>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/maximumCreditAmount> — **maximumCreditAmount**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/MonetaryAmount> — **MonetaryAmount**
- **Partial Shipment Allowed** (<https://iri.suomi.fi/model/dsilc/partialShipmentAllowed>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/partialShipmentAllowed> — **partialShipmentAllowed**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#boolean>
- **place of expiry** (<https://iri.suomi.fi/model/dsilc/placeOfExpiry>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfExpiry> — **placeOfExpiry**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Location> — **Location**
- **place of presentation** (<https://iri.suomi.fi/model/dsilc/placeOfPresentation>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfPresentation> — **placeOfPresentation**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Location> — **Location**
- **presentation base event** (<https://iri.suomi.fi/model/dsilc/presentationBaseEvent>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/presentationBaseEvent> — **presentationBaseEvent**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/ShipmentBasis> — **ShipmentBasis**
- **Presentation Period Days** (<https://iri.suomi.fi/model/dsilc/presentationPeriodDays>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/presentationPeriodDays> — **presentationPeriodDays**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#integer>
- **references pre advice** (<https://iri.suomi.fi/model/dsilc/referencesPreAdvice>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/referencesPreAdvice> — **referencesPreAdvice**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Document> — **Document**
- **reimbursing bank party** (<https://iri.suomi.fi/model/dsilc/reimbursingBankParty>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/reimbursingBankParty> — **reimbursingBankParty**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Party> — **Party**
- **requested confirmation party** (<https://iri.suomi.fi/model/dsilc/requestedConfirmationParty>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/requestedConfirmationParty> — **requestedConfirmationParty**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Party> — **Party**
- **requires document** (<https://iri.suomi.fi/model/dsilc/requiresDocument>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/requiresDocument> — **requiresDocument**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/DocumentRequirement> — **DocumentRequirement**
- **Transshipment Allowed** (<https://iri.suomi.fi/model/dsilc/transshipmentAllowed>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/transshipmentAllowed> — **transshipmentAllowed**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#boolean>

### Duty/Tax/Fee
- **IRI:** <https://iri.suomi.fi/model/dsilc/DutyTaxFee>
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/DutyTaxFee> — **DutyTaxFee**
- **Name:** Duty/Tax/Fee

### Goods Item
- **IRI:** <https://iri.suomi.fi/model/dsilc/GoodsItem>
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/GoodsItem> — **GoodsItem**
- **Name:** Goods Item

**Property constraints:**
- **applied commodity classification** (<https://iri.suomi.fi/model/dsilc/appliedCommodityClassification>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/appliedCommodityClassification> — **appliedCommodityClassification**
- **Description of Goods Text** (<https://iri.suomi.fi/model/dsilc/descriptionOfGoodsText>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/descriptionOfGoodsText> — **descriptionOfGoodsText**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **has country of origin** (<https://iri.suomi.fi/model/dsilc/hasCountryOfOrigin>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasCountryOfOrigin> — **hasCountryOfOrigin**
- **has dangerous goods details** (<https://iri.suomi.fi/model/dsilc/hasDangerousGoodsDetails>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasDangerousGoodsDetails> — **hasDangerousGoodsDetails**
- **has quantity** (<https://iri.suomi.fi/model/dsilc/hasQuantity>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasQuantity> — **hasQuantity**
- **Item Description Text** (<https://iri.suomi.fi/model/dsilc/itemDescriptionText>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/itemDescriptionText> — **itemDescriptionText**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Product Identifier** (<https://iri.suomi.fi/model/dsilc/productIdentifier>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/productIdentifier> — **productIdentifier**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>

### Identifier
- **IRI:** <https://iri.suomi.fi/model/dsilc/Identifier>
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Identifier> — **Identifier**
- **Name:** Identifier

### Instruction
- **IRI:** <https://iri.suomi.fi/model/dsilc/Instruction>
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Instruction> — **Instruction**
- **Name:** Instruction

**Property constraints:**
- **instructed party** (<https://iri.suomi.fi/model/dsilc/instructedParty>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/instructedParty> — **instructedParty**
- **instructing party** (<https://iri.suomi.fi/model/dsilc/instructingParty>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/instructingParty> — **instructingParty**
- **Instruction Text** (<https://iri.suomi.fi/model/dsilc/instructionText>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/instructionText> — **instructionText**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>

### Legal Entity
- **IRI:** <https://iri.suomi.fi/model/dsilc/LegalEntity>
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/LegalEntity> — **LegalEntity**
- **Name:** Legal Entity

### Location
- **IRI:** <https://iri.suomi.fi/model/dsilc/Location>
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Location> — **Location**
- **Name:** Location

**Property constraints:**
- **Alternate Name** (<https://iri.suomi.fi/model/dsilc/alternateName>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/alternateName> — **alternateName**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Border Crossing Point Code** (<https://iri.suomi.fi/model/dsilc/borderCrossingPointCode>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/borderCrossingPointCode> — **borderCrossingPointCode**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Customs Office Code** (<https://iri.suomi.fi/model/dsilc/customsOfficeCode>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/customsOfficeCode> — **customsOfficeCode**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Description** (<https://iri.suomi.fi/model/dsilc/description>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/description> — **description**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Elevation Meters** (<https://iri.suomi.fi/model/dsilc/elevationMeters>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/elevationMeters> — **elevationMeters**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#decimal>
- **Geo WKT** (<https://iri.suomi.fi/model/dsilc/geoWKT>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/geoWKT> — **geoWKT**
  - **Datatype:** <http://www.opengis.net/ont/geosparql#wktLiteral>
- **has Address** (<https://iri.suomi.fi/model/dsilc/hasAddress>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasAddress> — **hasAddress**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Address> — **Address**
- **has identifier** (<https://iri.suomi.fi/model/dsilc/hasIdentifier>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasIdentifier> — **hasIdentifier**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Identifier> — **Identifier**
- **IATA Code** (<https://iri.suomi.fi/model/dsilc/iataCode>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/iataCode> — **iataCode**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **ICAO Airport Code** (<https://iri.suomi.fi/model/dsilc/icaoAirportCode>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/icaoAirportCode> — **icaoAirportCode**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Latitude** (<https://iri.suomi.fi/model/dsilc/latitude>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/latitude> — **latitude**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#decimal>
- **location country** (<https://iri.suomi.fi/model/dsilc/locationCountry>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/locationCountry> — **locationCountry**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Country> — **Country**
- **Location ID** (<https://iri.suomi.fi/model/dsilc/locationID>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/locationID> — **locationID**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Location Name** (<https://iri.suomi.fi/model/dsilc/locationName>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/locationName> — **locationName**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Longitude** (<https://iri.suomi.fi/model/dsilc/longitude>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/longitude> — **longitude**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#decimal>
- **Port Facility Code** (<https://iri.suomi.fi/model/dsilc/portFacilityCode>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/portFacilityCode> — **portFacilityCode**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Post Code** (<https://iri.suomi.fi/model/dsilc/postCode>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/postCode> — **postCode**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Terminal Code** (<https://iri.suomi.fi/model/dsilc/terminalCode>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/terminalCode> — **terminalCode**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Time Zone** (<https://iri.suomi.fi/model/dsilc/timeZone>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/timeZone> — **timeZone**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **UIC Station Code** (<https://iri.suomi.fi/model/dsilc/uicStationCode>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/uicStationCode> — **uicStationCode**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **UN Locode** (<https://iri.suomi.fi/model/dsilc/unlocode>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/unlocode> — **unlocode**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Warehouse GLN** (<https://iri.suomi.fi/model/dsilc/warehouseGLN>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/warehouseGLN> — **warehouseGLN**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>

### Monetary Amount
- **IRI:** <https://iri.suomi.fi/model/dsilc/MonetaryAmount>
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/MonetaryAmount> — **MonetaryAmount**
- **Name:** Monetary Amount

**Property constraints:**
- **Amount Value** (<https://iri.suomi.fi/model/dsilc/amountValue>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/amountValue> — **amountValue**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#decimal>
- **Currency Code** (<https://iri.suomi.fi/model/dsilc/currencyCode>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/currencyCode> — **currencyCode**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>

### Party
- **IRI:** <https://iri.suomi.fi/model/dsilc/Party>
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Party> — **Party**
- **Name:** Party

**Property constraints:**
- **Name** (<https://iri.suomi.fi/model/dsilc/name>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/name> — **name**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **party address** (<https://iri.suomi.fi/model/dsilc/partyAddress>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/partyAddress> — **partyAddress**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Address> — **Address**
- **party identifier** (<https://iri.suomi.fi/model/dsilc/partyIdentifier>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/partyIdentifier> — **partyIdentifier**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Identifier> — **Identifier**
- **party legal entity** (<https://iri.suomi.fi/model/dsilc/partyLegalEntity>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/partyLegalEntity> — **partyLegalEntity**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/LegalEntity> — **LegalEntity**

### Payment Line
- **IRI:** <https://iri.suomi.fi/model/dsilc/PaymentLine>
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/PaymentLine> — **PaymentLine**
- **Name:** Payment Line

**Property constraints:**
- **has amount** (<https://iri.suomi.fi/model/dsilc/hasAmount>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasAmount> — **hasAmount**
- **payee party** (<https://iri.suomi.fi/model/dsilc/payeeParty>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/payeeParty> — **payeeParty**
- **Payment Due Date** (<https://iri.suomi.fi/model/dsilc/paymentDueDate>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/paymentDueDate> — **paymentDueDate**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#date>
- **payment settlement method** (<https://iri.suomi.fi/model/dsilc/paymentSettlementMethod>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/paymentSettlementMethod> — **paymentSettlementMethod**
- **Tenor** (<https://iri.suomi.fi/model/dsilc/tenor>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/tenor> — **tenor**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>

### Payment Schedule Line
- **IRI:** <https://iri.suomi.fi/model/dsilc/PaymentScheduleLine>
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/PaymentScheduleLine> — **PaymentScheduleLine**
- **Name:** Payment Schedule Line

**Property constraints:**
- **Amount Percent Of Base** (<https://iri.suomi.fi/model/dsilc/amountPercentOfBase>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/amountPercentOfBase> — **amountPercentOfBase**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#decimal>
- **base amount** (<https://iri.suomi.fi/model/dsilc/baseAmount>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/baseAmount> — **baseAmount**
- **Deferred Payment Date** (<https://iri.suomi.fi/model/dsilc/deferredPaymentDate>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/deferredPaymentDate> — **deferredPaymentDate**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#date>
- **has amount** (<https://iri.suomi.fi/model/dsilc/hasAmount>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasAmount> — **hasAmount**
- **Payment Due Date** (<https://iri.suomi.fi/model/dsilc/paymentDueDate>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/paymentDueDate> — **paymentDueDate**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#date>

### Payment Terms
- **IRI:** <https://iri.suomi.fi/model/dsilc/PaymentTerms>
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/PaymentTerms> — **PaymentTerms**
- **Name:** Payment Terms

**Property constraints:**
- **has payment schedule line** (<https://iri.suomi.fi/model/dsilc/hasPaymentScheduleLine>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasPaymentScheduleLine> — **hasPaymentScheduleLine**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/PaymentScheduleLine> — **PaymentScheduleLine**
- **Payment Term Code** (<https://iri.suomi.fi/model/dsilc/paymentTermCode>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/paymentTermCode> — **paymentTermCode**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Tenor** (<https://iri.suomi.fi/model/dsilc/tenor>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/tenor> — **tenor**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **tenor period** (<https://iri.suomi.fi/model/dsilc/tenorPeriod>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/tenorPeriod> — **tenorPeriod**

### Period of Time
- **IRI:** <https://iri.suomi.fi/model/dsilc/PeriodOfTime>
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/PeriodOfTime> — **PeriodOfTime**
- **Name:** Period of Time

**Property constraints:**
- **End Date** (<https://iri.suomi.fi/model/dsilc/endDate>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/endDate> — **endDate**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#date>
- **Start Date** (<https://iri.suomi.fi/model/dsilc/startDate>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/startDate> — **startDate**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#date>

### Presentation
- **IRI:** <https://iri.suomi.fi/model/dsilc/Presentation>
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Presentation> — **Presentation**
- **Name:** Presentation

### Rule Set
- **IRI:** <https://iri.suomi.fi/model/dsilc/RuleSet>
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/RuleSet> — **RuleSet**
- **Name:** Rule Set

**Property constraints:**
- **Publication Date** (<https://iri.suomi.fi/model/dsilc/publicationDate>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/publicationDate> — **publicationDate**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#date>
- **publisher** (<https://iri.suomi.fi/model/dsilc/publisher>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/publisher> — **publisher**
- **Rule Set Identifier** (<https://iri.suomi.fi/model/dsilc/ruleSetIdentifier>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/ruleSetIdentifier> — **ruleSetIdentifier**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Title** (<https://iri.suomi.fi/model/dsilc/title>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/title> — **title**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Version Identifier** (<https://iri.suomi.fi/model/dsilc/versionIdentifier>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/versionIdentifier> — **versionIdentifier**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>

### Shipment
- **IRI:** <https://iri.suomi.fi/model/dsilc/Shipment>
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Shipment> — **Shipment**
- **Name:** Shipment

**Property constraints:**
- **buyer party** (<https://iri.suomi.fi/model/dsilc/buyerParty>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/buyerParty> — **buyerParty**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Party> — **Party**
- **Contract Number** (<https://iri.suomi.fi/model/dsilc/contractNumber>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/contractNumber> — **contractNumber**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
  - **minCount:** 1
  - **maxCount:** 1
- **declared customs value amount** (<https://iri.suomi.fi/model/dsilc/declaredCustomsValueAmount>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/declaredCustomsValueAmount> — **declaredCustomsValueAmount**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/MonetaryAmount> — **MonetaryAmount**
- **delivery terms** (<https://iri.suomi.fi/model/dsilc/deliveryTerms>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/deliveryTerms> — **deliveryTerms**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/TradeDeliveryTerms> — **TradeDeliveryTerms**
- **Final Destination UN Locode** (<https://iri.suomi.fi/model/dsilc/finalDestinationUNLocode>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/finalDestinationUNLocode> — **finalDestinationUNLocode**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **has goods item** (<https://iri.suomi.fi/model/dsilc/hasGoodsItem>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasGoodsItem> — **hasGoodsItem**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/GoodsItem> — **GoodsItem**
- **has shipment period** (<https://iri.suomi.fi/model/dsilc/hasShipmentPeriod>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasShipmentPeriod> — **hasShipmentPeriod**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/PeriodOfTime> — **PeriodOfTime**
- **Hazardous Risk Indicator** (<https://iri.suomi.fi/model/dsilc/hazardousRiskIndicator>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hazardousRiskIndicator> — **hazardousRiskIndicator**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#boolean>
- **insurance value amount** (<https://iri.suomi.fi/model/dsilc/insuranceValueAmount>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/insuranceValueAmount> — **insuranceValueAmount**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/MonetaryAmount> — **MonetaryAmount**
- **invoice document** (<https://iri.suomi.fi/model/dsilc/invoiceDocument>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/invoiceDocument> — **invoiceDocument**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Document> — **Document**
- **is realized by consignment** (<https://iri.suomi.fi/model/dsilc/isRealizedByConsignment>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/isRealizedByConsignment> — **isRealizedByConsignment**
- **Place of Delivery UN Locode** (<https://iri.suomi.fi/model/dsilc/placeOfDeliveryUNLocode>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfDeliveryUNLocode> — **placeOfDeliveryUNLocode**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Place of Receipt UN Locode** (<https://iri.suomi.fi/model/dsilc/placeOfReceiptUNLocode>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfReceiptUNLocode> — **placeOfReceiptUNLocode**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Port Of Discharge UN Locode** (<https://iri.suomi.fi/model/dsilc/portOfDischargeUNLocode>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/portOfDischargeUNLocode> — **portOfDischargeUNLocode**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Port of Loading UN Locode** (<https://iri.suomi.fi/model/dsilc/portOfLoadingUNLocode>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/portOfLoadingUNLocode> — **portOfLoadingUNLocode**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **related order** (<https://iri.suomi.fi/model/dsilc/relatedOrder>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/relatedOrder> — **relatedOrder**
- **requested delivery period** (<https://iri.suomi.fi/model/dsilc/requestedDeliveryPeriod>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/requestedDeliveryPeriod> — **requestedDeliveryPeriod**
- **seller party** (<https://iri.suomi.fi/model/dsilc/sellerParty>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/sellerParty> — **sellerParty**
- **Shipment Identifier** (<https://iri.suomi.fi/model/dsilc/shipmentIdentifier>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/shipmentIdentifier> — **shipmentIdentifier**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **total goods item quantity** (<https://iri.suomi.fi/model/dsilc/totalGoodsItemQuantity>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/totalGoodsItemQuantity> — **totalGoodsItemQuantity**
- **total package quantity** (<https://iri.suomi.fi/model/dsilc/totalPackageQuantity>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/totalPackageQuantity> — **totalPackageQuantity**
- **total transport handling unit quantity** (<https://iri.suomi.fi/model/dsilc/totalTransportHandlingUnitQuantity>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/totalTransportHandlingUnitQuantity> — **totalTransportHandlingUnitQuantity**

### Shipment Basis
- **IRI:** <https://iri.suomi.fi/model/dsilc/ShipmentBasis>
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/ShipmentBasis> — **ShipmentBasis**
- **Name:** Shipment Basis

### Trade Delivery Terms
- **IRI:** <https://iri.suomi.fi/model/dsilc/TradeDeliveryTerms>
- **Target class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/TradeDeliveryTerms> — **TradeDeliveryTerms**
- **Name:** Trade Delivery Terms

**Property constraints:**
- **applicable rules** (<https://iri.suomi.fi/model/dsilc/applicableRules>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/applicableRules> — **applicableRules**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/RuleSet> — **RuleSet**
- **Delivery Terms Text** (<https://iri.suomi.fi/model/dsilc/deliveryTermsText>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/deliveryTermsText> — **deliveryTermsText**
  - **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **has delivery period** (<https://iri.suomi.fi/model/dsilc/hasDeliveryPeriod>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasDeliveryPeriod> — **hasDeliveryPeriod**
- **includes allowance charge** (<https://iri.suomi.fi/model/dsilc/includesAllowanceCharge>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/includesAllowanceCharge> — **includesAllowanceCharge**
  - **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/AllowanceCharge> — **AllowanceCharge**
- **incoterms code** (<https://iri.suomi.fi/model/dsilc/incotermsCode>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/incotermsCode> — **incotermsCode**
- **place of delivery** (<https://iri.suomi.fi/model/dsilc/placeOfDelivery>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfDelivery> — **placeOfDelivery**
- **place of discharge** (<https://iri.suomi.fi/model/dsilc/placeOfDischarge>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfDischarge> — **placeOfDischarge**
- **place of loading** (<https://iri.suomi.fi/model/dsilc/placeOfLoading>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfLoading> — **placeOfLoading**
- **relates to consignment** (<https://iri.suomi.fi/model/dsilc/relatesToConsignment>)
  - **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/relatesToConsignment> — **relatesToConsignment**

<a id="property-shapes"></a>
## Property Shapes

### additional amounts covered
- **IRI:** <https://iri.suomi.fi/model/dsilc/additionalAmountsCovered>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/additionalAmountsCovered> — **additionalAmountsCovered**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/AdditionalAmountCategory> — **AdditionalAmountCategory**
- **Name:** additional amounts covered

### Additional Conditions Text
- **IRI:** <https://iri.suomi.fi/model/dsilc/AdditionalConditionsText>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/additionalConditionsText> — **additionalConditionsText**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Additional Conditions Text

### advise through bank party
- **IRI:** <https://iri.suomi.fi/model/dsilc/adviseThroughBankParty>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/adviseThroughBankParty> — **adviseThroughBankParty**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Party> — **Party**
- **Name:** advise through bank party

### advising bank party
- **IRI:** <https://iri.suomi.fi/model/dsilc/advisingBankParty>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/advisingBankParty> — **advisingBankParty**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Party> — **Party**
- **Name:** advising bank party

### Allowance Charge Reason Code
- **IRI:** <https://iri.suomi.fi/model/dsilc/allowanceChargeReasonCode>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/allowanceChargeReasonCode> — **allowanceChargeReasonCode**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Allowance Charge Reason Code

### Alternate Name
- **IRI:** <https://iri.suomi.fi/model/dsilc/alternateName>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/alternateName> — **alternateName**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Alternate Name

### Amount Percent Of Base
- **IRI:** <https://iri.suomi.fi/model/dsilc/amountPercentOfBase>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/amountPercentOfBase> — **amountPercentOfBase**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#decimal>
- **Name:** Amount Percent Of Base

### Amount Value
- **IRI:** <https://iri.suomi.fi/model/dsilc/amountValue>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/amountValue> — **amountValue**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#decimal>
- **Name:** Amount Value

### applicable rules
- **IRI:** <https://iri.suomi.fi/model/dsilc/applicableRules>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/applicableRules> — **applicableRules**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/RuleSet> — **RuleSet**
- **Name:** applicable rules

### applicant bank party
- **IRI:** <https://iri.suomi.fi/model/dsilc/applicantBankParty>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/applicantBankParty> — **applicantBankParty**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Party> — **Party**
- **Name:** applicant bank party

### applicant party
- **IRI:** <https://iri.suomi.fi/model/dsilc/applicantParty>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/applicantParty> — **applicantParty**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Party> — **Party**
- **Name:** applicant party

### applied commodity classification
- **IRI:** <https://iri.suomi.fi/model/dsilc/appliedCommodityClassification>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/appliedCommodityClassification> — **appliedCommodityClassification**
- **Name:** applied commodity classification

### available at place
- **IRI:** <https://iri.suomi.fi/model/dsilc/availableAtPlace>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/availableAtPlace> — **availableAtPlace**
- **Name:** available at place

### available with party
- **IRI:** <https://iri.suomi.fi/model/dsilc/availableWithParty>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/availableWithParty> — **availableWithParty**
- **Name:** available with party

### available with qualifier
- **IRI:** <https://iri.suomi.fi/model/dsilc/availableWithQualifier>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/availableWithQualifier> — **availableWithQualifier**
- **Name:** available with qualifier

### base amount
- **IRI:** <https://iri.suomi.fi/model/dsilc/baseAmount>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/baseAmount> — **baseAmount**
- **Name:** base amount

### beneficiary party
- **IRI:** <https://iri.suomi.fi/model/dsilc/beneficiaryParty>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/beneficiaryParty> — **beneficiaryParty**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Party> — **Party**
- **Name:** beneficiary party

### Border Crossing Point Code
- **IRI:** <https://iri.suomi.fi/model/dsilc/borderCrossingPointCode>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/borderCrossingPointCode> — **borderCrossingPointCode**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Border Crossing Point Code

### buyer party
- **IRI:** <https://iri.suomi.fi/model/dsilc/buyerParty>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/buyerParty> — **buyerParty**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Party> — **Party**
- **Name:** buyer party

### Calculation Percent
- **IRI:** <https://iri.suomi.fi/model/dsilc/calculationPercent>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/calculationPercent> — **calculationPercent**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#decimal>
- **Name:** Calculation Percent

### Charge Indicator
- **IRI:** <https://iri.suomi.fi/model/dsilc/chargeIndicator>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/chargeIndicator> — **chargeIndicator**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#boolean>
- **Name:** Charge Indicator

### charged by party
- **IRI:** <https://iri.suomi.fi/model/dsilc/chargedByParty>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/chargedByParty> — **chargedByParty**
- **Name:** charged by party

### charged to party
- **IRI:** <https://iri.suomi.fi/model/dsilc/chargedToParty>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/chargedToParty> — **chargedToParty**
- **Name:** charged to party

### Confirmation Added Date
- **IRI:** <https://iri.suomi.fi/model/dsilc/confirmationAddedDate>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/confirmationAddedDate> — **confirmationAddedDate**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#date>
- **Name:** Confirmation Added Date

### confirmation instruction code
- **IRI:** <https://iri.suomi.fi/model/dsilc/confirmationInstructionCode>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/confirmationInstructionCode> — **confirmationInstructionCode**
- **Class:** <http://www.w3.org/2004/02/skos/core#Concept> 
- **Name:** confirmation instruction code

### confirming party
- **IRI:** <https://iri.suomi.fi/model/dsilc/confirmingParty>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/confirmingParty> — **confirmingParty**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Party> — **Party**
- **Name:** confirming party

### Contract Number
- **IRI:** <https://iri.suomi.fi/model/dsilc/contractNumber>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/contractNumber> — **contractNumber**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **minCount:** 1
- **maxCount:** 1
- **Name:** Contract Number

### Country Code
- **IRI:** <https://iri.suomi.fi/model/dsilc/countryCode>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/countryCode> — **countryCode**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Country Code

### Country Name
- **IRI:** <https://iri.suomi.fi/model/dsilc/countryName>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/countryName> — **countryName**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Country Name

### covers additional charge
- **IRI:** <https://iri.suomi.fi/model/dsilc/coversAdditionalCharge>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/coversAdditionalCharge> — **coversAdditionalCharge**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/AllowanceCharge> — **AllowanceCharge**
- **Name:** covers additional charge

### Credit Amount Tolerance Percentage
- **IRI:** <https://iri.suomi.fi/model/dsilc/creditAmountTolerancePercentage>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/creditAmountTolerancePercentage> — **creditAmountTolerancePercentage**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#decimal>
- **Name:** Credit Amount Tolerance Percentage

### Credit Identifier
- **IRI:** <https://iri.suomi.fi/model/dsilc/creditIdentifier>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/creditIdentifier> — **creditIdentifier**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Credit Identifier

### Currency Code
- **IRI:** <https://iri.suomi.fi/model/dsilc/currencyCode>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/currencyCode> — **currencyCode**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Currency Code

### Customs Office Code
- **IRI:** <https://iri.suomi.fi/model/dsilc/customsOfficeCode>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/customsOfficeCode> — **customsOfficeCode**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Customs Office Code

### declared customs value amount
- **IRI:** <https://iri.suomi.fi/model/dsilc/declaredCustomsValueAmount>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/declaredCustomsValueAmount> — **declaredCustomsValueAmount**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/MonetaryAmount> — **MonetaryAmount**
- **Name:** declared customs value amount

### Deferred Payment Date
- **IRI:** <https://iri.suomi.fi/model/dsilc/deferredPaymentDate>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/deferredPaymentDate> — **deferredPaymentDate**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#date>
- **Name:** Deferred Payment Date

### delivery terms
- **IRI:** <https://iri.suomi.fi/model/dsilc/deliveryTerms>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/deliveryTerms> — **deliveryTerms**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/TradeDeliveryTerms> — **TradeDeliveryTerms**
- **Name:** delivery terms

### Delivery Terms Text
- **IRI:** <https://iri.suomi.fi/model/dsilc/deliveryTermsText>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/deliveryTermsText> — **deliveryTermsText**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Delivery Terms Text

### Description
- **IRI:** <https://iri.suomi.fi/model/dsilc/description>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/description> — **description**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Description

### Description of Goods Text
- **IRI:** <https://iri.suomi.fi/model/dsilc/descriptionOfGoodsText>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/descriptionOfGoodsText> — **descriptionOfGoodsText**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Description of Goods Text

### Document Date
- **IRI:** <https://iri.suomi.fi/model/dsilc/documentDate>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/documentDate> — **documentDate**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#date>
- **Name:** Document Date

### Document Identifier
- **IRI:** <https://iri.suomi.fi/model/dsilc/documentIdentifier>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/documentIdentifier> — **documentIdentifier**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Document Identifier

### document type
- **IRI:** <https://iri.suomi.fi/model/dsilc/documentType>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/documentType> — **documentType**
- **Name:** document type

### Documentary Credit Type Code
- **IRI:** <https://iri.suomi.fi/model/dsilc/documentaryCreditTypeCode>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/documentaryCreditTypeCode> — **documentaryCreditTypeCode**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Documentary Credit Type Code

### drawee party
- **IRI:** <https://iri.suomi.fi/model/dsilc/draweeParty>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/draweeParty> — **draweeParty**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Party> — **Party**
- **Name:** drawee party

### Elevation Meters
- **IRI:** <https://iri.suomi.fi/model/dsilc/elevationMeters>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/elevationMeters> — **elevationMeters**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#decimal>
- **Name:** Elevation Meters

### End Date
- **IRI:** <https://iri.suomi.fi/model/dsilc/endDate>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/endDate> — **endDate**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#date>
- **Name:** End Date

### Expiry Date
- **IRI:** <https://iri.suomi.fi/model/dsilc/expiryDate>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/expiryDate> — **expiryDate**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#date>
- **Name:** Expiry Date

### Final Destination UN Locode
- **IRI:** <https://iri.suomi.fi/model/dsilc/finalDestinationUNLocode>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/finalDestinationUNLocode> — **finalDestinationUNLocode**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Final Destination UN Locode

### Geo WKT
- **IRI:** <https://iri.suomi.fi/model/dsilc/geoWKT>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/geoWKT> — **geoWKT**
- **Datatype:** <http://www.opengis.net/ont/geosparql#wktLiteral>
- **Name:** Geo WKT

### has Address
- **IRI:** <https://iri.suomi.fi/model/dsilc/hasAddress>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasAddress> — **hasAddress**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Address> — **Address**
- **Name:** has Address

### has amount
- **IRI:** <https://iri.suomi.fi/model/dsilc/hasAmount>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasAmount> — **hasAmount**
- **Name:** has amount

### has availability method
- **IRI:** <https://iri.suomi.fi/model/dsilc/hasAvailabilityMethod>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasAvailabilityMethod> — **hasAvailabilityMethod**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/AvailabilityMethod> — **AvailabilityMethod**
- **Name:** has availability method

### has country of origin
- **IRI:** <https://iri.suomi.fi/model/dsilc/hasCountryOfOrigin>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasCountryOfOrigin> — **hasCountryOfOrigin**
- **Name:** has country of origin

### has credit availability
- **IRI:** <https://iri.suomi.fi/model/dsilc/hasCreditAvailability>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasCreditAvailability> — **hasCreditAvailability**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/CreditAvailability> — **CreditAvailability**
- **Name:** has credit availability

### has dangerous goods details
- **IRI:** <https://iri.suomi.fi/model/dsilc/hasDangerousGoodsDetails>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasDangerousGoodsDetails> — **hasDangerousGoodsDetails**
- **Name:** has dangerous goods details

### has delivery milestone
- **IRI:** <https://iri.suomi.fi/model/dsilc/hasDeliveryMilestone>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasDeliveryMilestone> — **hasDeliveryMilestone**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/DeliveryMilestone> — **DeliveryMilestone**
- **Name:** has delivery milestone

### has delivery period
- **IRI:** <https://iri.suomi.fi/model/dsilc/hasDeliveryPeriod>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasDeliveryPeriod> — **hasDeliveryPeriod**
- **Name:** has delivery period

### has goods item
- **IRI:** <https://iri.suomi.fi/model/dsilc/hasGoodsItem>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasGoodsItem> — **hasGoodsItem**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/GoodsItem> — **GoodsItem**
- **Name:** has goods item

### has identifier
- **IRI:** <https://iri.suomi.fi/model/dsilc/hasIdentifier>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasIdentifier> — **hasIdentifier**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Identifier> — **Identifier**
- **Name:** has identifier

### has message
- **IRI:** <https://iri.suomi.fi/model/dsilc/hasMessage>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasMessage> — **hasMessage**
- **Name:** has message

### has payment line
- **IRI:** <https://iri.suomi.fi/model/dsilc/hasPaymentLine>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasPaymentLine> — **hasPaymentLine**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/PaymentLine> — **PaymentLine**
- **Name:** has payment line

### has payment schedule line
- **IRI:** <https://iri.suomi.fi/model/dsilc/hasPaymentScheduleLine>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasPaymentScheduleLine> — **hasPaymentScheduleLine**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/PaymentScheduleLine> — **PaymentScheduleLine**
- **Name:** has payment schedule line

### has payment terms
- **IRI:** <https://iri.suomi.fi/model/dsilc/hasPaymentTerms>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasPaymentTerms> — **hasPaymentTerms**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/PaymentTerms> — **PaymentTerms**
- **Name:** has payment terms

### has presentation period
- **IRI:** <https://iri.suomi.fi/model/dsilc/hasPresentationPeriod>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasPresentationPeriod> — **hasPresentationPeriod**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/PeriodOfTime> — **PeriodOfTime**
- **Name:** has presentation period

### has quantity
- **IRI:** <https://iri.suomi.fi/model/dsilc/hasQuantity>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasQuantity> — **hasQuantity**
- **Name:** has quantity

### has shipment
- **IRI:** <https://iri.suomi.fi/model/dsilc/hasShipment>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasShipment> — **hasShipment**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Shipment> — **Shipment**
- **Name:** has shipment

### has shipment period
- **IRI:** <https://iri.suomi.fi/model/dsilc/hasShipmentPeriod>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hasShipmentPeriod> — **hasShipmentPeriod**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/PeriodOfTime> — **PeriodOfTime**
- **Name:** has shipment period

### Hazardous Risk Indicator
- **IRI:** <https://iri.suomi.fi/model/dsilc/hazardousRiskIndicator>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/hazardousRiskIndicator> — **hazardousRiskIndicator**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#boolean>
- **Name:** Hazardous Risk Indicator

### IATA Code
- **IRI:** <https://iri.suomi.fi/model/dsilc/iataCode>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/iataCode> — **iataCode**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** IATA Code

### ICAO Airport Code
- **IRI:** <https://iri.suomi.fi/model/dsilc/icaoAirportCode>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/icaoAirportCode> — **icaoAirportCode**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** ICAO Airport Code

### includes allowance charge
- **IRI:** <https://iri.suomi.fi/model/dsilc/includesAllowanceCharge>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/includesAllowanceCharge> — **includesAllowanceCharge**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/AllowanceCharge> — **AllowanceCharge**
- **Name:** includes allowance charge

### incoterms code
- **IRI:** <https://iri.suomi.fi/model/dsilc/incotermsCode>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/incotermsCode> — **incotermsCode**
- **Name:** incoterms code

### instructed party
- **IRI:** <https://iri.suomi.fi/model/dsilc/instructedParty>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/instructedParty> — **instructedParty**
- **Name:** instructed party

### instructing party
- **IRI:** <https://iri.suomi.fi/model/dsilc/instructingParty>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/instructingParty> — **instructingParty**
- **Name:** instructing party

### Instruction Text
- **IRI:** <https://iri.suomi.fi/model/dsilc/instructionText>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/instructionText> — **instructionText**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Instruction Text

### instruction to bank
- **IRI:** <https://iri.suomi.fi/model/dsilc/instructionToBank>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/instructionToBank> — **instructionToBank**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/BankInstruction> — **BankInstruction**
- **Name:** instruction to bank

### insurance value amount
- **IRI:** <https://iri.suomi.fi/model/dsilc/insuranceValueAmount>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/insuranceValueAmount> — **insuranceValueAmount**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/MonetaryAmount> — **MonetaryAmount**
- **Name:** insurance value amount

### invoice document
- **IRI:** <https://iri.suomi.fi/model/dsilc/invoiceDocument>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/invoiceDocument> — **invoiceDocument**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Document> — **Document**
- **Name:** invoice document

### is realized by consignment
- **IRI:** <https://iri.suomi.fi/model/dsilc/isRealizedByConsignment>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/isRealizedByConsignment> — **isRealizedByConsignment**
- **Name:** is realized by consignment

### Issue Date
- **IRI:** <https://iri.suomi.fi/model/dsilc/issueDate>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/issueDate> — **issueDate**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#date>
- **minCount:** 1
- **maxCount:** 1
- **Name:** Issue Date

### issuer party
- **IRI:** <https://iri.suomi.fi/model/dsilc/issuerParty>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/issuerParty> — **issuerParty**
- **Name:** issuer party

### issuing bank party
- **IRI:** <https://iri.suomi.fi/model/dsilc/issuingBankParty>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/issuingBankParty> — **issuingBankParty**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Party> — **Party**
- **Name:** issuing bank party

### Item Description Text
- **IRI:** <https://iri.suomi.fi/model/dsilc/itemDescriptionText>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/itemDescriptionText> — **itemDescriptionText**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Item Description Text

### Latest Presentation Date
- **IRI:** <https://iri.suomi.fi/model/dsilc/latestPresentationDate>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/latestPresentationDate> — **latestPresentationDate**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#date>
- **Name:** Latest Presentation Date

### Latest Shipment Date
- **IRI:** <https://iri.suomi.fi/model/dsilc/latestShipmentDate>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/latestShipmentDate> — **latestShipmentDate**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#date>
- **Name:** Latest Shipment Date

### Latitude
- **IRI:** <https://iri.suomi.fi/model/dsilc/latitude>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/latitude> — **latitude**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#decimal>
- **Name:** Latitude

### location country
- **IRI:** <https://iri.suomi.fi/model/dsilc/locationCountry>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/locationCountry> — **locationCountry**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Country> — **Country**
- **Name:** location country

### Location ID
- **IRI:** <https://iri.suomi.fi/model/dsilc/locationID>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/locationID> — **locationID**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Location ID

### Location Name
- **IRI:** <https://iri.suomi.fi/model/dsilc/locationName>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/locationName> — **locationName**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Location Name

### Longitude
- **IRI:** <https://iri.suomi.fi/model/dsilc/longitude>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/longitude> — **longitude**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#decimal>
- **Name:** Longitude

### Maturity Date
- **IRI:** <https://iri.suomi.fi/model/dsilc/maturityDate>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/maturityDate> — **maturityDate**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#date>
- **Name:** Maturity Date

### maximum credit amount
- **IRI:** <https://iri.suomi.fi/model/dsilc/maximumCreditAmount>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/maximumCreditAmount> — **maximumCreditAmount**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/MonetaryAmount> — **MonetaryAmount**
- **Name:** maximum credit amount

### Multiplier Factor Percent
- **IRI:** <https://iri.suomi.fi/model/dsilc/multiplierFactorPercent>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/multiplierFactorPercent> — **multiplierFactorPercent**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#decimal>
- **Name:** Multiplier Factor Percent

### Name
- **IRI:** <https://iri.suomi.fi/model/dsilc/name>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/name> — **name**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Name

### Number of Copies
- **IRI:** <https://iri.suomi.fi/model/dsilc/numberOfCopies>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/numberOfCopies> — **numberOfCopies**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#integer>
- **Name:** Number of Copies

### Number of Originals
- **IRI:** <https://iri.suomi.fi/model/dsilc/numberOfOriginals>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/numberOfOriginals> — **numberOfOriginals**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#integer>
- **Name:** Number of Originals

### obligor party
- **IRI:** <https://iri.suomi.fi/model/dsilc/obligorParty>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/obligorParty> — **obligorParty**
- **Name:** obligor party

### Partial Shipment Allowed
- **IRI:** <https://iri.suomi.fi/model/dsilc/partialShipmentAllowed>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/partialShipmentAllowed> — **partialShipmentAllowed**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#boolean>
- **Name:** Partial Shipment Allowed

### party address
- **IRI:** <https://iri.suomi.fi/model/dsilc/partyAddress>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/partyAddress> — **partyAddress**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Address> — **Address**
- **Name:** party address

### party identifier
- **IRI:** <https://iri.suomi.fi/model/dsilc/partyIdentifier>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/partyIdentifier> — **partyIdentifier**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Identifier> — **Identifier**
- **Name:** party identifier

### party legal entity
- **IRI:** <https://iri.suomi.fi/model/dsilc/partyLegalEntity>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/partyLegalEntity> — **partyLegalEntity**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/LegalEntity> — **LegalEntity**
- **Name:** party legal entity

### payee party
- **IRI:** <https://iri.suomi.fi/model/dsilc/payeeParty>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/payeeParty> — **payeeParty**
- **Name:** payee party

### Payment Due Date
- **IRI:** <https://iri.suomi.fi/model/dsilc/paymentDueDate>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/paymentDueDate> — **paymentDueDate**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#date>
- **Name:** Payment Due Date

### payment settlement method
- **IRI:** <https://iri.suomi.fi/model/dsilc/paymentSettlementMethod>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/paymentSettlementMethod> — **paymentSettlementMethod**
- **Name:** payment settlement method

### Payment Term Code
- **IRI:** <https://iri.suomi.fi/model/dsilc/paymentTermCode>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/paymentTermCode> — **paymentTermCode**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Payment Term Code

### per unit amount
- **IRI:** <https://iri.suomi.fi/model/dsilc/perUnitAmount>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/perUnitAmount> — **perUnitAmount**
- **Name:** per unit amount

### place of delivery
- **IRI:** <https://iri.suomi.fi/model/dsilc/placeOfDelivery>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfDelivery> — **placeOfDelivery**
- **Name:** place of delivery

### Place of Delivery UN Locode
- **IRI:** <https://iri.suomi.fi/model/dsilc/placeOfDeliveryUNLocode>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfDeliveryUNLocode> — **placeOfDeliveryUNLocode**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Place of Delivery UN Locode

### place of discharge
- **IRI:** <https://iri.suomi.fi/model/dsilc/placeOfDischarge>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfDischarge> — **placeOfDischarge**
- **Name:** place of discharge

### place of expiry
- **IRI:** <https://iri.suomi.fi/model/dsilc/placeOfExpiry>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfExpiry> — **placeOfExpiry**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Location> — **Location**
- **Name:** place of expiry

### place of loading
- **IRI:** <https://iri.suomi.fi/model/dsilc/placeOfLoading>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfLoading> — **placeOfLoading**
- **Name:** place of loading

### place of presentation
- **IRI:** <https://iri.suomi.fi/model/dsilc/placeOfPresentation>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfPresentation> — **placeOfPresentation**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Location> — **Location**
- **Name:** place of presentation

### Place of Receipt UN Locode
- **IRI:** <https://iri.suomi.fi/model/dsilc/placeOfReceiptUNLocode>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfReceiptUNLocode> — **placeOfReceiptUNLocode**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Place of Receipt UN Locode

### Port Facility Code
- **IRI:** <https://iri.suomi.fi/model/dsilc/portFacilityCode>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/portFacilityCode> — **portFacilityCode**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Port Facility Code

### Port Of Discharge UN Locode
- **IRI:** <https://iri.suomi.fi/model/dsilc/portOfDischargeUNLocode>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/portOfDischargeUNLocode> — **portOfDischargeUNLocode**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Port Of Discharge UN Locode

### Port of Loading UN Locode
- **IRI:** <https://iri.suomi.fi/model/dsilc/portOfLoadingUNLocode>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/portOfLoadingUNLocode> — **portOfLoadingUNLocode**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Port of Loading UN Locode

### Post Code
- **IRI:** <https://iri.suomi.fi/model/dsilc/postCode>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/postCode> — **postCode**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Post Code

### presentation base event
- **IRI:** <https://iri.suomi.fi/model/dsilc/presentationBaseEvent>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/presentationBaseEvent> — **presentationBaseEvent**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/ShipmentBasis> — **ShipmentBasis**
- **Name:** presentation base event

### Presentation Period Days
- **IRI:** <https://iri.suomi.fi/model/dsilc/presentationPeriodDays>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/presentationPeriodDays> — **presentationPeriodDays**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#integer>
- **Name:** Presentation Period Days

### Product Identifier
- **IRI:** <https://iri.suomi.fi/model/dsilc/productIdentifier>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/productIdentifier> — **productIdentifier**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Product Identifier

### Publication Date
- **IRI:** <https://iri.suomi.fi/model/dsilc/publicationDate>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/publicationDate> — **publicationDate**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#date>
- **Name:** Publication Date

### publisher
- **IRI:** <https://iri.suomi.fi/model/dsilc/publisher>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/publisher> — **publisher**
- **Name:** publisher

### references pre advice
- **IRI:** <https://iri.suomi.fi/model/dsilc/referencesPreAdvice>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/referencesPreAdvice> — **referencesPreAdvice**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Document> — **Document**
- **Name:** references pre advice

### reimbursing bank party
- **IRI:** <https://iri.suomi.fi/model/dsilc/reimbursingBankParty>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/reimbursingBankParty> — **reimbursingBankParty**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Party> — **Party**
- **Name:** reimbursing bank party

### related order
- **IRI:** <https://iri.suomi.fi/model/dsilc/relatedOrder>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/relatedOrder> — **relatedOrder**
- **Name:** related order

### relates to consignment
- **IRI:** <https://iri.suomi.fi/model/dsilc/relatesToConsignment>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/relatesToConsignment> — **relatesToConsignment**
- **Name:** relates to consignment

### requested confirmation party
- **IRI:** <https://iri.suomi.fi/model/dsilc/requestedConfirmationParty>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/requestedConfirmationParty> — **requestedConfirmationParty**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/Party> — **Party**
- **Name:** requested confirmation party

### requested delivery period
- **IRI:** <https://iri.suomi.fi/model/dsilc/requestedDeliveryPeriod>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/requestedDeliveryPeriod> — **requestedDeliveryPeriod**
- **Name:** requested delivery period

### required document type
- **IRI:** <https://iri.suomi.fi/model/dsilc/requiredDocumentType>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/requiredDocumentType> — **requiredDocumentType**
- **Name:** required document type

### requires document
- **IRI:** <https://iri.suomi.fi/model/dsilc/requiresDocument>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/requiresDocument> — **requiresDocument**
- **Class:** <https://iri.suomi.fi/model/ktddecv/0.0.4/DocumentRequirement> — **DocumentRequirement**
- **Name:** requires document

### Rule Set Identifier
- **IRI:** <https://iri.suomi.fi/model/dsilc/ruleSetIdentifier>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/ruleSetIdentifier> — **ruleSetIdentifier**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Rule Set Identifier

### seller party
- **IRI:** <https://iri.suomi.fi/model/dsilc/sellerParty>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/sellerParty> — **sellerParty**
- **Name:** seller party

### Shipment Identifier
- **IRI:** <https://iri.suomi.fi/model/dsilc/shipmentIdentifier>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/shipmentIdentifier> — **shipmentIdentifier**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Shipment Identifier

### Start Date
- **IRI:** <https://iri.suomi.fi/model/dsilc/startDate>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/startDate> — **startDate**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#date>
- **Name:** Start Date

### Tenor
- **IRI:** <https://iri.suomi.fi/model/dsilc/tenor>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/tenor> — **tenor**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Tenor

### tenor period
- **IRI:** <https://iri.suomi.fi/model/dsilc/tenorPeriod>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/tenorPeriod> — **tenorPeriod**
- **Name:** tenor period

### Terminal Code
- **IRI:** <https://iri.suomi.fi/model/dsilc/terminalCode>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/terminalCode> — **terminalCode**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Terminal Code

### Time Zone
- **IRI:** <https://iri.suomi.fi/model/dsilc/timeZone>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/timeZone> — **timeZone**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Time Zone

### Title
- **IRI:** <https://iri.suomi.fi/model/dsilc/title>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/title> — **title**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Title

### total goods item quantity
- **IRI:** <https://iri.suomi.fi/model/dsilc/totalGoodsItemQuantity>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/totalGoodsItemQuantity> — **totalGoodsItemQuantity**
- **Name:** total goods item quantity

### total package quantity
- **IRI:** <https://iri.suomi.fi/model/dsilc/totalPackageQuantity>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/totalPackageQuantity> — **totalPackageQuantity**
- **Name:** total package quantity

### total transport handling unit quantity
- **IRI:** <https://iri.suomi.fi/model/dsilc/totalTransportHandlingUnitQuantity>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/totalTransportHandlingUnitQuantity> — **totalTransportHandlingUnitQuantity**
- **Name:** total transport handling unit quantity

### Transshipment Allowed
- **IRI:** <https://iri.suomi.fi/model/dsilc/transshipmentAllowed>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/transshipmentAllowed> — **transshipmentAllowed**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#boolean>
- **Name:** Transshipment Allowed

### UIC Station Code
- **IRI:** <https://iri.suomi.fi/model/dsilc/uicStationCode>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/uicStationCode> — **uicStationCode**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** UIC Station Code

### UN Locode
- **IRI:** <https://iri.suomi.fi/model/dsilc/unlocode>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/unlocode> — **unlocode**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** UN Locode

### Version Identifier
- **IRI:** <https://iri.suomi.fi/model/dsilc/versionIdentifier>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/versionIdentifier> — **versionIdentifier**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Version Identifier

### Warehouse GLN
- **IRI:** <https://iri.suomi.fi/model/dsilc/warehouseGLN>
- **Path:** <https://iri.suomi.fi/model/ktddecv/0.0.4/warehouseGLN> — **warehouseGLN**
- **Datatype:** <http://www.w3.org/2001/XMLSchema#string>
- **Name:** Warehouse GLN

<a id="unreferenced-property-shapes"></a>
## Unreferenced Property Shapes

_All property shapes are referenced from a node shape._

<a id="crosswalk-shapes--ktdde"></a>
## Crosswalk: Shapes → KTDDE

| Shape | Predicate | KTDDE IRI | KTDDE label |
|---|---|---|---|
| <https://iri.suomi.fi/model/dsilc/AdditionalAmountCategory> | sh:targetClass | <https://iri.suomi.fi/model/ktddecv/0.0.4/AdditionalAmountCategory> | AdditionalAmountCategory |
| <https://iri.suomi.fi/model/dsilc/Address> | sh:targetClass | <https://iri.suomi.fi/model/ktddecv/0.0.4/Address> | Address |
| <https://iri.suomi.fi/model/dsilc/AllowanceCharge> | sh:targetClass | <https://iri.suomi.fi/model/ktddecv/0.0.4/AllowanceCharge> | AllowanceCharge |
| <https://iri.suomi.fi/model/dsilc/allowanceChargeReasonCode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/allowanceChargeReasonCode> | allowanceChargeReasonCode |
| <https://iri.suomi.fi/model/dsilc/baseAmount> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/baseAmount> | baseAmount |
| <https://iri.suomi.fi/model/dsilc/calculationPercent> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/calculationPercent> | calculationPercent |
| <https://iri.suomi.fi/model/dsilc/chargeIndicator> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/chargeIndicator> | chargeIndicator |
| <https://iri.suomi.fi/model/dsilc/chargedByParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/chargedByParty> | chargedByParty |
| <https://iri.suomi.fi/model/dsilc/chargedToParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/chargedToParty> | chargedToParty |
| <https://iri.suomi.fi/model/dsilc/hasAmount> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasAmount> | hasAmount |
| <https://iri.suomi.fi/model/dsilc/multiplierFactorPercent> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/multiplierFactorPercent> | multiplierFactorPercent |
| <https://iri.suomi.fi/model/dsilc/perUnitAmount> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/perUnitAmount> | perUnitAmount |
| <https://iri.suomi.fi/model/dsilc/AvailabilityMethod> | sh:targetClass | <https://iri.suomi.fi/model/ktddecv/0.0.4/AvailabilityMethod> | AvailabilityMethod |
| <https://iri.suomi.fi/model/dsilc/BankInstruction> | sh:targetClass | <https://iri.suomi.fi/model/ktddecv/0.0.4/BankInstruction> | BankInstruction |
| <https://iri.suomi.fi/model/dsilc/BusinessDocument> | sh:targetClass | <https://iri.suomi.fi/model/ktddecv/0.0.4/BusinessDocument> | BusinessDocument |
| <https://iri.suomi.fi/model/dsilc/documentType> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/documentType> | documentType |
| <https://iri.suomi.fi/model/dsilc/hasMessage> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasMessage> | hasMessage |
| <https://iri.suomi.fi/model/dsilc/Country> | sh:targetClass | <https://iri.suomi.fi/model/ktddecv/0.0.4/Country> | Country |
| <https://iri.suomi.fi/model/dsilc/countryCode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/countryCode> | countryCode |
| <https://iri.suomi.fi/model/dsilc/countryName> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/countryName> | countryName |
| <https://iri.suomi.fi/model/dsilc/CreditAvailability> | sh:targetClass | <https://iri.suomi.fi/model/ktddecv/0.0.4/CreditAvailability> | CreditAvailability |
| <https://iri.suomi.fi/model/dsilc/availableAtPlace> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/availableAtPlace> | availableAtPlace |
| <https://iri.suomi.fi/model/dsilc/availableWithParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/availableWithParty> | availableWithParty |
| <https://iri.suomi.fi/model/dsilc/availableWithQualifier> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/availableWithQualifier> | availableWithQualifier |
| <https://iri.suomi.fi/model/dsilc/draweeParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/draweeParty> | draweeParty |
| <https://iri.suomi.fi/model/dsilc/hasAmount> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasAmount> | hasAmount |
| <https://iri.suomi.fi/model/dsilc/hasAvailabilityMethod> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasAvailabilityMethod> | hasAvailabilityMethod |
| <https://iri.suomi.fi/model/dsilc/maturityDate> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/maturityDate> | maturityDate |
| <https://iri.suomi.fi/model/dsilc/obligorParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/obligorParty> | obligorParty |
| <https://iri.suomi.fi/model/dsilc/payeeParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/payeeParty> | payeeParty |
| <https://iri.suomi.fi/model/dsilc/tenor> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/tenor> | tenor |
| <https://iri.suomi.fi/model/dsilc/DeliveryMilestone> | sh:targetClass | <https://iri.suomi.fi/model/ktddecv/0.0.4/DeliveryMilestone> | DeliveryMilestone |
| <https://iri.suomi.fi/model/dsilc/hasShipmentPeriod> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasShipmentPeriod> | hasShipmentPeriod |
| <https://iri.suomi.fi/model/dsilc/Document> | sh:targetClass | <https://iri.suomi.fi/model/ktddecv/0.0.4/Document> | Document |
| <https://iri.suomi.fi/model/dsilc/documentDate> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/documentDate> | documentDate |
| <https://iri.suomi.fi/model/dsilc/documentIdentifier> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/documentIdentifier> | documentIdentifier |
| <https://iri.suomi.fi/model/dsilc/DocumentRequirement> | sh:targetClass | <https://iri.suomi.fi/model/ktddecv/0.0.4/DocumentRequirement> | DocumentRequirement |
| <https://iri.suomi.fi/model/dsilc/issuerParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/issuerParty> | issuerParty |
| <https://iri.suomi.fi/model/dsilc/numberOfCopies> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/numberOfCopies> | numberOfCopies |
| <https://iri.suomi.fi/model/dsilc/numberOfOriginals> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/numberOfOriginals> | numberOfOriginals |
| <https://iri.suomi.fi/model/dsilc/requiredDocumentType> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/requiredDocumentType> | requiredDocumentType |
| <https://iri.suomi.fi/model/dsilc/DocumentaryCredit> | sh:targetClass | <https://iri.suomi.fi/model/ktddecv/0.0.4/DocumentaryCredit> | DocumentaryCredit |
| <https://iri.suomi.fi/model/dsilc/additionalAmountsCovered> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/additionalAmountsCovered> | additionalAmountsCovered |
| <https://iri.suomi.fi/model/dsilc/AdditionalConditionsText> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/additionalConditionsText> | additionalConditionsText |
| <https://iri.suomi.fi/model/dsilc/adviseThroughBankParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/adviseThroughBankParty> | adviseThroughBankParty |
| <https://iri.suomi.fi/model/dsilc/advisingBankParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/advisingBankParty> | advisingBankParty |
| <https://iri.suomi.fi/model/dsilc/applicableRules> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/applicableRules> | applicableRules |
| <https://iri.suomi.fi/model/dsilc/applicantBankParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/applicantBankParty> | applicantBankParty |
| <https://iri.suomi.fi/model/dsilc/applicantParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/applicantParty> | applicantParty |
| <https://iri.suomi.fi/model/dsilc/beneficiaryParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/beneficiaryParty> | beneficiaryParty |
| <https://iri.suomi.fi/model/dsilc/confirmationAddedDate> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/confirmationAddedDate> | confirmationAddedDate |
| <https://iri.suomi.fi/model/dsilc/confirmationInstructionCode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/confirmationInstructionCode> | confirmationInstructionCode |
| <https://iri.suomi.fi/model/dsilc/confirmingParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/confirmingParty> | confirmingParty |
| <https://iri.suomi.fi/model/dsilc/coversAdditionalCharge> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/coversAdditionalCharge> | coversAdditionalCharge |
| <https://iri.suomi.fi/model/dsilc/creditAmountTolerancePercentage> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/creditAmountTolerancePercentage> | creditAmountTolerancePercentage |
| <https://iri.suomi.fi/model/dsilc/creditIdentifier> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/creditIdentifier> | creditIdentifier |
| <https://iri.suomi.fi/model/dsilc/documentaryCreditTypeCode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/documentaryCreditTypeCode> | documentaryCreditTypeCode |
| <https://iri.suomi.fi/model/dsilc/draweeParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/draweeParty> | draweeParty |
| <https://iri.suomi.fi/model/dsilc/expiryDate> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/expiryDate> | expiryDate |
| <https://iri.suomi.fi/model/dsilc/hasAvailabilityMethod> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasAvailabilityMethod> | hasAvailabilityMethod |
| <https://iri.suomi.fi/model/dsilc/hasCreditAvailability> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasCreditAvailability> | hasCreditAvailability |
| <https://iri.suomi.fi/model/dsilc/hasDeliveryMilestone> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasDeliveryMilestone> | hasDeliveryMilestone |
| <https://iri.suomi.fi/model/dsilc/hasPaymentLine> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasPaymentLine> | hasPaymentLine |
| <https://iri.suomi.fi/model/dsilc/hasPaymentTerms> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasPaymentTerms> | hasPaymentTerms |
| <https://iri.suomi.fi/model/dsilc/hasPresentationPeriod> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasPresentationPeriod> | hasPresentationPeriod |
| <https://iri.suomi.fi/model/dsilc/hasShipment> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasShipment> | hasShipment |
| <https://iri.suomi.fi/model/dsilc/hasShipmentPeriod> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasShipmentPeriod> | hasShipmentPeriod |
| <https://iri.suomi.fi/model/dsilc/includesAllowanceCharge> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/includesAllowanceCharge> | includesAllowanceCharge |
| <https://iri.suomi.fi/model/dsilc/instructionToBank> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/instructionToBank> | instructionToBank |
| <https://iri.suomi.fi/model/dsilc/issueDate> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/issueDate> | issueDate |
| <https://iri.suomi.fi/model/dsilc/issuingBankParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/issuingBankParty> | issuingBankParty |
| <https://iri.suomi.fi/model/dsilc/latestPresentationDate> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/latestPresentationDate> | latestPresentationDate |
| <https://iri.suomi.fi/model/dsilc/latestShipmentDate> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/latestShipmentDate> | latestShipmentDate |
| <https://iri.suomi.fi/model/dsilc/maximumCreditAmount> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/maximumCreditAmount> | maximumCreditAmount |
| <https://iri.suomi.fi/model/dsilc/partialShipmentAllowed> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/partialShipmentAllowed> | partialShipmentAllowed |
| <https://iri.suomi.fi/model/dsilc/placeOfExpiry> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfExpiry> | placeOfExpiry |
| <https://iri.suomi.fi/model/dsilc/placeOfPresentation> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfPresentation> | placeOfPresentation |
| <https://iri.suomi.fi/model/dsilc/presentationBaseEvent> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/presentationBaseEvent> | presentationBaseEvent |
| <https://iri.suomi.fi/model/dsilc/presentationPeriodDays> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/presentationPeriodDays> | presentationPeriodDays |
| <https://iri.suomi.fi/model/dsilc/referencesPreAdvice> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/referencesPreAdvice> | referencesPreAdvice |
| <https://iri.suomi.fi/model/dsilc/reimbursingBankParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/reimbursingBankParty> | reimbursingBankParty |
| <https://iri.suomi.fi/model/dsilc/requestedConfirmationParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/requestedConfirmationParty> | requestedConfirmationParty |
| <https://iri.suomi.fi/model/dsilc/requiresDocument> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/requiresDocument> | requiresDocument |
| <https://iri.suomi.fi/model/dsilc/transshipmentAllowed> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/transshipmentAllowed> | transshipmentAllowed |
| <https://iri.suomi.fi/model/dsilc/DutyTaxFee> | sh:targetClass | <https://iri.suomi.fi/model/ktddecv/0.0.4/DutyTaxFee> | DutyTaxFee |
| <https://iri.suomi.fi/model/dsilc/GoodsItem> | sh:targetClass | <https://iri.suomi.fi/model/ktddecv/0.0.4/GoodsItem> | GoodsItem |
| <https://iri.suomi.fi/model/dsilc/appliedCommodityClassification> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/appliedCommodityClassification> | appliedCommodityClassification |
| <https://iri.suomi.fi/model/dsilc/descriptionOfGoodsText> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/descriptionOfGoodsText> | descriptionOfGoodsText |
| <https://iri.suomi.fi/model/dsilc/hasCountryOfOrigin> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasCountryOfOrigin> | hasCountryOfOrigin |
| <https://iri.suomi.fi/model/dsilc/hasDangerousGoodsDetails> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasDangerousGoodsDetails> | hasDangerousGoodsDetails |
| <https://iri.suomi.fi/model/dsilc/hasQuantity> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasQuantity> | hasQuantity |
| <https://iri.suomi.fi/model/dsilc/itemDescriptionText> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/itemDescriptionText> | itemDescriptionText |
| <https://iri.suomi.fi/model/dsilc/productIdentifier> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/productIdentifier> | productIdentifier |
| <https://iri.suomi.fi/model/dsilc/Identifier> | sh:targetClass | <https://iri.suomi.fi/model/ktddecv/0.0.4/Identifier> | Identifier |
| <https://iri.suomi.fi/model/dsilc/Instruction> | sh:targetClass | <https://iri.suomi.fi/model/ktddecv/0.0.4/Instruction> | Instruction |
| <https://iri.suomi.fi/model/dsilc/instructedParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/instructedParty> | instructedParty |
| <https://iri.suomi.fi/model/dsilc/instructingParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/instructingParty> | instructingParty |
| <https://iri.suomi.fi/model/dsilc/instructionText> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/instructionText> | instructionText |
| <https://iri.suomi.fi/model/dsilc/LegalEntity> | sh:targetClass | <https://iri.suomi.fi/model/ktddecv/0.0.4/LegalEntity> | LegalEntity |
| <https://iri.suomi.fi/model/dsilc/Location> | sh:targetClass | <https://iri.suomi.fi/model/ktddecv/0.0.4/Location> | Location |
| <https://iri.suomi.fi/model/dsilc/alternateName> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/alternateName> | alternateName |
| <https://iri.suomi.fi/model/dsilc/borderCrossingPointCode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/borderCrossingPointCode> | borderCrossingPointCode |
| <https://iri.suomi.fi/model/dsilc/customsOfficeCode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/customsOfficeCode> | customsOfficeCode |
| <https://iri.suomi.fi/model/dsilc/description> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/description> | description |
| <https://iri.suomi.fi/model/dsilc/elevationMeters> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/elevationMeters> | elevationMeters |
| <https://iri.suomi.fi/model/dsilc/geoWKT> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/geoWKT> | geoWKT |
| <https://iri.suomi.fi/model/dsilc/hasAddress> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasAddress> | hasAddress |
| <https://iri.suomi.fi/model/dsilc/hasIdentifier> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasIdentifier> | hasIdentifier |
| <https://iri.suomi.fi/model/dsilc/iataCode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/iataCode> | iataCode |
| <https://iri.suomi.fi/model/dsilc/icaoAirportCode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/icaoAirportCode> | icaoAirportCode |
| <https://iri.suomi.fi/model/dsilc/latitude> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/latitude> | latitude |
| <https://iri.suomi.fi/model/dsilc/locationCountry> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/locationCountry> | locationCountry |
| <https://iri.suomi.fi/model/dsilc/locationID> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/locationID> | locationID |
| <https://iri.suomi.fi/model/dsilc/locationName> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/locationName> | locationName |
| <https://iri.suomi.fi/model/dsilc/longitude> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/longitude> | longitude |
| <https://iri.suomi.fi/model/dsilc/portFacilityCode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/portFacilityCode> | portFacilityCode |
| <https://iri.suomi.fi/model/dsilc/postCode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/postCode> | postCode |
| <https://iri.suomi.fi/model/dsilc/terminalCode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/terminalCode> | terminalCode |
| <https://iri.suomi.fi/model/dsilc/timeZone> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/timeZone> | timeZone |
| <https://iri.suomi.fi/model/dsilc/uicStationCode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/uicStationCode> | uicStationCode |
| <https://iri.suomi.fi/model/dsilc/unlocode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/unlocode> | unlocode |
| <https://iri.suomi.fi/model/dsilc/warehouseGLN> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/warehouseGLN> | warehouseGLN |
| <https://iri.suomi.fi/model/dsilc/MonetaryAmount> | sh:targetClass | <https://iri.suomi.fi/model/ktddecv/0.0.4/MonetaryAmount> | MonetaryAmount |
| <https://iri.suomi.fi/model/dsilc/amountValue> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/amountValue> | amountValue |
| <https://iri.suomi.fi/model/dsilc/currencyCode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/currencyCode> | currencyCode |
| <https://iri.suomi.fi/model/dsilc/Party> | sh:targetClass | <https://iri.suomi.fi/model/ktddecv/0.0.4/Party> | Party |
| <https://iri.suomi.fi/model/dsilc/name> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/name> | name |
| <https://iri.suomi.fi/model/dsilc/partyAddress> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/partyAddress> | partyAddress |
| <https://iri.suomi.fi/model/dsilc/partyIdentifier> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/partyIdentifier> | partyIdentifier |
| <https://iri.suomi.fi/model/dsilc/partyLegalEntity> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/partyLegalEntity> | partyLegalEntity |
| <https://iri.suomi.fi/model/dsilc/PaymentLine> | sh:targetClass | <https://iri.suomi.fi/model/ktddecv/0.0.4/PaymentLine> | PaymentLine |
| <https://iri.suomi.fi/model/dsilc/hasAmount> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasAmount> | hasAmount |
| <https://iri.suomi.fi/model/dsilc/payeeParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/payeeParty> | payeeParty |
| <https://iri.suomi.fi/model/dsilc/paymentDueDate> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/paymentDueDate> | paymentDueDate |
| <https://iri.suomi.fi/model/dsilc/paymentSettlementMethod> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/paymentSettlementMethod> | paymentSettlementMethod |
| <https://iri.suomi.fi/model/dsilc/tenor> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/tenor> | tenor |
| <https://iri.suomi.fi/model/dsilc/PaymentScheduleLine> | sh:targetClass | <https://iri.suomi.fi/model/ktddecv/0.0.4/PaymentScheduleLine> | PaymentScheduleLine |
| <https://iri.suomi.fi/model/dsilc/amountPercentOfBase> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/amountPercentOfBase> | amountPercentOfBase |
| <https://iri.suomi.fi/model/dsilc/baseAmount> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/baseAmount> | baseAmount |
| <https://iri.suomi.fi/model/dsilc/deferredPaymentDate> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/deferredPaymentDate> | deferredPaymentDate |
| <https://iri.suomi.fi/model/dsilc/hasAmount> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasAmount> | hasAmount |
| <https://iri.suomi.fi/model/dsilc/paymentDueDate> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/paymentDueDate> | paymentDueDate |
| <https://iri.suomi.fi/model/dsilc/PaymentTerms> | sh:targetClass | <https://iri.suomi.fi/model/ktddecv/0.0.4/PaymentTerms> | PaymentTerms |
| <https://iri.suomi.fi/model/dsilc/hasPaymentScheduleLine> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasPaymentScheduleLine> | hasPaymentScheduleLine |
| <https://iri.suomi.fi/model/dsilc/paymentTermCode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/paymentTermCode> | paymentTermCode |
| <https://iri.suomi.fi/model/dsilc/tenor> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/tenor> | tenor |
| <https://iri.suomi.fi/model/dsilc/tenorPeriod> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/tenorPeriod> | tenorPeriod |
| <https://iri.suomi.fi/model/dsilc/PeriodOfTime> | sh:targetClass | <https://iri.suomi.fi/model/ktddecv/0.0.4/PeriodOfTime> | PeriodOfTime |
| <https://iri.suomi.fi/model/dsilc/endDate> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/endDate> | endDate |
| <https://iri.suomi.fi/model/dsilc/startDate> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/startDate> | startDate |
| <https://iri.suomi.fi/model/dsilc/Presentation> | sh:targetClass | <https://iri.suomi.fi/model/ktddecv/0.0.4/Presentation> | Presentation |
| <https://iri.suomi.fi/model/dsilc/RuleSet> | sh:targetClass | <https://iri.suomi.fi/model/ktddecv/0.0.4/RuleSet> | RuleSet |
| <https://iri.suomi.fi/model/dsilc/publicationDate> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/publicationDate> | publicationDate |
| <https://iri.suomi.fi/model/dsilc/publisher> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/publisher> | publisher |
| <https://iri.suomi.fi/model/dsilc/ruleSetIdentifier> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/ruleSetIdentifier> | ruleSetIdentifier |
| <https://iri.suomi.fi/model/dsilc/title> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/title> | title |
| <https://iri.suomi.fi/model/dsilc/versionIdentifier> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/versionIdentifier> | versionIdentifier |
| <https://iri.suomi.fi/model/dsilc/Shipment> | sh:targetClass | <https://iri.suomi.fi/model/ktddecv/0.0.4/Shipment> | Shipment |
| <https://iri.suomi.fi/model/dsilc/buyerParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/buyerParty> | buyerParty |
| <https://iri.suomi.fi/model/dsilc/contractNumber> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/contractNumber> | contractNumber |
| <https://iri.suomi.fi/model/dsilc/declaredCustomsValueAmount> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/declaredCustomsValueAmount> | declaredCustomsValueAmount |
| <https://iri.suomi.fi/model/dsilc/deliveryTerms> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/deliveryTerms> | deliveryTerms |
| <https://iri.suomi.fi/model/dsilc/finalDestinationUNLocode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/finalDestinationUNLocode> | finalDestinationUNLocode |
| <https://iri.suomi.fi/model/dsilc/hasGoodsItem> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasGoodsItem> | hasGoodsItem |
| <https://iri.suomi.fi/model/dsilc/hasShipmentPeriod> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasShipmentPeriod> | hasShipmentPeriod |
| <https://iri.suomi.fi/model/dsilc/hazardousRiskIndicator> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hazardousRiskIndicator> | hazardousRiskIndicator |
| <https://iri.suomi.fi/model/dsilc/insuranceValueAmount> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/insuranceValueAmount> | insuranceValueAmount |
| <https://iri.suomi.fi/model/dsilc/invoiceDocument> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/invoiceDocument> | invoiceDocument |
| <https://iri.suomi.fi/model/dsilc/isRealizedByConsignment> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/isRealizedByConsignment> | isRealizedByConsignment |
| <https://iri.suomi.fi/model/dsilc/placeOfDeliveryUNLocode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfDeliveryUNLocode> | placeOfDeliveryUNLocode |
| <https://iri.suomi.fi/model/dsilc/placeOfReceiptUNLocode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfReceiptUNLocode> | placeOfReceiptUNLocode |
| <https://iri.suomi.fi/model/dsilc/portOfDischargeUNLocode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/portOfDischargeUNLocode> | portOfDischargeUNLocode |
| <https://iri.suomi.fi/model/dsilc/portOfLoadingUNLocode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/portOfLoadingUNLocode> | portOfLoadingUNLocode |
| <https://iri.suomi.fi/model/dsilc/relatedOrder> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/relatedOrder> | relatedOrder |
| <https://iri.suomi.fi/model/dsilc/requestedDeliveryPeriod> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/requestedDeliveryPeriod> | requestedDeliveryPeriod |
| <https://iri.suomi.fi/model/dsilc/sellerParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/sellerParty> | sellerParty |
| <https://iri.suomi.fi/model/dsilc/shipmentIdentifier> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/shipmentIdentifier> | shipmentIdentifier |
| <https://iri.suomi.fi/model/dsilc/totalGoodsItemQuantity> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/totalGoodsItemQuantity> | totalGoodsItemQuantity |
| <https://iri.suomi.fi/model/dsilc/totalPackageQuantity> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/totalPackageQuantity> | totalPackageQuantity |
| <https://iri.suomi.fi/model/dsilc/totalTransportHandlingUnitQuantity> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/totalTransportHandlingUnitQuantity> | totalTransportHandlingUnitQuantity |
| <https://iri.suomi.fi/model/dsilc/ShipmentBasis> | sh:targetClass | <https://iri.suomi.fi/model/ktddecv/0.0.4/ShipmentBasis> | ShipmentBasis |
| <https://iri.suomi.fi/model/dsilc/TradeDeliveryTerms> | sh:targetClass | <https://iri.suomi.fi/model/ktddecv/0.0.4/TradeDeliveryTerms> | TradeDeliveryTerms |
| <https://iri.suomi.fi/model/dsilc/applicableRules> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/applicableRules> | applicableRules |
| <https://iri.suomi.fi/model/dsilc/deliveryTermsText> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/deliveryTermsText> | deliveryTermsText |
| <https://iri.suomi.fi/model/dsilc/hasDeliveryPeriod> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasDeliveryPeriod> | hasDeliveryPeriod |
| <https://iri.suomi.fi/model/dsilc/includesAllowanceCharge> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/includesAllowanceCharge> | includesAllowanceCharge |
| <https://iri.suomi.fi/model/dsilc/incotermsCode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/incotermsCode> | incotermsCode |
| <https://iri.suomi.fi/model/dsilc/placeOfDelivery> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfDelivery> | placeOfDelivery |
| <https://iri.suomi.fi/model/dsilc/placeOfDischarge> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfDischarge> | placeOfDischarge |
| <https://iri.suomi.fi/model/dsilc/placeOfLoading> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfLoading> | placeOfLoading |
| <https://iri.suomi.fi/model/dsilc/relatesToConsignment> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/relatesToConsignment> | relatesToConsignment |
| <https://iri.suomi.fi/model/dsilc/additionalAmountsCovered> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/additionalAmountsCovered> | additionalAmountsCovered |
| <https://iri.suomi.fi/model/dsilc/AdditionalConditionsText> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/additionalConditionsText> | additionalConditionsText |
| <https://iri.suomi.fi/model/dsilc/adviseThroughBankParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/adviseThroughBankParty> | adviseThroughBankParty |
| <https://iri.suomi.fi/model/dsilc/advisingBankParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/advisingBankParty> | advisingBankParty |
| <https://iri.suomi.fi/model/dsilc/allowanceChargeReasonCode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/allowanceChargeReasonCode> | allowanceChargeReasonCode |
| <https://iri.suomi.fi/model/dsilc/alternateName> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/alternateName> | alternateName |
| <https://iri.suomi.fi/model/dsilc/amountPercentOfBase> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/amountPercentOfBase> | amountPercentOfBase |
| <https://iri.suomi.fi/model/dsilc/amountValue> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/amountValue> | amountValue |
| <https://iri.suomi.fi/model/dsilc/applicableRules> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/applicableRules> | applicableRules |
| <https://iri.suomi.fi/model/dsilc/applicantBankParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/applicantBankParty> | applicantBankParty |
| <https://iri.suomi.fi/model/dsilc/applicantParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/applicantParty> | applicantParty |
| <https://iri.suomi.fi/model/dsilc/appliedCommodityClassification> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/appliedCommodityClassification> | appliedCommodityClassification |
| <https://iri.suomi.fi/model/dsilc/availableAtPlace> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/availableAtPlace> | availableAtPlace |
| <https://iri.suomi.fi/model/dsilc/availableWithParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/availableWithParty> | availableWithParty |
| <https://iri.suomi.fi/model/dsilc/availableWithQualifier> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/availableWithQualifier> | availableWithQualifier |
| <https://iri.suomi.fi/model/dsilc/baseAmount> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/baseAmount> | baseAmount |
| <https://iri.suomi.fi/model/dsilc/beneficiaryParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/beneficiaryParty> | beneficiaryParty |
| <https://iri.suomi.fi/model/dsilc/borderCrossingPointCode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/borderCrossingPointCode> | borderCrossingPointCode |
| <https://iri.suomi.fi/model/dsilc/buyerParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/buyerParty> | buyerParty |
| <https://iri.suomi.fi/model/dsilc/calculationPercent> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/calculationPercent> | calculationPercent |
| <https://iri.suomi.fi/model/dsilc/chargeIndicator> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/chargeIndicator> | chargeIndicator |
| <https://iri.suomi.fi/model/dsilc/chargedByParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/chargedByParty> | chargedByParty |
| <https://iri.suomi.fi/model/dsilc/chargedToParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/chargedToParty> | chargedToParty |
| <https://iri.suomi.fi/model/dsilc/confirmationAddedDate> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/confirmationAddedDate> | confirmationAddedDate |
| <https://iri.suomi.fi/model/dsilc/confirmationInstructionCode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/confirmationInstructionCode> | confirmationInstructionCode |
| <https://iri.suomi.fi/model/dsilc/confirmingParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/confirmingParty> | confirmingParty |
| <https://iri.suomi.fi/model/dsilc/contractNumber> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/contractNumber> | contractNumber |
| <https://iri.suomi.fi/model/dsilc/countryCode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/countryCode> | countryCode |
| <https://iri.suomi.fi/model/dsilc/countryName> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/countryName> | countryName |
| <https://iri.suomi.fi/model/dsilc/coversAdditionalCharge> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/coversAdditionalCharge> | coversAdditionalCharge |
| <https://iri.suomi.fi/model/dsilc/creditAmountTolerancePercentage> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/creditAmountTolerancePercentage> | creditAmountTolerancePercentage |
| <https://iri.suomi.fi/model/dsilc/creditIdentifier> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/creditIdentifier> | creditIdentifier |
| <https://iri.suomi.fi/model/dsilc/currencyCode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/currencyCode> | currencyCode |
| <https://iri.suomi.fi/model/dsilc/customsOfficeCode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/customsOfficeCode> | customsOfficeCode |
| <https://iri.suomi.fi/model/dsilc/declaredCustomsValueAmount> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/declaredCustomsValueAmount> | declaredCustomsValueAmount |
| <https://iri.suomi.fi/model/dsilc/deferredPaymentDate> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/deferredPaymentDate> | deferredPaymentDate |
| <https://iri.suomi.fi/model/dsilc/deliveryTerms> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/deliveryTerms> | deliveryTerms |
| <https://iri.suomi.fi/model/dsilc/deliveryTermsText> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/deliveryTermsText> | deliveryTermsText |
| <https://iri.suomi.fi/model/dsilc/description> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/description> | description |
| <https://iri.suomi.fi/model/dsilc/descriptionOfGoodsText> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/descriptionOfGoodsText> | descriptionOfGoodsText |
| <https://iri.suomi.fi/model/dsilc/documentDate> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/documentDate> | documentDate |
| <https://iri.suomi.fi/model/dsilc/documentIdentifier> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/documentIdentifier> | documentIdentifier |
| <https://iri.suomi.fi/model/dsilc/documentType> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/documentType> | documentType |
| <https://iri.suomi.fi/model/dsilc/documentaryCreditTypeCode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/documentaryCreditTypeCode> | documentaryCreditTypeCode |
| <https://iri.suomi.fi/model/dsilc/draweeParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/draweeParty> | draweeParty |
| <https://iri.suomi.fi/model/dsilc/elevationMeters> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/elevationMeters> | elevationMeters |
| <https://iri.suomi.fi/model/dsilc/endDate> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/endDate> | endDate |
| <https://iri.suomi.fi/model/dsilc/expiryDate> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/expiryDate> | expiryDate |
| <https://iri.suomi.fi/model/dsilc/finalDestinationUNLocode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/finalDestinationUNLocode> | finalDestinationUNLocode |
| <https://iri.suomi.fi/model/dsilc/geoWKT> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/geoWKT> | geoWKT |
| <https://iri.suomi.fi/model/dsilc/hasAddress> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasAddress> | hasAddress |
| <https://iri.suomi.fi/model/dsilc/hasAmount> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasAmount> | hasAmount |
| <https://iri.suomi.fi/model/dsilc/hasAvailabilityMethod> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasAvailabilityMethod> | hasAvailabilityMethod |
| <https://iri.suomi.fi/model/dsilc/hasCountryOfOrigin> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasCountryOfOrigin> | hasCountryOfOrigin |
| <https://iri.suomi.fi/model/dsilc/hasCreditAvailability> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasCreditAvailability> | hasCreditAvailability |
| <https://iri.suomi.fi/model/dsilc/hasDangerousGoodsDetails> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasDangerousGoodsDetails> | hasDangerousGoodsDetails |
| <https://iri.suomi.fi/model/dsilc/hasDeliveryMilestone> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasDeliveryMilestone> | hasDeliveryMilestone |
| <https://iri.suomi.fi/model/dsilc/hasDeliveryPeriod> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasDeliveryPeriod> | hasDeliveryPeriod |
| <https://iri.suomi.fi/model/dsilc/hasGoodsItem> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasGoodsItem> | hasGoodsItem |
| <https://iri.suomi.fi/model/dsilc/hasIdentifier> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasIdentifier> | hasIdentifier |
| <https://iri.suomi.fi/model/dsilc/hasMessage> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasMessage> | hasMessage |
| <https://iri.suomi.fi/model/dsilc/hasPaymentLine> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasPaymentLine> | hasPaymentLine |
| <https://iri.suomi.fi/model/dsilc/hasPaymentScheduleLine> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasPaymentScheduleLine> | hasPaymentScheduleLine |
| <https://iri.suomi.fi/model/dsilc/hasPaymentTerms> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasPaymentTerms> | hasPaymentTerms |
| <https://iri.suomi.fi/model/dsilc/hasPresentationPeriod> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasPresentationPeriod> | hasPresentationPeriod |
| <https://iri.suomi.fi/model/dsilc/hasQuantity> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasQuantity> | hasQuantity |
| <https://iri.suomi.fi/model/dsilc/hasShipment> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasShipment> | hasShipment |
| <https://iri.suomi.fi/model/dsilc/hasShipmentPeriod> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hasShipmentPeriod> | hasShipmentPeriod |
| <https://iri.suomi.fi/model/dsilc/hazardousRiskIndicator> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/hazardousRiskIndicator> | hazardousRiskIndicator |
| <https://iri.suomi.fi/model/dsilc/iataCode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/iataCode> | iataCode |
| <https://iri.suomi.fi/model/dsilc/icaoAirportCode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/icaoAirportCode> | icaoAirportCode |
| <https://iri.suomi.fi/model/dsilc/includesAllowanceCharge> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/includesAllowanceCharge> | includesAllowanceCharge |
| <https://iri.suomi.fi/model/dsilc/incotermsCode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/incotermsCode> | incotermsCode |
| <https://iri.suomi.fi/model/dsilc/instructedParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/instructedParty> | instructedParty |
| <https://iri.suomi.fi/model/dsilc/instructingParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/instructingParty> | instructingParty |
| <https://iri.suomi.fi/model/dsilc/instructionText> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/instructionText> | instructionText |
| <https://iri.suomi.fi/model/dsilc/instructionToBank> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/instructionToBank> | instructionToBank |
| <https://iri.suomi.fi/model/dsilc/insuranceValueAmount> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/insuranceValueAmount> | insuranceValueAmount |
| <https://iri.suomi.fi/model/dsilc/invoiceDocument> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/invoiceDocument> | invoiceDocument |
| <https://iri.suomi.fi/model/dsilc/isRealizedByConsignment> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/isRealizedByConsignment> | isRealizedByConsignment |
| <https://iri.suomi.fi/model/dsilc/issueDate> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/issueDate> | issueDate |
| <https://iri.suomi.fi/model/dsilc/issuerParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/issuerParty> | issuerParty |
| <https://iri.suomi.fi/model/dsilc/issuingBankParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/issuingBankParty> | issuingBankParty |
| <https://iri.suomi.fi/model/dsilc/itemDescriptionText> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/itemDescriptionText> | itemDescriptionText |
| <https://iri.suomi.fi/model/dsilc/latestPresentationDate> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/latestPresentationDate> | latestPresentationDate |
| <https://iri.suomi.fi/model/dsilc/latestShipmentDate> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/latestShipmentDate> | latestShipmentDate |
| <https://iri.suomi.fi/model/dsilc/latitude> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/latitude> | latitude |
| <https://iri.suomi.fi/model/dsilc/locationCountry> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/locationCountry> | locationCountry |
| <https://iri.suomi.fi/model/dsilc/locationID> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/locationID> | locationID |
| <https://iri.suomi.fi/model/dsilc/locationName> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/locationName> | locationName |
| <https://iri.suomi.fi/model/dsilc/longitude> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/longitude> | longitude |
| <https://iri.suomi.fi/model/dsilc/maturityDate> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/maturityDate> | maturityDate |
| <https://iri.suomi.fi/model/dsilc/maximumCreditAmount> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/maximumCreditAmount> | maximumCreditAmount |
| <https://iri.suomi.fi/model/dsilc/multiplierFactorPercent> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/multiplierFactorPercent> | multiplierFactorPercent |
| <https://iri.suomi.fi/model/dsilc/name> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/name> | name |
| <https://iri.suomi.fi/model/dsilc/numberOfCopies> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/numberOfCopies> | numberOfCopies |
| <https://iri.suomi.fi/model/dsilc/numberOfOriginals> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/numberOfOriginals> | numberOfOriginals |
| <https://iri.suomi.fi/model/dsilc/obligorParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/obligorParty> | obligorParty |
| <https://iri.suomi.fi/model/dsilc/partialShipmentAllowed> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/partialShipmentAllowed> | partialShipmentAllowed |
| <https://iri.suomi.fi/model/dsilc/partyAddress> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/partyAddress> | partyAddress |
| <https://iri.suomi.fi/model/dsilc/partyIdentifier> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/partyIdentifier> | partyIdentifier |
| <https://iri.suomi.fi/model/dsilc/partyLegalEntity> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/partyLegalEntity> | partyLegalEntity |
| <https://iri.suomi.fi/model/dsilc/payeeParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/payeeParty> | payeeParty |
| <https://iri.suomi.fi/model/dsilc/paymentDueDate> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/paymentDueDate> | paymentDueDate |
| <https://iri.suomi.fi/model/dsilc/paymentSettlementMethod> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/paymentSettlementMethod> | paymentSettlementMethod |
| <https://iri.suomi.fi/model/dsilc/paymentTermCode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/paymentTermCode> | paymentTermCode |
| <https://iri.suomi.fi/model/dsilc/perUnitAmount> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/perUnitAmount> | perUnitAmount |
| <https://iri.suomi.fi/model/dsilc/placeOfDelivery> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfDelivery> | placeOfDelivery |
| <https://iri.suomi.fi/model/dsilc/placeOfDeliveryUNLocode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfDeliveryUNLocode> | placeOfDeliveryUNLocode |
| <https://iri.suomi.fi/model/dsilc/placeOfDischarge> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfDischarge> | placeOfDischarge |
| <https://iri.suomi.fi/model/dsilc/placeOfExpiry> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfExpiry> | placeOfExpiry |
| <https://iri.suomi.fi/model/dsilc/placeOfLoading> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfLoading> | placeOfLoading |
| <https://iri.suomi.fi/model/dsilc/placeOfPresentation> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfPresentation> | placeOfPresentation |
| <https://iri.suomi.fi/model/dsilc/placeOfReceiptUNLocode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/placeOfReceiptUNLocode> | placeOfReceiptUNLocode |
| <https://iri.suomi.fi/model/dsilc/portFacilityCode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/portFacilityCode> | portFacilityCode |
| <https://iri.suomi.fi/model/dsilc/portOfDischargeUNLocode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/portOfDischargeUNLocode> | portOfDischargeUNLocode |
| <https://iri.suomi.fi/model/dsilc/portOfLoadingUNLocode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/portOfLoadingUNLocode> | portOfLoadingUNLocode |
| <https://iri.suomi.fi/model/dsilc/postCode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/postCode> | postCode |
| <https://iri.suomi.fi/model/dsilc/presentationBaseEvent> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/presentationBaseEvent> | presentationBaseEvent |
| <https://iri.suomi.fi/model/dsilc/presentationPeriodDays> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/presentationPeriodDays> | presentationPeriodDays |
| <https://iri.suomi.fi/model/dsilc/productIdentifier> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/productIdentifier> | productIdentifier |
| <https://iri.suomi.fi/model/dsilc/publicationDate> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/publicationDate> | publicationDate |
| <https://iri.suomi.fi/model/dsilc/publisher> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/publisher> | publisher |
| <https://iri.suomi.fi/model/dsilc/referencesPreAdvice> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/referencesPreAdvice> | referencesPreAdvice |
| <https://iri.suomi.fi/model/dsilc/reimbursingBankParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/reimbursingBankParty> | reimbursingBankParty |
| <https://iri.suomi.fi/model/dsilc/relatedOrder> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/relatedOrder> | relatedOrder |
| <https://iri.suomi.fi/model/dsilc/relatesToConsignment> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/relatesToConsignment> | relatesToConsignment |
| <https://iri.suomi.fi/model/dsilc/requestedConfirmationParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/requestedConfirmationParty> | requestedConfirmationParty |
| <https://iri.suomi.fi/model/dsilc/requestedDeliveryPeriod> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/requestedDeliveryPeriod> | requestedDeliveryPeriod |
| <https://iri.suomi.fi/model/dsilc/requiredDocumentType> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/requiredDocumentType> | requiredDocumentType |
| <https://iri.suomi.fi/model/dsilc/requiresDocument> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/requiresDocument> | requiresDocument |
| <https://iri.suomi.fi/model/dsilc/ruleSetIdentifier> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/ruleSetIdentifier> | ruleSetIdentifier |
| <https://iri.suomi.fi/model/dsilc/sellerParty> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/sellerParty> | sellerParty |
| <https://iri.suomi.fi/model/dsilc/shipmentIdentifier> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/shipmentIdentifier> | shipmentIdentifier |
| <https://iri.suomi.fi/model/dsilc/startDate> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/startDate> | startDate |
| <https://iri.suomi.fi/model/dsilc/tenor> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/tenor> | tenor |
| <https://iri.suomi.fi/model/dsilc/tenorPeriod> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/tenorPeriod> | tenorPeriod |
| <https://iri.suomi.fi/model/dsilc/terminalCode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/terminalCode> | terminalCode |
| <https://iri.suomi.fi/model/dsilc/timeZone> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/timeZone> | timeZone |
| <https://iri.suomi.fi/model/dsilc/title> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/title> | title |
| <https://iri.suomi.fi/model/dsilc/totalGoodsItemQuantity> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/totalGoodsItemQuantity> | totalGoodsItemQuantity |
| <https://iri.suomi.fi/model/dsilc/totalPackageQuantity> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/totalPackageQuantity> | totalPackageQuantity |
| <https://iri.suomi.fi/model/dsilc/totalTransportHandlingUnitQuantity> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/totalTransportHandlingUnitQuantity> | totalTransportHandlingUnitQuantity |
| <https://iri.suomi.fi/model/dsilc/transshipmentAllowed> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/transshipmentAllowed> | transshipmentAllowed |
| <https://iri.suomi.fi/model/dsilc/uicStationCode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/uicStationCode> | uicStationCode |
| <https://iri.suomi.fi/model/dsilc/unlocode> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/unlocode> | unlocode |
| <https://iri.suomi.fi/model/dsilc/versionIdentifier> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/versionIdentifier> | versionIdentifier |
| <https://iri.suomi.fi/model/dsilc/warehouseGLN> | sh:path | <https://iri.suomi.fi/model/ktddecv/0.0.4/warehouseGLN> | warehouseGLN |

---

---

# Appendix A — Full Turtle instance

The full RDF/Turtle example dataset for the Finnish gluelam export scenario is included below for reference.


## Full Turtle instance
```turtle
@prefix ex: <https://example.org/fi-jp/> .
@prefix ns1: <https://iri.suomi.fi/model/ktddecv/0.0.4/> .
@prefix rdfs: <http://www.w3.org/2000/01/rdf-schema#> .
@prefix xsd: <http://www.w3.org/2001/XMLSchema#> .

ex:Additional_Amount_Category a ns1:AdditionalAmountCategory ;
    rdfs:label "Additional Amount Category"@en .

ex:Allowance_Charge a ns1:AllowanceCharge ;
    rdfs:label "Allowance Charge"@en ;
    ns1:allowanceChargeReasonCode "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:baseAmount 12500000.0 ;
    ns1:calculationPercent "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:chargeIndicator "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:chargedByParty "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:chargedToParty "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:hasAmount 12500000.0 ;
    ns1:multiplierFactorPercent "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:perUnitAmount 12500000.0 .

ex:Availability_Method a ns1:AvailabilityMethod ;
    rdfs:label "Availability Method"@en .

ex:Bank_Instruction a ns1:BankInstruction ;
    rdfs:label "Bank Instruction"@en .

ex:Business_Document a ns1:BusinessDocument ;
    rdfs:label "Business Document"@en ;
    ns1:documentType "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:hasMessage "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" .

ex:Credit_Availability a ns1:CreditAvailability ;
    rdfs:label "Credit Availability"@en ;
    ns1:availableAtPlace "Tokyo (JP TYOKO)" ;
    ns1:availableWithParty "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:availableWithQualifier "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:draweeParty ex:Party ;
    ns1:hasAmount 12500000.0 ;
    ns1:hasAvailabilityMethod ex:AvailabilityMethod ;
    ns1:maturityDate "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:obligorParty "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:payeeParty "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:tenor "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" .

ex:Delivery_Milestone a ns1:DeliveryMilestone ;
    rdfs:label "Delivery Milestone"@en ;
    ns1:hasShipmentPeriod ex:PeriodOfTime .

ex:Document_Requirement a ns1:DocumentRequirement ;
    rdfs:label "Document Requirement"@en ;
    ns1:issuerParty "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:numberOfCopies "FI1234567-8" ;
    ns1:numberOfOriginals "FI1234567-8" ;
    ns1:requiredDocumentType "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" .

ex:Documentary_Credit a ns1:DocumentaryCredit ;
    rdfs:label "Documentary Credit"@en ;
    ns1:additionalAmountsCovered ex:AdditionalAmountCategory ;
    ns1:additionalConditionsText "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:adviseThroughBankParty ex:Party ;
    ns1:advisingBankParty ex:Party ;
    ns1:applicableRules ex:RuleSet ;
    ns1:applicantBankParty ex:Party ;
    ns1:applicantParty ex:Party ;
    ns1:beneficiaryParty ex:Party ;
    ns1:confirmationAddedDate "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:confirmationInstructionCode ex:Concept ;
    ns1:confirmingParty ex:Party ;
    ns1:coversAdditionalCharge ex:AllowanceCharge ;
    ns1:creditAmountTolerancePercentage 12500000.0 ;
    ns1:creditIdentifier "FI1234567-8" ;
    ns1:documentaryCreditTypeCode "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:draweeParty ex:Party ;
    ns1:expiryDate "2025-03-31"^^xsd:date ;
    ns1:hasAvailabilityMethod ex:AvailabilityMethod ;
    ns1:hasCreditAvailability ex:CreditAvailability ;
    ns1:hasDeliveryMilestone ex:DeliveryMilestone ;
    ns1:hasPaymentLine ex:PaymentLine ;
    ns1:hasPaymentTerms ex:PaymentTerms ;
    ns1:hasPresentationPeriod ex:PeriodOfTime ;
    ns1:hasShipment ex:Shipment ;
    ns1:hasShipmentPeriod ex:PeriodOfTime ;
    ns1:includesAllowanceCharge ex:AllowanceCharge ;
    ns1:instructionToBank ex:BankInstruction ;
    ns1:issueDate "2025-01-15"^^xsd:date ;
    ns1:issuingBankParty ex:Party ;
    ns1:latestPresentationDate "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:latestShipmentDate "2025-02-20"^^xsd:date ;
    ns1:maximumCreditAmount ex:MonetaryAmount ;
    ns1:partialShipmentAllowed "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:placeOfExpiry ex:Location ;
    ns1:placeOfPresentation ex:Location ;
    ns1:presentationBaseEvent ex:ShipmentBasis ;
    ns1:presentationPeriodDays 21 ;
    ns1:referencesPreAdvice ex:Document ;
    ns1:reimbursingBankParty ex:Party ;
    ns1:requestedConfirmationParty ex:Party ;
    ns1:requiresDocument ex:DocumentRequirement ;
    ns1:transshipmentAllowed "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" .

ex:Duty_Tax_Fee a ns1:DutyTaxFee ;
    rdfs:label "Duty/Tax/Fee"@en .

ex:Goods_Item a ns1:GoodsItem ;
    rdfs:label "Goods Item"@en ;
    ns1:appliedCommodityClassification "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:descriptionOfGoodsText "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:hasCountryOfOrigin "FI" ;
    ns1:hasDangerousGoodsDetails "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:hasQuantity 250 ;
    ns1:itemDescriptionText "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:productIdentifier "FI1234567-8" .

ex:Instruction a ns1:Instruction ;
    rdfs:label "Instruction"@en ;
    ns1:instructedParty "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:instructingParty "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:instructionText "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" .

ex:Legal_Entity a ns1:LegalEntity ;
    rdfs:label "Legal Entity"@en .

ex:Monetary_Amount a ns1:MonetaryAmount ;
    rdfs:label "Monetary Amount"@en ;
    ns1:amountValue 12500000.0 ;
    ns1:currencyCode "JPY" .

ex:Payment_Line a ns1:PaymentLine ;
    rdfs:label "Payment Line"@en ;
    ns1:hasAmount 12500000.0 ;
    ns1:payeeParty "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:paymentDueDate "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:paymentSettlementMethod "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:tenor "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" .

ex:Payment_Schedule_Line a ns1:PaymentScheduleLine ;
    rdfs:label "Payment Schedule Line"@en ;
    ns1:amountPercentOfBase 12500000.0 ;
    ns1:baseAmount 12500000.0 ;
    ns1:deferredPaymentDate "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:hasAmount 12500000.0 ;
    ns1:paymentDueDate "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" .

ex:Payment_Terms a ns1:PaymentTerms ;
    rdfs:label "Payment Terms"@en ;
    ns1:hasPaymentScheduleLine ex:PaymentScheduleLine ;
    ns1:paymentTermCode "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:tenor "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:tenorPeriod 21 .

ex:Period_of_Time a ns1:PeriodOfTime ;
    rdfs:label "Period of Time"@en ;
    ns1:endDate "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:startDate "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" .

ex:Presentation a ns1:Presentation ;
    rdfs:label "Presentation"@en .

ex:Rule_Set a ns1:RuleSet ;
    rdfs:label "Rule Set"@en ;
    ns1:publicationDate "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:publisher "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:ruleSetIdentifier "FI1234567-8" ;
    ns1:title "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:versionIdentifier "FI1234567-8" .

ex:Shipment_Basis a ns1:ShipmentBasis ;
    rdfs:label "Shipment Basis"@en .

ex:Trade_Delivery_Terms a ns1:TradeDeliveryTerms ;
    rdfs:label "Trade Delivery Terms"@en ;
    ns1:applicableRules ex:RuleSet ;
    ns1:deliveryTermsText "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:hasDeliveryPeriod 21 ;
    ns1:includesAllowanceCharge ex:AllowanceCharge ;
    ns1:incotermsCode "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:placeOfDelivery "Tokyo (JP TYOKO)" ;
    ns1:placeOfDischarge "Tokyo (JP TYOKO)" ;
    ns1:placeOfLoading "Kotka (FI KTK)" ;
    ns1:relatesToConsignment "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" .

ex:AdditionalAmountCategory a ns1:AdditionalAmountCategory ;
    rdfs:label "Example AdditionalAmountCategory" .

ex:BankInstruction a ns1:BankInstruction ;
    rdfs:label "Example BankInstruction" .

ex:Concept a <http://www.w3.org/2004/02/skos/core#Concept> ;
    rdfs:label "Example Concept" .

ex:Country a ns1:Country ;
    rdfs:label "Example Country",
        "Country"@en ;
    ns1:countryCode "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:countryName "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" .

ex:CreditAvailability a ns1:CreditAvailability ;
    rdfs:label "Example CreditAvailability" .

ex:DeliveryMilestone a ns1:DeliveryMilestone ;
    rdfs:label "Example DeliveryMilestone" .

ex:DocumentRequirement a ns1:DocumentRequirement ;
    rdfs:label "Example DocumentRequirement" .

ex:GoodsItem a ns1:GoodsItem ;
    rdfs:label "Example GoodsItem" .

ex:LegalEntity a ns1:LegalEntity ;
    rdfs:label "Example LegalEntity" .

ex:PaymentLine a ns1:PaymentLine ;
    rdfs:label "Example PaymentLine" .

ex:PaymentScheduleLine a ns1:PaymentScheduleLine ;
    rdfs:label "Example PaymentScheduleLine" .

ex:PaymentTerms a ns1:PaymentTerms ;
    rdfs:label "Example PaymentTerms" .

ex:Shipment a ns1:Shipment ;
    rdfs:label "Example Shipment",
        "Shipment"@en ;
    ns1:buyerParty ex:Party ;
    ns1:contractNumber "FI1234567-8" ;
    ns1:declaredCustomsValueAmount ex:MonetaryAmount ;
    ns1:deliveryTerms ex:TradeDeliveryTerms ;
    ns1:finalDestinationUNLocode "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:hasGoodsItem ex:GoodsItem ;
    ns1:hasShipmentPeriod ex:PeriodOfTime ;
    ns1:hazardousRiskIndicator "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:insuranceValueAmount ex:MonetaryAmount ;
    ns1:invoiceDocument ex:Document ;
    ns1:isRealizedByConsignment "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:placeOfDeliveryUNLocode "Tokyo (JP TYOKO)" ;
    ns1:placeOfReceiptUNLocode "Tokyo (JP TYOKO)" ;
    ns1:portOfDischargeUNLocode "Tokyo (JP TYOKO)" ;
    ns1:portOfLoadingUNLocode "Kotka (FI KTK)" ;
    ns1:relatedOrder "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:requestedDeliveryPeriod 21 ;
    ns1:sellerParty "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:shipmentIdentifier "FI1234567-8" ;
    ns1:totalGoodsItemQuantity 250 ;
    ns1:totalPackageQuantity 250 ;
    ns1:totalTransportHandlingUnitQuantity 250 .

ex:ShipmentBasis a ns1:ShipmentBasis ;
    rdfs:label "Example ShipmentBasis" .

ex:TradeDeliveryTerms a ns1:TradeDeliveryTerms ;
    rdfs:label "Example TradeDeliveryTerms" .

ex:Address a ns1:Address ;
    rdfs:label "Example Address",
        "Address"@en .

ex:AvailabilityMethod a ns1:AvailabilityMethod ;
    rdfs:label "Example AvailabilityMethod" .

ex:Document a ns1:Document ;
    rdfs:label "Example Document",
        "Document"@en ;
    ns1:documentDate "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:documentIdentifier "FI1234567-8" .

ex:Identifier a ns1:Identifier ;
    rdfs:label "Example Identifier",
        "Identifier"@en .

ex:Location a ns1:Location ;
    rdfs:label "Example Location",
        "Location"@en ;
    ns1:alternateName "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:borderCrossingPointCode "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:customsOfficeCode "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:description "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:elevationMeters "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:geoWKT "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:hasAddress ex:Address ;
    ns1:hasIdentifier ex:Identifier ;
    ns1:iataCode "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:icaoAirportCode "Tokyo (JP TYOKO)" ;
    ns1:latitude "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:locationCountry ex:Country ;
    ns1:locationID "FI1234567-8" ;
    ns1:locationName "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:longitude "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:portFacilityCode "Tokyo (JP TYOKO)" ;
    ns1:postCode "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:terminalCode "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:timeZone "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:uicStationCode "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:unlocode "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:warehouseGLN "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" .

ex:RuleSet a ns1:RuleSet ;
    rdfs:label "Example RuleSet" .

ex:AllowanceCharge a ns1:AllowanceCharge ;
    rdfs:label "Example AllowanceCharge" .

ex:MonetaryAmount a ns1:MonetaryAmount ;
    rdfs:label "Example MonetaryAmount" .

ex:PeriodOfTime a ns1:PeriodOfTime ;
    rdfs:label "Example PeriodOfTime" .

ex:Party a ns1:Party ;
    rdfs:label "Example Party",
        "Party"@en ;
    ns1:name "Finnish glued laminated timber (glulam) beams, planed, structural grade GL28h" ;
    ns1:partyAddress ex:Address ;
    ns1:partyIdentifier ex:Identifier ;
    ns1:partyLegalEntity ex:LegalEntity .


```