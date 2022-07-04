# Links, tables and forms

## `<a>` tag

The `<a>` tag defines a hyperlink, which is used to link from one page to another.

The most important attribute of the `<a>` element is the href attribute, which indicates the link's destination.

By default, links will appear as follows in all browsers:

* An unvisited link is underlined and blue;
* A visited link is underlined and purple;
* An active link is underlined and red.

### Example

```html
<a href="https://oliota.com">
<img border="0" alt="Oliota" width="100" height="100">
</a>
```

<br>

## `<table>` tag
The `<table>` tag defines an HTML table.

An HTML table consists of one `<table>` element and one or more `<tr>`, `<th>`, and `<td>` elements.

The `<tr>` element defines a table row, the `<th>` element defines a table header, and the `<td>` element defines a table cell.

An HTML table may also include `<caption>`, `<colgroup>`, `<thead>`, `<tfoot>`, and `<tbody>` elements.

### Example

```html
<head>
<style>
table, th, td {
  border: 1px solid black;
  border-collapse: collapse;
}
</style>
</head>
<body>

<table>
  <tr>
    <th>Month</th>
    <th>Savings</th>
  </tr>
  <tr>
    <td>January</td>
    <td>$100</td>
  </tr>
  <tr>
    <td>February</td>
    <td>$80</td>
  </tr>
</table>

</body>
</html>
```

Output:

<head>
<style>
table, th, td {
  border: 1px solid black;
  border-collapse: collapse;
}
</style>
</head>
<body>

<table>
  <tr>
    <th>Month</th>
    <th>Savings</th>
  </tr>
  <tr>
    <td>January</td>
    <td>$100</td>
  </tr>
  <tr>
    <td>February</td>
    <td>$80</td>
  </tr>
</table>

</body>
</html>

<br>

## `<thead>` , `<tbody>` and `<tfoot>` tag

* The `<thead>` tag is used to group header content in an HTML table.

* The `<tbody>` tag is used to group the body content in an HTML table.

* The `<tfoot>` tag is used to group footer content in an HTML table.



## Forms





