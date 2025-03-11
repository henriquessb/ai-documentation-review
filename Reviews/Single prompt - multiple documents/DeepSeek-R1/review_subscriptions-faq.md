# Technical Documentation Review: subscriptions-faq.md  

## Summary  

The FAQ addresses common subscription queries with clarity but has formatting inconsistencies in headings, emphasis, and code elements. Key issues include improper title case, unformatted API references, and missing punctuation. Strengths include descriptive links and logical organization.  

---  

## Detailed Findings  

### Issue 1: Title-Case Headings  

- **Location**: Main title "Subscriptions: FAQ"  
- **Current Text**: `Subscriptions: FAQ`  
- **Recommendation**: Use sentence case: `Subscriptions FAQ`  
- **Applicable Guideline**: *Section 4. Headings and titles*: "Use sentence case for titles and headings."  
- **Rationale**: Colons and title case violate VTEX’s sentence-case rule for headings.  

### Issue 2: Italicized Setting Name  

- **Location**: "Minimum total value in cart"  
- **Current Text**: `_Minimum total value in cart_`  
- **Recommendation**: Format as bold: **Minimum total value in cart**  
- **Applicable Guideline**: *Section 1.1. Bold*: "Format interface elements and key settings in bold."  
- **Rationale**: Italics are reserved for foreign terms or conceptual emphasis, not UI elements.  

### Issue 3: Unformatted API Endpoints  

- **Location**: "post-/api/rns/settings"  
- **Current Text**: Plain text reference.  
- **Recommendation**: Format as code: `` `POST /api/rns/settings` ``  
- **Applicable Guideline**: *Section 8.1. Placeholders*: "Format API endpoints as code."  
- **Rationale**: Unformatted endpoints reduce technical clarity.  

### Issue 4: Missing Periods  

- **Location**: Answers like "It is not possible to add more than one address to the same subscription."  
- **Current Text**: Missing terminal punctuation.  
- **Recommendation**: Add periods to all declarative sentences.  
- **Applicable Guideline**: *Section 5.5. Period*: "End sentences with periods."  
- **Rationale**: Inconsistent punctuation disrupts readability.  

### Issue 5: Generic Link Text  

- **Location**: "[APIs](https://developers.vtex.com/docs/api-reference/subscriptions-api-v3#overview)"  
- **Current Text**: Generic label "APIs."  
- **Recommendation**: Use descriptive text: "[Subscriptions API](https://developers.vtex.com/docs/api-reference/subscriptions-api-v3#overview)"  
- **Applicable Guideline**: *Section 5.2. Writing link text*: "Avoid generic terms like *APIs*; use specific labels."  
- **Rationale**: Ambiguous links lack context for users.  

### Issue 6: Time Format Inconsistency  

- **Location**: "6:00 and 7:00 am in Brazil zone (GMT-3)."  
- **Current Text**: Lowercase "am" without periods.  
- **Recommendation**: Use standardized format: "6:00 AM and 7:00 AM (GMT-3)."  
- **Applicable Guideline**: *Section 2.1. Numbers*: "Use numerals and uppercase AM/PM with periods."  
- **Rationale**: Non-standard time formats reduce professionalism.  

---  

## Positive Aspects  

1. **Descriptive Links**: Internal VTEX articles (e.g., "[Pickup points for Subscriptions (Beta)](...)") are clearly labeled and relevant.  
2. **Structured FAQs**: Questions are organized logically, addressing common user concerns.  
3. **Code Formatting for Fields**: `isMultipleInstallmentsEnabledOnCreation` is correctly formatted as code.  

---  

## Recommendations for This Document  

1. **Revise Headings**: Convert all titles and subheadings to sentence case.  
2. **Standardize Emphasis**: Replace italics with bold for UI elements/settings.  
3. **Enhance API References**: Format endpoints and methods (e.g., `` `POST /api/rns/settings` ``) as code.  

---  

**Final Note**: The document effectively resolves subscription-related queries but requires adjustments to formatting and punctuation for full adherence to the Style Guide.
