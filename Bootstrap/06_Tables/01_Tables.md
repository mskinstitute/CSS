## Basic Table

A basic Bootstrap 5 table has a light padding and horizontal dividers.

## `.table`
```html
<table class="table">
    <thead>
        <tr>
            <th>Firstname</th>
            <th>Lastname</th>
            <th>Email</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Sumit</td>
            <td>Kumar</td>
            <td>mrsumitcontact@gmail.com</td>
        </tr>
        <tr>
            <td>Amit</td>
            <td>Yadav</td>
            <td>amityadav@gmail.com</td>
        </tr>
        <tr>
            <td>Aryan</td>
            <td>Yadav</td>
            <td>aryanyadav@gmail.com</td>
        </tr>
    </tbody>
</table>
```

## `.table-striped`

The `.table-striped` class adds `zebra`-stripes to a table:
```html
<table class="table table-striped">
    ...
</table>
```

## `.table-bordered`
```html
<table class="table table-bordered">
    ...
</table>
```

## `.table-hover`
```html
<table class="table table-hover">
    ...
</table>
```

## `.table-dark`
```html
<table class="table table-dark">
    ...
</table>
```

## `.table-dark` and `.table-striped`
```html
<table class="table table-dark table-striped">
    ...
</table>
```

## `.table-dark` and `.table-hover`
```html
<table class="table table-dark table-hover">
    ...
</table>
```

## `.table-borderless`
```html
<table class="table table-borderless">
    ...
</table>
```

# Contextual Classes

```html
<table class="table">
    <thead>
        <tr>
            <th>Firstname</th>
            <th>Lastname</th>
            <th>Email</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Sumit</td>
            <td>Kumar</td>
            <td>mrsumitcontact@gmail.com</td>
        </tr>
        <tr class="table-primary">
            <td>Sumit</td>
            <td>Kumar</td>
            <td>mrsumitcontact@gmail.com</td>
        </tr>
        <tr class="table-success">
            <td>Sumit</td>
            <td>Kumar</td>
            <td>mrsumitcontact@gmail.com</td>
        </tr>
        <tr class="table-danger">
            <td>Sumit</td>
            <td>Kumar</td>
            <td>mrsumitcontact@gmail.com</td>
        </tr>
        <tr class="table-info">
            <td>Sumit</td>
            <td>Kumar</td>
            <td>mrsumitcontact@gmail.com</td>
        </tr>
        <tr class="table-warning">
            <td>Sumit</td>
            <td>Kumar</td>
            <td>mrsumitcontact@gmail.com</td>
        </tr>
        <tr class="table-active">
            <td>Sumit</td>
            <td>Kumar</td>
            <td>mrsumitcontact@gmail.com</td>
        </tr>
        <tr class="table-secondary">
            <td>Sumit</td>
            <td>Kumar</td>
            <td>mrsumitcontact@gmail.com</td>
        </tr>
        <tr class="table-light">
            <td>Sumit</td>
            <td>Kumar</td>
            <td>mrsumitcontact@gmail.com</td>
        </tr>
        <tr class="table-dark">
            <td>Sumit</td>
            <td>Kumar</td>
            <td>mrsumitcontact@gmail.com</td>
        </tr>
    </tbody>
</table>
```

# Table Head Colors

```html
<table class="table">
    <thead class="table-dark">
        ...
    </thead>
    <tbody>
        ...
    </tbody>
</table>
```

## `.table-sm`
```html
<table class="table table-bordered table-sm">
    <thead>
        ...
    </thead>
    <tbody>
        ...
    </tbody>
</table>
```

## `.table-responsive`

```html
<div class="table-responsive">
    <table class="table table-bordered">
        <thead>
            <tr>
                <th>#</th>
                <th>Firstname</th>
                <th>Lastname</th>
                <th>Age</th>
                <th>City</th>
                <th>Country</th>
                <th>Sex</th>
                <th>Example</th>
                <th>Example</th>
                <th>Example</th>
                <th>Example</th>
                <th>Example</th>
                <th>Example</th>
                <th>Example</th>
                <th>Example</th>
                <th>Example</th>
                <th>Example</th>
                <th>Example</th>
                <th>Example</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1</td>
                <td>Anna</td>
                <td>Pitt</td>
                <td>35</td>
                <td>New York</td>
                <td>USA</td>
                <td>Female</td>
                <td>Yes</td>
                <td>Yes</td>
                <td>Yes</td>
                <td>Yes</td>
                <td>Yes</td>
                <td>Yes</td>
                <td>Yes</td>
                <td>Yes</td>
                <td>Yes</td>
                <td>Yes</td>
                <td>Yes</td>
                <td>Yes</td>
            </tr>
        </tbody>
    </table>
</div>
```

You can also decide when the table should get a scrollbar, depending on the screen width:

| Class | Screen width |
| --- | --- |
| `.table-responsive-sm` | < 576px |
| `.table-responsive-md` | < 768px |
| `.table-responsive-lg` | < 992px |
| `.table-responsive-xl` | < 1200px |
| `.table-responsive-xxl` | < 1400px |

### Example
```html
<div class="table-responsive-sm">
  <table class="table">  
    ...  
  </table>  
</div>
```