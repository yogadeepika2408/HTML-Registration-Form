# HTML-Registration-Form
A simple HTML registration form with fields for username, email, password, and password confirmation.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration Form</title>
    <link rel="stylesheet" href="reg_form.css">
</head>
<body>
    <h2>Registration Form</h2>
    <form action="/submit" method="POST">
        <div>
            <label for="username">UserName:</label>
            <input type="text" id="username" name="username" required>
        </div>
        <div>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
        </div>
        <div>
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required>
        </div>
        <div>
            <label for="confirm-password">Confirm Password:</label>
            <input type="confirm-password" id="confirm-password" name="confirm-password" required>
        </div>
        <button type="submit">Register</button>
    </form>
</body>
</html>
