Spanning Columns
================

What if the table contains data that spans multiple columns?

For example, a personal calendar could have events that span across multiple hours, or even multiple days.

Data can span columns using the `colspan` attribute. The attributes accepts an integer (greater than or equal to 1) to denote the number of columns it spans across.
````html
<table>
  <tr>
    <th>Monday</th>
    <th>Tuesday</th>
    <th>Wednesday</th>
  </tr>
  <tr>
    <td colspan="2">Out of Town</td>
    <td>Back in Town</td>
  </tr>
</table>

````

In the example above, the data `Out of Town` spans the `Monday` and `Tuesday` table headings using the value `2` (two columns). The data `Back in Town` appear only under the `Wednesday` heading.

# Instructions

1. In index.html, span a `<td>` element across two columns.