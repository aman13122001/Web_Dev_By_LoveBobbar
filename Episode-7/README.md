```
Qun.What is Table in html?
Ans: HTML table tag is used to display data in tabular form (row * column). There can be many columns in a row.

We can create a table to display data in tabular form, using <table> element, with the help of <tr> , <td>, and <th> elements.

In Each table, table row is defined by <tr> tag, table header is defined by <th>, and table data is defined by <td> tags.

** Basic Table Structure **

<table>

<thead>

<th>  </th>
<th>  </th>

</thead>

<tbody>

<tr>
      <td>  </td>
</tr>

<tr>
      <td>  </td>
</tr>>

</tbody>

<tfooter>

<tr>
      <td>  </td>
</tr>

<tr>
      <td>  </td>
</tr>

</tfooter>
</table>


** Use of Tag **
<table>:- It defines a table.

<thead>:- It is used to group the header content in a table.

<th>:- It defines a header cell in a table.

<tbody>:- It is used to group the body content in a table.

<tr>:- It defines a row in a table.

<td>:- It defines a cell in a table.

<tfooter>:- It is used to group the footer content in a table.


 ** Use of rowspam and colspam in table **

 -> the rowspan attribute specifies how many rows a table cell should span, determining its vertical position. On the other hand, the colspan attribute specifies the number of columns a cell should span, determining its horizontal position.

rowspan attribute :- HTML Table with Colspan allows you to merge or combine adjacent table cells horizontally, creating a single, wider cell that spans across multiple columns.

syntex:-
<tr>
    <th colspan="2">Name</th>
    <th>Class</th>
</tr>

colspam attribute :- The HTML attribute rowspan determines how many rows a specific cell in a table should cover. When a cell spans multiple rows, it occupies the space of those rows within the table.

syntex:-

<tr>
    <th>Name</th>
    <th>Class</th>
    <th rowspan="3">MVM School</th>
</tr>
 

 Some of  table in index.html file.