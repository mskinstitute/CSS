## `.spinner-border` Spinners

To create a spinner/loader, use the `.spinner-border` class:

```html
<div class="spinner-border"></div>
```

### Colored Spinners

```html
<div class="spinner-border text-danger"></div>
```
## `.spinner-grow` Growing Spinners

Use the `.spinner-grow` class if you want the spinner/loader to grow instead of "spin":
```html  
<div class="spinner-grow text-success"></div>
```

## Spinner Size
Use `.spinner-border-sm` or `.spinner-grow-sm` to create a smaller spinner:
```html
<div class="spinner-border spinner-border-sm"></div>
<div class="spinner-grow spinner-grow-sm"></div>
```

## Spinner Buttons
You can also add spinners to a button, with or without text:
```html
<button class="btn btn-primary">
  <span class="spinner-border spinner-border-sm"></span>
</button>

<button class="btn btn-primary">
  <span class="spinner-border spinner-border-sm"></span>
  Loading..
</button>

<button class="btn btn-primary" disabled>
  <span class="spinner-border spinner-border-sm"></span>
  Loading..
</button>

<button class="btn btn-primary" disabled>
  <span class="spinner-grow spinner-grow-sm"></span>
  Loading..
</button>
```

