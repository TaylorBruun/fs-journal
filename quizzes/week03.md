# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Abstraction, encapsulation, inheritance, and polymorphism
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
bracket notation - staff[property]
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Writing code so that each object is responsible for its own state (or, another way it makes sense to me, making sure that things that are NOT your object don't have the ability to change things )
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single responsibility
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
An instance actually exists and has the properties described in the class. A class is more like a set of instructions on how its instances should be built. It reminds me of how a function has a definition that is later called and executed according to the instructions in the definition.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
An 'in between' version of an object that allows you to write custom instructions for basic operations
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
To help us write more organized code that adheres to best practices. Dividing our logic between multiple services for example should help us keep code encapsulated
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
To process user input and provide information to services. Additionally, to present the appropriate information to the view
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
To perform the business logic and interact with our data. Also to process the information received from the controller 
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
To describe the appropriate structure for data we are working with
```
