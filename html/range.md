# Range Input Element

## Definition

The range input element is used to let the user select a **value from a specified range** using a slider.

## Syntax

```html
<input type="range" min="0" max="100">
```

## Example

```html
<label for="volume">Volume:</label>
<input type="range" id="volume" name="volume" min="0" max="100">
```

## Attributes

### `type="range"`

Specifies that the input is a range slider.

```html
<input type="range">
```

### `min`

Specifies the minimum value of the range.

```html
<input type="range" min="0">
```

### `max`

Specifies the maximum value of the range.

```html
<input type="range" max="100">
```

### `value`

Specifies the default value of the slider.

```html
<input type="range" min="0" max="100" value="50">
```

### `step`

Specifies the amount by which the value changes when the slider is moved.

```html
<input type="range" min="0" max="100" step="10">
```

### `name`

Specifies the name of the input and is used when submitting form data.

```html
<input type="range" name="volume">
```

### `id`

Gives a unique identifier to the input element.

```html
<input type="range" id="volume">
```

### `for`

The `for` attribute of `<label>` connects the label with the range input using the input's `id`.

```html
<label for="volume">Volume:</label>
<input type="range" id="volume" name="volume">
```

## Example Form

```html
<form>

    <label for="volume">Volume:</label>

    <input
        type="range"
        id="volume"
        name="volume"
        min="0"
        max="100"
        value="50"
        step="10">

    <button type="submit">Submit</button>

</form>
```

## Note

- `<input type="range">` creates a slider.
- `min` defines the minimum value.
- `max` defines the maximum value.
- `value` sets the default value.
- `step` defines the increment between values.
- `name` is used when submitting the form.