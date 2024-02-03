Markdown Cheatsheet<a name="TOP"></a>
=================== 
[NoteBook File link](markdown_cheatSheet.ipynb)


# Heading 1 

## Heading 2 

### Heading 3 

#### Heading 4 

# Common_text

## `Italic text` `_`, `*`
_Italic text_ or *Italic*

## `Strong text` `__`, `**`

__Strong text__ or **Strong text**

## `Strong Italic text` `___`, `***`

___Strong Italic text___ or ***Strong Italic text***

## `Strickethrough` `~~`
~~Strikethrough text~~

<br><br>

# Link `[link-name](path, "title")`

1. [Named Link](http://www.google.fr/ "Named link title")
2. <http://example.com/>
3. [Id Link](#common_text "Goto Common_text")

<br>

# Table, like this one:

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

```
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell
```

## Adding a pipe `|` in a cell :

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | \|

```
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  |  \| 
```

Left, right and center aligned table

Left aligned Header | Right aligned Header | Center aligned Header
| :---        | ---:         | :---:
Content Cell  | Content Cell | Content Cell
Content Cell  | Content Cell | Content Cell

<br><br>

`code()`

```html
<p>paragraph <b>emphasis</b>
```


```javascript
var specificLanguage_code = 
{
    "data": {
        "lookedUpPlatform": 1,
        "query": "Kasabian+Test+Transmission",
        "lookedUpItem": {
            "name": "Test Transmission",
            "artist": "Kasabian",
            "album": "Kasabian",
            "picture": null,
            "link": "http://open.spotify.com/track/5jhJur5n4fasblLSCOcrTp"
        }
    }
}
```


* Bullet list
    * Nested bullet
        * Sub-nested bullet etc
* Bullet list item 2

~~~
* Bullet list
    * Nested bullet
        * Sub-nested bullet etc
* Bullet list item 2

-OR-

- Bullet list
    - Nested bullet
        - Sub-nested bullet etc
- Bullet list item 2 
~~~

1. A numbered list
    1. A nested numbered list
    2. Which is numbered
2. Which is numbered

~~~
1. A numbered list
    1. A nested numbered list
    2. Which is numbered
2. Which is numbered
~~~

- [ ] An uncompleted task
- [x] A completed task
```
- [ ] An uncompleted task
- [x] A completed task
```
- [ ] An uncompleted task
    - [ ] A subtask

~~~
- [ ] An uncompleted task
- [ ] A subtask
~~~

> Blockquote
>> Nested blockquote skldjf lkjsldkfj kldfjkl sdjfsdlkf slkdfj sdkjf dsfh sdkljfl sdlkfjls djjsfd ljsjdlkfhksdl fljdlkf lsdkjf lsdkjfklsd kjjfsd hlsjdkljfsd lkdjskljfsdfl sdlkjf ldskjflk dsjkflj sdkjklfsdj lksdjf jsdfl jkldjf lkjdlksd lsjdjsdkf Nested blockquote skldjf lkjsldkfj kldfjkl sdjfsdlkf slkdfj sdkjf dsfh sdkljfl sdlkfjls djjsfd ljsjdlkfhksdl fljdlkf lsdkjf lsdkjfklsd kjjfsd hlsjdkljfsd lkdjskljfsdfl sdlkjf ldskjflk dsjkflj sdkjklfsdj lksdjf jsdfl jkldjf lkjdlksd lsjdjsdkf

> Blockquote
>> Nested Blockquote

# Horizontal line :
----

# Image with alt `![text](image path "title")`:

![picture alt](https://mskinstitute.github.io/assets/img/hello.png "Title is optional")

![picture alt](http://via.placeholder.com/200x150 "Title is optional")

Foldable text:

<details>
  <summary>HTML</summary>
  <p>Content 1 Content 1 Content 1 Content 1 Content 1</p>
</details>

<details style="cursor: pointer">
  <summary>CSS</summary>
  <p>Content 2 Content 2 Content 2 Content 2 Content 2</p>
</details>

<br><br>

```HTML
<details>
    <summary>Title 1</summary>
    <p>Content 1 Content 1 Content 1 Content 1 Content 1</p>
</details>
```

```html
<h3>HTML</h3>
<p> Some HTML code here </p>
```

# Hotkey (keyboard button) `<kbd>`:

<kbd>⌘ + H</kbd>

<kbd>🪟 + H</kbd>

<kbd>Ctrl + A</kbd> = Select All 

Hotkey list:

| Key | Symbol |
| --- | --- |
| Option | ⌥ |
| Control | ⌃ |
| Command | ⌘ |
| Shift | ⇧ |
| Caps Lock | ⇪ |
| Tab | ⇥ |
| Esc | ⎋ |
| Power | ⌽ |
| Return | ↩ |
| Delete | ⌫ |
| Up | ↑ |
| Down | ↓ |
| Left | ← |
| Right | → |

Emoji:

:exclamation: Use emoji icons to enhance text. :+1:  Look up emoji codes at [emoji-cheat-sheet.com](http://emoji-cheat-sheet.com/)

    Markup : Code appears between colons :EMOJICODE:
