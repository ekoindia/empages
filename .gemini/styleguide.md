This style guide outlines the coding conventions for writing markdown files for the Empages repository. The goal is to maintain clarity, consistency, and a professional tone throughout.

# General Guidelines
- Use Markdown for formatting.
- Use a clear, concise, and conversational tone.
- Be logical and direct.
- Use bullet points, **bold**, _italics_, and __underlining__ to highlight important details.
- Ensure correct spelling and grammar throughout the document.
- Ensure proper case. Eg, abbreviations should be in uppercase (e.g., `DMT`, `AEPS`), while product names should be in title case (e.g., `Airtel DMT`, `AadhaarPay`).
- Ensure all proper nouns are capitalized.
- Ensure consistency of terms, phrases, and formatting across all markdown files.
- Use H2 (`##`) and H3 (`###`) headings for sections and sub-sections respectively.

# Tools
- Use https://bitdowntoc.derlin.ch/ for checking proper indentation of headings and sub-headings.

## General Filename Conventions
- Markdown filename must be in kebab-case: lower-case with hyphens as word separators. Eg: `airtel-dmt.md`.
- No spaces, underscores, or special characters in the filename.


## Markdown Formatting

### Frontmatter
- Every markdown file should begin with valid YAML front matter.
```markdown
---
layout: help
title: "Your Post Title"
---
```

### Title Format
- Add the title only in the `title` field of the front matter.
- Use sentence case.
- Abbreviations should be in uppercase (e.g., `DMT`, `AEPS`), while product names should be in title case (e.g., `Airtel DMT`, `AadhaarPay`).
- Ensure proper spacing around punctuation, for example, use a space after commas and periods.
- Avoid duplication in the body.
- Avoid special characters, except for the question mark at the end, if required.
- Title format: `How to do <product-name> transactions?` or `How to register for <product-name>?`
- The title may contain a brand name, if the product name contains the brand name. Eg: `How to do Airtel DMT transactions?` or `How to register for Airtel DMT?`

### Headings Format
- Use H2 (`##`) for main sections.
- Use H3 (`###`) for subsections.
- If required, use H4 (`####`) for sub-subsections.
- Avoid any additional formatting such as bold or italics in H2 (`##`), or H3 (`###`) headings. Eg: `## This is a heading` instead of `## **This is a heading**`.

### Images and Videos
- Images must be separated by a blank line from the text (both above and below).
- Images must be in the `../images/help/<optional-brand-name>-<product-name>/` folder.
- Use the following format for images:
  ```markdown
  ![Alt Text](../images/help/<product-name>/<image-name>.png)
  ```
- Use descriptive alt text for images to improve accessibility.

### Bullet Points
- Use bullet points for lists to improve readability.
- Keep bullet points succinct and directly related to the content.


# Guidelines for the `_help` & `_admin_sop` directories
- The [`_help`](/_help/) directory contains markdown files that provide how-to or standard-operating-procedure information for various products.
- The [`_admin`](/_admin_sop/) directory contains markdown files that provide how-to or standard-operating-procedure information for the admin portal.
- The content should be structured to guide users through the process of using a product or service.
- Title format: `How to do <product-name> transactions?` or `How to register for <product-name>?`
  - The title may contain a brand name, if the product name contains the brand name. Eg: `How to do Airtel DMT transactions?` or `How to register for Airtel DMT?`
- Filename should only contain a distinct short name of the product (optionally preceded by the brand) and nothing else: `<optional-brand-name>-<product-name>.md`. Eg: `airtel-dmt.md`.
  - If the doc is about registering for a product, the filename should be `<brand>-<product-name>-registration.md`, where the brand name is optional. Eg: `airtel-dmt-registration-registration.md`.
  - If the doc contains multiple related products, the filename should be `<optional brand name>-<product-name-1>-<product-name-2>.md`. Eg: `aeps-aadhaarpay.md`.

## Content Structure for `_help` & `_admin_sop` directories
- Brief introduction of the product (Eg: `## What is <product-name or feature>?`).
- (Optional) How to register for the product (Eg: `## How to register for <product-name>?`).
- Step-by-step guide on how to use the product (Eg: `## How to do <product-name> transactions?` or `## How to use <feature-name>?`).
- If the service returns multiple fields in the response, use Markdown tables to display the fields and their descriptions. For example:
  ```markdown
  | Field Name | Description |
  |------------|-------------|
  | DOB     | Date of Birth of the user |
  | Name   | Full name of the user |
  ```
- Key-points or FAQs at the end of the document (Eg: `## Key Points` or `## FAQs`).
- (Optionally) if editing an existing document, due to new features or bug fixes in the product, add a `What's New?` section at the end of the document. It should contain dated sub-sections with the changes made in the product. Start each entry with `New: ` or `Fix: `, followed by the change description. For example:
  ```
  ## What's New?
  - **2025-04-01**
  	- New: Added support for new biometric devices.
  	- Fix: Resolved issue with fingerprint scanning.
  ```

# AI Code-Review Assistant Guidelines

## Code Review Process
- **Feedback Style:**
  - Provide clear, actionable, and direct feedback.
  - Use bullet points to list issues or improvement suggestions.
- **Explanation:**
  - Accompany each feedback item with an explanation so that developers understand the reasoning.
- **Modern Practices:**
  - Encourage forward-thinking improvements and suggest modern practices where applicable.

## Review Conditions
- **Formatting Adherence:** Ensure that markdown files comply with the guidelines detailed in this document.
- **Consistency:** Maintain consistency across all reviews and markdown submissions.
- **Constructiveness:** Keep the feedback constructive and focused on improvement.
- **Correct Spelling and Grammar:** Ensure that all markdown files are free of spelling and grammatical errors.
- **Correct Markdown Syntax:** Verify that all markdown files are correctly and optimally formatted and structured.

## Best Practices
- **Clarity:** Write in a straightforward manner. Complex feedback should be broken down into simpler, manageable parts.
- **Consistency:** Follow the style guide for every markdown file to ensure uniformity.
- **Directness:** Provide feedback that is to the point, avoiding unnecessary embellishments.
