[<==Back](README.md)

# React Docs - Thinking in React

- What is the single responsibility principle and how does it apply to components?

A component should ideally only do one thing. If it ends up growing it needs to be 'decomposed' into smaller subcomponents.

- What does it mean to build a ‘static’ version of your application?

A version without any interactivity so as to show the data model and render the UI

- Once you have a static application, what do you need to add?

Functionality and interactivity.

- What are the three questions you can ask to determine if something is state?

Is it passed in from a parent via props?
Does it remain unchanged over time?
Can you compute it based on any other state or props in your component?

- How can you identify where state needs to live?

Which component owns the state. Identify which components render somethings based on the state. Find the common owner component. Either a common owner or another component higher up should own the state.
You can also create a new component solely for holding the state.

https://reactjs.org/docs/thinking-in-react.html



# Higher-Order Functions

- What is a “higher-order function”?

functions that operate on other functions, either by taking them as arguments or by returning them, are called higher-order functions. 

- Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

returning a function that cehcks if the input value n is less than the initial input value m

- Explain how either map or reduce operates, with regards to higher-order functions.



https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK