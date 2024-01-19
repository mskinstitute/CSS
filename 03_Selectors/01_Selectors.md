# [<<< Previous](../02_Syntax/01_Syntax.md) :: [Next >>>](../04_How_To_Add_CSS/01_How_To_Add_CSS.md)

# CSS Selectors

A CSS selector selects the HTML element(s) you want to style.

## CSS Selectors

CSS selectors are used to "find" (or select) the HTML elements you want to style.

We can divide CSS selectors into five categories:

-   Simple selectors (select elements based on name, id, class)
-   [Combinator selectors]() (select elements based on a specific relationship between them)
-   [Pseudo-class selectors]() (select elements based on a certain state)
-   [Pseudo-elements selectors]() (select and style a part of an element)
-   [Attribute selectors]() (select elements based on an attribute or attribute value)

This page will explain the most basic CSS selectors.

## The CSS element Selector

The element selector selects HTML elements based on the element name.

### [Example:](selector.html)

Here, all `<p>` elements on the page will be center-aligned, with a red text color: 
```css
p{
    text-align: center;  
    color: red;
}
```

## The CSS id Selector

The id selector uses the id attribute of an HTML element to select a specific element.

The id of an element is unique within a page, so the id selector is used to select one unique element!

To select an element with a specific id, write a hash (#) character, followed by the id of the element.

### Example

The CSS rule below will be applied to the HTML element with id="para1": 
```css
#para1{
    text-align: center;  
    color: red;
}
```

**Note:** An id name cannot start with a number!

## The CSS class Selector

The class selector selects HTML elements with a specific class attribute.

To select elements with a specific class, write a period (.) character, followed by the class name.

### Example

In this example all HTML elements with class="center" will be red and center-aligned: 
```css
.center{
    text-align: center;  
    color: red;
}
```

You can also specify that only specific HTML elements should be affected by a class.

### Example

In this example only `<p>` elements with class="center" will be red and center-aligned: 
```css
p.center{
    text-align: center;  
    color: red;
}
```

HTML elements can also refer to more than one class.

### Example

In this example the `<p>` element will be styled according to `class="center"` and to `class="large"`: 
```html
<p class="center large">This paragraph refers to two classes.</p>
```

**Note:** A class name cannot start with a number!

## The CSS Universal Selector

The universal selector `(\*)` selects all HTML elements on the page.

### Example

The CSS rule below will affect every HTML element on the page: 
```css
*{
    text-align: center;  
    color: blue;
}
```

## The CSS Grouping Selector

The grouping selector selects all the HTML elements with the same style definitions.

Look at the following CSS code (the h1, h2, and p elements have the same style definitions):
```css
h1{
    text-align: center;  
    color: red;
}  
  
h2{
    text-align: center;  
    color: red;
}  
  
p{
    text-align: center;  
    color: red;
}
```
It will be better to group the selectors, to minimize the code.

To group selectors, separate each selector with a comma.

### Example

In this example we have grouped the selectors from the code above: 
```css
h1, h2, p {
    text-align: center;  
    color: red;
}
```

## All CSS Simple Selectors

<table border>
  <tbody><tr>
    <th style="width:20%">Selector</th>
    <th style="width:20%">Example</th>
    <th>Example description</th>
  </tr>
  <tr>
    <td><a href="/cssref/sel_id.asp">#<i>id</i></a></td>
    <td class="notranslate">#firstname</td>
    <td>Selects the element with id="firstname"</td>
  </tr>
  <tr>
    <td><a href="/cssref/sel_class.asp">.<i>class</i></a></td>
    <td class="notranslate">.intro</td>
    <td>Selects all elements with class="intro"</td>
  </tr>
  <tr>
    <td><em><a href="../cssref/sel_element_class.asp">element.class</a></em></td>
    <td class="notranslate">p.intro</td>
    <td>Selects only &lt;p&gt; elements with class="intro"</td>
  </tr>
  <tr>
    <td><a href="/cssref/sel_all.asp">*</a></td>
    <td class="notranslate">*</td>
    <td>Selects all elements</td>
  </tr>
  <tr>
    <td><i><a href="/cssref/sel_element.asp">element</a></i></td>
    <td class="notranslate">p</td>
    <td>Selects all &lt;p&gt; elements</td>
  </tr>
  <tr>
    <td><i><a href="/cssref/sel_element_comma.asp">element,element,..</a></i></td>
    <td class="notranslate">div, p</td>
    <td>Selects all &lt;div&gt; elements and all &lt;p&gt; elements</td>
  </tr>
</tbody></table>

# [<<< Previous](../02_Syntax/01_Syntax.md) :: [Next >>>](../04_How_To_Add_CSS/01_How_To_Add_CSS.md)
