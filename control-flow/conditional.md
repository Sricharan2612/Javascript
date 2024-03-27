In conditional statements we have 
1-->if
if(condition){
    //operation
}

eg. 
if (year == 2015) {
  alert( "That's correct!" );
  alert( "You're so smart!" );
}

2--> if-else
syntax: if(condition){
    //Operation
}else{
    //Operation
}

eg. 
    let year = prompt('In which year was the ECMAScript-2015 specification published?', '');
    if (year == 2015) {
        alert( 'You guessed it right!' );
    } else {
        alert( 'How can you be so wrong?' ); // any value except 2015
    }

3--> if-else if-else
syntax: if(condition){
    //Operation
}else if(condition){
    //Operation
}
. else if
. else if
. else if
else{
    //Operation
}

eg. 
let year = prompt('In which year was the ECMAScript-2015 specification published?', '');
if (year < 2015) {
  alert( 'Too early...' );
} else if (year > 2015) {
  alert( 'Too late' );
} else {
  alert( 'Exactly!' );
}

3-->Switch
syntax: let x
        switch(x){
            case value: //operation
                        break;
            case value: //operation
                        break;
            case value: //operation
                        break;
            default: //Operation            
        }

eg. 
let num1 = Number(prompt("Enter 1st number"));
let num2 = Number(prompt("Enter 2nd number"));
let Operation = prompt("Enter a operation (+, -, *, /, %)");

switch(Operation){
    case '+': console.log(`${num1}${Operation}${num2} = ${num1+num2}`);
                break;
    case '-':  console.log(`${num1}${Operation}${num2} = ${num1-num2}`);
                break; 
    case '*':   console.log(`${num1}${Operation}${num2} = ${num1*num2}`);
                break;
    case '/': console.log(`${num1}${Operation}${num2} = ${num1/num2}`);
                break;  
    case '%': console.log(`${num1}${Operation}${num2} = ${num1%num2}`);
                break; 
    default: console.log("Opeation doesn't exist, Please enter a valid operation");    
}        