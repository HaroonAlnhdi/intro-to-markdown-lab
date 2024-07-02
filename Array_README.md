# Writing a Array in JavaScript

If you have a list of items (a list of car names, for example), storing the cars in single variables could look like this:

## Creating an Array
Using an array literal is the easiest way to create a JavaScript Array.

![Array](https://res.cloudinary.com/practicaldev/image/fetch/s--zQ-nPHAj--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/4w96qsx3544peb7gpl2e.png)

***Syntax:***
```javascript
const array_name = [item1, item2, ...]; 
```

***Example:***
1. **Creating an Empty Array :**
```javascript
let myArray = [];
```
2. **Creating an Array with Initial Values :**
```javascript
let myArray = [1, 2, 3, 4, 5];

```
3. **Creating an Array Using the Array Constructor:**
```javascript
let myArray = new Array();
let myArrayWithValues = new Array(1, 2, 3, 4, 5); 

```


## Basic Operations on JavaScript Arrays

1. **Accessing Elements of an Array**
Any element in the array can be accessed using the index number. The index in the arrays starts with 0.
```javascript
// Creating an Array and Initializing with Values
let courses = ["HTML", "CSS", "Javascript", "React"];

// Accessing Array Elements
console.log(courses[0]);
console.log(courses[1]);
console.log(courses[2]);
console.log(courses[3]);
```
**Output**
```
HTML
CSS
Javascript
React
```

2. **Accessing the First Element of an Array**

The array indexing starts from 0, so we can access first element of array using the index number.
```js
let courses = ["HTML", "CSS", "JavaScript", "React"];

// Accessing First Array Elements
let firstItem = courses[0];

console.log("First Item: ", firstItem);
```
**Output**
```
First Item:  HTML
```
3. **Array Length**
Get the length of an array using the length property.

```js
// Creating an Array and Initializing with Values
let courses = ["HTML", "CSS", "Javascript", "React", "Node.js"];

let len = courses.length;

console.log("Array Length: " + len);

```
**output:**
```
Array Length: 5
```

## JavaScript Array Complete Reference

We have a complete list of Javascript Array, to check those please go through this JavaScript Array Reference article. It contains a detailed description and examples of all Array Properties and Methods.

## JavaScript Array Examples
JavaScript Array examples contain a list of questions that are majorly asked in interviews. Please check this article JavaScript Array Examples for more detail.

## JavaScript CheatSheet
We have a Cheat Sheet on Javascript where we have covered all the important topics of Javascript to check those please go through Javascript Cheat Sheet-A Basic guide to JavaScript.


## Methods pop/push, shift/unshift
A queue is one of the most common uses of an array. In computer science, this means an ordered collection of elements which supports two operations:

- `push` appends an element to the end.
+ `shift` get an element from the beginning, advancing the queue, so that the 2nd element becomes the 1st.

 1. Pop : Extracts the last element of the array and returns it:
 ```js
let fruits = ["Apple", "Orange", "Pear"];

alert( fruits.pop() ); // remove "Pear" and alert it

alert( fruits ); // Apple, Orange

 ```
 > Both `fruits.pop()` and `fruits.at(-1)` return the last element of the array, but `fruits.pop()` also modifies the array by removing it.


 2. push
Append the element to the end of the array:
```js
let fruits = ["Apple", "Orange"];

fruits.push("Pear");

alert( fruits ); // Apple, Orange, Pear
```
> The call fruits.push(...) is equal to fruits[fruits.length] = ....

## Refrences 

[JavaScript.info](https://javascript.info/array)