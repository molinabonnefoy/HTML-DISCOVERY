Range Input
===========

Using an `<input type="number">` is great if we want to allow users to type in any number of their choosing. But, if we wanted to limit what numbers our users could type we might consider using a different `type` value. Another option we could use is setting `type` to `"range"` which creates a slider.

To set the minimum and maximum values of the slider we assign values to the `min` and `max` attribute of the `<input>`. We could also control how smooth and fluid the slider works by assigning the `step` attribute a value. Smaller `step` values will make the slider more fluidly, whereas larger `step` values will make the slider move more noticeably. Take a look at the code to create a slider:
````html
<form>
  <label for="volume"> Volume Control</label>
  <input id="volume" name="volume" type="range" min="0" max="100" step="1">
</form>

````

The code above renders:![rendered slider for volume control](https://s3.amazonaws.com/codecademy-content/courses/learn-html-forms/rangeInput+-+labeled.png)

In the example above, every time the slider moves by one, the value of the `<input>`'s `value` attribute changes.

# Instructions

1. Let's give our users an option for how they want to cook their patties. We can do this by adding a slider to the existing `<form>`.
    - In the `<section>` with `class="cooked"`, add an `<input>` element. Set the `id` and `name` to `"doneness"`. Also, set the `type` attribute to `"range"`.
    - Since our `<form>` is getting long, you might have to scroll down to find the provided `<section>`.

2. For the newly created `<input>` set the:
    -   `min` attribute to `"0"`.
    -   `max` attribute to `"5"`.
    -   `step` attribute to `"0.5"`.