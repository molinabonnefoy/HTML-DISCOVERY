Linking to Relative Page
========================

Thus far you have learned how to link to external web pages. Many sites also link to internal web pages like Home, About, and Contact.

Before we learn how to link between internal pages, let's establish where our files are stored. When making multi-page static websites, web developers often store HTML files in the *root directory*, or a main folder where all the files for the project are stored. As the size of the projects you create grows, you may use additional folders within the main project folder to organize your code.
````
project-folder/
|------ about.html
|------ contact.html
|------ index.html
````


The example above shows three different files --- about.html, contact.html, and index.html in one folder.

HTML files are often stored in the same folder, as shown in the example above. If the browser is currently displaying index.html, it also knows that about.html and contact.html are in the same folder. Because the files are stored in the same folder, we can link web pages together using a *relative path*.
````html
<a href="./contact.html">Contact</a>
````

In this example, the `<a>` tag is used with a relative path to link from the current HTML file to the `contact.html` file in the same folder. On the web page, `Contact` will appear as a link.

A relative path is a filename that shows the path to a *local file* (a file on the same website, such as `./index.html`) versus an absolute path (a full URL, like `https://www.codecademy.com/learn/learn-html` which is stored in a different folder). The `./` in `./index.html` tells the browser to look for the file in the current folder.

# Instructions

1.Directly below the opening `<body>` tag, add an anchor tag that links to index.html with a relative path. The link should say `Brown Bear`.

2. Under the link to index.html, add an anchor tag that links to aboutme.html using a relative path. The link should say `About Me`. Notice that there is also another file in the code editor, aboutme.html. Click the link to make sure it works!