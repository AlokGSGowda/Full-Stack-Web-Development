# Radio Input Element

## Definition

The radio input element is used to let the user select **only one option** from a group of options.

## Syntax

```html
<input type="radio" id="option1" name="option" value="value">
<label for="option1">Option 1</label>
```

## Example

```html
<input type="radio" id="male" name="gender" value="male">
<label for="male">Male</label>

<input type="radio" id="female" name="gender" value="female">
<label for="female">Female</label>

<input type="radio" id="other" name="gender" value="other">
<label for="other">Other</label>
```

## Attributes

### `type="radio"`

Specifies that the input element is a radio button.

```html
<input type="radio">
```

### `id`

Gives a unique identifier to the radio button.

```html
<input type="radio" id="male">
```

### `name`

Groups radio buttons together. Radio buttons with the **same `name`** allow only one option to be selected.

```html
<input type="radio" name="gender" value="male">
<input type="radio" name="gender" value="female">
```

### `value`

Specifies the value sent when the radio button is selected.

```html
<input type="radio" name="gender" value="male">
```

### `checked`

Selects a radio button by default.

```html
<input type="radio" name="gender" value="male" checked>
```

### `label for`

The `for` attribute connects the `<label>` with the `<input>` using the input's `id`.

```html
<input type="radio" id="male" name="gender">
<label for="male">Male</label>
```

Clicking the **Male** label will also select the radio button.

## Example Form

```html
<form>

    <input type="radio" id="male" name="gender" value="male">
    <label for="male">Male</label>

    <input type="radio" id="female" name="gender" value="female">
    <label for="female">Female</label>

    <input type="radio" id="other" name="gender" value="other">
    <label for="other">Other</label>

    <button type="submit">Submit</button>

</form>
```

## Note

- Radio buttons are used when the user should select **only one option**.
- Radio buttons must have the **same `name`** to form a group.
- The `id` of the input should match the `for` value of the label.
- `checked` selects an option by default.
- `value` is submitted when the radio button is selected.