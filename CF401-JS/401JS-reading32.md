# Hooks and Context exmaple

*1. With regard to the React Context API, what does a “provider” do?*
A context provider is responsible for displaying the local state of an object, and for exposing an API for globally managing them. 


*2. With regard to the React Context API, how would we implement a “consumer” role?*
A custom hook can be used to wrap the useContext internal React hook, which consumes our new context.


*3. Specifically with Context, how are we “wrapping” components to achieve our goals?*

We use Custom Hooks as wrappers around internal React hooks.


# Awesome React Context Links

Takeaway 1: React New Lifecycles: React version 16.3 has mad a few updates to the StrictMode component that help with identifying components with unsafe lifecycles, warning about legacy string ref API usage, and detecting unexpected side effects. 

Takeaway 2: React Blogs - How to Optimize Your Context Value: The simplest solution to optimizing your context value involves using useReducer or useState for your state management and putting the state in one context provider and the dispatch in another.
