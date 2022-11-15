1. What is the difference between prompt and alert box in JavaScript, show an example of their use.
2. Code below defines an object, what would `console.log(person.name, person['age'], person.car, person.car.year, person.lastname)` log to console?
 ```
 const person = {
  name: 'miljenko',
  age: 42,
  car: { year: 2023, make: 'Toyota', model: 'Corolla' },
};
```
3. What will the code below output to the console and why?
```
var arr1 = "marija".split('');
var arr2 = arr1.reverse();
var arr3 = "dedic".split('');
arr2.push(arr3);
console.log("array 1: length=" + arr1.length + " last=" + arr1.slice(-1));
console.log("array 2: length=" + arr2.length + " last=" + arr2.slice(-1));
```
4. What will the code below output to the console and why?
```
console.log("0 || 1 = "+(0 || 1));
console.log("1 || 2 = "+(1 || 2));
console.log("0 && 1 = "+(0 && 1));
console.log("1 && 2 = "+(1 && 2));
console.log("1 && 'text' = "+ (1 && 'text')) 
```
5. What is a ternary operator? Show an example of use.
6. What is optional chaining? If we have an object `let a = { }`, why does `console.log(a.person.name)` give an error but `console.log(a.person?.name)` does not?
7. What are undeclared and undefined variables, what's the difference?
8. What is the keyword `this` in JS?
9. What are named and anonymus functions in JS? Can you store a function in a variable and then call it? Show examples for both questions.
10. What are arrow functions and how are they different from normal functions? Show example.
