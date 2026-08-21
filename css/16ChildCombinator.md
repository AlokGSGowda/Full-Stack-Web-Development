# Child Combinator

## Definition

The child combinator is used to select **direct children** of an element.

It is represented by the `>` symbol.

## Syntax

```css
parent > child {
    property: value;
}
```

## Example

```html
<div>
    <p>Hello</p>
    <section>
        <p>Inside Section</p>
    </section>
</div>
```

```css
div > p {
    color: blue;
}
```

Only the **first `<p>`** is selected because it is a direct child of `<div>`.

The `<p>` inside `<section>` is not selected because it is not a direct child of `<div>`.

## Difference from Descendant Selector

### Descendant Selector

```css
div p {
    color: blue;
}
```

Selects **all `<p>` elements inside `<div>`**, at any level.

### Child Combinator

```css
div > p {
    color: blue;
}
```

Selects only `<p>` elements that are **direct children** of `<div>`.

## Note

- `>` represents the **child combinator**.
- It selects only **direct children**.
- It does not select deeper/nested descendants.