## Learn HTML

> When should you use an unordered list in your HTML document?

* You should use an unordered list in your HTML document when you want to display a list of items, features, or information without any particular order. Unordered lists are often represented with bullet points. Common uses include creating navigation menus, showcasing features, FAQs, and simple bulleted lists. 

> How do you change the bullet style of unordered list items?

* To change the style of the bullets in an unordered list, you can use CSS. Here are some common styles:

Default Bullets: list-style-type: disc;
Circle Bullets: list-style-type: circle;
Square Bullets: list-style-type: square;
Numbers: list-style-type: decimal;
Roman Numerals (Uppercase): list-style-type: upper-roman;
Roman Numerals (Lowercase): list-style-type: lower-roman;


> When should you use an ordered list vs an unorder list in your HTML document?

* You should use an ordered list when you want to present a list of items in a specific order, like steps in a process or a ranking. Use an unordered list when the order of items doesn't matter, such as for a simple list of items or features. In ordered lists, items are numbered (1, 2, 3), while unordered lists use bullet points.

> Describe two ways you can change the numbers on list items provided by an ordered list?

* Change Number Style: You can use CSS to change how the numbers appear. For instance, you can use Roman numerals (I, II, III) or letters (A, B, C) instead of regular numbers (1, 2, 3).

* Start from a Different Number: You can specify where the list begins. So, instead of starting from 1, you can begin with any number you want, like 5 or 10.

## Learn CSS 


> Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

* Margin is like a character who creates space around the main character (the content). It ensures there's some room and prevents overcrowding.

* Padding is another character that provides protection within the content box. It's like a soft cushion that keeps the content safe and cozy, away from the edges.

* Together, Margin and Padding work to make sure the story looks good and feels comfortable to the readers. Margin maintains space, and Padding keeps the content safe and snug.

source: ChatGPT


List and describe the four parts of an HTML elements box as referred to by the box model.

* Content: This is the main part of the element where your text and images are displayed. It's like the story inside a book.

* Padding: Think of this as the space around the content. It's like the cushioning inside a package that keeps the content cozy.

* Border: This is like the frame of a painting. It goes around the padding and content to give the element a clear edge.

* Margin: This is like the buffer space around the element, creating distance between it and other elements. It's like the empty space between paragraphs in a book, keeping things organized and not too crowded.

## Learn JS
Arrays. Operators and Expressions. Conditionals. Loops.

> What data types can you store inside of an Array?

* Numbers: Like 1, 2, 3.
Text: Such as words or sentences.
Other Arrays: You can put arrays inside arrays.
Objects: These hold multiple pieces of information.
Booleans: Which are either true or false.
Mix of Types: You can mix all of these in one array!

source: The reading/my own words


> Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?

 const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];

Yes, the "people" array is a valid JavaScript array. To access the values stored, you use the index position inside square brackets. For example, people[0] would give you the first sub-array ['pete', 32, 'librarian', null], and then you can access the values within that sub-array using indices again, like people[0][0] would give you "pete."

source:ChatGPT


> List five shorthand operators for assignment in javascript and describe what they do.
Read the code below and evaluate the last expression and explain what the result would be and why.

 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;

+=: Add and assign.
-=: Subtract and assign.
*=: Multiply and assign.
/=: Divide and assign.
%=: Calculate remainder and assign.

source:ChatGPT

> Describe a real world example of when a conditional statement should be used in a JavaScript program.

* A real-world example of using a conditional statement in a JavaScript program is in an online shopping app. It can be used to check if a user's total purchase qualifies for a discount. If their purchase is over a certain amount (e.g., $100), the code applies a discount. If not, no discount is given. It's a way to make online shopping more affordable for customers when they spend a certain amount.

source:my own words

> Give an example of when a Loop is useful in JavaScript.

* A loop in JavaScript is useful when you have a repetitive task. Imagine you're packing boxes with products in a warehouse. You have a list of items to put in each box. Instead of doing it one by one, you can use a loop to repeat the process: "Put the next item in the box" until you've packed all the items. A loop is like a helpful machine that automates these repetitive tasks.