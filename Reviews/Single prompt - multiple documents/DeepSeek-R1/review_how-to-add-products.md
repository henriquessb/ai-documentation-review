# Technical Documentation Review: how-to-add-products.md  

## Summary  

The document provides clear, concise instructions for adding products but has formatting inconsistencies in UI elements, callouts, and image accessibility. Key issues include improper bold formatting, non-descriptive alt text, and missing callout labels.  

---  

## Detailed Findings  

### Issue 1: Underscores Instead of Bold for UI Elements  

- **Location**: "Before creating a product, you must have created the **Brand** and **Category**..."  
- **Current Text**: Double underscores (`__Brand__`, `__Category__`).  
- **Recommendation**: Replace with bold formatting: **Brand** and **Category**.  
- **Applicable Guideline**: *Section 1.1. Bold*: "Format computer interfaces and key concepts in bold within text."  
- **Rationale**: Underscores are not compliant with VTEX’s emphasis rules for UI elements or concepts.  

### Issue 2: Non-Descriptive Image Alt Text  

- **Location**: `![Catalogo - Cadastrar produto EN.gif?h=250](//images.ctfassets.net/...)`  
- **Current Text**: File name with parameters (`?h=250`).  
- **Recommendation**: Use descriptive text: `![Product registration process in the VTEX Admin](//images...)`.  
- **Applicable Guideline**: *Section 8.3. Icons*: "Include a label describing images to improve accessibility."  
- **Rationale**: File names lack context and hinder accessibility compliance.  

### Issue 3: Missing Callout Label and Emoji  

- **Location**: API section alert  
- **Current Text**:  

  ```  
  <div class="alert alert-info">  
    If your product does not appear...  
  </div>  
  ```  

- **Recommendation**: Add label and emoji:  

  ```  
  ℹ️ **Information:** If your product does not appear...  
  ```  

- **Applicable Guideline**: *Section 9.1. Callout in flowing text*: "Use ℹ️ **Information**, ⚠️ **Caution**, or ⛔ **Danger** labels."  
- **Rationale**: Generic alerts lack visual consistency and fail to convey intent.  

### Issue 4: Punctuation Inside Link Tag  

- **Location**: Callout link: "...<a href="...">website?</a> to understand..."  
- **Current Text**: Question mark inside link tag.  
- **Recommendation**: Move punctuation outside: "...<a href="...">website</a>? to understand..."  
- **Applicable Guideline**: *Section 5.3. Punctuation with links*: "Put punctuation outside of the link tags."  
- **Rationale**: Improper punctuation placement disrupts readability and screen reader flow.  

### Issue 5: Title-Case Headings  

- **Location**: Headings "VTEX Admin," "Spreadsheet," "API."  
- **Current Text**: Title case (e.g., "VTEX Admin").  
- **Recommendation**: Use sentence case: "VTEX admin," "Spreadsheet," "API."  
- **Applicable Guideline**: *Section 4. Headings and titles*: "Use sentence case for titles and headings."  
- **Rationale**: Title case conflicts with VTEX’s sentence-case requirement.  

---  

## Positive Aspects  

1. **Procedural Clarity**: Steps under "VTEX Admin" are sequential, use code formatting for buttons (`Add Product`, `Save`), and include actionable commands.  
2. **Link Ownership**: Internal links (e.g., `help.vtex.com`) correctly specify VTEX ownership.  
3. **Code Formatting**: API endpoint (`Create Product`) is properly linked and formatted.  

---  

## Recommendations for This Document  

1. **Revise Emphasis**: Replace underscores with bold formatting for UI elements and concepts.  
2. **Standardize Callouts**: Add ℹ️/⚠️ labels and emojis to all alerts.  
3. **Improve Accessibility**: Update image alt texts to describe content, not file names.  

---  

**Final Note**: The document effectively guides users through product creation but requires adjustments to visual formatting and accessibility elements for full Style Guide compliance.
