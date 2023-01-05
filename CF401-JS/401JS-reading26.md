# react hello world

1. What are the building blocks of a React app?

Elements and components are the building blocks of a React app.


2. What is the difference between an element and a React component?

Components use props as inputs to return React elements describing what should appear on the screen.


3. What are some advantages of React’s component based architecture?

It allows you to split the UI into independent, reusable pieces, and think about each piece in isolation.


# Introducing JSX

1. What is JSX and why do we use it?

JSX is a syntax extension of JavaScript. Instead of artificially separating technologies by putting markup and logic in separate files, React separates concerns with loosely coupled unites called "components" that contain both.


2. Describe the process of embedding JavaScript expressions in JSX.

As an example, you can declare a variable and then use it inside JSX by wrapping it in curly braces. 

You can put any valid JavaScript expression inside the curly braces in JSX.


3. Is it safe to embed user input in JSX? Explain.

It is safe to embed user input in JSX. By defauly, React DOM escapes any values embedded in JSX before rendering them. Thus it ensures that you can never inject anything that's not explicitly written in your application. Everything is converted to a string before being rendered. This helps prevent XSS (cross-site-scripting) attacks.


# Rendering Elements

1. Explain what a React Component is to a non-technical friend.

Elements are "made up" of compoenents that "tell" the element what to render on the screen.


2. Describe mutability and React Components, specifically, how is the UI updated?

React elements are immutable. Once you create an element, you can't change its children or attributes. An element is like a single frame in a movie: it represents the UI ata certain point in time.

With our knowledge so far, the only way to update the UI is to create a new element, and pass it to root.render. 


3. If changes are made to the UI, what does React update?

React only updates what's necessary. React DOM compares the element and its children to the previous one, and only applies the DOM updates necessary to bring the DOM to the desired state.


