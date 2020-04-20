Number Input
============

We've now gone over two `type` attributes for `<input>` related to text. But, we might want our users to type in a number --- in which case we can set the `type` attribute to... (you guessed it)... `"number"`!

By setting `type="number"` for an `<input>` we can restrict what users type into the input field to just numbers (and a few special characters like `-`, `+`, and `.`). We can also provide a `step` attribute which creates arrows inside the input field to increase or decrease by the value of the `step` attribute. Below is the code needed to render an input field for numbers:
````html
<form>
  <label for="years"> Years of experience: </label>
  <input id="years" name="years" type="number" step="1">
</form>

````

Which renders:

![rendered number input field with arrows to the right hand side of the field](https://s3.amazonaws.com/codecademy-content/courses/learn-html-forms/numInput+-+labeled+blank+steps.png)

Now it's time to apply this knowledge.

# Instructions

1. In index.html we started a `<form>` for users to make a custom burger. Right now we have a `<label>` for patties that needs an associated `<input>` element.
Since we want users to enter a number, create an `<input>` and set the attributes:

    -   Associate the `<input>` to the first `<label>` by assigning the correct value to `id`.
    -   `type="number"`
    -   `step="1"`
    -   `name` to `"amount"`.