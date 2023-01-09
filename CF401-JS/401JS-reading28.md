# Effect Hooks

*What purpose does useEffect serve in a function component compared to its counterpart(s) in class components?*
It allows you to perform side effects such as update the DOM in REACT, fetch data, or set up a subscription within function components.


*When using the useEffect Hook:*
  *What does useEffect do?*
  By using this Hook, you tell React that your component needs to do something after render. React will remember the function you passed and call it later after performing the DOM updates.


  *Why is useEffect called inside a component?*
  Placing useEffect inside the component lets us access a state variable (or any props) from from the effect. We don't need a special API to read it as it is already within the function scope.


*Explain the importance of properly implementing effects with Cleanup*
It is important to clean up so that we do not introduce memory leak. This is similar to how we manage componentDidMount and componentWillUnmount in a React class.
