HTML Forms

Why are forms so important in web development?
Web forms are one of the main points of interaction between a user and a website or application. Forms allow users to enter data, which is generally sent to a web server for processing and storage (see Sending form data), or used on the client-side to immediately update the interface in some way (for example, add another item to a list, or show or hide a UI feature).
When designing a form, what are some key things to keep in mind when it comes to user experience?
Designing a quick mockup will help you to define the right set of data you want to ask your user to enter. From a user experience (UX) point of view, it's important to remember that the bigger your form, the more you risk frustrating people and losing users. Keep it simple and stay focused: ask only for the data you absolutely need.

List 5 form elements and explain their importance
Text Input ( <input type="text"> ):
Importance: Text input fields are essential for collecting short text or alphanumeric data such as names, email addresses, search queries, and more. They are versatile and widely used in web forms.
Textarea ( <textarea></textarea> ):
Importance: Textareas are used to collect longer text input from users, such as comments, feedback, or messages. They allow users to enter multi-line text, which is not suitable for single-line text inputs.
Dropdown Select ( <select><option></option></select> ):
Importance: Dropdown select elements provide users with a list of options from which they can choose a single selection. They are useful for gathering user preferences, selecting categories, or choosing from a predefined set of choices.
Radio Buttons ( <input type="radio"> ):
Importance: Radio buttons allow users to select a single option from a list of mutually exclusive choices. They are used when you want users to make a single selection from a set of options, such as gender or subscription type.
Checkboxes ( <input type="checkbox"> ):
Importance: Checkboxes enable users to select multiple options from a list of choices. They are used when you want users to make multiple selections, such as selecting items from a shopping cart or choosing multiple interests or preferences.
Learn JS
sources: Introduction To Events, chatGPT

How would you describe events to a non-technical friend?
Events in JavaScript are like a bell at a party. When someone rings the bell (an event), it tells your friend (a JavaScript function) to prepare snacks (perform an action). Similarly, in web development, events like button clicks signal JavaScript functions to do things, making web pages interactive and responsive to user actions.

When using the addEventListener() method, what 2 arguments will you need to provide?
The type of the event you want to listen for, such as "click," "mouseover," "keydown," etc. This is a string representing the event type.
The function that should be executed when the event occurs, also known as the event handler or callback function. This function will be triggered in response to the specified event.
In this example, the first argument is the event type ("click"), and the second argument is the function to be executed when a click event is detected.

element.addEventListener("click", function () {
  // Your code to handle the click event goes here
});
Describe the event object. Why is the target within the event object useful?
The event object in JavaScript is an object that contains information about an event that has occurred, such as a user's interaction with a web page. It is automatically created by the browser and passed as an argument to event handler functions when an event occurs.

One of the properties of the event object is event.target. The event.target property is a reference to the DOM (Document Object Model) element on which the event was originally triggered. This property is particularly useful because it allows you to pinpoint the specific element that triggered the event, even if the event has propagated through multiple nested elements.

Here's why event.target is useful:

Precise Targeting: It allows you to identify the exact element that the user interacted with. For example, if you have multiple buttons on a page, you can determine which button was clicked by accessing event.target.

Delegation: It facilitates event delegation, which is a technique to handle events on a parent element for multiple child elements. You can check event.target to determine which child element was the actual source of the event, making your code more efficient and less repetitive.

Dynamic Elements: When you have dynamic content that is added or removed from the page, event.target ensures that your event handling code remains functional for new elements, as it always references the current target element.

Here's an example of using event.target to get the clicked element in a click event handler:

document.addEventListener("click", function (event) {
  // event.target refers to the element that was clicked
  if (event.target.tagName === "BUTTON") {
    // Do something specific when a button is clicked
    event.target.style.backgroundColor = "red";
  }
});
In this example, we check if the event.target is a BUTTON element, and if so, we change its background color. This allows you to respond specifically to button clicks within the entire document.

What is the difference between event bubbling and event capturing?
In JavaScript, event propagation defines the order in which events are processed when they occur on nested HTML elements within the DOM (Document Object Model). There are two main phases of event propagation: event bubbling and event capturing.

Event Bubbling:

In the event bubbling phase, the innermost element's event is handled first, and then the event propagates outward to the outer elements, all the way up to the document or window.
This is the default behavior in most browsers, and it makes intuitive sense because it mimics the way events "bubble up" from the source to their container elements.
Event listeners attached to the innermost element will be called before those attached to its ancestors.
<div id="parent">
  <button id="child">Click me</button>
</div>;

document.getElementById("child").addEventListener("click", function () {
  console.log("Child element clicked");
});

document.getElementById("parent").addEventListener("click", function () {
  console.log("Parent element clicked");
});
When you click the button, the output will be:

Child element clicked
Parent element clicked
Event Capturing:

In the event capturing phase, the outermost element's event is handled first, and then the event propagates inward, from the document or window down to the target element.
Event capturing is less commonly used but can be helpful in situations where you want to intercept events before they reach the target element.
document.getElementById("child").addEventListener(
  "click",
  function () {
    console.log("Child element clicked");
  },
  true
);

document.getElementById("parent").addEventListener(
  "click",
  function () {
    console.log("Parent element clicked");
  },
  true
);
In this case, by setting the third argument to true in the addEventListener method, you enable event capturing. When you click the button, the output will be:

Parent element clicked
Child element clicked

sources: Your first Web Form. How To Structure A Web Form., chatGPT