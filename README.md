# js-technique-and-topic

## Javascript
JavaScript is a prototype-based language, which means that it uses prototypes to inherit properties and methods from one object to another. In JavaScript, objects can be linked to other objects, forming a prototype chain. Since JavaScript is a loosely typed language, you are not required to correctly predict the kind of data that will be kept in a variable.
Dynamically typed languages like Python and JavaScript offer more flexibility, but they might lead to runtime errors due to unexpected type mismatches. On the other hand, statically typed languages are more verbose, which developers might sometimes find inconvenient, especially when rapid prototyping is required.

### Mention some Browser Engine (also refer as Rendering Engine) name?

* **Webkit** developed by Apple (used by *Safari*, *Chrome*)
* **Gecko** developed by Mozila (used by *Firefox*)
* **Blink** developed by Google (*Chrome* and all other Chromium-based browsers, notably *Microsoft Edge*, *Brave*, *Vivaldi*, *Samsung Internet* and *Opera*)
  
### Mention some javascript engine name?

* **Chakra** written in c++ for microsoft used by Edge browser
* [**V8**](https://v8.dev/) is Google’s open source high-performance JavaScript and WebAssembly engine, written in C++. It is used in Chrome and in Node.js, among others. It implements [ECMAScript](https://tc39.es/ecma262/) and [WebAssembly](https://webassembly.github.io/spec/core/), and runs on Windows 7 or later, macOS 10.12+, and Linux systems that use x64, IA-32, ARM, or MIPS processors. V8 can run standalone, or can be embedded into any C++ application.
* [**SpiderMonkey**](https://spidermonkey.dev/) is Mozilla’s JavaScript and [WebAssembly](https://webassembly.github.io/spec/core/) Engine, used in Firefox, Servo and various other projects. It is written in C++, Rust and JavaScript. You can embed it into C++ and Rust projects, and it can be run as a stand-alone shell. It can also be compiled to WASI; see our online demo.
* [**JavaScriptCore**](https://developer.apple.com/documentation/javascriptcore) written in Objective-c, used by Safari browser.

* [**QuickJs**](https://github.com/bellard/quickjs) is an embeddable JS engine written in C.
* [**Hermes**](https://github.com/facebook/hermes/) is a JavaScript engine optimized for fast start-up of **React Native** apps.
* [**Duktape**](https://github.com/svaarala/duktape) - embeddable Javascript engine with a focus on portability and compact footprint.

### Mention some javascript Runtime environment?

* [**Node.js**](https://github.com/nodejs/node) is an open-source, cross-platform JavaScript runtime environment.
* [**Deno**](https://deno.com/) Next-generation JavaScript runtime
  .Secure by default
  .Native support for TypeScript and JSX
  .Testing, linting, formatting, and more out of the box
  .High performance async I/O with Rust and Tokio
  .Backwards compatible with Node.js and npm
* [**Bun**](https://github.com/oven-sh/bun) At its core is the Bun runtime, a fast JavaScript runtime designed as a drop-in replacement for Node.js. It's written in **Zig** and powered by **JavaScriptCore** under the hood, dramatically reducing startup times and memory usage.
* [**LLRT**](https://github.com/awslabs/llrt) LLRT (Low Latency Runtime) is a lightweight JavaScript runtime designed to address the growing demand for fast and efficient Serverless applications. LLRT offers up to over 10x faster startup and up to 2x overall lower cost compared to other JavaScript runtimes running on AWS Lambda. It's built in Rust, utilizing QuickJS as JavaScript engine, ensuring efficient memory usage and swift startup.
* [**txiki**](https://github.com/saghul/txiki.js) A tiny JavaScript runtime
### [Specification](https://tc39.es/)
| ECMAScript Version | Release Year | Notable Features                              |
|--------------------|--------------|-----------------------------------------------|
| ES1                | 1997         | Initial version of ECMAScript.                |
| ES2                | 1998         | Addition of try/catch statement, and method toLocaleString(). |
| ES3                | 1999         | Introduction of new features like regular expressions, exceptions, and more robust error handling. |
| ES5                | 2009         | Added 'strict mode', JSON support, getters and setters, and more array methods like forEach(), map(), and reduce(). |
| ES6 / ES2015       | 2015         | Major update with significant additions including arrow functions, classes, template literals, let and const keywords, and more. |
| ES7 / ES2016       | 2016         | Introduction of features like the exponentiation operator (`**`) and Array.prototype.includes(). |
| ES8 / ES2017       | 2017         | Added async/await, Object.values/Object.entries, String padding, and more. |
| ES9 / ES2018       | 2018         | Introduced features like asynchronous iteration, Rest/Spread Properties, and Promise.prototype.finally(). |
| ES10 / ES2019      | 2019         | Added features like Array.prototype.flat(), Array.prototype.flatMap(), String.prototype.trimStart()/trimEnd(), and optional catch binding. |
| ES11 / ES2020      | 2020         | Introduced features like BigInt, Promise.allSettled(), String.prototype.matchAll(), and globalThis. |
| ES12 / ES2021      | 2021         | Added features like String.prototype.replaceAll(), Numeric separators, Logical Assignment Operators, and Promise.any(). |
| ES13 / ES2022      | 2022         | Proposed features include Array.prototype.groupBy(), Object.observe(), and more. |

### Mention some *Transpiler* AKA *Module Bundler*
javaScript transcompiler that is mainly used to convert ECMAScript 2015+ code into backwards-compatible JavaScript code that can be run by older JavaScript engines. It allows web developers to take advantage of the newest features of the language.

* [Vite](https://vitejs.dev/)
* [Rollup](https://rollupjs.org/)
* [Webpack](https://webpack.js.org/)
* [Babel](https://babeljs.io/)
* [TurboPack](https://turbo.build/)
* [ESBuild](https://esbuild.github.io/)
* [SWC](https://swc.rs/)

### WebSocket
- peer-server-peer comunication
- protocol `WS` / `WSS`
### [WebRTC](https://webrtc.org/getting-started/overview)
- peer to peer comunication
- protocol `UDP`

### [Web API](https://developer.mozilla.org/en-US/docs/Web/API)
### Mention some Standard Library
* [**Core-js**](https://github.com/zloirock/core-js) polyfills library.
* [**stdlib**](https://github.com/stdlib-js/stdlib) (/ˈstændərd lɪb/ "standard lib") is a standard library, with an emphasis on numerical and scientific computation, written in JavaScript (and C) for execution in browsers and in Node.js.
* [RxJS](https://github.com/ReactiveX/rxjs) A reactive programming library for JavaScript
* [lodash](https://github.com/lodash/lodash)
* [moment](https://github.com/moment/moment)
* [async](https://github.com/caolan/async)
* [collect.js](https://github.com/ecrmnn/collect.js)

### Some Tool
* [**EsLint**](https://eslint.org/)
* [jsLint](https://www.jslint.com/)
* [**TypeScript**](https://www.typescriptlang.org/docs/handbook/) is super-set of javascript.
* [**tsConfig**](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html)
### Primitive data type and non primitive data type?
- **Primitive** The predefined data types provided by JavaScript language are known as primitive data types. Primitive data types are also known as in-built data types.
    1. **String**. > typeof 'hello world' // string;
    2. **Number**. > typeof 123 // number
    3. **Bigint**. > typeof 2n // bigint
    4. **Boolean**. > typeof true // boolean
    5. **Undefined**. > typeof undefined // undefined
    6. **Null**. > typeof null // object
    7. **Symbol**. > typeof Symbol('test') // symbol
- **Non Primitive** The data types that are derived from primitive data types of the JavaScript language are known as non-primitive data types. It is also known as derived data types or reference data types.
    1. **Object**. > typeof {test:123} // object
    2. **Function** > typeof function(){} // function
    3. **Array**. > typeof [1,2,3] // object
    4. [**Map**](https://javascript.info/map-set) // typeof new Map([['a',1],['b',2]); // object
    5. [**Set**](https://javascript.info/map-set)
### Mention some [Standard built-in objects](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects)
#### Standard objects by category
1. **Value properties** :These global properties return a simple value. They have no properties or methods.
    - `globalThis`
    - `Infinity`
    - `NaN`
    - `undefined`
2. **Fundamental objects** :These objects represent fundamental language constructs.
    - `Object`
    - `Function`
    - `Boolean`
    - `Symbol`
3. **Numbers and Dates** :These are the base objects representing numbers, dates, and mathematical calculations.
    - `Number`
    - `BigInt`
    - `Math`
    - `Date`
4. **Function properties** : These global functions—functions which are called globally, rather than on an object—directly return their results to the caller.
    - `eval()`
    - `isFinite()`
    - `isNaN()`
    - `parseFloat()`
    - `parseInt()`
    - `decodeURI()`
    - `encodeURI()`
5. **Text processing** :These objects represent strings and support manipulating them.
    - `String`
    - `RegExp`
6. **Indexed collections** : These objects represent collections of data which are ordered by an index value.
    - [**Array**](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)
    - [Read More](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects#indexed_collections)
7. **Keyed collections** :These objects represent collections which use keys.
    - [**Map**](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map)
    - [**Set**](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set)
    - [WeakMap](/#)
    - [WeakSet](/#)
8. **Control abstraction objects** :Control abstractions can help to structure code, especially async code (without using deeply nested callbacks, for example).
    - [**Iterator**](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Iterator)
    - AsyncIterator
    - [**Promise**](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)
    - GeneratorFunction
    - AsyncGeneratorFunction
    - [**Generator**](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Generator)
    - AsyncGenerator
    - [**AsyncFunction**](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/AsyncFunction)
9. **Reflection** :
    - [**Reflect**](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Reflect)
    - [**Proxy**](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy)
[Read More](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects)
### Mention some array method which are modified orginal `array` and mention some method which are not modifying orginal `array`
**Modifying Orginal Array**
* `arr.pop()` remove from last index and return `removed item`
* `arr.push()` insert in last index and return `length of modified array`
* `arr.unshift()` insert in first index and return `length of modified array`
* `arr.shift()` remove from fisrt index and return `removed item`
* `arr.splice(fromIndex,length)` remove from index to length and return `new array with removed values`
* `arr.reverse()` reverse the original array and return `reversed array`

**Not modifying Orginal Array**
* `[1,2,3].map(e=>e*2)` return new array [2,4,6]
* `[2,4,6].filter(e=>e>2` return new array [6]
* `[1,2,3,4,5].slice(startIndex,endIndex)` return new array with the new slice, **endIndex is not include**
* `[1,2,3].concat([4,5])` merge the array with existing one and return new array
### Type conversion in javascript
**Numeric Conversion** – Occurs in math operations. Can be performed with Number(value).
| Value       | Becomes                              |
|-------------|--------------------------------------|
| `undefined`   |`NaN`                                  |
| `null`       | 0                                    |
| `true` / `false`| 1 / 0                                |
| `string`     | The string is read “as is”, whitespaces (includes spaces, tabs \t, newlines \n etc.) from both sides are ignored. An empty string becomes 0. An error gives NaN. |

**Boolean Conversion** – Occurs in logical operations. Can be performed with Boolean(value).

Follows the rules:

| Value                             | Becomes                              |
|-----------------------------------|--------------------------------------|
| `0`, `null`, `undefined`, `NaN`, ""      | false                                |
| any other value                  | true                                 |

[Read details](https://javascript.info/type-conversions)

### What is iterable?
(**index value**)

Those object are working with `for...of` are iterable. Iterable objects like `arrays`, `strings`, `sets`, `maps`, etc. Now if `[Symbol.iterator]` implemented in object, it also work as iterable 
```js
let range = {
  from: 1,
  to: 5
};

// 1. call to for..of initially calls this
range[Symbol.iterator] = function() {

  // ...it returns the iterator object:
  // 2. Onward, for..of works only with the iterator object below, asking it for next values
  return {
    current: this.from,
    last: this.to,

    // 3. next() is called on each iteration by the for..of loop
    next() {
      // 4. it should return the value as an object {done:.., value :...}
      if (this.current <= this.last) {
        return { done: false, value: this.current++ };
      } else {
        return { done: true };
      }
    }
  };
};

// now it works!
for (let num of range) {
  console.log(num); // 1, 2, 3, 4, 5
}
```
[Read details](https://javascript.info/iterable)

### What is emunarable?
(**key value**)
Those object are working with `for...in` are enumarable.
```js
const person = {
  name: 'John',
  age: 30,
  occupation: 'Developer'
};

for (const key in person) {
  console.log(`${key}: ${person[key]}`);
}
```
### Hoisting

JavaScript Hoisting refers to the process whereby the interpreter appears to move the declaration of functions, variables, classes, or imports to the top of their scope, prior to execution of the code.
### [Constructor in Javascript](https://www.codecademy.com/resources/docs/javascript/constructors)
It’s preferred to capitalize a constructor function.
```js
function Car(make, model, year) {
  this.make = make;
  this.model = model;
  this.year = year;
}

var car1 = new Car('Chevy', 'Blazer', 2015);
var car2 = new Car('Ford', 'Taurus', 2018);

console.log('Car 1 is a ' + car1.year + ' ' + car1.make + ' ' + car1.model);
// Output: Car 1 is a 2015 Chevy Blazer

console.log('Car 2 is a ' + car2.year + ' ' + car2.make + ' ' + car2.model);
// Output: Car 2 is a 2018 Ford Taurus
```
### Higher Order Function

In JavaScript, a higher-order function is a function that takes another function as an argument or returns a function as its result. Higher-order functions are a fundamental concept in functional programming and enable powerful and flexible programming paradigms such as function `composition`, `currying`, and `lazy evaluation`.

### What is `Function Expression`?
Function expressions are when you create a function and assign it to a variable. The function is anonymous, which means it doesn’t have a name.
```js
function funcDeclaration() {
    return 'A function declaration';
}

let funcExpression = function () {
    return 'A function expression';
}
```
#### Difference between *function expression* and *function decleration*?
There are a few key differences between function expressions and function declarations:

- Function declarations are ***hoisted***, while function expressions are not. This means that you can call a function declaration before it is defined, but you cannot do this with a function expression.
- With function expressions, you can use a function immediately after it is defined. With function declarations, you have to wait until the entire script has been parsed.
- Function expressions can be used as an argument to another function, but function declarations cannot.
- Function expressions can be anonymous, while function declarations cannot.

* [when-to-use-a-function-expression-vs-function-declaration](https://www.sitepoint.com/when-to-use-a-function-expression-vs-function-declaration/)
* [function-expressions](https://javascript.info/function-expressions)
### Describe "use stict"?
"Use strict" is like setting rules for your JavaScript code. It makes sure your code follows stricter guidelines, catching mistakes that could cause problems later on. It helps you write cleaner, safer code by enforcing better coding practices.

Without "use strict":

```js
// This code will run without any warnings
x = 10; // No need to declare 'x' with var, let, or const
console.log(x); // Outputs 10
```
With "use strict":

```js
"use strict";
// This code will show an error
x = 10; // Error: 'x' is not defined
console.log(x); // This line won't be executed due to the error above
```
> Note: Javascript `ES6 Module` and `Class` are built-in strict mode.
### Immediately Invoked Function Expressions (IIFE)
function expression that annonymouse and called immediately after its defined.
```js
(function () {
    // code in here
}());
```
and it's useful for maintainable module code with out side effecting as it is fall into a function scope with it's property and methods.

```js
let myModule = (function () {
    let privateMethod = function () {
        console.log('A private method');
    },
    someMethod = function () {
        console.log('A public method');
    },
    anotherMethod = function () {
        console.log('Another public method');
    };

    return {
        someMethod: someMethod,
        anotherMethod: anotherMethod
    };
}());
```
### Closure in javascript
In JavaScript, a closure is a combination of a function and the lexical environment within which that function was declared. This lexical environment consists of any variables that were in scope at the time the closure was created.
**Example**
```js
function queryBuilder() {
  let query = '';

  return function(statement) {
    // query variable is in its parent scope or outer scope or in lexical scope
    // it accessable even if outer function is executed
    query+=statement;
    if(statement.indexOf(';') > -1) {
      let re = query;
      query='';
      return re;
    }
    return 'building....';
  }
}

const query = queryBuilder();
console.log(query('select'));
console.log(query(' * '));
console.log(query(' from '));
console.log(query(' user where id=1'));
console.log(query(' limit 1;')); // output 'select * from user where id=1 limit 1;'
```
### Currying in javascript
Currying is a functional programming technique in JavaScript where a function with multiple arguments is transformed into a sequence of nested functions, each taking a single argument. The curried function returns a new function for each argument until all arguments have been supplied, at which point it executes and returns the result.

**As Usual Implementation**
```js

const totalPrice = (price,taxAmount) => price+(price*taxAmount);

console.log(totalPrice(30,0.15)); // output 34.5
console.log(totalPrice(100,0.15)); // output 115

```
**Currying Implementation**
```js

const tax = (taxAmount) => (price) => price+(price*taxAmount);

const totalPrice= tax(0.15);

console.log(totalPrice(30)); // output 34.5
console.log(totalPrice(100)); // output 115
```

### Composition in javascript

Function composition is a fundamental concept in functional programming where two or more functions are combined to produce a new function. The output of one function becomes the input of another, allowing you to create complex behavior by chaining together simpler functions.

**Example**

```js
const split = str => str.split('');
const reverse = arr => arr.reverse();
const join = arr => arr.join('');
const compose = (...functions) => (str) => functions.reduce((acc,fn) => fn(acc),str);

// reverse a string
const composedFunction= compose(split,reverse,join);
console.log(composedFunction('hello')) // output 'olleh'

```
### Lazy Evalution
Lazy evaluation is a strategy where an expression is not evaluated until its value is actually needed. In JavaScript, this can be achieved using higher-order functions or by using generator functions. This technique can help improve performance and optimize memory usage in scenarios where computations are resource-intensive or when dealing with potentially infinite data sets.

**Explaination**
Suppose your script compute only array of size two, but given a large array dataset. How do you handle this situation, simple answer is by using `Lazy Evalution` strategy.
```js
function makeSmallDataSet(longDataSet) {
  const chunks = [];
  for (let i = 0; i < longDataSet.length; i += 2) {
    const chunk = longDataSet.slice(i, i + 2);
      chunks.push(chunk);
  }
  return chunks;
}

// Example long array
const longArray = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12];

// Split the long array into 2x2 arrays
const intermediateDataSet = makeSmallDataSet(longArray);
console.log(intermediateDataSet); // [ [ 1, 2 ], [ 3, 4 ], [ 5, 6 ], [ 7, 8 ], [ 9, 10 ], [ 11, 12 ] ]

function lazyEvalution(data){
    const chunks = makeSmallDataSet(data);
    const cpuIntesiveTask= function (stream){
      // now process two size array with cpu intensive function
    }
    for(let chunk of chunks){
        cpuIntesiveTask(chunk);
    }
}
```
### Pipeline in Javascript
In JavaScript, a pipeline is a sequence of functions where the output of one function becomes the input of the next. It's a common pattern used for data transformation and processing, allowing you to compose complex operations by chaining together simpler functions.

**Example**
```js
const split = str => str.split('');
const reverse = arr => arr.reverse();
const join = arr => arr.join('');
const makePipeline = (...functions) => (str) => functions.reduce((acc,fn) => fn(acc),str);

const startPiping= makePipeline(split,reverse,join,split);
console.log(startPiping('hello')); // output [ 'o', 'l', 'l', 'e', 'h' ]
```

### How to make Object immutable?
with `Object.freeze()` method you can set any object to immutable.
```js
const arr = [1, 2, 3, 4, 90];
Object.freeze(arr);
arr.pop(); // Throw TypeError
```
Only specific property to make immutable
```js
const person={
  name:'John',
  age:30
}
Object.defineProperty(person,'name',{
  value:'Jane',
  writable:false
});
person.name='Jane'; // TypeError: Cannot assign to read only property 'name' of object
```
### Implementing an Enum in JavaScript
A way to implement an enum in JavaScript by creating an Object of key/value pairs and using the Object.freeze() function to make it immutable:

```js
  const directions = Object.freeze({ 
    north: 0,
    south: 1,
    east: 2,
    west: 3
  });
```
### ProtoType in javascript
Every data types in js are extended from `Object` except `null`
```js
const arr= [1,2,3];
console.log(arr.__proto__);
// it log all array functionality
console.log(arr.__proto__.__proto__);
// it log all object functionality
console.log(arr.__proto__.__proto__.__proto__);
// it log null and proto chaining is stop
```

### Recursion in javascript

### Why **Tail Recursion** is optimal from pure **Recursion**?

### What will print when `console.log()` execute and why?

### what are the difference between `var`, `let`, and `const`?

### what is the difference between `Promise` and `Async await`?

### How behave `Postfix increment/ decrement` and `Prefix increment/ decrement` operator?
If used postfix, with operator after operand (for example, x++), the increment operator increments and returns the value before incrementing.

If used prefix, with operator before operand (for example, ++x), the increment operator increments and returns the value after incrementing.
```js
let x =3;
let y=++x; // prefix increment return incremented value
console.log(x,y,"x,y"); // 4,4
y=x++; // postfix increment return without incremented value

console.log(x,y,"x,y"); // 5,4

y=--x; // prefix increment return decremented value
console.log(x,y,"x,y"); // 4,4
y=x--; // postfix increment return without decremented value

console.log(x,y,"x,y"); // 3,4
```

### How you achive Function chaining?

### Explain Non Blocking I/O?

### explain `apply`, `call`, `bind`?
You can `this` configurable with these methods,
* `apply` with comma seperated params.
```js
function originalFunction(param1,param2){
    // as you see here is no reference for `name` variable
    // when you call by "call", "apply", "bind"
    // you pass a "object" which have a 'name' property
    console.log(this.name);
    return ;
}
const result = originalFunction.apply(thisArg, param1, param2, ...);
```
* `call` with params in array
```js
const result = originalFunction.call(thisArg, [param1, param2, ...]);
```
* `bind` is currying implementation,it make invokable for later. You can call it later as many time as you need
```js
const boundFunction = originalFunction.bind(thisArg, param1, param2, ...);
boundFunction();
```
### which method are modified orginal array?
`pop`, `push`, `shift`, and `splice` modify the original array.
```js
console.log([1,2,3].pop()) // return the
```
### what will return when we call `arr.push()` and `arr.pop()`?

### Task queue [Micro Task queue | Macro task queue] > Event Loop > Call stack

| Microtask Queue                | Macrotask Queue              |
|--------------------------------|------------------------------|
| Resolve promise A              | Read file (I/O operation)    |
| Execute process.nextTick callbacks              | Timer (setTimeout, setInterval) |
| Execute event emitter callbacks              | Network request (HTTP)       |
## Javascript Runtime (Node, Bun)

### [Important](https://nodejs.org/en/learn/asynchronous-work/dont-block-the-event-loop)
### [Best Practices](https://github.com/goldbergyoni/nodebestpractices)
