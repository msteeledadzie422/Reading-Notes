# useReducer hook

*1. Name an alternative to the useState Hook.*
useReducer is an alternative to useState. useReducer eaccepts a reducer type (state, action) => newState, and returns the current state paired with a dispatch method.


*2. Why might the useReducer Hook be preferable to the useState Hook?*
useReducer is usually preferable to useState when you have complext state logic that involves multiple sub-values or when the next state depends on the previous one.

useReducer also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks.


*3. What are two ways to set the initial state?*
The simplest way to set the initial state is to pass the initial state as a second argument.

You can also create the initial state lazily. To do this, you can pass an init function as the third argument. The initial state will be set to init(initialArg).


# Ultimate Guide to useReducer

*1. In terms of state, what does useReducer expect to receive as a parameter?*
It expects to receive state as a second parameter.


*2. What does useReducer return?*
useReducer returns an array that holds the current state value and a dispatch function to which you can pass an action and later invoke it.


*3. Explain dispatch to a non-technical recruiter.*
The dispatch function accepts an object that represents the type of action we want to executee when it is called.

Basically, it sends the type of action to the reducer function to perform its job, which is updating state.





