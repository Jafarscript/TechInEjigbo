# **Week 2: Learning HTML**

HTML (HyperText Markup Language) is the standard language used to create web pages. It provides the structure of a webpage by using elements (tags) that define the content. This week, we will focus on understanding the basic structure of an HTML document, common HTML tags, and the importance of semantic HTML.

---

## **1. Understanding the Anatomy of an HTML Document**
An HTML document follows a specific structure that ensures proper rendering by web browsers. The main parts of an HTML document are:

### **a) `<!DOCTYPE html>` (Document Type Declaration)**
The `<!DOCTYPE html>` declaration tells the browser that the document follows HTML5 standards. It must be the first line of the HTML file.

### **b) `<html>` (Root Element)**
The `<html>` tag wraps the entire HTML document. It contains two main sections: `<head>` and `<body>`.

### **c) `<head>` (Metadata Section)**
The `<head>` section contains metadata (information about the document) and links to external resources. It does not display content on the webpage but includes elements like:
- `<title>` – Sets the webpage title (visible on the browser tab).
- `<meta>` – Provides metadata such as character encoding (`charset`), viewport settings for responsiveness, and descriptions for search engines.
- `<link>` – Links external resources like CSS stylesheets.
- `<script>` – Includes JavaScript files.

Example:
```html
<head>
    <title>My First Webpage</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
</head>
```

### **d) `<body>` (Content Section)**
The `<body>` section contains the visible content of the webpage. This is where we place text, images, links, tables, and other elements.

Example:
```html
<body>
    <h1>Welcome to My Webpage</h1>
    <p>This is a simple paragraph of text.</p>
</body>
```

---

## **2. Common HTML Tags**
HTML tags define the content and structure of a webpage. Below are some commonly used tags:

### **a) Headings (`<h1>` to `<h6>`)**
Headings define the structure of content. `<h1>` is the largest and `<h6>` is the smallest.

Example:
```html
<h1>Main Heading</h1>
<h2>Subheading</h2>
<h3>Smaller Subheading</h3>
```

### **b) Paragraphs (`<p>`)**
Used for blocks of text.

Example:
```html
<p>This is a paragraph of text.</p>
```

### **c) Links (`<a>`)**
Used to create hyperlinks.

Example:
```html
<a href="https://www.example.com">Visit Example</a>
```

### **d) Images (`<img>`)**
Displays images. The `src` attribute specifies the image URL, and `alt` provides alternative text for accessibility.

Example:
```html
<img src="image.jpg" alt="A beautiful landscape">
```

### **e) Lists**
- **Ordered List (`<ol>`)** – Displays numbered items.
- **Unordered List (`<ul>`)** – Displays bulleted items.

Example:
```html
<ul>
    <li>Item One</li>
    <li>Item Two</li>
</ul>

<ol>
    <li>First Step</li>
    <li>Second Step</li>
</ol>
```

### **f) Tables (`<table>`)**
Used to display data in a structured format.

Example:
```html
<table border="1">
    <tr>
        <th>Name</th>
        <th>Age</th>
    </tr>
    <tr>
        <td>John</td>
        <td>25</td>
    </tr>
</table>
```

---

## **3. Semantic HTML**
Semantic HTML improves readability and accessibility by using meaningful tags that describe the content. Instead of using generic `<div>` or `<span>`, semantic elements provide context.

### **Common Semantic Tags:**
- `<header>` – Represents the top section of a webpage (e.g., logo, navigation).
- `<footer>` – Contains footer information (e.g., copyright, links).
- `<section>` – Defines sections within a page.
- `<article>` – Represents standalone content (e.g., a blog post).
- `<nav>` – Defines a navigation menu.
- `<aside>` – Represents side content (e.g., a sidebar).

### **Example of Semantic HTML:**
```html
<header>
    <h1>My Website</h1>
    <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
    </nav>
</header>

<section>
    <h2>About Me</h2>
    <p>I am learning HTML.</p>
</section>

<article>
    <h2>Latest Blog Post</h2>
    <p>This is my latest blog post.</p>
</article>

<footer>
    <p>&copy; 2025 My Website</p>
</footer>
```

---

## **Conclusion**
Understanding the structure of an HTML document, using common tags effectively, and adopting semantic HTML practices are essential steps in learning web development. Semantic HTML not only makes code easier to read but also improves SEO and accessibility.

This week, practice by creating a simple webpage using the concepts covered. Experiment with different tags, create lists and tables, and try using semantic elements to structure your content.
