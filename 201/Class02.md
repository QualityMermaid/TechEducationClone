# Introduction to Web Development

## Links to keep reading
[HTML Text Fundamentals](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals)   
[HTML Advanced Text Formatting](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting)   
[How CSS is Structured](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/How_CSS_is_structured)   
[JavaScript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)   
[Making Decisions in Your Code - Conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)   


## Q&A from 02 Readings
### HTML
1. Why is it important to use semantic elements in our HTML?
> It makes the HTML more comprehensible by better defining the different sections and layout of web pages.
2. How many levels of headings are there in HTML?
> 6 h1-h6
3. What are some uses for the 'sup' and 'sub' elements?
> sup = Superscript.  
sub = Subscript   
you might need these for marking up items like dates and mathermatical equations so they have the correct meaning.
4. When using the 'abbr' element, what attribute must be added to provide the full expansion of the term?
> title="xxx"

### CSS
1. What are ways we can apply CSS to our HTML?
> - by linking a .css file
> - inline using style
2. Why should we avoid using inline styles?
> For sites with more than one page, an internal stylesheet becomes a less efficient way of working. To apply uniform CSS styling to multiple pages using internal stylesheets, you must have an internal stylesheet in every web page that will use the styling. The efficiency penalty carries over to site maintenance too. With CSS in internal stylesheets, there is the risk that even one simple styling change may require edits to multiple web pages.
3. Review the block of code below and answer the following questions:
    1.  What is representing the selector?
    > h2
    2. Which components are the CSS declarations?
    > color and padding
    3. Which components are considered properties?
    > black and 5px
  > h2 {   
     color: black;   
     padding: 5px;   
   }
### JS

1. What data type is a sequence of text enclosed in single quote marks?
> string
2. List 4 types of JavaScript operators.
> 1. Addition +
> 2. Subtraction -
> 3. Multiplication *
> 4. Division /
> 5. Strict equality ===
3. Describe a real world Problem you could solve with a Function.
> Packing a lunch box everyday! I could create a function called makeLunch and it would run and make it for me without me having to do more work!

4. An if statement checks a __ and if it evaluates to ___, then the code block will execute.
> condition and if it has been met the
5. What is the use of an else if?
> if we want to have multiple outcomes based of other information
6. List 3 different types of comparison operators.
> 1. === and !== test if one calue is identical to another or is NOT identical
> 2. < and > test if one value is lesser or greater than another
> 3. <= and >= tests if one value is less than or equal to OR is great than or equal to another
7. What is the difference between the logical operator && and ||?
> && = and this must be true   
|| = either/or this is true