# -<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Котокафе "Лапка"</title>
    <style>
        body {
            font-family: Oswald, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ff69b4;
        }
        
        .header {
            background-color: #c133a7;
            color: white;
            padding: 20px;
            text-align: center;
        }
        
        nav {
            background-color: #930b7a;
            padding: 10px;
        }
        
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px;
        }
        
        .content {
            padding: 20px;
            display: flex;
        }
        
        .menu-section {
            flex: 1;
            padding: 20px;
            background-color: white;
            border: 1px solid #ddd;
            box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
        }
        
        .contact-section {
            flex: 1;
            padding: 20px;
            background-color: white;
            border: 1px solid #ddd;
            box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
        }
        
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Котокафе "Лапка"</h1>
        <p>Вкусная еда для ваших особенных моментов</p>
    </div>
    
    <nav>
        <a href="#home">Главная</a>
        <a href="#menu">Меню</a>
        <a href="#contacts">Контакты</a>
    </nav>
    
    <div class="content">
        <div class="menu-section">
            <h2>Наше мен</h2>
            <h3>Завтраки</h3>
            <ul>
                <li>Омлет с сыром - 250₽</li>
                <li>Тосты с авокадо - 300₽</li>
                <li>Каша овсяная - 200₽</li>
            </ul>
            
            <h3>Основные блюда</h3>
            <ul>
                <li>Паста карбонара - 500₽</li>
                <li>Куриное филе - 450₽</li>
                <li>Рыбное филе - 550₽</li>
            </ul>
            
            <h3>Десерты</h3>
            <ul>
                <li>Тирамису - 350₽</li>
                <li>Чизкейк - 300₽</li>
                <li>Мороженое - 200₽</li>
            </ul>
        </div>
        
        <div class="contact-section">
            <h2>Контакты</h2>
            <p>Адрес: ул. Центральная, 123</p>
            <p>Телефон: +7 (999) 123-45-67</p>
            <p>Email: cafe@example.com</p>
            <p>Часы работы:</p>
            <p>Пн-Вс: 8:00 - 22:00</p>
            
            <h3>Карта проезда</h3>
            <div id="map" style="width: 100%; height: 300px;"></div>
        </div>
    </div>
    
    <footer>
        &copy; 2025 Котакафе "Лапка"`
