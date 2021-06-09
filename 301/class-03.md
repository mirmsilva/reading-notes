# Day 3 Reading Notes

## Lists & Keys

- What does .map() return?
  - A new array with the results of each element in the original array being passed through a function
- If I want to loop through an array and display each value in JSX, how do I do that in React?

- Each list item needs a unique ____.
  - key

- What is the purpose of a key?
  - They help react identify what items have changed, added or removed. thye give they inside the array a stable identity

## Spread Operator

- What is the spread operator?
  - An ellipsis (...) that expand an iterable object into a list of arguments
- List 4 things that the spread operator can do.
  - copy an array
  - adding to state to in React
  - combine objects
  - use an array as arguments
- Give an example of using the spread operator to combine two arrays.
  - arr1 = [1,2,3]
  - arr2 = [4,5,6]
  - arr1and2 = [...Arr1,...Arr2]
  - ...arr1and2 = 1,2,3,4,5,6
- Give an example of using the spread operator to add a new item to an array.
  - arr1 = [1,2,3]
  - arr2 = [4,5,...arr1]
  - arr2 = [1,2,3,4,5]
- Give an example of using the spread operator to combine two objects into one.
  - object1 = {hello: bear}
  - obejct2 = {goodbye:cat}
  - object3 = {...object1, ...obeject2,}
  - object3 = {hello: bear, goodbye: cat}

## How to pass functions between components

- In the video, what is the first step that the developer does to pass functions between components?
  - create a fucntion where the state is
- In your own words, what does the increment function do?
  - it raised the orginal value by one
- How can you pass a method from a parent component into a child component?
  - use this.functionName()
- How does the child component invoke a method that was passed to it from a parent component?
  - use this.props.functionName()

[Back to Main](README.md)

### My Sources:
- https://reactjs.org/docs/lists-and-keys.html
- https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab
- https://www.youtube.com/watch?v=c05OL7XbwXU