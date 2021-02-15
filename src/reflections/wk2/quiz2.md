# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
let, var, and const

```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
a function is something in javascript that does a thing when you call it 
function abc(xyz){

}
abc(xyz)
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single responsibility
Open closed principle
Liskov substitution principle
Interface segregation principle
Dependency Inversion Principle
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
Pineapple is at [2] because array count starts at [0]
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.name.push(friends)
them.name.push(friends)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
if(i=0;i>0;i++){

} the parens are the conditional
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
the piece in the blank space would be called the incrementer and you would write it as i++ in order to increment it. 

```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
DOM stands for Document Object Model and the DOM is rendered when the HTML file is loaded.

```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
There are six primitive types in ECMAScript, undefined, boolean, number, string, bigInt, Symbol. There are also 2 structural types, Object and function, and a structural root primitive, which is null.

```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
a parameter a placeholder in memory that passes a piece of data through a function.
function abc(xyz){}
an argument is the data that replaces the parameter. 
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
Primitive values are what is stored  direction in the location that a variable accesses. Reference values are stored in the variable location which points at a location in memory where an object is stored.

```