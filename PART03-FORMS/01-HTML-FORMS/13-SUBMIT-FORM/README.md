Submit Form
===========

Remember, the purpose of a form is to collect information that will be submitted. That's the role of the submit button --- users click on it when they are finished with filling out information in the `<form>` and they're ready to send it off. Now that we've gone over how to create various input elements, let's now go over how to create a submit button!

To make a submit button in a `<form>`, we're going to use the reliable `<input>` element and set the `type` to `"submit"`. For instance:
````html
<form>
  <input type="submit" value="Send">
</form>

````

Which renders:

![rendered submit button](https://s3.amazonaws.com/codecademy-content/courses/learn-html-forms/submit+button2.png)

Notice in the code snippet that the `value` assigned to the `<input>` shows up as text on the submit button. If there isn't a `value` attribute, the default text, `Submit` shows up on the button.

Let's now add this element to make our `<form>`s complete!

# Instructions

1. At the bottom of the `<form>` inside the element `<section class="submission">`, add a submit button using the `<input>` element.
The text inside the submit button should read: `Submit`.