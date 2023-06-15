# In Memory Storage

## Understanding the Javascript Call Stack

1. What is a ‘call’?
2. How many ‘calls’ can happen at once?
3. What does LIFO mean?
4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
5. What causes a Stack Overflow?

## Response

1. Function invocation.
2. One at a time in order of top to bottom.
3. Last in, first out principle.
4. Example below from *The JavaScript Call Stack* by Charles Freeborn.

`function firstFunction(){
  throw new Error('Stack Trace Error');
}`

`function secondFunction(){
  firstFunction();
}`

`function thirdFunction(){
  secondFunction();
}`

`thirdFunction();`

5. If there is a recursive function, a function without exit point (looping in calling itself).

## Javascript error messages

1. What is a ‘reference error’?
2. What is a ‘syntax error’?
3. What is a ‘range error’?
4. What is a ‘type error’?
5. What is a breakpoint?
6. What does the word ‘debugger’ do in your code?

## Answers

1. Reference errors are when you dont define a variable.
2. When something cannot be parsed.
3. When there is an problem with the length of an item, it would be considered out of range. For example an array does not have a negative length.
4. When component types are incompatible.
5. A breakpoint is a stopping point for the code to run. It can help when trying to fix errors.
6. Helps you see the history before that breakpoint. Helps ensure the code works in sections..

## Resources

<https://medium.freecodecamp.org/understanding-the-javascript-call-stack-861e41ae61d4>

<https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c>

<https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors>

## Things I want to know more about

More about the developer tools in our VS Code editor.
