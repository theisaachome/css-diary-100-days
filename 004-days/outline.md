
# CSS Outline

- a line drawn outside the element's border.

- OUTSIDE the borders, to make the element "stand out".

- CSS has the following outline properties:

    - outline-style
    - outline-color
    - outline-width
    - outline-offset
    - outline

## CSS Outline Width

- The `outline-width` property specifies the width of the outline.

```css
.btn {
  border: 1px solid black;
  outline-style: solid;
  outline-color: red;
  outline-width: thin; 
  outline-width: medium;
  outline-width: thick;
  outline-width: 4px;
}
```
## CSS Outline Color
- The `outline-color` property is used to set the color of the outline.

```css
.btn{
    border:2px solid black;
    outline-style:solid;
    outline-color:red;
    outline-width:4px;
}
```
## CSS Outline - Shorthand property
- The `outline` property is a shorthand property for setting the following individual outline properties:
    - outline-width
    - outline-style (required)
    - outline-color
```css
p {outline: dashed;}
p {outline: dotted red;}
p {outline: 5px solid yellow;}
p {outline: thick ridge pink;}
```

## CSS Outline Offset
- The `outline-offset` property adds space between an outline and the edge/border of an element.
- The space between an element and its outline is transparent.
```css
p {
  margin: 30px;
  border: 1px solid black;
  outline: 1px solid red;
  outline-offset: 15px;
}
```

