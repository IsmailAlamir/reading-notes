# Understanding the JavaScript Call Stack

#### What is a 'call'?
is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).

#### How many 'calls' can happen at once?
one at a time.

#### What does LIFO mean?
Last In, First Out.


#### Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

let func1=()=>console.log("this is func. 1");

let func2=()=>func1=();

func2();

#### What causes a Stack Overflow?
When the function call it self is the last function in the call stack.


# JavaScript error messages

#### What is a 'reference error'?
when a code attempts to reference a non-existing variable
console.log(foo) // Uncaught ReferenceError: foo is not defined

#### What is a 'syntax error'?
this occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.
JSON.parse( {'foo': 'bar'} ) // Uncaught SyntaxError: Unexpected token o in JSON at position 1

#### What is a 'range error'?
Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.
var foo= []
foo.length = foo.length -1 // Uncaught RangeError: Invalid array length

#### What is a 'tyep error'?
this types of errors show up when the types you are trying to use or access are incompatible.


#### What is a breakpoint?
A breakpoint is an intentional stopping or pausing place in a program, put in place for debugging purposes.


#### What does the word 'debugger' do in your code?
Debugging tools used to identify coding errors at various development stages. 

## Things I want to know more about
debugger


