# Module 1 Class 4 Reading Notes

## HTML Hyperlinks

### Creating a basic link

1. Use the anchor `<a>` element and wrap the text you want displayed inside the opening and closing tags.
2. Add an the `href` attribute to the opening tag with a value that is the web address to visit.

The `<a>` element can wrap round other elements e.g. headers and images.

### The `href` attribute

This contains the web address value and optional attributes such as `target`.

### Links and accessibility

- Link title attributes which are displayed on hover, so if it contains important additional information this should be included in the rendered text.
- Link text should be descriptive, not just "click here". This is to aid search engines and improve SEO.
- Avoid using the URLs themselves as link text as screen readers will read them character by character.
- Stick to the default convention of underlining link text and displaying it in a different colour.
- Try not to link to the same target multiple times in the same document.

## CSS Layout

### Normal flow

Normal flow is the way the page elements automatically lay themselves out before any positioning has been altered using css.

### Block level vs inline

In normal flow a block level element takes up the available width of its containing element, whereas an inline element sits alongside its neighbours and wraps in the same way as normal text.

Top and bottom margins of block level elements collapse into each other, so the vertical margin between two block level elements will be the size of whichever is greater.

Margin top and margin bottom have no effect on inline elements except for certain ones like `<img>`.

### Default positioning

Static postioning is the default for every HTML element.

### Absolute positioning

Absolute positioning is useful when you want to remove an element from normal flow and display it in the same location relative to its nearest positioned ancestor, for example we might want an information box to pop up somewhere on top of the rest of an element's content.

### Fixed vs absolute positioning

An element with fixed positioning is positioned relative to the browser window.

## JavaScript Re-Usable Code

### Function declaration and invocation

A function declaration is where you define the function including its parameters and the code to be executed. When you want the function to run you have to call or 'invoke' the function that you have declared. A function declaration is 'hoisted', which means the invocation can appear before the declaration in the script.

### Parameters and arguments

The 'parameters' are defined inside the brackets of the function declaration. These act like variable names. When you invoke the function you need to pass it the corresponding values or 'arguments', which are like values to be assigned to the parameters when the function executes.

## Pair Programming

Source material: [Code Fellows](https://www.codefellows.org/blog/6-reasons-for-pair-programming/)

Two benefits of pair programming are:

- **Social skills** - this is a good opportunity to adopt a role, to communicate effectively using technical language and to practise getting on with other team members.

- **Learning from fellow students** - there are so many different approaches to solving coding problems, and we can get stuck in a mindset of relying on the same old skills and strategies. Learning alternative techniques from a coding partner is a good opportunity.

## Things I want to know more about

Behaviours of block, inline and inline-block elements
