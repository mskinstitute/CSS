# CSS Backgrounds

The CSS background properties are used to add background effects for elements.

In these chapters, you will learn about the following CSS background properties:

-   `background-color`
-   `background-image`
-   `background-repeat`
-   `background-attachment`
-   `background-position`
-   `background` (shorthand property)

## CSS background-color

The `background-color` property specifies the background color of an element.

### Example

The background color of a page is set like this:
```css
body {
    background-color: lightblue;
}
```

With CSS, a color is most often specified by:

-   a valid color name - like "red"
-   a HEX value - like "#ff0000"
-   an RGB value - like "rgb(255,0,0)"

Look at [CSS Color Values](/HTML_Course/09_Colors/01_colors.md) for a complete list of possible color values.

## Other Elements

You can set the background color for any HTML elements:

### Example

Here, the `<h1>`, `<p>`, and `<div>` elements will have different background colors: 
```css
h1 {
    background-color: green;
}
  
div {
    background-color: lightblue;
}
  
p {
    background-color: yellow;
}
```

## Opacity / Transparency

The `opacity` property specifies the opacity/transparency of an element. It can take a value from 0.0 - 1.0. The lower value, the more transparent:

opacity 1
opacity 0.6
opacity 0.3
opacity 0.1

### Example
```css
div {
    background-color: green;  
    opacity: 0.3;
}
```

**Note:** When using the `opacity` property to add transparency to the background of an element, all of its child elements inherit the same transparency. This can make the text inside a fully transparent element hard to read.

## Transparency using RGBA

If you do not want to apply opacity to child elements, like in our example above, use **RGBA** color values. The following example sets the opacity for the background color and not the text:

100% opacity
60% opacity
30% opacity
10% opacity

You learned from our [CSS Colors Chapter](), that you can use RGB as a color value. In addition to RGB, you can use an RGB color value with an **alpha** channel (RGB**A**) - which specifies the opacity for a color.

An RGBA color value is specified with: rgba(red, green, blue, _alpha_). The _alpha_ parameter is a number between 0.0 (fully transparent) and 1.0 (fully opaque).

**Tip:** You will learn more about RGBA Colors in our [CSS Colors Chapter]().

### Example
```css
div {
    background: rgba(0, 128, 0, 0.3) /* Green background with 30% opacity */
}
```
## The CSS Background Color Property

| Property | Description |
| --- | --- |
| [background-color]() | Sets the background color of an element |


# [<<< Previous](../05_Comments/01_Comments.md) :[More](02_background_image.md): [Next >>>](../07_Box_Modal/01_box_modal.md)
