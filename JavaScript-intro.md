# JavaScript

JavaScript is a **dynamically** typed language.

| Statically typed | Dynamically typed |
| ------------- | ------------- |
| Perform type checking | Type checking is done at runtime |
| Explicitly define your data types | Assumes the data type automatically |
| If the value od x is a string, then it must be defined and can not change to another type | Less code but also more prone to errors |

JavaScript uses the keywords `var`, `let` and `const` to declare variables.

```
var x;
let y;

x = 5;
y = 6;

const z = x + y;

console.log(z); // 11
```

Variables created with `var` and `let` keywords can have changing values.
````
 let x = 2;
 x = 'marija';
 ````

Variables created with `const` keyword **can not** have changing values.
````
const x = 2;
x = 'marija'; // Uncaught TypeError: invalid assignment to const 'x'
````


**General practice is to use `const` by default but if you know the variable will have changing value use `let`.**

## Data types in JavaScript

| Data Types | Description | Example |
| ------------- | ------------- | ------------- |
| `String` | represents textual data | `'hello'` |
| `Number` | an integer or a floating-point number | `3`, `3.12`, `3e-2` |
| `BigInt` | an integer with arbitrary precision | `900719925124740999n` , `1n` |
| `Boolean` | True or false | `true` and `false` |
| `undefined` | a data type whose variable is not initialized | `let a;` |
| `null` | denotes a `null` value | `let a = null;` |
| `Symbol` | data type whose instances are unique and immutable | `let value = Symbol('hello');` |
| `Object` | key-value pairs of collection of data | `let person = { name: 'Marija', lastName: 'Dedić' }` |



