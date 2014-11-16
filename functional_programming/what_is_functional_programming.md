## What is functional programming

Functional programming produces abstraction through clever ways of combining functions. A programmer armed with a repertoire of fundamental functions and, more importantly is much more effective than one who starts from scratch.

Imperative programs tend to emphasize the series of steps taken by a program in carrying out an action, while functional programs tend to emphasize the composition and arrangement of functions.

### Differences is from OOP

The biggest difference between the two *schools of thought* concerns the relationship between data and operations on the data.

The central tenet of OOP is that data and the operations upon it are tightly coupled: An object owns its data and it owns the implementation of the operations on the data. It hides those from other objects via its interface, a collection of methods or messages it responds to. Thus, the central model for abstraction is the data itself, hidden as it is behind a small API in the form of its interface.

The central activity in OOP is composing new objects and extending existing objects by adding new methods to them.

The central tenet of FP is that data is only loosely coupled to functions. You can write different operations on the same data structure, and the central model for abstraction is the function, not the data structure. Functions hide their implementation, and the language’s abstractions speak to functions and they way they are combined or expressed, such as generic functions or combinators.

The central activity in FP is writing new functions.



### More info
- [Eloquent Javascript](http://eloquentjavascript.net/1st_edition/chapter6.html)
- [FP vs OOP](http://raganwald.com/2013/04/08/functional-vs-OOP.html)
