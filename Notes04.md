# Notes 04


## Advantages of Test Driven Development:

Test-driven development (TDD) is a software development process that relies on the repetition of a very short development cycle. First, the developer writes an (initially failing) automated test case that defines a desired improvement or new function, then produces the minimum amount of code to pass that test, and finally refactors the new code to acceptable standards.

1. You spend less time in the debugger.

2. TDD creates a detailed specification.

3. The development time to market is shorter.

**beforeEach()** is run before each test in a describe allowing you to prepare your test environment.

**afterEach()** is run after each test in a describe allowing for cleanup or tracking.

### Disadvantage of Test Driven Development:

The tests may be hard to write, esp. beyond the unit testing level.

### ES6 Classes versus Constructor Prototype:

Newer ES6 classes are much more versatile and concise than the previous Constructor Prototype functions.

### Why Rest?:

EST, or REpresentational State Transfer, is an architectural style for providing standards between computer systems on the web, making it easier for systems to communicate with each other. REST-compliant systems, often called RESTful systems, are characterized by how they are stateless and separate the concerns of client and server. We will go into what these terms mean and why they are beneficial characteristics for services on the Web.

**You should use REST because** it really encompasses all the potential actions you want to do on a resource/object. Another reason is that it is a standard that everyone can implement and use. To read up on why standardization is important, I would suggest reading this and this (it is rather funny, but really helps people grasp the concept of REST).


## Vocab:

**Functional Programming:** In computer science, functional programming is a programming paradigm where programs are constructed by applying and composing functions.

**Object-oriented programming (OOP):** a programming paradigm based on the concept of "objects", which can contain data and code: data in the form of fields (often known as attributes or properties), and code, in the form of procedures (often known as methods).

**Class:** In object-oriented programming, a class is an extensible program-code-template for creating objects, providing initial values for state (member variables) and implementations of behavior (member functions or methods).

**super:**  a reference variable which is used to refer immediate parent class object.

**this:** a reference variable which is used to reference the class object.

**Test Driven Development (TDD):** a software development process relying on software requirements being converted to test cases before software is fully developed, and tracking all software development by repeatedly testing the software against all test cases.


**Jest:** Jest is a JavaScript testing framework maintained by Facebook, Inc. designed and built by Christoph Nakazawa with a focus on simplicity and support for large web applications. It works with projects using Babel, TypeScript, Node.js, React, Angular, Vue.js and Svelte. Jest does not require a lot of configuration for first time users of a testing framework.


**Continuous integration:** is the practice of automating the integration of code changes from multiple contributors into a single software project. It’s a primary DevOps best practice, allowing developers to frequently merge code changes into a central repository where builds and tests then run.

**REST:** REpresentational State Transfer, is an architectural style for providing standards between computer systems on the web, making it easier for systems to communicate with each other. REST-compliant systems, often called RESTful systems, are characterized by how they are stateless and separate the concerns of client and server. We will go into what these terms mean and why they are beneficial characteristics for services on the Web.

**Data Model:** (or datamodel) is an abstract model that organizes elements of data and standardizes how they relate to one another and to the properties of real-world entities. For instance, a data model may specify that the data element representing a car be composed of a number of other elements which, in turn, represent the color and size of the car and define its owner.

