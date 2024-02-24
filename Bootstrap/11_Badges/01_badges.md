## `.badge` Badges

Badges are used to add additional information to any content:

Use the `.badge` class together with a contextual class (like `.bg-secondary`) within `<span>` elements to create rectangular badges. Note that badges scale to match the size of the parent element (if any):

```html
<h1>Example heading <span class="badge bg-secondary">New</span></h1>
```

## `.badge bg-primary` Contextual Badges

Use any of the contextual classes (`.bg-*`) to change the color of a badge:
```html
<span class="badge bg-primary">Primary</span>
``` 


## `.rounded-pill`

Use the `.rounded-pill` class to make the badges more round:
```html
<span class="badge rounded-pill bg-primary">Primary</span>
```

## Badge `inside` an Element

An example of using a badge inside a button:
```html
<button type="button" class="btn btn-primary">
  Messages <span class="badge bg-danger">4</span>
</button>
```