# InterviewPrep

# HTML & HTML DOM

## Introduction
HTML (HyperText Markup Language) is the standard language used to create and structure web pages. It defines the elements and layout of a webpage using *tags*.

### Key Points about HTML
- *Markup Language*: Structures content using tags like &lt;h1&gt;, &lt;p&gt; , &lt;a&gt;, etc.
- *Not a Programming Language*: HTML does not have logic (like loops or conditions).
- *Works with CSS & JavaScript*: CSS styles the page, and JavaScript makes it interactive.

### Basic Structure of an HTML Page:
```html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Page</title>
</head>
<body>
    <h1>Hello, World!</h1>
    <p>This is a simple HTML page.</p>
</body>
</html>

```
---

# HTML DOM (Document Object Model)

## 1️⃣ What is the HTML DOM?
The *HTML DOM (Document Object Model)* is a programming interface that represents the structure of an HTML document as a tree of objects. It allows JavaScript to dynamically access and manipulate HTML elements.

### JavaScript Interactions with DOM:
- Modify content (innerHTML, textContent)
- Change styles (style)
- Handle events (onclick, addEventListener)
- Add or remove elements (createElement, removeChild)

## 2️⃣ DOM Tree Structure
Consider this HTML:
```html
<!DOCTYPE html>
<html>
<head>
    <title>DOM Example</title>
</head>
<body>
    <h1 id="heading">Hello, DOM!</h1>
    <p class="text">This is a paragraph.</p>
</body>
</html>
```

### The *DOM tree* representation:
```js

Document
 ├── html
 │   ├── head
 │   │   └── title
 │   ├── body
 │       ├── h1 (id="heading")
 │       ├── p (class="text")
 
```

This hierarchical structure enables JavaScript to interact with and manipulate web pages dynamically.