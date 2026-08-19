# Text Align Property

## Definition

The `text-align` property is used to set the **horizontal alignment of text** inside an element.

## Syntax

```css
selector {
    text-align: value;
}
```

## Values

### `left`

Aligns the text to the left.

```css
p {
    text-align: left;
}
```

### `right`

Aligns the text to the right.

```css
p {
    text-align: right;
}
```

### `center`

Aligns the text to the center.

```css
h1 {
    text-align: center;
}
```

### `justify`

Stretches the text so that each line has equal width.

```css
p {
    text-align: justify;
}
```

## Example

```html
<h1>Hello World</h1>
<p>This is a paragraph.</p>
```

```css
h1 {
    text-align: center;
}

p {
    text-align: justify;
}
```

## Note

- `left` → Aligns text to the left.
- `right` → Aligns text to the right.
- `center` → Aligns text to the center.
- `justify` → Aligns text evenly on both sides.