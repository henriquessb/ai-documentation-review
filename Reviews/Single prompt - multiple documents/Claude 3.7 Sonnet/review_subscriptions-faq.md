# Technical Documentation Review: subscriptions-faq.md

## Document Information
- File: Input docs/subscriptions-faq.md
- Review Date: 2024-03-07
- Reviewer: Claude 3.7 Sonnet

## Summary
This document provides answers to frequently asked questions about VTEX Subscriptions. While the content is informative and addresses common questions, there are several inconsistencies with the style guide, particularly in the formatting of headings, links, and technical terms. The document would benefit from a more structured FAQ format and consistent formatting.

## Detailed Findings

### Issue 1
- **Location**: Throughout the document
- **Current Text**: All FAQ questions are formatted as H3 headings (###)
- **Recommendation**: Follow the FAQ template structure from the style guide, using H2 headings for topic categories and H3 headings for questions.
- **Applicable Guideline**: Frequently Asked Questions section - "Templates: Single topic FAQ" and "Multiple topics FAQ"
- **Rationale**: Using the proper FAQ template structure improves organization and readability.

### Issue 2
- **Location**: "Can my customer pay for their subscription orders in installments?" section
- **Current Text**: "This is done through the [Edit subscriptions settings](https://developers.vtex.com/docs/api-reference/subscriptions-api-v3#post-/api/rns/settings) endpoint, marking the `isMultipleInstallmentsEnabledOnCreation` and `isMultipleInstallmentsEnabledOnUpdate` fields as `true`."
- **Recommendation**: Format API endpoint names and parameters consistently using code formatting.
- **Applicable Guideline**: 8.1 Placeholders - "When mentioning a placeholder in a flowing text, format it as code without the curly brackets."
- **Rationale**: Consistent formatting of technical elements improves readability and follows the style guide.

### Issue 3
- **Location**: "What time are subscription orders generated?" section
- **Current Text**: "Subscription orders are created between 6:00 and 7:00 am in Brazil zone (GMT-3)."
- **Recommendation**: Use a more neutral global reference for time zones, such as "UTC-3" instead of "Brazil zone".
- **Applicable Guideline**: 2.3 Globalization - "Our content should be contextualized for users anywhere in the world."
- **Rationale**: Using standard time zone references improves clarity for a global audience.

### Issue 4
- **Location**: "If the retailer creates a minimum value rule, will it affect subscriptions?" section
- **Current Text**: "Yes, if the subscription order value is below the threshold defined by the _Minimum total value in cart_ setting."
- **Recommendation**: Use bold formatting instead of italic for UI elements.
- **Applicable Guideline**: 1.1 Bold - "The bold type formatting should be used in the following cases: Whenever you mention computer interfaces in the middle of the text."
- **Rationale**: Consistent formatting of UI elements improves readability and follows the style guide.

### Issue 5
- **Location**: "How does it work to create subscriptions from original orders that have SKUs with attachments?" section
- **Current Text**: "By default, stores do not create subscription orders associating SKU [attachments](https://help.vtex.com/en/tutorial/o-que-e-um-anexo--aGICk0RVbqKg6GYmQcWUm) with the original order, i.e., attachments are not considered in recurring orders."
- **Recommendation**: Avoid using abbreviations like "i.e." and spell out "that is" instead.
- **Applicable Guideline**: 4.3 Contractions - "When writing in English, do not use contractions."
- **Rationale**: Avoiding abbreviations improves clarity and follows the style guide.

### Issue 6
- **Location**: Introduction
- **Current Text**: "This article intends to answer some of the most frequently asked questions about Subscriptions."
- **Recommendation**: Add a brief explanation of what Subscriptions are before diving into the FAQs.
- **Applicable Guideline**: Frequently Asked Questions section - "Brief introduction about the topic."
- **Rationale**: Providing context about Subscriptions helps users understand the purpose of the feature before reading the FAQs.

## Positive Aspects
- The document covers a wide range of common questions about Subscriptions.
- The answers are concise and focused on providing useful information.
- The document includes links to additional resources for more detailed information.
- The questions are phrased from the perspective of store administrators, which is appropriate for the target audience.
- The document addresses both technical and business aspects of Subscriptions.

## Recommendations for This Document
- Restructure the document using the proper FAQ template from the style guide.
- Add a brief introduction explaining what Subscriptions are and their benefits.
- Ensure consistent formatting of UI elements, technical terms, and API references.
- Group related questions under topic categories for better organization.
- Consider adding a "Learn more" section at the end with links to related documentation. 