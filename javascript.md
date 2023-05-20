# javascript

Date Created: May 19, 2023 9:09 PM
Status: Doing

# **What is JavaScript?**

JavaScript is the **Programming Language** for the Web.

JavaScript can update and change both **HTML** and **CSS.**

JavaScript can **calculate**, **manipulate** and **validate** data.

# JavaScript Quickstart Tutorial

This tutorial will take a quick look at the most important JavaScript data types.

JavaScript variables can be:

- Numbers
- Strings
- Objects
- Arrays
- Functions

# JavaScript Variables

JavaScript variables are containers for storing data values.

In this example, x, y, and z, are variables:

<!DOCTYPE html>
<html>
<body>

<h2>JavaScript Variables</h2>

<p>In this example, x, y, and z are variables.</p>

<p id="demo"></p>

<script>
var x = 5;
var y = 6;
var z = x + y;
document.getElementById("demo").innerHTML =
"The value of z is: " + z;
</script>

</body>
</html>

From the example above, you can expect:

- x stores the value 5
- y stores the value 6
- z stores the value 11

# JavaScript Numbers

JavaScript has only **one type** of number. Numbers can be written with or without decimals.

# Example

<!DOCTYPE html>
<html>
<body>

<h2>JavaScript Numbers</h2>

<p>Numbers can be written with or without decimals:</p>

<p id="demo"></p>

<script>
var x = 3.14;
var y = 3;
document.getElementById("demo").innerHTML = x + "<br>" + y;
</script>

</body>
</html>

value will be

## JavaScript Numbers

Numbers can be written with or without decimals:

3.14

3

All numbers are stored as double precision floating point numbers.

The maximum number of decimals is 17, but floating point is not always 100% accurate:

# JavaScript Strings

Strings **store text**. Strings are written inside quotes. You can use **single** or double **quotes**:

<!DOCTYPE html>
<html>
<body>

<h2>JavaScript Strings</h2>

<p>Strings are written inside quotes. You can use single or double quotes:</p>

<p id="demo"></p>

<script>

var carName1 = "Volvo XC60"; // Double quotes
var carName2 = 'Volvo XC60'; // Single quotes

document.getElementById("demo").innerHTML =
carName1 + " " + carName2;

</script>

</body>
</html>

value will be

## JavaScript Strings

Strings are written inside quotes. You can use single or double quotes:

Volvo XC60 Volvo XC60

The length of a string is found in the built in property **length**:

var txt = "ABCDEFGHIJKLMNOPQRSTUVWXYZ";

var sln = txt.length;

# JavaScript Objects

You have already learned that JavaScript variables are containers for data values.

This code assigns a **simple value** (Fiat) to a **variable** named car:

<!DOCTYPE html>
<html>
<body>

<h2>JavaScript Variables</h2>

<p id="demo"></p>

<script>
// Create and display a variable:
var car = "Fiat";
document.getElementById("demo").innerHTML = car;
</script>

</body>
</html>

value will be 

## JavaScript Variables

Fiat

Objects are variables too. But objects can contain many values.

This code assigns **many values** (Fiat, 500, white) to a **variable** named car:

<!DOCTYPE html>
<html>
<body>

<h2>JavaScript Objects</h2>

<p id="demo"></p>

<script>
// Create an object:
var car = {type:"Fiat", model:"500", color:"white"};

// Display some data from the object:
document.getElementById("demo").innerHTML = "The car type is " + car.type;
</script>

</body>
</html>

value will be

## JavaScript Objects

The car type is Fiat

# JavaScript Arrays

JavaScript arrays are used to store multiple values in a single variable.

<!DOCTYPE html>
<html>
<body>

<h2>JavaScript Arrays</h2>

<p id="demo"></p>

<script>
var cars = ["Saab", "Volvo", "BMW"];
document.getElementById("demo").innerHTML = cars;
</script>

</body>
</html>

the value will be 

## JavaScript Arrays

Saab,Volvo,BMW

# JavaScript Functions

A JavaScript function is a block of code designed to perform a particular task.

A JavaScript function is executed when "something" invokes it (calls it).

<!DOCTYPE html>
<html>
<body>

<h2>JavaScript Functions</h2>

<p>This example calls a function which performs a calculation, and returns the result:</p>

<p id="demo"></p>

<script>
function myFunction(p1, p2) {
return p1 * p2;
}
document.getElementById("demo").innerHTML = myFunction(4, 3);
</script>

</body>
</html>

the value will be 

## JavaScript Functions

This example calls a function which performs a calculation, and returns the result:

12

# What can JavaScript Do?

This section contains some examples of what JavaScript can do:

- JavaScript Can Change HTML Content
- JavaScript Can Change HTML Attribute Values
- JavaScript Can Change HTML Styles (CSS)
- JavaScript Can Hide HTML Elements
- JavaScript Can Show HTML Elements

# JavaScript Can Change HTML Content

One of many JavaScript HTML methods is **getElementById()**.

This example uses the method to "find" an HTML element (with id="demo") and changes the element content (**innerHTML**) to "Hello JavaScript":

<!DOCTYPE html>
<html>
<body>

<h2>What Can JavaScript Do?</h2>

<p id="demo">JavaScript can change HTML content.</p>

<button type="button" onclick='document.getElementById("demo").innerHTML = "Hello JavaScript!"'>Click Me!</button>

</body>
</html>

the value will be 

## What Can JavaScript Do?

JavaScript can change HTML content.

Click Me!

# JavaScript Can Change HTML Attribute Values

In this example JavaScript changes the value of the src (source) attribute of an <img> tag:

<!DOCTYPE html>
<html>
<body>

<h2>What Can JavaScript Do?</h2>

<p>JavaScript can change HTML attribute values.</p>

<p>In this case JavaScript changes the value of the src (source) attribute of an image.</p>

<button onclick="document.getElementById('myImage').src='img_bulbon.gif'">Turn on the light</button>

<img id="myImage" src="img_bulboff.gif" style="width:100px">

<button onclick="document.getElementById('myImage').src='img_bulboff.gif'">Turn off the light</button>

</body>
</html>

the value will be 

## What Can JavaScript Do?

JavaScript can change HTML attribute values.

In this case JavaScript changes the value of the src (source) attribute of an image.

Turn on the light

![https://www.w3schools.com/whatis/img_bulbon.gif](https://www.w3schools.com/whatis/img_bulbon.gif)

Turn off the light

# JavaScript Can Change HTML Styles (CSS)

Changing the style of an HTML element, is a variant of changing an HTML attribute:

<!DOCTYPE html>
<html>
<body>

<h2>What Can JavaScript Do?</h2>

<p id="demo">JavaScript can change the style of an HTML element.</p>

<button type="button" onclick="document.getElementById('demo').style.fontSize='35px'">Click Me!</button>

</body>
</html>

the value will be 

## What Can JavaScript Do?

JavaScript can change the style of an HTML element.

Click Me!

# JavaScript Can Hide HTML Elements

Hiding HTML elements can be done by changing the display style:

<!DOCTYPE html>
<html>
<body>

<h2>What Can JavaScript Do?</h2>

<p id="demo">JavaScript can hide HTML elements.</p>

<button type="button" onclick="document.getElementById('demo').style.display='none'">Click Me!</button>

</body>
</html>

the value will be

<!DOCTYPE html
<html>
<body>

<h2>What Can JavaScript Do?</h2>

<p id="demo">JavaScript can hide HTML elements.</p>

<button type="button" onclick="document.getElementById('demo').style.display='none'">Click Me!</button>

</body>
</html>

the value will be

## What Can JavaScript Do?

JavaScript can hide HTML elements.

Click Me!

# JavaScript Can Show HTML Elements

Showing hidden HTML elements can also be done by changing the display style:

<!DOCTYPE html>
<html>
<body>

<h2>What Can JavaScript Do?</h2>

<p>JavaScript can show hidden HTML elements.</p>

<p id="demo" style="display:none">Hello JavaScript!</p>

<button type="button" onclick="document.getElementById('demo').style.display='block'">Click Me!</button>

</body>
</html>

the value is 

## What Can JavaScript Do?

JavaScript can show hidden HTML elements.

Click Me!

#
