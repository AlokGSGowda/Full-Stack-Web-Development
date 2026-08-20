# Font Family

## Definition

The `font-family` property is used to specify the **font of the text**.

## Syntax

```css
selector {
    font-family: font-name;
}
```

## Example

```css
p {
    font-family: Arial;
}
```

## Multiple Fonts

Multiple fonts can be provided as a **fallback**. If the first font is not available, the browser uses the next one.

```css
p {
    font-family: Arial, sans-serif;
}
```

## Common Font Families

```css
p {
    font-family: Arial;
}

h1 {
    font-family: Georgia;
}

h2 {
    font-family: "Times New Roman";
}
```

## Generic Font Families

### `serif`

Fonts with small decorative strokes.

```css
p {
    font-family: serif;
}
```

### `sans-serif`

Fonts without decorative strokes.

```css
p {
    font-family: sans-serif;
}
```

### `monospace`

Each character has the same width.

```css
p {
    font-family: monospace;
}
```

## Note

- `font-family` changes the **typeface of text**.
- Multiple fonts can be specified as fallbacks.
- Use quotes when the font name contains spaces.

```css
p {
    font-family: "Times New Roman", serif;
}
```