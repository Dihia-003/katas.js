# Minimum

Write a function min that takes two arguments and returns their minimum.


```
console.log(min(0, 10));
// → 0
console.log(min(0, -10));
// → -10

```
``` 
Solution:

function min(a, b) {
    return a < b ? a : b;
}
console.log(min(0, 10));
console.log(min(0, -10));

```
