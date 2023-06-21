# Module 2 Class 8 Reading Notes

## CSS Flexbox

### Flexbox is designed for one-dimensional content

It only deals with layout in a single direction at one time - row or column. It can take elements of different sizes and return the best layout for those elements.

### The difference between the main axis and cross axis

The main axis is along the row, if the flex-direction is set to `row` and down the column if the flex-direction is set to `column`.

The cross axis runs at 90deg to the main axis - i.e. perpendicular to the row if flex-direction is sit to `row` and perpendicular to the column if flex-direction is set to `column`.

### How certain properties of flexbox negatively impact accessibility

Care should be taken when using properties that display the order differently from the HTML structure (such as flex-directions `row-reverse` and `column-reverse`) as this can confuse the meaning when accessing the document using a screen reader, and should not be used when the order of the elements is significant. The screen reader will read the logical order, not the visual order.
