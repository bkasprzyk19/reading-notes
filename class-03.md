[<==Back](README.md)


## Reading

### From the Duckett HTML book:

- Chapter 3: “Lists” (pp.62-73)
- Chapter 13: “Boxes” (pp.300-329)

### From the Duckett JS book:

- Review from Reading 02 - Chapter 2: “Basic JavaScript  Instructions” (pp.70-73)
- Chapter 4: “Decisions and Loops” from switch statements on (pp.162-182)


## ordered vs unordered lists

- `<ul>`
<br>
`<li>something listed</li>`
<br>
`</ul>`
<br>

- `<ol>`<br>
`<li>first</li>`
<br>
`</ol>`

### Boxing

`	margin: 0;`<br>
	`padding: 0;`<br>
`	border: 0;`<br>
	`font-size: 100%;`<br>
`	font: inherit;`<br>
	`vertical-align: baseline;`<br>
}

## if .. else statements

- checks a condition
- if it resolves `true`...

- execute code

`if (rain = no) {`
`plant();`
`}`
`else {`
 ` wait();`

`}`

## switch statement

- example
let review = prompt('On a scale of 1-7, please submit a number which you rate our site as: 1 being terrible, 7 being the best you ever saw');

console.log(typeof review);

let reviewNumber = parseInt(review);

`<!-- switch (reviewNumber) {
  case 1: 
    alert(userName + ', please join our team to help us!');
    break;
    case 2: 
    alert(userName + ', please join our team to help us!');
    break;
    case 3: 
    alert(userName + ', please join our team to help us!');
    break;
    case 4: 
    alert(userName + ', please join our team to help us!');
    break;
    case 5: 
    alert(userName + ', please join our team to help us!');
    break;
    case 6:
      alert(userName + ', please spread the word!');
      break;
    case 7: 
      alert('woot woot!!! good job '+ userName);
      break;
  default:
      alert('Enjoy your time ' + userName) -->`
      
## Data Types

- string
- number
- boolean
- null
- undefined

<br>


## - *falsy* and **truthy** values
<br>

# Loops

## For -- While -- Do While


*For*<br>
Runs code specific number of times
- most common

*While*<br>
Not not sure how many times it will need to be run
- if condition is true, code runs

*Do While* <br>
Similar to while loop
- will always run at least once even if evaluates to false

<br>

## `for (var i=0; i < 10; i++)`
## `{document.write(i);}`
<br>

##  `Decisions & Loops`

- conditions allow code to make decions about what happens 
- comparison operators dictate (`===,!==,==,!=,<,>,<=>`)
- if .. else .. allow you to break away in a direction depending on true v false
- data types can be "coerced"

