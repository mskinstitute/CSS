## `.text-color`
Colors name for bootstrap:

- muted
- primary
- success
- info
- warning
- danger
- secondary
- dark
- body
- light
- white

## [Example File:](index.html)

```html
<p class="text-muted">muted.</p>
<p class="text-primary">important.</p>
<p class="text-success">success.</p>
<p class="text-info">information.</p>
<p class="text-warning">This text represents a warning.</p>
<p class="text-danger">danger.</p>
<p class="text-secondary">Secondary text.</p>
<p class="text-dark">dark grey.</p>
<p class="text-body">Default body color (often black).</p>
<p class="text-light">light grey (on white background).</p>
<p class="text-white">white (on white background).</p>
```

## `.text-color-opacity-50`
You can also add 50% opacity for black or white text with the `.text-black-50` or `.text-white-50` classes:
```html
<p class="text-black-50">Black text with 50% opacity on white background</p>
<p class="text-white-50 bg-dark">White text with 50% opacity on black background</p>
```

## `.bg-color`
```html
<div class="bg-primary p-3"></div>
<div class="bg-success p-3"></div>
<div class="bg-info p-3"></div>
<div class="bg-warning p-3"></div>
<div class="bg-danger p-3"></div>
<div class="bg-secondary p-3"></div>
<div class="bg-dark p-3"></div>
<div class="bg-light p-3"></div>
```

The `.bg-color` classes above does not work well with text, or atleast then you have to specify a proper `.text-color` class to get the right text color for each background.

However, you can use the `.text-bg-color` classes and Bootstrap will automatically handle the appropriate text color for each background color:
## `.text-bg-color`
```html
<p class="text-bg-primary">This text is important.</p>
<p class="text-bg-success">This text indicates success.</p>
<p class="text-bg-info">This text represents some information.</p>
<p class="text-bg-warning">This text represents a warning.</p>
<p class="text-bg-danger">This text represents danger.</p>
<p class="text-bg-secondary">Secondary background color.</p>
<p class="text-bg-dark">Dark grey background color.</p>
<p class="text-bg-light">Light grey background color.</p>
```

# 👈 [Back](../04_Typography/01_Typography.md)  📝  [Next](../06_Tables/01_Tables.md) 👉
