# Read: Class 02

> What are the key principles of Test-Driven Development (TDD) in Python, and how do they contribute to the overall quality of code?

Test-Driven Development (TDD) in Python:
TDD involves writing tests before code, ensuring comprehensive test coverage, initially failing tests, writing minimal code to pass the tests, and refactoring code to maintain functionality. It elevates code quality by catching bugs early and providing a safety net for continuous improvement.

>Explain the purpose of the if __name__ == '__main__': statement in Python scripts. What are some use cases for including this conditional in your code?

This statement checks if the Python script is being run directly or if it's being imported as a module. Code within this block executes only when the script is run as the main program, allowing for specific instructions or functionality tailored for that purpose.

> Describe the concept of recursion in Python.

Recursion involves a function calling itself to solve a problem by breaking it into smaller instances. It continues this process until it reaches a base case, solving each smaller instance to obtain the final solution. Recursion provides an elegant solution for tasks that can be divided into smaller, similar subtasks.

> What is the difference between Python modules and packages? Explain how to create, import, and use them in your Python programs.

Modules are individual Python files containing functions, variables, or classes. Packages are directories containing multiple modules and an __init__.py file. To create a module or package, write code in a .py file or a directory with an __init__.py file, respectively. Import them using import module_name or from package_name import module_name. Access their contents using dot notation: module_name.function() or package_name.module_name.function().


