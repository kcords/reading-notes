Ternary operators could be beneficial in the conditional rendering of components based on selected filters.

### React Forms

1. What is a ‘Controlled Component’?
   * An input form element whose value is controlled by React
2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why?
   * It depends on whether it is a controlled or uncontrolled component, and what we are needing to accomplish
3. How do we target what the user is entering if we have an event handler on an input field?
   * The first parameter `event` is passed into the event handler, and will have a property of `target`. So the exact value of the input can be accessed at `event.target.value`

### The Conditional (Ternary) Operator Explained

1. Why would we use a ternary operator?
   * In react, it can be used to conditionally render a component. In standard JS code, it can create a simple, single line conditional statement when assigning values
2. Rewrite the following statement using a ternary statement:
   * `console.log(x === y ? 'true' : 'false')`

### References

* [React Forms](https://reactjs.org/docs/forms.html)
* [Conditional Rendering](https://legacy.reactjs.org/docs/conditional-rendering.html)
* [Ternary Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)

### Things I want to know more about

* More of a reminder note that multiple actions can occur within a ternary utilizing a `,`
