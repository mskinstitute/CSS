## CSS Margins
<!-- <body style="background-color:skyblue;> -->

The CSS `margin` properties are used to create space around elements, outside of any defined borders.

With CSS, you have full control over the margins. There are properties for setting the margin for each side of an element (top, right, bottom, and left).

___

## Margin - Individual Sides

CSS has properties for specifying the margin for each side of an element:

-   `margin-top`
-   `margin-right`
-   `margin-bottom`
-   `margin-left`

All the margin properties can have the following values:

-   auto - the browser calculates the margin
-   _length_ - specifies a margin in px, pt, cm, etc.
-   _%_ - specifies a margin in % of the width of the containing element
-   inherit - specifies that the margin should be inherited from the parent element

**Tip:** Negative values are allowed.

### Example

Set different margins for all four sides of a <p> element:
```css
p {
    margin-top: 100px;  
    margin-bottom: 100px;  
    margin-right: 150px;  
    margin-left: 80px;
}
```

## Margin - Shorthand Property

To shorten the code, it is possible to specify all the margin properties in one property.

The `margin` property is a shorthand property for the following individual margin properties:

-   `margin-top`
-   `margin-right`
-   `margin-bottom`
-   `margin-left`

So, here is how it works:

If the `margin` property has four values:

-   **margin: 25px 50px 75px 100px;**
    -   top margin is 25px
    -   right margin is 50px
    -   bottom margin is 75px
    -   left margin is 100px

### Example

Use the margin shorthand property with four values:
```css
p {  margin: 25px 50px 75px 100px; }
```

If the `margin` property has three values:

-   **margin: 25px 50px 75px;**
    -   top margin is 25px
    -   right and left margins are 50px
    -   bottom margin is 75px

### Example

Use the margin shorthand property with three values: 
```css
p {  margin: 25px 50px 75px;}
```

If the `margin` property has two values:

-   **margin: 25px 50px;**
    -   top and bottom margins are 25px
    -   right and left margins are 50px

### Example

Use the margin shorthand property with two values: 
```css
p { margin: 25px 50px;}
```

If the `margin` property has one value:

-   **margin: 25px;**
    -   all four margins are 25px

### Example

Use the margin shorthand property with one value: 
```css
p {  margin: 25px;}
```

## The auto Value

You can set the margin property to `auto` to horizontally center the element within its container.

The element will then take up the specified width, and the remaining space will be split equally between the left and right margins.

### Example

Use margin: auto:
```css
div { 
    width: 300px;  
    margin: auto;  
    border: 1px solid red;
}
```

## The inherit Value

This example lets the left margin of the` <p class="ex1">` element be inherited from the parent element (`<div>`):

### Example

Use of the inherit value:
```css
div {  border: 1px solid red;  
  margin-left: 100px;}  
  
p.ex1 {  margin-left: inherit;}
```

## All CSS Margin Properties

| Property | Description |
| --- | --- |
| [margin]() | A shorthand property for setting all the margin properties in one declaration |
| [margin-bottom]() | Sets the bottom margin of an element |
| [margin-left]() | Sets the left margin of an element |
| [margin-right]() | Sets the right margin of an element |
| [margin-top]() | Sets the top margin of an element |


# [👈 Previous](../09_Padding/01_Padding.md) 📝 [Next 👉](../11_Hight_Width/01_Height_Width_and_Max_width.md)