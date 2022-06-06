# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
Syncronous code runs in order, fully completing a line of code before moving on. Asynchronous code does not wait for the line to complete; it may still be waiting (for a response from an API for example), and the code will continue to run
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
An event handler that checks when a specific event takes place and then executes provided instructions
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
The Open-closed principle
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
A function that takes another function as an argument
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
A promise is the initial response from an API telling you that your request was received and that you should expect something back. You can get the content of an error with error.message (which can then be placed in a console.error, or whatever else you want to do with it)
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
Get, Push, and Post
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
Application Programming Interface
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
The service
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
To help protect data privacy and ensure that the user is only able to access/interact with data that you want them to.
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
200
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
The generic server error
```