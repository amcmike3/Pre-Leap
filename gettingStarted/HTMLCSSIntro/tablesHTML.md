# HTML Tables Tutorial

Tables are a fundamental part of web design and are used to organize and present data in a structured format. In HTML, you can create tables using the `<table>` element and its related elements to define rows and columns. This tutorial will guide you through creating and styling tables in HTML.

## 1. Basic Table Structure

To create a basic table, use the `<table>` element to define the table container, and within it, use the `<tr>` element to define table rows and the `<td>` element to define table data cells.

```html
<table>
  <tr>
    <td>Row 1, Cell 1</td>
    <td>Row 1, Cell 2</td>
  </tr>
  <tr>
    <td>Row 2, Cell 1</td>
    <td>Row 2, Cell 2</td>
  </tr>
</table>
```

## 2. Table Headings

To add table headings, use the `<th>` element within the `<tr>` element. Table headings are typically placed in the first row (header row) of the table.

```html
<table>
  <tr>
    <th>Header 1</th>
    <th>Header 2</th>
  </tr>
  <tr>
    <td>Data 1</td>
    <td>Data 2</td>
  </tr>
</table>
```

## 3. Table Rows and Cells

You can add as many rows and cells as needed to your table structure. Use the `<tr>` element for rows and the `<td>` element for data cells within those rows.

```html
<table>
  <tr>
    <td>Row 1, Cell 1</td>
    <td>Row 1, Cell 2</td>
  </tr>
  <tr>
    <td>Row 2, Cell 1</td>
    <td>Row 2, Cell 2</td>
  </tr>
  <!-- Add more rows and cells as needed -->
</table>
```

## 4. Spanning Rows and Columns

You can merge cells both vertically (rows) and horizontally (columns) using the `rowspan` and `colspan` attributes. This is useful for creating complex table layouts.

```html
<table>
  <tr>
    <td rowspan="2">Merged Cell</td>
    <td>Cell 1</td>
    <td>Cell 2</td>
  </tr>
  <tr>
    <td>Cell 3</td>
    <td>Cell 4</td>
  </tr>
</table>
```

## 5. Adding Captions

You can add a table caption using the `<caption>` element. The caption is typically placed above the table.

```html
<table>
  <caption>Sample Table</caption>
  <!-- Table row and cell content here -->
</table>
```

HTML tables are a powerful way to present data on web pages. Whether you're displaying tabular data, creating complex layouts, or designing pricing tables, understanding how to use tables effectively is essential for web development.
[prev](HTMLlab5.md) | [Up](README.md) | [Next](HTMLlab6.md)