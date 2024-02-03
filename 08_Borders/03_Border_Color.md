## CSS Border Color

The `border-color` property is used to set the color of the four borders.

> **Note:** If `border-color` is not set, it inherits the color of the element.

### Example

Demonstration of the different border colors:
```css
p.one { 
    border-style: solid;  
    border-color: red;
}  
  
p.two {
    border-style: solid;  
    border-color: green;
}
  
p.three {
    border-style: dotted;  
    border-color: blue;
}
```
Result:
<div style="border-style: solid; margin-bottom: 5px; border-color: Red;">
    Red border
</div>
<div style="border-style: solid; margin-bottom: 5px; border-color: Green;">
    Green border
</div>
<div style="border-style: solid; margin-bottom: 5px; border-color: Blue;">
    Blue border
</div>

## Specific Side Colors

The `border-color` property can have from one to four values (for the top border, right border, bottom border, and the left border). 

### Example
```css
p.one {
  border-style: solid;
  border-color: red green blue yellow; /* red top, green right, blue bottom and yellow left */
}
```
<style>
p.one {
  border-style: solid;
  border-color: red green blue yellow; /* red top, green right, blue bottom and yellow left */
}
</style>

<p class="one">A solid multicolor border</p>

