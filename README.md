# Note_Modern-JavaScript-From-The-Beginning

Note for a course on Udemy
</br>
*Modern JavaScript From The Beginning* https://www.udemy.com/modern-javascript-from-the-beginning/

The title and some of key point of the course, to help recall the course. Also can be used as index.
### Section 1: Intro & Getting Started
- Visual Studio Code Setup

### Section 2: JavaScript Language Fundamentals
- Section Intro & File Setup
```
  <script src="app.js"></script>
```
- Using The Console
	- chrome console
			can write js directly code from console
	-	console.log() and some other function
  - multi line comments
- Variables - var, let & const
- Data Types in JavaScript
	- 6 Primitive Data Types
	- Reference Data Types
	- Dynamically Typed Language
- Type Conversion
	- to String: String() / .toString()
	-	to number Number() ／ parseInt ／ parseFloat
	-	Type Conversion
- Number The Math Object
	-	Simple math with numbers
	-	Math Object and function
		- PI / E / round() / ceil() / floor() / sqrt() / abs() / pow() / min() / max()
- String Methods & Concatenation
	- Concatenation: + / concat()
	- Append: +=
	- Escaping: \
	- Length
	- indexOf() / charAt() / substring() / slice() / split() / replace() / includes()
- Template Literals
	-	Without template strings (es5): ' Name: ' + name
	-	With template strings (es6): `Name: ${name}`
- Arrays & Arrays Methods
	- [] / new Array()
	- Array.isArray()
	- indexOf()
	- push() / unshift() / pop() / shift()
	- concat() / sort() / find()
- Object Literals
	-	Create Object: {}
	- Get specific value: . / []
- Dates & Times
	-	Initial Date: new Date()
	-	change Date: new Date('9/10/1981')
	-	get
	-	set
- If Statements & Comparison Operators
	-	format
  - OPERATORS
		- == value
		- === value and type
  - LOGICAL OPERATORS: && / || / ?:
- Switches
- Function Declarations & Expressions
	-	Function Declarations: function name(){}
  - Function Expressions: const name = function(){}
  - Immidiately Invokable Function - IIFEs: (function(name){console.log('Hello '+ name);})('Name');
  - Property Methods: function in an object called method
- General Loops
	-	FOR / WHILE / DO WHILE
  - FOREACH: array.forEach(function(){});
  - MAP: const x = array.map(function(){});
  - FOR IN LOOP: for(let x in array){}
- A Look At The Window Object
	-	WINDOW METHODS / OBJECTS / PROPERTIES
	- window.console.log();
	- alert() / prompt() / confirm
	- PROPERTIES
	- Location Object
	- History Object
	- Navigator Object
- Block Scope With let & const
	-	let, const work like other language
	-	var is less secure: var inside function scope can change global scope var with the same name
