

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Expense Tracker Application</title>
</head>
<body>
    <header>
        <h1>Welcome to Expense Tracker</h1>
    </header>

    <section>
        <h2>About Expense Tracker</h2>
        <p>Expense Tracker helps you manage your finances efficiently.</p>
    </section>

    <section>
        <h2>Registration Form</h2>
        <form action="#" method="POST">
            <label for="name">Name:</label><br>
            <input type="text" id="name" name="name" required><br><br>

            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" required><br><br>

            <label for="phone">Phone Number:</label><br>
            <input type="tel" id="phone" name="phone" required><br><br>

            <input type="submit" value="Register">
        </form>
    </section>

    <section>
        <h2>User Information</h2>
        <table border="1">
            <tr>
                <th>Name</th>
                <th>Email</th>
                <th>Phone Number</th>
            </tr>
            <tr>
                <td>John Doe</td>
                <td>john.doe@example.com</td>
                <td>(123) 456-7890</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>jane.smith@example.com</td>
                <td>(987) 654-3210</td>
            </tr>
        </table>
    </section>

    <section>
        <h2>Sample Image</h2>
        <img src="image.jpg" alt="Sample Image" width="300">
    </section>

    <section>
        <h2>External Link</h2>
        <p>Check out <a href="https://google.com" target="_blank">Google</a>.</p>
    </section>

</body>
</html>
```

### Explanation:
1. **DOCTYPE and HTML Tag**: Defines the document type and starts the HTML structure.
2. **Head Section**: Contains metadata like `title`, `charset`, and `viewport`.
3. **Body Section**:
   - **Header**: Includes a heading (`<h1>`) for the main title.
   - **Paragraph**: Provides a brief description (`<p>`) about the application.
   - **Registration Form**: Includes a basic form (`<form>`) with fields for name, email, phone number, and a submit button.
   - **User Information Table**: Displays user information in a simple table (`<table>`).
   - **Image**: Shows a placeholder image (`<img>`).
   - **External Link**: Directs to an external site (Google in this case) using an anchor (`<a>`) tag with the `href` attribute.

