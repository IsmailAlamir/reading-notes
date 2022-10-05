# TDD - Test-Driven Development
Test-Driven Development is a strategy to think and do tests first.

##### the test name
The test file name should follow the same name of module name "test_module.py"
It’s ideal to separate the tests folder from production code
##### AAA: Arrange, Act and Assert.
- Arrange: you need to organize the data needed to execute that piece of code (input);
- Act: here you will execute the code being tested (exercise the behaviour);
- Assert: after executing the code, you will check if the result (output) is the same as you were expecting.

# What does the if ``` __name__ == "__main__" ```: do?
Whenever the python interpreter runs a module, it sets the name to main, indicating that it's the main module.
But if you imported the module into another module, the interpreter would put its name variable to the module name to show that this module is not the main one but used in the main one.
##### Advantages :
- Python files can act as either reusable modules, or as standalone programs.
- If you import this script as a module in another script, the ``` __name__ ``` is set to the name of the script/module.
- if ``` __name__ == "__main__" ```: is used to execute some code only if the file was run directly, and not imported.

# Recursion 
The fundamental part of recursion is self-reference - functions calling themselves. It is used to solve problems that can be broken up into easier sub-problems of the same type.
Recursion can also be indirect. One function can call a second, which calls the first, which calls the second, and so on.

##### Properties of Recursion:
- Performing the same operations multiple times with different inputs.
- In every step, we try smaller inputs to make the problem smaller.
- __Base condition__ is needed to stop the recursion otherwise infinite loop will occur.
(The base case is a way to return without making a recursive call.)

