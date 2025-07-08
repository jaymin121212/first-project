# first-project
# project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Login Page</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            background: #f5f6fa;
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
            font-family: Arial, sans-serif;
        }
        .login-container {
            background: #fff;
            padding: 2rem 2.5rem;
            border-radius: 8px;
            box-shadow: 0 4px 24px rgba(0,0,0,0.08);
            width: 320px;
        }
        .login-container h2 {
            text-align: center;
            margin-bottom: 1.5rem;
            color: #333;
        }
        .login-container label {
            display: block;
            margin-bottom: 0.5rem;
            color: #555;
            font-size: 0.95rem;
        }
        .login-container input[type="text"],
        .login-container input[type="password"] {
            width: 100%;
            padding: 0.6rem;
            margin-bottom: 1.2rem;
            border: 1px solid #ccc;
            border-radius: 4px;
            font-size: 1rem;
            box-sizing: border-box;
        }
        .login-container button {
            width: 100%;
            padding: 0.7rem;
            background: #007bff;
            color: #fff;
            border: none;
            border-radius: 4px;
            font-size: 1rem;
            cursor: pointer;
            transition: background 0.2s;
        }
        .login-container button:hover {
            background: #0056b3;
        }
        .login-container .signup-link {
            display: block;
            text-align: center;
            margin-top: 1rem;
            color: #007bff;
            text-decoration: none;
            font-size: 0.95rem;
        }
        .login-container .signup-link:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="login-container">
        <div style="text-align: center; margin-bottom: 1rem;">
            <img src="https://upload.wikimedia.org/wikipedia/commons/a/a7/React-icon.svg" alt="Logo" style="width:48px; height:48px; display:block; margin:0 auto 0.5rem;">
            <h2 style="margin: 0;">Login</h2>
        </div>
        <form>
            <label for="username">Username</label>
            <input type="text" id="username" name="username" required>
            <label for="password">Password</label>
            <input type="password" id="password" name="password" required>
            <button type="submit">Login</button>
        </form>
        <a href="#" class="signup-link">Don't have an account? Sign up</a>
    </div>
</body>
</html>
