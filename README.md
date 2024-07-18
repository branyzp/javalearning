# Object Oriented Programming

OOP uses objects as a primary source to implement what will the code do
The main aim is to bind data and functions that operate on them together so that no other part of the code can access the data except for the related functions

### Access modifiers
	• Public - accessible to all classes in the app
	• Protected - accessible within the package that it is defined
	• Private - accessible only within the class that it is defined
	• Default - accessible only within the same class and package within its class

### Return type
	• Data type of the value returned by the method - void, int, String etc

### Class
	• A user-defined blueprint from which objects are created

### Object
	• Basic unit of OOP

### Pillars of OOP
	1. Abstraction
		a. Only essentials are displayed to the user
	2. Encapsulation
		a. Data in a class is hidden from other classes
	3. Inheritance
		a. Classes inherit fields and methods of another class using 'Extends' keyword
		b. Superclass - class whos features are inherited
	4. Polymorphism
		a. Ability of OOP languages to differentiate between entities with the same name efficiently
		b. Java will intelligently identify which function/method is being called depending on the return types and parameters defined etc

  ### Spring
  Core concepts

Bean life-cycle
	• Java beans are managed by the Spring container
	• When program starts -> Spring container is started -> dependencies injected and bean instances created
	• When spring container is closed -> bean instances destroyed
![image](https://github.com/user-attachments/assets/72d521a0-2a7b-43ae-a449-4094444dee3c)


Dependency Injection

Inversion Of Control

Bean Factory and application context

 ### SpringBoot
    Java Framework based on microservices that includes many things out of the box
  	• Standalone java apps
  	• Tomcat or Jetty directly included as server
  	• Starter dependencies to simplify build configurations
    • Production-ready stuff like health checks
### MVC Framework
MVC stands for Model, View, Controller.
1. Model - handles the application's data and business logic
2. View - handles the presentation layer, displaying data to users
3. Controller - intermediary between Model and View, handles the user input, processes it and manages the flow of data between Model and View.

### MVC in Java Spring Boot
1. Model in Spring Boot is represented by Java Objects, also known as Beans or Entities. These objects encapsulate data and business logic. 
Spring Data JPA and Hibernate are commonly used for data persistence.
2. View is the user interface. ThymeLeaf, JSP or other templating engine can be used. However, we will be using JavaScript and React.
3. Controller is the handler for user requests and manages the interaction between M and V.
Controllers are annotated with @Controller. They handle the REST API portion.


### What are Spring Beans?
- Spring beans are java objects that are managed by the Spring IoC container.
- To be specific, they are an instance of a class managed by the Spring Container.
- IoC stands for Inversion of Control, that is, if you have an object which requires another object to function properly, Spring handles the relationships (dependencies) between these objects instead of handling it yourself.
- The Spring Container also performs dependency injection which means that it ensures that the instances are at the right place

Overloading
- using same method name for different tasks
- for example, at a coffee shop you order a coffee (method name) but you can specify what type of coffee you want, such as espresso, mocha or latte (parameters)
- they all are coffee but prepared differently based on your order
![image](https://github.com/user-attachments/assets/2e2d61a2-53a3-45e4-b01f-b9b13b0af5a4)


Overriding
- when a child class changes a method from its parent class
- for example, 'Animal' class with 'Speak' method could be overridden by a 'Dog' class that has a 'Woof' method instead
