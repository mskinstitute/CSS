# CSS Height, Width and Max-width

The CSS `height` and `width` properties are used to set the height and width of an element.

The CSS `max-width` property is used to set the maximum width of an element.

___

This element has a height of 50 pixels and a width of 100%.

## CSS Setting height and width

The `height` and `width` properties are used to set the height and width of an element.

The height and width properties do not include padding, borders, or margins. It sets the height/width of the area inside the padding, border, and margin of the element.

___

## CSS height and width Values

The `height` and `width` properties may have the following values:

-   `auto` - This is default. The browser calculates the height and width
-   `length` - Defines the height/width in px, cm, etc.
-   `%` - Defines the height/width in percent of the containing block
-   `initial` - Sets the height/width to its default value
-   `inherit` - The height/width will be inherited from its parent value

___

## CSS height and width Examples

### Example

Set the height and width of a `<div>` element:
```css
div {
    height: 200px;  
    width: 50%;  
    background-color: powderblue;
}
```

This element has a height of 100 pixels and a width of 500 pixels.

### Example

Set the height and width of another `<div>` element:
```css
div {
    height: 100px;  
    width: 500px;  
    background-color: powderblue;
}
```

**Note:** Remember that the `height` and `width` properties do not include padding, borders, or margins! They set the height/width of the area inside the padding, border, and margin of the element!

___

## Setting max-width

The `max-width` property is used to set the maximum width of an element.

The `max-width` can be specified in _length values_, like px, cm, etc., or in percent (%) of the containing block, or set to none (this is default. Means that there is no maximum width).

The problem with the `<div>` above occurs when the browser window is smaller than the width of the element (500px). The browser then adds a horizontal scrollbar to the page.

Using `max-width` instead, in this situation, will improve the browser's handling of small windows.

**Tip:** Drag the browser window to smaller than 500px wide, to see the difference between the two divs!

This element has a height of 100 pixels and a max-width of 500 pixels.

**Note:** If you for some reason use both the `width` property and the `max-width` property on the same element, and the value of the `width` property is larger than the `max-width` property; the `max-width` property will be used (and the `width` property will be ignored).

### Example

This `<div>` element has a height of 100 pixels and a max-width of 500 pixels: 
```css
div {
    max-width: 500px;  
    height: 100px;  
    background-color: powderblue;
}
```

## Try it Yourself - Examples

[Set the height and width of elements]()  
This example demonstrates how to set the height and width of different elements.

[Set the height and width of an image using percent]()  
This example demonstrates how to set the height and width of an image using a percent value.

[Set min-width and max-width of an element]()  
This example demonstrates how to set a minimum width and a maximum width of an element using a pixel value.

[Set min-height and max-height of an element]()  
This example demonstrates how to set a minimum height and a maximum height of an element using a pixel value.

## All CSS Dimension Properties

| Property | Description |
| --- | --- |
| [height](https://www.w3schools.com/cssref/pr_dim_height.asp) | Sets the height of an element |
| [max-height](https://www.w3schools.com/cssref/pr_dim_max-height.asp) | Sets the maximum height of an element |
| [max-width](https://www.w3schools.com/cssref/pr_dim_max-width.asp) | Sets the maximum width of an element |
| [min-height](https://www.w3schools.com/cssref/pr_dim_min-height.asp) | Sets the minimum height of an element |
| [min-width](https://www.w3schools.com/cssref/pr_dim_min-width.asp) | Sets the minimum width of an element |
| [width](https://www.w3schools.com/cssref/pr_dim_width.asp) | Sets the width of an element |