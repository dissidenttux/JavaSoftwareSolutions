# 1.6 Object-Oriented Programming
- Java is an object-oriented (OO) language.
- An object is a fundamental entity in a Java Program
- OOP software design is defining objects that interact with each other


- OOP is the dominant approach used in commercial software development


- OOP's popularity stems from objects can be used to represent real-world entities effectively
	- We can use a software object to represent a company employee
	- One object per employee, each with separate behaviors and characteristics
- In this way, OOP makes it easy to:
	- map our programs to real-world situations
	- solve problems (the point of writing a program in the first place)

## Problem Solving
Problem solving consists of multiple steps:
1. Understanding the problem
2. Designing a solution
3. Considering alternatives
4. Implementing the solution
5. Testing the solution and fixing any problems that exist


- This approach works when developing software
- Steps aren't purely linear, some activites will overlap others
- At some point, all steps are to be addressed


- Understanding the problem requires specific attention, without it, causes misguided efforts
- If we don't completely understand the problem, we end up solving the wrong one, or going on tangents
- Each problem has a *problem domain*, the real world issues that are key
	- If the problem is to score a bowling match, the problem domain is the rules of bowling
- To develop a good solution, we must thoroughly understand the problem domain.


- Program design involves breaking a solution into managable pieces
- The key to designing a problem solution is breaking it down into managable pieces
- A solution to any problem can rarely be expressed as one big task
	- I.e. it's a series of small cooperating tasks
- When developing software, we don't write a big program, but separate pieces that are responsible for
certain parts of the solution, then integrate them with the other parts


- Our first inclination toward a solution may not be the best. Always consider alternatives and refine as
necessary.
- The earlier the consider alternatives, the easier it is to implement modify our approach


- Implementation is act of taking the design and putting it into a useable form
- Programming != writing code.
- The act of designing the program should be more interesting than implementing the design in a
particular language


- At many points in the developement process, we should test our solution to find any errors to fix them
- Testing can't guarantee fixing problems to be discovered, but it can raise confidence that we have a
viable solution


- The text explores techniques to design & implement programs
- Never forget the primary goal is to solve problems


## Object-Oriented Software Principles
- OOP ultimately requires a solid understanding of these terms:
	- object
	- attribute
	- method
	- class
	- encapsulation
	- inheritance
	- polymorphism


- An **object** is a fundemental element in a program
- Every object has a **state** and a set of **behaviors**
- "State" = state of being, i.e. fundamental characteristics that currently define the object
	- ex. a bank accounts current balance


- Java manages objects and primitive data in addition
- *Primitive data* fundamental values such as numbers and characters
- Objects represent more interesting or complex entities


- An object's *attributes* are values it stores internally, which could be rep'd as primitive data or other objects
	- A bank account object may store a `float` value that represents the balance
	- May contain ohter attributes, like the name of account owner
- Collectively, the values of the object's attributes define its current state


- **Key Concept**: each object has a state, defined by attributes, and a set of behaviours, defined by
methods.


- A *method* is a group of programming statements that's given a name
- When a method is invoked, its statements are executed
- A set of methods is associated with an object
- Methods of an object define its potential behaviors
	- Example: to define the deposit into a bank account, we define a method containing programming
	statements that will update the account balance accordingly


- An object is defined by a *class*
- A class is the model/blueprint from which an object is created
- Blueprint of a house is a prime example
- Once the blueprint is created, several houses can be built using it
- I.e. house blueprint can be used to create different but similar or "same" houses


- Generally, classes contain no space for data
- Each object, however, does has space for its own data, which is why each has its own state


- Once a class has been defined, multiple objects can be created from that class
- Example: a class represents a bank account, we can create multiple objects to represent
multiple different accounts. Each account has its down balance


- **Key Concept**: a class is a blueprint of an object. Multiple objects can be created from one
class definition.


- An object should be *encapulated*, meaning it protects and manages its own information.
- I.e. an object should be self-governing
- Changes made to the state of the object should **only** be accomplished by that object's methods
- I.e. we should design objects so that other objects can't "reach in" and change their states


- Classes can be created from other classes by using *inheritance*.
- I.e., the definition of one class can be based on another class that already exists.
- Inheritance is a form of *software reuse*, capitalizing on the similarities between various kinds
of classes we may want to create
- One class can be used to derive other classes, derived classes can be used to derive even more classes
- This creates a heirarchy of classes, where the attributes and methods in one class are inherited by
its children, and so on.
- Example: we might create a hierarchy of classes that represent various types of bank accounts.
- Common characterists are defined in high-level classes, and specific differences are defined in
derived classes.


- **Polymorphism** is the idea that we can refer to multiple types of related objects over time
in consistent ways.
- It gives us the ability to design powerful and elegant solution to problems that deal with multiple
objects


## Self-Review Questions
**SR1.33**	List the five general steps required to solve a problem


1. Understanding the problem
2. Designing a solution
3. Considering alternatives
4. Implementing a solution
5. Testing the solution and fixing any problem that exist



**SR1.34**	Why is it important to consider more than one approach to solving a problem?
Why is it important to consider alternatives early in the process of solving a problem?


It's important to consider more than one approach to a problem because our first solution may not be
a good one. By considering alternatives early, we can save ourselves from expending too much energy
on the first idea, saving overall time and effort.


**SR1.35**	What are the primary concepts that support object-
oriented programming?


The primary concepts supporting OOP is object, attribute, method, class, encapsulation, inheritance,
polymorphism. An object is defined by a class, which contains methods that define operations on those
objects (services that they perform). Objects are encapsulated such that they store and manage their
own data. Inheritance is a reuse technique in which one class can be derived from another.
