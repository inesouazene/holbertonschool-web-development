# [Advanced HTML](https://github.com/MathieuMorel62/holbertonschool-web-development/tree/main/html_advanced)

![Advanced HTML Structure Project](https://blog-media.byjusfutureschool.com/bfs-blog/2021/11/12170200/HTML-for-Kids-Article-Page.png)

## Description

This project is a deep dive into implementing advanced HTML structures based solely on provided mockups. The focus will be on using pure HTML to construct web pages, emphasizing the importance of semantics and accessibility without the aid of CSS or inline styles. This educational journey will cover all HTML tags, their utility, and how to arrange them to faithfully transform a mockup into a functional web page.

#### `General`
By the end of this project, you should be able to [explain to anyone](https://fs.blog/feynman-learning-technique/), **without the help of Google:**

<details>
<summary>What is HTML</summary>
<br>

- **HTML (HyperText Markup Language)** is the standard markup language used for creating and structuring web pages and applications.

</details>

<details>
<summary>How to create an HTML page from a wireframe</summary>
<br>

- **Creating an HTML page from a wireframe:** Start by analyzing the mockup to identify the different components. Then use HTML tags to reproduce the structure and content, placing elements logically and semantically in your code.

</details>

<details>
<summary>What is a markup language</summary>
<br>

- **A markup language** is a coding system that uses tags to structure text in a document. Besides structuring, it also allows for adding semantics and formatting instructions.

</details>

<details>
<summary>What is the DOM</summary>
<br>

- **The DOM (Document Object Model)** is a programming interface for HTML and XML documents. It represents the page as a tree structure, allowing for the content, structure, and style to be modified via scripts.

</details>

<details>
<summary>What is an element / tag</summary>
<br>

- **An element or tag** in HTML is a basic unit of webpage structure. Elements are defined by tags, like `<p>` for paragraphs, which can also contain attributes.

</details>

<details>
<summary>What is an attribute</summary>
<br>

- **An attribute** provides additional information about an HTML element, such as the reference URL for links in the `href` attribute of the `<a>` tag.

</details>

<details>
<summary>What is the purpose of each HTML tag</summary>
<br>

- **The purpose of each HTML tag** is to define and structure the web page content for the browser. For instance, `<header>` defines the heading of a section or page, `<footer>` for the footer, `<img>` to embed images, and so on.

</details>

----------------------

# [Advanced CSS](https://github.com/MathieuMorel62/holbertonschool-web-development/tree/main/css_advanced)

![img](https://cssversicherung.scene7.com/is/image/csskrankenversicherung/css-logo-schutzzone-large:image-21-9?wid=1600&fit=constrain,0&resMode=sharp2&noCache=1667821703763)

## Description

"Advanced CSS" is an in-depth exploration of advanced CSS techniques for creating sophisticated, responsive web interfaces. This project trains developers to master layout, animation, and the modularity of CSS, focusing on browser compatibility and performance.

#### `General`
By the end of this project, you should be able to demonstrate a thorough understanding of CSS without external assistance:

<details>
<summary>What is CSS</summary>
<br>

- `CSS (Cascading Style Sheets)`: CSS is a stylesheet language used to describe the presentation of a document written in HTML or XML. It controls how the web page's content is displayed, including colors, layouts, and fonts. It separates content from design, allowing you to change the look and feel of a site without altering the underlying HTML.

</details>

<details>
<summary>How to add style to an element</summary>
<br>

- `Adding Style to an Element`: You can add style to an HTML element in several ways:
  - **Inline Styling**: Directly in an element's opening tag using the `style` attribute. E.g., `<p style="color: blue;">This is blue text.</p>`
  - **Internal Styling**: In the `<head>` section of your HTML document within a `<style>` tag. E.g.,
 
    ```html
    <style>
      p { color: red; }
    </style>
    ```
    
  - **External CSS**: By linking to an external CSS file using the `<link>` tag in the `<head>` section. E.g., `<link rel="stylesheet" type="text/css" href="styles.css">`

</details>

<details>
<summary>What is a class</summary>
<br>

- `Class in CSS`: A class is a group of styling rules identified by a class selector. It allows you to apply the same style to multiple elements without repeating the style definitions. A class is defined in CSS with a period (`.`) followed by the class name and applied to HTML elements using the `class` attribute. E.g.,
  
  ```css
  .example { color: green; }
  
  And in HTML: <div class="example">This is a green text.</div>
  ```

</details>

<details>
<summary>What is a selector</summary>
<br>
  
- `Selector in CSS`: Selectors are patterns used to select the elements you want to style. Types of selectors include element selectors, class selectors, ID selectors, and more complex ones like attribute selectors and pseudo-selectors.

</details>

<details>
<summary>How to compute CSS Specificity Value</summary>
<br>
  
- `CSS Specificity Value`: It is a system that determines which styles are applied to an element when there is a conflict. Specificity is calculated based on different types of selectors:
  
  - **ID selectors** have a specificity of 100.
  - **Class, pseudo-class, and attribute selectors** have a specificity of 10.
  - **Element and pseudo-element selectors** have a specificity of 1.
  - **Inline styles** have a specificity of 1000.
  - **!important** overrides any other declaration.
    
To calculate, count each type of selector in your rule and then write them in a form (ID, Class, Element).

</details>

<details>
<summary>What are Box properties in CSS</summary>
<br>
  
- `Box Properties in CSS`: These properties define the layout of a 'box', which is the fundamental layout component in CSS. They include:
  
  - **Margin**: Controls the space outside of the border.
  - **Border**: The line that goes around the padding and content.
  - **Padding**: The space between the border and the actual content.
  - **Width and Height**: Specifies the width and height of the content area.
    
</details>

<details>
<summary>How does the browser load a webpage</summary>
<br>
  
`Loading a Webpage`: When a browser loads a webpage, it follows these steps:
  1. **DNS Lookup**: Translates the website URL into an IP address.
  2. **HTTP Request**: The browser sends a request to the server at the found IP.
  3. **Server Response**: The server sends back the requested HTML file.
  4. **Browser Rendering**: The browser parses the HTML and applies CSS styles. It also executes JavaScript and loads additional resources like images.
  5. **Display**: The processed content is displayed on the screen.

</details>