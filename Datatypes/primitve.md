Primitve data types are the most basic data types.
they are directly stored in the memory.
they are immutable.
it includes :
1-->Number: used to store decimal as well as floating point numbers.
eg. let num = 10
    let num1 = 12.3
    let n = 123;
    n = 12.345;

2-->String: Used to store a sequence of characters.anything which is enclosed within single or double quotes is considered as string.
eg. let str = "Hello"
    let str = "Hello";
    let str2 = 'Single quotes are ok too';
    let phrase = `can embed another ${str}`;

3-->Boolean: it basically contains two types of values, which is true or false.
eg. let isAdmin = false
eg. let isUser = true
    let nameFieldChecked = true; // yes, name field is checked
    let ageFieldChecked = false;

4-->null: it signifies absence of a value or placeholder for an object that doesn't exist.
eg. let a = null

5-->Undefined: when a variable is declared but hasn't been assigned a value then it is called undefined.
eg. let firstName = Undefined
eg. let name;
    let age;
    alert(age); // shows "undefined"

6-->BigInt: it is used it decimal numbers with larger size.
eg. let num = BigInt(1334899983342)
    const bigInt = 1234567890123456789012345678901234567890n;

7-->Symbol: returns a unique symbol or identifier.
    eg. let s = Symbol("hello");
    const sym1 = Symbol();
    const sym2 = Symbol("foo");