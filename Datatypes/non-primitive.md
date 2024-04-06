Non primitive data types are also known as complex data types.
they are stored as the reference to variable.
they are mutuable.

it includes:
1-->Arrays
2-->Objects
3-->Functions


1.Arrays
Arrays consist of an ordered collection or list containing zero or more data types, and use numbered indices starting from 0 to access specific items.

eg.1
const cars = ["Saab", "Volvo", "BMW"];
console.log(cars);

eg.2
const cars = [];
cars[0]= "Saab";
cars[1]= "Volvo";
cars[2]= "BMW";

eg.3
const cars = ["Saab", "Volvo", "BMW"];
for(let i = 0; i<arr.length; i++>){
    console.log(cars)
}

Array methods:
1.push() : Used to push an element to the last index of an array.
2.pop() : Used to pop an element from the last index of an array.
3.unshift() : Used to push an element to the first index of an array.
4.shift() : Used to pop an element from the first index of an array.
5.find() : used to find an element in an array.



