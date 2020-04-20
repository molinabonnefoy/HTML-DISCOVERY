Datalist Input
==============

Even if we have an organized dropdown list, if the list has a lot of options, it could be tedious for users to scroll through the entire list to locate one option. That's where using the `<datalist>` element comes in handy.

The `<datalist>` is used with an `<input type="text">` element. The `<input>` creates a text field that users can type into and filter options from the `<datalist>`. Let's go over a concrete example:
````html
<form>
  <label for="city">Ideal city to visit?</label>
  <input type="text" list="cities" id="city" name="city">

  <datalist id="cities">
    <option value="New York City"></option>
    <option value="Tokyo"></option>
    <option value="Barcelona"></option>
    <option value="Mexico City"></option>
    <option value="Melbourne"></option>
    <option value="Other"></option>
  </datalist>
</form>
````

Notice, in the code above, we have an `<input>` that has a `list` attribute. The `<input>` is associated to the `<datalist>` via the `<input>`'s `list` attribute and the `id` of the `<datalist>`.

From the code provided, the following form is rendered:![input field with a label 'Ideal city to visit?'](https://s3.amazonaws.com/codecademy-content/courses/learn-html-forms/datalist+-+concealed.png)

And when field is selected:![clicking on the input field reveals a dropdown
list](https://s3.amazonaws.com/codecademy-content/courses/learn-html-forms/datalist+-+revealed.png)

While `<select>` and `<datalist>` share some similarities, there are some major differences. In the associated `<input>` element, users can type in the input field to search for a particular option. If none of the `<option>`s match, the user can still use what they typed in. When the form is submitted, the value of the `<input>`'s `name` and the `value` of the option selected, or what the user typed in, is sent as a pair.

Now it's time to make a `<datalist>` of our own!

Instructions

1. Time to add some sauce! Users might get creative with what sauce they choose to put, so let's use the `<datalist>` element.
In `<section>` element with a `class` of `"sauce-selection"`, we already have the `<label>` and `<input>` set up. Add a `<datalist>` element with an `id` of `"sauces"`.

2. Inside the `<datalist>` element, add 3 `<option>`s.
    -   The first `<option>` should have a value of `"ketchup"`.
    -   The second `<option>` should have a value of `"mayo"`.
    -   The third `<option>` can be a value that you choose and display text relevant to the value (make sure it's not empty!)