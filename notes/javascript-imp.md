# Important Javascript Concepts

This file contains explainations to important javascript concepts that I forget frequently

The main difference is that nullish coalescing(??) operator will only give the result as the right operand only if the left operand is either null or undefined.

Whereas the OR(||) operator will give the result as right operand for all the falsy values of the left operand.

Below are some examples

```js
const a = 0;
// a || 10 --> Will result in 10, as || operator considers 0 as falsy value and resulting the right side operand
console.log(`a || 10 = ${a || 10}`);
// a ?? 10 --> Will result in 0, as ?? operator considers 0 as truthy value and resulting the left side operand
console.log(`a ?? 10 = ${a ?? 10}`);
```
