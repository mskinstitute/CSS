## `.alert` 

Alerts are created with the `.alert` class, followed by one of the contextual classes `.alert-success`, `.alert-info`, `.alert-warning`, `.alert-danger`, `.alert-primary`, `.alert-secondary`, `.alert-light` or `.alert-dark`:

```html
<div class="alert alert-success">  
  <strong>Success!</strong> Indicates a successful or positive action.  
</div>  
```

## `.alert-link` Alert Links
Add the `.alert-link` class to any links inside the alert box to create "matching colored links":

```html
<div class="alert alert-success">  
  <strong>Success!</strong> You should <a href="#" class="alert-link">read this message.</a>
</div>  
```

## `.alert-dismissible` Closing Alerts

To close the alert message, add a `.alert-dismissible` class to the alert container. Then add `class="btn-close"` and `data-bs-dismiss="alert"` to a link or a button element (when you click on this the alert box will disappear).

```html
<div class="alert alert-success alert-dismissible">  
  <button type="button" class="btn-close" data-bs-dismiss="alert"></button>  
  <strong>Success!</strong> This alert box could indicate a successful or positive action.  
</div>  
```

## `.fade` and `.show` Animated Alerts

The `.fade` and `.show` classes adds a fading effect when closing the alert message:

```html
<div class="alert alert-danger alert-dismissible fade show">
```

