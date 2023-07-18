# State and Props

## Reading
[React lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)   
[React State Vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)   
[React DOcs State and Lifecycle](https://reactjs.org/docs/state-and-lifecycle.html)
[React Docs handling events](https://reactjs.org/docs/handling-events.html)
[React Tutorial Dev Tools](https://reactjs.org/tutorial/tutorial.html)
[React Bootstap Doc](https://react-bootstrap.github.io/)
[Bootstrap Cheatsheet](https://getbootstrap.com/docs/5.0/examples/cheatsheet/)
[Bootstrap Shuffle](https://bootstrapshuffle.com/classes)
[Netlify](https://www.netlify.com/)

## Q&A
1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
> render() happens first
2. What is the very first thing to happen in the lifecycle of React?
> constructor() method. This is called wen the component is first created
3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
- Constructor
- Render
- React Updates
- componentDidMount
- componentWillUnmount
4. What does componentDidMount do?
> after the component has been rendered and inserted into the DOM. It is a good place to perform any actions that need to be done after the component is visible, such as making API requests or subscribing to events.
5. What types of things can you pass in the props?
> You can pass any JavaScript value as a prop, including strings, numbers, booleans, objects, arrays, and functions
6. What is the big difference between props and state?
> They are both used to pass data to components, but they are used in different ways. for instance Props can be Passed to a Child Component but a State cannot be passed.
7. When do we re-render our application?
- State Changes
- Props change
- parent component re-renders
- user interaction
8. What are some examples of things that we could store in state?
- User input
- Data from an API
- Configuration Data
- Application State