## Bootstrap 5 Default Settings

Bootstrap 5 uses a default `font-size` of 1rem (16px by default), and its `line-height` is 1.5.

In addition, all `<p>` elements have `margin-top: 0` and `margin-bottom: 1rem` (16px by default).

## `.h1` to `.h6`

```html
<p class="h1">h1 Bootstrap heading</p>  
<p class="h2">h2 Bootstrap heading</p>  
<p class="h3">h3 Bootstrap heading</p>  
<p class="h4">h4 Bootstrap heading</p>  
<p class="h5">h5 Bootstrap heading</p>  
<p class="h6">h6 Bootstrap heading</p>
```

## `.display-1` to `.display-6` Headings

```html
<h1 class="display-1">Display 1</h1>
<h1 class="display-2">Display 2</h1>
<h1 class="display-3">Display 3</h1>
```

## `<small>`or `.small`

`<small>` element  is used to create a smaller, secondary text in any heading:
```html
<h1>h1 heading <small>secondary text</small></h1>
<h2>h2 heading <small>secondary text</small></h2>
<h3>h3 heading <small>secondary text</small></h3>
<h4>h4 heading <small>secondary text</small></h4>
<h5>h5 heading <small>secondary text</small></h5>
<h6>h6 heading <small>secondary text</small></h6>
```

## `<mark>` or `.mark`

`<mark>` and `.mark` with a yellow background color and some padding:

```html
<p>Use the mark element (or the .mark class) to <mark>highlight</mark> text.</p>
```

Use the mark element to highlight text.
## `<abbr>`

HTML `<abbr>` element with a dotted border bottom and a cursor with question mark on hover:

```html
<p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>
```

## `<blockquote>` or `.blockquote`

`.blockquote` class to a `<blockquote>` when quoting blocks of content from another source. And when naming a source, like "from WWF's website", use the `.blockquote-footer` class:

```html
<blockquote class="blockquote">
    <p>For 50 years, WWF has been protecting the future of nature. The world's leading conservation organization, WWF works in 100 countries and is supported by 1.2 million members in the United States and close to 5 million globally.</p>
    <footer class="blockquote-footer">From WWF's website</footer>
</blockquote>
```

## `<dl>`
```html
<dl>
    <dt>Coffee</dt>
        <dd>- black hot drink</dd>
    <dt>Milk</dt>
        <dd>- white cold drink</dd>
</dl>
```

## `<code>`
```html
<p>The following HTML elements: <code>span</code>, <code>section</code>, and <code>div</code> defines a section in a document.</p>
```

## `<kbd>` Keyboard Shortcut
```html
<p>Use <kbd>ctrl + p</kbd> to open the Print dialog box.</p>
```

## `<pre>`
```html
<h1>Multiple Code Lines</h1>
<p>For multiple lines of code, use the pre element:</p>
<pre>
Text in a pre element
is displayed in a fixed-width
font, and it preserves
both      spaces and
line breaks.
</pre>
```

## More Typography Classes

## `.lead`
```html
<p class="lead">This paragraph stands out.</p>
```

```html
<p class="text-start">Left-aligned text.</p>
<p class="text-end">Right-aligned text.</p>      
<p class="text-center">Center-aligned text.</p>
<p class="text-nowrap">No wrap text. No wrap text. No wrap text. No wrap text.</p>
```
## `.text-break`
```html
<p class="text-break">
    AaBbCcDdEeFfGgHhIiJjKkLlMmNnOoPpQqRrSsTtUuVvWwXxYyZzAaBbCcDdEeFfGgHhIiJjKkLlMmNnOoPpQqRrSsTtUuVvWwXxYyZzAaBbCcDdEeFfGgHhIiJjKkLlMmNnOoPpQqRrSsTtUuVvWwXxYyZzAaBbCcDdEeFfGgHhIiJjKkLlMmNnOoPpQqRrSsTtUuVvWwXxYyZz
</p>

<p>Without .text-break:</p>
<p>
    AaBbCcDdEeFfGgHhIiJjKkLlMmNnOoPpQqRrSsTtUuVvWwXxYyZzAaBbCcDdEeFfGgHhIiJjKkLlMmNnOoPpQqRrSsTtUuVvWwXxYyZzAaBbCcDdEeFfGgHhIiJjKkLlMmNnOoPpQqRrSsTtUuVvWwXxYyZzAaBbCcDdEeFfGgHhIiJjKkLlMmNnOoPpQqRrSsTtUuVvWwXxYyZz
</p>
```

## `.text-decoration-none`
```html
<a href="#" class="text-decoration-none">A link without underline.</a>
```

## `.text-lowercase`, `.text-uppercase`, `.text-capitalize`
```html
<h2>Case</h2>
<p class="text-lowercase">Lowercased text.</p>
<p class="text-uppercase">Uppercased text.</p>      
<p class="text-capitalize">Capitalized text.</p>
```
## `.initialism`
```html
<p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948. (normal abbr)</p>      
<p>The <abbr title="World Health Organization" class="initialism">WHO</abbr> was founded in 1948. (slightly smaller abbr)</p>
```
## `.list-unstyled`
```html
<ul class="list-unstyled">
    <li>Coffee</li>
    <li>Tea
        <ul>
            <li>Black tea</li>
            <li>Green tea</li>
        </ul>
    </li>
    <li>Milk</li>
</ul>
```
## `.list-inline`
```html
<ul class="list-inline">
    <li class="list-inline-item">Coffee</li>
    <li class="list-inline-item">Tea</li>
    <li class="list-inline-item">Milk</li>
</ul>
```