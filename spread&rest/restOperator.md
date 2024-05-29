Rest Operator --->
The rest operator in JavaScript is denoted by three consecutive dots (...), and is used to gather the remaining elements of an iterable (like an array) into a single array variable.

eg.1
const numbers = [1, 2, 3, 4, 5];
const [first, ...rest] = numbers;

console.log(first); // 1
console.log(rest); // [2, 3, 4, 5]

eg.2
const numbers = [1, 2, 3, 4, 5, 6];

const [one, two, ...rest] = numbers;