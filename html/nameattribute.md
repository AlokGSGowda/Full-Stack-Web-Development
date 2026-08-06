# Name Attribute

## Definition

The `name` attribute is used to identify an input field when form data is submitted to the server.

## Syntax

```html
<input type="text" name="username">
```

## Example

```html
<form action="/submit">

    <input type="text" name="username">

    <input type="password" name="password">

    <button type="submit">Login</button>

</form>
```

## Important Points

- Identifies the input field during form submission.
- The server uses the `name` to access the submitted value.
- Multiple input fields should have different `name` values.
- Without the `name` attribute, the input value is not sent to the server.

HTML search bar that redirects the user's search query to Google, use this code:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Google Search Redirect</title>
</head>
<body>

    <h2>Search on Google</h2>

    <form action="https://www.google.com/search" method="GET">
        <input
            type="text"
            name="q"
            placeholder="Search Google..."
            required>

        <button type="submit">Search</button>
    </form>

</body>
</html>
How it works
action="https://www.google.com/search" → Sends the form to Google Search.
method="GET" → Sends the search query in the URL.
name="q" → Google expects the search term in a parameter named q.

For example, if the user types:

HTML Forms

The browser redirects to:

https://www.google.com/search?q=HTML+Forms

which displays the Google search results.

This is a great example of how the action, method, and name attributes work together in an HTML form.