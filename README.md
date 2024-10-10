# Constructors-and-destructors
## AIM:-
Constructors and destructors in C++

## Software used:-
VS code

## Theory:-
#### Constructor 
A constructor in C++ is a special member function that is used to initialize the variables of a class when an object is created.

### Key Features
1. Name Matching: The constructor's name matches exactly with the class name.
2. No Return Type: Constructors do not have a return type, not even void.
3. Automatic Invocation: A constructor is automatically invoked when an object of the class is instantiated.
4. Initialization: Primarily used to initialize member variables of the class.
### Access Control
1. Public Section: Constructors are typically declared in the public section of a class to allow easy creation of objects.
2. Private or Protected Sections: Can also be declared in the private or protected sections to restrict object creation.
#### Constructor Overloading
Multiple Constructors: Constructors can be overloaded, allowing multiple ways of initializing an object. Restrictions: Constructors cannot be declared as virtual functions.
### Types of constructors:
1. Default constructor :
   A default constructor is a constructor that takes no parameters or has all default arguments. If no constructor is explicitly defined, C++ automatically provides a default constructor. It initializes the class's members with default values (for built-in types) or calls their default constructors (for other objects).
2. Parameterized constructor:
 A parameterized constructor allows arguments to be passed when an object is created. This constructor initializes object attributes with specific values provided by the user. It enables flexibility in object creation by allowing different initialization based on the passed parameters.
3. Copy constructor:
A copy constructor creates a new object as a copy of an existing object. It takes a reference to an object of the same class as its parameter and duplicates the attributes of the given object. The copy constructor is called when an object is passed by value, returned by value, or explicitly copied. It ensures that the new object has the same state as the copied object.

### Syntax:-
```
Inside Class Definition:

ClassName(parameters) { 
    // implementation 
}
```
#### Destructor 
A destructor is a special member function that is automatically called when an object goes out of scope or is explicitly deleted. The destructor has the same name as the class, preceded by a tilde (~), and it has no return type or parameters. Destructors are primarily used to release resources, such as memory or file handles, ensuring that objects clean up after themselves when they are no longer needed.
## Output:
