# Introduction to React and Components

## Component-Based Architecture

* What is a “component”?

A component is a modular, portable, replaceable, and reusable set of well-defined functionality that encapsulates its implementation and exporting it as a higher-level interface.

A component is a software object, intended to interact with other components, encapsulating certain functionality or a set of functionalities. It has an obviously defined interface and conforms to a recommended behavior common to all components within an architecture.

A software component can be defined as a unit of composition with a contractually specified interface and explicit context dependencies only. That is, a software component can be deployed independently and is subject to composition by third parties.

* What are the characteristics of a component?

Reusability − Components are usually designed to be reused in different situations in different applications. However, some components may be designed for a specific task.

Replaceable − Components may be freely substituted with other similar components.

Not context specific − Components are designed to operate in different environments and contexts.

Extensible − A component can be extended from existing components to provide new behavior.

Encapsulated − A A component depicts the interfaces, which allow the caller to use its functionality, and do not expose details of the internal processes or any internal variables or state.

Independent − Components are designed to have minimal dependencies on other components.

* What are the advantages of using component-based architecture?

Reduced time in market and the development cost by reusing existing components.
Increased reliability with the reuse of the existing components.

source: Component-Based Architecture

## What is Props and How to Use it in React

* What is “props” short for?

“Props” is a special keyword in React, which stands for properties and is being used for passing data from one component to another.

* How are props used in React?

Firstly, define an attribute and its value(data)

Then pass it to child component(s) by using Props

Finally, render the Props Data

* What is the flow of props?

But the important part here is that data with props are being passed in a uni-directional flow. (one way from parent to child)

## Things I want to know more about