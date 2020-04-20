Checkbox Input
==============

So far the types of inputs we've allowed were all single choices. But, what if we presented multiple options to users and allow them to select any number of options? Sounds like we could use checkboxes! In a `<form>` we would use the `<input>` element and set `type="checkbox"`. Examine the code used to create multiple checkboxes:
````html
<form>
  <p>Choose your pizza toppings:</p>
  <label for="cheese">Extra cheese</label>
  <input id="cheese" name="topping" type="checkbox" value="cheese">
  <br>
  <label for="pepperoni">Pepperoni</label>
  <input id="pepperoni" name="topping" type="checkbox" value="pepperoni">
  <br>
  <label for="anchovy">Anchovy</label>
  <input id="anchovy" name="topping" type="checkbox" value="anchovy">
</form>
````

Which renders:![HTML form asking user to select pizza toppings and three topping selections as checkboxes](https://s3.amazonaws.com/codecademy-content/courses/learn-html-forms/checkboxInput+-+labeled.png)

Notice in the example provided:

-   there are assigned values to the `value` attribute of the checkboxes. These values are not visible on the form itself, that's why it is important that we use an associated `<label>` to identify the checkbox.
-   each `<input>` has the same value for the `name` attribute. Using the same `name` for each checkbox groups the `<input>`s together. However, each `<input>` has a unique `id` to pair with a `<label>`.

Alright, time to use checkboxes in our code!

Instructions

1. Time to add some toppings! In the `<section>` with `class="toppings"`, there are two `<label>`s but no associated `<input>` elements. Add an `<input>` element associated with the first `<label>`.
The created `<input>` should have:
    -   an `id` set to `"lettuce"`.
    -   a `name` attribute with a value of `"topping"`.
    -   a `type` set to `"checkbox"`
    -   a `value` of `"lettuce"`.

2. Add another `<input>` element and associate it with the second `<label>`.
The `<input>` element should have:
    -   an `id` set to `"tomato"`.
    -   a `type` set to `"checkbox"`.
    -   a `name` attribute with a value of `"topping"`.
    -   a `value` of `"tomato"`.

3. Two choices are good, but it would be better to have even more.
Add another `<input type="checkbox">` and `<label>` pair. Assign the `name` of the `<input>` to `"topping"`. You're free to decide the `value` and `id` but make sure that your new `<label>` and `<input>` are associated.