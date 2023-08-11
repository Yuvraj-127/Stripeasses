<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" type="text/css" href="style.css">
</head>

<body>
    <div class="container">
        <h2>Login</h2>
        <form action="login.php" method="POST">
            <label for="name">Username</label>
            <input type="email" name="email" placeholder="Email" required>
            <label for="password">Password</label>
            <input type="password" name="password" placeholder="Password" required>
            <button type="submit">Login</button>
        </form>
        <p>New to My App? <a href="Register.html">SignUp</a></p>
    </div>
</body>

</html>
