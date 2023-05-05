# Class6 Notes

***"An object is a collection of related data and/or functionality."***

Data items in objects are considered the object's **properties**. Functions in an object are considered the object's **methods**.

**DOM** stands for Document Object Model. A document on the web is comprised of objects that hold data representation of structure and content. 

## JS Reading Questions

1. How would you describe an object to a non-technical friend you grew up with?
2. What are some advantages to creating object literals?
3. How do objects differ from arrays?
4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
5. Evaluate the code below. What does the term this refer to and what is the advantage to using this?

## Answers

1. An object is like a balloon filled with water. The water is composed of molecules (variables&functions renamed to properties/methods when inside an object). The object (balloon) holds together all the related data (water or properties/methods).
2. The advantage of object literals is that you are creating an object and writting out its content at the same time.
3. Objects are easier to work with than arrays, helps identify items by name where array is more idex location based.
4. If you are using a variable as an object property name it cannot be accessed through dot notation but will work in brackets.
5. this key word refers to current object. In the code this is referring to the object which would be ***dog***. When creating a variety of object literals you can use the same method definition for each object created, which would make code writting faster.

## DOM Questions

1. What is the DOM?
2. Briefly describe the relationship between the DOM and JavaScript.

## DOM Answers

1. A web document programming interface. ***"The DOM represents the document as nodes and objects; that way, programming languages can interact with the page."***
2. The DOM holds all the settings and features about a web document that can be accessed through JavaScript and other programs. It is like factory settings that have been defined making them accessible as shortcuts/functions in other programming languages.

## Resources

<https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics>

<https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction>

<http://simpleprogrammer.com/2013/07/15/understanding-the-problem-domain-is-the-hardest-part-of-programming>

<https://betterprogramming.pub/intermediate-javascript-whats-the-difference-between-primitive-values-and-object-references-e863d70677b>