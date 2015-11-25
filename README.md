# Design Patterns Study
This project is a study into object oriented and functional design patterns, implemented in Scala. It is for my own study 
and future reference but if you find the subject matter interesting and if the information here helps you in your study
then I would be glad! :)

I'm confident in having a good understanding of design patterns, and enough insight / experience when to apply them
is key into creating agile software and therefor supporting the goals of agile software development like [Disciplined
Agile Delivery](http://www.disciplinedagiledelivery.com/).

[![Build Status](https://travis-ci.org/dnvriend/design-patterns-study.svg?branch=master)](https://travis-ci.org/dnvriend/design-patterns-study)
[![License](http://img.shields.io/:license-Apache%202-red.svg)](http://www.apache.org/licenses/LICENSE-2.0.txt)

# What are Patterns?
There are different categories of software patterns:
* Architectural patterns: big broad things that can describe an entire computer system. They are programming language
 agnostic, but talk about how all the different subsystems and components fit together,
* Design patterns: patterns that describe how things happen in a single component, how a program is structured, how the data flows, 
how the execution flows, etc..
* Idioms: (pattern oriented software); specific to a single programming language; examples of a design pattern 
implemented in a programming language, or smaller localized patterns that are seen in a particular programming language

# Object Oriented Design Patterns
The following (23) patterns describe creational, structural and behavioral patterns are fully described in the Gang of Four
book 'Design Patterns: Elements of Reusable Object-Oriented Software'

## Creational (5)
Creational patterns are patterns that create object for you; hence creational. The goal here is, rather than having your 
code instant object directly and therefor having all the logic about how to create (sometimes complex initialization 
logic surrounding objects), the creational pattern will do that for you. This has a second benefit, in that having all
the creational logic in one place, changes to that logic will propagate to where the new object is needed. 

* Abstract factory pattern: groups object factories that have a common theme.
* Builder pattern: constructs complex objects by separating construction and representation.
* __Factory method pattern__: creates objects without specifying the exact class to create.
* Prototype pattern: creates objects by cloning an existing object.
* __Singleton pattern__: restricts object creation for a class to only one instance.

## Structural (7)
Structural patterns concern class and object composition; hence structural. They use inheritance to compose interfaces 
and define ways to compose objects to obtain new functionality.

* __Adapter pattern:__ allows classes with incompatible interfaces to work together by wrapping its own interface around that of an already existing class.
* Bridge pattern: decouples an abstraction from its implementation so that the two can vary independently.
* __Composite pattern:__ composes zero-or-more similar objects so that they can be manipulated as one object.
* __Decorator pattern:__ dynamically adds/overrides behaviour in an existing method of an object.
* __Facade pattern:__ provides a simplified interface to a large body of code.
* Flyweight pattern: reduces the cost of creating and manipulating a large number of similar objects.
* __Proxy pattern:__  provides a placeholder for another object to control access, reduce cost, and reduce complexity.

## Behavioral (11)
Behavioral patterns are specifically concerned with communication between objects, hence behavioral.

* Chain of responsibility pattern: delegates commands to a chain of processing objects.
* __Command pattern:__ creates objects which encapsulate actions and parameters.
* Interpreter pattern: implements a specialized language.
* __Iterator pattern:__ accesses the elements of an object sequentially without exposing its underlying representation.
* [Mediator pattern](https://sourcemaking.com/design_patterns/mediator): allows loose coupling between classes by being the only class that has detailed knowledge of their methods.
* Memento pattern: provides the ability to restore an object to its previous state (undo).
* __Observer pattern:__ is a publish/subscribe pattern which allows a number of observer objects to see an event.
* __State pattern:__ allows an object to alter its behavior when its internal state changes.
* Strategy pattern:  allows one of a family of algorithms to be selected on-the-fly at runtime.
* __Template method pattern:__ defines the skeleton of an algorithm as an abstract class, allowing its subclasses to provide concrete behavior.
* Visitor pattern: separates an algorithm from an object structure by moving the hierarchy of methods into one object.

# Replacing Object Oriented Patterns with Functional Patterns

* Replacing Functional Interface
* Replacing state-carrying functional interface
* Replacing command
* Replacing Builder for Immutable Objects
* Replacing Iterator
* Replacing Template Method
* Replacing Strategy
* Replacing Null Object
* Replcing Decorator
* Replacing Visitor
* Replacing Dependency Injection

# Functional Patterns

* Monoid Pattern
* Functor Pattern
* Applicative Functor Pattern
* Type Class Pattern
* Tail Recursion
* Mutual Recursion
* Filter-Map-Reduce
* Chain of operations
* Function Builder
* Memoization
* Lazy Sequence
* Focused Mutability
* Customized Control Flow
* Domain-Specific Language

# Reactive Design Patterns

## Video's
* [Stuart Sierra - Functional Design Patterns](https://www.youtube.com/watch?v=etr08mExAI0)

# Links
* [Design Pattern in Simple Examples](http://www.go4expert.com/articles/design-pattern-simple-examples-t5127)

# Books
* Pattern oriented software architecture