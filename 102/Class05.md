# CSS

## Notes

- create file called styles.css in main repo
- make sure to LINK the .css file and the html file
   - do this by adding "link rel="stylesheet" href="style.css" (with opening and closing tags)
   - can be created in the head by adding style element in the html file
   - added as as attribute in the element in the html file
      - useful if you wanted to change ONE different header for instance as it will take priortiy over the .css file
- .css is a cascading page and will read top to bottom
- there is a point system for which style will take priorty!!!
- can inspect webpage to show the Elements (pn webpage right click and at the bottome select Inspect)
   - element > padding > border > margin


## Syntax
- h1 (type selecter) will change style to all h1 (same for other h2, h3)
- color is a property which we can then add value eg. blue (can use font-size and loads of other different things)
- sizing can be done in different measurements! including % of a page
- '*' is a universal selecter and will select EVERYTHING (mostly)
- .XXX (class selecter) whatever has that class name will have this style attached to it
- use > to target a child eg nav > ul will target all ul's in nav
- most populare properties are (can be done in the .css and add it to body{} for it to target everything in the body)
  - font-family:
  - 
- create a reset.css useful for trouble shooting and to work off a blank canvas removing the inbuilt page styles. can populate the file from [HERE](https://meyerweb.com/eric/tools/css/reset/)
   - make sure to add it BEFORE anyother style


## Q&A
1. What is the purpose of CSS?
> To create a read sheet of styles that the browser will use to format the html documents. All informtion should be in the style sheet but some browsers have their own built in so you can create a reset.css file to overwrite this.
2. What are the three ways to insert CSS into your project?
> 1. External CSS
> 2. Internal CSS
> 3. Inline CSS
3. Write an example of a CSS rule that would give all 'p' elements red text.
> in the css file create  
p {
    color: red;
}