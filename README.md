# Programming Principles and Methodologies

<br>

- [SOLID](#solid)
- [KISS](#kiss)
- [DRY](#dry)
- [YAGNI](#yagni)

<br>

## SOLID


SOLID is an acronym for the first five object-oriented design (OOD) principles by Robert C. Martin

Design Principles and Design Patterns -- Robert C. Martin(Uncle Bob)
[https://web.archive.org/web/20150906155800/http://www.objectmentor.com/resources/articles/Principles_and_Patterns.pdf](https://web.archive.org/web/20150906155800/http://www.objectmentor.com/resources/articles/Principles_and_Patterns.pdf)

<br>

- S - Single-responsiblity Principle
- O - Open-closed Principle
- L - Liskov Substitution Principle
- I - Interface Segregation Principle
- D - Dependency Inversion Principle

<br>
<hr>

### Single-Responsibility Principle

    A class should have one and only one reason to change, meaning that a class should have only one responsibility.
    Not to add too many responsibilities as classes get more complicated. Refactor and break them up into smaller classes and modules.

<br>

### Open-closed Principle

    Objects or entities should be open for extension but closed for modification.
    A class should be extendable without modifying the class itself.

<br>

### Liskov Substitution Principle

    Let q(x) be a property provable about objects of x of type T. Then q(y) should be provable for objects y of type S where S is a subtype of T.
    Every subclass or derived class should be substitutable for their base or parent class.

<br>

### Interface Segregation Principle

    A client should never be forced to implement an interface that it doesn’t use, or clients shouldn’t be forced to depend on methods they do not use.
    If you have a class that has several clients, rather than loading the class with all the methods that the clients need, create specific interfaces for each client and multiply inherit them into the class.

<br>

### Dependency Inversion Principle

    Entities must depend on abstractions, not on concretions. It states that the high-level module must not depend on the low-level module, but they should depend on abstractions.

<br>
<br>

## KISS


### Keep It Simple, Stupid (KISS)

    Designs or systems should be as simple as possible.
    The KISS principle states that most systems work best if they are kept simple rather than made complicated. Simplicity should be a key goal in design, and unnecessary complexity should be avoided
    It was Albert Einstein who said; “If you can’t explain it, you don’t understand it well enough.”

<br>

## DRY



### Don't repeat yourself (DRY)

    Every piece of knowledge must have a single, unambiguous, authoritative representation within a system.
    The main purpose of DRY of which is to reduce the repetitionof code.

<br>

## YAGNI



### You aren't gonna need it (YAGNI)

    A programmer should not add functionality until deemed necessary.
    Always implement things when you actually need them, never when you just foresee that you need them

