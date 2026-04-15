# Semantic HTML 
## What is Semantic HTML?
Semantic HTML means using HTML elements based on their meaning (purpose), not just appearance.

Example:
- Use `<strong>` for important text (meaning)
- Not `<div>` just to make it bold (style)
  
---

## Why Semantic HTML is Important
### 1. Accessibility
- Helps screen readers understand content
- Improves navigation for visually impaired users

### 2. SEO (Search Engine Optimization)
- Search engines understand content better
- Improves ranking (e.g., `<h1>` is important)
    
### 3. Readability
- Code is easier to understand
- Developers quickly know purpose of elements

### 4. Maintainability
- Easier to update and manage code
    
### 5. Future-Proof
- Works better with future browsers and technologies

---

## Common Semantic Elements
- `<header>` → Top section (logo, title, nav)
- `<nav>` → Navigation links
- `<main>` → Main content (only one per page)
- `<article>` → Independent content (blog post, news)
- `<section>` → Group of related content
- `<aside>` → Sidebar / extra content
- `<footer>` → Bottom section (copyright, info)
- `<figure>` → Media container
- `<figcaption>` → Caption for media
- `<time>` → Date or time
- `<mark>` → Highlighted text
    
---

## Semantic vs Non-Semantic

|Semantic|Non-Semantic|Meaning|
|---|---|---|
|`<header>`|`<div>`|Page intro|
|`<nav>`|`<div>`|Navigation|
|`<main>`|`<div>`|Main content|
|`<article>`|`<div>`|Independent content|
|`<aside>`|`<div>`|Sidebar|
|`<footer>`|`<div>`|Footer|
|`<strong>`|`<b>`|Important text|
|`<em>`|`<i>`|Emphasis|
|`<section>`|`<div>`|Content grouping|

---

## Key Rule
- Avoid overusing `<div>` and `<span>`
- Use semantic elements whenever possible
    

---

## Simple Structure Example

```html
<header>
  <h1>My Blog</h1>
  <nav>Menu</nav>
</header>

<main>
  <article>
    <h2>Title</h2>
    <p>Content...</p>
  </article>

  <aside>Sidebar</aside>
</main>

<footer>
  <p>Copyright</p>
</footer>
```

