<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Меню завтраков</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Приготовление блюд для моего лучшего и невероятного Марса Зюсиковича</h1>
        <p>Шеф-повар: Зюсичка</p>
        <p>Оплата принимается только поцелуями и обнимашками!</p>
    </header>

    <main>
        <h2>Выберите блюда:</h2>
        <ul class="menu-list">
            <li><a href="menu1.html">Блины со сгущёнкой и гречневая каша с сыром</a></li>
            <li><a href="menu2.html">Яйца с сосисками и драники с лососем</a></li>
            <li><a href="menu3.html">Тост с сыром и маслом, рисовая каша с тыквой</a></li>
            <li><a href="menu4.html">Авокадо-тост и чай с конфетами</a></li>
        </ul>
    </main>

    <footer>
        <p>Не всегда кухня работает в постоянном режиме, у шефа может быть разное настроение не по её собственному желанию.</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Меню завтраков</title>
    <link rel="stylesheet" href="styles.css">
    <script defer src="script.js"></script>
</head>
<body>
    <header>
        <h1>Меню завтраков</h1>
    </header>

    <main>
        <section class="dish">
            <h2>Блины со сгущёнкой</h2>
            <p>Нежные блины, пропитанные сладкой сгущёнкой – идеальный завтрак для сладкоежек.</p>
            <button onclick="orderDish('Блины со сгущёнкой')">Заказать</button>
        </section>

        <section class="dish">
            <h2>Гречневая каша с сыром</h2>
            <p>Питательная гречка с расплавленным сыром – вкусное и полезное начало дня.</p>
            <button onclick="orderDish('Гречневая каша с сыром')">Заказать</button>
        </section>

        <a href="index.html">Назад в меню</a>
    </main>
</body>
</html>
body {
    font-family: 'Georgia', serif;
    background-color: #f4e8d8;
    color: #5a3e2b;
    text-align: center;
}

header {
    background-color: #d4a373;
    padding: 20px;
    color: white;
}

.menu-list {
    list-style: none;
    padding: 0;
}

.menu-list li {
    margin: 15px 0;
}

.menu-list a {
    text-decoration: none;
    font-size: 20px;
    color: #5a3e2b;
}

.dish {
    background-color: white;
    padding: 20px;
    margin: 20px auto;
    width: 80%;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

button {
    background-color: #d4a373;
    color: white;
    padding: 10px;
    border: none;
    cursor: pointer;
    font-size: 18px;
    margin-top: 10px;
}

button:hover {
    background-color: #b3835c;
}
function orderDish(dishName) {
    alert(`Вы заказали: ${dishName}\nОплата: 3 поцелуя (в разные зоны) и объятия! ❤️`);
}
