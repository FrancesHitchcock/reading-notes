# Module 1 Class 3 Reading Notes

## HTML Lists

### When to use an unordered list

The `<ul>` element should be used where each item's position in the list is of no significance.

### Changing an unordered list's bullet style

The `list-style-type` property is used. this can take the following values:

- `circle`
- `disc`
- `square`

### When to use an ordered vs and unordered list

The `<ol>` should be used when the order of the list items is significant, for example when the list is a set of steps such as instructions or a recipe.

### Changing the list item numbers in an ordered list

Two ways you can change the numbers are:

- by adding a type attribute to the `<ol>` element tag e.g. `type="i"` will render the numbers as roman numerals.
- by using the start attribute in the `<ol>` element tag, which will start the numbering at the specified number e.g. `start="4"` will start the numbering at 4.

## CSS box model

### Margin and padding

The padding property introduces white space between the element's content and border. The margin property adds the white space outside the border, and has the effect of moving the element away from surrounding elements (this is dependent on whether the element and it's neighbours are block or inline elements).

### The box model structure

In the box model of an element has four parts:

- content box - contains the content of the element
- padding box - contains the content along with its padding
- border box - contains the content along with its padding and border
- margin box - contains the content along with its padding, border and margin

## JavaScript Arrays, Operators, Expressions, Conditionals, Loops

### Arrays and data types

Arrays can contain virtually any data type, including strings, numbers, booleans, objects, functions and even other arrays. A single array can contain multiple data types.

### Array of arrays

The `people` array as shown in the question is a valid array. The outer array contains other arrays as its elements. The inner arrays contain mixed data types.

To access elements within the array you would need to find its index value. For example, to access the second array element within the `people` array you would use `people[1]`. To access the third element within the second array element you would write `people[1][2]`.

### Assignment operators (shorthand)

Five examples of shorthand assignment operators are:

- Assignment: `=` The value to the right of the operator is assigned to the variable on the left.
- Addition assignment: `+=` e.g. `text += myArray[i]`. This is shorthand for `text = text + myArray[i]`. This has the effect of adding the value to the right of the addition operator to the value of `text` and re-assigning it as a new value to `text`.
- Subtraction assignment: `-=` e.g. `num -= 2` is shorthand for `num = num - 2`. The variable `num` is reassigned the value of the previous value of `num` subtract 2.
- Exponentiation assignment: `**=` e.g. `num **= 2` is shorthand for `num = num ** 2`. The new value of num is the previous value to the power of 2.
- Remainder assignment: `%=` e.g. `num %= 3` is short for `num = num % 3`. The new value of num is the value of the remainder when the previous value is divided by 3.

### Evaluate the last expression

![JS code block](/Module1/Screenshot%202023-06-17%20181424.png "JS code block")

In the code above, the last expression will evaluate to `10dog`. This is because the boolean `false` value evaluates to `0` when added to `10`, totalling 10. The `+` operator used on a number and a string first stringifies the number, then acts to concatenate the two strings.

### Conditional statement - a real world example

A conditional statement could be used to greet a user with the time of day, depending on whether it is morning ("Good morning"), afternoon ("Good afternoon") or evening ("Good evening").

### Use of loops - an example

Loops are used to repeat an operation a specified number of times. For example, you could render a multiplication table by using a for loop with 12 iterations, and multiplying each iteration number by the desired table number e.g. `console.log(i * 4)` would log the products in the four times table to the console.

## Things I want to know more about

I want to become proficient at array methods.
