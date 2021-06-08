# Day 2 Reading Notes

## React Lifecycle

- Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’? Mounting.

- What is the very first thing to happen in the lifecycle of React? Mounting an insistance of a component  is being created and inserted into the DOM

- Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
  - constructor
  - render
  - componentDidMount
  - react updates
  - componentWillUnmount

- What does componentDidMount do?
  - after a component is mounted if you need to load or initialize DOM you would need to do it here. Set subscriptions

## React State VS Props

- What types of things can you pass in the props?
  - arguments of a function. Thing that you want to initialize your component to do. Variable to a function.
- What is the big difference between props and state?
  - props are used for things that aren't going to change,  props are handled outisde a component and then passed into a component. state is handled inside the component
- When do we re-render our application?
  - when your data changes i.e when our props change
- What are some examples of things that we could store in state?
  - when you need to update and re-nder based on user info. Could be used in forms. Use state to store user input.

[Back to Main](README.md)

### My sources:
- https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093
- https://www.youtube.com/watch?v=IYvD9oBCuJI
