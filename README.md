# cheatsheet

var myName = "Adam"

myName = 8

let ourName = "freeCodeCamp"

const pi = 3.14


var a; //this would be DECLARING 
var b = 2;// This is ASSIGNING i.e 2 is now b 

var a = 9; 
var c = "I am a string"
var a = a + 1; //THIS WOULD BE INITIALIZING 

myName = myName + 1; 
myName = myName - 1; // these increment and decrement the numbers. 


//BASIC MATH AUGMENTATION
a+=12; //this is the same as saying a= a+3;
//compound Assignment with AUGMENTED addition
a-= 6;  
a*= 5; 
a/= 3;  

var firstName= "Alan"; 
var lastName = "Turing"; 
//Strings

//literal quotes? 
var myStr= "I am a \double quoted\" string inside\" double quotes" //escape characters? = it will no longer be considered the end of the string. 23.12 of the video
console.log(myStr)

//a literal string can either be surrounding by single '' quotes, or double quotes"".
//the main reason you would use single instead of double is "" needs escape characters or \". so for example a url . 
// myStr = <a href= http://www.example.com\"> you could get rid of the \and "

/*
CONSTRUCTING STRINGS WITH VARIABLES
use the = to define a variable
then use the += to add to a variable or append. 

ex: //

APPENDING VARIABLES TO STRINGS
  

var ourStr = "I comefirst. "; 
ourStr += " I come second." 

var myStr= " This is the first sentence."
myStr+= "this is the second sentence."
console.log(myStr); 
*/
/*Constructing Strings with variables
Same as Java...
var ourName = "freeCodeCamp"; 
var ourStr= "Hello, our name is " + ourName + ". how are you?"; 

var myName = "Adam"; 
var myStr = "My name is " + myName + " and I am well!";

console.log(myStr)
*/
/*APPENDING VARIABLES TO STRINGS- In JavaScript, appending a variable to a string is commonly done to create dynamic strings or to display variable values within a larger string.

var anAdjective = " and awesome!"; 
var ourStr= "freeCodeCamp is "; 
ourStr += anAdjective; 

var someAdjective = "worthwhile"; 
var myStr= "Learning to code is "; 
myStr += someAdjective;

console.log(myStr+anAdjective)

*/
/*find length of a string//
var firstNameLength = 0; 
var firstName = "Ada"; 

firstNameLength = firstName.length;

//setup 

var lastNameLength = 0; //notice you have to first ASSIGN it 0 
var lastName = "olson"; 

lastNameLength = lastName.length

console.log(lastNameLength)
*/

/*BRACKET NOTATION TO FIND FIRST CHARACTER IN A STRING
IT WOULD BE THE SAME AS REFERENCING THE FIRST ELEMENT OF AN ARRAY IN JAVA*/

/*HONESTLY WHY AM I DOING THIS BECAUSE I CAN JUST LOOK AT THIS VIDEO IF I EVER NEED TO REFERENCE ANYTHING...
https://www.youtube.com/watch?v=PkZNo7MFNFg*/
