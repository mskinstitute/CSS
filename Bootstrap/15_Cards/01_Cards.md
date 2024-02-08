## Cards

A card in Bootstrap 5 is a bordered box with some padding around its content. It includes options for headers, footers, content, colors, etc.

## Basic Card

A basic card is created with the `.card` class, and content inside the card has a `.card-body` class:
```html
<div class="card">
  <div class="card-body">Basic card</div>
</div>
```

## Header and Footer

- Header
- Content
- Footer

The `.card-header` class adds a heading to the card and the `.card-footer` class adds a footer to the card:
```html
<div class="card">
  <div class="card-header">Header</div>
  <div class="card-body">Content</div>
  <div class="card-footer">Footer</div>
</div>
```

## Contextual Cards

To add a background color the card, use contextual classes `.bg-primary`, `.bg-success`, `.bg-info`, `.bg-warning`, `.bg-danger`, `.bg-secondary`, `.bg-dark` and `.bg-light`.
```html
<div class="card bg-primary text-white">
    <div class="card-body">Primary card</div>
</div>
```

## Titles, text, and links

Use `.card-title` to add card titles to any heading element. The `.card-text` class is used to remove bottom margins for a `<p>` element if it is the last child (or the only one) inside `.card-body`. The `.card-link` class adds a blue color to any link, and a hover effect.
```html
<div class="card">
  <div class="card-body">
    <h4 class="card-title">Card title</h4>
    <p class="card-text">Some example text. Some example text.</p>
    <a href="#" class="card-link">Card link</a>
    <a href="#" class="card-link">Another link</a>
  </div>
</div>
```

Add `.card-img-top` or `.card-img-bottom` to an `<img>` to place the image at the top or at the bottom inside the card. Note that we have added the image outside of the `.card-body` to span the entire width:
```html
<div class="card" style="width:400px">
  <img class="card-img-top" src="img_avatar1.png" alt="Card image">
  <div class="card-body">
    <h4 class="card-title">John Doe</h4>
    <p class="card-text">Some example text.</p>
    <a href="#" class="btn btn-primary">See Profile</a>
  </div>
</div>
```

## Card Image Overlays
Turn an image into a card background and use `.card-img-overlay` to add text on top of the image:
```html
<div class="card" style="width:500px">
  <img class="card-img-top" src="img_avatar1.png" alt="Card image">
  <div class="card-img-overlay">
    <h4 class="card-title">John Doe</h4>
    <p class="card-text">Some example text.</p>
    <a href="#" class="btn btn-primary">See Profile</a>
  </div>
</div>
```

