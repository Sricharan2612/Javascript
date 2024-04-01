Looping statements are used to perform a certain task repeatedly until the condition becomes false.
In looping statements we have :
1.For loop
syntax : 
for(initialization; condition; increament/decreament){
    //Operations
}

eg.1 
for (var i = 0; i < 3; i++) {
    setTimeout(() => {console.log(i)},1)
 }

2.
for (let i =0;i <5;i++){
if(i==2){
console.log("Skipping iteration",i)
contine;
}
console.log("Iteration",i)
}

3.
let arr = [
{name:"Chinmaya",age:28,Job:false},

{name:"Charan",age:23,Job:false},
 
{name:"Anand",age:29,Job:true},

{name:"Naina",age:22,Job:false},
 
{name:"Sanjay",age:22,Job:true}
]
 
for(let i=0;i<arr.length;i++){
 
console.log(arr[i])

}

4.
let arr1 = [
{name:"Chinmaya",age:28,Job:false},

{name:"Charan",age:23,Job:false},
 
{name:"Anand",age:29,Job:true},

{name:"Naina",age:22,Job:false},
 
{name:"Sanjay",age:22,Job:true}
]
 
for(let i=0;i<arr.length;i++){
 
    if(arr[i].Job==true){
        continue;
    }
 
console.log(arr[i]);

}
