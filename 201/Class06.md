# Domain modeling, Intro to the DOM and Object Literal

## Reading
[JS Object Basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)
[Intro to the DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)

### Review links
[Understanding the problem domain is the hardest part of programming](http://simpleprogrammer.com/2013/07/15/understanding-the-problem-domain-is-the-hardest-part-of-programming)
[What's the difference between primitive values and object references in JS](https://betterprogramming.pub/intermediate-javascript-whats-the-difference-between-primitive-values-and-object-references-e863d70677b)

## Q&A
### JS

1. How would you describe an object to a non-technical friend you grew up with?
> An object is something that has properties. Everything has properties like a book. Properties are things like, colour, design, weight, title, material. Every BOOK object will have these same properties.
2. What are some advantages to creating object literals?
> they are a way to define and create objects using concise syntax (object initializers). This can improve an objects flexibility and reusability and ease Data Manipulation.
3. How do objects differ from arrays?
> data is stored in key-value pairs within objects unlike arrays where it's single values. 
4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
> We use bracket notation when we want to acces an object’s property, when the property name needs to be dynamically determines or when property name includes special characters or spaces. bracket notation is used, allowing us to access the properties by providing the property name as a string enclosed in square brackets. Dot notation to access the properties would result in an error.
5. Evaluate the code below. What does the term this refer to and what is the advantage to using this?
> const dog = {   
>   name: 'Spot',   
>   age: 2,   
>   color: 'white with black spots',  
>   humanAge: function (){  
>     console.log(`${this.name} is ${this.  age*7} in human years`);  
>   }  
> }

> this. refers to the dog object eg it will grab dog.name = "Spot"

### DOM
1. What is the DOM?
> DOM stands for Document Object Model and is a programming interface for web documents which represents the page.
2. Briefly describe the relationship between the DOM and JavaScript.
> The DOM is not part of the JavaScript language, but is instead a Web API used to build websites. You can access the DOM though JS and use JS to manipulate the  DOM

## Usefull links
[dom visualizer](https://bioub.github.io/dom-visualizer/)