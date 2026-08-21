# ID Selector

## Definition

The ID selector is used to select **one specific HTML element** using its `id` attribute.

## Syntax

```css
#id {
    property: value;
}
```

## Example

```html
<h1 id="heading">Hello World</h1>
```

```css
#heading {
    color: blue;
}
```

Here:

- `id="heading"` → gives the element a unique ID.
- `#heading` → selects the element with that ID.

## Example with Multiple Elements

```html
<h1 id="title">Welcome</h1>
<p>This is a paragraph.</p>
```

```css
#title {
    color: red;
    text-align: center;
}
```

Only the `<h1>` with `id="title"` will be affected.

## Note

- ID selector starts with `#`.
- An `id` should be **unique** within a webpage.
- It is used to style a **specific element**.
- The CSS ID selector must match the HTML `id`.

```css
#heading {
    color: blue;
}
```

```html
<h1 id="heading">Hello</h1>
```