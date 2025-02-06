# Frontend Interview Questions and Answers

## HTML & CSS

### 1. What is the use of doctype declaration?
The `<!DOCTYPE>` declaration defines the document type and version of HTML, ensuring proper rendering in web browsers.

### 2. What is the difference between `opacity: 0` and `visibility: hidden`?
- `opacity: 0` makes the element fully transparent but still occupies space in the layout.
- `visibility: hidden` hides the element while it still takes up space in the layout.

### 3. What is the difference between `display: flex` and `display: grid`?
- `display: flex` is a one-dimensional layout model for arranging items in a row or column.
- `display: grid` is a two-dimensional layout system allowing arrangement in both rows and columns.

### 4. What are semantic elements in HTML?
Semantic elements clearly define their meaning in HTML, such as `<header>`, `<article>`, `<section>`, `<footer>`, etc.

### 5. What is the difference between `id` and `class`?
- `id` is a unique identifier for an element, used only once per page.
- `class` is a reusable selector that can be applied to multiple elements.

### 6. What is the difference between block-level and inline elements?
- Block-level elements (`<div>`, `<p>`, `<h1>`, etc.) take up the full width of the parent container.
- Inline elements (`<span>`, `<a>`, `<b>`, etc.) only take up as much width as necessary.

### 7. What are the different CSS positioning methods?
- `static` (default), `relative`, `absolute`, `fixed`, and `sticky`.

### 8. What is `z-index` in CSS?
`z-index` controls the stacking order of elements. A higher value brings the element in front of others.

### 9. What is a box-modal in CSS?
The box model consists of margins, borders, padding, and the content area, defining how elements are spaced and sized.

### 10. What is the use of meta tags in the `<head>` section?
Meta tags provide metadata about a webpage, such as character set, viewport settings, SEO keywords, and descriptions.

### 11. How do we optimize a webpage?
- Minify CSS and JavaScript, use lazy loading, optimize images, leverage caching, and reduce HTTP requests.

---

## JavaScript

### 1. What is the difference between `let`, `var`, and `const`?
- `var` is function-scoped and can be redeclared.
- `let` is block-scoped and cannot be redeclared.
- `const` is block-scoped and cannot be reassigned.

### 2. What is the difference between `querySelector` and `querySelectorAll`?
- `querySelector` returns the first matching element.
- `querySelectorAll` returns a NodeList of all matching elements.

### 3. What are JavaScript data types?
- Primitive types: `string`, `number`, `boolean`, `null`, `undefined`, `symbol`, `bigint`.
- Non-primitive types: `object`, `array`, `function`.

### 4. How can we convert a string to a number in JavaScript?
Using `parseInt()`, `parseFloat()`, `Number()`, or the unary `+` operator.

### 5. What is the difference between `==` and `===`?
- `==` checks for value equality with type coercion.
- `===` checks for both value and type equality.

### 6. What is the difference between `null` and `undefined`?
- `null` is an assigned value representing "no value".
- `undefined` means a variable has been declared but not assigned a value.

### 7. What does `console.log(typeof null)` return?
It returns `"object"`, which is a known JavaScript bug.

### 8. What does `console.log(typeof (2 < 12 < 4))` return?
It returns `"boolean"` because `(2 < 12)` evaluates to `true`, and then `true < 4` becomes `1 < 4`, which is `true`.

---

## React JS

### 1. How many types of components are there in React?
Functional components and Class components.

### 2. What is the difference between state and props in React?
- `state` is local and mutable data managed inside a component.
- `props` are read-only properties passed from a parent component.

### 3. What is the Virtual DOM?
The Virtual DOM is a lightweight copy of the real DOM that React uses to optimize rendering and updates efficiently.

### 4. What are React Hooks?
Hooks are functions that let you use state and lifecycle features in functional components. Examples include `useState`, `useEffect`, and `useContext`.

### 5. What are the lifecycle methods in React?
- **Mounting:** `constructor()`, `componentDidMount()`.
- **Updating:** `componentDidUpdate()`.
- **Unmounting:** `componentWillUnmount()`.
