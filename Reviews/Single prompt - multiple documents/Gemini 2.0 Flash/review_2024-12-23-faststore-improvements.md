# Technical Documentation Review: 2024-12-23-faststore-improvements.md

## Summary

The document provides a good overview of the FastStore performance improvements for mobile devices. It clearly outlines the changes, the reasons behind them, and the necessary steps to implement them. The writing is generally clear and concise, but there are some areas where it can be improved to align more closely with the E&D Style Guide.

## Detailed Findings

### Issue 1

- **Location**: Title
- **Current Text**: "FastStore: Performance improvements for mobile devices"
- **Recommendation**: "FastStore: Improve performance for mobile devices" or "Improve FastStore performance for mobile devices"
- **Applicable Guideline**: 4. Headings and titles - Your heading or title must be descriptive, as short as possible, and generally convey only one main action.
- **Rationale**: The suggested titles are more concise while still conveying the main action of the document.

### Issue 2

- **Location**: Excerpt
- **Current Text**: "Improved performance experience for FastStore stores."
- **Recommendation**: "Improve performance experience for FastStore stores."
- **Applicable Guideline**: 3.1 Sentence case - Use sentence case for titles, headings, lists, and table elements.
- **Rationale**: It is best practice to write the excerpt in present tense.

### Issue 3

- **Location**: Section - What has changed?
- **Current Text**: "What has changed?"
- **Recommendation**: "Describe performance improvements"
- **Applicable Guideline**: 4. Headings and titles - Make the learning objective of the article clear, preferably with only one verb.
- **Rationale**: The suggested title is more descriptive and aligns better with the purpose of the section, which is to describe the changes.

### Issue 4

- **Location**: List item under "What has changed?" - Lazy loading
- **Current Text**: "Lazy loading has been implemented for sections outside the viewport, such as CartSidebar and RegionModal, improving initial load times. This feature currently works only for native sections."
- **Recommendation**: "Lazy loading implemented for sections outside the viewport, such as `CartSidebar` and `RegionModal`, to improve initial load times. This feature currently works only for native sections."
- **Applicable Guideline**: 8.2 Button names - When referring to names for buttons in a list or numbered procedure or bulleted list, format the button name as code.
- **Rationale**: The terms CartSidebar and RegionModal refer to computer interfaces, thus they must be written using code formatting.

### Issue 5

- **Location**: List item under "What has changed?" - Optimizing website load times
- **Current Text**: "Preconnect and prefetch: Browser directives that establish early connections to external resources (fonts, images) and prioritize their fetching, resulting in faster loading times."
- **Recommendation**: "**Preconnect and prefetch:** browser directives that establish early connections to external resources (fonts, images) and prioritize their fetching, resulting in faster loading times."
- **Applicable Guideline**: 1.1 Bold - Whenever explaining concepts in bulleted lists. Be aware that in those situations, you only format bold the name or expression of the concept, nothing else in the explanation.
- **Rationale**: The concept name (Preconnect and prefetch) is the only part that should be bold.

### Issue 6

- **Location**: List item under "What has changed?" - Optimizing website load times
- **Current Text**: "Dynamic imports: Using next/dynamic to load components efficiently, reducing the impact on initial page load size."
- **Recommendation**: "**Dynamic imports:** Using `next/dynamic` to load components efficiently, reducing the impact on initial page load size."
- **Applicable Guideline**: 8.2 Button names - When referring to names for buttons in a list or numbered procedure or bulleted list, format the button name as code.
- **Rationale**: The term next/dynamic refers to a computer interface, thus it must be written using code formatting.

### Issue 7

- **Location**: Section - What needs to be done? Step 2
- **Current Text**: "Update your FastStore project to version `3.0.112` or later by running the following:"
- **Recommendation**: "Update your FastStore project to version `3.0.112` or later by running the following command:"
- **Applicable Guideline**: N/A - General writing clarity.
- **Rationale**: Using the word "command" provides more clarity to the reader, as they are not running the project, but running a command to update it.

### Issue 8

- **Location**: Throughout the document (e.g., "After updating your FastStore project version," "Why did we make this change?")
- **Current Text**: Using questions as section titles
- **Recommendation**: Rephrase questions into declarative statements or imperative phrases (e.g., "Update FastStore project version," "Reason for the change").
- **Applicable Guideline**: 4. Headings and titles - Preferably start with a verb in infinitive form or a noun. Verbs in the imperative should be used mainly in a sequence of steps.
- **Rationale**: Question format is less direct and actionable than a statement or command. Using imperative titles makes the document more task-oriented.

## Positive Aspects

- The document clearly explains the performance improvements made to FastStore.
- It provides specific details about the changes, including the technologies used (e.g., Preact, lazy loading).
- The steps to update the FastStore project are clearly outlined.
- The document effectively communicates the benefits of the performance improvements for mobile users.

## Recommendations for This Document

1. **Revise Headings to Be More Actionable**: Replace question-based headings with descriptive statements or imperative phrases to enhance clarity and directness.
2. **Consistently Format Code Elements**: Ensure that all references to code elements (e.g., libraries, functions, components) are formatted consistently using code formatting.
3. **Review Bulleted List Formatting**: Ensure bulleted lists adhere to the style guide, particularly concerning the use of bold text and punctuation.
