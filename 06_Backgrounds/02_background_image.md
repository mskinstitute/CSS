## CSS background-image

The `background-image` property specifies an image to use as the background of an element.

By default, the image is repeated so it covers the entire element.

### Example

Set the background image for a page: 
```css
body {
    background-image: url("paper.gif");
}
```

### Example

This example shows a **bad combination** of text and background image. The text is hardly readable: 
```css
body {
    background-image: url("bgdesert.jpg");
}
```

> **Note:** When using a background image, use an image that does not disturb the text.

The background image can also be set for specific elements, like the `<p>` element:

### Example
```css
p {
    background-image: url("paper.gif");
}
```

## The CSS Background Image Property

| Property | Description |
| --- | --- |
| [background-image]() | Sets the background image for an element |

# [<<< Previous](01_Backgrounds.md) :: [Next >>>](03_background-repeat.md)