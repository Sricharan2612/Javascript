callback is a function called inside the another function.
Callback is a function that passed as parameter to an another function.
It is an unique way for handling async operations.

eg.
function sum(number1,number2, callback){


}
 const sum = (number1,number2,callback) =>{
let sum = number1+ number2
callback(sum)
}

const result = (res) => console.log(res)

sum(5,5,result)


Call back use cases /or how call back works

1 will pass function as callback 
2 Callback will exec after specific task is done
3 it will handle async operations


Simple synchronous operations do not required callback event. 
where as in  async operations in some scenarios or edge cases we may use callback to perfrom some task after obtaining certain output.