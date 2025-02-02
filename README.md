
/* Общие стили для всего документа */
body {
    font-family: Arial, sans-serif;
    font-size: 16px;
    margin: 0;
    padding: 0;
    background-color: #f5f5f5;
    color: #333;
}

/* Ссылка для перехода к основному содержимому */
a.skip-to-content {
    position: absolute;
    top: -40px;
    left: 10px;
    background: #0077cc;
    color: white;
    padding: 10px;
    z-index: 100;
}

a.skip-to-content:focus {
    top: 10px;
}

/* Стили для заголовка страницы */
header {
    background-color: #0077cc;
    color: white;
    padding: 20px;
    text-align: center;
}

/* Стили для навигационного меню */
nav {
    background-color: #005599;
    padding: 10px;
    display: inline-block;
    width: 80%;
}

nav ul {
    list-style-type: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: center;
}

nav ul li {
    /* Закомментировано существующее правило */
    /* display: block;
    width: 100%;
    padding: 10px;
    border-bottom: 1px solid #ddd; */
}

nav img {
    width: 10%;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

/* Стили для основного содержимого */
main {
    background-color: #ffffff;
    padding: 20px;
    font-size: 18px;
    max-width: 800px;
    margin: 20px auto;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    border-radius: 5px;
}

main#content {
    scroll-margin-top: 50px;
}

/* Стили для подвала страницы */
footer {
    background-color: #222;
    color: white;
    text-align: center;
    padding: 15px;
    position: relative;
    bottom: 0;
    width: 100%;
}

/* Стили для заголовков */
h1 {
    text-align: center;
    font-family: 'Georgia', serif;
    color: #0077cc;
}

/* Стили для класса grid */
.grid {
    display: grid;
    grid-template-columns: 40% 40%;
    justify-content: center;
    align-items: center;
    row-gap: 20px;
}

.grid img {
    width: 100%;
}

/* Стили для flex-контейнера */
.flex {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
}

/* Стили для абзацев */
p {
    line-height: 1.6;
}
