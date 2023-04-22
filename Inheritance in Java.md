
#java 

It is the mechanism by which one class is allowed to inherit the features of another class
This means creating new classes based on existing ones
A class that inherits from another class can reuse methods and fields of that class
It represents a *parent-child* relationship

###### Some important words
1. ***Super/Base/Parent Class*** - The class whose features are inherited.
2. ***Sub/Derived/Child*** - The class that inherits the features of the base class. It can add its own fields and methods.

***Why do we need inheritance in java?***
1. **Code Reuseability** - The code written in the super class is common to all sub classes
2. **Method Overriding** -This can be achieved only through inheritance. It is one method to achieve *Run Time Polymorphism*
3. **Abstraction** - The concept of abstraction is achieved only through inheritance

###### Syntax
The `extends` keyword is used. For example:
```java
class derievedClass extends baseClass {
	// Your Code
}
```

###### Types
There are **3** main types of inheritance in java
![[Pasted image 20230417230336.png]]

##### Method Overriding
*If a base class and derived class have a method with same name but different parameter list, then it is called as method overloading.

But, If a base class and derived class have a method with same name and same parameter list, then it is called as method overriding.*

***Usage of  Method Overriding***
- Provides the specific implementation of a method already defined in the parent class
- Used for run-time polymorphism

***Rules for Method Overriding***
1. The method must have the same name as in the parent class
2. The method must have the same parameters as in the parent class
3. There must be inheritance and a IS-A relationship

###### The `final` Keyword
- If the field member is declared final then the variable value becomes constant.
- If a method is declared as final then that method cannot be overridden.
- If a class is declared as final then that class cannot have any sub-class i.e. no class can be derived from a final class.

### Abstract Classes
In any programming language, a class which is declared with the keyword abstract is known as an abstract class. An abstract class captures common characteristics of subclasses and may or may not contain any abstract method. It cannot be instantiated but can be only used as a superclass by its subclasses.

***The Features of Abstract Classes are***
1. Abstract classes are used to declare common characteristics of subclasses.
2. Abstract classes are declared with keyword abstract followed by class definition. They provide template for subclasses.
3. No object can be made of abstract class. It can be used as a base class for other classes that are derived from the abstract class.
4. An abstract class can contain fields and methods. It can have abstract and non-abstract methods
5. Methods of abstract class can have only declaration and no definition. **These methods are known as Abstract Methods**
7. Abstract methods must be overridden.
8. If a class has any abstract method, the class becomes abstract and must be declared as abstract.

### The `super` Keyword
- The super keyword in Java is a reference variable which is used to refer immediate parent class object.
- If you want to access a member of a base class from the derived class, then the super keyword is used.
- Whenever you create the instance of subclass, an instance of parent class is created implicitly which is referred by super reference variable.

![[Pasted image 20230417232442.png]]
