Non primitive data types are also known as complex data types.
they are stored as the reference to variable.
they are mutuable.

it includes:
1-->Arrays
2-->Objects
3-->Functions


1.Arrays
It consist of an ordered collection or list containing zero or more data types, and use numbered indices starting from 0 to access specific items.

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
eg. const arr = [10, 6, 23, 46, 54];
    arr.push(15);
    console.log(arr);

2.pop() : Used to pop an element from the last index of an array.
eg. const arr = [10, 6, 23, 46, 54];
    arr.pop();
    console.log(arr);

3.unshift() : Used to push an element to the first index of an array.
eg. const arr = [10, 6, 23, 46, 54];
    arr.unshift(15);
    console.log(arr);

4.shift() : Used to pop an element from the first index of an array.
eg. const arr = [10, 6, 23, 46, 54];
    arr.shift();
    console.log(arr);

5.find() : used to find an element in an array.
eg. const array1 = [5, 12, 8, 130, 44];
    const found = array1.find((element) => element > 10);
    console.log(found);

6.slice() : used to obtain a part of an array.
eg. const arr = [10, 6, 23, 46, 54];
    console.log(arr.slice(1,4););

7.splice(): used to remove certain elements from an array.
eg. const arr = [10, 6, 23, 46, 54];
    arr.splice(1,2);
    console.log(arr);


Some More Practice Questions --->
//Find max element in an array
function Max(arr){
    let max = -1;
    for(let i = 0; i<arr.length; i++){
        if(arr[i] > max){
            max = arr[i];
        }
    }
    return max;
}
let arr = [5, 90, 16, 3, 25, 64];
const res = Max(arr);
console.log(res);


//Find sum of all elements in an array

function sum(arr){
    let sum = 0;
    for(let i = 0; i<arr.length; i++){
        sum+=arr[i];
    }
    return sum;
}
let arr = [10, 20, 30, 40, 50];
let res = sum(arr);
console.log(res);


//Remove elements from array which are not divisible by 2
function divNum(arr){
    for(let i = 0; i<arr.length; i++){
        if(arr[i] % 2 !== 0){
            arr.splice(i,1);
        }
    }
    return arr;
}
let arr = [10, 3, 71, 45, 30];
let res = divNum(arr);
console.log(res);

//Function to sort an array
function sortElements(arr){
    let temp;
    for(let i = 0; i<arr.length; i++){
        for(let j = i+1; j<arr.length; j++){
            if(arr[i] > arr[j]){
                temp = arr[i];
                arr[i] = arr[j];
                arr[j] = temp;
            }
        }  
    }
    return arr;
}

let arr = [40, 5, 13, 27, 9];
let arr1 = ['e', 'f', 'c', 'a', 'z'];
let res = sortElements(arr);
console.log(res);

//Function to sort elements using single for loop
function sortElements(arr){
    let temp;
    let valueSwitched = false;

    for(let i = 0; i<arr.length; i++){
        if(i+1 === arr.length){
             if(!valuesSwitched){
            break;  
        } 
            valuesSwitched = false;
            i = 0;
    }    
               
        if(arr[i] > arr[i+1]){
                temp = arr[i];
                arr[i] = arr[i+1];
                arr[i+1] = temp;
                valuesSwitched = true;
        }
    }
    return arr;
}

let arr = [5, 3, 6, 11, 2]
let arr1 = ['e', 'f', 'c', 'a', 'z'];
let res = sortElements(arr1);
console.log(res);



