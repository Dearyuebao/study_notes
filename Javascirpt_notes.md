Javascirpt

"she said \\"goodbye!\\""

"to see a backslash:\\\\"  //only show one backslash

"my favourite number is:1234".length //27 don't count space

"The Beatles"[0] //T



Variable

var name="Rusty";

var secretnumber=73;

var isadorable=trueu8

%(mod)

should be camelCased



null and undefined

var name;

the name is undefined for nothing stored in this variable



Useful Built in method

alert prompt console.log

clear()

alert("Hello there!!!");

alert(198+12);//print things to users

console.log("hello from the console!")//print things to ourselves

prompt("what is your name?")//print to users as a question

var userName=prompt("what is your name?");

store the users' answer to the userName variable



writing javascript in a seperate file

script.html:

<head>

<script src="script.js"></script>

</head>

script.js:

var userName=prompt("what is your name?");

alert("Nice to meet you, "+userName);

console.log("Also great to meet you, "+username)



JS stalker exercise:

stalker.html:

<h1> JS Stalker Solution</h1>

script.js:

var firstName=prompt("first name is?");

var lastName=prompt("last name is?");

var age=prompt("age?");

console.log("your full name is "+firstName+" "+lastName);

console.log("you are "+ age +" years old");



Age calculator Exercise: