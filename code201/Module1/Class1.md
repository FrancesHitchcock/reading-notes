# Module 1 Class 1 Reading Notes

## Getting Started

### How HTTP sends data between computers

The HyperText Transfer Protocol defines the language with which the client (device or browser) and server communicate. The server first requests a piece of information (for example a HTML file) from the server. To do this it must first find the relevant server. So it uses the web address typed into the browser to look up the website's IP address in the Domain Name System, which is like an address book of servers. The IP address is where all the data for the website is stored.

When the server has received the request it sends a response, which is usually the information requested by the client. This first piece of information might contain references to other pieces of information. These could be in the form of a code file such as a CSS file, or an asset such as an image. So the client makes further requests to the server for the these piece of information, and so on until it has everything it needs to paint a representation of the web page to the screen.

### How HTML, CSS and JS are parsed in the browser

1. The browser parses the HTML file, searching for `<link>` (CSS) and `<script>` (JavaScript) elements.
2. When it encounters one of these elements it sends a request back to the server for the relevant files.
3. When the server has responded with the CSS and/or JS files it then parses the CSS and JavaScript.
4. The browser then constructs a DOM tree from the parsed HTML and CSSOM tree from the parsed CSS.
5. The browser compiles and executes the parsed JavaScript.
6. The web page is painted to the screen on construction of the DOM and CSSOM trees, and the execution of the JavaScript enables interaction with the page.

### Finding images to add to a website

1. Go to Google Images.
2. Click on the tools button, then on the usage rights option, and select _Creative Commons Licences_ to avoid violating copyright.
3. Select a suitable image.
4. To use the image in your work either save a copy of the image in the site directory or else copy its web address so you can link to it directly.

### How to create a string vs a number in JavaScript

A string value should be surrounded by single or double quotes (or backticks), whereas a number value is not surrounded by quotes.

### Variables and their importance in JavaScript

A variable can be visualised as a container that 'stores' or points to a value. Variables are important because we can change their values to make websites dynamic.

## Introduction to HTML

### HTML attributes

An HTML attribute is something that contains extra information about the element that won't appear in the content.

### The anatomy of a HTML element

An HTML element typically contains an opening tag, a closing tag and the content to be rendered in between. Some elements are self-closing which means they don't have a separate closing tag. Any attributes are declared inside the opening tag.

### The difference between `<article>` and `<section>` element tags

`<article>` and `<section>` are both semantic elements. A section encloses a part of the page that constitutes a single piece of funcionality or topic. However, an article encloses a block of content that makes sense on its own without the main page. Don't put it in a section.

### Elements in a typical website

A typical website includes:

- `<header>`
- `<nav>`
- `<main>`, often enclosing `<article>` `<section>` `<div>`
- `<aside>` (often inside `<main>`)
- `<footer>`

### Metadata in SEO

A `<meta>` tag should be included for a description. This should contain keywords to make the site appear higher up the search list.

### Specifying metadata using the HTML tag

The `<meta>` tag includes name and content attributes.

## Miscellaneous

### The first step to designing a website

First you should use project ideation, including determining what you want to accomplish, how the website will help you achieve your goals and what needs to be done and in what order to achieve those goals.

### The most important question to answer when designing a site

You must identify what you want to accomplish.

### Why an `<h1>` element should be used over a `<span>` element to display a top level heading

The `<h1>` element is a semantic element, whereas the `<span>` is not.

### The benefits of using semantic tags

Semantic elements improve SEO, enable screen readers to interpret the page structure and help the developer to make sense of the code.

### Two things that require JavaScript in the browser

- Store useful values inside variables to create dynamic websites
- Run code in response to events that occur on the page

### Adding JavaScript to an HTML document

1. internally inside `<script>` tags at the end of the body
2. externally using a link to a separate .js file like this: `<script src="script.js"></script>`

## Things I want to know more about

SEO optimisation
