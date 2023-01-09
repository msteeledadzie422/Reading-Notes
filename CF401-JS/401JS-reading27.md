# Introducing Hooks

*What was the motivation for introducing Hooks?*

React doesn't offer a way to "attach" reusable behavior to a component, and it was felt that it needed a better primitive for sharing stateful logic.

With hooks you can extract stateful logic from a component so it can be tested independently and reused. Hooks allow you to reuse stateful logic without changing your component hierarchy. This makes it easy to share Hooks among many components or with the community.


*What changes are important regarding implementing Hooks versus Component Classes?*

Hooks let you use more of React's features without classes.

Hooks let you split one component into smaller functions based on what pieces are related (such as setting up a subscription or fetching data), rather than forcing a split based on lifecycle methods. You may also opt into managing the component's local state with a reducer to make it more predictable.


*Hooks allow you to reuse stateful logic without changing ___ _______.*

Hooks allow you to reuse stateful logic without changing your component hierarchy. 


# Hooks API

*Name two rules imposed by React Hook usage.*

Rule 1: Only call Hooks at the top level. Don't call Hooks inside loops, conditions, or nested functions.
Rule2: Only call Hooks from React function components. Don't call Hooks from regular JavaScript functions. (The only other valid place to call Hooks would be your own custom Hooks.)


*How would you identify a custom Hook and why might you create one?*

Custom Hooks allow you to reuse some stateful logic between components without adding more components to your tree.

We create these by creating a function with the name "use" that calls another Hook.
