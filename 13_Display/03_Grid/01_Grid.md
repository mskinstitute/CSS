# Grid Layout
The CSS Grid Layout Module offers a grid-based layout system, with rows and columns, making it easier to design web pages without having to use floats and positioning.

## Grid Elements
A grid layout consists of a parent element, with one or more child elements.

## Display Property

An HTML element becomes a grid container when its `display` property is set to `grid` or `inline-grid`.

### Grid Columns
The vertical lines of grid items are called columns.

![alt text](../assets/img/grid_columns.png)

### Grid Rows
The horizontal lines of grid items are called rows.

![alt text](../assets/img/grid_rows.png)

### Grid Gaps
The spaces between each column/row are called gaps.

![alt text](../assets/img/grid_gaps.png)

You can adjust the gap size by using one of the following properties:

## Grid Lines

The lines between columns are called _column lines_.

The lines between rows are called _row lines_.

![alt text](../assets/img/grid_lines.png)


Refer to line numbers when placing a grid item in a grid container:


## All CSS Grid Properties

| Property | Description |
| --- | --- |
| [column-gap]() | Specifies the gap between the columns |
| [gap]() | A shorthand property for the _row-gap_ and the _column-gap_ properties |
| [grid]() | A shorthand property for the _grid-template-rows, grid-template-columns, grid-template-areas, grid-auto-rows, grid-auto-columns_, and the _grid-auto-flow_ properties |
| [grid-area]() | Either specifies a name for the grid item, or this property is a shorthand property for the _grid-row-start_, _grid-column-start_, _grid-row-end_, and _grid-column-end_ properties |
| [grid-auto-columns]() | Specifies a default column size |
| [grid-auto-flow]() | Specifies how auto-placed items are inserted in the grid |
| [grid-auto-rows]() | Specifies a default row size |
| [grid-column]() | A shorthand property for the _grid-column-start_ and the _grid-column-end_ properties |
| [grid-column-end]() | Specifies where to end the grid item |
| [grid-column-gap]() | Specifies the size of the gap between columns |
| [grid-column-start]() | Specifies where to start the grid item |
| [grid-gap]() | A shorthand property for the _grid-row-gap_ and _grid-column-gap_ properties |
| [grid-row]() | A shorthand property for the _grid-row-start_ and the _grid-row-end_ properties |
| [grid-row-end]() | Specifies where to end the grid item |
| [grid-row-gap]() | Specifies the size of the gap between rows |
| [grid-row-start]() | Specifies where to start the grid item |
| [grid-template]() | A shorthand property for the _grid-template-rows_, _grid-template-columns_ and _grid-areas_ properties |
| [grid-template-areas]() | Specifies how to display columns and rows, using named grid items |
| [grid-template-columns]() | Specifies the size of the columns, and how many columns in a grid layout |
| [grid-template-rows]() | Specifies the size of the rows in a grid layout |
| [row-gap]() | Specifies the gap between the grid rows |