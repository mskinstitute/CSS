## CSS background - Shorthand property

To shorten the code, it is also possible to specify all the background properties in one single property. This is called a shorthand property.

Instead of writing:
```css
body {
    background-color: #ffffff;  
    background-image: url("img_tree.png");  
    background-repeat: no-repeat;  
    background-position: right top;
}
```
You can use the shorthand property `background`:

### Example

Use the shorthand property to set the background properties in one declaration:
```css
body {background: #ffffff url("img\_tree.png") no-repeat right top;}
```

When using the shorthand property the order of the property values is:

-   `background-color`
-   `background-image`
-   `background-repeat`
-   `background-attachment`
-   `background-position`

It does not matter if one of the property values is missing, as long as the other ones are in this order. Note that we do not use the background-attachment property in the examples above, as it does not have a value.

## Test Yourself With Exercises

## Exercise:

Set the background color of the `<h1>` element to "lightblue".

```html
<style>
h1 {
  _________: lightblue;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>
```

## All CSS Background Properties

| Property | Description |
| --- | --- |
| [background]() | Sets all the background properties in one declaration |
| [background-attachment]() | Sets whether a background image is fixed or scrolls with the rest of the page |
| [background-clip]() | Specifies the painting area of the background |
| [background-color]() | Sets the background color of an element |
| [background-image]() | Sets the background image for an element |
| [background-origin]() | Specifies where the background image(s) is/are positioned |
| [background-position]() | Sets the starting position of a background image |
| [background-repeat]() | Sets how a background image will be repeated |
| [background-size]() | Specifies the size of the background image(s) |

# [<<< Previous](04_background-attachment.md) :: [Next >>>](../07_Box_Modal/01_box_modal.md)