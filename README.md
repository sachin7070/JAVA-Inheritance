# Inheritance in Java

In Java, inheritance is a fundamental concept of Object-Oriented Programming (OOP). It allows one class to inherit the properties and behaviors (fields and methods) of another class. This README provides an overview of inheritance in Java, including its importance, terminology, syntax, and examples.

## Why Java Inheritance?

Java inheritance serves several purposes:

- **Code Reusability**: Subclasses can directly use the code written in their superclass, promoting code reuse.
- **Method Overriding**: Inheritance enables method overriding, facilitating runtime polymorphism.
- **Abstraction**: Inheritance supports abstraction by allowing subclasses to inherit abstract functionality from their superclass, hiding implementation details.
  
## Terminology

- **Class**: A blueprint or template for creating objects that share common characteristics and behaviors.
- **Superclass/Parent Class**: The class whose features are inherited is known as the superclass, base class, or parent class.
- **Subclass/Child Class**: The class that inherits from another class is known as the subclass, derived class, extended class, or child class.
- **Reusability**: Inheritance promotes code reuse by allowing the creation of new classes based on existing ones.

## Types of Inheritance

Java supports several types of inheritance:

### Single Inheritance

Single inheritance involves one class extending another class. In this type of inheritance, a subclass inherits from only one superclass.

```java
class Superclass {
    // Superclass members
}

class Subclass extends Superclass {
    // Subclass members
}
