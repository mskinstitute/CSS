## `.rounded`
The `.rounded` class adds rounded corners to an image:
```html
<img src="cinqueterre.jpg" class="rounded" alt="Cinque Terre">
```
## `.rounded-circle`
The `.rounded-circle` class shapes the image to a circle:
```html
<img src="cinqueterre.jpg" class="rounded-circle" alt="Cinque Terre">
```

## `.img-thumbnail`
The `.img-thumbnail` class shapes the image to a thumbnail (bordered):

### Example
```html
<img src="cinqueterre.jpg" class="img-thumbnail" alt="Cinque Terre">
```

## `.float-start` or `.float-end`

Float an image to the left with the `.float-start` class or to the right with `.float-end`:
```html
<img src="paris.jpg" class="float-start">  
<img src="paris.jpg" class="float-end">
```

## `.mx-auto` and `.d-block` Centered Image

Center an image by adding the utility classes `.mx-auto` (margin X position:auto) and `.d-block` (display:block) to the image:
```html
<img src="paris.jpg" class="mx-auto d-block">
```

## `.img-fluid` Responsive Images

Images come in all sizes. So do screens. Responsive images automatically adjust to fit the size of the screen.

The `.img-fluid` class applies `max-width: 100%;` and `height: auto;` to the image:

### Example
```html
<img class="img-fluid" src="ny.jpg" alt="New York" width="1100" height="500">
```
