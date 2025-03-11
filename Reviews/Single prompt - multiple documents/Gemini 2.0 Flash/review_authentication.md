# Technical Documentation Review: authentication.md

## Summary

This document provides a good overview of authentication methods on the VTEX platform, covering login, integrations, and app development. The content is generally well-structured and informative, but there are several areas where improvements can be made to adhere to the E&D Style Guide, particularly in formatting, heading structure, and link text.

## Detailed Findings

### Issue 1

- **Location**: Title
- **Current Text**: "Authentication"
- **Recommendation**: "Explain Authentication Methods" or "Understand Authentication on VTEX"
- **Applicable Guideline**: 4. Headings and titles - Make the learning objective of the article clear, preferably with only one verb. Your heading or title must be descriptive, as short as possible, and generally convey only one main action.
- **Rationale**: The current title is too generic. More descriptive titles help users quickly understand the purpose of the article.

### Issue 2

- **Location**: First paragraph, bulleted list
- **Current Text**: "* [Login](#login): Verifies and validates the user's identity when accessing an online store or the VTEX Admin."
- **Recommendation**: "* **Login:** Verifies and validates the user's identity when accessing an online store or the VTEX Admin."
- **Applicable Guideline**: 1.1. Bold - Whenever explaining concepts in bulleted lists. Be aware that in those situations, you only format bold the name or expression of the concept, nothing else in the explanation.
- **Rationale**: According to the style guide, in bulleted lists explaining concepts, only the name or expression of the concept should be in bold. The link should also be removed here.

### Issue 3

- **Location**: Table in the Login section
- **Current Text**: "Check out the [Configuring login with Facebook and Google](https://help.vtex.com/en/tutorial/configurar-login-com-facebook-e-google--tutorials_513) guide for more information."
- **Recommendation**: "For more information, see the Configuring login with Facebook and Google guide."
- **Applicable Guideline**: 5.2. Writing link text - When you write a complete sentence that refers to another topic, introduce the link with the phrase *For more information, see* or *For more information about..., see*.
- **Rationale**: This adheres to the prescribed format for introducing links to other topics.

### Issue 4

- **Location**: Table in the Login section - Webstore (OAuth 2.0) and Admin (SAML 2.0)
- **Current Text**: "Read the [Webstore (OAuth 2.0)](https://developers.vtex.com/docs/guides/login-integration-guide-webstore-oauth2) developer guide to learn more."
- **Recommendation**: "Read the Webstore (OAuth 2.0) developer guide for more information."
- **Applicable Guideline**: 5.2. Writing link text - When you write a complete sentence that refers to another topic, introduce the link with the phrase *For more information, see* or *For more information about..., see*.
- **Rationale**: This adheres to the prescribed format for introducing links to other topics.

### Issue 5

- **Location**: Alert boxes (both info and warning)
- **Current Text**: Uses `<div>` tags with Bootstrap CSS classes
- **Recommendation**: Use the callout format described in the style guide, with appropriate icons and formatting.
- **Applicable Guideline**: 9. Callouts - This describes the proper format for callouts.
- **Rationale**: Consistent formatting of callouts improves readability and aligns with the style guide.

### Issue 6

- **Location**: Enabling login methods, step 4
- **Current Text**: "In the **Password** row, click`Edit`."
- **Recommendation**: "In the **Password** row, click `Edit`."
- **Applicable Guideline**: 8.2. Button names - When referring to names for buttons in a list or numbered procedure or bulleted list, format the button name as code.
- **Rationale**: The button name Edit must be written using code formatting.

### Issue 7

- **Location**: Enforcing password expiration, step 7
- **Current Text**: "Click `Save`."
- **Recommendation**: "Click `Save`."
- **Applicable Guideline**: 8.2. Button names - When referring to names for buttons in a list or numbered procedure or bulleted list, format the button name as code.
- **Rationale**: The button name Save must be written using code formatting.

### Issue 8

- **Location**: Developing integrations, bulleted list
- **Current Text**: "* **Application keys (appKeys):** [Application keys](https://help.vtex.com/en/tutorial/application-keys--2iffYzlvvz4BDMr6WGUtet) authenticate requests made to VTEX APIs. Store admins can create keys and associate them with [roles](https://help.vtex.com/en/tutorial/roles--7HKK5Uau2H6wxE1rH5oRbc), allowing them to use certain platform[resources](https://help.vtex.com/en/tutorial/license-manager-resources--3q6ztrC8YynQf6rdc6euk3). Learn more in the [API authentication using application keys](https://developers.vtex.com/docs/guides/api-authentication-using-application-keys) developer guide."
- **Recommendation**: "* **Application keys (appKeys):** Application keys authenticate requests made to VTEX APIs. Store admins can create keys and associate them with roles, allowing them to use certain platform resources. For more information, see the API authentication using application keys developer guide."
- **Applicable Guideline**: 1.1. Bold - Whenever explaining concepts in bulleted lists. Be aware that in those situations, you only format bold the name or expression of the concept, nothing else in the explanation. 5.2. Writing link text - When you write a complete sentence that refers to another topic, introduce the link with the phrase *For more information, see* or *For more information about..., see*.
- **Rationale**: According to the style guide, in bulleted lists explaining concepts, only the name or expression of the concept should be in bold. The links must follow the format "For more information, see...".

## Positive Aspects

- The document provides a comprehensive overview of authentication methods.
- It includes clear steps for enabling login methods and enforcing password expiration.
- The use of a table to summarize login methods is effective.

## Recommendations for This Document

1. **Revise Headings**: Use more descriptive and actionable headings.
2. **Standardize Link Text**: Ensure all links follow the prescribed format (e.g., "For more information, see...").
3. **Apply Consistent Formatting**: Use bold text, code formatting, and callouts according to the style guide.
