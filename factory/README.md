# Factory design pattern

- [General info](#general-info)
- [Resources](#resources)

## General info

In _object-oriented programming_, a **factory** is an object for creating other objects; formally, it is a function or method that returns objects of a varying prototype or class from some method call, which is assumed to be _"new"_. More broadly, a subroutine that returns a _"new"_ object may be referred to as a _"factory"_, as in **factory method** or **factory function**. The **factory pattern** is the basis for a number of related software design patterns.

In _class-based programming_, a **factory** is an abstraction of a constructor of a class, while in _prototype-based programming_ a **factory** is an abstraction of a prototype object. A constructor is concrete in that it creates objects as instances of a single class, and by a specified process (class instantiation), while a **factory** can create objects by instantiating various classes, or by using other allocation schemes such as an object pool. A prototype object is concrete in that it is used to create objects by being cloned, while a **factory** can create objects by cloning various prototypes, or by other allocation schemes.

A **factory** may be implemented in various ways. Most often it is implemented as a method, in which case it is called a **factory method**. Sometimes it is implemented as a function, in which case it is called a **factory function**. In some languages, constructors are themselves factories. However, in most languages they are not, and constructors are invoked in a way that is idiomatic to the language, such as by using the keyword _new_, while a **factory** has no special status and is invoked via an ordinary method call or **function call**. In these languages, a **factory** is an abstraction of a constructor, but not strictly a generalization, as constructors are not themselves factories.

Terminology differs as to whether the concept of a **factory** is itself a design pattern – in Design Patterns there is no _"factory pattern"_, but instead two patterns (**factory method pattern** and **abstract factory pattern**) that use factories. Some sources refer to the concept as the **factory pattern**, while others consider the concept itself a programming idiom, reserving the term _"factory pattern"_ or _"factory patterns"_ to more complicated patterns that use factories, most often the **factory method pattern**; in this context, the concept of a **factory** itself may be referred to as a **simple factory**. In other contexts, particularly the Python language, _"factory"_ itself is used, as in this article. More broadly, _"factory"_ may be applied not just to an object that returns objects from some method call, but to a subroutine that returns objects, as in a **factory function** (even if functions are not objects) or **factory method**. Because in many languages factories are invoked by calling a method, the general concept of a **factory** is often confused with the specific **factory method pattern design pattern**.

## Resources

* [Wikipedia: Factory pattern](https://en.wikipedia.org/wiki/Factory_(object-oriented_programming))
* [Wikipedia: Abstract factory pattern](https://en.wikipedia.org/wiki/Abstract_factory_pattern)
* [Wikipedia: Factory method pattern](https://en.wikipedia.org/wiki/Factory_method_pattern)
* [sbcode.net: Factory Design Pattern](https://sbcode.net/typescript/factory/)
* [sbcode.net: Abstract Factory Design Pattern](https://sbcode.net/typescript/abstract_factory/)
* [refactoring.guru: Factory Method](https://refactoring.guru/design-patterns/factory-method)
* [refactoring.guru: Abstract Factory](https://refactoring.guru/design-patterns/abstract-factory)
* [Design patterns in TypeScript: Factory](https://thedulinreport.com/2017/07/30/design-patters-in-typescript-factory/)
* [JavaScript Patterns: Factory](https://javascriptpatterns.vercel.app/patterns/design-patterns/factory-pattern)
* [Factory Design Pattern in TypeScript](https://blog.bitsrc.io/factory-design-pattern-in-typescript-55a91d74f3a4)
* [4 Ways to Implement Factory Pattern in JavaScript](https://itnext.io/4-ways-to-implement-factory-pattern-in-javascript-2e019c2a9ada)
* [2 Ways to Implement Abstract Factory Pattern in JavaScript](https://itnext.io/2-ways-to-implement-abstract-factory-pattern-in-javascript-85f151bd5cbe)
* [Extendable Factory Pattern for React Using TypeScript](https://betterprogramming.pub/extendable-factory-pattern-for-react-using-typescript-3298c59fefd8)
* [Understanding the Abstract Factory Design Patterns](https://betterprogramming.pub/understanding-the-abstract-method-design-patterns-bc416aaaf076)
* [Abstract Factory pattern in TypeScript](https://dev.to/jmalvarez/abstract-factory-pattern-in-typescript-6c8)
* [Abstract Factory in Typescript (GoF Design Pattern)](https://medium.com/@cristianalemanfuentes/abstract-factory-in-typescript-gof-design-pattern-e8f661e49071)
* [Design Patterns: Factory Method Pattern in TypeScript](https://javascript.plainenglish.io/design-patterns-factory-method-pattern-in-typescript-c4c3047a6289)
* [Design Patterns: Abstract Factory Pattern in TypeScript](https://javascript.plainenglish.io/design-patterns-abstract-factory-pattern-in-typescript-84cd7b002964)
* [Understanding Design Patters: Factory Method](https://www.carloscaballero.io/understanding-design-patters-factory-method/)
* [Abstract Factory Method](https://medium.com/@bindubc/abstract-factory-method-4866520858a1)
* [Abstract Factory Design Pattern Down to Earth](https://www.pentalog.com/blog/design-patterns/abstract-factory-design/)
* [Factory Comparison](https://refactoring.guru/design-patterns/factory-comparison)
* [Stackoverflow: What are the differences between Abstract Factory and Factory design patterns?](https://stackoverflow.com/questions/5739611/what-are-the-differences-between-abstract-factory-and-factory-design-patterns)
* [Stackoverflow: What is the difference in case of intent and application between these two Patterns?](https://stackoverflow.com/questions/1001767/what-is-the-difference-in-case-of-intent-and-application-between-these-two-patte)
* [Stackoverflow: Design Patterns: Factory vs Factory method vs Abstract Factory](https://stackoverflow.com/questions/13029261/design-patterns-factory-vs-factory-method-vs-abstract-factory)
* [Stackoverflow: Design Patterns: Abstract Factory vs Factory Method](https://stackoverflow.com/questions/4209791/design-patterns-abstract-factory-vs-factory-method)
* [Medium: Factory vs Factory Method vs Abstract Factory](https://medium.com/bitmountn/factory-vs-factory-method-vs-abstract-factory-c3adaeb5ac9a)
* [1. Design Pattern:- Factory Method & Abstract Factory](https://levelup.gitconnected.com/1-design-pattern-factory-method-abstract-factory-bb162910050)
* [anirudh bhatnagar: Difference between Factory and Abstract Factory](https://anirudhbhatnagar.com/2011/01/04/difference-between-factory-and-abstract-factory/)
* [DZone: Factory Method vs Abstract Factory (again?)](https://dzone.com/articles/factory-method-vs-abstract)
* [Factory Method vs. Factory vs. Abstract Factory](https://www.baeldung.com/cs/factory-method-vs-factory-vs-abstract-factory)
* [Factory Pattern in TypeScript: Simplify Coding Secrets](https://justcode.me/design-patterns/factory-pattern-in-typescript/)
* [Wennovation Academy: Factory Method Pattern | Implementation in TypeScript](https://www.youtube.com/watch?v=mVn8_I9QtPA)
* [Wennovation Academy: Abstract Factory Pattern | Implementation in TypeScript](https://www.youtube.com/watch?v=sj5ALZEoOhg)
* [Christopher Okhravi: Factory Method Pattern – Design Patterns (ep 4)](https://www.youtube.com/watch?v=EcFVTgRHJLM)
* [Christopher Okhravi: Abstract Factory Pattern – Design Patterns (ep 5)](https://www.youtube.com/watch?v=v-GiuMmsXj4)
* [devszczepaniak.pl: Wzorzec projektowy Factory (Fabryka)](https://devszczepaniak.pl/wzorzec-projektowy-factory-fabryka/)