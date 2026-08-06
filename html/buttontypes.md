# Button Types

## 1. Submit Button

### Definition

The `submit` type sends the form data to the server.

### Syntax

```html
<button type="submit">Submit</button>
```

### Example

```html
<form action="/register">
    <button type="submit">Register</button>
</form>
```

---

## 2. Reset Button

### Definition

The `reset` type clears all the input fields in a form.

### Syntax

```html
<button type="reset">Reset</button>
```

### Example

```html
<form>
    <button type="reset">Reset</button>
</form>
```

---

## 3. Button

### Definition

The `button` type creates a normal clickable button without submitting or resetting the form.

### Syntax

```html
<button type="button">Click Me</button>
```

### Example

```html
<button type="button">Show Message</button>
```

## Important Points

- `submit` → Submits the form.
- `reset` → Clears all form fields.
- `button` → Used for custom actions with JavaScript.