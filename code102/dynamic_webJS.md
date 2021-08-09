
Variables

Variables are containers for storing data (values).




var x = 5;
var y = 6;
var z = x + y;




var price1 = 5;
var price2 = 6;
var total = price1 + price2;


In JavaScript, the equal sign (=) is an "assignment" operator, not an "equal to" operator.

This is different from algebra. The following does not make sense in algebra:




 <p id="demo"></p>

<script>
var carName = "Volvo";
document.getElementById("demo").innerHTML = carName;
</script> 


var person = "John Doe", carName = "Volvo", price = 200;


Prerequisites: 	Basic computer literacy, a basic understanding of HTML and CSS.
Objective: 	To gain familiarity with what JavaScript is, what it can do, and how it fits into a web site.

#Document Object Model (DOM)

The Document Object Model (DOM) connects web pages to scripts or programming languages by representing the structure of a document—such as the HTML representing a web page—in memory. Usually it refers to JavaScript, even though modeling HTML, SVG, or XML documents as objects are not part of the core JavaScript language. The DOM represents a document with a logical tree. Each branch of the tree ends in a node, and each node contains objects. DOM methods allow programmatic access to the tree. With them, you can change the document's structure, style, or content.

Nodes can also have event handlers attached to them. Once an event is triggered, the event handlers get executed.

https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model





[<==Back](README.md)



