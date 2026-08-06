# HTML Forms

## Form

The `<form>` element is used to collect user input and send it to a server.

### Syntax

```html
<form action="">
    ...
</form>
```

---

## Action Attribute

The `action` attribute specifies where the form data is sent after submission.

### Syntax

```html
<form action="/submit">
```

### Example

```html
<form action="https://example.com/register">
```

### Important Points

- Specifies the destination URL.
- Executes when the form is submitted.
- If omitted, the form submits to the current page.

---

## Input Element

The `<input>` element is used to create different types of input fields.

### Syntax

```html
<input type="">
```

---

## Common Input Types

### Text

```html
<input type="text">
```

Used to enter text.

---

### Password

```html
<input type="password">
```

Hides the entered characters.

---

### Email

```html
<input type="email">
```

Accepts email addresses.

---

### Number

```html
<input type="number">
```

Accepts numeric values.

---

### Date

```html
<input type="date">
```

Displays a date picker.

---

### Checkbox

```html
<input type="checkbox">
```

Allows multiple selections.

---

### Radio

```html
<input type="radio">
```

Allows only one option to be selected from a group.

---

### Submit

```html
<input type="submit" value="Submit">
```

Submits the form.

---

### Reset

```html
<input type="reset">
```

Resets all form fields.

---

### Button

```html
<input type="button" value="Click Me">
```

Creates a clickable button.

---

## Common Attributes

| Attribute | Description |
|-----------|-------------|
| `type` | Specifies the input type. |
| `name` | Identifies the input when form data is submitted. |
| `value` | Sets the default value. |
| `placeholder` | Displays hint text inside the input field. |
| `required` | Makes the field mandatory. |
| `readonly` | Prevents editing of the field. |
| `disabled` | Disables the input field. |
| `maxlength` | Limits the number of characters. |
| `min` | Minimum value for number/date inputs. |
| `max` | Maximum value for number/date inputs. |

---

## Example

```html
<form action="/register">

    <input
        type="text"
        name="username"
        placeholder="Enter username"
        required>

    <input
        type="password"
        name="password"
        required>

    <input
        type="email"
        name="email">

    <input type="submit" value="Register">

</form>
```