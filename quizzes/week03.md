# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
(Summed up answers & in my own words)
Encapsulation - allows us to "hide" the functions or code away from the "users"

Abstraction - This basicaly means to only "show" the bare minimum to the "users" that is neccisary and to keep things from  being dependant on one another

 Inheritance - This allows for the code to be reused by putting that code within classes and then creating those classes or child classes

 polymorphism - This is saying that the class you create should be able to be used in different ways on not be dependant on other which allows more flexability within your projects.
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
staff.name = "Timmy"
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Encapsulation is basically where you put your data and functions within a class to make it unaccessible to "users"
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single responsiblity principle
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
a class is the "structure" and the instance of a class is the "built out" of said class
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
a proxy object is an "access" to another object or class so that said object or class isnt able to be accessed by users.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
The purpose is to seperate the DOM from the actual data aswell as to increasee flexabilty for functions
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
the controller interacts with the DOM like gets user information than talks to the service if needed then sends back visual information
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
the service gets information from the controller to manipulate or to change buisness logic or the Data that you dont want the "users" to see or have access to
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The model is used to create the data. For example a player which has a name and a favorite color the model is responsible for laying out the foundation for the data then stored in the appState.
```
