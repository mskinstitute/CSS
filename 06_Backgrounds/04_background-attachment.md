## CSS background-attachment

The `background-attachment` property specifies whether the background image should scroll or be fixed (will not scroll with the rest of the page):

### Example

Specify that the background image should be fixed:
```css
body {
    background-image: url("img_tree.png");  
    background-repeat: no-repeat;  
    background-position: right top;  
    background-attachment: fixed;
}
```
### Example

Specify that the background image should scroll with the rest of the page:
```css
body {
    background-image: url("img_tree.png");  
    background-repeat: no-repeat;  
    background-position: right top;  
    background-attachment: scroll;
}
```

## The CSS Background Attachment Property

| Property | Description |
| --- | --- |
| [background-attachment]() | Sets whether a background image is fixed or scrolls with the rest of the page |

## Property Values

| Value | Description |
| --- | --- |
| scroll | The background image will scroll with the page. This is default |
| fixed | The background image will not scroll with the page |
| local | The background image will scroll with the element's contents |
| initial | Sets this property to its default value. [Read about _initial_]() |
| inherit | Inherits this property from its parent element. [Read about _inherit_]() |