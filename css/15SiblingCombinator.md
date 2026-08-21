# Sibling Combinator

## Definition

The sibling combinator is used to select elements that are **siblings**, meaning they have the same parent element.

There are two types of sibling combinators:

- Adjacent sibling (`+`)
- General sibling (`~`)

## 1. Adjacent Sibling Combinator (`+`)

### Definition

Selects the element that comes **immediately after** another element.

### Syntax

```css
element1 + element2 {
    property: value;
}
```

### Example

```html
<h1>Heading</h1>
<p>First paragraph</p>
<p>Second paragraph</p>
```

```css
h1 + p {
    color: blue;
}
```

Only the **first `<p>`** is selected because it comes immediately after `<h1>`.

---

## 2. General Sibling Combinator (`~`)

### Definition

Selects **all matching sibling elements that come after** another element.

### Syntax

```css
element1 ~ element2 {
    property: value;
}
```

### Example

```html
<h1>Heading</h1>
<p>First paragraph</p>
<p>Second paragraph</p>
```

```css
h1 ~ p {
    color: red;
}
```

Both `<p>` elements are selected because they are siblings of `<h1>` and come after it.

## Note

- `+` → selects the **immediately next sibling**.
- `~` → selects **all matching siblings after** the element.
- Sibling elements must have the **same parent**.