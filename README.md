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

### Mention some Standard Library
* [**Core-js**](https://github.com/zloirock/core-js) polyfills library.
* [**stdlib**](https://github.com/stdlib-js/stdlib) (/ˈstændərd lɪb/ "standard lib") is a standard library, with an emphasis on numerical and scientific computation, written in JavaScript (and C) for execution in browsers and in Node.js.

### Primitive data type and non primitive data type?
- **Primitive** The predefined data types provided by JavaScript language are known as primitive data types. Primitive data types are also known as in-built data types.
    1. **String**.
    2. **Number**.
    3. **Bigint**.
    4. **Boolean**.
    5. **Undefined**.
    6. **Null**.
    7. **Symbol**.
    8. **Object**.
- **Non Primitive** The data types that are derived from primitive data types of the JavaScript language are known as non-primitive data types. It is also known as derived data types or reference data types.
    1. **Object**.
    2. **Array**.
    3. [**Map**](https://javascript.info/map-set)
    4. [**Set**](https://javascript.info/map-set)
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
### Type conversion in javascript
[Read details](https://javascript.info/type-conversions)
### What is iterable?
[Read details](https://javascript.info/iterable)

### Hoisting

JavaScript Hoisting refers to the process whereby the interpreter appears to move the declaration of functions, variables, classes, or imports to the top of their scope, prior to execution of the code.

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
#### Difference between function expression and function decleration?
There are a few key differences between function expressions and function declarations:

- Function declarations are ***hoisted***, while function expressions are not. This means that you can call a function declaration before it is defined, but you cannot do this with a function expression.
- With function expressions, you can use a function immediately after it is defined. With function declarations, you have to wait until the entire script has been parsed.
- Function expressions can be used as an argument to another function, but function declarations cannot.
- Function expressions can be anonymous, while function declarations cannot.

* [when-to-use-a-function-expression-vs-function-declaration](https://www.sitepoint.com/when-to-use-a-function-expression-vs-function-declaration/)
* [function-expressions](https://javascript.info/function-expressions)

### Immediately Invoked Function Expressions (IIFE)
function expression that annonymouse and called immediately after its defined.
```js
(function () {
    // code in here
}());
```
and it's useful for maintainable module code with out side effecting as it is fall into a function scope of it's property and methods.

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
### Task queue [Micro Task queue | Macro task queue] > Event Loop > Call stack

### ProtoType in javascript

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

### what will return when we call `arr.push()` and `arr.pop()`?

## Javascript Runtime (Node, Bun)

### [Important](https://nodejs.org/en/learn/asynchronous-work/dont-block-the-event-loop)
### [Best Practices](https://github.com/goldbergyoni/nodebestpractices)
