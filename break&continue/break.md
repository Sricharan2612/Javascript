The break statement in JavaScript is used to terminate the current loop or switch statement and transfers program control to the statement following the terminated statement.

eg.1
for (var i = 0; i < 10; i++) {
  if (i === 5) {
    break;
  }
  console.log(i);
}

2.
const food = "sushi";

switch (food) {
  case "sushi":
    console.log("Sushi is originally from Japan.");
    break;
  case "pizza":
    console.log("Pizza is originally from Italy.");
    break;
  default:
    console.log("I have never heard of that dish.");
    break;
}

3.
let arr1 = [
{name:"Chinmaya",age:28,Job:false},

{name:"Charan",age:23,Job:false},
 
{name:"Anand",age:29,Job:true},

{name:"Naina",age:22,Job:false},
 
{name:"Sanjay",age:22,Job:true}
]
 
for(let i=0;i<arr.length;i++){

    if(arr[i].Job==true){
        break;
    } 
console.log(arr[i]);

}