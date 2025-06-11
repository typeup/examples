# TypeUp Cheat Sheet

## Quick Reference

### Basic Formatting
```
_emphasis_           Italicize text
%inline code%        Inline code
$x^2$               Inline math
[url text]          Link
```

### Headers
```
# Level 1
## Level 2
### Level 3
```

### Lists
```
- Unordered
- List
  - Nested
    1. Ordered
    1. Sub-list

Term
: Definition 1
: Definition 2
```

### Blocks
Code:
```
%% python
def hello():
    print("Hello")
%%
Caption here
```

Math:
```
$$E = mc^2$$
Caption here
```

### Media
```
!figure path/to/image.png
Caption here

!video url/to/video.mp4
Caption here
```

### Tables
```
| Left   | Center | Right |
|--------|:------:|------:|
| Col 1  | Col 2  | Col 3 |
Caption here
```

### Document Structure
```
===    Start new chapter
---    Start new section
!import filename    Import document
```

### Comments
```
// Single line comment

/* Multi-line
   comment */
```

## Common Patterns

### Document Template
```
template = http://typeup.cogneco.com/templates/document
class = document
title = Title
date = YYYY-MM-DD
author = Name

# Introduction
Content here...
```

### Complex Table Example
```
| Feature    | Syntax     | Notes          |
|------------|:----------:|---------------:|
| Bold       | Not used   | Use emphasis   |
| Links      | `[]()`     | Both supported |
| Math       | `$x^2$`    | LaTeX style    |
Caption explaining the features
```

### Math Examples
```
Inline: $x^2 + y^2 = z^2$

Block:
$$
\sum_{i=1}^{n} i = \frac{n(n+1)}{2}
$$
```

### Nested List with Paragraph
```
- Main item
    - Sub item
        With additional
        paragraph text
    - Another sub
        1. Ordered
        2. Sub-items
```

### Definition List with Multiple Definitions
```
Term 1
: Primary definition
: Secondary definition
: Tertiary definition

Term 2
: Single definition
```

### Chapter with Sections
```
===
# Chapter Title
Introduction text

---
## Section 1
Content

---
## Section 2
More content
```

## Tips & Best Practices

1. Always leave blank lines before and after blocks
2. Indent nested lists with spaces or tabs consistently
3. Use semantic headers (don't skip levels)
4. Include captions for better document structure
5. Keep lines at a reasonable length (80-100 chars)
6. Use comments sparingly and meaningfully
7. Validate output in target formats
