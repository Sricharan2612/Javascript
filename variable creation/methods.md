In javascript, we can create variable using let, var, and const.
eg. let a = 10;
eg. var isUser = true; 
eg. const str = "Hello";

variable created using var are both function and global scoped.This means that they are accessible within the entire function in which they are defined, or globally if they are defined outside of a function.

let and const are block scoped, This means that they are only accessible within the block (a pair of curly braces) in which they are defined.
also const variables cannot be changed once they have been assigned a value.

eg. 1
var a = 10;
 
function foo(){
console.log("a in foo",a);
var b = 20;
}
 
foo()
console.log("b outside foo",b);

//In the above example it will throw error while console logging the value of b because it is declared within the function and will not be accessible outside of the function.
