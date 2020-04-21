Header and Nav
==============

Let's take a look at some semantic elements that assist in the structure of a web page. A `<header>` is a container usually for either navigational links or introductory content containing `<h1>` to `<h6>` headings.

The example below shows `<header>` in action:
````html
<header>
  <h1>
     Everything you need to know about pizza!
  </h1>
</header>
````

This can be compared to the code below which uses a `<div>` tag instead of a `<header>` tag:
````html
<div id="header">
  <h1>
    Everything you need to know about pizza!
  </h1>
</div>
````
By using a `<header>` tag, our code becomes easier to read. It is much easier to identify what is inside of the `<h1>`'s parent tags, as opposed to a `<div>` tag which would provide no details as to what was inside of the tag.

A `<nav>` is used to define a block of navigation links such as menus and tables of contents. It is important to note that `<nav>` can be used inside of the `<header>` element but can also be used on its own.

Let's take a look at the example below:
````html
<header>
  <nav>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
    </ul>
  </nav>
</header>
````
By using `<nav>` as a way to label our navigation links, it will be easier for not only us, but also for web browsers and screen readers to read the code.

Now that we've learned about the `<header>` and `<nav>` elements let's add them into our code!

Instructions

1. In the code editor, find the `<div id="header">` tag and change it to `<header>`.
    -   Note: When changing an opening tag, you must find the corresponding closing tag and change that as well. If you don't, you'll see some red in your code to indicate the error.

2. Now, find the `<div id="nav">` tag and change it to `<nav>`.