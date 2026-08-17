# Select Input Element

## Definition

The `<select>` element is used to create a **dropdown list** from which the user can select an option.

## Syntax

```html
<select name="option">
    <option value="value">Option</option>
</select>
```

## Example

```html
<label for="country">Choose Country:</label>

<select id="country" name="country">
    <option value="india">India</option>
    <option value="usa">USA</option>
    <option value="uk">UK</option>
</select>
```

## Attributes

### `name`

Specifies the name of the select element and is used when submitting form data.

```html
<select name="country">
```

### `id`

Gives a unique identifier to the select element.

```html
<select id="country" name="country">
```

### `for`

The `for` attribute of `<label>` connects the label with the `<select>` using the select's `id`.

```html
<label for="country">Country:</label>
<select id="country" name="country">
```

### `value`

The `value` attribute specifies the value sent when an option is selected.

```html
<option value="india">India</option>
```

### `selected`

The `selected` attribute selects an option by default.

```html
<option value="india" selected>India</option>
```

## Example Form

```html
<form>

    <label for="country">Choose Country:</label>

    <select id="country" name="country">
        <option value="india">India</option>
        <option value="usa">USA</option>
        <option value="uk">UK</option>
    </select>

    <button type="submit">Submit</button>

</form>
```

## Note

- `<select>` creates the dropdown list.
- `<option>` defines the choices inside the dropdown.
- `selected` selects an option by default.
- `name` is used when submitting the form.
- The label's `for` attribute should match the select element's `id`.