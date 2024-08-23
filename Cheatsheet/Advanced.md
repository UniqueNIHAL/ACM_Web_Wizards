Here's an extended CSS cheat sheet with more tags and properties to help participants create interactive and visually appealing webpages:

---

# CSS Cheat Sheet for Interactive and Advanced Styling

## Basic Styling
- **Color:** `color: #hexcode;`
- **Background Color:** `background-color: #hexcode;`
- **Font Size:** `font-size: 16px;`
- **Font Family:** `font-family: Arial, sans-serif;`
- **Text Alignment:** `text-align: center;`
- **Line Height:** `line-height: 1.5;`

## Box Model
- **Margin:** `margin: 10px;`
- **Padding:** `padding: 10px;`
- **Border:** `border: 1px solid #hexcode;`
- **Border Radius:** `border-radius: 5px;`
- **Box Shadow:** `box-shadow: 2px 2px 5px rgba(0,0,0,0.3);`

## Layout
- **Display:** 
  - `display: block;`
  - `display: inline;`
  - `display: inline-block;`
  - `display: flex;`
  - `display: grid;`
  - `display: none;`
- **Flexbox:**
  - `justify-content: center;`
  - `align-items: center;`
  - `flex-direction: row;`
  - `flex-wrap: wrap;`
- **Grid:**
  - `grid-template-columns: 1fr 1fr 1fr;`
  - `grid-template-rows: 100px auto;`
  - `grid-area: header / main / footer / sidebar;`
  - `gap: 10px;`

## Positioning
- **Position:** 
  - `position: static;`
  - `position: relative;`
  - `position: absolute;`
  - `position: fixed;`
  - `position: sticky;`
- **Top, Right, Bottom, Left:**
  - `top: 10px;`
  - `right: 10px;`
  - `bottom: 10px;`
  - `left: 10px;`

## Text and Fonts
- **Font Weight:** `font-weight: bold;`
- **Font Style:** `font-style: italic;`
- **Text Transform:** 
  - `text-transform: uppercase;`
  - `text-transform: lowercase;`
  - `text-transform: capitalize;`
- **Text Decoration:** 
  - `text-decoration: underline;`
  - `text-decoration: line-through;`
  - `text-decoration: none;`
- **Letter Spacing:** `letter-spacing: 1px;`
- **Word Spacing:** `word-spacing: 2px;`

## Backgrounds
- **Background Image:** `background-image: url('image.jpg');`
- **Background Position:** `background-position: center;`
- **Background Size:** `background-size: cover;`
- **Background Repeat:** `background-repeat: no-repeat;`

## Responsive Design
- **Media Queries:**
  ```css
  @media (max-width: 600px) {
      .container {
          flex-direction: column;
      }
  }
  ```
- **Viewport Width/Height Units:** `vw`, `vh`

## Interactive Features
- **Transitions:**
  ```css
  transition: property duration timing-function delay;
  transition: all 0.3s ease;
  ```
- **Animations:**
  ```css
  @keyframes example {
      from { opacity: 0; }
      to { opacity: 1; }
  }
  .animated {
      animation: example 2s ease-in-out;
  }
  ```
- **Hover Effects:**
  ```css
  a:hover {
      color: red;
      text-decoration: underline;
  }
  button:hover {
      background-color: #ddd;
      cursor: pointer;
  }
  ```
- **Focus Effects:**
  ```css
  input:focus {
      border-color: blue;
      outline: none;
  }
  ```
- **Active Effects:**
  ```css
  button:active {
      background-color: #ccc;
  }
  ```

## Pseudo-Classes and Elements
- **Hover:** `:hover`
- **Active:** `:active`
- **Focus:** `:focus`
- **Visited:** `:visited`
- **First Child:** `:first-child`
- **Last Child:** `:last-child`
- **Nth Child:** `:nth-child(n)`
- **Before/After:**
  ```css
  .element::before {
      content: "Prefix";
  }
  .element::after {
      content: "Suffix";
  }
  ```

## CSS Variables
- **Define Variables:**
  ```css
  :root {
      --primary-color: #3498db;
      --secondary-color: #2ecc71;
  }
  ```
- **Use Variables:**
  ```css
  .element {
      color: var(--primary-color);
  }
  ```

## Flexbox and Grid Advanced
- **Flexbox:**
  - `flex-grow: 1;`
  - `flex-shrink: 1;`
  - `flex-basis: 0%;`
- **Grid:**
  - `grid-template-areas: "header header header" "main main sidebar" "footer footer footer";`
  - `grid-column: span 2;`

---

This cheat sheet covers a broad range of CSS properties and techniques, including advanced and interactive features to help participants create engaging and visually appealing webpages.
