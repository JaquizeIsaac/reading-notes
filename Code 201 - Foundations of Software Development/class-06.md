### Problem Domain, Objects, and the DOM

## How would you describe an object to a non-technical friend you grew up with?

> Think of an object in JavaScript like a digital box. This box can hold different pieces of information, like the color, model, and year of a car or the name, health, strength, and armor of a video game character. So, it's a way to organize and store data in the computer world, just like we used to organize things with our building blocks as kids.

## What are some advantages to creating object literals?

> Organization: Objects help keep related data together for easier management.
Encapsulation: They bundle data and functions, promoting clean code structure.
Flexibility: Objects can hold various data types and be reused for efficiency.

## How do objects differ from arrays?

> Objects: Objects use named keys to store data, making them ideal for associating unique labels with specific values. They are best suited for handling non-sequential, structured data.

Arrays: Arrays store data in a numerical, ordered sequence and are ideal for handling lists or collections of similar items, like numbers or strings, where the order matters.

## Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.

> you should use bracket notation when the property name in an object has special characters, spaces, or when the property name is stored in a variable. For example, if a property is named "first name" or if you have a variable propertyName with the value "last name," you'd use bracket notation like this:

const person = {
  "first name": "John",
  "last name": "Doe",
};

const propertyName = "last name";
const lastName = person[propertyName];


## Evaluate the code below. What does the term this refer to and what is the advantage to using this?

> this refers to the dog object itself, which is like a way of talking about the dog from inside the dog's description.

The advantage is that it lets you easily use the dog's own information (like its name and age) within the humanAge function without having to repeat the word "dog" each time. This makes the code more convenient and flexible if you have different dogs with similar descriptions.


## Introduction To The DOM

## What is the DOM?

> DOM, or Document Object Model, is a programming interface for web documents. It represents the structure of a web page, such as HTML or XML, as a tree of objects. This tree structure allows developers to access, manipulate, and modify the content and elements of a web page using programming languages like JavaScript. In essence, the DOM serves as a bridge between web content and scripts, enabling dynamic and interactive web pages.

## Briefly describe the relationship between the DOM and JavaScript.

> JavaScript is a scripting language commonly used in web development to interact with and manipulate the DOM. JavaScript can access and modify the content, structure, and style of a web page by using the DOM as a bridge. This interaction allows developers to create dynamic, interactive web applications and update web content in response to user actions or events.

source: ChatGPT/ Introduction to the DOM/ JS Object Basics