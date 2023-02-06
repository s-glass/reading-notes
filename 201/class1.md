# 201 class 1 notes

**Why this Matters**: This information matters because it's a review of the basic building blocks for beginning developers, including how browsers and web pages function, and the basics of HTML, CSS, and JavaScript.

## Getting Started

Sources [https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web)

1. Compose a short poem describing how HTTP sends data between computers.

> HTTP is the protocol,
  The language between browser and server.
  Allows for messages to and fro,
  Getting copies of web pages (with fervor?).

2. Describe how HTML, CSS, and JS files are “parsed” in the browser.

The HTML file is parsed first by the browser, allowing it to recognize HTML element references to CSS stylesheets and JS scripts. The browser sends requests to the server for any CSS or JS files from <link> and <script> elements and then parses the CSS and JS. 

To see the visual representation of the page, the browser first generates an in-memory DOM tree from parsed HTML and  CCSOM structure from parsed CSS. It then applies the styles from the CSSOM tree and compiles and executes the parsed JavaScript.

3. How can you find images to add to a Website?

One option is to go to [Google Images](www.google.com/images), click on the Tools button, and filter by Usage Rights --> Creative Commons License.

4. How do you create a String vs a Number in JavaScript?

To signify that the value in a sequence of text is a string, you must enclose it in single or double quote marks, whereas numbers don't have quotes around them.  

5. What is a Variable and why are they important in JavaScript?

Variables are containers that store values. They're declared with the *let* keyword followed by the name given to the variable. They're important because you can't make anything happen in JS without having a Variable to be defined and told what to do, how to relate, etc.

## Intro to HTML

1. What is an HTML attribute?

Attributes contain extra info about a given element that won't appear in the content.

2. Describe the Anatomy of an HTMl element.

An element contains an opening tag, the content, and the closing tag. 

The opening tag is the name of the element wrapped in <> bracket. It marks where the element begins.

The content is the text an element contains between tags.

The closing tag is the same as the opening tag, but it includes a / before the element name. It makrs where the element ends.


3. What is the Difference between <article> and <section> element tags?

<article> represents a self-contained composition in a document, page, application, or site, intended to be independently distributable or reusable. For example, a newspaper article, blog entry, interactive widget or any other independent item of content.

<section> represents a generic, standalone section of a document; It doesn't have a more specific semantic element to represent it. They should almost always have a heading.

4. What Elements does a “typical” website include?

A "typical" website might include the following elements:

-header: <header>.
-navigation bar: <nav>.
-main content: <main> (with various content subsections represented by <article>, <section>, and <div> elements).
-sidebar: <aside>; often placed inside <main>.
-footer: <footer>.

5. How does metadata influence Search Engine Optimization?

The metadata can influence SEO because the descriptions and keywords used relating to the content of your page has the potential to make your page appear higher (or lower) in relevant search engine searches.

6. How is the <meta> HTML tag used when specifying metadata?

It can be used to specify the document's character encoding using **<meta> charset="utf-8:**, for example.

Or it can include **name** and **content** attributes to specify the type of metadata element/type of information and to specify the actual meta content. 

Example from [https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML)

<meta name="author" content="Chris Mills" />
<meta
  name="description"
  content="The MDN Web Docs Learning Area aims to provide
complete beginners to the Web with all they need to know to get
started with developing web sites and applications." />


## Miscellaneous

### How To Design A Website

1. What is the first step to designing a Website?

To define what you want to accomplish with it.

2. What is the most important question to answer when designing a Website?

"What exactly do I want to accomplish?"

### Semantics

1. Why should you use an <h1> element over a <span> element to display a top level heading?

Because <h1> means "a top level heading on your page," and <span> is an inline non-semantic element used mostly when you don't want to add specific meaning or you can't think of a better semantic text element to wrap your content.

2. What are the benefits of using semantic tags in our HTML?

[This source](https://developer.mozilla.org/en-US/docs/Glossary/Semantics) lists the following as some of the benefits of using semantic markup in HTML:

-Search engines will consider its contents as important keywords to influence the page's search rankings (see SEO.)
-Screen readers can use it as a signpost to help visually impaired users navigate a page.
-Finding blocks of meaningful code is significantly easier than searching through endless divs with or without semantic or namespaced classes.
-Suggests to the developer the type of data that will be populated.
-Semantic naming mirrors proper custom element/component naming.

### What is JavaScript?

1. Describe 2 things that require JavaScript in the Browser?

Animating images
Dynamically updating content
Multimedia control

2. How can you add JavaScript to an HTML document?

Using the <script> element. You can create a script.js file in the same directory as your HTML file, or add JavaScript inline - inside of your HTML. 

## Things I Want To Know More About:
Nothing at the moment!