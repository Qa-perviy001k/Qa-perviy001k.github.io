<!DOCTYPE html>
<html lang="ru">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Сайт портфолио</title>
    <link rel="stylesheet" href="./css/main.css">
    <link rel="stylesheet" href="./css/media.css">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&display=swap" rel="stylesheet">
</head>

<body class="root">

    <header class="header" id="header">
        <h1 class="header__title">Ruslan Skvortsov</h1>
        <p class="header__subtitle">Я - QA ENGINEER (ТЕСТИРОВЩИК ВЕБ- МОБИЛЬНОГО КЛИЕНТА, БЭКЕНДА, SQL БАЗЫ ДАННЫХ) </p>
        <a href="#portfolio">
            <img class="header__arrow" src="./images/header/chevron-down.svg" alt="#"></img>
        </a>
    </header>


    <footer class="footer">
        <div class="root__container">
            <ul class="footer__row">
                <li class="footer__copyright footer__col">
                    <h3 class="footer__copyright-name">© Ruslan Skvortsov</h3>
                    <p class="footer__copyright-description">™ QA ENGINEER</p>
                </li>
                <li class="footer__icons footer__col">
                    <p class="footer__icons-title">Контакты для связи:</p>
                    <div class="footer__icon-list">
                        <a href="https://t.me/perviy001k" target="_blank">
                            <img src="./images/footer/tele.png" alt="#">
                        </a>
                        <a href="https://wa.me/79277043373" target="_blank">
                            <img src="./images/footer/wats.png" alt="#">
                        </a>
                        <a href="https://github.com/Qa-perviy001k" target="_blank">
                            <img src="./images/footer/git.png" alt="#">
                        </a>
                    </div>
                </li>
                <li class="footer__contacts footer__col">
                    <a class="footer__contacts-btn" href="https://t.me/perviy001k" target="_blank"
                        class="footer__btn">Связаться Telegram</a>
                    <p class="footer__contacts-description"></p>
                </li>
            </ul>
        </div>
    </footer>

    <!-- Библиотеки и плагины -->
    <script src="./libs/jquery/jquery-3.6.0.min.js"></script>
    <script src="./libs/vide/jquery.vide.min.js"></script>

    <!-- Собственные скрипты и вызовы библиотек -->
    <script src="./js/main.js"></script>
</body>

</html>
