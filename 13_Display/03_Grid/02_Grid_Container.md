## Grid Container

To make an HTML element behave as a grid container, you have to set the `display` property to `grid` or `inline-grid`.

Grid containers consist of grid items, placed inside columns and rows.

___

## The grid-template-columns Property

The `grid-template-columns` property defines the number of columns in your grid layout, and it can define the width of each column.

The value is a space-separated-list, where each value defines the width of the respective column.

If you want your grid layout to contain 4 columns, specify the width of the 4 columns, or "auto" if all columns should have the same width.

### Example

Make a grid with 4 columns:
```css
.grid-container {
  display: grid;
  grid-template-columns: auto auto auto auto;
}
```

**Note:** If you have more than 4 items in a 4 columns grid, the grid will automatically add a new row to put the items in.

The `grid-template-columns` property can also be used to specify the size (width) of the columns.

### Example

Set a size for the 4 columns:
```css
.grid-container {
  display: grid;
  grid-template-columns: 80px 200px auto 40px;
}
```

## The grid-template-rows Property

The `grid-template-rows` property defines the height of each row.

The value is a space-separated-list, where each value defines the height of the respective row:

### Example
```css
.grid-container {
  display: grid;
  grid-template-rows: 80px 200px;
}
```

## The justify-content Property

The `justify-content` property is used to align the whole grid inside the container.

**Note:** The grid's total width has to be less than the container's width for the `justify-content` property to have any effect.

### Example

```css
.grid-container {
  display: grid;
  justify-content: space-evenly;
}
```

### Example
```css
.grid-container {
  display: grid;
  justify-content: space-around;
}
```

### Example
```css
.grid-container {
  display: grid;
  justify-content: space-between;
}
```

### Example
```css
.grid-container {  
    display: grid;  
    justify-content: center;
}
```

### Example
```css
.grid-container {
    display: grid;  
    justify-content: start;
}
```
### Example
```css
.grid-container {
    display: grid;  
    justify-content: end;
}
```

## The align-content Property

The `align-content` property is used to _vertically_ align the whole grid inside the container.

**Note:** The grid's total height has to be less than the container's height for the `align-content` property to have any effect.

### Example
```css
.grid-container {
    height: 400px;  
    display: grid;  
    align-content: center;
}
```

### Example
```css
.grid-container {
    display: grid;  
    height: 400px;  
    align-content: space-evenly;
}
```

### Example
```css
.grid-container {
    display: grid;  
    height: 400px;  
    align-content: space-around;
}
```

### Example
```css
.grid-container {
    display: grid;  
    height: 400px;  
    align-content: space-between;
}
```

### Example
```css
.grid-container {
    display: grid;  
    height: 400px;  
    align-content: start;
}
```

### Example
```css
.grid-container {
    display: grid;  
    height: 400px;  
    align-content: end;
}
```