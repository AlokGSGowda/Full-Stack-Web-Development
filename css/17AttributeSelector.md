# Attribute Selector

## Definition

The attribute selector is used to select HTML elements based on their **attributes or attribute values**.

## Syntax

```css
[attribute] {
    property: value;
}
```

## Example

```html
<input type="text">
<input type="password">
```

```css
[type="text"] {
    background-color: lightgray;
}
```

This selects the `<input>` element whose `type` attribute is `"text"`.

## Common Types

### Select by Attribute

Selects elements that have the specified attribute.

```css
input[type] {
    border: 1px solid black;
}
```

### Select by Exact Attribute Value

Selects elements whose attribute has exactly the specified value.

```css
input[type="text"] {
    background-color: yellow;
}
```

### Select by Class Attribute

```css
[class="box"] {
    color: blue;
}
```

## Example

```html
<input type="text">
<input type="email">
<input type="password">
```

```css
input[type="email"] {
    background-color: lightblue;
}
```

Only the email input will be selected.

## Note

- Attribute selector is written using **square brackets `[]`**.
- `[attribute]` → selects elements that have the attribute.
- `[attribute="value"]` → selects elements with a specific attribute value.