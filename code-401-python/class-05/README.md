# Classes and Objects
#### OOP : object-oriented programming
Objects are created using classes, which are actually the focal point of OOP.
The class describes what the object will be, but is separate from the object itself. In other words, a class can be described as an object's blueprint, description, or definition.
You can use the same class as a blueprint for creating multiple different objects.

Classes are created using the keyword class and an indented block, which contains class methods (which are functions).

### ```__init__```


The ```__init__()``` function, is a special function that is called when the class is being initiated. It's used for assigning values in a class.
This is called when an instance (object) of the class is created, using the class name as a function.

All methods must have self as their first parameter, although it isn't explicitly passed, Python adds the self argument to the list for you; you do not need to include it when you call the methods. Within a method definition, self refers to the instance calling the method.
Instances of a class have attributes, which are pieces of data associated with them.


# Thinking Recursively
__What is Recursion function?__
- Well a recursion function is a kind of where the function keep calling it self until a basecase is met, then it stops and gives the result.

### Maintaining State
When dealing with recursive functions, keep in mind that each recursive call has its own execution context, so to maintain state during recursion you have to either:
- Thread the state through each recursive call so that the current state is part of the current call’s execution context
- Keep the state in global scope

### Recursive Data Structures in Python

A data structure is recursive if it can be deﬁned in terms of a smaller version of itself. A list is an example of a recursive data structure. 
Using the empty list and the attach_head operation, you can generate any list.
List is not the only recursive data structure. Other examples include set, tree, dictionary, etc.

Recursive data structures and recursive functions go together like bread and butter. The recursive function’s structure can often be modeled after the definition of the recursive data structure it takes as an input.


# Pytest Fixtures and Coverage

### Fixtures
do some objects available to all of your tests. Those objects might contain data you want to share across tests, or they might involve the network or filesystem. These are often known as "fixtures" in the testing world, and they take a variety of different forms.

In pytest, you define fixtures using a combination of the ```pytest.fixture``` decorator, along with a function definition
- usege inside code ```@pytest.fixture.```
### Coverage
 its to checking that your tests have run all of the code.
 
 you can install it by ```pip pytest-cov```

#### Another info about Anatomy of a test to know 
__Arrange__ : is where we prepare everything for our test.

__Act__ : is the singular, state-changing action that kicks off the behavior we want to test.

__Assert__ : is where we look at that resulting state and check if it looks how we’d expect after the dust has settled.

__Cleanup__ : is where the test picks up after itself, so other tests aren’t being accidentally influenced by it.




