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
