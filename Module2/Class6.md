# Module 2 Class 1 Reading Notes

## JavaScript Object Basics

### An object as described to a non-technical person

An object is a set of data that are all related to each other. This data could be a property, for example if the object represents an animal, it could include information telling us about the species, the name or the diet. The data could be a functionality, for example tell us the sound the animal makes.

### Advantages of object literals

An object is a single item, even though it contains multiple pieces of data. So it is more efficient to handle than if we were treating the individual items separately.

### Using bracket notation to access a property of an object

You must use bracket notation instead of dot notation if the property name is held in a variable.

### `this`

![JS code block](/Module2/Screenshot%202023-06-19%20083326.png "JS code block")

In the above code the `this` refers to the object within which the function sits i.e. 'dog'. So the logged string would read: 'Spot is 2 in human years'. The `this` keyword helps when you are creating more than one object, especially when creating objects using constructors.

## Introduction to the DOM

### What is the DOM

The DOM is a representation of the HTML page in the form of nodes and objects.

### The relationship between the DOM and JS

The DOM can be manipulated using JavaScript methods such as `document.getElementById` and many more.

## How To Solve Programming Problems

Source material: [Simple programmer](https://simpleprogrammer.com/solving-problems-breaking-it-down/)

Very helpful advice - I always want to dive straight in. I will practise reading and understanding the question, and solving the problem manually using hard-coded values for now. I will refer to this article next time I have a JS problem to solve.

## Primitive Values and Object References in JS

Source material: [Better programming](https://betterprogramming.pub/intermediate-javascript-whats-the-difference-between-primitive-values-and-object-references-e863d70677b)
