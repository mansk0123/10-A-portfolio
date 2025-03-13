<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>10"A" сынып</title>
    <link rel="stylesheet" href="css/styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #FFFFFF; /* Белый фон */
            color: #333333; /* Темно-серый текст */
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #007BFF; /* Синий цвет шапки */
            color: white;
            padding: 20px 0;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            color: #007BFF; /* Синий цвет ссылок */
            text-decoration: none;
            font-weight: bold;
        }
        section {
            padding: 40px 20px;
            margin: 20px;
            background-color: #F8F9FA; /* Светло-серый фон секций */
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            color: #007BFF;
        }
        .student-card {
            background-color: #E9ECEF; /* Светло-серый фон карточек */
            color: #333333;
        }
        .student-card a {
            color: #007BFF;
        }
        .student-card a:hover {
            text-decoration: underline;
        }
        ul li {
            background: #E9ECEF;
            border-left: 5px solid #007BFF;
        }
        .class-photo {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 20px 0;
            border-radius: 8px;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <ul class="nav-links">
                <li><a href="#about">Сынып туралы</a></li>
                <li><a href="#students">Оқушылар</a></li>
                <li><a href="#achievements">Жетістіктер</a></li>
            </ul>
        </nav>
    </header>
    <section id="about" class="about">
        <h1>10-сынып туралы</h1>
        <p>РФММ мектебінің 10 “А” сыныбында қазіргі таңда 25 оқушы бар...</p>
        <h2>Сынып суреті</h2>
        <img src="./img/10A.jpeg" alt="Сынып суреті" class="class-photo">
    </section>
    <section id="students" class="students">
        <h2>Оқушылар</h2>
        <div class="student-list">
            <div class="student-card">
                <h3><a href="adiya.htm" target="_blank">Адия</a></h3>
            </div>
            <div class="student-card">
                <h3><a href="inform3.html" target="_blank">Алуа</a></h3>
            </div>
            <div class="student-card">
                <h3><a href="erasyl1.htm" target="_blank">Ерасыл</a></h3>
            </div>
        </div>
    </section>
    <section id="achievements" class="achievements">
        <h2>Жетістіктер</h2>
        <ul>
            <li>🏆 Республиканский этап Hippo Olympiad 2 место</li>
            <li>🏆 IMEC онлайн математика олимпиадасында қола жүлде</li>
        </ul>
    </section>
</body>
</html>
