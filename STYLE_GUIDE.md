# TypeUp Style Guide

This document outlines the standard formatting rules for TypeUp documents.

## Document Structure

### Required Metadata
Every document must begin with the following metadata in this order:
```
template = <template_url>
class = <document_class>
title = <document_title>
date = <YYYY-MM-DD>
author = <author_name>
```

### Headers
- Use ATX-style headers (`#`, `##`, `###`, etc.)
- Maximum header depth is 6 levels
- Leave one blank line before headers (except at file start)
- Leave one blank line after headers

### Paragraphs
- Separate paragraphs with exactly one blank line
- Use soft wrapping for long lines
- Do not indent paragraphs

## Text Formatting

### Emphasis
- Use `_single underscores_` for emphasis (italics)
- Do not use asterisks for emphasis

### Code
- Inline code: Use `%percentage signs%`
- Code blocks:
  ```
  %% language
  code here
  %%
  ```
- Always specify language for syntax highlighting when possible

### Math
- Inline math: Use `$single dollars$`
- Math blocks:
  ```
  $$formula$$
  caption (optional)
  ```

### Links
- Use `[text](url)` format
- For bare URLs, use `[url]`

## Lists

### Unordered Lists
- Start each item with a single hyphen (`-`)
- One space after the hyphen
- Indent nested items with one tab

### Ordered Lists
- Start with `1.` for all items (auto-numbering)
- One space after the period
- Indent nested items with one tab

### Definition Lists
```
Term
: Definition
: Additional definition
```

## Media

### Images
```
!figure url
caption (optional)
```

### Videos
```
!video url
caption (optional)
```

## Tables
```
| Header 1 | Header 2 |
|----------|----------|
| Cell 1   | Cell 2   |
caption (optional)
```

- Use at least 3 dashes in separator row
- Align columns using colons in separator row:
  - Left (default): `|-------|`
  - Center: `|:-----:|`
  - Right: `|-------:|`
- Maintain consistent column widths for readability

## Document Sections

### Chapters
- Separate chapters with `===`
- Start each chapter with a level 1 header

### Sections
- Separate sections with `---`
- Use appropriate header levels within sections

### Imports
- Use relative paths: `!import filename`
- Place imports on their own line
- Add blank lines before and after imports

## Comments
- Single line: `// comment`
- Multi-line:
  ```
  /* Multi-line
     comment */
  ```
- Use comments sparingly and only when necessary

## Best Practices
1. Maintain consistent indentation
2. Use semantic markup
3. Provide descriptive captions for figures, tables, and math blocks
4. Follow heading hierarchy (don't skip levels)
5. Keep lines at a reasonable length (recommended 80-100 characters)
6. Use blank lines judiciously
7. Validate document output in target formats
