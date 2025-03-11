# Technical Documentation Review: vtex-io-documentation-engineering-guidelines.md

## Document Information
- File: Input docs/vtex-io-documentation-engineering-guidelines.md
- Review Date: 2024-03-07
- Reviewer: Claude 3.7 Sonnet

## Summary
This document provides engineering best practices for VTEX IO app development. The content is comprehensive and well-structured with clear headings and logical organization. However, there are several inconsistencies with the style guide, particularly in the formatting of callouts, links, and some technical terms that should be addressed to improve readability and adherence to the style guide.

## Detailed Findings

### Issue 1
- **Location**: Beginning of the document
- **Current Text**: ">⚠️ Notice that you must respect these guidelines if you aim to publish your app at the VTEX App Store."
- **Recommendation**: Replace the Markdown blockquote with the proper HTML div format for a warning callout.
- **Applicable Guideline**: 9.5 Formatting callouts - "Callouts use HTML `<div>` tags with Bootstrap CSS classes"
- **Rationale**: Using the proper callout format ensures consistent styling and accessibility across all documentation.

### Issue 2
- **Location**: "Using APIs efficiently" section
- **Current Text**: ">ℹ️ **Performance of external systems**
>
>When you offer your app on the VTEX App Store, your app may become available to brands of all sizes across different time zones and business calendars. In this context, relying on a manual system with on-demand scalability can become a huge risk in terms of performance."
- **Recommendation**: Replace the Markdown blockquote with the proper HTML div format for an information callout.
- **Applicable Guideline**: 9.5 Formatting callouts - "Callouts use HTML `<div>` tags with Bootstrap CSS classes"
- **Rationale**: Using the proper callout format ensures consistent styling and accessibility across all documentation.

### Issue 3
- **Location**: "Using the latest builders" section
- **Current Text**: "For developing and publishing apps for the VTEX App Store, the following builders must be up-to-date in your app's code:

- Node builder - version 7.x.
- React builder - version 3.x.
- Admin builder - version 1.x.
- Messages builder - version 1.x.
- Docs builder- version 0.x.
- Graphql builder -version 1.x."
- **Recommendation**: Format version numbers consistently using code formatting.
- **Applicable Guideline**: 8.1 Placeholders - "When mentioning a placeholder in a flowing text, format it as code without the curly brackets."
- **Rationale**: Consistent formatting of version numbers improves readability and follows the style guide.

### Issue 4
- **Location**: "Hardcoding VTEX appKey/appToken" section
- **Current Text**: "Having an appKey/appToken exposed in your code can cause serious security issues, like unwanted access. Instead of using a VTEX appKey/appToken pair, apps should use the existing tokens (`ctx.authToken`,  `ctx.vtex.storeUserAuthToken` or `ctx.vtex.adminUserAuthToken`)."
- **Recommendation**: Format code elements consistently using code formatting.
- **Applicable Guideline**: 8.1 Placeholders - "When mentioning a placeholder in a flowing text, format it as code without the curly brackets."
- **Rationale**: Consistent formatting of code elements improves readability and follows the style guide.

### Issue 5
- **Location**: "Declaring broad policies" section
- **Current Text**: "Outbound access policies (`outbound-access`) to VTEX resources should follow the [principle of least privilege](https://en.wikipedia.org/wiki/Principle_of_least_privilege). In short, you only give access to what is really needed. For instance, the `path` should not be configured as `*`."
- **Recommendation**: Format code elements consistently using code formatting.
- **Applicable Guideline**: 8.1 Placeholders - "When mentioning a placeholder in a flowing text, format it as code without the curly brackets."
- **Rationale**: Consistent formatting of code elements improves readability and follows the style guide.

### Issue 6
- **Location**: "Do not expose private information through public routes" section
- **Current Text**: "Access to REST APIs should be restricted using [policies](https://developers.vtex.com/docs/guides/vtex-io-documentation-policies#resource-based-policies). Access to GraphQL APIs should be restricted using directives, either [@auth](https://github.com/vtex/node-vtex-api/blob/08ea11d380997f5abf02455487b342caa74b2001/src/service/worker/runtime/graphql/schema/schemaDirectives/Auth.ts#L66-L75) or a custom-made one."
- **Recommendation**: Format code elements consistently using code formatting.
- **Applicable Guideline**: 8.1 Placeholders - "When mentioning a placeholder in a flowing text, format it as code without the curly brackets."
- **Rationale**: Consistent formatting of code elements improves readability and follows the style guide.

## Positive Aspects
- The document has a clear, logical structure with appropriate headings and subheadings.
- The content provides comprehensive guidance on engineering best practices.
- The document covers a wide range of important topics, from security to performance.
- Links to additional resources are appropriately provided where needed.
- The explanations are concise and focused on practical advice.

## Recommendations for This Document
- Replace all Markdown blockquotes with the proper HTML div format for callouts.
- Format code elements and version numbers consistently using code formatting.
- Consider adding more examples or code snippets to illustrate best practices.
- Add a troubleshooting section for common issues encountered during app development.
- Consider organizing the security section into more specific subsections for better navigation. 