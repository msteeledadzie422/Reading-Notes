# React Lifecycle

1. Render occurs before componentDidMount.
2. The constructor is the firs tthing to happen in the lifecycle of React.
3. constructor, render, React Updates, componentDidMount, componentWillUnmount.
4. the componentDidMount() method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here.

# React State vs. Props

1. when you create a component in React, you pass the Props you would like that Component to have into the Component. Props are used to initialize your component or to get it to render an initial state to what/how you would like.
2. Difference between Props and State: Props you _pass into_ a component, States _happen inside_ of a Component - Props exist outside of a Component.
3. When do we re-render our application: when you change the state inside of your application, that section of your application will re-render.
4. Examples of things to store in Sate: State is for when you need to re-render and update your application based on something the user has done. If you want to change something in your application, you need to store that in State so that it properly re-renders when that actually changes
