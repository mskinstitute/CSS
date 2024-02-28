## Dark Mode

By default, bootstrap pages have a `light` theme.

If you want to change the whole page to a dark theme, you can add `data-bs-theme="dark"` to the `<html>` element:

```html
<!DOCTYPE html>
<html lang="en" data-bs-theme="dark">
<head>
  <title>MSK !nstitute</title>
<body>

<div class="container mt-3">
  <h1>MSK !nstitute</h1>
  <p>Best for learn coding</p>
  
</div>

</body>
</html>
```


## Dark Mode For Components

If you don't want the whole page to have a darker color, but only specific components, you can add the `data-bs-theme="dark"` attribute to the specified component.

For example, add dark mode to a table:

### Example
```html
<table class="table" data-bs-theme="dark">
```

Or for example, add dark mode to a dropdown menu:

### Example
```html
<div class="dropdown" data-bs-theme="dark">
```