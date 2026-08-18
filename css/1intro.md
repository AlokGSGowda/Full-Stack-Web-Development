# CSS

## What is CSS?

CSS stands for **Cascading Style Sheets**.

CSS is used to **style and design HTML elements** on a webpage.

It is used to control things like:
- Colors
- Fonts
- Sizes
- Spacing
- Layout
- Backgrounds
- Borders

## Basic CSS Format

```css
selector {
    property: value;
}
```

### Example

```css
h1 {
    color: blue;
    font-size: 30px;
}
```

Here:

- `h1` → Selector
- `color` → Property
- `blue` → Value
- `color: blue;` → Declaration

## Including CSS in HTML

There are **3 ways** to include CSS in HTML:

### 1. Inline CSS

CSS is written directly inside the HTML element using the `style` attribute.

```html
<h1 style="color: red;">Hello</h1>
```

### 2. Internal CSS

CSS is written inside the `<style>` element in the HTML `<head>`.

```html
<head>
    <style>
        h1 {
            color: blue;
        }
    </style>
</head>
```

### 3. External CSS

CSS is written in a separate `.css` file and connected to the HTML using the `<link>` element.

**HTML:**

```html
<head>
    <link rel="stylesheet" href="style.css">
</head>
```

**style.css:**

```css
h1 {
    color: green;
}
```

## Note

- **Inline CSS** → Written inside the HTML element.
- **Internal CSS** → Written inside `<style>` in the HTML file.
- **External CSS** → Written in a separate `.css` file.
- External CSS is commonly preferred for larger websites because it keeps HTML and CSS separate.