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

### 15.1 - Introduction to Machine Learning
#### 15.1.1 - Scikit-Learn
- Scikit-Learn: conveniently packages the most effective maching-learning algorithms as estimators. 
#### 15.1.2 - Types of Machine Learning
- Supervised machine learning: works with labeled data
    - Classification: predict the discrete classes (categories) to which samples belong. 
    - Regression: predict a continuous output
- Unsupervised machine learning: works with unlabeled data
#### 15.1.3 - Datasets Bundled with Scikit-Learn
#### 15.1.4 - Steps in a Typical Data Science Study

### 15.2 - Case Study: Classification with k-Nearest Neighbors and the Digits Dataset, Part 1
- Binary classification: having two classes
#### 15.2.1 - k-Nearest Neighbors Algorithm
- k-Nearest Neighbors: attempts to predict a test sample's class by looking at the k training samples that are nearest (in distance) to the test sample. 
There are two parameter types in machine learning:
1. those the estimator claculates as it learns from the data you provide
2. those you specify in advance when you create the scikit-learn estimator object that represents the model
- hyperparameters: parameters specified in advance
#### 15.2.2 - Loading the Dataset
#### 15.2.3 - Visualizing the Data
#### 15.2.4 - Splitting the Data for Training and Testing
#### 15.2.5 - Creating the Model
#### 15.2.6 - Training the Model
#### 15.2.7 - Predicting Digit Classes

### 15.3 - Case Study: Classification with k-Nearest Neighbors and the Digits Dataset, Part 2
#### 15.2.1 - Metrics for Model Accuracy
- score method: returns an indication of how well the estimator performs for the test data you pass as arguments
- confusion matrix: shows the correct and incorrect predicted values for a given class
#### 15.2.3 - K-Fold Cross-Visualization
#### 15.3.3 - Running Multiple Models to Find the Best One
#### 15.3.4 - Hyperparameter Tuning

### 15.4 - Case Study: Time Series and Simple Linear Regression
- underfitting: Occurs when a model is too simple to make predictions, based on its training data
- overfitting: When you model is too complex. The most extreme case would be a model that memorizes its training data. 
