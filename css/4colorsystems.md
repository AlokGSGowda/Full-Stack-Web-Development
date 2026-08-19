# CSS Color System

## Color Names

CSS provides predefined **color names** that can be used to set the color of an element.

## Syntax

```css
selector {
    color: color-name;
}
```

## Example

```css
h1 {
    color: red;
}

p {
    color: blue;
}
```

Some common color names:

```text
red
blue
green
yellow
black
white
orange
purple
pink
gray
```

---

# RGB Color System

RGB stands for **Red, Green, Blue**.

An RGB color is represented using three values:

```text
rgb(red, green, blue)
```

Each value ranges from **0 to 255**.

## Syntax

```css
selector {
    color: rgb(red, green, blue);
}
```

## Example

```css
p {
    color: rgb(255, 0, 0);
}
```

This represents **red**.

```css
p {
    color: rgb(0, 255, 0);
}
```

This represents **green**.

```css
p {
    color: rgb(0, 0, 255);
}
```

This represents **blue**.

## Common RGB Values

```text
rgb(255, 0, 0)     → Red
rgb(0, 255, 0)     → Green
rgb(0, 0, 255)     → Blue
rgb(0, 0, 0)       → Black
rgb(255, 255, 255) → White
```

---

# Hex Codes

Hexadecimal color codes are used to represent colors using **6 hexadecimal characters**.

A hex code starts with `#`.

## Syntax

```css
selector {
    color: #RRGGBB;
}
```

`RR`, `GG`, and `BB` represent:

- `RR` → Red
- `GG` → Green
- `BB` → Blue

Each pair can have a value from `00` to `FF`.

## Examples

```css
p {
    color: #ff0000;
}
```

Red

```css
p {
    color: #00ff00;
}
```

Green

```css
p {
    color: #0000ff;
}
```

Blue

## Common Hex Codes

```text
#ff0000 → Red
#00ff00 → Green
#0000ff → Blue
#000000 → Black
#ffffff → White
#ffff00 → Yellow
#ffa500 → Orange
#800080 → Purple
```

## Note

- **Color name** → Easy and readable, e.g. `red`
- **RGB** → Uses values from `0` to `255`, e.g. `rgb(255, 0, 0)`
- **Hex code** → Uses hexadecimal values from `00` to `FF`, e.g. `#ff0000`
- All three methods can be used to set colors in CSS.