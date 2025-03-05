<!DOCTYPE!>
<html lang="ru">
    <body>
    This is another-page.html
    <a href="/">go back to index.html</a>
    </body>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Котокафе "Лапка"</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #FFC0CB;
        }
header { background-color: #f0f0f0; padding: 10 px; display: flex; justify-content: space-between; align-items: center; }
        header img { height: 50 px; }
        nav { display: flex; gap: 20 px; }
        section { padding: 20 px; text-align: center; }
        .two-images { display: flex; justify-content: center; gap: 20 px; }
        .fragment { margin-top: 40 px; }
        .fragment img { width: 100 %; max-width: 400 px; }
    </style>
</head>
<body>

<header>
    <img src="logotip.jpg" alt="Логотип Котакафе Лапка"> 
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
    <img src="face.jpg" alt="Лицевая картинка Котакафе Лапка"> 
</section>

<section class="two-images">
    <img src="kitten.jpg" alt="Внутреннее убранство1"> 
    <img src="kitti.jpg" alt="Внутреннее убранство2"> 
</section>

<p>Что интересного вы у нас найдете</p>
<p>Ассортимент, декор и персонал</p>

<div class="fragment" id="decor">
    <h2>Декор</h2>
    <p>Наше кафе состоит из двух зон, украшенных кошачьими элементами. Первая зона само кафе, а вторая игровая, в которой вы можете провести время с нашими котиками.</p>
    <img src="decore.jpg" alt="Картинка декора"> 
</div>

<div class="fragment" id="menu">
    <h2>Напитки и десерты</h2>
    <p>В нашем кафе большой выбор горячих и холодных напитков. А также большой выбор десертов в кошачьей тематике.</p>
    <img src="desert.jpg" alt="Картинка напитков и десертов"> 
</div>
<div class="fragment" id="staff">
    <h2>Наш персонал</h2>
    <p>В кафе вас встретят прекрасные кошко-девушки. На протяжении всего вашего присутствия они будут сопровождать и радовать вас.</p>
    <img src="staff-image.jpg" alt="Картинка персонала"> 
</div>

</body>
</html>
