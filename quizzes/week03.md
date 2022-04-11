# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
  Abstraction, Encapsulation, Polymorphism, inheritance
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
  staff[property]
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
  The separation of data from the interaction of the methods that act on them.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
  S - single responsibility functions
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
  A class is a blueprint of what data will look like.  An instance of a class is the actual data object that uses the structure of the class blueprint.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
  A proxy is an object that is an instance of another and has special operations to access the original object.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
  The MVC pattern separates the view from the data and functions so that the website only displays what the end user needs.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
  Acts as a liason between the view and the service.  It controls the logic between the them.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
  Accesses the data from the model.  This is also where the controller sends functions when the data needs to be manipulated.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
  This is where the data is stored and also shapes what the data will look like at the view.
```
