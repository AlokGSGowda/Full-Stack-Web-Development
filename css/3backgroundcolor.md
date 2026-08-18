# Background Color Property

## Definition

The `background-color` property is used to set the **background color** of an HTML element.

## Syntax

```css
selector {
    background-color: value;
}
```

## Example

```css
h1 {
    background-color: yellow;
}
```

## Different Ways to Set Color

### Color Name

```css
p {
    background-color: red;
}
```

### HEX Value

```css
p {
    background-color: #ff0000;
}
```

### RGB Value

```css
p {
    background-color: rgb(255, 0, 0);
}
```

### HSL Value

```css
p {
    background-color: hsl(0, 100%, 50%);
}
```

## Example with HTML

```html
<h1>Hello World</h1>
<p>This is a paragraph.</p>
```

```css
h1 {
    background-color: blue;
}

p {
    background-color: lightgreen;
}
```

## Note

- `background-color` changes the **background color** of an element.
- `color` changes the **text color**.