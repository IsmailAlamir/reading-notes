# Read & Write Files in Python
__a file__ is a contiguous set of bytes used to store data in a specific format.
these byte files are translated into binary 1 and 0 for easier processing by the computer.
What this data contains is represented by the extension of the file for example ```.txt```.
When you access a file on an operating system, a file path is required. The file path is a string that represents the location of a file.

### Opening and Closing a File in Python:
When you want to open a file in python you need to use the ```open(file path)``` and to close the file you need to use ```close()```.
</br>
Another way to open and close is using the keyword ```with```.
There are also some modes when opening files, and they are indicated by characters:
| Character   | Meaning                   |
|-------------|---------------------------|
| 'r'     | Open for reading (default)|
|'w'    | Open for writing, truncating (overwriting) the file first |
 |'rb' or 'wb'    | Open in binary mode (read/write using byte data) |

### Reading and Writing Opened Files

| Character   | Meaning                   |
|-------------|---------------------------|
|.read(size=-1)  | This reads from the file based on the number of size bytes. If no argument is passed or None or -1 is passed, then the entire file is read.|
|.readline(size=-1)  | This reads at most size number of characters from the line. This continues to the end of the line and then wraps back around. If no argument is passed or None or -1 is passed, then the entire line (or rest of the line) is read. |
|.readlines()   | This reads the remaining lines from the file object and returns them as a list. |


# Exceptions in Python
__Exceptions__ is An event that occurs due to incorrect code or input.

### Exceptions VS Syntax Errors
Syntax errors occur when the parser detects an incorrect statement. 
The arrow indicates where the parser ran into the syntax error.

Exception Error: This type of error occurs whenever syntactically correct Python code results in an error. The last line of the message indicated what type of exception error you ran into.
Instead of showing the message exception error, Python details what type of exception error was encountered.
Python comes with various built-in exceptions as well as the possibility to create self-defined exceptions.

#### Raising Exception
You can raise exceptions by using the raise statement.
``` raise ValueError ```

#### The AssertionError Exception
An assertion is a sanity-check that you can turn on or turn off when you have finished testing the program.
An expression is tested, and if the result comes up false, an exception is raised.
it can be done by using the ```assert()``` , after that you can add a condition and a message, so that if the condition wasn’t met where will be a message to throw in the console.

#### The try and except Block: Handling Exceptions
```Try``` is where the main code goes, and the except is where the ```exception``` goes if there was an error


#### finally
To ensure some code runs no matter what errors occur, you can use a ```finally```,it placed at the bottom of a ```try..except``` statement. </br>
Code within a finally statement always runs after execution of the code in the ```try```, and possibly in the ```except```.

