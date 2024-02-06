## Basic Progress Bar

A progress bar can be used to show how far a user is in a process.

To create a default progress bar, add a `.progress` class to a container element and add the `.progress-bar` class to its child element. Use the CSS `width` property to set the width of the progress bar:

```html
<div class="progress">
  <div class="progress-bar" style="width:70%"></div>
</div>
```

## Progress Bar Height

The height of the progress bar is `16px` by default. Use the CSS `height` property to change it:

```html
<div class="progress" style="height:20px">
  <div class="progress-bar" style="width:40%;"></div>
</div>
```

## Progress Bar Labels

Add text inside the progress bar to show the visible percentage:

```html
<div class="progress">
  <div class="progress-bar" style="width:70%">70%</div>
</div>
```

## Colored Progress Bars

By default, the progress bar is blue (primary). Use any of the contextual background classes to change its color:
```html
<!-- Orange -->
<div class="progress">
   <div class="progress-bar bg-warning" style="width:40%"></div>
</div>
```

## `.progress-bar-striped` Striped Progress Bars

Use the `.progress-bar-striped` class to add stripes to the progress bars:
```html
<div class="progress">
    <div class="progress-bar bg-info progress-bar-striped" style="width:50%"></div>
</div
```

## `.progress-bar-animated` Animated Progress Bar5

Add the `.progress-bar-animated` class to animate the progress bar:
```html
<div class="progress">
    <div class="progress-bar progress-bar-striped progress-bar-animated" style="width:40%"></div>
</div>
```

## Multiple Progress Bars

Progress bars can also be stacked:
```html
<div class="progress">
  <div class="progress-bar bg-success" style="width:40%">
    Free Space
  </div>
  <div class="progress-bar bg-warning" style="width:10%">
    Warning
  </div>
  <div class="progress-bar bg-danger" style="width:20%">
    Danger
  </div>
</div>
```