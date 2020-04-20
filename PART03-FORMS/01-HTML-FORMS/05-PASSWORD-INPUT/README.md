Password Input
==============

Think about all those times we have to put sensitive information, like a password or PIN, into a `<form>`. We wouldn't want our information to be seen by anyone peeking over our shoulder! Luckily, we have the `type="password"` attribute for `<input>`!

An `<input type ="password">` element will replace input text with another character like an asterisk (*) or a dot (-). The code below provides an example of how to create a password field:
````html
<form>
  <label for="user-password">Password: </label>
  <input type="password" id="user-password" name="user-password">
</form>

````
After a user types into the field, it would look like:

![password field in a form with 6 dots showing text added to the field](https://s3.amazonaws.com/codecademy-content/courses/learn-html-forms/pwInput+-+labeled+filled.png)

Even though the password field obscures the text of the password, when the form is submitted, the value of the text is sent. In other words, if "hunter2" is typed into the password field, "user-password=hunter2" is sent along with the other information on the form.

# Instructions

1. To complete our login page in index.html we need a password field. Add an `<input>` element under the second `<label>` element.    
    -   Assign the `id` to the correct value to associate the second `<label>` with this new `<input>`.
    -   Set the newly created `<input>` element's `type` attribute to `"password"`.
    -   Set the `name` attribute to `"user-pw"`.