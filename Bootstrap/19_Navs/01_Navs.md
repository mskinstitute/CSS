## Nav Menus

If you want to create a simple horizontal menu, add the `.nav` class to a `<ul>` element, followed by `.nav-item` for each `<li>` and add the `.nav-link` class to their links:

### Example
```html
<ul class="nav">
  <li class="nav-item">
    <a class="nav-link" href="#">Link</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" href="#">Link</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" href="#">Link</a>
  </li>
  <li class="nav-item">
    <a class="nav-link disabled" href="#">Disabled</a>
  </li>
</ul>
```

## Aligned Nav

[Link](javascript:void(0)) [Link](javascript:void(0)) [Link](javascript:void(0)) [Disabled](javascript:void(0))

[Link](javascript:void(0)) [Link](javascript:void(0)) [Link](javascript:void(0)) [Disabled](javascript:void(0))

Add the `.justify-content-center` class to center the nav, and the `.justify-content-end` class to right-align the nav.

### Example

<!-- Centered nav -->  
<ul class\="nav justify-content-center"\>  
  
<!-- Right-aligned nav -->  
<ul class\="nav justify-content-end"\>  

[Try it Yourself »](https://www.w3schools.com/bootstrap5/bootstrap_navs.phptryit.asp?filename=trybs_nav_align&stacked=h)

___

## Vertical Nav

[Link](javascript:void(0)) [Link](javascript:void(0)) [Link](javascript:void(0)) [Disabled](javascript:void(0))

Add the `.flex-column` class to create a vertical nav:

### Example

<ul class\="nav flex-column"\>  

[Try it Yourself »](https://www.w3schools.com/bootstrap5/bootstrap_navs.phptryit.asp?filename=trybs_nav_vertical&stacked=h)

___

___

## Tabs

[Active](javascript:void(0)) [Link](javascript:void(0)) [Link](javascript:void(0)) [Disabled](javascript:void(0))

Turn the nav menu into navigation tabs with the `.nav-tabs` class. Add the `.active` class to the active/current link. If you want the tabs to be togglable, see the last example on this page.

### Example

<ul class\="nav nav-tabs"\>  
  <li class\="nav-item"\>  
    <a class\="nav-link active" href\="#"\>Active</a\>  
  </li\>  
  <li class\="nav-item"\>  
    <a class\="nav-link" href\="#"\>Link</a\>  
  </li\>  
  <li class\="nav-item"\>  
    <a class\="nav-link" href\="#"\>Link</a\>  
  </li\>  
  <li class\="nav-item"\>  
    <a class\="nav-link disabled" href\="#"\>Disabled</a\>  
  </li\>  
</ul\>

[Try it Yourself »](https://www.w3schools.com/bootstrap5/bootstrap_navs.phptryit.asp?filename=trybs_nav_tabs&stacked=h)

___

## Pills

[Active](javascript:void(0)) [Link](javascript:void(0)) [Link](javascript:void(0)) [Disabled](javascript:void(0))

Turn the nav menu into navigation pills with the `.nav-pills` class. If you want the pills to be togglable, see the last example on this page.

### Example

<ul class\="nav nav-pills"\>  
  <li class\="nav-item"\>  
    <a class\="nav-link active" href\="#"\>Active</a\>  
  </li\>  
  <li class\="nav-item"\>  
    <a class\="nav-link" href\="#"\>Link</a\>  
  </li\>  
  <li class\="nav-item"\>  
    <a class\="nav-link" href\="#"\>Link</a\>  
  </li\>  
  <li class\="nav-item"\>  
    <a class\="nav-link disabled" href\="#"\>Disabled</a\>  
  </li\>  
</ul\>

[Try it Yourself »](https://www.w3schools.com/bootstrap5/bootstrap_navs.phptryit.asp?filename=trybs_nav_pills&stacked=h)

___

## Justified Tabs/pills

Justify the tabs/pills with the `.nav-justified` class (equal width):

-   [Active](javascript:void(0))
-   [Link](javascript:void(0))
-   [Link](javascript:void(0))
-   [Disabled](javascript:void(0))

  

-   [Active](javascript:void(0))
-   [Link](javascript:void(0))
-   [Link](javascript:void(0))
-   [Disabled](javascript:void(0))

### Example

<ul class\="nav nav-pills nav-justified"\>..</ul\>  
<ul class\="nav nav-tabs nav-justified"\>..</ul\>

[Try it Yourself »](https://www.w3schools.com/bootstrap5/bootstrap_navs.phptryit.asp?filename=trybs_nav_justified&stacked=h)

___

## Pills with Dropdown

-   [Active](javascript:void(0))
-   [Dropdown](javascript:void(0))
    
    [Link 1](javascript:void(0)) [Link 2](javascript:void(0)) [Link 3](javascript:void(0))
    
-   [Link](javascript:void(0))
-   [Disabled](javascript:void(0))

### Example

<ul class\="nav nav-pills"\>  
  <li class\="nav-item"\>  
    <a class\="nav-link active" href\="#"\>Active</a\>  
  </li\>  
  <li class\="nav-item dropdown"\>  
    <a class\="nav-link dropdown-toggle" data-bs-toggle\="dropdown" href\="#"\>Dropdown</a\>  
    <ul class\="dropdown-menu"\>  
      <li\><a class\="dropdown-item" href\="#"\>Link 1</a\></li\>  
      <li\><a class\="dropdown-item" href\="#"\>Link 2</a\></li\>  
      <li\><a class\="dropdown-item" href\="#"\>Link 3</a\></li\>  
    </ul\>  
  </li\>  
  <li class\="nav-item"\>  
    <a class\="nav-link" href\="#"\>Link</a\>  
  </li\>  
  <li class\="nav-item"\>  
    <a class\="nav-link disabled" href\="#"\>Disabled</a\>  
  </li\>  
</ul\>

[Try it Yourself »](https://www.w3schools.com/bootstrap5/bootstrap_navs.phptryit.asp?filename=trybs_nav_pills_dropdown&stacked=h)

___

## Tabs with Dropdown

-   [Active](javascript:void(0))
-   [Dropdown](javascript:void(0))
    
    [Link 1](javascript:void(0)) [Link 2](javascript:void(0)) [Link 3](javascript:void(0))
    
-   [Link](javascript:void(0))
-   [Disabled](javascript:void(0))

### Example

<ul class\="nav nav-tabs"\>  
  <li class\="nav-item"\>  
    <a class\="nav-link active" href\="#"\>Active</a\>  
  </li\>  
  <li class\="nav-item dropdown"\>  
    <a class\="nav-link dropdown-toggle" data-bs-toggle\="dropdown" href\="#"\>Dropdown</a\>  
    <ul class\="dropdown-menu"\>  
      <li\><a class\="dropdown-item" href\="#"\>Link 1</a\></li\>  
      <li\><a class\="dropdown-item" href\="#"\>Link 2</a\></li\>  
      <li\><a class\="dropdown-item" href\="#"\>Link 3</a\></li\>  
    </ul\>  
  </li\>  
  <li class\="nav-item"\>  
    <a class\="nav-link" href\="#"\>Link</a\>  
  </li\>  
  <li class\="nav-item"\>  
    <a class\="nav-link disabled" href\="#"\>Disabled</a\>  
  </li\>  
</ul\>

[Try it Yourself »](https://www.w3schools.com/bootstrap5/bootstrap_navs.phptryit.asp?filename=trybs_nav_tabs_dropdown&stacked=h)

___

## Toggleable / Dynamic Tabs

-   [Home](https://www.w3schools.com/bootstrap5/bootstrap_navs.php#home)
-   [Menu 1](https://www.w3schools.com/bootstrap5/bootstrap_navs.php#menu1)
-   [Menu 2](https://www.w3schools.com/bootstrap5/bootstrap_navs.php#menu2)

### HOME

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

### Menu 1

Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

### Menu 2

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam.

To make the tabs toggleable, add the `data-toggle="tab"` attribute to each link. Then add a `.tab-pane` class with a unique ID for every tab and wrap them inside a `<div>` element with class `.tab-content`.

If you want the tabs to fade in and out when clicking on them, add the `.fade` class to `.tab-pane`:

### Example

<!-- Nav tabs -->  
<ul class\="nav nav-tabs"\>  
  <li class\="nav-item"\>  
    <a class\="nav-link active" data-bs-toggle\="tab" href\="#home"\>Home</a\>  
  </li\>  
  <li class\="nav-item"\>  
    <a class\="nav-link" data-bs-toggle\="tab" href\="#menu1"\>Menu 1</a\>  
  </li\>  
  <li class\="nav-item"\>  
    <a class\="nav-link" data-bs-toggle\="tab" href\="#menu2"\>Menu 2</a\>  
  </li\>  
</ul\>  
  
<!-- Tab panes -->  
<div class\="tab-content"\>  
  <div class\="tab-pane container active" id\="home"\>...</div\>  
  <div class\="tab-pane container fade" id\="menu1"\>...</div\>  
  <div class\="tab-pane container fade" id\="menu2"\>...</div\>  
</div\>  

[Try it Yourself »](https://www.w3schools.com/bootstrap5/bootstrap_navs.phptryit.asp?filename=trybs_nav_tabs_toggleable&stacked=h)

___

## Toggleable / Dynamic Pills

-   [Home](https://www.w3schools.com/bootstrap5/bootstrap_navs.php#home1)
-   [Menu 1](https://www.w3schools.com/bootstrap5/bootstrap_navs.php#menu12)
-   [Menu 2](https://www.w3schools.com/bootstrap5/bootstrap_navs.php#menu22)

### HOME

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

### Menu 1

Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

### Menu 2

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam.

The same code applies to pills; only change the data-toggle attribute to `data-toggle="pill"`:

### Example

<!-- Nav pills -->  
<ul class\="nav nav-pills"\>  
  <li class\="nav-item"\>  
    <a class\="nav-link active" data-bs-toggle\="pill" href\="#home"\>Home</a\>  
  </li\>  
  <li class\="nav-item"\>  
    <a class\="nav-link" data-bs-toggle\="pill" href\="#menu1"\>Menu 1</a\>  
  </li\>  
  <li class\="nav-item"\>  
    <a class\="nav-link" data-bs-toggle\="pill" href\="#menu2"\>Menu 2</a\>  
  </li\>  
</ul\>  
  
<!-- Tab panes -->  
<div class\="tab-content"\>  
  <div class\="tab-pane container active" id\="home"\>...</div\>  
  <div class\="tab-pane container fade" id\="menu1"\>...</div\>  
  <div class\="tab-pane container fade" id\="menu2"\>...</div\>  
</div\>