Table Headings
==============

Table data doesn't make much sense without titles to describe what the data represents.

To add titles to rows and columns, you can use the *table heading* element: `<th>`.

The table heading element is used just like a table data element, except with a relevant title. Just like table data, a table heading must be placed within a table row.
````html
<table>
  <tr>
    <th></th>
    <th scope="col">Saturday</th>
    <th scope="col">Sunday</th>
  </tr>
  <tr>
    <th scope="row">Temperature</th>
    <td>73</td>
    <td>81</td>
  </tr>
</table>
````

What happened in the code above?

First, a new row was added to hold the three headings: a blank heading, a `Saturday` heading, and a `Sunday` heading. The blank heading creates the extra table cell necessary to align the table headings correctly over the data they correspond to.

In the second row, one table heading was added as a row title: `Temperature`.

Note, also, the use of the `scope` attribute, which can take one of two values:

1.  `row` - this value makes it clear that the heading is for a row.
2.  `col` - this value makes it clear that the heading is for a column.

HTML code for tables may look a little strange at first, but analyzing it piece by piece helps make the code more understandable.

# Instructions

1. In the first row, add three table headings. The headings should contain the following data, in order:
-   Company Name
-   Number of Items to Ship
-   Next Action

These headings will add meaning to the rest of the data in the table.