# Line Height

## Definition

The `line-height` property is used to control the **space between lines of text**.

## Syntax

```css
selector {
    line-height: value;
}
```

## Example

```css
p {
    line-height: 1.5;
}
```

You can also use a fixed value:

```css
p {
    line-height: 30px;
}
```

## Note

- A higher `line-height` creates more space between lines.
- A lower `line-height` creates less space between lines.

---

# Letter Spacing

## Definition

The `letter-spacing` property is used to control the **space between individual letters**.

## Syntax

```css
selector {
    letter-spacing: value;
}
```

## Example

```css
h1 {
    letter-spacing: 2px;
}
```

Negative values can also be used:

```css
h1 {
    letter-spacing: -1px;
}
```

## Note

- Positive value → increases space between letters.
- Negative value → decreases space between letters.
- `0` → normal letter spacing.