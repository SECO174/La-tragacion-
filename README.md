<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>La Tragación</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 10px;
            padding: 20px;
            height: 50vh;
            background: linear-gradient(90deg, rgb(0, 0, 0) 50%, rgb(0, 0, 0) 50%);
            color: rgb(19, 18, 18);
        }
        .watermark {
            background-image: url('traga.jpg'); 
            background-repeat: no-repeat;
            background-position: center;
            background-size: cover;
            opacity: 0.1; 
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1; 
        }
        .content {
            background-color: rgba(255, 255, 255, 0.7);
            width: 250px;
            height: 250px;
            padding: 10px;
            border-radius: 10px;
            margin: 30px auto; 
            z-index: 1; 
        }
    </style>
</head>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Inicio de Sesión</title>
    
 <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f2f2f2;
        }
        .login-container {
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .login-container h1 {
            margin-bottom: 20px;
        }
        .login-container input {
            width: 95%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .login-container button {
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            width: 100%;
        }
    </style>
</head>
<body>
    <div class="login-container">
        <h1>Iniciar Sesión</h1>
        <form action="/login" method="post">
            <input type="email" id="email" name="email" placeholder="Correo Electrónico" required>
            <input type="password" id="password" name="password" placeholder="Contraseña" required>
            <button type="submit">Iniciar Sesión</button>
        </form>
    </div>
</body>
</html>
<body>
    <div class="watermark"></div>
    <div class="content">
        <h1>Bienvenido a la Tragación</h1>
        <p>Iniciar sesión para continuar al menu.</p>
    </div>
    <script>
    </script>
</body>
</html>
