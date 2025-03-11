# Technical Documentation Review: subscriptions-faq.md

## Summary

This document is a FAQ addressing common questions about the Subscriptions feature. The content is informative and helpful, but it needs significant revisions to align with the E&D Style Guide, particularly in formatting, link text, and capitalization.

## Detailed Findings

### Issue 1

- **Location**: Title
- **Current Text**: "Subscriptions: FAQ"
- **Recommendation**: "Subscriptions FAQ" or "Frequently Asked Questions About Subscriptions"
- **Applicable Guideline**: 4. Headings and titles - Make the learning objective of the article clear, preferably with only one verb. Your heading or title must be descriptive, as short as possible, and generally convey only one main action.
- **Rationale**: The current title is acceptable, but the suggested alternatives are more concise and align better with the purpose of the document.

### Issue 2

- **Location**: Introduction paragraph
- **Current Text**: "This article intends to answer some of the most frequently asked questions about Subscriptions."
- **Recommendation**: "This article answers frequently asked questions about Subscriptions."
- **Applicable Guideline**: 1. Pragmatics -> 1.1 Discourse - Technical writing is direct, informative, clear, and concise language written specifically for an identified audience.
- **Rationale**: The phrase "This article intends to answer some of the most frequently asked questions" is redundant and can be simplified.

### Issue 3

- **Location**: Question "Can I have more than one subscription in my store?"
- **Current Text**: "Can I have more than one subscription in my store?"
- **Recommendation**: "Can I Have More Than One Subscription in My Store?"
- **Applicable Guideline**: 3.1. Sentence case - Use sentence case for titles, headings, lists, and table elements.
- **Rationale**: According to style guidelines, all article titles and questions must follow sentence case.

### Issue 4

- **Location**: Question "Can my customer buy via subscription and pick up from stores or other pickup points?"
- **Current Text**: "Yes, read our article [Pickup points for Subscriptions (Beta)](https://help.vtex.com/en/tutorial/pickup-points-for-subscription-orders-beta--csIqB6iBh4QNIFdEj0nVv) for more information."
- **Recommendation**: "Yes. For more information, see the Pickup points for Subscriptions (Beta) article."
- **Applicable Guideline**: 5.2. Writing link text - When you write a complete sentence that refers to another topic, introduce the link with the phrase *For more information, see* or *For more information about..., see*.
- **Rationale**: This adheres to the prescribed format for introducing links to other topics.

### Issue 5

- **Location**: Question "Can my customer pay for their subscription orders in installments?"
- **Current Text**: "Yes, as long as the store is configured to allow installments for subscriptions orders. This is done through the [Edit subscriptions settings](https://developers.vtex.com/docs/api-reference/subscriptions-api-v3#post-/api/rns/settings) endpoint, marking the `isMultipleInstallmentsEnabledOnCreation` and `isMultipleInstallmentsEnabledOnUpdate` fields as `true`."
- **Recommendation**: "Yes, if the store is configured to allow installments for subscription orders. To configure this, use the Edit subscriptions settings endpoint, marking the `isMultipleInstallmentsEnabledOnCreation` and `isMultipleInstallmentsEnabledOnUpdate` fields as `true`."
- **Applicable Guideline**: 5.2. Writing link text - When you write a complete sentence that refers to another topic, introduce the link with the phrase *For more information, see* or *For more information about..., see*. 8.2 Button names - When referring to names for buttons in a list or numbered procedure or bulleted list, format the button name as code.
- **Rationale**: The link is not introduced using the recommended format from the style guide. The terms `isMultipleInstallmentsEnabledOnCreation` and `isMultipleInstallmentsEnabledOnUpdate` are code-related elements, so they must be written using code formatting.

### Issue 6

- **Location**: Question "Does the functionality Subscriptions work with Seller Portal?"
- **Current Text**: "No, Subscriptions does not work with [Seller Portal](https://help.vtex.com/en/tutorial/how-to-set-up-your-store-on-seller-portal)."
- **Recommendation**: "No, Subscriptions does not work with Seller Portal. For more information, see How to set up your store on Seller Portal."
- **Applicable Guideline**: 5.2. Writing link text - When you write a complete sentence that refers to another topic, introduce the link with the phrase *For more information, see* or *For more information about..., see*.
- **Rationale**: This adheres to the prescribed format for introducing links to other topics.

### Issue 7

- **Location**: Question "How does it work to create subscriptions from original orders that have SKUs with attachments?"
- **Current Text**: "By default, stores do not create subscription orders associating SKU [attachments](https://help.vtex.com/en/tutorial/o-que-e-um-anexo--aGICk0RVbqKg6GYmQcWUm) with the original order, i.e., attachments are not considered in recurring orders. However, you can enable this setting for your store, but it can only be done via API using the [Edit subscriptions settings](https://developers.vtex.com/docs/api-reference/subscriptions-api-v3#post-/api/rns/settings) endpoint. Learn more in [How to keep attachments from original orders in subscriptions](https://developers.vtex.com/docs/guides/how-to-keep-attachments-from-original-orders-in-subscriptions)."
- **Recommendation**: "By default, stores do not create subscription orders associating SKU attachments with the original order, meaning attachments are not considered in recurring orders. However, you can enable this setting for your store via API using the Edit subscriptions settings endpoint. For more information, see How to keep attachments from original orders in subscriptions."
- **Applicable Guideline**: 5.2. Writing link text - When you write a complete sentence that refers to another topic, introduce the link with the phrase *For more information, see* or *For more information about..., see*.
- **Rationale**: This adheres to the prescribed format for introducing links to other topics.

## Positive Aspects

- The document provides answers to common questions about the Subscriptions feature.
- The information is generally clear and easy to understand.

## Recommendations for This Document

1. **Revise Headings**: Use more descriptive and actionable headings.
2. **Standardize Link Text**: Ensure all links follow the prescribed format (e.g., "For more information, see...").
3. **Apply Consistent Formatting**: Use bold text, code formatting, and sentence case according to the style guide.
