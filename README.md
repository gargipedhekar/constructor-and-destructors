# constructor-and-destructors
Experiment 12

## Contents
- [Aim](#Aim)
- [Software Used](#Software-used)
- [Theory](#Theory)
  * [Purpose of Constructors](#purpose-of-constructors)
  * [Types of Constructors](#types-of-constructors)
  * [Default Constructor](#default-constructor)
  * [Parameterized Constructor](#parameterized-constructor)
  * [Copy Constructor](#copy-constructor)
  * [Constructor Overloading](#constructor-overloading)
  * [Destructors](#destructors)
- [Algorithms](#Algorithms)
- [Conclusion](#Conclusion)
  
## Aim 
To study Constructors

## Software Used 
VS Code

## Theory

Constructors are special member functions of a class that are automatically invoked when an object of that class is created. They play a crucial role in initializing objects, ensuring that they are set up correctly before they are used. 

### 1. Purpose of Constructors
The primary purpose of a constructor is to initialize an object. When a new object is created, the constructor ensures that the object's member variables are set to appropriate values (either default values or ones provided by the user).

#### Characteristics of Constructors:
- **Same name as the class:** Constructors always have the same name as the class they belong to.
- **No return type:** Unlike regular member functions, constructors do not have a return type, not even `void`.

### 2. Types of Constructors

#### 2.1 Default Constructor
A default constructor is one that takes no parameters. If you do not provide any constructor in your class, the compiler automatically generates a default constructor that initializes the object with default values. However, if any other constructor is defined, the compiler will not provide a default one.

```cpp
class MyClass {
public:
    MyClass() { // Default constructor
        // Initialization code
