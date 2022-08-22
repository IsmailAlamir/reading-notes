This class talks about the lists and keys,The Spread Operator, and how to pass functions between components
and how to use them in the best way possible

# React Docs - lists and keys

#### What does .map() return?
new array and does not change the original array.

#### If I want to loop through an array and display each value in JSX, how do I do that in React?
use -map method-  and then braces to assign value of -props- for every element.

#### Each list item needs a unique ____.
 key 
 
#### What is the purpose of a key?
help React identify which items have changed, are added, or are removed.

# The Spread Operator

#### What is the spread operator?
The spread operator is a new addition to the set of operators in JavaScript ES6.
It takes in an iterable like array and expands it into individual elements.

#### List 4 things that the spread operator can do.
- Copying an array
- Concatenating or combining arrays
- Using Math functions
- Using an array as arguments

#### Give an example of using the spread operator to combine two arrays.
let arr1 =[1,2,3];
let arr2 =[1,2,3];
let combine = [...arr1, ...arr2]; 
//[1, 2, 3, 1, 2, 3]

#### Give an example of using the spread operator to add a new item to an array.
let arr = [1,2,3];
let newItem = 2;
let addItem = [newItem, ...arr];
//[2,1,2,3]

#### Give an example of using the spread operator to combine two objects into one.
let obj1 = { a:1 , b:2 }; 
let obj2 = { c:3 , d:4 };
let combineObj = {...obj1, ...obj2};
//{a: 1, b: 2, c: 3, d: 4}

# Pass Functions Between Components

#### In the video, what is the first step that the developer does to pass functions between components?
create a function  

#### In your own words, what does the increment function do?
Increase the value

#### How can you pass a method from a parent component into a child component?
you can passing method as a prop 

#### How does the child component invoke a method that was passed to it from a parent component?
The save button click will call handleSaveClick on the child 
when the child component mounts and passes the callback to the Parent component


## Things I want to know more about
Spread Operator

### resources
[The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

[React Docs - lists and keys](https://reactjs.org/docs/lists-and-keys.html)
