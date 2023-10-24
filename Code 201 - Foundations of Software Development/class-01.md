## Getting Started

> Compose a short poem describing how HTTP sends data between computers.

HTTP, a web's connector sleek,
Sends data fast with every click.
Client and server, they converse,
Through cyberspace, data traverses.

source: ChatGpt 

### Describe how HTML, CSS, and JS files are “parsed” in the browser.

* HTML Parsing: HTML defines the webpage's structure. The browser parses it into a structured tree called the DOM.

CSS Parsing: CSS styles the HTML elements. The browser reads and applies these styles to the DOM, creating the CSSOM.

JavaScript Parsing: JavaScript adds interactivity. It's either parsed and executed while parsing HTML (synchronously) or after the HTML is parsed (asynchronously or deferred). It can modify the DOM and CSSOM.

source: ChatGPT/My own words

### How can you find images to add to a Website?

* You can search for images on google. When it comes to copy right infringment, you can use a license filter by navigating to the "Tools" menu and selecting "Usage rights", then you can choose "Creative Common licenses".

### How do you create a String vs a Number in JavaScript?

* Creating a String:
To create a string, you can enclose text within single or double quotation marks. For example:

var myString = "This is a string";

* Creating a Number:
To create a number, you can use numeric literals. Numbers can be integers or floating-point values. For example:

var myNumber = 42; // An integer
var myFloat = 3.14; // A floating-point number

### What is a Variable and why are they important in JavaScript?

* A variable in JavaScript is like a labeled container for storing and managing data. They are essential for working with and manipulating information in your code, improving code readability and flexibility.

>Introduction to HTML

### What is an HTML attribute?

An HTML attribute is an additional piece of information or instruction attached to an HTML element. It is composed of a name and a value, and it is used to specify properties, relationships, styling, and other characteristics for that element. Attributes are defined within the opening tag of an HTML element and are crucial for customizing how web page elements behave and appear. Example, DO NOT INCLUDE SLASHES BEHIND THE FIRST "a" :
' <a // href="https://www.example.com">Visit Example</a>'

### Describe the Anatomy of an HTMl element.

* Opening Tag with Attributes:

The opening tag is enclosed in angle brackets and contains the element's name.
It marks the start of where the element's effects begin.
Attributes, if present, provide additional information about the element.
Enclosed Text Content:

In this instance, the content enclosed is text or any material you want to display.
Closing Tag:

This tag marks where the element's impact or influence ends, in this case, it signifies the conclusion of the paragraph.

### What is the Difference between <article> and <section> element tags?

The article element is like a container for content that's like a complete story on its own. It could be a blog post, a comment, or a news article. You can take it and use it independently, like sharing it on another website.

The section element is a more general container. You use it when there isn't a better option available. It's like a section or a chapter in a book. It's part of a bigger topic, and it usually has a heading to explain what's inside.

### What Elements does a “typical” website include?

<'!DOCTYPE html>: This is a must. It tells the browser to use the latest rules for displaying the web page.

<'html></'html>: Think of this as the main container for everything on the page. It's like the root of a tree.

<'head></'head>: The head is like a box for stuff that's not shown directly on the page. It holds things like keywords for search engines, styles to make the page look nice, and instructions for the characters used in the text.

<'meta charset="utf-8">: This part deals with characters in different languages. Setting it to UTF-8 helps the page handle text from most languages.

<'title></'title>: The title goes in the browser tab and is what you see when you bookmark a page.

<'body></'body>: The body is where all the good stuff goes – text, pictures, videos, games, and more. It's what people see on the web page.

### How does metadata influence Search Engine Optimization?

It improves how your pages appear in search results, and that's important for SEO. It helps you get noticed and clicked on more often.

### How is the <'meta'> HTML tag used when specifying metadata?

Many <'meta'> elements include name and content attributes:

The name specifies the type of meta element it is; what type of information it contains.
The content specifies the actual meta content.

### How to dessign a website?

What is the first step to designing a Website?

What exactly do I want to accomplish?
How will a website help me reach my goals?
What needs to be done, and in what order, to reach my goals?

What is the most important question to answer when designing a Website?

What are you tryihg to accomplish?

source: How to start to design a website 

### Semantics

Why should you use an <h1> element over a <span> element to display a top level heading?

the h1 element is a semantic element, which gives the text it wraps around the role(or meaning) of a "top level heading on your page."
Using a span element can be used to render it to look like a top level heading, but since it has no semantic value, it will not get any extra benefits

source: semantics

What are the benefits of using semantic tags in our HTML?

Search engines will consider its contents as important keywords to influence the page's search rankings (see SEO)
Screen readers can use it as a signpost to help visually impaired users navigate a page
Finding blocks of meaningful code is significantly easier than searching through endless divs with or without semantic or namespaced classes
Suggests to the developer the type of data that will be populated
Semantic naming mirrors proper custom element/component naming

source: sematics

### What is JavaScript?

Describe 2 things that require JavaScript in the Browser?

Form Check: JavaScript checks if you've filled out forms correctly on websites. For example, it can make sure your email is in the right format and that you've entered a good password.

Quick Updates: JavaScript makes web pages change without reloading. It's like how social media updates or chat messages appear instantly. JavaScript helps with those quick changes.

source: Google


How can you add JavaScript to an HTML document?

nline: Inside an HTML element, you can use the <script> tag and write your JavaScript directly. For example:

html
Copy code
<script>
  alert("Hello, World!");
</script>
External File: You can also put your JavaScript in a separate file with a .js extension. Then, use the <script> tag with the src attribute to link to that file:

html
Copy code
<script src="myscript.js"></script>
Remember to place your JavaScript inside the <script> tags, whether it's inline or in an external file.

source: ChatGPT