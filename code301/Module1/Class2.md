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
