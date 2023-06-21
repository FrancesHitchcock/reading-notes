# Module 2 Class 8 Reading Notes

## CSS Flexbox

### Flexbox is designed for one-dimensional content

It only deals with layout in a single direction at one time - row or column. It can take elements of different sizes and return the best layout for those elements.

### The difference between the main axis and cross axis

The main axis is along the row, if the flex-direction is set to `row` and down the column if the flex-direction is set to `column`.

The cross axis runs at 90deg to the main axis - i.e. perpendicular to the row if flex-direction is sit to `row` and perpendicular to the column if flex-direction is set to `column`.

### How certain properties of flexbox negatively impact accessibility

Care should be taken when using properties that display the order differently from the HTML structure (such as flex-directions `row-reverse` and `column-reverse` and the `order` property) as this can confuse the meaning when accessing the document using a screen reader, and should not be used when the order of the elements is significant. The screen reader will read the logical order, not the visual order.

### Some advantages of using flexbox over float

Flexbox is as its name suggests, flexible. Float is a limiting way to position content. With flexbox you can vertically centre an element within its parent container; you can divide the available space in a parent element between its children, regardless of their width (in a row) or height (in a column).

### How this topic connects with my long-term goals

Flexbox is a fantastic tool for creating attractive and meaningful web layouts. The flex-wrap, flex-grow and flex-shrink properties can be used to make websites responsive. CSS is quite a recent addition to the CSS toolbox, so it could be quite a sought-after skill.

## CSS Layout

Source-material: [web-dev](https://web.dev/learn/css/layout/)
