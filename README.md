!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Конструирование алгоритмов</title>
    <style>
        /* Сброс отступов и установка высоты body и html на 100% */
        html, body {
            margin: 0;
            padding: 0;
            height: 100%;
            font-family: Arial, sans-serif;
            color: #000000; /* Черный цвет текста */
            overflow: auto; /* Включаем прокрутку */
        }

        /* Анимация для фона */
        body {
            background: linear-gradient(270deg, #ff9a9e, #fad0c4, #fbc2eb, #a6c1ee, #84fab0);
            background-size: 400% 400%;
            animation: GradientBackground 15s ease infinite;
        }

        @keyframes GradientBackground {
            0% {
                background-position: 0% 50%;
            }
            50% {
                background-position: 100% 50%;
            }
            100% {
                background-position: 0% 50%;
            }
        }

        /* Контейнер для контента */
        .container {
            max-width: 800px;
            margin: 50px auto;
            padding: 20px;
            background-color: rgba(255, 255, 255, 0.9); /* Светлый фон для контраста */
            border-radius: 20px;
            backdrop-filter: blur(10px);
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.2);
        }

        /* Заголовок */
        h1 {
            font-size: 3em;
            text-align: center;
            margin-bottom: 20px;
            color: #000000; /* Черный цвет текста */
        }

        /* Текст */
        .content {
            font-size: 1.2em;
            line-height: 1.6;
            color: #000000; /* Черный цвет текста */
        }

        /* Кнопка "Тест" */
        .test-button {
            display: block;
            width: 200px;
            margin: 20px auto;
            padding: 15px;
            font-size: 1.2em;
            text-align: center;
            background-color: #1e90ff; /* Синий цвет кнопки */
            color: #ffffff; /* Белый цвет текста */
            border: none;
            border-radius: 10px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .test-button:hover {
            background-color: #0077cc; /* Темно-синий цвет при наведении */
        }

        /* Пример кода */
        pre {
            background-color: rgba(0, 0, 0, 0.1);
            padding: 10px;
            border-radius: 5px;
            overflow-x: auto;
            color: #000000; /* Черный цвет текста в блоке кода */
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Конструирование алгоритмов</h1>
        <div class="content">
            <h2>Что такое алгоритм?</h2>
            <p>
                Алгоритм — это последовательность четких шагов, которые нужно выполнить, чтобы решить задачу. Алгоритмы используются в программировании, математике и других науках.
            </p>
