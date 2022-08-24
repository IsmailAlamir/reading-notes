
## React Docs - Thinking in React

#### What is the single responsibility principle and how does it apply to components?
a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents

#### What does it mean to build a ‘static’ version of your application?
a compiled version of a program which has been statically linked against libraries.

#### Once you have a static application, what do you need to add?
build components that reuse other components and pass data using props only and we don't use state since it static.

#### What are the three questions you can ask to determine if something is state?
1- Is it passed in from a parent via props? If so, it probably isn’t state.
2- Does it remain unchanged over time? If so, it probably isn’t state.
3- Can you compute it based on any other state or props in your component? If so, it isn’t state.

#### How can you identify where state needs to live?
if our component depends on a data to render and show some results, then this data can be placed in state.
State changes, component rerenders and show results depending on the state.

## Higher-Order Functions

#### What is a “higher-order function”?
Higher Orders Functions are functions that perform operations on other functions.

#### Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
returning a logic to comparing m and n which returns boolean.

#### Explain how either map or reduce operates, with regards to higher-order functions.
reduce: accumlate a value by doing something to each item in an array and will return single value.
map: create new array by doing something with each item in an original array and will return the same number of element that in origin array.

## Things I want to know more about 
reduce

