# Class 07

## Understanding Scope

> Scope refers to how variables and names are accessed within code, determining their visibility and accessibility. This concept follows the LEGB rule, which stands for Local, Enclosing, Global, and Built-in.

## Insight into Scope

> The scope of a name specifies the region within a program where you can unambiguously access that name, including variables, functions, and objects.

Two main types of scopes exist:

* Global Scope: Accessible throughout the entire code.
* Local Scope: Limited to the specific scope it is defined within.

## LEGB Rule

> Python employs the LEGB rule to resolve names:

* Local (or function) scope: Pertains to the code block or body of any Python function or lambda expression. Names defined within the function are only visible within that function's code. Each function call creates a new local scope.

* Enclosing (or nonlocal) scope: A special scope for nested functions. If the local scope is within a nested function, the enclosing scope is that of the outer function. Names in the enclosing scope are visible to both inner and enclosing functions.

* Global (or module) scope: The top-most scope in a Python program or module, containing names defined at the top level. Names in this scope are visible throughout the code.

* Built-in scope: A special Python scope loaded with keywords, functions, exceptions, and other built-in attributes. Available globally and automatically loaded when running a Python program.

## Keywords

> While Python follows LEGB, it provides global and nonlocal keywords to modify standard behavior:

* global: Used when assigning values to a global name, bypassing the creation of a new local name.

* nonlocal: Enables access to nonlocal names from inner functions without the need to assign or update them.

## Big O Notation

> Big O is a metric used to evaluate the resource usage (time and space) of an algorithm. It helps analyze algorithm intensity and serves as a benchmark for resource optimization.

## Dice Simulation

> To simulate rolling a die and calculate the probability of getting a specific number, use random.randint within a loop. Increase a counter when the desired number is rolled, then calculate the probability.

import random

target_number = 2
num_rolls = 1000

rolls = [random.randint(1, 6) for _ in range(num_rolls)]
probability = (rolls.count(target_number) / num_rolls) * 100

print(f"The probability of rolling a {target_number} in {num_rolls} rolls is: {probability}%")