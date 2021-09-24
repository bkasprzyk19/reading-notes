[<==Back](README.md)


What is a ‘call’?

function invocation

How many ‘calls’ can happen at once?

last in first out, one at a time

What does LIFO mean?

last in first out

Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

``` javascript

credit : https://www.freecodecamp.org/news/understang-the-javascript-call-stack-861e41ae61d4/

function firstFunction(){
  throw new Error('Stack Trace Error');
}

function secondFunction(){
  firstFunction();
}

function thirdFunction(){
  secondFunction();
}

thirdFunction();

```

What causes a Stack Overflow?.

![img](./stack.png)



JavaScript error messages


What is a ‘refrence error’?

When you use a variable that hasnt been declared yet. 

What is a ‘syntax error’?

WHen you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using json.parse

What is a ‘range error’?.

trying to manipulate an object with some king of length and giving it an invalid length returns this type of error

What is a ‘tyep error’?

(number, string, so on) you are trying to use or access are incompatitble.

What is a breakpoint?

it stops the program at that point if a condition is met. it helps for debugging big cycles

What does the word ‘debugger’ do in your code?.

initiate a breakpoint


