
---

## HTML & CSS Cheat Sheet

### HTML Cheat Sheet

#### Basic Structure
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document Title</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Header Content</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <main>
        <section id="home">
            <h2>Home Section</h2>
            <p>Welcome to the homepage!</p>
        </section>
        <section id="about">
            <h2>About Section</h2>
            <p>About us section content.</p>
        </section>
        <section id="contact">
            <h2>Contact Section</h2>
            <form action="#" method="post">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <input type="submit" value="Submit">
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Your Name. All rights reserved.</p>
    </footer>
</body>
</html>
```

#### Common Tags
- **Headings:** `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>`
- **Paragraph:** `<p>`
- **Links:** `<a href="URL">Link Text</a>`
- **Images:** `<img src="URL" alt="description">`
- **Lists:** `<ul>`, `<ol>`, `<li>`
- **Tables:** `<table>`, `<tr>`, `<td>`, `<th>`
- **Forms:** `<form>`, `<input>`, `<textarea>`, `<button>`, `<select>`, `<option>`

#### Accessibility
- **Alt Text for Images:** `<img src="URL" alt="description">`
- **Labels for Forms:** `<label for="id">Label</label>`
- **Semantic HTML:** Use tags like `<header>`, `<footer>`, `<nav>`, `<article>`, `<section>`

### CSS Cheat Sheet

#### Basic Syntax
```css
selector {
    property: value;
}
```

#### Selectors
- **Element Selector:** `p { color: red; }`
- **Class Selector:** `.class-name { color: blue; }`
- **ID Selector:** `#id-name { color: green; }`
- **Attribute Selector:** `[type="text"] { border: 1px solid black; }`

#### Box Model
- **Content:** The actual content of the element.
- **Padding:** Space between content and border.
- **Border:** Surrounds the padding (optional).
- **Margin:** Space outside the border.

```css
.element {
    padding: 10px;
    border: 1px solid black;
    margin: 20px;
}
```

#### Layout
- **Display:**
  - `block`: Takes up the full width available.
  - `inline`: Takes up only as much width as needed.
  - `inline-block`: Combination of block and inline.
  - `none`: Hides the element.

```css
div {
    display: block;
}
```

- **Positioning:**
  - `static`: Default positioning.
  - `relative`: Position relative to its normal position.
  - `absolute`: Position relative to the nearest positioned ancestor.
  - `fixed`: Position relative to the viewport.
  - `sticky`: Based on the user's scroll position.

```css
.relative-element {
    position: relative;
    top: 10px;
}
```

#### Responsive Design
- **Media Queries:**
```css
@media screen and (max-width: 600px) {
    body {
        background-color: lightblue;
    }
}
```

- **Flexbox:**
```css
.container {
    display: flex;
    justify-content: center; /* Align items horizontally */
    align-items: center; /* Align items vertically */
}
```

- **Grid:**
```css
.grid-container {
    display: grid;
    grid-template-columns: repeat(3, 1fr); /* 3 equal columns */
}
```

#### Fonts & Colors
- **Font Size:**
```css
p {
    font-size: 16px;
}
```

- **Font Family:**
```css
body {
    font-family: Arial, sans-serif;
}
```

- **Text Color:**
```css
h1 {
    color: #333;
}
```

- **Background Color:**
```css
body {
    background-color: #f0f0f0;
}
```

#### Animations & Transitions
- **Transition:**
```css
.element {
    transition: all 0.3s ease;
}
```

- **Animation:**
```css
@keyframes example {
    from { opacity: 0; }
    to { opacity: 1; }
}

.element {
    animation: example 2s ease-in-out;
}
```

### Tips
- **Indentation:** Use consistent indentation (e.g., 2 or 4 spaces).
- **Comments:** Use comments to explain your code.
```css
/* This is a comment */
```
```html
<!-- This is a comment -->
```
- **Validation:** Use validators to ensure your HTML and CSS are error-free.

This cheat sheet should help you and participants during the event, covering essential HTML and CSS concepts, syntax, and best practices.
