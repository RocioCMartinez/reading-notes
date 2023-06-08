# React and Forums

In this reading we learn that React uses forms in more of a real time manner and can do more with the user input although it does require a bit of code. We also learned how to write conditional statements using the ternary operator.

## Forms

1. What is a ‘Controlled Component’?
2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
3. How do we target what the user is entering if we have an event handler on an input field?

## Response

1. A controlled component is a React component that renders an input form element AND controls its state. 
2. We should update the state  as the user types, becuse you can pass the value to other UI elements.
3. Add a `name` value to each attribute then use `event.target.name` to let handler function run.

## The Conditional (Ternary) Operator

1. Why would we use a ternary operator?
2. Rewrite the following statement using a ternary statement:

`if(x===y){
  console.log(true);
} else {
  console.log(false);
}`

## Answers

1. Works as an *if* statement, beneficial when setting conditions to running code.
2. 

`let z = x===y ? 'true': 'false'
console.log(z)`

## Resources

<https://reactjs.org/docs/forms.html>

<https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff>

<https://react-bootstrap.github.io/forms/overview/>

<https://reactjs.org/docs/conditional-rendering.html>

## Things I want to know more about

Although the ternary operator seems simple enough I think I'm going to need more practice.
