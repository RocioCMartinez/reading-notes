# Class7 Notes

This reading went more into details around functions and how to use contructors to more efficiently build objects that reuse code. Big emphasis on prototypes and models, which makes sense since that is basically the core or shell.

## Domain Modeling

1. Explain why we need domain modeling.

## Answer

1. Domain modeling is important because it organizes data and can help target specific changes. Seems like it is more important in terms of research, you can set different attributes and organize data based on the predetermined model features.

## HTML Table Basics

1. Why should tables not be used for page layouts?
2. List and describe 3 different semantic HTML elements used in an HTML `<table>`.

## Answers

1. Tables shouldnot be used for page layouts due to accessibility. Screen readers outputs could be confusing due to the lack of flow organization and HTML tags. Code is harder to read making it harder to write, debug, or maintain. Tables size is determined according to content, this makes it harder to get a clear display of content and to manipulate as well.
2. First create the table with `<table></table>`.
Then use `<td>` (table data) to create cells in the table.
Next is `<tr>`(table row) `<td>s` go inside the table row tag.
Finally a `<th>` element adds a table header.

## Introducing Constructors

1. What is a constructor and what are some advantages to using it?
2. How does the term *this* differ when used in an object literal versus when used in a constructor?

## Constructor Answers

1. **"A constructor is just a function called using the *new* keyword"** They start with a capitalized letter and named after type of object. The advantage is to be able to effeciently create multiple objects with the same code inside.
2. It seems to work in a similar value with the difference being that in a constructor *this* is part of the property and method key rather than being referrenced later after key and value are determined.

## Object Prototypes Using A Constructor

1. Explain prototypes and inheritance via an analogy from your previous work experience.

In my previous work experience each biomed tech could be conidered a prototype. We recieved the same training and have the same tools available to us to do the job. Inheritance could be seen as different skills. We all have different skills ranging from physical strength to life experience. In coding when an object is created it not only looks at prototype but at inheritance as well to find the answer. When looking for the best biomed tech for the job you would consider the prototype (qualification/tools) and experiece or skill (inheritance) to find the best fit.

## Resources

<https://github.com/codefellows/domain_modeling#domain-modeling>

<https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics>

<https://ui.dev/beginners-guide-to-javascript-prototype>

<https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Advanced>

<https://chat.openai.com/> Prompt: explain prototypes and inheritance in coding

## Things I want to know more about

Building object prototypes.
