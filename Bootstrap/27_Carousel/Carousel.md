## How To Create a Carousel

The following example shows how to create a basic carousel with indicators and controls:

### Example
```html
<!-- Carousel -->
<div id="demo" class="carousel slide" data-bs-ride="carousel">

  <!-- Indicators/dots -->
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#demo" data-bs-slide-to="0" class="active"></button>
    <button type="button" data-bs-target="#demo" data-bs-slide-to="1"></button>
    <button type="button" data-bs-target="#demo" data-bs-slide-to="2"></button>
  </div>

  <!-- The slideshow/carousel -->
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="https://mdbcdn.b-cdn.net/img/new/slides/041.webp" alt="Los Angeles" class="d-block w-100">
    </div>
    <div class="carousel-item">
      <img src="https://mdbcdn.b-cdn.net/img/new/slides/042.webp" alt="Chicago" class="d-block w-100">
    </div>
    <div class="https://mdbcdn.b-cdn.net/img/new/slides/043.webp">
      <img src="ny.jpg" alt="New York" class="d-block w-100">
    </div>
  </div>

  <!-- Left and right controls/icons -->
  <button class="carousel-control-prev" type="button" data-bs-target="#demo" data-bs-slide="prev">
    <span class="carousel-control-prev-icon"></span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#demo" data-bs-slide="next">
    <span class="carousel-control-next-icon"></span>
  </button>
</div>
```

### Example explained

A description of what each class from the example above do:

| Class | Description |
| --- | --- |
| `.carousel` | Creates a carousel |
| `.carousel-indicators` | Adds indicators for the carousel. These are the little dots at the bottom of each slide (which indicates how many slides there are in the carousel, and which slide the user are currently viewing) |
| `.carousel-inner` | Adds slides to the carousel |
| `.carousel-item` | Specifies the content of each slide |
| `.carousel-control-prev` | Adds a left (previous) button to the carousel, which allows the user to go back between the slides |
| `.carousel-control-next` | Adds a right (next) button to the carousel, which allows the user to go forward between the slides |
| `.carousel-control-prev-icon` | Used together with .carousel-control-prev to create a "previous" button |
| `.carousel-control-next-icon` | Used together with .carousel-control-next to create a "next" button |
| `.slide` | Adds a CSS transition and animation effect when sliding from one item to the next. Remove this class if you do not want this effect |

Add elements inside `<div class="carousel-caption">` within each `<div class="carousel-item">` to create a caption for each slide:

### Example
```html
<div class="carousel-item">
  <img src="la.jpg" alt="Los Angeles">
  <div class="carousel-caption">
    <h3>MSK Institute</h3>
    <p>Best for learn coding & computer course in shikohabad</p>
  </div>
</div>
```