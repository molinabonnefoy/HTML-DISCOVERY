Spanning Rows
=============

Data can also span multiple rows using the `rowspan` attribute.

The `rowspan` attribute is used for data that spans multiple rows (perhaps an event goes on for multiple hours on a certain day). It accepts an integer (greater than or equal to 1) to denote the number of rows it spans across.
````html
<table>
  <tr> <!-- Row 1 -->
    <th></th>
    <th>Saturday</th>
    <th>Sunday</th>
  </tr>
  <tr> <!-- Row 2 -->
    <th>Morning</th>
    <td rowspan="2">Work</td>
    <td rowspan="3">Relax</td>
  </tr>
  <tr> <!-- Row 3 -->
    <th>Afternoon</th>
  </tr>
  <tr> <!-- Row 4 -->
    <th>Evening</th>
    <td>Dinner</td>
  </tr>
</table>
````

In the example above, there are four rows:

1.  The first row contains an empty cell and the two column headings.
2.  The second row contains the `Morning` row heading, along with `Work`, which spans two rows under the `Saturday` column. The "Relax" entry spans three rows under the `Sunday` column.
3.  The third row only contains the `Afternoon` row heading.
4.  The fourth row only contains the `Dinner` entry, since "Relax" spans into the cell next to it.

If you'd like to see how the browser interprets the code above, feel free to copy and paste it into the code editor to understand it a little better.

Instructions

1. In index.html, span a `<td>` element across two rows.