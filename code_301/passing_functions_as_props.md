### Lists and Keys

1. What does .map() return?
   * A new array of the same length, with each item as returned from the provided callback
2. If I want to loop through an array and display each value in JSX, how do I do that in React?
   * Using a .map method on an array, provide a callback that will output a JSX element that will utilize the values from the array as props
3. Each list item needs a unique ____.
   * String attribute called a "key"
4. What is the purpose of a key?
   * It helps React itentify when sibling items have been added, removed, or changed

### The Spread Operator

What is the spread operator?

1. List 4 things that the spread operator can do.
   1. Concatinate/combine arrays or objects
   2. [Shallow] Copy arrays or objects
   3. Spread an array passed as a single argument into separate arguments in a function call, (i.e. Math methods like `Math.min()`)
   4. Convert array-like iterables into an array (i.e. string, nodeList, etc.)
2. Give an example of using the spread operator to combine two arrays.
   * `const newArr = [...arr1, ...arr2]`
3. Give an example of using the spread operator to add a new item to an array.
   * `const newArrWithAddlItem = [...arr, 'new item']`
4. Give an example of using the spread operator to combine two objects into one.
   * `const combinedObj = {...obj1, ...obj2}`
