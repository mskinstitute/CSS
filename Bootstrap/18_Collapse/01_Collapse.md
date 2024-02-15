## Basic Collapse

Collapsibles are useful when you want to hide and show large amount of content:

Click Me

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

### Example

```html
<button data-bs-toggle="collapse" data-bs-target="#demo">Collapsible</button>

<div id="demo" class="collapse">
    Lorem ipsum dolor text....
</div>
```

### Example Explained

The `.collapse` class indicates a collapsible element (a `<div>` in our example); this is the content that will be shown or hidden with a click of a button.

To control (show/hide) the collapsible content, add the `data-bs-toggle="collapse"` attribute to an `<a>` or a `<button>` element. Then add the `data-bs-target="#id"` attribute to connect the button with the collapsible content (`<div id="demo">`).

**Note:** For `<a>` elements, you can use the `href` attribute instead of the `data-bs-target` attribute:

### Example
```html
<a href="#demo" data-bs-toggle="collapse">Collapsible</a>

<div id="demo" class="collapse">
    Lorem ipsum dolor text....
</div>
```

By default, the collapsible content is hidden. However, you can add the `.show` class to show the content by default:

### Example
```html
<div id="demo" class="collapse show">
    Lorem ipsum dolor text....
</div>
```

## Accordion

### Example

```html
<div id="accordion">

  <div class="card">
    <div class="card-header">
      <a class="btn" data-bs-toggle="collapse" href="#collapseOne">
        Collapsible Group Item #1
      </a>
    </div>
    <div id="collapseOne" class="collapse show" data-bs-parent="#accordion">
      <div class="card-body">
        Lorem ipsum..
      </div>
    </div>
  </div>

  <div class="card">
    <div class="card-header">
      <a class="collapsed btn" data-bs-toggle="collapse" href="#collapseTwo">
        Collapsible Group Item #2
      </a>
    </div>
    <div id="collapseTwo" class="collapse" data-bs-parent="#accordion">
      <div class="card-body">
        Lorem ipsum..
      </div>
    </div>
  </div>

  <div class="card">
    <div class="card-header">
      <a class="collapsed btn" data-bs-toggle="collapse" href="#collapseThree">
        Collapsible Group Item #3
      </a>
    </div>
    <div id="collapseThree" class="collapse" data-bs-parent="#accordion">
      <div class="card-body">
        Lorem ipsum..
      </div>
    </div>
  </div>

</div>
```