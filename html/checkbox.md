# Checkbox Input Element

## Definition

A checkbox allows the user to select **one or more options** from a list.

## Syntax

```html
<input type="checkbox" name="option" value="value">
```

## Example

```html
<input type="checkbox" name="skills" value="html"> HTML
<input type="checkbox" name="skills" value="css"> CSS
<input type="checkbox" name="skills" value="javascript"> JavaScript
```

## Attributes

### `type="checkbox"`

Specifies that the input element is a checkbox.

```html
<input type="checkbox">
```

### `name`

Specifies the name of the checkbox.

```html
<input type="checkbox" name="skills">
```

### `value`

Specifies the value of the checkbox when it is selected.

```html
<input type="checkbox" name="skills" value="html">
```

### `checked`

Makes the checkbox selected by default.

```html
<input type="checkbox" name="skills" value="html" checked>
```

## Example Form

```html
<form>
    <label>
        <input type="checkbox" name="skills" value="html">
        HTML
    </label>

    <label>
        <input type="checkbox" name="skills" value="css">
        CSS
    </label>

    <label>
        <input type="checkbox" name="skills" value="javascript">
        JavaScript
    </label>

    <button type="submit">Submit</button>
</form>
```

## Note

- Checkbox allows **multiple selections**.
- `checked` selects the checkbox by default.
- `value` is submitted when the checkbox is selected.