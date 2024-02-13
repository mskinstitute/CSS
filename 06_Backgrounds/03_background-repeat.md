## CSS background-repeat

By default, the `background-image` property repeats an image both horizontally and vertically.

Some images should be repeated only horizontally or vertically, or they will look strange, like this:

### Example
```css
body {
    background-image: url("gradient\_bg.png");
}
```
If the image above is repeated only horizontally (`background-repeat: repeat-x;`), the background will look better:

### Example
```css
body {
    background-image: url("gradient\_bg.png");  
    background-repeat: repeat-x;
}
```

**Tip:** To repeat an image vertically, set `background-repeat: repeat-y;`

## CSS background-repeat: no-repeat

Showing the background image only once is also specified by the `background-repeat` property:

### Example

Show the background image only once:
```css
body {
    background-image: url("img\_tree.png");  
      background-repeat: no-repeat;
}
```

In the example above, the background image is placed in the same place as the text. We want to change the position of the image, so that it does not disturb the text too much.

## CSS background-position

The `background-position` property is used to specify the position of the background image.

### Example

Position the background image in the top-right corner: 
```css
body {
    background-image: url("img\_tree.png");  
    background-repeat: no-repeat;  
    background-position: right top;
}
```
## The CSS Background Repeat and Position Properties

| Property | Description |
| --- | --- |
| [background-position]() | Sets the starting position of a background image |
| [background-repeat]() | Sets how a background image will be repeated |


# [<<< Previous](02_background_image.md) :: [Next >>>](04_background-attachment.md)