
# Functional Programming
#### What is functional programming?
it is a programming paradigm ,that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data .

#### What is a pure function and how do we know if something is a pure function?
It returns the same result if given the same arguments (it is also referred as deterministic)
It does not cause any observable side effects

#### What are the benefits of a pure function?
it is easier to test

#### What is immutability?
state cannot change after it’s created.

#### What is Referential transparency?
pure functions + immutable data = referential transparency
and it can be replaced with its corresponding value (and vice-versa) without changing the program’s behavior

# module

#### What is a module?
simple or complex functionality organized in single or multiple JavaScript files which can be reused throughout the Node

#### What does the word 'require' do?
used to load and cache JavaScript modules

#### How do we bring another module into the file the we are working in?
module.exports = { your function };

#### What do we have to do to make a module available?
require(“your file path”);

## Things I want to know more about
module 
