# JavaScritp
Java is NOT JavaScript

for my working page go [here](https://qualitymermaid.github.io/html-demo/)

## Notes
what makes our page dynamic:
html is sctucture
css details (sofa)
js what makes it all work

JS can store data and change based on user input. It is HUGE and can do a lot!

- create file in VSCode called app.js (.js for javascript)
- Inspect a webpage (right click) and open the Console where we can write JS directly to test what we want to do
   -  console.log() logs to the console
- best practice is to write in cammal case eg myNameIs for variables etc

### Variable in Programming

What is a variable? In programming, a variable is a value that can change, depending on conditions or on information passed to the program. Typically, a program consists of instruction s that tell the computer what to do and data that the program uses when it is running.
[js_variables](https://www.w3schools.com/js/js_variables.asp)
   - var. can be redeclaired for variable so try and not use it
   - let does not need a veriable when created unlike var
   - const the value will NOT change

> The var keyword was used in all JavaScript code from 1995 > to 2015.  
> The let and const keywords were added to JavaScript in 2015.  
> The var keyword should only be used in code written for older browsers.



### Errors

- VM555:1 Uncaught TypeError: Assignment to constant variable.
    at 'anonymous':1:9 (' replaces > icons in notes)
    - cannot change as its a constant variable cause we used const
- Uncaught SyntaxError: Identifier 'herName' has already been declared
   - tried to create a duplicate variable
- VM282:1 Uncaught ReferenceError: herN is not defined
    at 'anonymous':1:17
    - var NEEDS a value


### Notes from app.js file
> - console.log("this is a test");  
> - let myName = "Jessica";   
> - console.log(myName);   

> // data types   
> - let myPet = "Dog"; // this data is a string   
> - let myPetsAge = 7; // this data is a number   
> - let petDetails = "My pet is " + myPetsAge; // this will print as a string   
> - console.log(petDetails);   
> - console.log(typeof petDetails); // will tell us what type the data is   
> - let likesWalkies = true // this data type is a boolean true/false statement   
> - console.log(typeof likesWalkies);   
> // other types are arrays and objects

> // arethemetic operators   
> - let addition = 7 + 7 // + is for addition   
> - console.log(addition)   
> - let subtraction = 5 - 2 // - is for subtraction   
> - console.log(subtraction)   
> - let multiplication = 2 * 3 // * is for multiplication    
> - console.log(multiplication)   
> - let division = 15 / 3 // / this is for division   
> - console.log(division)   
> - let myNum = 5   
> - let thisNum = ++myNum //++ is to increment (will look different if ++ is put at the end)   
> - console.log(thisNum)   
> - let thatNum = --myNum // -- this will decrement by one
> - console.log(thatNum)


> //  Comparison operators
> - // == equal to
> - // === equal value and equal type "7" === 7
> - // != not equal
> - // !== not equal value and not equal type
> - // > greater than
> - // < less than
> - // >= greater than or equal to
> - // <= less than or equal to


> // Methods   
// consol.log()   
// prompt()   
// document.write() !!! DO NOT USE THIS AS IT WILL OVERWRITE HTML  
// alert() will show a message to the user  

> let userName = prompt("Hi user :) please tell me your prefered name!")   
> console.log(userName)   
> // if (userName == "Je"){
 // } else (alert("Please enter your name"))

> const welcomeMsg = alert("Welcome to my page " + userName)

> document.write()
