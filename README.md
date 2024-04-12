# js-technique-and-mastery

## Javascript
JavaScript is a prototype-based language, which means that it uses prototypes to inherit properties and methods from one object to another. In JavaScript, objects can be linked to other objects, forming a prototype chain. Since JavaScript is a loosely typed language, you are not required to correctly predict the kind of data that will be kept in a variable.
Dynamically typed languages like Python and JavaScript offer more flexibility, but they might lead to runtime errors due to unexpected type mismatches. On the other hand, statically typed languages are more verbose, which developers might sometimes find inconvenient, especially when rapid prototyping is required.

### Mention some Browser Engine (also refer as Rendering Engine) name?

* **Webkit** developed by Apple (used by *Safari*, *Chrome*)
* **Gecko** developed by Mozila (used by *Firefox*)
* **Blink** developed by Google (*Chrome* and all other Chromium-based browsers, notably *Microsoft Edge*, *Brave*, *Vivaldi*, *Samsung Internet* and *Opera*)
  
### Mention some javascript engine name?

* **Chakra** written in c++ for microsoft used by Edge browser
* [**V8**](https://v8.dev/) V8 is Google’s open source high-performance JavaScript and WebAssembly engine, written in C++. It is used in Chrome and in Node.js, among others. It implements [ECMAScript](https://tc39.es/ecma262/) and [WebAssembly](https://webassembly.github.io/spec/core/), and runs on Windows 7 or later, macOS 10.12+, and Linux systems that use x64, IA-32, ARM, or MIPS processors. V8 can run standalone, or can be embedded into any C++ application.
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
    - globalThis
    - Infinity
    - NaN
    - undefined
2. **Fundamental objects** :These objects represent fundamental language constructs.
    - Object
    - Function
    - Boolean
    - Symbol
3. **Numbers and Dates** :These are the base objects representing numbers, dates, and mathematical calculations.
    - Number
    - BigInt
    - Math
    - Date
4. **Function properties** : These global functions—functions which are called globally, rather than on an object—directly return their results to the caller.
    - eval()
    - isFinite()
    - isNaN()
    - parseFloat()
    - parseInt()
    - decodeURI()
    - encodeURI()
5. **Text processing** :These objects represent strings and support manipulating them.
    - String
    - RegExp
6. **Indexed collections** : These objects represent collections of data which are ordered by an index value.
    - Array
7. **Keyed collections** :These objects represent collections which use keys.
    - Map
    - Set
    - WeakMap
    - WeakSet

### Type conversion in javascript
[Read details](https://javascript.info/type-conversions)
### What is `Function Expression`?
[Read details](https://javascript.info/function-expressions)
### What is iterable?
[Read details](https://javascript.info/iterable)
### Currying in javascritpt

### Composition in javascript

### Closure in javascript

### Task queue, Micro Task queue, Macro task queue

### ProtoType in javascript

### Recursion in javascript

### Why **Tail Recursion** is optimal from pure **Recursion**?

### What will print when `console.log()` execute and why?

### what are the difference between `var`, `let`, and `const`?

### what is the difference between `Promise` and `Async await`?

### How behave `Post increment/ decrement` and `Pre increment/ decrement` operator?

### How you achive Function chaining?

### Explain Non Blocking I/O?

### explain `apply`, `call`, `bind`?

### what will return when we call `arr.push()` and `arr.pop()`?

## Javascript Runtime (Node, Bun)

### 
