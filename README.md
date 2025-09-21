# portfolio-demo
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Моё Портфолио</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f4f4f4; }
        header { background: #4CAF50; color: white; padding: 30px 20px; text-align: center; }
        nav { background: #333; text-align: center; }
        nav a { color: white; margin: 0 15px; text-decoration: none; padding: 14px; display: inline-block; }
        nav a:hover { background: #575757; }
        section { padding: 40px 20px; max-width: 1000px; margin: auto; }
        .gallery { display: flex; flex-wrap: wrap; gap: 20px; justify-content: center; }
        .gallery img { width: 250px; height: 150px; object-fit: cover; border-radius: 5px; }
        form { display: flex; flex-direction: column; max-width: 400px; margin: auto; }
        input, textarea { margin-bottom: 10px; padding: 10px; border-radius: 4px; border: 1px solid #ccc; }
        button { padding: 10px; border: none; background: #4CAF50; color: white; font-weight: bold; cursor: pointer; }
        footer { background: #333; color: white; text-align: center; padding: 15px; }
    </style>
</head>
<body>
    <header>
        <h1>Привет! Я — [Ваше имя]</h1>
        <p>Добро пожаловать в моё онлайн-портфолио</p>
    </header>
    <nav>
        <a href="#home">Главная</a>
        <a href="#portfolio">Портфолио</a>
        <a href="#contact">Контакты</a>
    </nav>
    <section id="home">
        <h2>Обо мне</h2>
        <p>Я создаю красивые сайты и цифровые проекты. Здесь вы можете увидеть мои работы и связаться со мной.</p>
    </section>
    <section id="portfolio">
        <h2>Мои работы</h2>
        <div class="gallery">
            <img src="https://via.placeholder.com/250x150.png?text=Проект+1" alt="Проект 1">
            <img src="https://via.placeholder.com/250x150.png?text=Проект+2" alt="Проект 2">
            <img src="https://via.placeholder.com/250x150.png?text=Проект+3" alt="Проект 3">
            <img src="https://via.placeholder.com/250x150.png?text=Проект+4" alt="Проект 4">
        </div>
    </section>
    <section id="contact">
        <h2>Связаться со мной</h2>
        <form action="mailto:your-email@example.com" method="post" enctype="text/plain">
            <input type="text" name="name" placeholder="Ваше имя" required>
            <input type="email" name="email" placeholder="Ваш email" required>
            <textarea name="message" placeholder="Сообщение" required></textarea>
            <button type="submit">Отправить</button>
        </form>
    </section>
    <footer>
        <p>© 2025 [Ваше имя]</p>
    </footer>
</body>
</html>
