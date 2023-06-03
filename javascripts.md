# javascript

**Variables are Containers for Storing Data**

JavaScript Variables can be declared in 4 ways:

- Automatically
- Using `var`
- Using `let`
- Using `const`

It is considered good programming practice to always declare variables before use.

# When to Use var, let, or const?

1. Always declare variables

2. Always use `const` if the value should not be changed

3. Always use `const` if the type should not be changed (Arrays and Objects)

4. Only use `let` if you can't use `const`

5. Only use `var` if you MUST support old browsers.

[](https://www.notion.so/e65a1f0ac3de4f3599396ab0a8c17b30?pvs=21)

# JavaScript Identifiers

All JavaScript **variables** must be **identified** with **unique names**.

These unique names are called **identifiers**.

Identifiers can be short names (like x and y) or more descriptive names (age, sum, totalVolume).

The general rules for constructing names for variables (unique identifiers) are:

- Names can contain letters, digits, underscores, and dollar signs.
- Names must begin with a letter.
- Names can also begin with $ and _ (but we will not use it in this tutorial).
- Names are case sensitive (y and Y are different variables).
- Reserved words (like JavaScript keywords) cannot be used as names.

# Note

The "equal to" operator is written like `==` in JavaScript.

In JavaScript, the equal sign (`=`) is an "assignment" operator, not an "equal to" operator.

# Declaring a JavaScript Variable

Creating a variable in JavaScript is called "declaring" a variable.

You declare a JavaScript variable with the `var` or the `let` keyword:

After the declaration, the variable has no value (technically it is `undefined`).

You can  assign a value to the variable when you declare it:

# One Statement, Many Variables

You can declare many variables in one statement.

Start the statement with `let` and separate the variables by **comma**:

A declaration can span multiple lines:

let person = "John Doe",

carName = "Volvo",

price = 200;

# Re-Declaring JavaScript Variables

If you re-declare a JavaScript variable declared with `var`, it will not lose its value.

You cannot re-declare a variable declared with `let` or `const`.

### Arithmetic Operators

Arithmetic operators are mathematical operators.

- Addition(+): a + b
- Subtraction(-): a - b
- Multiplication(*): a * b
- Division(/): a / b
- Modulus(%): a % b
- Exponential(**): a ** b

### Comparison Operators

In programming we compare values, we use comparison operators to compare two values. We check if a value is greater or less or equal to other value.

![Untitled](javascript%20ccb517a190d24184a3c024acc6923b42/Untitled.png)

// && ampersand operator example

const check = 4 > 3 && 10 > 5         // true && true -> true
const check = 4 > 3 && 10 < 5         // true && false -> false
const check = 4 < 3 && 10 < 5         // false && false -> false

// || pipe or operator, example

const check = 4 > 3 || 10 > 5         // true  || true -> true
const check = 4 > 3 || 10 < 5         // true  || false -> true
const check = 4 < 3 || 10 < 5         // false || false -> false

//! Negation examples

let check = 4 > 3                     // true
let check = !(4 > 3)                  //  false
let isLightOn = true
let isLightOff = !isLightOn           // false
let isMarried = !false                // true

**Primitive and Non-primitive data-types in JavaScript**

**Primitive data types:** The predefined data types provided by JavaScript language are known as primitive data types.

**1. [Number](https://www.geeksforgeeks.org/javascript-numbers/):** Number data type in javascript can be used to hold decimal values as well as values without decimals.

**2.** **[String](https://www.geeksforgeeks.org/javascript-strings/):** The string data type in javascript represents a sequence of characters that are surrounded by single or double quotes.

**3. [Undefined](https://www.geeksforgeeks.org/javascript-undefined-property/):** The meaning of undefined is ‘value is not assigned’.

**4. [Boolean](https://www.geeksforgeeks.org/javascript-boolean/):** The boolean data type can accept only two values i.e. true and false.

**5. [Null](https://www.geeksforgeeks.org/null-in-javascript/):** This data type can hold only one possible value that is null.

**6. [BigInt](https://www.geeksforgeeks.org/bigint-in-javascript/):** This data type can represent numbers greater than 253-1 which helps to perform operations on large numbers. The number is specified by writing ‘n’ at the end of the value

**7. [Symbol](https://www.geeksforgeeks.org/javascript-symbol-method/):** This data type is used to create objects which will always be unique. these objects can be created using Symbol constructor.

*Symbol Output*

**Non-primitive data types:** The data types that are derived from primitive data types of the JavaScript language are known as non-primitive data types. It is also known as derived data types or reference data types.

**1. [Object](https://www.geeksforgeeks.org/javascript-objects/): An object** in Javascript is an entity having properties and methods. Everything is an object in javascript.

• **Using Constructor Function to define an object:**

`var obj = new Object();`

• **Using Literal notations to define an object:**

`var square = {};`

**2. [Array](https://www.geeksforgeeks.org/arrays-in-javascript/):** With the help of an array, we can store more than one element under a single name.

**Ways to declare a** **single-dimensional array:**

`// Call it with no arguments`

`var a = new Array();`

`// Call it with single numeric argument`

`var b = new Array(10);`

**String**

**string method**

**accessing string**

let string = 'JavaScript'
let firstLetter = string[0]
console.log(firstLetter) // 

**char at**

string.charAt(index)
let string = '30 Days Of JavaScript'
console.log(string.charAt(0)) // 3
let lastIndex = string.length - 1
console.log(string.charAt(lastIndex)) // t

**charCodeAt**

string.charCodeAt(index)
let string = '30 Days Of JavaScript'
console.log(string.charCodeAt(3)) // D ASCII number is 51
let lastIndex = string.length - 1
console.log(string.charCodeAt(lastIndex))

**concat**

// concat(): it takes many substrings and creates concatenation.
// string.concat(substring, substring, substring)
let string = '30'
console.log(string.concat("Days", "Of", "JavaScript")) // 30DaysOfJavaScript
let country = 'Fin'
console.log(country.concat("land")) // Finland

**endswith**

// endsWith: it takes a substring as an argument and it checks if the string starts with that specified substring. It returns a boolean(true or false).
// string.endsWith(substring)
let string = 'Love is the best to in this world'
console.log(string.endsWith('world')) // true
console.log(string.endsWith('love')) // false
console.log(string.endsWith('in this world')) // true

let country = 'Finland'
console.log(country.endsWith('land')) // true
console.log(country.endsWith('fin')) // false
console.log(country.endsWith('Fin')) //  false

include

let string = '30 Days Of JavaScript'
console.log(string.includes('Days'))     // true
console.log(string.includes('days'))     // false
console.log(string.includes('Script'))     // true
console.log(string.includes('script'))     // false
console.log(string.includes('java'))     // false
console.log(string.includes('Java'))     // true

indexof

string.indexOf(substring)
let string = '30 Days Of JavaScript'
console.log(string.indexOf('D'))          // 3
console.log(string.indexOf('Days'))       // 3
console.log(string.indexOf('days'))       // -1
console.log(string.indexOf('a'))

last_indexof

let string = 'I love JavaScript. If you do not love JavaScript what else can you love.'
console.log(string.lastIndexOf('love'))       // 67
console.log(string.lastIndexOf('you'))        // 63
console.log(string.lastIndexOf('JavaScript')) // 38

length

let js = 'JavaScript'
console.log(js.length)        // 10
let firstName = 'Asabeneh'
console.log(firstName.length) // 8

**Arrays**

an array can store *multiple values*.Each value in an array has an *index*,and each index has *a reference in a memory address*.each value can be accessed by using their *indexes*.he index of an array starts from *zero*, and the index of the last element is less by one from the length of the array.

An array is a collection of different data types which are ordered and changeable(modifiable). An array allows storing duplicate elements and different data types. An array can be empty, or it may have different data type values.

• Array can have items of different data types

```
const arr = [
    'Asabeneh',
    250,
    true,
    { country: 'Finland', city: 'Helsinki' },
    { skills: ['HTML', 'CSS', 'JS', 'React', 'Python'] }
] // arr containing different data types
console.log(arr)
```

**how to create array**

• Using Array constructor

`const arr = Array()`

• Using square brackets([])

```
const arr = []
console.log(arr)
```

**Creating an array using split**

```
let js = 'JavaScript'
const charsInJavaScript = js.split('')

console.log(charsInJavaScript) // ["J", "a", "v", "a", "S", "c", "r", "i", "p", 
```

### Methods to manipulate array

There are different methods to manipulate an array. These are some of the available methods to deal with arrays:*Array, length, concat, indexOf, slice, splice, join, toString, includes, lastIndexOf, isArray, fill, push, pop, shift, unshift*

**Creating static values with fill**

fill: Fill all the array elements with a static value

```
const eightXvalues = Array(8).fill('X') // it creates eight element values filled with 'X'
console.log(eightXvalues) // ['X', 'X','X','X','X','X','X','X']
```

### Concatenating array using concat

concat:To concatenate two arrays.

```
const firstList = [1, 2, 3]
const secondList = [4, 5, 6]
const thirdList = firstList.concat(secondList)

console.log(thirdList) // [1, 2, 3, 4, 5, 6]

```

### Getting index an element in arr array

indexOf:To check if an item exist in an array. If it exists it returns the index else it returns -1.

### Getting last index of an element in array

lastIndexOf: It gives the position of the last item in the array. If it exist, it returns the index else it returns -1.

includes:To check if an item exist in an array. If it exist it returns the true else it returns false.

### Checking array

Array.isArray:To check if the data type is an array

### Converting array to string

toString:Converts array to string

### Joining array elements

join: It is used to join the elements of the array, the argument we passed in the join method will be joined in the array and return as a string. By default, it joins with a comma, but we can pass different string parameter which can be joined between the items.

```
const numbers = [1, 2, 3, 4, 5]
console.log(numbers.join()) // 1,2,3,4,5

const names = ['Asabeneh', 'Mathias', 'Elias', 'Brook']

console.log(names.join()) // Asabeneh,Mathias,Elias,Brook
console.log(names.join('')) //AsabenehMathiasEliasBrook
console.log(names.join(' ')) //Asabeneh Mathias Elias Brook
console.log(names.join(', ')) //Asabeneh, Mathias, Elias, Brook
console.log(names.join(' # ')) //Asabeneh # Mathias # Elias # Brook
```

### Slice array elements

Slice: To cut out a multiple items in range. It takes two parameters:starting and ending position. It doesn't include the ending position.

```
 const numbers = [1,2,3,4,5]

  console.log(numbers.slice()) // -> it copies all  item
  console.log(numbers.slice(0)) // -> it copies all  item
  console.log(numbers.slice(0, numbers.length)) // it copies all  item
  console.log(numbers.slice(1,4)) // ->
```

### Splice method in array

Splice: It takes three parameters:Starting position, number of times to be removed and number of items to be added.

\

```
const numbers = [1, 2, 3, 4, 5, 6]
	numbers.splice(3, 3, 7, 8, 9)
  console.log(numbers.splice(3, 3, 7, 8, 9))  // -> [1, 2, 3, 7, 8, 9] //it removes three item and replace three items
```

**Adding item to an array using push**

```
const arr  = ['item1', 'item2','item3']
arr.push('new item')
console.log(arr)
// ['item1', 'item2','item3','new item']
```

**Removing the end element using pop**

pop: Removing item in the end.

`const numbers = [1, 2, 3, 4, 5]
numbers.pop() // -> remove one item from the end
console.log(numbers) // -> [1,2,3,4]`

### Removing an element from the beginning

shift: Removing one array element in the beginning of the array.

```
const numbers = [1, 2, 3, 4, 5]
numbers.shift() // -> remove one item from the beginning
console.log(numbers) // -> [2,3,4,5]
```

### Add an element from the beginning

unshift: Adding array element in the beginning of the array.

```
const numbers = [1, 2, 3, 4, 5]
numbers.unshift(0) // -> add one item from the beginning
console.log(numbers) // -> [0,1,2,3,4,5]
```

### Reversing array order

reverse: reverse the order of an array.

```
const numbers = [1, 2, 3, 4, 5]
numbers.reverse() // -> reverse array order
console.log(numbers) // [5, 4, 3, 2, 1]
```

### Sorting elements in array

sort: arrange array elements in ascending order. Sort takes a call back function, we will see how we use sort with a call back function in the coming sections.

```
const webTechs = [
  'HTML',
  'CSS',
  'JavaScript',
  'React',
  'Redux',
  'Node',
  'MongoDB'
]

webTechs.sort()
console.log(webTechs) // ["CSS", "HTML", "JavaScript", "MongoDB", "Node", "React", "Redux"]

```

### Array of arrays

Array can store different data types including an array itself. Let us create an array of arrays

```
const frontEnd = ['HTML', 'CSS', 'JS', 'React', 'Redux']
 const backEnd = ['Node','Express', 'MongoDB']
 const fullStack = [frontEnd, backEnd]
 console.log(fullStack)   // [["HTML", "CSS", "JS", "React", "Redux"], ["Node", "Express", "MongoDB"]]
 console.log(fullStack.length)  // 2
 console.log(fullStack[0])  // ["HTML", "CSS", "JS", "React", "Redux"]
 console.log(fullStack[1]) // ["Node", "Express", "MongoDB"]
```

**Functions**

A function is a reusable block of code or programming statements designed to perform a certain task.

A function is declared by a function key word followed by a name, followed by parentheses (). A parentheses can take a parameter. If a function take a parameter it will be called with argument. A function can also take a default parameter.

### Function Declaration

Let us see how to declare a function and how to call a function.

### 

```
function functionName() {
  // code goes here
}
functionName()
```

A function can be declared or created in couple of ways:

- *Declaration function*
- *Expression function*
- *Anonymous function*
- *Arrow function*

### Function without a parameter and return

Function can be declared without a parameter.

**Example:**

```
function square() {
  let num = 2
  let sq = num * num
  console.log(sq)
}

square() // 4
```

### Function returning value

Function can also return values, if a function does not return values the value of the function is undefined.

```
function addTwoNumbers() {
      let numOne = 2
      let numTwo = 3
      let total = numOne + numTwo
      return total

  }

console.log(addTwoNumbers())
```

### Function with a parameter

In a function we can pass different data types(number, string, boolean, object, function) as a parameter.

```
functionName(parm1) // during calling or invoking one argument needed

function areaOfCircle(r) {
  let area = Math.PI * r * r
  return area
}

```

**Function with unlimited number of parameters**

Sometimes we do not know how many arguments the user going to pass. Therefore, we should know how to write a function which can take unlimited number of arguments. The way we do it has a significant difference between a function declaration(regular function) and arrow function. Let us see examples both in function declaration and arrow function.

A function declaration provides a function scoped arguments array like object. Any thing we passed as argument in the function can be accessed from arguments object inside the functions. Let us see an example

```
function sumAllNums() {
 console.log(arguments)
}

sumAllNums(1, 2, 3, 4)
```

```
function sumAllNums() {
  let sum = 0
  for (let i = 0; i < arguments.length; i++) {
    sum += arguments[i]
  }
  return sum
}

console.log(sumAllNums(1, 2, 3, 4)) // 10
```

**Unlimited number of parameters in arrow function**

Arrow function does not have the function scoped arguments object. To implement a function which takes unlimited number of arguments in an arrow function we use spread operator followed by any parameter name.

```
const sumAllNums = (...args) => {
 // console.log(arguments), arguments object not found in arrow function
 // instead we use a parameter followed by spread operator (...)
 console.log(args)
}

sumAllNums(1, 2, 3, 4)
// [1, 2, 3, 4]
```

**Anonymous Function**

Anonymous function or without name

`const anonymousFun = function() {
  console.log(
    'I am an anonymous function and my value is stored in anonymousFun'
  )
}`

### Expression Function

Expression functions are anonymous functions. After we create a function without a name and we assign it to a variable. To return a value from the function we should call the variable. Look at the example below.

```
const square = function(n) {
  return n * n
}

console.log(square(2)) //
```

### Self Invoking Functions

Self invoking functions are anonymous functions which do not need to be called to return a value.

```
(function(n) {
  console.log(n * n)
})(2)
```

### function with default parameters

Sometimes we pass default values to parameters, when we invoke the function if we do not pass an argument the default value will be used. Both function declaration and arrow function can have a default value or values.

```
function functionName(param = value) {
  //codes
}

```

**JavaScript Loops**

Loops are handy, if you want to run the same code over and over again, each time with a different value.

**Different Kinds of Loops**

JavaScript supports different kinds of loops:

- `for` - loops through a block of code a number of times
- `for/in` - loops through the properties of an object
- `for/of` - loops through the values of an iterable object
- `while` - loops through a block of code while a specified condition is true
- `do/while` - also loops through a block of code while a specified condition is true

# The For Loop

The `for` statement creates a loop with 3 optional expressions:

**Expression 1** is executed (one time) before the execution of the code block.

**Expression 2** defines the condition for executing the code block.

**Expression 3** is executed (every time) after the code block has been executed.

for (let i = 0; i < 5; i++) {

text += "The number is " + i + "<br>";

}

**The For In Loop**

The JavaScript `for in` statement loops through the properties of an Object:

const person = {fname:"John", lname:"Doe", age:25};

let text = "";

for (let x in person) {

text += person[x];

}

const person = {fname:"John", lname:"Doe", age:25};

let text = "";

for (let x in person) {

text += person[x];

}

# For In Over Arrays

The JavaScript `for in` statement can also loop over the properties of an Array:

const numbers = [45, 4, 9, 16, 25];

let txt = "";

for (let x in numbers) {

txt += numbers[x];

}

Do not use **for in** over an Array if the index **order** is important.

The index order is implementation-dependent, and array values may not be accessed in the order you expect.

It is better to use a **for** loop, a **for of** loop, or **Array.forEach()** when the order is important.

# Array.forEach()

The `forEach()` method calls a function (a callback function) once for each array element.

const numbers = [45, 4, 9, 16, 25];

let txt = "";

numbers.forEach(myFunction);

function myFunction(value, index, array) {

txt += value;

}

Note that the function takes 3 arguments:

- The item value
- The item index
- The array itself

# The For Of Loop

The JavaScript `for of` statement loops through the values of an iterable object.

It lets you loop over iterable data structures such as Arrays, Strings, Maps, NodeLists, and more:

**Looping over an Array**

const cars = ["BMW", "Volvo", "Mini"];

let text = "";

for (let x of cars) {

text += x;

}

**Looping over a String**

let language = "JavaScript";

let text = "";

for (let x of language) {

text += x;

}

# The While Loop

The `while` loop loops through a block of code as long as a specified condition is true.

while (

*condition*

) {

*// code block to be executed*

}

# The Do While Loop

The `do while` loop is a variant of the while loop. This loop will execute the code block once, before checking if the condition is true, then it will repeat the loop as long as the condition is true.

# Syntax

do {  *// code block to be executed*}while (*condition*);

**JavaScript Objects**

Objects are variables too. But objects can contain many values.

The values are written as **name:value** pairs (name and value separated by a colon).

**Object Definition**

You define (and create) a JavaScript object with an object literal:

const person = {firstName:"John", lastName:"Doe", age:50, eyeColor:"blue"};

An object definition can span multiple lines:

const person = {

firstName: "John",

lastName: "Doe",

age: 50,

eyeColor: "blue"

};

**Object Properties**

The **name:values** pairs in JavaScript objects are called **properties**:

| Property | Property Value |
| --- | --- |
| firstName | John |
| lastName | Doe |
| age | 50 |
| eyeColor | blue |

**Accessing Object Properties**

You can access object properties in two ways:

*objectName.propertyName*

or 

*objectName["propertyName"]*

**Object Methods**

Objects can also have **methods**.

Methods are **actions** that can be performed on objects.

Methods are stored in properties as **function definitions**.

| Property | Property Value |
| --- | --- |
| firstName | John |
| lastName | Doe |
| age | 50 |
| eyeColor | blue |
| fullName | function() {return this.firstName + " " + this.lastName;} |

A method is a function stored as a property.

**Accessing Object Methods**

You access an object method with the following syntax:

*objectName.methodName()*

example

name = person.fullName();
