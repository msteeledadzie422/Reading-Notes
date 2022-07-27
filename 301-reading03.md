# Lists and Keys

1. The map() function makes a copy of a given array and allows the user to adjust each element of the array into a newly specified element (ie. the original value of each original array element is doubled in the newly mapped array).
2. To include elements in JSX you need to include them in curly braces. To loop through an array and display each value in JSX in React you would loop through the array using the JS map() function and then return each array element within a component (a list item, for example) by wrapping the return element in curly braces.
3. Each list item needs a unique key.
4. Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity.

# The Spread Operator

1. The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.
2. The spread operator can:
     1. Copy an array
     2. Concatenate or combine an array
     3. Use Math functions
     4. Use an array as arguments
3. const fruits = ['🍏','🍊','🍌','🍉','🍍']
   const moreFruits = [...fruits];
4. console.log(moreFruits) // Array(5) [ "🍏", "🍊", "🍌", "🍉", "🍍" ]
   fruits[0] = '🍑'
   console.log(...[...fruits,'...',...moreFruits]) //  🍑 🍊 🍌 🍉 🍍 ... 🍏 🍊 🍌 🍉 🍍
5. const objectOne = {hello: "🤪"}
   const objectTwo = {world: "🐻"}
   const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
   console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
   
 # How to Pass Functions Between Components
 
 1. The first thing the developer does to pass functions between components is create a function wherever the state is that we are going to change.
 2. The developer uses the increment function to update the count property within the state of the App component
 3. By going to the child component reference in the parent component and creating a new variable and calling the parent component method using this."function name".
 4. By calling that method within an existing method in the child component using this.props."function name".
