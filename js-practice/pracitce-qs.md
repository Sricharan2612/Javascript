what is javascript and why it is used?
JavaScript is a scripting or programming language that allows you to implement complex features on web pages.
It is an interpreted programming language, which means that it does not need to be compiled before it can be run. This makes it very fast and easy to use

why?
Adding interactivity to web pages, such as creating menus, forms, and games.
Validating user input on web pages.
Creating dynamic content on web pages, such as updating content without reloading the page.
Creating animations and graphics on web pages.
Communicating with servers to retrieve and send data.
Creating mobile apps and desktop software.

v8 engine?
V8 is a key component of Chrome's performance. It is responsible for parsing, compiling, and executing JavaScript code. V8 uses a number of techniques to improve performance, including: jit compilers, hidden class optimization, garbage collection.

how our program works in any browser?
When JavaScript executes within a web browser it is operating within the browser's runtime environment. The browser runtime environment provides access to the DOM which enables interaction with web page elements, handling events, and manipulating the page structure

written using both c and c++?
JavaScript engines, which are the programs that interpret and execute JavaScript code, are often written in C or C++. This is because C and C++ are very efficient languages that can provide the performance that JavaScript engines need.

async and sync?
Asynchronous is a non-blocking architecture, so the execution of one task isn't dependent on another. Tasks can run simultaneously. Synchronous is a blocking architecture, so the execution of each operation depends on completing the one before it.

javascript is async or sync?
JavaScript is a single-threaded, synchronous programming language. This means that JavaScript code is executed one line at a time
JavaScript also has asynchronous capabilities. This means that JavaScript can execute code without blocking the main thread. 
This is done through the use of callbacks and promises.

JIT COMPILER VS AOH COMPILER
AOT translate source code into machine code before the application is executed. This allows for optimizations and analysis to be performed ahead of time, resulting in faster startup times and better performance. However, AOT compilation can also increase build times and make it more difficult to debug code.

JIT compile code at runtime, as the program is executing. This allows for more flexibility and easier debugging, but it can also result in slower startup times and reduced performance.

trim(), slice(), charat, toString()

concat() indexof() touppercase()

tolower()

lastIndexOf()

let a= 3;
let b = new Number(3)
let c= 3 
 
console.log(a==b)
console.log(a===b)
console.log(a===c)

question 2 :
let number =0
console.log(number++)
console.log(++number)
console.log(number)

var num = 8;
var num = 10;
console.log(num)

console.log( typeof typeof 1)

const numbers = [1,2,3]
numbers[10] = 11
console.log(numbers)

chinamaya_age = 28
charanage = 23
anandage = 28 

if(chinamaya_age > anandage){
    if(chinamaya_age > charanage){
    console.log("chinmaya is elder")
    } else {
    console.log("charan is elder")
    }
} else {
console.log("anand and chinamaya are in same age ")
}

scope of var, let, and const?
var is function-scoped or global-scoped. This means that they are accessible within the entire function in which they are defined, or globally if they are defined outside of a function.

let and const are block scoped, This means that they are only accessible within the block (a pair of curly braces) in which they are defined.
also const variables cannot be changed once they have been assigned a value.

for (var i = 0; i < 3; i++) {
    setTimeout(() => {console.log(i)},1)
 }

 The output of this program might be unexpected if you're expecting 0, 1, 2 to be logged consecutively. However, due to the asynchronous nature of setTimeout, it will actually log 3 three times. This is because setTimeout schedules a callback function to be executed after a specified delay (in this case, 1 millisecond), but the loop continues to run immediately without waiting for the setTimeout callbacks to be executed.

output will be:3, 3, 3

Each console.log(i) statement inside the setTimeout callback is referencing the same i variable, which by the time the callback is executed, has already been incremented to 3 after the loop finishes.

When you use let instead of var in the for loop for the above example, it creates a new binding for i in each iteration of the loop. This means that each iteration of the loop will have its own separate i variable, preserving the value of i at each iteration when the setTimeout callback is executed.

 what is hoisting?
 Hoisting is a JavaScript mechanism where variable and function declarations are moved to the top of their scope before code execution. This means that functions and variables can be used before they are declared.

 [9:58 AM] Admin
y= 5;
console.log(y);
var y ;
