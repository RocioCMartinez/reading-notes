# Passing Functions as Props

Todays reading taught me about the spread operator. I did not know it could do so many things. Also got to watch a video reviewing the use of props and changing a components state.

## lists and keys

1. What does .map() return?
2. If I want to loop through an array and display each value in JSX, how do I do that in React?
3. Each list item needs a unique ____.
4. What is the purpose of a key?

## Answers

1. .map() returns an new array with modified elements from the original array used.
2. In order to display values in JSX, the use of curly braces is needed. You can build a new array and use .map() to modify elements then convert with curly braces.
3. Key.
4. *"Gives the elements a stable identity"* , This is helpful if the order of items may change.

## The Spread Operator

1. What is the spread operator?
2. List 4 things that the spread operator can do.
3. Give an example of using the spread operator to combine two arrays.
4. Give an example of using the spread operator to add a new item to an array.
5. Give an example of using the spread operator to combine two objects into one.

## Spread Operator Answers

1. A series of 3 dots (...) that allows expantion of an iterble object to display as a list of arguments.
2. Can do the following;

- Copying an array
- Concatenating or combining arrays
- Using Math functions
- Using an array as arguments
- Adding an item to a list
- Adding to state in React
- Combining objects
- Converting NodeList to an array

3. Here is an example of how to combine arrays (Array Concatention).

- const myArray = [`a`, `b`, `c`]
- const yourArray = [`g`, `h`, `i`]
- const ourArray = [...myArray,...yourArray]
- console.log(...ourArray) // a b c g h i

4. Adding new item to an array.

- const myArray = [`a`, `b`, `c`]
- const newArray = [...myArray, `d`, `e`, `f`]
- console.log(...newArray)// a b c d e f

5. Combining 2 objects

- const objectOne = {class: 'classmates'}
- const objectTwo = {student: 'Rocio'}
- const objectThree = {...objectOne, ...objectTwo, instructor: 'Audrey'}
- console.log(objectThree) // Object { class: 'classmates', student: 'Rocio', instructor: 'Audrey'}

## How to Pas Functions Between Components

1. In the video, what is the first step that the developer does to pass functions between components?
2. In your own words, what does the `increment` function do?
3. How can you pass a method from a parent component into a child component?
4. How does the child component invoke a method that was passed to it from a parent component?

## Video Answers

1. The first step the developer took was to create a function (arrow function) to increment the count.
2. Creates new array called ppl, it loops through the people array and uses the name property match to increase the count, then changes the state.
3. Through the use of props! Must also define function at this level.
4. A child component has access to anything in the parent, so it would need to invoke the method with props at its own component level.

## Resources

<https://reactjs.org/docs/lists-and-keys.html>

<https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab>

<https://www.youtube.com/watch?v=c05OL7XbwXU>

<https://reactjs.org/tutorial/tutorial.html>

<https://reactjs.org/docs/lifting-state-up.html>

## Things I want to know more about

I still need to get used to the new syntax in React.
