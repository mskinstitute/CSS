## How To Create a Modal

The following example shows how to create a basic modal:

> **Note:**  Not working without these link: 👇
```html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
```
### Example
```html
<!-- Button to Open the Modal -->
<button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#myModal">
Open modal
</button>

<!-- The Modal -->
<div class="modal" id="myModal">
<div class="modal-dialog">
    <div class="modal-content">

    <!-- Modal Header -->
    <div class="modal-header">
        <h4 class="modal-title">Modal Heading</h4>
        <button type="button" class="btn-close" data-bs-dismiss="modal"></button>
    </div>

    <!-- Modal body -->
    <div class="modal-body">
        Modal body..
    </div>

    <!-- Modal footer -->
    <div class="modal-footer">
        <button type="button" class="btn btn-danger" data-bs-dismiss="modal">Close</button>
    </div>

    </div>
</div>
</div>
```

## Add animation

Use the `.fade` class to add a fading effect when opening and closing the modal:

### Example
```html
<!-- Fading modal -->
<div class="modal fade"></div>

<!-- Modal without animation -->
<div class="modal"></div>
```

## Modal Size

Change the size of the modal by adding the `.modal-sm` class for small modals (max-width 300px), `.modal-lg` class for large modals  (max-width 800px), or `.modal-xl` for extra large modals  (max-width 1140px). Default is 500px max-width.

Add the size class to the `<div>` element with class `.modal-dialog`:

### Small Modal
```html
<div class="modal-dialog modal-sm">
```

### Large Modal
```html
<div class="modal-dialog modal-lg">
```

### Extra Large Modal
```html
<div class="modal-dialog modal-xl">
```

> By default, modals are "medium" in size (500px max-width).

## Fullscreen Modals

If you want the modal to span the whole width and height of the page, use the `.modal-fullscreen` class:

### Example
```html
<div class="modal-dialog modal-fullscreen">
```

## Responsive Fullscreen Modals

You can also control when the modal should be in fullscreen, with the `.modal-fullscreen-*-*` classes:

| Class | Description | Example |
| --- | --- | --- |
| `.modal-fullscreen-sm-down` | Fullscreen below 576px | [Check Now]() |
| `.modal-fullscreen-md-down` | Fullscreen below 768px | [Check Now]() |
| `.modal-fullscreen-lg-down` | Fullscreen below 992px | [Check Now]() |
| `.modal-fullscreen-xl-down` | Fullscreen below 1200px | [Check Now]() |
| `.modal-fullscreen-xxl-down` | Fullscreen below 1400px | [Check Now]() |
---

## Centered Modal

Center the modal vertically and horizontally within the page, with the `.modal-dialog-centered` class:

### Example
```html
<div class="modal-dialog modal-dialog-centered">
```

## Scrolling Modal

When you have a lot of content inside the modal, a scrollbar is added to the page. See the examples below to understand it:

### Example
```html
<div class="modal-dialog">
```

However, it is possible to only scroll inside the modal, instead of the page itself, by adding `.modal-dialog-scrollable` to `.modal-dialog`:

### Example
```html
<div class="modal-dialog modal-dialog-scrollable">
```