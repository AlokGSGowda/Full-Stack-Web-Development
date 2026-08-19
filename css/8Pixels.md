# CSS Units - Pixel

## Definition

A **pixel (`px`)** is an absolute CSS unit used to specify the size of elements, text, spacing, borders, and other properties.

## Basic Conversion

```text
1 inch = 96 pixels
```

So:

```text
1in = 96px
0.5in = 48px
2in = 192px
```

## Syntax

```css
selector {
    property: value;
}
```

## Example

```css
h1 {
    font-size: 32px;
}

p {
    margin: 20px;
}
```

Here:

- `32px` → font size of 32 pixels
- `20px` → margin of 20 pixels

## Common Uses

### Font Size

```css
p {
    font-size: 16px;
}
```

### Width

```css
div {
    width: 300px;
}
```

### Height

```css
div {
    height: 200px;
}
```

### Margin

```css
div {
    margin: 20px;
}
```

### Padding

```css
div {
    padding: 10px;
}
```

## Note

- `px` stands for **pixel**.
- `px` is an **absolute CSS unit**.
- `1 inch = 96 pixels` in CSS.
- Pixels can be used for font size, width, height, margin, padding, borders, etc.