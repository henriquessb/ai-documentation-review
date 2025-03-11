# Technical Documentation Review: i-am-getting-errors-with-my-service-configuration-app.md

## Summary

This document addresses a common issue encountered when developing service configuration apps on the VTEX IO platform. It clearly explains the cause of the errors and provides two practical solutions. However, the document can be improved by adhering more closely to the E&D Style Guide, particularly in formatting, link text, and heading structure.

## Detailed Findings

### Issue 1

- **Location**: Title
- **Current Text**: "I am getting errors with my service configuration app"
- **Recommendation**: "Troubleshoot Errors in Service Configuration App" or "Resolve Service Configuration App Errors"
- **Applicable Guideline**: 4. Headings and titles - Make the learning objective of the article clear, preferably with only one verb. Your heading or title must be descriptive, as short as possible, and generally convey only one main action.
- **Rationale**: The current title is written in the first person and is not as clear or professional as the suggested alternatives. More descriptive titles help users quickly understand the purpose of the article.

### Issue 2

- **Location**: First paragraph
- **Current Text**: "If you are [developing a configuration app](https://developers.vtex.com/docs/guides/vtex-io-documentation-developing-service-configuration-apps), you may be getting errors because the service your app is configuring is installed or linked to a different workspace."
- **Recommendation**: "If you are developing a configuration app, you may encounter errors if the service your app is configuring is installed or linked to a different workspace. For more information, see Developing service configuration apps."
- **Applicable Guideline**: 5.2. Writing link text - When you write a complete sentence that refers to another topic, introduce the link with the phrase *For more information, see* or *For more information about..., see*.
- **Rationale**: The current sentence includes the phrase "you may be getting errors" which is too informal. The link is not introduced using the recommended format from the style guide.

### Issue 3

- **Location**: Solution Section
- **Current Text**: "Below, we outline solutions for addressing errors with your service configuration app:"
- **Recommendation**: "The following solutions outline how to address errors with your service configuration app:"
- **Applicable Guideline**: 1. Pragmatics -> 1.1 Discourse - Technical writing is direct, informative, clear, and concise language written specifically for an identified audience.
- **Rationale**: The current sentence includes the personal pronoun "we" which is too informal.

### Issue 4

- **Location**: Unnumbered steps in sections "Avoiding errors when installing or linking your configuration app" and "Publishing your configuration app in an alternative workspace"
- **Current Text**: The steps are numbered in the markdown, but they are not rendering as a numbered list.
- **Recommendation**: Review markdown syntax and use numbered list format.
- **Applicable Guideline**: 6. Procedures - Procedures must follow a numbered list format.
- **Rationale**: To ensure the steps appear in a numbered list for clarity.

### Issue 5

- **Location**: Throughout the document - links to VTEX IO CLI commands, like "link" and "install"
- **Current Text**: Linked text only with the command name
- **Recommendation**: For more information on how to link an app, see Linking an app.
- **Applicable Guideline**: 5.2. Writing link text - When you write a complete sentence that refers to another topic, introduce the link with the phrase *For more information, see* or *For more information about..., see*.
- **Rationale**: Use the recommended link style in the style guide.

### Issue 6

- **Location**: Steps with CLI code
- **Current Text**:

    ```
    vtex use workspace {desiredWorkspace}
    ```

- **Recommendation**:

    ```
    vtex use workspace {desiredWorkspace}
    ```

    Replace `{desiredWorkspace}` with the workspace you want to work in.
- **Applicable Guideline**: 8.1 Placeholders
- **Rationale**: To keep consistency on documentation and to make it easier for the user to understand that that value is a placeholder.

## Positive Aspects

- The document clearly identifies a specific problem and provides actionable solutions.
- The steps are generally easy to follow.

## Recommendations for This Document

1. **Revise Headings**: Use more descriptive and actionable headings.
2. **Standardize Link Text**: Ensure all links follow the prescribed format (e.g., "For more information, see...").
3. **Apply Consistent Formatting**: Use code formatting and callouts according to the style guide.
