### Object-Oriented Programming, HTML Tables

## Domain Modeling

> Explain why we need domain modeling.

Clarity and Understanding: It helps stakeholders, including developers, project managers, and clients, understand and visualize the problem domain or the real-world context in which the software will operate. This clarity is crucial for effective communication and shared understanding.

Problem Solving: Domain modeling allows you to break down complex real-world problems into smaller, manageable components. By representing these components and their relationships in a model, you can systematically address and solve the problem.

Design: Domain models serve as the foundation for designing the software system's structure and architecture. They help you define the structure of the software, including classes, data, and how different parts of the system interact.

Consistency: A well-defined domain model ensures consistency throughout the software development process. It acts as a reference point, helping developers maintain a uniform understanding of the domain and its rules.

Efficiency: It provides a roadmap for building the software, making the development process more efficient. Developers can refer to the domain model to understand what needs to be implemented and how it relates to other parts of the system.

Testing: Domain models help in designing tests and validation procedures to ensure that the software behaves as expected and accurately represents the problem domain.

## HMTL Table Basics 

## Why should tables not be used for page layouts?

> Using tables for web page layouts is not recommended because it makes web pages harder to understand and can cause problems for people who use screen readers or different devices. It's also less flexible and can slow down page loading. Instead, web designers use CSS, which is better for creating modern, accessible, and responsive web layouts.

## List and describe 3 different semantic HTML elements used in an HTML <table>.

> The <caption> element is used to provide a title or caption for the entire table. It should be placed immediately after the opening <table> tag. The caption summarizes the purpose or content of the table.
<thead>, <tbody>, and <tfoot>:
Description: These elements are used to group the table's rows into different sections - the header, body, and footer of the table, respectively.
<thead>: Contains header information, typically column labels or titles.
<tbody>: Contains the main content of the table.
<tfoot>: Contains the footer information, such as summary rows or totals.
<th>:
Description: The <th> element is used to define header cells within the table. Header cells are typically used in the table's header (inside <thead>), and they provide labels for columns or rows. They are semantically different from regular data cells, making screen readers and other assistive technologies identify them as headers.

## What is a constructor and what are some advantages to using it?

> A constructor is just a function called using the new keyword. When you call a constructor, it will:

create a new object
bind this to the new object, so you can refer to this in your constructor code
run the code in the constructor
return the new object.

## How does the term this differ when used in an object literal versus when used in a constructor?

> The key distinction is in how this is bound or refers to different objects. Object Literal (Object Initializer): When you use this within an object literal, this refers to the object that encloses the object literal. In this context, this points to the object itself.

## Explain prototypes and inheritance via an analogy from your previous work experience.

> In the military, think of prototypes as the standard operating procedures (SOPs) for a particular equipment type, like a tank. These SOPs provide a shared blueprint for how that equipment should be used and maintained. Inheritance is like creating different variations of that equipment, such as modifying the tank to become a recovery vehicle or an artillery piece, while still following the core SOPs. Similarly, in JavaScript, prototypes define the standard properties and methods for objects, and inheritance allows you to create different objects with shared features while adding specific attributes and behaviors.

## Things I want to know more about

I




