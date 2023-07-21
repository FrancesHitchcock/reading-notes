# Module 1 Class 5 Reading Notes

## Thinking in React

### The 'single responsibility principle'

Each React component should be responsible for a single task

### A 'static' version of an application

A 'static' version renders the UI only, with no functionality

### What you should add to a static application

Once you have a static version you should add the minimal but complete representation of UI state

### Three questions to determine if something is state

- If it remains unchanged over time it is not state
- If it passed from a parent via props it is not state
- If you can compute it based on existing state or props in your component it is not state

### How to identify where state needs to live

State should live in the closest common ancestor of all the components that need to use the state.

## Higher Order Functions
