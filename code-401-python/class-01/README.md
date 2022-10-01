# Big O Notation

Big O Notation is used to measure or describe the performance of any algorithm by providing the order of growth of the function.

- O(1) describes an algorithm that will always execute in the same time (or space) regardless of the size of the input data set.
- O(n) describes an algorithm whose performance will grow linearly and in direct proportion to the size of the input data set.
- O(n²) represents an algorithm whose performance is directly proportional to the square of the size of the input data set.
- O(2^n) denotes an algorithm whose growth doubles with each addition to the input data set.

|    Notation   | Name | Example |
| :---:        |    :----:   |          :---: |
| O(1)      | constant	       | A function that only returns a value(without loops).   |
| O(n)      | linear	       |  A function that includes one loop. |
| O(n²)   | quadratic	        | A function that includes nested loops.      |
| O(2^n)   | exponential        |  A recursion function.      |


# Python names and values

A variable allows you to store a value by assigning it to a name, which can be used to refer to the value later in the program.
For example, in game development, you would use a variable to store the points of the player.
To assign a variable, use one equals sign
```
x=10
```
## Variable Names
Certain restrictions apply in regard to the characters that may be used in Python variable names. The only characters that are allowed are letters, numbers, and underscores. Also, they can't start with numbers.
Not following these rules results in errors.

Variables can be reassigned as many times as you want, in order to change their value.
In Python, variables don't have specific types, so you can assign a string to a variable, and later assign an integer to the same variable.



