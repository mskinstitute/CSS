## Flexbox

The biggest difference between Bootstrap 3 and Bootstrap 4 & 5 is that Bootstrap 5 now uses flexbox, instead of floats, to handle the layout.

The Flexible Box Layout Module, makes it easier to design flexible responsive layout structure without using float or positioning. If you are new to flex, you can read about it in our [CSS Flexbox Tutorial]().

**Note:** Flexbox is not supported in IE9 and earlier versions.

**If you require IE8-9 support, use [Bootstrap 3.]()** It is the most stable version of Bootstrap, and it is still supported by the team for critical bugfixes and documentation changes. However, no new features will be added to it.

To create a flexbox container and to transform direct children into flex items, use the `d-flex` class:

# `d-flex`
### Example
```html
<div class="d-flex p-3 bg-secondary text-white">
  <div class="p-2 bg-info">Home</div>
  <div class="p-2 bg-warning">About</div>
  <div class="p-2 bg-primary">Contact</div>
</div>
```
# `d-inline-flex`
To create an inline flexbox container, use the `d-inline-flex` class:
### Example
```html
<div class="d-inline-flex p-3 bg-secondary text-white">
  <div class="p-2 bg-info">Home</div>
  <div class="p-2 bg-warning">About</div>
  <div class="p-2 bg-primary">Contact</div>
</div>
```
# `.flex-row`
Use `.flex-row` to display the flex items horizontally (side by side). This is default.
### Example
```html
<div class="container mt-3">
  <div class="d-flex flex-row bg-secondary mb-3">
    <div class="p-2 bg-info">Home</div>
    <div class="p-2 bg-warning">About</div>
    <div class="p-2 bg-primary">Contact</div>
  </div>
</div>
```
# `.flex-row-reverse`
Use `.flex-row-reverse` to right-align the horizontal direction:
```html
<div class="container mt-3">
  <div class="d-flex flex-row-reverse bg-secondary">
    <div class="p-2 bg-info">Home</div>
    <div class="p-2 bg-warning">About</div>
    <div class="p-2 bg-primary">Contact</div>
  </div>
</div>
```
# `.flex-column`
Use `.flex-column` to display the flex items vertically (on top of each other):

### Example
```html
<div class="container mt-3">
  <div class="d-flex flex-column mb-3">
    <div class="p-2 bg-info">Home</div>
    <div class="p-2 bg-warning">About</div>
    <div class="p-2 bg-primary">Contact</div>
  </div>
</div>
```
# `.flex-column-reverse`
Use `.flex-column-reverse` to reverse the vertical direction:
```html
<div class="container mt-3">
  <div class="d-flex flex-column-reverse">
    <div class="p-2 bg-info">Home</div>
    <div class="p-2 bg-warning">About</div>
    <div class="p-2 bg-primary">Contact</div>
  </div>
</div>
```
# `.justify-content-*`

Use the `.justify-content-*` classes to change the alignment of flex items. Valid classes are `start` (default), `end`, `center`, `between` or `around`:

### Example
```html
<div class="container mt-3">
  <div class="d-flex justify-content-start bg-secondary mb-3">
      <div class="p-2 bg-info">Start</div>
      <div class="p-2 bg-info">Start</div>
      <div class="p-2 bg-info">Start</div>
  </div>
  <div class="d-flex justify-content-end bg-secondary mb-3">
      <div class="p-2 bg-info">End</div>
      <div class="p-2 bg-info">End</div>
      <div class="p-2 bg-info">End</div>
  </div>
  <div class="d-flex justify-content-center bg-secondary mb-3">
      <div class="p-2 bg-info">Center</div>
      <div class="p-2 bg-info">Center</div>
      <div class="p-2 bg-info">Center</div>
  </div>
  <div class="d-flex justify-content-between bg-secondary mb-3">
      <div class="p-2 bg-info">Between</div>
      <div class="p-2 bg-info">Between</div>
      <div class="p-2 bg-info">Between</div>
      <div class="p-2 bg-info">Between</div>
  </div>
  <div class="d-flex justify-content-around bg-secondary mb-3">
      <div class="p-2 bg-info">Around</div>
      <div class="p-2 bg-info">Around</div>
      <div class="p-2 bg-info">Around</div>
      <div class="p-2 bg-info">Around</div>
  </div>
</div>
```


# `.flex-fill`

Use `.flex-fill` on flex items to force them into equal widths:

### Example
```html
<div class="container mt-3">
  <div class="d-flex mb-3">
    <div class="p-2 bg-info">Home</div>
    <div class="p-2 bg-warning">About</div>
    <div class="p-2 bg-primary">Contact</div>
  </div>
</div>
```

# `.flex-grow-1`

Use `.flex-grow-1` on a flex item to take up the rest of the space. In the example below, the first two flex items take up their necessary space, while the last item takes up the rest of the available space:

### Example
```html
<div class="container mt-3">
  <div class="d-flex mb-3">
      <div class="p-2 bg-info">Home</div>
      <div class="p-2 bg-warning">About</div>
      <div class="p-2 bg-primary">Contact</div>
    <div class="p-2 bg-warning">Flex item 2</div>
    <div class="p-2 flex-grow-1 bg-primary">Flex (flex-grow-1)</div>
  </div>
</div>
```

# `.order-*`
Change the visual order of a specific flex item(s) with the `.order` classes. Valid classes are from `0 to 5`, where the lowest number has highest priority (order-1 is shown before order-2, etc..):

### Example
```html
<div class="container mt-3">
  <div class="d-flex mb-3">
    <div class="p-2 order-3 bg-info">Flex item 1</div>
    <div class="p-2 order-2 bg-warning">Flex item 2</div>
    <div class="p-2 order-1 bg-primary">Flex item 3</div>
  </div>
</div>
```

# `.m-auto`

Easily add auto margins to flex items with `.ms-auto` (push items to the right), or by using `.me-auto` (push items to the left):

### Example
```html
<div class="container mt-3">
  <div class="d-flex mb-3 bg-secondary">
      <div class="p-2 me-auto bg-info">Flex item 1</div>
      <div class="p-2 bg-warning">Flex item 2</div>
      <div class="p-2 bg-primary">Flex item 3</div>
  </div>
</div>
```

## Wrap

Control how flex items wrap in a flex container with `.flex-nowrap` (default), `.flex-wrap` or `.flex-wrap-reverse`.

Click on the buttons below to see the difference between the three classes, by changing the wrapping of the flex items in the example box:
### [Open Example](examples/wrap.html)
```html
<div class="d-flex flex-wrap">..</div>

<div class="d-flex flex-wrap-reverse">..</div>

<div class="d-flex flex-nowrap">..</div>
```


## Align Content

Control the vertical alignment of **gathered** flex items with the `.align-content-*` classes. Valid classes are `.align-content-start` (default), `.align-content-end`, `.align-content-center`, `.align-content-between`, `.align-content-around` and `.align-content-stretch`.

**Note:** These classes have no effect on single rows of flex items.

Click on the buttons below to see the difference between the five classes, by changing the vertical alignment of the flex items in the example box:

### [Open Example](examples/align_content.html)
```html
<div class="d-flex flex-wrap align-content-start">..</div>

<div class="d-flex flex-wrap align-content-end">..</div>

<div class="d-flex flex-wrap align-content-center">..</div>

<div class="d-flex flex-wrap align-content-around">..</div>

<div class="d-flex flex-wrap align-content-stretch">..</div>
```

## Align Items

Control the vertical alignment of **single rows** of flex items with the `.align-items-*` classes. Valid classes are `.align-items-start`, `.align-items-end`, `.align-items-center`, `.align-items-baseline`, and `.align-items-stretch` (default).

Click on the buttons below to see the difference between the five classes:

align-items-start align-items-end align-items-center align-items-baseline align-items-stretch

### [Open Example](examples/align_item.html)

```html
<div class="d-flex align-items-start">..</div>
<div class="d-flex align-items-end">..</div>
<div class="d-flex align-items-center">..</div>
<div class="d-flex align-items-baseline">..</div>
<div class="d-flex align-items-stretch">..</div>
```

## Align Self

Control the vertical alignment of **a specified flex item** with the `.align-self-*` classes. Valid classes are `.align-self-start`, `.align-self-end`, `.align-self-center`, `.align-self-baseline`, and `.align-self-stretch` (default).

Click on the buttons below to see the difference between the five classes:

align-self-start align-self-end align-self-center align-self-baseline align-self-stretch

### [Example](examples/align_self.html)
```html
<div class="d-flex bg-light" style="height:150px">  
  <div class="p-2 border">Flex item 1</div>
  <div class="p-2 border **align-self-start**">Flex item 2</div>
  <div class="p-2 border">Flex item 3</div>
</div>  
```
