# Technical Documentation Review: backend-integrations.md

## Summary

This document provides a comprehensive overview of backend integrations with the VTEX platform, covering ERP, PIM, WMS, CRM, catalog architecture, pricing, inventory, customer data, order integration, payments, and extensions. The document is well-structured and informative, offering valuable guidance for developers and store administrators. However, there are several areas where improvements can be made to adhere to the E&D Style Guide, particularly in formatting, link text, callouts, and headings.

## Detailed Findings

### Issue 1

- **Location**: First paragraph
- **Current Text**: "Integrations normally begin with back-office software, which allows the management of essential parts of the operation related to [Catalog](https://help.vtex.com/en/tracks/vtex-store-overview--eSDNk26pdvemF3XKM0nK9/75MX4aorniD0BYAB8Nwbo7#catalog), [Pricing](https://help.vtex.com/en/tracks/vtex-store-overview--eSDNk26pdvemF3XKM0nK9/75MX4aorniD0BYAB8Nwbo7#prices), [Logistics](https://help.vtex.com/en/tracks/vtex-store-overview--eSDNk26pdvemF3XKM0nK9/75MX4aorniD0BYAB8Nwbo7#logistics), and [Orders](https://help.vtex.com/en/tracks/vtex-store-overview--eSDNk26pdvemF3XKM0nK9/75MX4aorniD0BYAB8Nwbo7#pedidos)."
- **Recommendation**: "Integrations normally begin with back-office software, which allows the management of essential parts of the operation related to Catalog, Pricing, Logistics, and Orders. For more information, see the Catalog, Pricing, Logistics and Orders articles."
- **Applicable Guideline**: 5.2. Writing link text - When you write a complete sentence that refers to another topic, introduce the link with the phrase *For more information, see* or *For more information about..., see*. 1.1 Bold - Whenever you mention computer interfaces in the middle of the text.
- **Rationale**: This adheres to the prescribed format for introducing links to other topics. The terms Catalog, Pricing, Logistics and Orders must be written in bold.

### Issue 2

- **Location**: Headings such as "ERP integration", "Integrations"
- **Current Text**: "ERP integration", "Integrations"
- **Recommendation**: "Integrate with ERP", "Understand Integrations"
- **Applicable Guideline**: 4. Headings and titles - Preferably start with a verb in infinitive form or a noun. Verbs in the imperative should be used mainly in a sequence of steps.
- **Rationale**: The titles should express a clear action.

### Issue 3

- **Location**: ERP integration, last paragraph
- **Current Text**: "Learn more about setup in the [Back office integration guide (ERP/PIM/WMS)](https://developers.vtex.com/docs/guides/erp-integration-guide)."
- **Recommendation**: "For more information, see the Back office integration guide (ERP/PIM/WMS)."
- **Applicable Guideline**: 5.2. Writing link text - When you write a complete sentence that refers to another topic, introduce the link with the phrase *For more information, see* or *For more information about..., see*.
- **Rationale**: This adheres to the prescribed format for introducing links to other topics.

### Issue 4

- **Location**: Initial setup, step 1
- **Current Text**: "[Catalog architecture](#catalog-architecture)"
- **Recommendation**: "Catalog architecture"
- **Applicable Guideline**: 1.1 Bold - Whenever you mention computer interfaces in the middle of the text.
- **Rationale**: The term Catalog architecture must be written in bold.

### Issue 5

- **Location**: List item "Platform integration" under "Middleware configuration"
- **Current Text**: "**Platform integration:** This option involves using a third-party platform, known as Platform-as-a-Service (PaaS), which offers a ready-made solution to integrate with VTEX, requiring minimal development effort."
- **Recommendation**: "**Platform integration:** this option involves using a third-party platform, known as Platform-as-a-Service (PaaS), which offers a ready-made solution to integrate with VTEX, requiring minimal development effort."
- **Applicable Guideline**: 1.1. Bold - Whenever explaining concepts in bulleted lists. Be aware that in those situations, you only format bold the name or expression of the concept, nothing else in the explanation.
- **Rationale**: The concept name (Platform integration) is the only part that should be bold.

### Issue 6

- **Location**: Alert boxes
- **Current Text**: Uses `<div>` tags with Bootstrap CSS classes
- **Recommendation**: Use the callout format described in the style guide, with appropriate icons and formatting.
- **Applicable Guideline**: 9. Callouts - This describes the proper format for callouts.
- **Rationale**: Consistent formatting of callouts improves readability and aligns with the style guide.

### Issue 7

- **Location**: Section "Importing products"
- **Current Text**: There are multiple instances of the term `Product` and `SKU`.
- **Recommendation**: Format all instances of `Product` and `SKU` as code, as they refer to computer interfaces.
- **Applicable Guideline**: 8.2 Button names - When referring to names for buttons in a list or numbered procedure or bulleted list, format the button name as code.
- **Rationale**: This adheres to the style guide regarding computer interfaces.

### Issue 8

- **Location**: SSO - Table
- **Current Text**: Hyperlinked text `VTEX Admin` and `Webstore`
- **Recommendation**: Bold the terms and add links at the end of the sentence, following this format: "For more information, see the Admin (SAML 2.0) developer guide"
- **Applicable Guideline**: 1.1 Bold - Whenever you mention computer interfaces in the middle of the text.
- **Rationale**: This adheres to the style guide regarding computer interfaces.

## Positive Aspects

- The document provides a comprehensive overview of backend integrations.
- It includes detailed steps and guidance for various integration scenarios.
- The structure is logical and easy to follow.
- The document effectively communicates the importance of each integration for running a VTEX store.

## Recommendations for This Document

1. **Revise Headings**: Use more descriptive and actionable headings.
2. **Standardize Link Text**: Ensure all links follow the prescribed format (e.g., "For more information, see...").
3. **Apply Consistent Formatting**: Use bold text, code formatting, and callouts according to the style guide.
