# Passing Functions as Props

## Reading
[React Docs Lists and Keys](https://reactjs.org/docs/lists-and-keys.html)
[The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)
[How to pass functions between components](https://www.youtube.com/watch?v=c05OL7XbwXU)
[React Tutorial through Declaring a Winner](https://reactjs.org/tutorial/tutorial.html)
[React Docs Lifting state up](https://reactjs.org/docs/lifting-state-up.html)

## Q&A

1. What does .map() return?
> a new array with the same lenth as the origianl array
2. If I want to loop through an array and display each value in JSX, how do I do that in React?
> you use the .map() function. create an array then use the .map() function to iterate over each element in the array. 
3. Each list item needs a unique ____.
> key attribute
4. What is the purpose of a key?
> The purpose of a key in React is to help React identify each list item uniquely when rendering lists dynamically. 
5. What is the spread operator?
> The spread operator (...) in JavaScript allows you to expand iterable objects, such as arrays or objects, into individual elements.
6. List 4 things that the spread operator can do.
> Copying Arrays and Objects, Concaterating Arrays, Passing Arguments, Merging Objects
7. Give an example of using the spread operator to combine two arrays.
> const array1 = [1, 2, 3]
> const array2 = [4, 5, 6]
> const combinedArray = [...array1, ...array2]
8. Give an example of using the spread operator to add a new item to an array.
> const array1 = [1, 2, 3]
> const newItem = 4
> const newArray = [...array1,newItem]
9. Give an example of using the spread operator to combine two objects into one.
> const object1 = { number: 1, colour: red}
> const object2 = { number: 2, colour: blue}
> const combineOpject = {...object1,object2}
10. In the video, what is the first step that the developer does to pass functions between components?
> the first step typically involves defining the function in the parent component that you want to pass to a child component. This function is usually defined as a method within the parent component's class or as a regular function within the parent component.
11. In your own words, what does the increment function do?
> its a custom function that increass a counter or can update a value
12. How can you pass a method from a parent component into a child component?
> To pass a method from a parent component to a child component in React, you can pass the method as a prop to the child component. This allows the child component to access and invoke the method
13. How does the child component invoke a method that was passed to it from a parent component?
> By invoking this.props.increment in the child component, it calls the increment method defined in the parent component, allowing the child component to trigger the parent's functionality.