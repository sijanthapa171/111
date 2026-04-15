# HTML Elements (Short Notes)
## What is an HTML Element?
An HTML element has:
- **Opening tag** → `<p>`
- **Content** → Text or other elements
- **Closing tag** → `</p>`

Example:
```html
<p>This is a paragraph</p>
```
---

## Common Elements
### 1. Text Elements
- `<h1> - <h6>` → Headings
- `<p>` → Paragraph
- `<span>` → Inline styling/grouping
- `<br>` → Line break

---

### 2. Grouping
- `<div>` → Container
- Semantic tags → `<header>`, `<nav>`, `<main>`, `<article>`, `<footer>`

---

### 3. Lists
- `<ul>` → Unordered list
- `<ol>` → Ordered list
- `<li>` → List item

---

### 4. Links & Images
- `<a>` → Link (`href`)
- `<img>` → Image (`src`, `alt`)

---

### 5. Forms
- `<form>` → Form container
- `<input>` → Input field
- `<textarea>` → Multi-line input
- `<button>` → Button
- `<select>` & `<option>` → Dropdown

---

### 6. Tables
- `<table>` → Table
- `<tr>` → Row
- `<th>` → Header
- `<td>` → Data

---

### 7. Embedded Content
- `<iframe>` → Embed external content
    
---

## Important Concepts
### Nesting
Elements can be placed inside others:
```html
<div>
  <p>Hello <strong>World</strong></p>
</div>
```

### Block vs Inline
- **Block** → Full width, new line (`<div>`, `<p>`)
- **Inline** → Only needed width (`<span>`, `<a>`)

### Empty Elements
No closing tag:
- `<img>`
- `<br>`
