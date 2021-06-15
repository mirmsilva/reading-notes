# Day 5 Reading Notes

## Thinking in React

- How would you break a mock into a component heirarchy?
  - Draw boxes around every component and sub component & give them names
  - Each component should do one thing. 
  - UI & Data models tend to adhere to the same information

- What is the single responsibility principle and how does it apply to components?
  - a component should do one thing. Once it starts doing more break it up  

- What does it mean to build a ‘static’ version of your application?
  - build a verision of your app that renders all the information but has no interactivity. You do not use state at this point.

- Once you have a static application, what do you need to add?
  - Think about the minimal set of mutable state. Think **DRY**

- What are the three questions you can ask to determine if something is state?
  - Is it passed in from a parent via props? If so, it probably isn’t state.
  - Does it remain unchanged over time? If so, it probably isn’t state.
  - Can you compute it based on any other state or props in your component? If so, it isn’t state.

- How can you identify where state needs to live?
  - Identify every component that renders something based on that state.

  - Find a common owner component (a single component above all the components that need the state in the hierarchy).

  - Either the common owner or another component higher up in the hierarchy should own the state.

  - If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

[Back to Main](README.md)

### My Sources:
- https://reactjs.org/docs/thinking-in-react.html 