The Temporal Dead Zone (TDZ) is a concept introduced in ES6 as part of the specification for variables declared with let and const. 
It refers to the period between entering the scope where a variable is declared and the actual declaration being reached in the code. During this period, attempting to access the variable results in a ReferenceError.

eg.1
console.log(x); // Throws a ReferenceError
let x = 5;

2.
function ex(){
console.log(a);
var a= 5;
 
{
console.log(b)
let b = 10 ;
}
console.log(c)
const c = 15;
}
ex()