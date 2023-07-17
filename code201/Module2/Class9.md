# Module 2 Class 9 Reading Notes

## HTML forms

### Why forms are important in web development

Forms allow users to interact with the app. They provide a way for the program to collect user data, and confirmation to the user that they are interacting, if some of their details are played back to them immediately, such as via a greeting with their name.

### Key things to keep in mind regarding user experience

Draw a mockup before starting on the markup. The display should make it easy for the user to understand which input or text area aligns with which label.

The form should be simple and as succinct as possible. It should only request data that is actually required.

### Five form elements

- `<form>` - This element formally defines the form and encloses the child elements. A `<button>` contained within a `<form>` element will adopt the behaviours of a `<input type="submit">`element.
- `<fieldset>` and `<legend>` - The `<fieldset>` element can be used with `<legend>` to group and label related data items within the `<form>`.
- `<input>` - The `<input>` element is for single line responses, and should include a `type` attribute.
- `<textarea>` - A `<textarea>` invites the user to give a more detailed answer - perhaps several lines.
- `<label>` - A label indicates to the user what information is required in the input field. It is also a clickable element, so when linked correctly it will highlight its linked form field when clicked. It is read by screen readers.

## JavaScript Events

### An event is ...

Something that happens to the system, that the code is programmed to respond to. This could be a user click or mouseover. Or it could be the completion of the DOM loading.

### `addEventListener()` arguments

The `addEventListener()` method takes the event as the first argument and a function (event handler) as the second argument, which will run when the event occurs.

### The event object and why the target is useful

The event object is a collection of properties that describe the event. One of these is properties if the event `target`, and the target is the element on which the event occurred, which is useful if we want to make changes to that element.

### Bubbling and capturing

Bubbling is where you the event listener target has child elements, and the event target includes those child elements. For example, if you set an event listener to listen for an event on a `<div>` then it will also register if you click on a button that is a child of the `<div>`. If we set event listeners on child and ancestor elements the events will fire or `bubble from the child elements **up** through the family tree and will take place in that order. We can stop this from happening with the stopPropogation() method.

Event capture is the opposite of bubbling in that the events occur in the opposite order - from parent element **down** through the family tree. Capture will only take place if `{capture: true}` is passed to the event handler function as a third argument.
