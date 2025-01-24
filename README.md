<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Сайт класса</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        header {
            background: #4CAF50;
            color: white;
            padding: 10px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #333;
        }
        nav a {
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background: #4CAF50;
        }
        .container {
            padding: 20px;
        }
        .schedule, .news, .gallery {
            margin: 20px 0;
        }
        .gallery img {
            max-width: 100%;
            height: auto;
        }
        footer {
            text-align: center;
            padding: 10px 0;
            background: #333;
            color: white;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Добро пожаловать на сайт нашего класса!</h1>
    </header>

    <nav>
        <a href="#schedule">Расписание</a>
        <a href="#news">Новости</a>
        <a href="#gallery">Галерея</a>
        <a href="#contacts">Контакты</a>
    </nav>

    <div class="container">
        <section id="schedule" class="schedule">
            <h2>Расписание на понедельник для 8а</h2>
            <table border="1" cellpadding="10">
                <tr>
                    <th>Время</th>
                    <th>Предмет</th>
                    <th>Учитель</th>
                </tr>
                <tr>
                    <td>08:00 - 08:40</td>
                    <td>Алгебра</td>
                    <td>Ирина Анатольевна</td>
                </tr>
                <tr>
                    <td>08:55 - 09:35</td>
                    <td>Русский язык</td>
                    <td>Ольга Роальдовна</td>
                </tr>
                <tr>
                    <td>09:50 - 10:30</td>
                    <td>Черчение</td>
                    <td>Вера Генадьевна</td>
                </tr>
                <tr>
                    <td>10:45 - 11:25</td>
                    <td>Музыка</td>
                    <td>Светлана Никаноровна</td>
                </tr>
                <tr>
                    <td>11:40 - 12:20</td>
                    <td>Алгебра</td>
                    <td>Ирина Анатольевна</td>
                </tr>
                <tr>
                    <td>12:35 - 13:15</td>
                    <td>Физика</td>
                    <td>Наталья Юрьевна</td>
                </tr>
                <tr>
                    <td>13:30 - 14:10</td>
                    <td>Английский</td>
                    <td>Наталья Викторовна</td>
                </tr>
            </table>
        </section>

        <section id="news" class="news">
            <h2>Новости</h2>
            <article>
                <h3>Полезно</h3>
                <p>Не забудьте во вторник 1 группа идет на хайтек. А 2 группа идет в четверг.</p>
            </article>
            <article>
                <h3>Для талантов</h3>
                <p>В пятницу после уроков идет электротехника. Незабывааем!</p>
            </article>
        </section>

        <section id="gallery" class="gallery">
            <h2>Домашние задания и интересные новости</h2>
            <img src="example.jpg" alt="Сегодня был дистант, поэтому ничего интересного не происходило">
            <p>Дз на сегодня:</p>
            <p>по алгебре: фото с заданиями в 8а</p>
            <p>по химии: готовится к самостоятельной работе (параграфы 32, 33, задания 3)</p>
            <p>по биологии: параграф 32 (в АИСе написано)</p>
            <p>по литературе: доделать работу</p>
            <p>по русскому: номер 278 с. 136</p>
        </section>

        <section id="contacts" class="contacts">
            <h2>Контакты</h2>
            <p>Классный руководитель: Ирина Анатольевна</p>
            <p>Email: <a href="mailto:Legendary190710@gmail.com">Legendary190710@gmail.com</a></p>
            <p>Телефон: +7 (992) 339-37-64</p>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Наш класс. Все права защищены.</p>
    </footer>
</body>
</html>
