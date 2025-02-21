# HTML Tables
Tables display data in grid or tabular format.

Content is organized into rows and columns. 

## Basic Structure of HTML Table

- `<table></table>` - main container of the table.

- `<tr></tr>` - (table row) - defines the rows of a table. 

- `<th></th>`- (table header), defines a header cell, typically displayed as bold and centered by default.

- `<td></td>` - (table data), defines a standard cell in the table.

```html
<table>
    <tr>
        <th>Name</th>
        <th>Age</th>
        <th>City</th>
    </tr>
    <tr>
        <td>Alice</td>
        <td>30</td>
        <td>Nairobi</td>
    </tr>
    <tr>
        <td>Jack</td>
        <td>25</td>
        <td>Mombasa</td>
    </tr>
    <tr>
        <td>Elvis</td>
        <td>55</td>
        <td>Nyeri</td>
    </tr>
</table>
```

<table>
    <tr>
        <th>Name</th>
        <th>Age</th>
        <th>City</th>
    </tr>
    <tr>
        <td>Alice</td>
        <td>30</td>
        <td>Nairobi</td>
    </tr>
    <tr>
        <td>Jack</td>
        <td>25</td>
        <td>Mombasa</td>
    </tr>
    <tr>
        <td>Elvis</td>
        <td>55</td>
        <td>Nyeri</td>
    </tr>
</table>


## Table Attributes and Other Features

1. `border` attribute adds a boarder around the  cells.

```html
<table border="1">
    <tr>
        <th>Name</th>
        <th>Age</th>
        <th>City</th>
    </tr>
    <tr>
        <td>Alice</td>
        <td>30</td>
        <td>Nairobi</td>
    </tr>
    <tr>
        <td>Jack</td>
        <td>25</td>
        <td>Mombasa</td>
    </tr>
</table>
```
<table border="1">
    <tr>
        <th>Name</th>
        <th>Age</th>
        <th>City</th>
    </tr>
    <tr>
        <td>Alice</td>
        <td>30</td>
        <td>Nairobi</td>
    </tr>
    <tr>
        <td>Jack</td>
        <td>25</td>
        <td>Mombasa</td>
    </tr>
</table>

2. `rowspan` and `colspan` allows cells to span multiple rows or columns. 

```html
<table border="1">
    <tr>
        <th>Name</th>
        <th colspan="2">Details</th>
    </tr>
    <tr>
        <td>Alice</td>
        <td>30</td>
        <td>Nairobi</td>
    </tr>
</table>
```

<table border="1">
    <tr>
        <th>Name</th>
        <th colspan="2">Details</th>
    </tr>
    <tr>
        <td>Alice</td>
        <td>30</td>
        <td>Nairobi</td>
    </tr>
</table>

## Organizing Table Content

1. `<thead></thead>` - wraps the table header.
2. `<tbody></tbody>` - wraps the body of the table.
3. `<tfoot></tfoot>` - wraps the footer of the table.

```html
<table border="1">
    <thead>
        <tr>
            <th>Name</th>
            <th>Age</th>
            <th>City</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Alice</td>
            <td>30</td>
            <td>Nairobi</td>
        </tr>
        <tr>
            <td>Jack</td>
            <td>25</td>
            <td>Mombasa</td>
        </tr>
    </tbody>
    <tfoot>
        <tr>
            <td colspan="3">End of data</td>
        </tr>
    </tfoot>
</table>
```

<table border="1">
    <thead>
        <tr>
            <th>Name</th>
            <th>Age</th>
            <th>City</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Alice</td>
            <td>30</td>
            <td>Nairobi</td>
        </tr>
        <tr>
            <td>Jack</td>
            <td>25</td>
            <td>Mombasa</td>
        </tr>
    </tbody>
    <tfoot>
        <tr>
            <td colspan="3">End of data</td>
        </tr>
    </tfoot>
</table>



