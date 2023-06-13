# 

## Reading links
### HTML
[Ordered Lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)
[Unordered Lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)
### CSS
[The Box Model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)

### JS
[Arrays](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays)
[Operators and Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
[Conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)
[Loops](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code)

## Q&A
### HTML
1. When should you use an unordered list in your HTML document?
> when things dont need to be done in a certain order
2. How do you change the bullet style of unordered list items?
> by selecting a different style using css ul list-style-type
3. When should you use an ordered list vs an unorder list in your HTML document?
> if you want things to be done in order use and ordered list, eg baking a cake recipe (ordered) list of ingredants (unordered)
4. Describe two ways you can change the numbers on list items provided by an ordered list?
> - give them the attribute reversed to reverse the order of numbers   
> - give them an integar to start the 'count' by assigning attribute start.

### CSS
1. Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?
> margin is someone who during the box model story gathers everyone together guids them to where they should be
> padding is someone who during the box model story who likes to fill in gaps and creates space for the main character Content to stand out
2. List and describe the four parts of an HTML elements box as referred to by the box model.
> 1. Content box: area where your content is displayed. the 'centre'
> 2. Padding box: sitting around the outside of your content as white space
> 3. Border box: wraps the content and padding (if any)
> 4. Margin box: the outermost layer wrapping everything listed above

### JS
1. What data types can you store inside of an Array?
> strings, numbers, objects and other arrays!
2. Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?
>const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
> Yes you can have different data types in an array.
> You can access the value by typing 'console.log(people[2]);

3. List five shorthand operators for assignment in javascript and describe what they do.
> 1.  = assign the value
> 2. += adds the values together
> 3. -= subtracts from eachother
> 4. /= divids them
> 5. <<= left shifs the assignment
4. Read the code below and evaluate the last expression and explain what the result would be and why.                    

 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;

 > This area always confuses me and will need to spend more time on!
5. Describe a real world example of when a conditional statement should be used in a JavaScript program.
>Conditional statements control behavior in JavaScript and determine whether or not pieces of code can run. There are multiple different types of conditionals in JavaScript including: “If” statements: where if a condition is true it is used to specify execution for a block of code.   
> A suggestion is during  a confirmation model. If something should only run when someone wants to proceed then using a conditional statment is a good start.
6. Give an example of when a Loop is useful in JavaScript.
> Loops are all about doing the same thing over and over again. Often, the code will be slightly different each time round the loop, or the same code will run but with different variables. Like if your waiting for a state to change before you can proceed with the next stage of code.