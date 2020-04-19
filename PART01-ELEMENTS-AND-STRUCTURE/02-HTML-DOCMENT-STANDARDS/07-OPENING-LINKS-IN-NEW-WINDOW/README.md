Opening Links in a New Window
=============================

Have you ever clicked on a link and observed the resulting web page open in a new browser window? If so, you can thank the `<a>` element's `target` attribute.

The `target` attribute specifies how a link should open.

It's possible that one or more links on your web page link to an entirely different website. In that case, you may want users to read the linked website, but hope that they return to your web page. This is exactly when the `target` attribute is useful!

For a link to open in a new window, the `target` attribute requires a value of `_blank`. The `target` attribute can be added directly to the opening tag of the anchor element, just like the `href` attribute.
````html
<a href="https://en.wikipedia.org/wiki/Brown_bear" target="_blank">The Brown Bear</a>
````

In the example above, setting the `target` attribute to `"_blank"` instructs the browser to open the relevant Wikipedia page in a new window.

In this exercise, we've used the terminology "open in a new window." It's likely that you are using a modern browser that opens up websites in new *tabs*, rather than new windows. Before the advent of browsers with tabs, additional browser windows had to be opened to view more websites. The `target="_blank"` attribute, when used in modern browsers, will open new websites in a new tab.

# Instructions

1. In the link that reads `Learn More`, add the `target` attribute and set it equal to `_blank`.