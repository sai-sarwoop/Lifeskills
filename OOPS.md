new
(OOPs called as) Object-oriented programming system.

*  "Object Oriented Programming” is a popularly known and widely used concept in modern programming languages like Java.

*  This programming concept is to works on the principles of abstraction, encapsulation, inheritance, and polymorphism.

*  It allows users to create objects they want and create methods to handle those objects. 

*  Aim : The main aim of the oops concept is to impliment real-words into the programs.

# [img]https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.scaler.com%2Ftopics%2Fwhat-is-object-oriented-programming-oop%2F&psig=AOvVaw0fVwyrElOnQJ2FXEpmJ-Fd&ust=1669456845299000&source=images&cd=vfe&ved=0CA8QjRxqFwoTCNDlvcOJyfsCFQAAAAAdAAAAABAE 

# Benefits of OOPS:

* It is easy to resolve the huge problem and breaking it down to be solvad.

* OOP systems can be easily upgraded from small to large systems.

* We can develop the programs from starting work modules that communicate with one another.

* writing  the code from abrasion which leads to saving of development time and advanced productivity.

# disadvantages of OOPS:

* The lenghty of programs are developed by the help of OOPS.

* Since the program becomes larger in size , it consumes more to complete the proram and it leades to slow down the program .

* And the main think is to be know note we cont use the oops at everywhere because it is not a universal language . and it is applyed we it is requeied.

## Types of oops languages:

*  **Class**

*  A class is a definition of the method and variable in a particular kind of object. 

*  And the class is one of the defining ideas of object-oriented programming.

*  The structure of a class and its subclasses is called the class hierarchy.

-
-
-
-
-
-
-
<> For example <>

(Example for class)

//Class body containing variables and methods//

public class Student
{
  String name;
  int age;
        void display()
  {
         //method body;
  }
}
Code Snippet:

//declaring a class
public class Person
{ //class body starts here

  //creating the data members of the class
  static String name = "John";
  static int age = 25;

  //creating the methods of the class
  void eat()
  {
    //methodBody
  }
  void study()
  {
    //methodBody
  }
  void play()
  {
    //methodBody
  }
  public static void main(String args[])
  {
    System.out.println("Name of the person: " +name)
    System.out.println("Age of the person: " +age)
  }
} class body ends here.md


**Object**

* An object in OOPS is nothing but a self-contained.

* It consists of methods and properties to make a particular type of data.

* object in OOPS is a specimen of a class.

* Objects are allocated memory space and address too.

**Polymorphism**

 ## In Java polymorphism is mainly divided into two types ##


> Compile-time Polymorphism <

* It is also known as static polymorphism.
* polymorphism is achieved by function overloading or operator overloading. 
* But the main thing is java doesn’t support the Overloading.


> Runtime Polymorphism <

* polymorphism is achieved by Method Overriding. 
* And it is also called as Dynamic Method Dispatch.
* In Run time Polymorphism, the call is not resolved by the compiler.
* It is achieved by virtual functions and pointers.


**Inheritance**

## **Types of Inheritance** :  - Single    - Multiple    - Multilevel    - Hybrid    - Hierarchical.


* It is a mechanism in which one object comes into  all the properties and behaviors of a parent object.
* It is an important part of OOPs (Object Oriented programming system.
* The idea behind inheritance in Java is that you can create new classes.and that are build upon the existing classes.
* Reusability of code can be achieved because of inheritance. If we want to create a class that already has some common methods    which we want to define within .

<> For example <>

Example for Inheritance:

## //Base class
class Person
{
  String name = "John";
  int age =17;
  String city = "Delhi";
  public void show()
  {
    System.out.println("Student inheriting properties from Person:\n");
  }
}
//child class
class Student extends Person
{
  // defining additional properties to child class
  int marks = 78;
  String tutorial = "TechVidvan Tutorial of Java";
  public static void main(String args[])
  {
    Student obj = new Student();
    obj.show();
    System.out.println("Name of the student is: " + obj.name);
    System.out.println("Age of the student is: " + obj.age);
    System.out.println("Student lives in: " + obj.city);
    System.out.println("Student learns from: " + obj.tutorial);
    System.out.println("Marks obtained by the student is: " + obj.marks);
  }
}

## **Abstraction**

* In java, abstraction is achieved by interfaces and abstract classes. We can achieve abstraction using interfaces.
* Data Abstraction is the property of which of which displayed to the user.
* The trivial or the non-essential units are not displayed to the user.
* Data Abstraction may also be defined as the process of identifying characteristics of an object.
  bstract class Animal {
  abstract void makeSound();

  public void eat() {
    System.out.println("I can eat.");
  }
}

class Dog extends Animal {

  // provide implementation of abstract method
  public void makeSound() {
    System.out.println("Bark bark");
  }
}

class Main {
  public static void main(String[] args) {

    // create an object of Dog class
    Dog d1 = new Dog();

    d1.makeSound();
    d1.eat();
  }
}















