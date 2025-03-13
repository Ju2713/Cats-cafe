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
             line-height: 1.6;
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
        nav a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
            margin: 0 10px;
            transition: color 0.3s ease;
        }
        nav a:hover {
            color: #ff69b4;
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
         .cta-button {
            display: inline-block;
            margin: 20 px auto;
            padding: 10 px 20 px;
            background-color: #ff69b4;
            color: white;
            text-decoration: none;
            border-radius: 5 px;
            font-size: 16 px;
            transition: background-color 0.3 s ease;
        }
        .cta-button:hover {
            background-color: #ff1493;
        }
        .popup {
            display: none;
            position: fixed;
            top: 50 %;
            left: 50 %;
            transform: translate (-50 %, -50 %);
            background-color: white;
            padding: 20 px;
            box-shadow: 0 4 px 8 px rgba (0, 0, 0, 0.2);
            border-radius: 10 px;
            z-index: 1000;
            text-align: center;
        }
        .popup img {
            width: 100 px;
            height: auto;
            margin-bottom: 10 px;
            border-radius: 10 px;
        }
        .popup p {
            font-size: 18 px;
            margin: 10 px 0;
        }
        .overlay {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100 %;
            height: 100 %;
            background-color: rgba (0, 0, 0, 0.5);
            z-index: 999;
        }
        .close-btn {
            display: inline-block;
            margin-top: 10 px;
            padding: 5 px 10 px;
            background-color: #ff69b4;
            color: white;
            border: none;
            border-radius: 5 px;
            cursor: pointer;
            font-size: 14 px;
            transition: background-color 0.3 s ease;
        }
        .close-btn:hover {
            background-color: #ff1493;
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
        </nav>
    </header>
    <main>
        <section>
            <h1>Добро пожаловать в Котакафе "Лапка"</h1>
            <img src="face.jpg" alt="Лицевая картинка Котакафе Лапка"> 
            <a href="#our-cats" class="cta-button">Котики</a>
            <button id="helpButton" class="cta-button">Помочь</button>
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
        <p>&copy; 2025 Котокафе "Лапка". Все права защищены.</p>
    </footer>
    <div id="popup" class="popup">
        <img src="cat-help.jpg" alt="Котик, который нуждается в помощи">
        <p>Если хотите помочь, позвоните нам: <strong>+7 938 908 55 13</strong></p>
        <button id="closePopup" class="close-btn">Закрыть</button>
    </div>
    <div id="overlay" class="overlay"></div>
    <script>
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const targetId = this.getAttribute('href').substring(1);
                const targetElement = document.getElementById(targetId);
                if (targetElement) {
                    targetElement.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });
        const helpButton = document.getElementById('helpButton');
        const popup = document.getElementById('popup');
        const overlay = document.getElementById('overlay');
        const closePopup = document.getElementById('closePopup');
        helpButton.addEventListener('click', () => {
            popup.style.display = 'block';
            overlay.style.display = 'block';
        });
        closePopup.addEventListener('click', () => {
            popup.style.display = 'none';
            overlay.style.display = 'none';
        });
        overlay.addEventListener('click', () => {
            popup.style.display = 'none';
            overlay.style.display = 'none';
        });
    </script>
</body>
</html>
     
