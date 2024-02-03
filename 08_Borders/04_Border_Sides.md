## CSS Border - Individual Sides

From the examples on the previous pages, you have seen that it is possible to specify a different border for each side.

In CSS, there are also properties for specifying each of the borders (top, right, bottom, and left):

### Example
```css
p {
    border-top-style: dotted;  
    border-right-style: solid;  
    border-bottom-style: dotted;  
    border-left-style: solid;
}
```
<style>
    p.different{
    border-top-style: dotted;  
    border-right-style: solid;  
    border-bottom-style: dotted;  
    border-left-style: solid;
}
</style>

Result:
<p class=different>
    Different Border Styles
</p>

The example above gives the same result as this:

### Example
```css
p {
    border-style: dotted solid;
}
```

So, here is how it works:

If the `border-style` property has four values:

-   **border-style: dotted solid double dashed;**
    -   top border is dotted
    -   right border is solid
    -   bottom border is double
    -   left border is dashed

If the `border-style` property has three values:

-   **border-style: dotted solid double;**
    -   top border is dotted
    -   right and left borders are solid
    -   bottom border is double

If the `border-style` property has two values:

-   **border-style: dotted solid;**
    -   top and bottom borders are dotted
    -   right and left borders are solid

If the `border-style` property has one value:

-   **border-style: dotted;**
    -   all four borders are dotted

### Example
```css
<style>
body {
  text-align: center;
}
/* Four values */
p.four {
  border-style: dotted solid double dashed;
}

/* Three values */
p.three {
  border-style: dotted solid double;
}

/* Two values */
p.two {
  border-style: dotted solid;
}

/* One value */
p.one {
  border-style: dotted;
}
</style>
```

<style>
p.four {
  border-style: dotted solid double dashed;
}
p.three {
  border-style: dotted solid double;
}
p.two {
  border-style: dotted solid;
}
p.one {
  border-style: dotted;
}
</style>


<h2>Individual Border Sides</h2>
<p class="four">4 different border styles.</p>
<p class="three">3 different border styles.</p>
<p class="two">2 different border styles.</p>
<p class="one">1 border style.</p>

> The `border-style` property is used in the example above. However, it also works with `border-width` and `border-color`.