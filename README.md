<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Пример кнопки регистрации</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            padding: 20px;
        }

        form {
            max-width: 400px; 
            margin: auto; 
        }

        label {
            display: block; 
            margin-bottom: 5px;
        }

        input {
            width: 100%;
            padding: 10px; 
            margin-bottom: 15px; 
            border: 1px solid #ccc; 
            border-radius: 4px; 
        }

        button {
            padding: 10px 15px;
            border: none; 
            border-radius: 4px; 
            background-color: #4CAF50; 
            color: white;
            cursor: pointer;
        }

        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <h1 id="register">Страница регистрации</h1>
    <form>
        <label for="username">Имя пользователя:</label>
        <input type="text" id="username" name="username" required>
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        
        <label for="password">Пароль:</label>
        <input type="password" id="password" name="password" required>
        
        <button type="submit">Зарегистрироваться</button>
    </form>
</body>
</html>

