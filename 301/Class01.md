# Intro to React and Components

## Reading
[Component-based architecture](https://www.tutorialspoint.com/software_architecture_design/component_based_architecture.htm)
[]()

## Questions

1. What is a “component”?
> a building block that represents a reusable piece of the user interface. components can be combined to create more complex components.
2. What are the characteristics of a component?
> Reusability − Components are usually designed to be reused in different situations in different applications. However, some components may be designed for a specific task.

Replaceable − Components may be freely substituted with other similar components.

Not context specific − Components are designed to operate in different environments and contexts.

Extensible − A component can be extended from existing components to provide new behavior.

Encapsulated − A A component depicts the interfaces, which allow the caller to use its functionality, and do not expose details of the internal processes or any internal variables or state.

Independent − Components are designed to have minimal dependencies on other components.


3. What are the advantages of using component-based architecture?
> Component-oriented software design has many advantages over the traditional object-oriented approaches such as −

Reduced time in market and the development cost by reusing existing components.

Increased reliability with the reuse of the existing components.
4. What is “props” short for?
> properties
5. How are props used in React?
> They are used to provide data or configuration to a component, allowing the component to render based on the provided informaion   
6. What is the flow of props?
> data is passed from parent to their child components in a one-way direction ensuring that the parent component remains the source of truth for the data