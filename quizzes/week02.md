# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
var let const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
they are a subprogram to perform a particular task. 
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
S - single responsibility functions
o - open for easy expansion / closed for breaking functioning code
l - liskov, code should be written in such a way that subclasses can replace parent classes without breaking
i - interface segregation clients should never be force to use code that they don't need
d - dependency inversion 
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
pineapple is at position 2, arrays start counting with 0, so this array's 5 items would be indexed 0-4
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you[friends].push(them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
if(3 > 2) {return 'Three is greater than two'}
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
  incrementor, i++
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
Document Object Model, the html file
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
bool, null, undefined, number, string, symbol, bigInt, objects, arrays
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
arguments are the value that will be used function. parameters are the placeholders used in the creation of the function that will pass the values from the arguements.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
 primitive values are stored individually and do not have properties that can be assigned/changed.
 Reference values are stored only as a reference and the values must be retrieved.  These can have properties that can be assigned/changed.
```