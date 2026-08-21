# Descendant Selector

## Definition

The descendant selector is used to select elements that are **inside another element**, at any level.

## Syntax

```css
parent child {
    property: value;
}
```

## Example

```html
<div>
    <p>Hello World</p>
    <p>This is a paragraph.</p>
</div>
```

```css
div p {
    color: blue;
}
```

This selects all `<p>` elements that are inside the `<div>`.

## Example with Multiple Levels

```html
<div>
    <section>
        <p>Hello</p>
    </section>
</div>
```

```css
div p {
    color: red;
}
```

The `<p>` is still selected because it is a descendant of `<div>`.

## Note

- A space between selectors represents a **descendant relationship**.
- It selects matching elements at **any level inside** the parent.
- It is different from the child selector (`>`), which selects only **direct children**.

```css
div p {
    color: blue;
}
```