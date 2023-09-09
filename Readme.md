# Programming Concepts

This document holds some common PF concepts till some advance concepts that could be asked in an interview, or that a software engineer should be aware off. I've just jotted down concepts and very basic definitions, please be-aware that this is NOT ALL!

## 👶 Basics

Following concepts belongs to a basic level:

### Program

A specific set of instructions that tells the computer/machine what to do, how to do and when to do.

### Compile time vs Runtime

- Compile time is the concept when a programming code (c++, python, dart etc.) is being converted into machine code.
- Runtime is when a program is running generally occurs after compile time.

### Types of Errors

- Syntax
- Logical error
- Compilation error

### Library vs SDK vs Framework

- Library is a chunk of code that you can call from your own code to get some job done. For example, math library can help you with mathematical functions that you’d need to write down all by yourself

- SDK is a group of multiple libraries. For example, Windows/MacOS/Office etc.

- Framework is somewhat similar to SDK, it consists of huge group of libraries that are specific for some job. For example, .NET → Mostly used for Desktop apps. Flutter → Mostly used for cross platforms and so on.

## 👦 Intermediate

Following concepts belongs to an intermediate level:

### OOP

- Object oriented programming (OOP) is a style of write a program. It’s not an SDK, it’s not a language but just a way of writing a program. It holds 4 major pillars:
    - Abstraction => Hiding of functionality
        - `abstract` classes => partial abstraction
        - `interface` => complete abstraction
    - Inheritance
    - Encapsulation => Hiding of data
    - Polymorphism
        - Overriding => Dynamic polymorphism, occurs at runtime
        - Overloading => Static polymorphism, occurs at compile time
            - Same name of methods in Same class
            - Can have, different number of params, different return type and different param types


### SOLID Principle
The word "SOLID" is an abbreviation of:
- Single Responsibility Principle
    - A class should have one reason to change i.e. one responsibility or one job to handle. 
- Open-Closed Principle
    - Classes should be open for extension and closed for modification.
- Liskov Substitution Principle
    - Superclasses should be complete replaceable of their subclasses.
- Interfaces Segregation Principle
    - "Segregation" means separated, so it's better to have multiple interfaces rather than a general interface that is being used by classes which doesn't require most of the functionality.
- Dependency Inversion Principle
    - Classes should be depending on `abstract` classes or `interfaces` rather than depending on concrete classes.