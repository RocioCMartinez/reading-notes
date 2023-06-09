# Thinking in React/Higher-Order Functions

## Thinking in React

1. What is the `single responsibility principle` and how does it apply to components?
2. What does it mean to build a ‘static’ version of your application?
3. Once you have a static application, what do you need to add?
4. What are the three questions you can ask to determine if something is state?
5. How can you identify where state needs to live?

## Answers

1. This is the idea that a component should only do one thing (one purpose), if it aquires more then it should be divided up into subcomponents.
2. Building a 'static' version of your app means that you build out your components without dynamic features (you dont mess with the interactivity of the component... yet) this helps with foundation.
3. Once your static version is complete you would need to add state, state needs to be the minimal functions your code must use to change data based on user interaction.
4. 

- ***"Does it remain unchanged over time? If so, it isn’t state."***

- ***"Is it passed in from a parent via props? If so, it isn’t state."***

- ***"Can you compute it based on existing state or props in your component? If so, it definitely isn’t state!"***

5. ***"For each piece of state in your application:"***

- ***"Identify every component that renders something based on that state."***
- ***"Find their closest common parent component—a component above them all in the hierarchy."***
 ***"Decide where the state should live:"***
- ***"Often, you can put the state directly into their common parent.You can also put the state into some component above their common parent."***
- ***"If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common parent component."***

## Higher-Order Functions

1. What is a “higher-order function”?
2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
3. Explain how either map or reduce operates, with regards to higher-order functions.

## Responses

1. It is a functions that will take other functions as arguments.
2. It is returning an element as long as the element is greater than the n (number) it was passed above.
3. Map will work normally by returning a new array but its contents will take a new form by the function.

## Resources

<https://reactjs.org/docs/thinking-in-react.html>

<https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK>

## Things I want to know more about
