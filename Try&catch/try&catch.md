Try -->
The try statement allows you to define a block of code to be tested for errors while it is being executed.
Catch -->
The catch statement allows you to define a block of code to be executed, if an error occurs in the try block.
Finally -->
The finally statement lets you execute code, after try and catch, regardless of the result 

Syntax:
try {
  Block of code to try
}
catch(err) {
  Block of code to handle errors
}
finally {
  Block of code to be executed regardless of the try / catch result
}

eg.1 
function division(a,b) {
    if(b === 0){
    throw new Error("divison by zero is not possible")
    }
    return a/b; 
}

try{
    const result = division(10,10)
    console.log(result)
} catch (error){
console.error(error)
}finally {
    console.log("finally")
}