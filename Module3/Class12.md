# Module 3 Class 11 Reading Notes

## Canvas

Canvas: [JavaScript Tutorial](https://www.javascripttutorial.net/web-apis/javascript-canvas/)

### What the `<canvas>` element allows the developer to achieve

`<canvas>` gives the developer the power to draw 2D shapes using JavaScript. It must have both `width` and `height` attributes to specify its size;

### The importance of the closing `</canvas>` tag

The closing tag is required, and any fallback text to be displayed if the browser does not support canvas should be enclosed between the opening and closing tages.

### What the `getContext()` method does

`getContext()` specifies the type of context, (e.g. "2d") which it takes as its argument.

## Chart.js

Chart.js [Chart.js](https://www.chartjs.org/docs/latest/)

### Chart.js and how to bring it into your project

Chart.js is a charting library and it needs to be downloaded into the project. You first need to create a `<canvas>` element where the chart will render. Then create a `new Chart` object with two argurments: the reference to the `canvas` element and an object containing the chart specifications and data.

### Three different chart types in Chart.js

Chart types include:

- bar
- bubble
- pie

Chart.js [Web Designer Depot] (https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/)

### Some advantages to displaying data in a chart over a table

Charts provide a visual display that can convey data quickly to the user.

### How Chart.js could improve my previous apps

Chart.js could improve the cookie-stand project data display

## Canvas resources

Drawing shapes: [mdn](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)

Applying style and colours: [mdn](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors)

Drawing text: [mdn](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text)
