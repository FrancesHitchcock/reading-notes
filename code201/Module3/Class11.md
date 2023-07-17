# Module 3 Class 11 Reading Notes

## Video and Audio Content

### Evolution of video and audio on the web since early 2000s

The original web video and audio required plug-ins such as **_flash_** and **_silverlight_**. The are now obsolete, and video and audio content are now handled using HTML `<video>` and `<audio>` elements, which are more secure and accessible.

### The use of `src` and `controls` attributes in the `<video>` element

The `src` attribute value is a link to the url of the source file - either locally or on the web. The `controls` attribute is a boolean attribute and defaults to true. It should always be included as it gives the user control over if, when and how they want to view the content.

### The importance of **fallback content** inside the `<video>` element

Some (older) browsers don't support video / audio content, so it's important to inform the user of this.

## Grid

### How the Grid layout differs from Flexbox

Whereas flexbox has a one-dimensional layout, the grid layout is two-dimensional.

### Grid container, grid items and grid lines

The grid container is the parent element on which `display: grid` is applied. Its direct children are the grid items. The grid lines are the vertical and horizontal lines between the rows and columns.

Useful grid guide: [CSS tricks](https://css-tricks.com/snippets/css/complete-guide-grid/)

## Responsive Images

### Why developers should make images responsive

Responsive images help improve performance across devices. It allows a smaller image to be downloaded on a smaller device where bandwidth might be an issue, and a larger image for a larger device to avoid a "pixellated" effect.

### The `<img>` attributes `srcset` and `sizes`

`srcset` contains a comma-separated list of the different image urls. `sizes` contains a comma-separated list of the sizes at which they should be displayed, along with the corresponding media queries.

### How `srcset` can be more helpful than CSS or JavaScript

It's helpful to render a cropped image on a handheld device, so as to be able to see a smaller, detailed area of the image clearly without compromising bandwidth.

## Images in HTML

Embedding images: [MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)

### `<iframe>`, `<embed>` and `<object>`

Other embedding technologies: [MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Other_embedding_technologies)
