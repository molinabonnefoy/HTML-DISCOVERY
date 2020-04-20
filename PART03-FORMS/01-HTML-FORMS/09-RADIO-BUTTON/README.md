Radio Button Input
==================

Checkboxes work well if we want to present users with multiple options and let them choose one or more of the options. However, there are cases where we want to present multiple options and only allow for one selection --- like asking users if they agree or disagree with the terms and conditions. Let's look over the code used to create radio buttons:
````html
<form>
  <p>What is sum of 1 + 1?</p>
  <input type="radio" id="two" name="answer" value="2">
  <label for="two">2</label>
  <br>
  <input type="radio" id="eleven" name="answer" value="11">
  <label for="eleven">11</label>
</form>

````

Which renders:

![rendered form containing radio buttons](https://s3.amazonaws.com/codecademy-content/courses/learn-html-forms/radioInput+-+labeled.png)

Notice from the code snippet, radio buttons (like checkboxes) do not display their value. We have an associated `<label>` to represent the value of the radio button. To group radio buttons together, we assign them the same `name` and only one radio button from that group can be selected.

Let's see this in action by creating our own radio buttons.

# Instructions

1. We can give our users the option to make the burger into a cheeseburger. Let's use radio buttons for that.
In `<section>` element with a `class` of `"cheesy"` there are two `<label>`s that don't have associated `<input>` elements. Add an `<input>` element associated with the first `<label>`.
The created `<input>` should have:
    -   an `id` set to `"yes"`.
    -   a `type` set to `"radio"`
    -   a `name` attribute with a value of `"cheese"`.
    -   a `value` of `"yes"`.

2. Awesome, now add another `<input>` element to give users another choice. The created `<input>` should have:
    -   an `id` set to `"no"`.
    -   a `type` set to `"radio"`
    -   a `name` attribute with a value of `"cheese"`.
    -   a `value` of `"no"`.