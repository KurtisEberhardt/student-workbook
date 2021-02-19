# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Encapsulation, Abstraction, Polymorphism, and Inheritance. 
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
property.staff.name
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Encapsulation is using multiple layers of files to conceal the data stored in the application.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
The S in 'SOLID' stands for Single Responsibility Principle
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class in JS is a defined set of, well, whatever you want it to be. An instance of a class can inhereit from other objects. 

```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A proxy object is an object that stands in place of a different set of data so it remains private.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
MVC is used to adhere more closely to the SOLID design principles by giving everything its own responsibilities. It can also be used to more easily separate the project into pieces for different developers.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The Controller acts as the middleman between the Service and the User. Data will go from the User to the Controller which will tell the Service to change the data. 
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
Service is where all the functions are defined and makes direct changes to the data stored in the model.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The model is used as the base storage location for all the data used in the application
```

