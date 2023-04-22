
#java 

Java is a high-level, robust, secure programming language
It was developed in 1995 by Sun Microsystems

### The basic concepts of OOP are:
1. Objects - Objects are instances of classes
2. Classes - Classes are templates of objects
3. Inheritance - Inheritance is when an object acquires another objects properties
4. Polymorphism - Polymorphism is the ability of an object or method to do more than one action
5. Abstraction - Abstractions is a process that displays only relevant information and hides unnecessary information
6. Encapsulation - Encapsulation is wrapping up data and methods is a single unit

### Methods in java
A method is a block of code or collection of statements or a set of code grouped together to perform a certain task or operation. It is used to achieve the re-usability of code. We write a method once and use it many times. We do not require to write code again and again.

##### Method Header
A method has 6 components called it's method signature
1. **Access Specifier** - Access specifier or modifier is the access type of the method. It specifies the visibility of the method. Java provides four types of access specifiers.
2. **Return Type** - Return type is a data type that the method returns. It may have a primitive data type, object, collection, void, etc. If the method does not return anything, we use void keyword.
3. **Method Name** - It is a unique name that is used to define the name of a method. It must be corresponding to the functionality of the method. A method is invoked by its name.
4. **Parameter List** - It is the list of parameters separated by a comma and enclosed in the pair of parentheses. It contains the data type and variable name. If the method has no parameter, we leave the parentheses blank.

##### Access Specifiers
Java has 4 types of access specifiers
1. **Default** - The scope is within the package
2. **Public** - The scope is within or outside the class, within or outside the package
3. **Protected** - The scope is within the package or through an inherited or child class
4. **Private** - The scope is within the class
![[Pasted image 20230415122356.png]]

##### Recursive Method
- A method that invokes itself is called a recursive method
- In order to stop a recursive method from calling itself infinitely we need to provide some exit condition
![[Pasted image 20230415122727.png]]

### Classes and Objects
#### Classes Basics
A class is a group of objects having common properties, It acts as the template for creating objects. It is a logical entity not a physical one. 
A class contains:
1. Fields
2. Methods
3. Constructors
4. Blocks
5. Nested classes and interfaces

#### Objects
An entity that has a state and behaviour is known as an object
It can be physical or logical
An object has 3 characteristics: 
1. **State** - Represents the data of an object
2. **Behaviour** - Represents the functionality of an object
3. **Identity** - An object is typically implemented via a unique id, which is not visible to the user but used to uniquely identify the object by the JVM
***A class is a template or blueprint from which objects are created. So, an object is the instance (result) of a class.***

**Defining and Object**
1. An object is a *real-world entity*
2. An object is a *runtime entity*
3. An object is an *entity with state and behaviour*
4. An object is an *instance of a class*

##### Array of Objects
An array of objects is created to store information about multiple objects having similar functionality
The syntax is `class_name object_name[] = new class_name[];`
***MEMORY IS NOT ALLOCATED YET***, memory is allocated once `new()` is used on the individual object

##### Constructors
It is a special method that initialises objects.
It is called when an object of the class is created.
It is used to set initial values of an object.
Every time an object is created with *new()* a constructor is called

There are 2 types of constructors:
1. *No-Arg Constructor (Default Constructor)* takes no arguments
2. *Parameterised Constructor* takes arguments

Rules for creating constructors are:
1. The constructor must be **public/protected/default**
2. The constructor **cannot have a return type**, not even void
3. There can be **more than one constructor** but each must have a **different parameter list**

##### Overloading
- Multiple constructors of same class with different parameters is called constructor overloading
- Multiple methods with same name in same class or in base class and derived class with different parameters is called method overloading

Advantages of **Method Overloading**
1. It increases the readability of a program
2. It provides flexibility so they can call the same methods for different programs
3. It makes the code look clean
4. It reduces execution time
5. It increases the reuse-ability of code

*Method overloading can be achieved by changing the number of arguments or the datatype*

### Static 
The `static` keyword is used to declare class members as static
A static method is one that works on the class and not on the object
It can be called by `class_name.method_name(parameter_list)`
A static variable will be common for all objects of the class
We can use them to count the number of objects created of a class

### This
The `this` keyword refers to the current object

![[Pasted image 20230417223927.png]]
