# Layout - float and clear

The CSS `float` property specifies how an element should float.

The CSS `clear` property specifies what elements can float beside the cleared element and on which side.

## The float Property

The `float` property is used for positioning and formatting content e.g. let an image float left to the text in a container.

The `float` property can have one of the following values:

-   `left` - The element floats to the left of its container
-   `right` - The element floats to the right of its container
-   `none` - This is default

In its simplest use, the `float` property can be used to wrap text around images.

## Example 👇
- float: right; [view](float_right.html)
- float: left; [view](float_left.html)
- float: none; [view](float_none.html)

## Float Next To Each Other

Normally div elements will be displayed on top of each other. However, if we use `float: left` we can let elements float next to each other:
## Example 👇
```html
<!DOCTYPE html>
<html>
<head>
<style>
div {
  float: right;
  padding: 15px; 
}

.div1 {
  background: red;
}

.div2 {
  background: yellow;
}

.div3 {
  background: green;
}
</style>
</head>
<body>

<h2>Float Next To Each Other</h2>

<p>In this example, the three divs will float next to each other.</p>

<div class="div1">Box 1</div>
<div class="div2">Box 2</div>
<div class="div3">Box 3</div>

</body>
</html>
```
