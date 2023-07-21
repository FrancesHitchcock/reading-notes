# Module 1 Class 4 Reading Notes

## React Forms

### Controlled components

In React the form fields' values are stored in state - not in the HTML/JSX form elements themselves. They are updated with setState(). So the React state becomes the 'single source of truth' for the elements' values.

### Storing the user's responses

The user's response is stored as soon as it is entered, rather than waiting for the form to be submitted.

### Targeting what the user is entering

The onChange event is used to target what the user is entering.

## The Ternary Operator

### Why we would use a ternary operator

The ternary operator is a concise way of writing a simple if else statement.

### The syntax

```
if(x===y){
  console.log(true);
} else {
  console.log(false);
}
```

would be written:

```
x===y ? console.log(true) : console.log(false)
```
