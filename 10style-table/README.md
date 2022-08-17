![phillip zastrow logo](https://pbs.twimg.com/profile_images/1452633114044403715/d3liT5vd_400x400.jpg)

# [_Tutorial 10_](https://www.digitalocean.com/community/tutorials/how-to-style-a-table-with-css)

## How To Style a Table with CSS

## What I learned and how it applies in my Github page example:

- The _<table>_ element defines the tabular content area.

- If you add a _<caption>_ element within the <table> element, it indicates the table’s purpose in an accessible way.

- _<thead>_ indicates the table header and <tbody> indicates the table body (the area where table content will go). You can use <tfoot> for summary information (totals, etc.).

- Table rows are defined by the _<tr>_ element and individual data points are indicated by _<td>_ elements.

- The _<th>_ element indicates a heading for a row or column.

- The _border_ and _border-collapse_ properties can be used to create. boundary lines between cells using <th> and <td> element selectors.

- For border you can specify size, style, and color such as border: 1px solid black.

- The border-collapse property defaults to “separate” but you can change it to “collapse” and it removes spacing between table cells so borders overlap and straight lines are created.

- You can set the _table size_ by adjusting _column-width and padding_ properties on specific selectors. Set column width by adjusting the width and padding values of the thead and th selectors (use a combination selector and you can do both at the same time).

- To give the cell contents more space, adjust the padding of the th and td selectors.

- To _target a specific cell_, give it a class name in the HTML and apply styles to it (example “highlight-cell”).

- You can set the _font-family_ for the entire table in the body element.

- _Aligning the table_ to center is possible by setting text-align: center and vertical-align: middle on the table element.

- The _table caption and header (thead) elements_ can take styles similarly to a regular header to make them stand out on the table.

- To make your table rows and left header rows stand out, you can use nth:child() pseudo-class. This allows you to alternate colors on odd and even rows to help the eye better follow the flow of information.
