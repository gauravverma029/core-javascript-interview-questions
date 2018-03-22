# Core Javascript Interview Questions
 
  We have tried to cover maximum javascript interview questions possible - For Freshers and Experienced UI Developers

## We will cover all question Topic wise in javscript.it will be good for fresher also.

## Question 1. How will you create array in javscript and tell some operations with array. 

> Now we are creating array

```javascript
var x = [1,2,3,5,6]; // declaring x
console.log(x); //output: [1, 2, 3, 5, 6]
```
> How to use Loop for array

```javascript
x.forEach(function(item,index){
	console.log(index,item) 
})  
 
  output :- 
   0 1 
   1 2
   2 3
   3 5
   4 6

```
> Remove first element from array

```javascript
 var first = x.shift() // [2,3,5,6]

```
> Add element front of array

```javascript
 var last = x.shift(1) // [1,2,3,5,6]
 
```
> 
