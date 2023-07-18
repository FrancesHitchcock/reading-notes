# Module 1 Class 2 Reading Notes

## React Lifecycle

### `render` and `componentDidMount`

`render` takes place before `componentDidMount`

### The first thing to happen in the React lifecycle

The first phase of the lifecycle is `mounting`. `constructor` is the first thing that happens in the mounting phase.

### The order of lifecycle events

1. constructor
2. render
3. ComponentDidMount
4. React updates
5. componentWillUnmount

### componentDidMount

This method is for using a network request and initializing the DOM.

## React State Vs Props

### What you can pass in as props

You can pass just about any data type in as props, including strings, numbers, booleans, functions etc.

### The main difference between props and state

Props are immutable and cannot be modified. State, on the other hand is designed to change in response to events. State can be passed as a prop.

### When we re-render our application

The app re-renders when any state changes in any of the components

### Things that can be stored in state

Just about any data type can be stored in state.
