# Textarea Element

## Definition

The `<textarea>` element is used to create a **multi-line text input field**.

## Syntax

```html
<textarea name="message"></textarea>
```

## Example

```html
<label for="message">Message:</label>

<textarea id="message" name="message"></textarea>
```

## Attributes

### `name`

Specifies the name of the textarea and is used when submitting form data.

```html
<textarea name="message"></textarea>
```

### `id`

Gives a unique identifier to the textarea.

```html
<textarea id="message"></textarea>
```

### `rows`

Specifies the visible number of rows in the textarea.

```html
<textarea rows="5"></textarea>
```

### `cols`

Specifies the visible width of the textarea in columns.

```html
<textarea cols="30"></textarea>
```

### `placeholder`

Displays a hint inside the textarea before the user enters text.

```html
<textarea placeholder="Enter your message"></textarea>
```

## Example Form

```html
<form>

    <label for="message">Message:</label>

    <textarea
        id="message"
        name="message"
        rows="5"
        cols="30"
        placeholder="Enter your message">
    </textarea>

    <button type="submit">Submit</button>

</form>
```

## Note

- `<textarea>` is used for **multi-line text input**.
- `rows` controls the visible height.
- `cols` controls the visible width.
- `placeholder` provides a hint to the user.
- `name` is used when submitting form data.
- The label's `for` attribute should match the textarea's `id`.