# Technical Documentation Review: how-to-add-products.md

## Summary

This document explains how to add products to a VTEX store using three different methods: VTEX Admin, spreadsheet, and API. The document is concise and provides a basic overview of each method. However, it needs significant revisions to align with the E&D Style Guide, particularly in formatting, link text, and terminology.

## Detailed Findings

### Issue 1

- **Location**: Title
- **Current Text**: "How to add products"
- **Recommendation**: "Add Products to VTEX Catalog" or "Learn How to Add Products"
- **Applicable Guideline**: 4. Headings and titles - Make the learning objective of the article clear, preferably with only one verb. Your heading or title must be descriptive, as short as possible, and generally convey only one main action.
- **Rationale**: The current title is too generic. The suggested titles are more specific and action-oriented.

### Issue 2

- **Location**: Second paragraph
- **Current Text**: "Before creating a product, you must have created the **Brand** and **Category** that correspond to it. Both need to be active in order for the product to be created."
- **Recommendation**: "Before creating a product, you must have created the **Brand** and **Category** that correspond to it. Ensure that both are active for the product to be created."
- **Applicable Guideline**: 1.1 Bold - Whenever you mention computer interfaces in the middle of the text.
- **Rationale**: Use bold formatting for computer interfaces as stated in the style guide. The term "Both need to be active in order for the product to be created" was re-written to improve readability.

### Issue 3

- **Location**: VTEX Admin, step 1 and 2
- **Current Text**: "Click on **Catalog**." and "Click on **All products** ."
- **Recommendation**: "Click on **Catalog**." and "Click on **All products**."
- **Applicable Guideline**: 1.1 Bold - Whenever you mention computer interfaces in the middle of the text.
- **Rationale**: Use bold formatting for computer interfaces as stated in the style guide.

### Issue 4

- **Location**: VTEX Admin, step 3 and 5
- **Current Text**: "Click on `Add Product`." and "Click on `Save` or `Save and add new SKU`, in case you want to add SKUs associated to that product."
- **Recommendation**: "Click `Add Product`." and "Click `Save` or `Save and add new SKU` if you want to add SKUs associated with that product."
- **Applicable Guideline**: 8.2 Button names - When referring to names for buttons in a list or numbered procedure or bulleted list, format the button name as code.
- **Rationale**: The button name must be written using code formatting. The sentence "in case you want to add SKUs associated to that product" was re-written to improve readability.

### Issue 5

- **Location**: VTEX Admin, step 4
- **Current Text**: "Fill out the product form fields. For more on what each field means, read our article on [product registration fields](https://help.vtex.com/en/tutorial/product-registration-fields--4dYXWIK3zyS8IceKkQseke)."
- **Recommendation**: "Fill out the product form fields. For more information, see the product registration fields article."
- **Applicable Guideline**: 5.2. Writing link text - When you write a complete sentence that refers to another topic, introduce the link with the phrase *For more information, see* or *For more information about..., see*.
- **Rationale**: This adheres to the prescribed format for introducing links to other topics.

### Issue 6

- **Location**: Spreadsheet section
- **Current Text**: "We recommend that you add products and SKUs together when using a spreadsheet. You can check out the steps on the [Adding SKU](https://help.vtex.com/en/tracks/catalog-101--5AF0XfnjfWeopIFBgs3LIQ/17PxekVPmVYI4c3OCQ0ddJ) article of this track."
- **Recommendation**: "We recommend that you add products and SKUs together when using a spreadsheet. For more information, see the Adding SKU article."
- **Applicable Guideline**: 5.2. Writing link text - When you write a complete sentence that refers to another topic, introduce the link with the phrase *For more information, see* or *For more information about..., see*.
- **Rationale**: This adheres to the prescribed format for introducing links to other topics.

### Issue 7

- **Location**: API section
- **Current Text**: "To add a new product via API use the [Create Product](https://developers.vtex.com/vtex-rest-api/reference/post-product) request."
- **Recommendation**: "To add a new product via API, use the Create Product request."
- **Applicable Guideline**: 5.2. Writing link text - When you write a complete sentence that refers to another topic, introduce the link with the phrase *For more information, see* or *For more information about..., see*.
- **Rationale**: This adheres to the prescribed format for introducing links to other topics.

### Issue 8

- **Location**: Alert box
- **Current Text**: Uses `<div>` tags with Bootstrap CSS classes
- **Recommendation**: Use the callout format described in the style guide, with appropriate icons and formatting.
- **Applicable Guideline**: 9. Callouts - This describes the proper format for callouts.
- **Rationale**: Consistent formatting of callouts improves readability and aligns with the style guide.

## Positive Aspects

- The document provides a clear and concise overview of how to add products using different methods.
- The steps for adding a product in the VTEX Admin are easy to follow.

## Recommendations for This Document

1. **Revise Headings**: Use more descriptive and actionable headings.
2. **Standardize Link Text**: Ensure all links follow the prescribed format (e.g., "For more information, see...").
3. **Apply Consistent Formatting**: Use bold text, code formatting, and callouts according to the style guide.
