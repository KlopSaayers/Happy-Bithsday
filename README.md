<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>С Днем Рождения, Мама!</title>
    <link href="https://fonts.googleapis.com/css2?family=Pacifico&family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to right, #ff7e5f, #feb47b);
            color: #fff;
            text-align: center;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
            overflow: hidden;
            position: relative;
        }
        header {
            background: rgba(0, 0, 0, 0.6);
            padding: 20px;
            position: relative;
            z-index: 10;
            border-bottom: 2px solid #ffcc00;
        }
        h1 {
            font-family: 'Pacifico', cursive;
            font-size: 3.5em;
            margin: 0;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
            animation: fadeIn 1s ease-in-out;
        }
        .message {
            font-size: 1.5em;
            margin: 20px 0;
            animation: slideIn 1s ease-in-out;
            text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.5);
            max-width: 800px;
            margin-left: auto;
            margin-right: auto;
            line-height: 1.6;
            padding: 0 20px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 10px;
            padding: 30px;
        }
        .heart {
            color: #ff69b4;
            font-size: 2em;
        }
        footer {
            background: rgba(0, 0, 0, 0.6);
            padding: 20px;
            position: relative;
            z-index: 10;
            margin-top: auto;
            border-top: 2px solid #ffcc00;
        }
        footer p {
            margin: 0;
            font-size: 1.2em;
        }
        /* Боковые эффекты */
        .side-effect {
            position: absolute;
            top: 0;
            bottom: 0;
            width: 50px;
            background: linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0.3));
            z-index: 0;
            animation: pulse 3s infinite;
        }
        .left {
            left: 0;
            border-radius: 0 10px 10px 0;
        }
        .right {
            right: 0;
            border-radius: 10px 0 0 10px;
        }
        @keyframes pulse {
            0% { opacity: 0.5; }
            50% { opacity: 1; }
            100% { opacity: 0.5; }
        }
    </style>
</head>
<body>
    <div class="side-effect left"></div>
    <div class="side-effect right"></div>
    
    <header>
        <h1>С Днем Рождения, Мама!</h1>
    </header>
    
    <div class="message">
        <p>Дорогая мама,</p>
        <p>Сегодня твой день, и я хочу поздравить тебя с этим замечательным событием!</p>
        <p>Ты — самый светлый и добрый человек в моей жизни. Спасибо за твою безграничную любовь и поддержку!</p>
        <p>Желаю тебе море счастья, океан здоровья и горы исполнения всех твоих мечт!</p>
        <p>С любовью и нежностью, твой сын.</p>
        <p class="heart">❤️❤️❤️</p>
    </div>

    <footer>
        <p>© 2024 Поздравления от сына</p>
    </footer>
</body>
</html>
