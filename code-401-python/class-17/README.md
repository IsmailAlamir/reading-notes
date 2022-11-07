# Automation

## Python Regular Expressions 

Regular Expressions, often shortened as regex, are a sequence of characters used to check whether a pattern exists in a given text (string) or not.

In Python, regular expressions are supported by the re module. That means that if you want to start using them in your Python scripts, you have to import this module with the help of import.

### Basic Patterns: Ordinary Characters

You can easily tackle many basic patterns in Python using ordinary characters. Ordinary characters are the simplest regular expressions. They match themselves exactly and do not have a special meaning in their regular expression syntax.

The match() function returns a match object if the text matches the pattern. Otherwise, it returns None. 

The (r) at the start of the pattern is called a raw string literal. It changes how the string literal is interpreted. Such literals are stored as they appear.
For example, \ is just a backslash when prefixed with an r rather than being interpreted as an escape sequence.

### Repetitions

It becomes quite tedious if you are looking to find long patterns in a sequence. Fortunately, the re module handles repetitions using the following special characters:

- ``` + -```Checks if the preceding character appears one or more times starting from that position.

- ``` * -```Checks if the preceding character appears zero or more times starting from that position.

- ``` ? -```Checks if the preceding character appears exactly zero or one time starting from that position.

- {x} - Repeat exactly x number of times.
- {x,} - Repeat at least x times or more.
- {x, y} - Repeat at least x times but no more than y times.

### Grouping in Regular Expressions

The group feature of regular expression allows you to pick up parts of the matching text. Parts of a regular expression pattern bounded by parenthesis () are called groups. The parenthesis does not change what the expression matches, but rather forms groups within the matched sequence. 

Another way of doing the same is with the usage of ```<>``` brackets instead. This will let you create named groups. Named groups will make your code more readable. The syntax for creating named group is: ```(?P<name>...)```. Replace the name part with the name you want to give to your group. The ```...``` represent the rest of the matching syntax. 

### Greedy vs. Non-Greedy Matching

When a special character matches as much of the search sequence (string) as possible, it is said to be a "Greedy Match". It is the normal behavior of a regular expression, but sometimes this behavior is not desired.
