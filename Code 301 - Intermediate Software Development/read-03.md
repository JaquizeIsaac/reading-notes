# Passing Functions as Props

* The .map() method returns a new array with the results of calling a function for each element in the original array.

* If I want to loop through an array and display each value in JSX, how do I do that in React? -To loop through an array and display each value in JSX in React, you can use the .map() method to create an array of JSX elements and then return that array.
* Each list item needs a unique ____. -Each list item needs a unique key to help React identify and efficiently update the list when data changes.

* What is the purpose of a key? -The purpose of a key is to provide a unique identifier for each list item, allowing React to efficiently track and update the list when data changes.

## The Spread Operator

* What is the spread operator? 

The spread operator is a concise way to expand iterable objects, such as arrays and objects.

* List 4 things that the spread operator can do.

Combine arrays: Merge two or more arrays into a single array. Add items to arrays: Add new elements to an existing array. Spread objects: Create a new object with the properties of another object and any additional properties. Pass arguments: Expand an iterable object as arguments to a function.

* Give an example of using the spread operator to combine two arrays.

const arr1 = [1, 2, 3]; const arr2 = [4, 5, 6]; const combinedArr = [...arr1, ...arr2]; // [1, 2, 3, 4, 5, 6]

* Give an example of using the spread operator to add a new item to an array. 

const arr = [1, 2, 3]; const newArr = [...arr, 4]; // [1, 2, 3, 4]

* Give an example of using the spread operator to combine two objects into one. 

const obj1 = { a: 1, b: 2 }; const obj2 = { c: 3, d: 4 }; const combinedObj = { ...obj1, ...obj2 }; // { a: 1, b: 2, c: 3, d: 4 }

## Videos

* How to Pass Functions Between Components -The first step to pass functions between components is to define the function in the parent component

* In the video, what is the first step that the developer does to pass functions between components?

He defined two componets the first one being the Parent then the child then he clicked a Button to invoke a function on the child component. And then proceeded to do the inverse.

* In your own words, what does the handleClick function do? 

The handleClick function serves as an event handler that is activated upon clicking the button.

* How can you pass a method from a parent component into a child component?

To pass a method from a parent component into a child component, you can include it as a prop in the child component's JSX tag.

* How does the child component invoke a method that was passed to it from a parent component? 

The child component can invoke a method that was passed to it from a parent component by accessing the prop and calling it like a regular function.