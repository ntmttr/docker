<h1>Лабораторна робота 1: Знайомство з Docker</h1>

Клонування репозиторію з прикладом Todo-додатку з GitHub. Команда git clone завантажує вихідний код проекту для подальшої роботи з ним.

<p align="center">
<img src="Screenshots/ (1).png" alt="(1)"/>
</p>

Запуск першого Docker контейнера з вітальним повідомленням. Команда docker run завантажує образ welcome-to-docker та запускає його на порту 8080:80.

<p align="center">
<img src="Screenshots/ (2).png" alt="(2)"/>
</p>

Перегляд стану запущеного контейнера та його файлової системи через Docker Desktop. Вкладка Files показує структуру файлів всередині контейнера.

<p align="center">
<img src="Screenshots/ (3).png" alt="(3)"/>
</p>

Перевірка конфігурації контейнера через вкладку Inspect. Відображаються налаштування середовища та команди запуску NGINX.

<p align="center">
<img src="Screenshots/ (4).png" alt="(4)"/>
</p>

Успішне завершення завантаження та запуску першого контейнера з вітальним повідомленням "Congratulations!!!".

<p align="center">
<img src="Screenshots/ (5).png" alt="(5)"/>
</p>

Запуск всіх контейнерів додатку за допомогою Docker Compose. Команда docker compose watch запускає сервіси phpMyAdmin, proxy та mysql, які необхідні для роботи Todo-додатку.

<p align="center">
<img src="Screenshots/ (6).png" alt="(6)"/>
</p>

Перший запуск Todo-додатку з привітальним повідомленням "Hello world!". Інтерфейс дозволяє додавати нові елементи списку завдань.

<p align="center">
<img src="Screenshots/ (7).png" alt="(7)"/>
</p>

Перегляд коду файлу getGreeting.js, який містить логіку генерації випадкових привітальних повідомлень. Масив GREETINGS містить морську тематику.

<p align="center">
<img src="Screenshots/ (8).png" alt="(8)"/>
</p>

Оновлений інтерфейс додатку з випадково вибраним привітанням "Whalecome!". Форма для додавання нових елементів залишається порожньою.

<p align="center">
<img src="Screenshots/ (9).png" alt="(9)"/>
</p>

Код компонента AddNewItemForm.jsx, який відповідає за форму додавання нових елементів. Компонент містить поле введення та кнопку підтвердження.

<p align="center">
<img src="Screenshots/ (10).png" alt="(10)"/>
</p>

Інтерфейс Todo-додатку з текстом привітання "Whalecome!" та порожньою формою для додавання нових завдань.

<p align="center">
<img src="Screenshots/ (11).png" alt="(11)"/>
</p>

Файл стилів index.scss, який визначає основні стилі додатку - колір фону, відступи та шрифт Lato.

<p align="center">
<img src="Screenshots/ (12).png" alt="(12)"/>
</p>

Оновлений інтерфейс додатку після застосування стилів - змінено колір фону на світло-блакитний.

<p align="center">
<img src="Screenshots/ (13).png" alt="(13)"/>
</p>

Створення нового репозиторію на Docker Hub з назвою getting-started-todo-app. Налаштування публічного доступу для пошуку в Docker Hub.

<p align="center">
<img src="Screenshots/ (14).png" alt="(14)"/>
</p>

Процес збірки та завантаження образів додатку до Docker Hub. Команда docker image ls показує список локальних образів з їх розмірами та часом створення.

<p align="center">
<img src="Screenshots/ (15).png" alt="(15)"/>
</p>

Завантаження створеного образу Todo-додатку до Docker Hub. Команда docker push публікує образ maksimprokopenko/getting-started-todo-app з тегом latest у віддалений репозиторій.

<p align="center">
<img src="Screenshots/ (16).png" alt="(16)"/>
</p>
