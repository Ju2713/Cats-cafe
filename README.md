# -<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Котокафе "Лапка"</title>
    <style>
        body {
            
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ff69b4;
        }
header { background-color: #f0f0f0; padding: 10px; display: flex; justify-content: space-between; align-items: center; }
        header img { height: 50px; }
        nav { display: flex; gap: 15px; }
        section { padding: 20px; text-align: center; }
        .two-images { display: flex; justify-content: center; gap: 20px; }
        .fragment { margin-top: 40px; }
        .fragment img { width: 100%; max-width: 400px; }
    </style>
</head>
<body>

<header>
    <img src="logo.png" alt="Логотип Котакафе Лапка"> <!-- Не забудьте заменить на ваш логотип -->
    <nav>
        <a href="#help">Помочь</a>
        <a href="#contacts">Контакты</a>
        <a href="#cats">Котики</a>
        <a href="#login">Войти</a>
        <a href="#reserve">Забронировать</a>
    </nav>
</header>

<section>
    <h1>Котакафе Лапка</h1>
    <img src="main-image.jpg" alt="Картинка Котакафе Лапка"> <!-- Основная картинка -->
</section>

<section class="two-images">
    <img src="image1.jpg" alt="Картинка 1"> <!-- Первая картинка -->
    <img src="image2.jpg" alt="Картинка 2"> <!-- Вторая картинка -->
</section>

<div class="fragment" id="decor">
    <h2>Декор</h2>
    <p>Наше кафе оформлено в уютном стиле с использованием натуральных материалов и мягкого освещения.</p>
    <img src="decor-image.jpg" alt="Картинка декора"> <!-- Картинка декора -->
</div>

<div class="fragment" id="menu">
    <h2>Напитки и десерты</h2>
    <p>Мы предлагаем широкий выбор кофе, чая и сладостей, которые вы сможете попробовать в компании кошек.</p>
    <img src="drinks-desserts.jpg" alt="Картинка напитков и десертов"> <!-- Картинка напитков и десертов -->
</div>

<div class="fragment" id="staff">
    <h2>Наш персонал</h2>
    <p>Наши сотрудники всегда готовы помочь вам и сделать ваш визит незабываемым!</p>
    <img src="staff-image.jpg" alt="Картинка персонала"> <!-- Картинка персонала -->
</div>

</body>
</html>
