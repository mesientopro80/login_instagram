<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login de Instagram</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="login-container">
        <div class="login-box">
            <div class="logo">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a5/Instagram_icon.png/1024px-Instagram_icon.png" alt="Instagram Logo">
            </div>
            <form class="login-form">
                <input type="text" placeholder="Teléfono, usuario o correo electrónico" required>
                <input type="password" placeholder="Contraseña" required>
                <button type="submit">Iniciar sesión</button>
            </form>
            <div class="divider">
                <hr>
                <span>O</span>
                <hr>
            </div>
            <div class="login-with-facebook">
                <button class="fb-login">Iniciar sesión con Facebook</button>
            </div>
            <a href="#" class="forgot-password">¿Olvidaste tu contraseña?</a>
        </div>
        <div class="signup-box">
            <p>¿No tienes una cuenta? <a href="#">Regístrate</a></p>
        </div>
    </div>
</body>
</html>
