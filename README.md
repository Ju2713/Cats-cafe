<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style/normalize.css">
    <link rel="stylesheet" href="style/main.css">
    <title>Котокафе "Лапка"</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ffc0cb;
        }
        header { background-color: #ffc0cb; 
                padding: 10 px; 
                display: flex; 
                justify-content: space-between; 
                align-items: center; 
        }
        header img { 
            height: 50 px; 
        }
        nav { 
            display: flex; 
            gap: 20 px; 
        }
        section { 
            padding: 20 px; 
            text-align: center; 
        }
        .two-images { 
            display: flex; 
            justify-content: center; 
            gap: 40 px; 
        }
        .fragment { 
            margin-top: 60 px; 
        }
        .fragment img { 
            width: 100 %; 
            max-width: 400 px; 
        }
        .photo-container {
            display: flex;
            flex-wrap: wrap;
            gap: 20 px;
            justify-content: center;
        }
        .photo-item {
            text-align: center;
            max-width: 300 px;
        }
        .photo-item img {
            width: 100 %;
            height: auto;
        }
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
    <main>
        <section>
            <h1>Добро пожаловать в Котакафе "Лапка"</h1>
            <img src="face.jpg" alt="Лицевая картинка Котакафе Лапка"> 
        </section>
        <section class="two-images">
            <img src="kitten.jpg" alt="Внутреннее убранство1"> 
            <img src="kitti.jpg" alt="Внутреннее убранство2"> 
        </section>
        <selection>
             <h1>Что интересного вы у нас найдете</h1>
             <p>Ассортимент, декор и персонал</p>
        </selection>
        <div class="fragment" id="decor">
            <h1>Декор</h1>
            <p>Наше кафе состоит из двух зон, украшенных кошачьими элементами. Первая зона само кафе, а вторая игровая, в которой вы можете провести время с нашими котиками.</p>
            <img src="decore.jpg" alt="Картинка декора"> 
        </div>
        <div class="fragment" id="menu">
            <h1>Напитки и десерты</h1>
            <p>В нашем кафе большой выбор горячих и холодных напитков. А также большой выбор десертов в кошачьей тематике.</p>
            <img src="desert.jpg" alt="Картинка напитков и десертов"> 
        </div>
        <div class="fragment" id="staff">
            <h1>Наш персонал</h1>
            <p>В кафе вас встретят прекрасные кошко-девушки. На протяжении всего вашего присутствия они будут сопровождать и радовать вас.</p>
            <img src="personal.jpg" alt="Картинка персонала"> 
        </div>
        <selection>
              <h1>Наши котики</h1>
              <div class="photo-container">
                  <div class="photo-item">
                      <img src="mar.jpg" alt="Кот 1"> 
                      <h1>Марципан</h1>
                      <p>Это элегантный и изысканный котик с очаровательной внешностью. Он очень культурный и скромный, любит играть с солнечными зайчиками и плюшевыми мышками. А его любимое лакомство лосось.</p>
                  </div>
                  <div class="photo-item">
                      <img src="nik.jpg" alt="Кот 2"> 
                      <h1>Никки</h1>
                      <p>Это гордая и независимая кошечка. Она любит лежать на коленках у гостей и нежиться на солнышке. Если вы захотите ее угостить, то знайте, ее любимое блюдо - куриная грудка.</p>
                  </div>
                  <div class="photo-item">
                      <img src="myr.jpg" alt="Кот 3"> 
                      <h1>Муро</h1>
                      <p>Это очень ласковый котик. Он любит спать на подоконнике, греясь на солнышке. Муро нравится, когда его гладят или чешут ему животик.  При желании можете покормить его креветками. </p>
                  </div>
                  <div class="photo-item">
                      <img src="kleo.jpg" alt="Кот 4"> 
                      <h1>Клео</h1>
                      <p>Это очень озорная сиамская принцесса. Она очень умная кошка, которая любит играть с лазерной указкой и гладиться об ноги посетителей. А угостить ее вы можете сливочным сыром.</p>
                  </div>
                  <div class="photo-item">
                      <img src="felix.jpg" alt="Кот 5"> 
                      <h1>Феликс</h1>
                      <p>Это важный джентльмен, любящий через окно наблюдать за птицами и играть с удочкой-дразнилкой. Он с радостью полежит у вас на коленях и погладится об все ваше тело. А если вы покормите его паштетом из креветок, он будет счастлив.</p>
                  </div>
                  <div class="photo-item">
                      <img src="mgo.jpg" alt="Кот 6"> 
                      <h1>Марго</h1>
                      <p>Очаровательная, но горделивая кошка, которая никошда сама не попросит ласки. Однако она будет рада полежать у вас на коленях. Особенно, если вы угостите ее паштетом из индейки.</p>
                  </div>
              </div>
        </selection>
    </main>
    <footer>
        <p>&copy; 2023 Котокафе "Лапка". Все права защищены.</p>
    </footer>
</body>
</html>
     
