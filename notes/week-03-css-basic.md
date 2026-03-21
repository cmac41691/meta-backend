# Week 03 – CSS Basics

## Date

2026-03-20

## Topics Covered

* Selecting and styling
* CSS selectors
* Text and color
* Box model
* Block vs inline
* Alignment basics

## Key Notes

CSS is used to style and layout HTML elements.

Selectors target HTML elements to apply styles.

Example:

* `h1 { color: blue; }`

The box model defines spacing:

* content → padding → border → margin

Block elements take full width.

Inline elements take only necessary space.

CSS controls visual presentation, not structure.

HTML → structure
CSS → styling


# Week 03 – CSS Basics

---

## 📅 2026-03-20

### 📚 Topics Covered
- Selecting and styling
- CSS selectors
- Text and color
- Box model

### 🔄 System Flow
Client → Request → Server → HTML Response  
Browser → DOM → CSS Applied → UI Rendered  

### 🧠 Key Notes
...

### 🎯 Why This Matters
...

### 🧠 Reflection

Completed the styling assignment after debugging failing tests.

Initial issues:
- Incorrect selector targeting (`h2 span` vs `h2 > span`)
- Minor syntax error with font-size

Key lesson:
CSS requires precise selectors and correct syntax. Small mistakes can cause rules to fail silently.

Improved understanding of:
- class vs id vs element selectors
- nested selectors
- layout behavior (block elements + margin auto for centering)

### 🧠 Key Notes

- Block elements take full width and stack vertically
- Inline elements take only necessary space and flow horizontally

- `text-align: center` centers inline content inside a block container

- `display: block` allows elements to behave like block elements
- `margin-left: auto` + `margin-right: auto` centers block elements

- Class selectors (`.class`) are reusable across multiple elements
- ID selectors (`#id`) target a single unique element

- Nested selectors (`h2 > span`) target specific child elements
- Selector precision matters — incorrect selectors may not apply styles

- Small syntax errors (missing `;`) can break CSS rules silently