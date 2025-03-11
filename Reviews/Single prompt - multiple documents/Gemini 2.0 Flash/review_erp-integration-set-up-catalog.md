# Technical Documentation Review: erp-integration-set-up-catalog.md

## Summary

This document provides a detailed guide on setting up a catalog within VTEX for ERP integration. It covers the creation of departments, categories, subcategories, brands, and specifications. The document is well-structured and informative but can be improved by adhering more closely to the E&D Style Guide.

## Detailed Findings

### Issue 1

- **Location**: Title
- **Current Text**: "Set up catalog"
- **Recommendation**: "Configure Catalog for ERP Integration" or "Set Up Catalog Integration"
- **Applicable Guideline**: 4. Headings and titles - Make the learning objective of the article clear, preferably with only one verb. Your heading or title must be descriptive, as short as possible, and generally convey only one main action.
- **Rationale**: The current title is too generic. The recommended titles are more specific and indicate the context of ERP integration.

### Issue 2

- **Location**: First paragraph
- **Current Text**: "In this step, we give you an overview of how to prepare your catalog structure to receive all of your products."
- **Recommendation**: "This guide provides an overview of how to prepare your catalog structure for ERP integration."
- **Applicable Guideline**: 1. Pragmatics -> 1.1 Discourse - Technical writing is direct, informative, clear, and concise language written specifically for an identified audience.
- **Rationale**: This is more direct and informative. Avoid using personal pronouns like "we".

### Issue 3

- **Location**: First paragraph
- **Current Text**: "While this article provides the basic flow of integration, we recommend you check the implementation details provided on our [Catalog integration guide](https://developers.vtex.com/docs/guides/catalog-integration), as well as each **Learn more** section below."
- **Recommendation**: "While this article provides the basic flow of integration, for implementation details, see the Catalog integration guide. "
- **Applicable Guideline**: 5.2. Writing link text - When you write a complete sentence that refers to another topic, introduce the link with the phrase *For more information, see* or *For more information about..., see*.
- **Rationale**: The current sentence uses "we recommend you check" which is an informal and not in line with technical writing style. The link is not introduced using the recommended format from the style guide. "Learn more" sections are no longer used in VTEX documentation.

### Issue 4

- **Location**: Section - Before you begin
- **Current Text**: "Before uploading your entire catalog to VTEX it is very important to think carefully about your desired catalog structure."
- **Recommendation**: "Before uploading your catalog to VTEX, it is important to carefully consider your catalog structure."
- **Applicable Guideline**: 3. Morphology -> 3.3 Adjectives - Avoid using subjective adjectives like "easy" or "simple".
- **Rationale**: Removing the subjective words to improve sentence clarity and precision.

### Issue 5

- **Location**: Section - Create Departments, Categories and Subcategories
- **Current Text**: "To create your Category Tree, you should use the [Create Category](https://developers.vtex.com/docs/api-reference/catalog-api#post-/api/catalog/pvt/category) endpoint in the Catalog API."
- **Recommendation**: "To create your Category Tree, use the Create Category endpoint in the Catalog API. "
- **Applicable Guideline**: 5.2. Writing link text - When you write a complete sentence that refers to another topic, introduce the link with the phrase *For more information, see* or *For more information about..., see*.
- **Rationale**: The recommendation is more direct and action-oriented, removing unnecessary phrasing.

### Issue 6

- **Location**: Code blocks, example: "Integration"
- **Current Text**: "Integration"
- **Recommendation**: "`Integration`"
- **Applicable Guideline**: 1.1 Bold - Whenever you mention computer interfaces in the middle of the text.
- **Rationale**: Terms related to code, placeholders or APIs must be enclosed in code format.

### Issue 7

- **Location**: "Create Brands" section
- **Current Text**: >⚠️ If your backend does not have brand information, you can perform the same process mentioned above for [category migration](https://developers.vtex.com/docs/guides/erp-integration-set-up-catalog#category-migration-from-erps), by creating an inactive mock brand, used exclusively for migration. The products' information can later be manually enriched.
- **Recommendation**: Add a callout using the standards from the style guide, and re-write to: "If your backend does not have brand information, you can create an inactive mock brand for migration purposes. Manually enrich the products' information later."
- **Applicable Guideline**: 9. Callouts
- **Rationale**: The "tips" must follow the callout template in the style guide.

### Issue 8

- **Location**: Wrapping up section
- **Current Text**: "After following the instructions in this step, you should have set up your catalog, including the category tree, brands and specifications needed to completely describe your products. This should enable you to upload all your products in the next step."
- **Recommendation**: "After following the instructions in this guide, you should have set up your catalog, including the category tree, brands, and specifications needed to describe your products completely. You can then upload your products."
- **Applicable Guideline**: 1. Pragmatics -> 1.1 Discourse - Technical writing is direct, informative, clear, and concise language written specifically for an identified audience.
- **Rationale**: To improve the clarity and conciseness of the final statement.

## Positive Aspects

- The document provides a comprehensive and detailed guide to setting up a catalog for ERP integration.
- It includes clear steps for creating categories, brands, and specifications.
- The document offers practical recommendations for handling category migration and enriching product information.

## Recommendations for This Document

1. **Revise Headings**: Use more descriptive and actionable headings.
2. **Standardize Link Text**: Ensure all links follow the prescribed format (e.g., "For more information, see...").
3. **Apply Consistent Formatting**: Use code formatting and callouts according to the style guide.
