[<==Back](README.md)

# Things I want to know more about

## What does .map() return?

.map() returns an array of the same length just with diferent values. 

## If I want to loop through an array and display each value in JSX, how do I do that in React?

console.log(

 ## Each list item needs a unique ____.  key

## What is the purpose of a key?

to give elements a stable identity

# Spread Operator

## What is the spread operator?

...arr is a spread, really its just the ... part

## List 4 things that the spread operator can do.

It spreads the array into seperate arguments for functions like math.max

It can copy an array

It was use other math functions
It can use an array as arguments to a function
It can combine objects or convert NodeList or add to a state in react.


Give an example of using the spread operator to combine two arrays.

const arrayCombined = {...firstArray,...secondArray};


Give an example of using the spread operator to add a new item to an array.

[item 1, item 2, ...other ithem of array to be added]

Give an example of using the spread operator to combine two objects into one

const objectsCombined = {...firstObj,...secondObj, thirdObj: emoji smile};

objects combines, firstObj, secondObj, and emoji smile

In the video, what is the first step that the developer does to pass functions between components?

create the function whereever the state is that is going to change. called increment, passed in a person object, which count to increment

In your own words, what does the increment function do?
How can you pass a method from a parent component into a child component?

it loops through an array using the map method to create the new array of the same length using updated counts based on a name. 

How does the child component invoke a method that was passed to it from a parent component?

call the function in the child

 increment = {this.increment}
 place this.props.increment(this.props.name) in the increment 