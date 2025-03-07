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
            background-color: #ffc0cb;
        }
header { background-color: #f0f0f0; padding: 10 px; display: flex; justify-content: space-between; align-items: center; }
        header img { height: 50 px; }
        nav { display: flex; gap: 20 px; }
        section { padding: 20 px; text-align: center; }
        .two-images { display: flex; justify-content: center; gap: 40 px; }
        .fragment { margin-top: 60 px; }
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

<h2>Что интересного вы у нас найдете</h2>
<p>Ассортимент, декор и персонал</p>

<div class="fragment" id="decor">
    <h3>Декор</h3>
    <p>Наше кафе состоит из двух зон, украшенных кошачьими элементами. Первая зона само кафе, а вторая игровая, в которой вы можете провести время с нашими котиками.</p>
    <img src="decore.jpg" alt="Картинка декора"> 
</div>

<div class="fragment" id="menu">
    <h3>Напитки и десерты</h3>
    <p>В нашем кафе большой выбор горячих и холодных напитков. А также большой выбор десертов в кошачьей тематике.</p>
    <img src="desert.jpg" alt="Картинка напитков и десертов"> 
</div>
<div class="fragment" id="staff">
    <h3>Наш персонал</h3>
    <p>В кафе вас встретят прекрасные кошко-девушки. На протяжении всего вашего присутствия они будут сопровождать и радовать вас.</p>
    <img src="personal.jpg" alt="Картинка персонала"> 
</div>
<h4>Наши котики</h4>
 <div class="photo-container">
        <div class="photo-item">
            <img src="mar.jpg" alt="Кот 1"> 
            <h5>Марципан</h5>
            <p>Это элегантный и изысканный котик с очаровательной внешностью. Он очень культурный и скромный, любит играть с солнечными зайчиками и плюшевыми мышками. А его любимое лакомство лосось.</p>
        </div>
        <div class="photo-item">
            <img src="nik.jpg" alt="Кот 2"> 
            <h5>Никки</h5>
            <p>Это гордая и независимая кошечка. Она любит лежать на коленках у гостей и нежиться на солнышке. Если вы захотите ее угостить, то знайте, ее любимое блюдо - куриная грудка.</p>
        </div>
        <div class="photo-item">
            <img src="myr.jpg" alt="Кот 3"> 
            <h5>Муро</h5>
            <p>Это очень ласковый котик. Он любит спать на подоконнике, греясь на солнышке. Муро нравится, когда его гладят или чешут ему животик.  При желании можете покормить его креветками. </p>
        </div>
        <div class="photo-item">
            <img src="cat4.jpg" alt="Кот 4"> <!-- Замените на свой путь к изображению -->
            <h5>Клео</h5>
            <p>Это очень озорная сиамская принцесса. Она очень умная кошка, которая любит играть с лазерной указкой и гладиться об ноги посетителей. А угостить ее вы можете сливочным сыром.</p>
        </div>
    </div>
</div>
</body>
</html>
