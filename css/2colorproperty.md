# Color Property

## Definition

The `color` property is used to set the **text color** of an HTML element.

## Syntax

```css
selector {
    color: value;
}
```

## Example

```css
h1 {
    color: blue;
}
```

## Different Ways to Set Color

### Color Name

```css
p {
    color: red;
}
```

### HEX Value

```css
p {
    color: #ff0000;
}
```

### RGB Value

```css
p {
    color: rgb(255, 0, 0);
}
```

### HSL Value

```css
p {
    color: hsl(0, 100%, 50%);
}
```

## Example with HTML

```html
<h1>Hello World</h1>
<p>This is a paragraph.</p>
```

```css
h1 {
    color: blue;
}

p {
    color: green;
}
```

## Note

- `color` changes the **text color**.
- It does not change the background color.
- For background color, use the `background-color` property.