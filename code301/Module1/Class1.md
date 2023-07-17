# Module 1 Class 1 Reading Notes

## Component Based Architecture

Source material: [tutorialspoint]("https://www.tutorialspoint.com/reactjs/reactjs_components.htm#:~:text=A%20React%20component%20represents%20a,belongs%20to%20its%20user%20interface.")

### A component

A component is a reusable piece of code that represents a smaller building block of the React application.

### Characteristics of a component

A React component renders its user interface and updates it when its internal state is changed. It also manages the events belonging to its user interface.

### Advantages of using component-based architecture

Source material: [geekforgeeks]("https://www.geeksforgeeks.org/what-are-some-advantages-of-component-driven-development/")

- Reusability
- Repetition
- Scalability
- Simpler maintenance
- Faster development

## Props and how to use it in React

### What `props` is short for

'props' is short for 'properties'.

### How `props` are used in React

Props are passed into React components as arguments. The syntax for props is similar to HTML attributes e.g. name="value". The component receives the prop as a `props` object.

### The flow of `props`

Props are passed _down_ the component tree from parent to child to grand-child etc.
