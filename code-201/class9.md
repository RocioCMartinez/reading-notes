# Class 9 Notes

This reading covers the topics of forms and events. Forms gather user data and can process and store it which is super helpful in many applications. Events can be used in forms but are more user interaction focused functions.

Form elements are more complex when compared to most HTML Elemnts. They work best when mixing a close marriage of related JavaScript and CSS.

A point of interaction. Forms let users enter date and send it to a server for processing and storage. Can also be used to update user interfaces.

*"The action attribute defines the location (URL) where the form's collected data should be sent when it is submitted.
The method attribute defines which HTTP method to send the data with (usually get or post)."*

## Web Form

1. Why are forms so important in web development?
2. When designing a form, what are some key things to keep in mind when it comes to user experience?
3. List 5 form elements and explain their importance.

## Web Form Answers

1. Forms are so important because they help gather user data.
2. We have to help them by making it simple to understand how to fill out the form and validating input. Only ask for data you need to keep user focused.
3. Forms start with `<form>` element. This is a container now specifically to forms, like `<section>` or `<div>`. Standard practice is to set 2 attributes; **action** and **method**.
Next are the `<label>`, `<input>`, and `<textarea>` elements. Label is for a single-line text field. Input should be accepting only valid data for this field (like email). Textarea is a multiline text field. The `<button>` element. Can accept a type attribute like **submit, reset, or button**. Submit sends the datat to server UL, reset is bad practice since it will wipe info and default to original settings, button by default does nothing but can be used for custom actions.

## Events

1. How would you describe events to a non-technical friend?
2. When using the addEventListener() method, what 2 arguments will you need to provide?
3. Describe the event object. Why is the target within the event object useful?
4. What is the difference between event bubbling and event capturing?

## Event Answers

1. An event is like a planned response. You want users to be ble to interact with certain elements on your page so that interaction triggers a response of your choosing. Example: user 'clicks' or types a key button.
2. The two arguments needed are a string of what to listen for like "click", "mouseover", or "keydown". The second is a function to call. What the reaction/response should be, like displaying a message or changing a color.
3. An event object is a perameter inside an event handler function. It can provide extra features and informatation.
4. Event bubbling and event capturing work in a similar manner. Event bubling works from the inside out. Starting in the inner most nested elements. Event capturing works from the outside in. Starting in the outter elements when nested and working in.

## Resources

<https://developer.mozilla.org/en-US/docs/Learn/Forms>

<https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form>

<https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_structure_a_web_form>

<https://developer.mozilla.org/en-US/docs/Learn/JavaScript>

<https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events>

<https://developer.mozilla.org/en-US/docs/Learn/Forms/HTML5_input_types>

<https://developer.mozilla.org/en-US/docs/Web/Events>

## Things I want to know more about

Understanding event listeners fully especially when nested.
