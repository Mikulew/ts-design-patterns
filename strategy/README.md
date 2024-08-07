# Strategy design pattern

- [General info](#general-info)
- [Resources](#resources)

## General info

In computer programming, the **strategy pattern** (also known as the **policy pattern**) is a behavioral software design pattern that enables selecting an algorithm at runtime. Instead of implementing a single algorithm directly, code receives runtime instructions as to which in a family of algorithms to use.

Strategy lets the algorithm vary independently from clients that use it. Strategy is one of the patterns included in the influential book *Design Patterns* by *Gamma et al*. that popularized the concept of using design patterns to describe how to design flexible and reusable object-oriented software. Deferring the decision about which algorithm to use until runtime allows the calling code to be more flexible and reusable.

For instance, a class that performs validation on incoming data may use the strategy pattern to select a validation algorithm depending on the type of data, the source of the data, user choice, or other discriminating factors. These factors are not known until runtime and may require radically different validation to be performed. The validation algorithms (strategies), encapsulated separately from the validating object, may be used by other validating objects in different areas of the system (or even different systems) without code duplication.

Typically, the strategy pattern stores a reference to code in a data structure and retrieves it. This can be achieved by mechanisms such as the native function pointer, the first-class function, classes or class instances in object-oriented programming languages, or accessing the language implementation's internal storage of code via reflection.

## Resources

* [Wikipedia: Strategy pattern](https://en.wikipedia.org/wiki/Strategy_pattern)
* [sbcode.net: Strategy Design Pattern](https://sbcode.net/typescript/strategy/)
* [refactoring.guru: Strategy](https://refactoring.guru/design-patterns/strategy)
* [dev.to: Design Pattern: Strategy (TS)](https://dev.to/daniyarotynshin/design-pattern-strategy-ts-3e55)
* [Medium: Design Patterns with Typescript: Strategy](https://medium.com/@gabriel_avila/design-patterns-with-typescript-strategy-35007cbcd57a)
* [codeburst.io: Implementing Strategy pattern on TypeScript](https://codeburst.io/implementing-strategy-pattern-on-typescript-b74c447da37b)
* [devmaking: Strategy in TypeScript ](https://devmaking.com/learn/design-patterns/strategy-pattern/typescript/)
* [Strategy Design Pattern in TypeScript](https://blog.bitsrc.io/a-beautiful-design-pattern-strategy-pattern-62afe44886fc)
* [Valentino Gagliardi: Avoiding death by thousands ifs with the strategy pattern](https://www.valentinog.com/blog/strategy-pattern-javascript/)
* [How to correctly implement strategy design pattern](https://stackoverflow.com/questions/60107761/how-to-correctly-implement-strategy-design-pattern)
* [Implementing Strategy Pattern and Callbacks in TypeScript](https://visualstudiomagazine.com/articles/2015/10/01/implementing-strategy-pattern.aspx)
* [Christopher Okhravi: Strategy Pattern – Design Patterns (ep 1)](https://youtu.be/v9ejT8FO-7I?si=RRyZwKh-eO46PqkS)
* [Christopher Okhravi: Strategy Pattern Screencast – OO Design Patterns Screencasts (ep 1)](https://www.youtube.com/watch?v=13nftsQUUE0)
* [Christopher Okhravi: Strategy Pattern (in real life) Screencast – OO Design Patterns Screencasts (ep 2)](https://www.youtube.com/watch?v=slfeCvztnT4)