# A word about ES6 arrow functions

The next version of JavaScript will bring us new and better ways to write our code.

A very nice feature would be the addition of the Arrow Function or Fat Arrow Function notation.

If we would "*translate*" it to something we already do today, it would be something like this:

```js
// this function
var func = function (param) {
    return param.split(" ");
}

// would become:
var func = param => param.split(" ");

console.log( func('Hello ES6 World!') );
// ->  [ "Hello", "ES6", "World!" ]
```

You can use this feature right now, at least in Firefox 22+. Because of the simplicity that this notation provides, I'll be using it for some of the examples.

#### More info

* [ES6 Arrow functions](http://es6rocks.com/2014/10/arrow-functions-and-their-scope/)
* [Arrow function in MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)
