[<==Back](README.md)


Functional Programming Concepts


What is functional programming?

- a programming paradigm - "a style of building the structure and elements of computer programs - that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data

What is a pure function and how do we know if something is a pure function?

Purity strictly defines as:

- it returns the same result if given same arguments (referred as deterministic)
- it does not cause any observable side effects

What are the benefits of a pure function?

it uses parameters passed to the function only.

What is immutability?

unchanging over time of unable to change, state doesnt change after its createdl cant change it need to make a  new object

What is Referential transparency?

a function that simply always has the same value of output given the same input



Node JS Tutorial for Beginners #6 - Modules and require()



What is a module?

a different module for every different bit of code that has a certain funcitonality. call upon those modules when they are needed.

What does the word ‘require’ do?

calls upon the module


How do we bring another module into the file the we are working in?

require(./counter)

<!-- import weather from './weather.js; -->


What do we have to do to make a module available?

module.export = counter; (whatever you want available)

<!-- export default app; -->