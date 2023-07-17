# Module 1 Class 5 Reading Notes

## HTML Media

### The `alt` attribute

The value of the `alt` property is a string which will display if for some reason the image is not available. If there is already a description of the image in the rendered text then its value can be an empty string.

### Accessibility of images

Use the `alt` text with screen readers in mind - it's important for the text to be sufficiently descriptive.

### Using the `<figure>` element

The figure element is useful for when you want a caption to be linked directly with an image. Both the `<img>` and the `<figcaption>` elements are children to the `<figure>` element. This could be helpful when displaying a gallery of images for example.

### .gif images vs .svg images

.gif supports simple animations. It also supports interlacing, so if there is a slow network a lower quality version of the image is displayed while the page is loading.

.svg does not rely on pixels to display, but on a mathematical formula, which means it's ideal for charts and diagrams that need to display accurately at any size.

### A screenshot as an image

I would use a .jpg or a .png for a screenshot, depending on what it depicts. If it's a detailed colour image probably a .jpg. If it's a simple image with few colours or monochrome then .png.

## CSS Color and Styling HTML Text Elements

### Foreground color and background color

The `background-color` property is used to determine the background colour of an element. By contrast, the `color` property determines the colour of text and text decorations.

### Adding colour to a monchrome site

I would choose a good dark colour and a good light colour and one or more mid-tone accent colours. These could be black and white but not necessarily. The accent colours should provide sufficient contrast with both the light and the dark. You can then use any of the colours as background colours, with one of the contrasting colours for the text. Play around with it until you get it looking good. Don't use too many colours or it can lose its sense of 'theme' and look messy. If the site contains an image, then the colours chosen could be inspired by colours in the image.

### Choosing fonts for an HTML document

You should use the font-family property and specify any number of fonts in the form of a font-stack, along with a fall-back web-safe font and a default generic font such as 'sans-serif'.

### `font-weight`, `font-size` and `font-style`

- The `font-weight` property determines how thick or thin the strokes of the characters are. Values include 'bold', 'lighter' or a numberic value.
- The `font-size` property determines the size of the text, and values can be set absolutely in pixels, rem, em or given a relative value such as vw.
- The `font-style` property determines whether the text will be 'normal', 'italic' or 'oblique'.

### Adding spacing around characters in an `<h1>` element

To add spacing between the characters you can use the `letter-spacing` and '`word-spacing` properties. You can also use `line-height` which controls the distance between lines.

## Things I want to know more about

Designing beautiful pages
