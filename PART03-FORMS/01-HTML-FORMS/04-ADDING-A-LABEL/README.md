Adding a Label
==============

In the previous exercise we created an `<input>` element but we didn't include anything to explain what the `<input>` is used for. For a user to properly identify an `<input>` we use the appropriately named `<label>` element.

The `<label>` element has an opening and closing tag and displays text that is written between the opening and closing tags. To associate a `<label>` and an `<input>`, the `<input>` needs an `id` attribute. We then assign the `for` attribute of the `<label>` element with the value of the `id` attribute of `<input>`, like so:
````html
<form action="/example.html" method="POST">

  <label for="meal">What do you want to eat?</label>

  <br>

  <input type="text" name="food" id="meal">

</form>

````

The code above renders:

![rendered form with labeled text field](https://s3.amazonaws.com/codecademy-content/courses/learn-html-forms/label+-+text+input.png)

Look, now users know what the `<input>` element is for! Another benefit for using the `<label>` element is when this element is clicked, the corresponding `<input>` is highlighted/selected.

Let's see the `<label>` element in action!

# Instructions

1. Add a `<label>` element that is associated with the included `<input>` element in index.html. (use the `for` attribute!).Then add text `Username` within the `<label>` element.

After clearing this checkpoint, click on the label to see the `<input>` field in focus!