# Module 1 Class 3 Reading Notes

## React Lists and Keys

### `.map()`

`.map()` returns a new array of all the elements from the original array, which have had the same operation performed on them.

### Loop through an array and display each value in JSX

Set up a variable and assign to it the return value of the mapped array where each item is wrapped in JSX tags. e.g.

```
const people = ["Ann", "Bob", "Charlie", "Dan"];

function PeopleList() {

const listItems = people.map((person) =>
<li>{person}</li>
);

return (
<ul>{listItems}</ul>
);
}
```

### List Items

Each list item needs a unique key

### Keys

Keys give each array item a stable identity and are there so React can identify which items have changed, are added, or are removed.
