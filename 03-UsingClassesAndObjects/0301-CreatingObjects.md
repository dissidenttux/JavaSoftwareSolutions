- Chapter 1 presented an overview of object-oriented concepts, such as the basic relationship between classes and objects.
- Chapter 2 discussed primitive data, as well as some examples of using objects for the services they provide.


- The `println` method used in chapters before is a service provided be the `System.out` object.
- The `System.out` object represents the standard output stream.
	- `out` being an object variable that's stored in the `System` class.
	- These are predefined and set up for us as part of the Java standard class library: we can just use it.


- We create objects in Java using the `new` operator. Once created, we're able to use the various services it provides (i.e. invoking its methods).
- In Java, a variable name represents either a primitive value, or an object.
- Like primitive type variables, a variable that refers to an object must be declared.
- The class used to define an object can be thought of as a type of an object.
- The declaration of object variables has a similar structure to declarations of primitives:
```java
int num; // primitive variable declaration
String name; // object variable declaration
```
- The first declaration holds an integer value
- The second declaration creates a `String` variable that holds a *reference* to a `String` object.
	- Object variables don't hold an object itself, it holds the address of an object.
	- 
