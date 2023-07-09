It is important to know the react lifecycle and state/prop management to ensure that you have a dynamic and performant site.

### React Lifecycle

1. What happens first, the ‘render’ or the ‘componentDidMount’?
   - Render
2. What is the very first thing to happen in the lifecycle of React?
   - Mounting
3. Put the following things in the order that they happen:
   - constructor
   - render
   - React Updates
   - componentDidMount
   - componentWillUnmount
4. What does componentDidMount do?
   - Invoked after component is mounted and is a great place for network requests

### React State vs Props
1. What types of things can you pass in the props?
   - External values from another component
2. What is the big difference between props and state?
   - Props are passed in and updated externally, state is handled inside the component and is managed internally
3. When do we re-render our application?
   - When props change, or state changes internally
4. What are some examples of things that we could store in state?
   - Form values, updating values, anything that needs to be changed within the component

### References

- [React Lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)
- [React State vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)

### Things I want to know more about
- How to identify rerender issues such as
  - Unnecessary rerenders affecting performance
  - Failure to rerender
