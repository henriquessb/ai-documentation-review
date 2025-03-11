# Technical Documentation Review: vtex-io-documentation-engineering-guidelines.md

## Summary

This document outlines engineering best practices for developing VTEX IO apps, covering scalability, security, data privacy, usability, and documentation. It provides valuable guidelines for developers aiming to publish their apps on the VTEX App Store. However, the document needs revisions to fully comply with the E&D Style Guide, particularly in formatting, link text, and callouts.

## Detailed Findings

### Issue 1

- **Location**: Title
- **Current Text**: "Engineering best practices"
- **Recommendation**: "Apply Engineering Best Practices" or "Follow Engineering Best Practices"
- **Applicable Guideline**: 4. Headings and titles - Make the learning objective of the article clear, preferably with only one verb. Your heading or title must be descriptive, as short as possible, and generally convey only one main action.
- **Rationale**: The current title is too generic. The suggested titles are more specific and action-oriented.

### Issue 2

- **Location**: Introduction paragraph
- **Current Text**: "Refer to the following guidelines to guarantee the quality and usability of your VTEX IO app during development."
- **Recommendation**: "Follow these guidelines to guarantee the quality and usability of your VTEX IO app during development."
- **Applicable Guideline**: 1. Pragmatics -> 1.1 Discourse - Technical writing is direct, informative, clear, and concise language written specifically for an identified audience.
- **Rationale**: The wording can be more direct and concise.

### Issue 3

- **Location**: Introduction paragraph
- **Current Text**: ">⚠️ Notice that you must respect these guidelines if you aim to publish your app at the VTEX App Store."
- **Recommendation**: Add a callout to the text, using the style guide's standard.
- **Applicable Guideline**: 9. Callouts - Callouts highlight information or notify about something.
- **Rationale**: Use the callout standard for better visual communication.

### Issue 4

- **Location**: Section: Scalability and performance
- **Current Text**: "Use the [VTEX IO](https://developers.vtex.com/docs/guides/vtex-io-documentation-what-is-vtex-io) infrastructure to build and deploy your extensions."
- **Recommendation**: "Use the VTEX IO infrastructure to build and deploy your extensions. For more information, see VTEX IO."
- **Applicable Guideline**: 5.2. Writing link text - When you write a complete sentence that refers to another topic, introduce the link with the phrase *For more information, see* or *For more information about..., see*.
- **Rationale**: Follow the style guide regarding links.

### Issue 5

- **Location**: Section: Using APIs efficiently
- **Current Text**:  "Efficiently utilizing APIs is paramount for optimal performance in your application. Whenever possible, leverage our pre-built [VTEX IO Clients](https://github.com/vtex/io-clients) to harness the following advantages:"
- **Recommendation**: "Efficiently utilize APIs for optimal performance in your application. Whenever possible, leverage our pre-built VTEX IO Clients. "
- **Applicable Guideline**: 5.2. Writing link text - When you write a complete sentence that refers to another topic, introduce the link with the phrase *For more information, see* or *For more information about..., see*.
- **Rationale**: For directness, the sentence "Efficiently utilizing APIs is paramount for optimal performance in your application" was re-written. To follow style guide's link standards, the section about VTEX IO Clients was also re-written.

### Issue 6

- **Location**: Section: Security Breaches - Step 1 and 2.
- **Current Text**: " [Open a ticket](https://help.vtex.com/en/tutorial/opening-tickets-to-vtex-support--16yOEqpO32UQYygSmMSSAM) requesting to remove your app from the VTEX App Store and avoid further installations of the unstable version."
- **Recommendation**: "Open a ticket requesting to remove your app from the VTEX App Store and avoid further installations of the unstable version. For more information, see Opening tickets to VTEX support."
- **Applicable Guideline**: 5.2. Writing link text - When you write a complete sentence that refers to another topic, introduce the link with the phrase *For more information, see* or *For more information about..., see*.
- **Rationale**: Follow the style guide regarding links.

### Issue 7

- **Location**: Section: Hardcoding VTEX appKey/appToken
- **Current Text**: "For more information, see [Connecting to VTEX Core Commerce APIs](https://developers.vtex.com/docs/guides/how-to-connect-with-vtex-core-commerce-apis-using-vtex-io#steps)."
- **Recommendation**: "For more information, see Connecting to VTEX Core Commerce APIs."
- **Applicable Guideline**: 5.2. Writing link text - When you write a complete sentence that refers to another topic, introduce the link with the phrase *For more information, see* or *For more information about..., see*.
- **Rationale**: Follow the style guide regarding links.

### Issue 8

- **Location**: Section: Declaring broad policies
- **Current Text**: "the `path` should not be configured as `*`."
- **Recommendation**: "do not configure the `path` as `*`."
- **Applicable Guideline**: N/A
- **Rationale**: Use the negative form, since it is an advise.

## Positive Aspects

- The document is well-organized and covers essential aspects of VTEX IO app development.
- It provides clear guidance on scalability, security, data privacy, and usability.
- The document emphasizes the importance of following best practices for publishing apps on the VTEX App Store.

## Recommendations for This Document

1. **Revise Headings**: Use more descriptive and actionable headings.
2. **Standardize Link Text**: Ensure all links follow the prescribed format (e.g., "For more information, see...").
3. **Apply Consistent Formatting**: Use bold text, code formatting, and callouts according to the style guide.
