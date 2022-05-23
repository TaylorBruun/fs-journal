# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
let, var, and const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
the definition of the function is where you describe in the code what the function does, including its inputs and outputs (as opposed to invoking it)
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
These are a set of principles for object oriented design, they are:

single-responsibility, open-closed, liskov substitution, interface segregation, dependency inversion
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
2, because arrays are zero-indexed and their order matters.
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.friends.push(them)

```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
if(+0 == 0){
  Do a thing
}
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
the increment; i++
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
The document object model; the index.html file
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
undefined, null, boolean, number, bigint, string, symbol, object
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
Parameters are the 'generic' version, provided in the definition of the function. Arguments are the 'specific' version, which are provided to fulfil the parameters when the function is actually called.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
Primitive values are the most basic elements like numbers or strings. Reference values are made up of/act on those basic values - arrays, objects, and I guess technically functions. 
```