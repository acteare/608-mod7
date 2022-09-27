# 608-mod7
## Chapter 10 - Object-Oriented Programming

### 10.1 - Introduction
- Object-based programming: Primarily creating and using objects of existing classes. 

### 10.2 - Custom Class Account
#### 10.2.1 - Test-Driving Class Account
- Constructor expression: An expression that builds and initializes an object of the class. These create new objects and initialize their data using arguments specified in parentheses.
#### 10.2.2 - Account Class Definition
#### 10.2.3 - Composition: Object References as Members of Classes
- Composition: Embedding references to objects of other types 

### 10.3 - Controlling Access to Attributes
- Client code: any code that uses objects of the class

### 10.4 - Properties for Data Access
#### 10.4.1 - Test-Driving Class Time
#### 10.4.2 - Class Time Definition
- eval function: Receives the preceding string as an argument and uses it to create and initialize a Time object containing values specified in the string. 
- unary * operator: used to unpack the time_tuple's values, then passes them as individual arguments.
#### 10.4.3 - Class Time Definition Design Notes
- public interface: the set of properties and methods programmers should use to interact with objects of the class

### 10.5 - Simulating "Private" Attributes
- private: Class members that may not be accessed outside a class definition. They are only visible within the class that defines them.

### 10.6 - Case Study: Card Shuffling and Dealing Simulation
#### 10.6.1 - Test-Driving Classes Card and DeckOfCards
#### 10.6.2 - Class Card - Introducing Class Attributes
- class attribute: represents class-wide information. It belongs to the class, not to a specific object of that class. 
#### 10.6.3 - Class DeckOfCards
#### 10.6.4 - Displaying Card Images with Matplotlib

### 10.7 - Inheritance: Base Classes and Subclasses
- single inheritance: a class derived from one base class
- multiple inheritance: a subclass inherits from two or more base classes
- "is-a" relationships: an objecrt of a subclass type may also be treated as an object of the base-class type
- "has-a" relationship: a class has references to one or more objects of other classes as members

### 10.8 - Building an Inheritance Hierarchy; Introducing Polymorphism
#### 10.8.1 - Base Class CommissionEmployee
#### 10.8.2 - Subclass SalariedCommissionEmployee
#### 10.8.3 - Processing CommissionEmployees and SalariedCOmmissionEmployes Polymorphically
#### 10.8.4 - A Note About Object-Based and Object-Oriented Programming

### 10.9 - Duck Typing and Polymorphism
- duck typing: A programming style which does not look at an object's type to determine if it has the right interface; instead, the method ro attribute is simply called or used

### 10.10 - Operator Overloading
#### 10.10.1 - Test-Driving Class Complex
#### 10.10.2 - Class Complex Definition

### 10.11 - Exception Class Hierarchy and Custom Exceptions
### 10.12 - Named Tuples
- nametuple function: creates a subclass of the built-in tuple type
- OrderedDict: remembers the order in which its key-value pairs were inserted in the dictionary

### 10.13 - A Brief Intro to Python 3.7's New Data Classes
#### 10.13.1 - Creating a Card Data Class
#### 10.13.2 - Using the Card Data Class
#### 10.13.3 - Data Class Advantages over Named Tuples

## Chapter 15 - Machine Learning
