Proper state management is critical for interactive components. HOF such as map and reduce can be important to understand for rendering or shaping data records.

### Thinking in React

1. What is the single responsibility principle and how does it apply to components?
   * It states that a class should have only one job or responsibility. Keeping things simple and focused makes it easier to understand, maintain, and modify the code
   * It applies in that a component should only do one thing
2. What does it mean to build a ‘static’ version of your application?
   * It renders the UI from your data model
3. Once you have a static application, what do you need to add?
   * Interactivity
4. What are the three questions you can ask to determine if something is state
   1. Does it change over time
   2. Is it passed in props
   3. Can it be computed within the component from existing state or props
5. How can you identify where state needs to live?
   1. Identify components that depend on that state
   2. Find closest common parent
   3. Put it in the commmon parent, a higher component, or a new state component

### Higher-Order Functions

1. What is a “higher-order function”?
   * "Functions that operate on other functions, either by taking them as arguments or by returning them"
2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
   * Returns a function that will return another function. The first takes in `n`, the second takes in `m`. The second function will return a boolean depending on whether the value of `m` is greater than `n`
3. Explain how either map or reduce operates, with regards to higher-order functions.
   * Both are higher-order functions. `map` accepts a function to transform elements of an array & returns a new array with transformed values, `reduce` accepts a function that reduces an array to a single value by iteratively applying a callback function to each element

### References

- [React Docs - Thinking in React](https://reactjs.org/docs/thinking-in-react.html)
- [Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

### Things I want to know more about
