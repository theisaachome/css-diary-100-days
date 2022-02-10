# CSS Height, Width and Max-width

- To set the height and width of an element.

## CSS Setting height and width

```css
div {
  height: 50px;
  width: 100%;
  border: 1px solid #4caf50;
}
```

- The height and width properties do not include padding, borders, or margins.

- It sets the height/width of the area inside the padding, border, and margin of the element.

---

## CSS height and width Values

The height and width properties may have the following values:

- `auto`
  - This is default. The browser calculates the height and width.
  ```css
  .mybox {
    height: auto;
    width: auto;
    background-color: aqua;
  }
  ```
- `length`
  - Defines the height/width in px, cm etc.
  ```css
  .mybox {
    height: 200px;
    width: 50%;
    background-color: powderblue;
  }
  ```
- `%`

  - Defines the height/width in percent of the containing block

  ```css
  .box {
    height: 300px;
    width: 50%;
    background: blueviolet;
  }
  ```

- `initial`
  - Sets the height/width to its default value.
- `inherit`
  - The height/width will be inherited from its parent value


---
## Max-width

### Setting max-width

- The CSS `max-width` property is used to set the maximum width of an element.


- The max-width can be specified in length values, like px, cm, etc., or in percent (%) of the containing block, or set to none

```css
div {
  max-width: 500px;
  height: 100px;
  background-color: powderblue;
}
```