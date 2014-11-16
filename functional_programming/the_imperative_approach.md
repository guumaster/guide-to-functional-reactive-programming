## The imperative approach

You can read about [Imperative Programming](http://en.wikipedia.org/wiki/Imperative_programming) and [Procedural Programming](http://en.wikipedia.org/wiki/Procedural_programming) in the Wikipedia.

Now we will see some code. A normal for loop, and a way to write it in a better way.

### The old way
This is how you may be coding loops in JavaScript:

```js
var data = [1, 2, 3], i, new_data = [];
for(i=0, i<data.length;i++) {
    new_data[i] = data[i] * 2;
}
console.log( new_data );
// -> [ 2, 4, 6 ]
```

> **Danger** ***Stop it***!. Seriously, ***stop doing this right now***. This is too verbose and ugly.


### A less ugly manner

The first step towards becoming more functional is to start using array functions.

In **ES5**:
```js
var data = [1,2,3, new_data=[];

data.forEach(function(i,val){
    new_data[i] = val * 2;
});

console.log( new_data );
// -> [ 2, 4, 6 ]
```

In **ES6** with the fat arrow notation:
```js
var data = [1,2,3], new_data = [];

data.forEach( (i, val) => new_data[i] = val * 2; );

console.log( new_data );
// -> [ 2, 4, 6 ]
```

### The future is here

In **ES6** with the fat arrow notation:
```js
var data = [1,2,3],
    new_data = data.map( val => val * 2 );

console.log( new_data );
// -> [ 2, 4, 6 ]
```
> **Success** Wow! That was shorter, simpler, easier to read and more beautiful to look at.
