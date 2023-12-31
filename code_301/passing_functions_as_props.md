Iterating over values to conditionally render reusable child components is a core concept of React. Additionally, updating state from a child component is a task that is frequently performed in React. So understanding these concepts is pivitol to successful React application development.

### Lists and Keys

1. What does .map() return?
   * A new array of the same length, with each item as returned from the provided callback
2. If I want to loop through an array and display each value in JSX, how do I do that in React?
   * Using a .map method on an array, provide a callback that will output a JSX element that will utilize the values from the array as props
3. Each list item needs a unique ____.
   * String attribute called a "key"
4. What is the purpose of a key?
   * It helps React identify when sibling items have been added, removed, or changed

### The Spread Operator

1. List 4 things that the spread operator can do.
   1. Concatenate/combine arrays or objects
   2. [Shallow] Copy arrays or objects
   3. Spread an array passed as a single argument into separate arguments in a function call, (i.e. Math methods like `Math.min()`)
   4. Convert array-like iterables into an array (i.e. string, nodeList, etc.)
2. Give an example of using the spread operator to combine two arrays.
   * `const newArr = [...arr1, ...arr2]`
3. Give an example of using the spread operator to add a new item to an array.
   * `const newArrWithAddlItem = [...arr, 'new item']`
4. Give an example of using the spread operator to combine two objects into one.
   * `const combinedObj = {...obj1, ...obj2}`

### How to Pass Functions Between Components

1. In the video, what is the first step that the developer does to pass functions between components?
   * Pass the method to update state as a prop
2. In your own words, what does the increment function do?
   * Creates a new `ppl` array from current state, then using `map`, increments the count on the person object whose `name` field matches the `name` parameter. It then sets that new array as the value for `people` in state
3. How can you pass a method from a parent component into a child component?
   * Pass the function/method as a prop to the child
4. How does the child component invoke a method that was passed to it from a parent component?
   * Call it just like any other callback function. In a React class component, it would look something like `this.props.propMethodName(expectedArg)`

### References

- [Lists & Keys](https://reactjs.org/docs/lists-and-keys.htmlhttps:/)
- [The spread operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fabhttps:/)
- [How to pass functions between components](https://www.youtube.com/watch?v=c05OL7XbwXUhttps:/)

### Things I want to know more about
- How rerenders affect functions passed as props and what performance issues can arise when state is updated this way