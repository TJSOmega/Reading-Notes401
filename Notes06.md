# Notes 06

### What is a Singleton?

A singleton is a class that allows only a single instance of itself to be created and gives access to that created instance. It contains static variables that can accommodate unique and private instances of itself. It is used in scenarios when a user wants to restrict instantiation of a class to only one object. This is helpful usually when a single object is required to coordinate actions across a system.


### How Can we use a Singleton with Node Modules:

Usually a Singleton can be used in a module export by either writing module.exports = (With code inline here), or writing a function and calling it in the module.exports or instantiating something such as Class object in the module.exports.

### Constructing a Middleware:

The route you may want to go to create a middleware item it to create a separate function file, and inside create your middleware function with all of the required parameters, and then module.export that function and place it into your route calls.


## Vocab:

**Router Middleware:** Router-level middleware works in the same way as application-level middleware, except it is bound to an instance of express.Router().


**Dynamic Module Loading:** a mechanism by which a computer program can, at run time, load a library (or other binary) into memory, retrieve the addresses of functions and variables contained in the library, execute those functions or access those variables, and unload the library from memory.


**Singleton Pattern:** In software engineering, the singleton pattern is a software design pattern that restricts the instantiation of a class to one "single" instance. This is useful when exactly one object is needed to coordinate actions across the system. The term comes from the mathematical concept of a singleton.


**CRUD -> REST Method Matches:** create, read, update, and delete (CRUD) are the four basic operations of persistent storage. Alternate words are sometimes used when defining the four basic operations of CRUD, such as construct instead of create, retrieve instead of read, or destroy or destruct instead of delete.


**Mock Testing:** Mock testing is an approach to unit testing that lets you make assertions about how the code under test is interacting with other system modules. In mock testing, the dependencies are replaced with objects that simulate the behaviour of the real ones. The purpose of mocking is to isolate and focus on the code being tested and not on the behaviour or state of external dependencies.
