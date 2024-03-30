Hoisting is a mechanism where variable and function declarations are moved to the top of their scope before code execution. This means that functions and variables can be used before they are declared.

eg.1
    foo()
    function foo(){
    console.log("Hello World");
    }

2.
console.log(x);
var x= 5;

//In this case it will throw an error because the variable declaration will only move to the top of their scope but not the value.

3.
y= 5;
console.log(y);
var y ;

//In this case since the variable is moved to the top and we are also assigning the value of the variable before the console log statement that's why it will not throw an error and the value of y 5 will be printed.

4.
weekend()
 
var weekend = function(){
console.log("Weekends classes are boring");
}

//In this case also only the variable will be moved to the top but not the function because it is assigned to a variable. the functions which are declared individually to by using function keyword but not assigned to a variable will only be moved to top.  