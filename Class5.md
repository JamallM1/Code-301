## Class 5
- What is the single responsibility principle and how does it apply to components?
  - a component should ideally only do one thing
- What does it mean to build a ‘static’ version of your application?
  - render in the user's browser without the need for server side processing
- Once you have a static application, what do you need to add?
  - Inverse Data Flow
- What are the three questions you can ask to determine if something is state?
  - Is it passed in from a parent via props?
  - Does it remain unchanged over time?
  - Can you compute it based on any other state or props in your component?
- How can you identify where state needs to live?
  - Identify every component that renders something based on that state.
  - Find a common owner component
  - Either the common owner or another component higher up in the hierarchy should own the state.
  - If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.
  

- What is a “higher-order function”?
  - functions that operate on other functions
- Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
  - m arrow m greater than n
- Explain how either map or reduce operates, with regards to higher-order functions.
  - 
