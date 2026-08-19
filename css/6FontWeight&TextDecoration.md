# Font Weight

## Definition

The `font-weight` property is used to set the **thickness of the text**.

## Syntax

```css
selector {
    font-weight: value;
}
```

## Values

### `normal`

Sets the normal thickness of the text.

```css
p {
    font-weight: normal;
}
```

### `bold`

Makes the text bold.

```css
h1 {
    font-weight: bold;
}
```

### Numeric Values

Font weight can also be specified using numbers from `100` to `900`.

```css
p {
    font-weight: 700;
}
```

Common values:

```text
400 → Normal
700 → Bold
```

---

# Text Decoration

## Definition

The `text-decoration` property is used to **add or remove decorations** from text.

## Syntax

```css
selector {
    text-decoration: value;
}
```

## Values

### `underline`

Adds an underline to the text.

```css
p {
    text-decoration: underline;
}
```

### `overline`

Adds a line above the text.

```css
p {
    text-decoration: overline;
}
```

### `line-through`

Adds a line through the text.

```css
p {
    text-decoration: line-through;
}
```

### `none`

Removes text decoration.

```css
a {
    text-decoration: none;
}
```

## Example

```html
<h1>Hello World</h1>
<p>This is a paragraph.</p>
<a href="#">Visit Website</a>
```

```css
h1 {
    font-weight: bold;
}

p {
    text-decoration: underline;
}

a {
    text-decoration: none;
}
```

## Note

- `font-weight` controls the **thickness** of text.
- `bold` makes text thicker.
- `text-decoration` adds or removes **lines/decorations** from text.
- `underline` → line below the text.
- `overline` → line above the text.
- `line-through` → line through the text.
- `none` → removes decoration.