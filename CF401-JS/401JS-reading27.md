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




How would you identify a custom Hook and why might you create one?
