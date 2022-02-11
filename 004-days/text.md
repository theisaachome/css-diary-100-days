# CSS Text

- Formatting Text in css.

## Text Color
The `color` property is used to set the color of the text.
- Using the following properties:
- a color name 
    - like "red"
    ```css
        h1 {
            color: green;
        }
    ```
- a HEX value 
    - like "#ff0000"
    ```css
        h1 {
            color: #ff0000;
        }
    ```
- an RGB value 
    - like "rgb(255,0,0)"
    ```css
    h1{
        color:rgb(255,0,0);
    }
    ```
---
## CSS Text Alignment

- Text Alignment

The text-align property is used to set the horizontal alignment of a text.
- A text can be left or right aligned.

```css
h2 {
  text-align: left;
}
h3 {
  text-align: right;
}
```
- A text can be centered, or justified.
```css
h1 {
  text-align: center;
}
p {
  text-align: justify;
}
```

## Text Align Last
- The `text-align-last` property specifies how to align the last line of a text.
```css
p.b {
  text-align-last: center;
}
```

---
## CSS Text Decoration

The `text-decoration-line` property is used to add a decoration line to text.
- Avaiables values:
    - overline
    - line-through
    - underline
```css
h1 {
  text-decoration-line: underline;
}
```

## Specify a Color for the Decoration Line

- The `text-decoration-color` property is used to set the color of the decoration line.

```css
h3 {
  text-decoration-line: underline;
  text-decoration-color: green;
}
```