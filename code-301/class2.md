# State and Props

This reading covers important concepts of React. First is the lifecycle, there is an order to the way things proces and happen when using React, it is important to understand this so that you know where to place information or code. Next is state vs. props. Props seems to more static, code or information that does not change. State is best practice when information will be updated or changed based on a user.

## React lifcycle Questions

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
2. What is the very first thing to happen in the lifecycle of React?
3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
4. What does componentDidMount do?

## Answers

1. Based off the diagram the 'render' will happen first.
2. There are 3 phases in component lifecycle listed in order; Mounting, Updating, and Unmounting.
3. Constructor, render, React Updates, componentDidMount, componentWillUnmount.
4. It is a method, invoked after a component is mounted. Best place to load using a network request or initialize the DOM.

## Video Questions

1. What types of things can you pass in the props?
2. What is the big difference between props and state?
3. When do we re-render our application?
4. What are some examples of things that we could store in state?

## Video Answers

1. Counter starting value, titles, subtitles.
2. State is handled inside the components, props are handled outside the components.
Props is typically static info, state is typically dynamic info.
3. When you want to update components after user interaction(set a new value based on user input).
4. We could store the updated values of a counter or form.

## Resources

<https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093>

<https://www.youtube.com/watch?v=IYvD9oBCuJI>

<https://www.youtube.com/watch?v=IYvD9oBCuJI>

<https://reactjs.org/docs/handling-events.html>

<https://reactjs.org/tutorial/tutorial.html>

<https://react-bootstrap.github.io/>

<https://getbootstrap.com/docs/5.0/examples/cheatsheet/>

<https://bootstrapshuffle.com/classes>

<https://www.netlify.com/>

## Things I want to know more about

React in general, there is a lot more to it than I was expecting