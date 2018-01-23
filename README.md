> *Things I wish I knew in the start of my frontend-development-carreer*

> This repo consists of list of various other resources on internet along with my notes on various topics related to frontend developement so that it will help everyone to either build up or brush up their basic skillset.

## Web Development Ecosystem

- [The Big Picture](https://learn-anything.xyz/web-development)
- [Developer Roadmap](https://github.com/kamranahmedse/developer-roadmap)

## Javascript Related Videos

- [Functional Programming in JavaScript](https://www.youtube.com/watch?v=BMUiFMZr7vk&list=PL0zVEGEvSaeEd9hlmCXrk5yUyqUag-n84)
  - A 12 video fun series by **fun fun function**

## React

- [React Official Docs](https://reactjs.org/)
- [Create React App](https://github.com/facebookincubator/create-react-app)
- [ReactJS Basics](https://www.youtube.com/watch?v=JPT3bFIwJYA)
- [Awesome React](https://github.com/enaqx/awesome-react)

## Node

- [Download Node](https://nodejs.org/en/download/)
- [Node Official Docs](https://nodejs.org/en/docs/)
- [What is NodeJs](https://www.youtube.com/watch?v=pU9Q6oiQNd0)
- [What is NodeJs by "The Coding Train"](https://www.youtube.com/watch?v=RF5_MPSNAtU)
- [Awesome Node](https://github.com/sindresorhus/awesome-nodejs)

## The Awesome List

- [Awesome](https://github.com/sindresorhus/awesome)

## Youtube Vids to Watch

- [Myth of the "Real JS Developer"](https://www.youtube.com/watch?v=Xt5qpbiqw2g)

## Learn About Git & Github

- [What is Github](https://www.youtube.com/watch?v=w3jLJU7DT5E)
- [Github in 20 Mins](https://www.youtube.com/watch?v=Y9XZQO1n_7c)
- [Github Tutorial](https://www.youtube.com/watch?v=0fKg7e37bQE)

## Learn about Markdown

- [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)

## Misc

- [Stackoverflow Developer Survey](https://insights.stackoverflow.com/survey/2017)

## Jargons to Google and Learn

- ES5, ES6 and ES7 Comparison
- Package Managers
	- NPM
	- YARN
- Module Bundlers
	- Webpack
- StackOverflow
- Regex
- JSON
- JSX (JavaScript Styled XML)
- Object Manipulation
- Array Manipulation
- String Manipulation
- React Component Life Cycle
- DevOps

## Resource wise

- Algorithm Visualization
https://www.cs.usfca.edu/~galles/visualization/Algorithms.html

### Github

- [Technical Interview Megarepo](https://github.com/jdsutton/Technical-Interview-Megarepo)
- [Node JS](https://elemefe.github.io/node-interview/#/)
- [Node JS](https://github.com/ElemeFE/node-interview)
- [YDKJS](https://github.com/getify/You-Dont-Know-JS)
- [JS Interview Review](https://github.com/adam-s/js-interview-review)
- [Interview/DS & Alg](https://github.com/alex-cory/Interviews)

### Youtube

- [Fizz buzzkill - Answering tricky JS interview questions](https://www.youtube.com/watch?v=cMxI8n393ZM)
- [Live Mock Technical Interview - React & JavaScript](https://www.youtube.com/watch?v=UdiXLzBie9g)
- [Live Mock Technical Interview - JavaScript](https://www.youtube.com/watch?v=057Rs6CgJnY)
- [Functional Programming with JS](https://www.youtube.com/watch?v=BMUiFMZr7vk&index=1&list=PL0zVEGEvSaeEd9hlmCXrk5yUyqUag-n84)
- [Object Creation JS](https://www.youtube.com/watch?v=GhbhD1HR5vk&index=1&list=PL0zVEGEvSaeHBZFy6Q8731rcwk0Gtuxub)
- [Big O Notation](https://www.youtube.com/watch?v=v4cd1O4zkGw)
- [What the heck is Event Loop ?](https://www.youtube.com/watch?v=8aGhZQkoFbQ&t=2s)
- https://www.youtube.com/watch?v=nX0ajFKB2E0
- https://www.youtube.com/watch?v=2MYBP-ZD1tk

### Egghead

### Medium

- [Frontend in 2018](https://blog.logrocket.com/what-im-looking-for-from-frontend-in-2018-2f1de300b548)
- [JavaScript Modules: A Beginner’s Guide](https://medium.freecodecamp.org/javascript-modules-a-beginner-s-guide-783f7d7a5fcc?source=latest---------1)
- [JavaScript Modules Part 2: Module Bundling](https://medium.freecodecamp.org/javascript-modules-part-2-module-bundling-5020383cf306)
- [I just got a developer job at Facebook. Here’s how I prepped for my interviews.](https://medium.freecodecamp.org/software-engineering-interviews-744380f4f2af)

## Checklist of basic stuff

Things that you should have clear definition / distinction /analogy/examples of:

- Paradigms of JavaScript
  - Object Oriented
  - Functional

- Classes
- Prototypes
- Classes Vs Prototypes
- "use strict"
- var/let/const
- Scope (Block and function)
- this keyword
- binding
- Closure
  - A closure is an inner function that has access to the outer (enclosing) function’s variables—scope chain. The closure has three scope chains: it has access to its own scope (variables defined between its curly brackets), it has access to the outer function’s variables, and it has access to the global variables.

  - The inner function has access not only to the outer function’s variables, but also to the outer function’s parameters. Note that the inner function cannot call the outer function’s arguments object, however, even though it can call the outer function’s parameters directly.

  - You create a closure by adding a function inside another function.
- Hoisting
- IIFE (Immediately Invoked Function Expression)
- Undefined vs Null
  - undefined means a variable has been declared but has not yet been assigned a value. On the other hand, null is an assignment value. It can be assigned to a variable as a representation of no value.
  - Also, undefined and null are two distinct types: undefined is a type itself (undefined) while null is an object.
  - Unassigned variables are initialized by JavaScript with a default value of undefined. JavaScript never sets a value to null. That must be done programmatically.

- JavaScript Object Prototypes
  - Every JavaScript object has a prototype. The prototype is also an object.
  - All JavaScript objects inherit their properties and methods from their prototype.
  - All JavaScript objects inherit the properties and methods from their prototype.
  - Objects created using an object literal, or with new Object(), inherit from a prototype called Object.prototype.
  - Objects created with new Date() inherit the Date.prototype.
  - The Object.prototype is on the top of the prototype chain.
  - All JavaScript objects (Date, Array, RegExp, Function, ....) inherit from the Object.prototype.

```
  function Person(first, last, age, eyecolor) {
    this.firstName = first;
    this.lastName = last;
    this.age = age;
    this.eyeColor = eyecolor;
  }

  var myFather = new Person("John", "Doe", 50, "blue");
  var myMother = new Person("Sally", "Rally", 48, "green");
```

- map/filter/reduce
- for loops
  - standard for-loop
  - for-in
  - for-each
  - for-of

- new keyword
- object creation/manipulation
- array creation/manipulation

- REST / SOAP
- MVC Architecture
- Sorting Algorithms
  - Quick Sort
  - Merge Sort
  - Insertion Sort

- Big O Notation
  - Space and time complexity
  - A tool we use for talking about how much time an algorithm takes to run or how much memory a data structure takes up in our computer.
  - This function runs in O(1) time (or "constant time") relative to its input.
  - This function runs in O(n) time (or "linear time"), where n is the number of items in the array.
  - Thus this function runs in O(n^2)time (or "quadratic time").

- React
  - React 16's new features
    - New render return types: fragments and strings
    - Better error handling with error boundaries
    - Portals
    - Better server-side rendering
    - Support for custom DOM attributes
    - Reduced file size
    - New core architecture "Fiber"
    - WIP - async rendering

- Shim
  - In computer programming, a shim is a small library that transparently intercepts an API, changing the parameters passed, handling the operation itself, or redirecting the operation elsewhere. 
  - A shim that mimics a future API providing fallback functionality to older browsers.
- Polyfill
  - A polyfill, or polyfiller, is a piece of code (or plugin) that provides the technology that you, the developer, expect the browser to provide natively. Flattening the API landscape if you will.
  - https://remysharp.com/2010/10/08/what-is-a-polyfill/

- Module Bundler [Browserify/RequireJS/Webpack]
  - Module bundling is simply the process of stitching together a group of modules (and their dependencies) into a single file (or group of files) in the correct order.
  - Webpack provides some useful features like “code splitting” — a way to split your codebase into “chunks” which are loaded on demand.

- Minification
  - Minification is the process of removing unnecessary characters from source code (e.g. whitespace, comments, new line characters, etc.), in order to reduce the overall size of the content without changing the functionality of the code.

- Transpiler [Babel]

---

- Decorators
- Generators
  - Generators are (kind of) pausable functions in JavaScript. Another word for them is co-routines. They are used (among other things) to manage async operations,and play very well with promises. 
- Asynchronous Programming
  - AJAX
  - HTTP
  - Callbacks
  - Async/await
- MicroServices
- Dependeny Injection
  - Dependency injection (here shown using JavaScript) is a software design pattern that is primarily to make code unit testable, by moving the responsibility for getting dependencies outside the code that depends on it. It does require some restructuring of your application, which feels a bit wrong to do just to get testability, but it’s an otherwise remarkably simple pattern that gets the job done. 
- Dependeny Injection without classes
- NameSpaces
  - In many programming languages, namespacing is a technique employed to avoid collisions with other objects or variables in the global namespace. They're also extremely useful for helping organize blocks of functionality in your application into easily manageable groups that can be uniquely identified.

  - In JavaScript, namespacing at an enterprise level is critical as it's important to safeguard your code from breaking in the event of another script on the page using the same variable or method names as you are. With the number of third-party tags regularly injected into pages these days, this can be a common problem we all need to tackle at some point in our careers. 


# Code Snippets

```
	// check palindrome
	function isPalindrome(string) {
		return string === string.split('').reverse().join('');
	}
	console.log(isPalindrome("level"), isPalindrome("foo"));

	// count the no of specified character
	function getCountOfChar(char, string) {
		let count = 0;
		for (let i = 0; i < string.length; i++) {
			(string[i] === char) ? count++ : null;
		}
		return count;
	}
	console.log(getCountOfChar("c", "chocofun"));
	console.log(getCountOfChar("f", "chocofun"));

	//find duplicate
	let sampleArray = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 5, 6, 7, 99, 99, 101, 99, 99];
	// let duplicate;
	function findDuplicate(array) {
		let dup = [];
		let obj = {};
		for (let i = 0; i < array.length; i++) {
			if (obj[array[i]]) {
				dup.push(array[i]);
			}
			else {
				obj[array[i]] = 'unique';
			}
		}
		return dup;
	}
	console.log(findDuplicate(sampleArray));

	// find output
	var dummy = 'batman';
	console.log(dummy);
	function log() {
		console.log(dummy); //undefined
		var dummy = 'superman';
		console.log(dummy);
	}
	log();


	// currying example 1
	let dragon =
		name =>
			size =>
				element =>
					name + ' is a ' +
					size + ' dragon that breathes ' +
					element + '!'

	let output = dragon('drogo')('large')('fire');
	console.log(output);

	// currying example 2
	const dragons = [
		{ name: 'fluffykins', element: 'lighting' },
		{ name: 'noomi', element: 'lighting' },
		{ name: 'karo', element: 'fire' },
		{ name: 'doomer', element: 'timewrap' },
	];
	const hasElement = (element) => (object) => {
		return object.element === element;
	};
	const lightingDragons = dragons.filter(hasElement('lighting'));
	console.log(lightingDragons);

	// confusing this example
	// sound = 'ding-dong-ding';
	let dog = {
		sound: 'woof',
		talk: function () {
			console.log(this.sound);
		}
	}
	dog.talk(); //woof
	// let alienDog = dog.talk;
	// equivalent to 
	// let alienDog = function () {
	//   console.log(this.sound);
	// }
	// alienDog(); // undefined

	// solution
	let alienDog = dog.talk.bind(dog);
	alienDog();
```