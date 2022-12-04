# Thinking in React

1. The single responsibility principle stipulates that a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.
2. A static version of your application takes your data model and renders the UI but has no interactivity.
3. Once you have a static application you need to add UI. To make your UI interactive, you need to be able to trigger changes to your underlying data model. React achieves this with state.
4. The three questions you can ask yourself to determine if something is state:
    1. Is it passed in from a parent via props? If so, it probably isn't state.
    2. Does it remain unchanged over time? If so, it probably isn't state.
    3. Can you compute it based on any other state or props in your component? If so, it isn't state.
5. For each piece of state in your application:
    - Identify every component that renders something based on that state.
    - Find a common owner component (a single component above all the components that need the state in the hierarchy).
    - Either the common owner or another component higher up in the hierarchy should own the state.
    - If you can't find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

# Higher-Order Functions

1. Fuctions that operate on other functions, either by taking them as arguments or by returning them, are called higher-order functions.
2. It is creating a new function m that checks to see if the statement m > n is true.
3. You could map over a function that creates an array, making the map function a higher-order function.
