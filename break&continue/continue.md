The continue statement terminates execution of the statements in the current iteration of the current loop, and continues execution of the loop with the next iteration.

eg.1

for (let i = 0; i < 10; i++) {
  if (i === 3) {
    continue;
  }
  console.log(i);
}


2.
let text = '';

for (let i = 0; i < 10; i++) {
  if (i === 3) {
    continue;
  }
  text = text + i;
}

console.log(text);

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
        continue;
    } 
console.log(arr[i]);

}