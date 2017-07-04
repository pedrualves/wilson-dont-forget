# Wilson don't forget!

This simple example using filter

```javascript
const numbers = [1,2,3,4,5,1,1,1]

console.log('array with numbers ', numbers)
console.log('array numbers distinct to 1 ', numbers.filter(n => {return n != 1}))
console.log('array numbers equals to 1 ' , numbers.filter(n => {return n === 1}))

const objects = [{o:1},{o:2},{o:3},{o:4},{o:5},{o:1},{o:1},{o:1}]

console.log('array with objects ', objects)
console.log('array objects distinct to 1 ', objects.filter(o => {return o.o != 1}))
console.log('array objects equals to 1 ', objects.filter(o => {return o.o === 1}))
```
