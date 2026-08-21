# Class Selector

## Definition

The class selector is used to select **HTML elements that have a specific class**.

## Syntax

```css
.class-name {
    property: value;
}
```

## Example

```html
<p class="text">Hello World</p>
<p class="text">This is a paragraph.</p>
```

```css
.text {
    color: blue;
}
```

This applies the style to **all elements with `class="text"`**.

## Example with Different Elements

```html
<h1 class="heading">Welcome</h1>
<p class="heading">Hello World</p>
```

```css
.heading {
    color: red;
}
```

Both elements will have red text.

## Note

- Class selector starts with a **`.`**.
- The class name in CSS must match the `class` attribute in HTML.
- The same class can be used on **multiple HTML elements**.
- One HTML element can have **multiple classes**.

```html
<p class="text highlight">Hello</p>
```