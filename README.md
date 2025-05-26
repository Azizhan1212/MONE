# MONE
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Вкусные Моменты | Блог о еде</title>
    <link rel="stylesheet" href="style.css">
    <!-- Для красивых иконок, например, иконок социальных сетей в будущем -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">
                <a href="#">Вкусные Моменты</a>
            </div>
            <nav>
                <ul>
                    <li><a href="#home">Главная</a></li>
                    <li><a href="#posts">Блог</a></li>
                    <li><a href="#gallery">Галерея</a></li>
                    <li><a href="#about">О нас</a></li>
                    <li><a href="#contact">Контакты</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <section id="home" class="hero-section">
            <div class="container">
                <div class="hero-content">
                    <h1>Добро пожаловать во Вкусные Моменты!</h1>
                    <p>Здесь мы делимся рецептами, кулинарными вдохновениями и историями о еде, которая согревает душу.</p>
                    <a href="#posts" class="button">Читать блог</a>
                </div>
            </div>
        </section>

        <section id="posts" class="latest-posts">
            <div class="container">
                <h2>Последние публикации</h2>
                <div class="post-grid">
                    <!-- Пример карточки поста -->
                    <div class="post-card">
                        <img src="https://via.placeholder.com/400x250?text=Уютный+суп" alt="Уютный суп">
                        <div class="card-content">
                            <h3>Рецепт уютного осеннего супа</h3>
                            <p class="post-meta">15 октября 2023 | Категория: Супы</p>
                            <p>Приготовьте этот согревающий суп, который идеально подходит для прохладных вечеров...</p>
                            <a href="#" class="read-more">Читать далее</a>
                        </div>
                    </div>
                    <div class="post-card">
                        <img src="https://via.placeholder.com/400x250?text=Домашняя+выпечка" alt="Домашняя выпечка">
                        <div class="card-content">
                            <h3>Ароматная домашняя выпечка для всей семьи</h3>
                            <p class="post-meta">10 октября 2023 | Категория: Выпечка</p>
                            <p>Откройте для себя простые рецепты, которые наполнят ваш дом запахом свежего хлеба...</p>
                            <a href="#" class="read-more">Читать далее</a>
                        </div>
                    </div>
                    <div class="post-card">
                        <img src="https://via.placeholder.com/400x250?text=Кофе+и+десерты" alt="Кофе и десерты">
                        <div class="card-content">
                            <h3>Идеальные десерты к утреннему кофе</h3>
                            <p class="post-meta">5 октября 2023 | Категория: Десерты</p>
                            <p>Побалуйте себя и своих близких этими легкими и вкусными десертами...</p>
                            <a href="#" class="read-more">Читать далее</a>
                        </div>
                    </div>
                </div>
                <div class="button-center">
                    <a href="#" class="button outline">Все посты</a>
                </div>
            </div>
        </section>

        <section id="gallery" class="image-gallery">
            <div class="container">
                <h2>Наша фотогалерея</h2>
                <div class="gallery-grid">
                    <div class="gallery-item">
                        <img src="https://via.placeholder.com/600x400?text=Салат+с+авокадо" alt="Салат с авокадо">
                    </div>
                    <div class="gallery-item">
                        <img src="https://via.placeholder.com/600x400?text=Домашний+хлеб" alt="Домашний хлеб">
                    </div>
                    <div class="gallery-item">
                        <img src="https://via.placeholder.com/600x400?text=Свежие+фрукты" alt="Свежие фрукты">
                    </div>
                    <div class="gallery-item">
                        <img src="https://via.placeholder.com/600x400?text=Кофейный+напиток" alt="Кофейный напиток">
                    </div>
                    <div class="gallery-item">
                        <img src="https://via.placeholder.com/600x400?text=Паста+с+овощами" alt="Паста с овощами">
                    </div>
                    <div class="gallery-item">
                        <img src="https://via.placeholder.com/600x400?text=Ягодный+пирог" alt="Ягодный пирог">
                    </div>
                </div>
            </div>
        </section>

        <!-- Вы можете добавить секции "О нас" и "Контакты" по аналогии -->
        <section id="about" class="about-section">
            <div class="container">
                <h2>О нашем блоге</h2>
                <p>Мы верим, что еда — это не просто топливо, а источник радости, комфорта и единения. Наш блог создан для того, чтобы делиться этой философией и помогать вам открывать новые горизонты вкуса и кулинарного творчества.</p>
                <p>Присоединяйтесь к нам в этом вкусном приключении!</p>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2024 Вкусные Моменты. Все права защищены.</p>
            <div class="social-links">
                <!-- Пример иконок социальных сетей -->
                <a href="#" target="_blank"><i class="fab fa-facebook-f"></i></a>
                <a href="#" target="_blank"><i class="fab fa-instagram"></i></a>
                <a href="#" target="_blank"><i class="fab fa-pinterest-p"></i></a>
            </div>
        </div>
    </footer>
</body>
</html>
/* Общие стили и переменные для "уютного" стиля */
:root {
    --primary-color: #A37B5F; /* Мягкий коричневый */
    --secondary-color: #D16B5A; /* Приглушенный красный/оранжевый */
    --accent-color: #8BC34A; /* Мягкий зеленый */
    --text-color: #4A4A4A; /* Темно-серый для основного текста */
    --light-text-color: #6C6C6C; /* Светлее для мета-информации */
    --background-light: #FDFBFC; /* Очень светлый фон, почти кремовый */
    --background-dark: #333; /* Для футера */
    --card-background: #FFFFFF;
    --border-color: #E0E0E0; /* Легкий серый для границ */

    --font-heading: 'Georgia', serif; /* Или любой другой приятный serif шрифт */
    --font-body: 'Arial', sans-serif; /* Или 'Open Sans', 'Roboto' */

    --spacing-sm: 10px;
    --spacing-md: 20px;
    --spacing-lg: 40px;
}

body {
    font-family: var(--font-body);
    margin: 0;
    padding: 0;
    background-color: var(--background-light);
    color: var(--text-color);
    line-height: 1.6;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 var(--spacing-md);
}

h1, h2, h3, h4, h5, h6 {
    font-family: var(--font-heading);
    color: var(--primary-color);
    margin-bottom: var(--spacing-sm);
}

h1 { font-size: 3em; }
h2 { font-size: 2.5em; }
h3 { font-size: 1.8em; }

a {
    color: var(--secondary-color);
    text-decoration: none;
    transition: color 0.3s ease;
}

a:hover {
    color: var(--primary-color);
}

/* Кнопки */
.button {
    display: inline-block;
    background-color: var(--secondary-color);
    color: white;
    padding: var(--spacing-sm) var(--spacing-md);
    border-radius: 5px;
    font-weight: bold;
    transition: background-color 0.3s ease, transform 0.2s ease;
    border: 2px solid var(--secondary-color);
}

.button:hover {
    background-color: #BF5B4A; /* Чуть темнее */
    transform: translateY(-2px);
}

.button.outline {
    background-color: transparent;
    color: var(--secondary-color);
    border: 2px solid var(--secondary-color);
}

.button.outline:hover {
    background-color: var(--secondary-color);
    color: white;
}

.button-center {
    text-align: center;
    margin-top: var(--spacing-lg);
}


/* Хедер */
header {
    background-color: var(--background-light);
    padding: var(--spacing-md) 0;
    box-shadow: 0 2px 5px rgba(0,0,0,0.05);
    position: sticky;
    top: 0;
    z-index: 1000;
}

header .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo a {
    font-family: var(--font-heading);
    font-size: 2.2em;
    font-weight: bold;
    color: var(--primary-color);
    text-decoration: none;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
}

nav ul li {
    margin-left: var(--spacing-md);
}

nav ul li a {
    font-weight: bold;
    color: var(--text-color);
    padding: 5px 0;
    position: relative;
}

nav ul li a::after {
    content: '';
    position: absolute;
    width: 0;
    height: 2px;
    background-color: var(--secondary-color);
    bottom: 0;
    left: 0;
    transition: width 0.3s ease;
}

nav ul li a:hover::after {
    width: 100%;
}

/* Секция Hero */
.hero-section {
    background: linear-gradient(rgba(253,251,252,0.8), rgba(253,251,252,0.8)), url('https://via.placeholder.com/1500x700?text=Фон+Уютная+Кухня') no-repeat center center/cover;
    text-align: center;
    padding: 100px var(--spacing-md);
    margin-bottom: var(--spacing-lg);
    color: var(--text-color);
    border-radius: 8px; /* Немного скругляем края */
    margin: var(--spacing-lg) auto;
}

.hero-content h1 {
    font-size: 3.5em;
    color: var(--primary-color);
    margin-bottom: var(--spacing-sm);
    text-shadow: 1px 1px 2px rgba(0,0,0,0.05);
}

.hero-content p {
    font-size: 1.3em;
    max-width: 800px;
    margin: 0 auto var(--spacing-md);
    color: var(--light-text-color);
}

/* Секция последних постов */
.latest-posts, .image-gallery, .about-section {
    padding: var(--spacing-lg) 0;
    margin-bottom: var(--spacing-lg);
}

.latest-posts h2, .image-gallery h2, .about-section h2 {
    text-align: center;
    margin-bottom: var(--spacing-lg);
    color: var(--primary-color);
}

.post-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: var(--spacing-lg);
}

.post-card {
    background-color: var(--card-background);
    border-radius: 8px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.08);
    overflow: hidden;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.post-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 15px rgba(0,0,0,0.12);
}

.post-card img {
    width: 100%;
    height: 250px;
    object-fit: cover;
    display: block;
}

.post-card .card-content {
    padding: var(--spacing-md);
}

.post-card h3 {
    margin-top: 0;
    margin-bottom: var(--spacing-sm);
    color: var(--text-color);
}

.post-meta {
    font-size: 0.9em;
    color: var(--light-text-color);
    margin-bottom: var(--spacing-sm);
}

.post-card p {
    font-size: 1em;
    margin-bottom: var(--spacing-md);
    color: var(--text-color);
}

.read-more {
    display: inline-block;
    color: var(--secondary-color);
    font-weight: bold;
    text-decoration: none;
    position: relative;
    padding-bottom: 2px;
}

.read-more::after {
    content: '';
    position: absolute;
    width: 0;
    height: 1px;
    background-color: var(--secondary-color);
    bottom: 0;
    left: 0;
    transition: width 0.3s ease;
}

.read-more:hover::after {
    width: 100%;
}


/* Галерея изображений */
.gallery-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: var(--spacing-md);
}

.gallery-item {
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.gallery-item:hover {
    transform: scale(1.02);
    box-shadow: 0 6px 15px rgba(0,0,0,0.15);
}

.gallery-item img {
    width: 100%;
    height: 300px; /* Фиксированная высота для галереи */
    object-fit: cover;
    display: block;
}

/* Секция "О нас" (дополнительная) */
.about-section {
    background-color: var(--card-background);
    border-radius: 8px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.05);
    padding: var(--spacing-lg) var(--spacing-md);
    text-align: center;
    max-width: 900px;
    margin: var(--spacing-lg) auto;
}

.about-section p {
    font-size: 1.1em;
    margin-bottom: var(--spacing-sm);
}


/* Футер */
footer {
    background-color: var(--background-dark);
    color: white;
    text-align: center;
    padding: var(--spacing-md) 0;
    margin-top: var(--spacing-lg);
    font-size: 0.9em;
}

footer .container {
    display: flex;
    flex-direction: column;
    align-items: center;
}

.social-links a {
    color: white;
    font-size: 1.5em;
    margin: 0 10px;
    transition: color 0.3s ease;
}

.social-links a:hover {
    color: var(--secondary-color);
}


/* Медиа-запросы для адаптивности */
@media (max-width: 768px) {
    .container {
        padding: 0 var(--spacing-sm);
    }

    header .container {
        flex-direction: column;
    }

    .logo {
        margin-bottom: var(--spacing-sm);
    }

    nav ul {
        flex-wrap: wrap;
        justify-content: center;
    }

    nav ul li {
        margin: 5px 10px;
    }

    .hero-content h1 {
        font-size: 2.5em;
    }

    .hero-content p {
        font-size: 1.1em;
    }

    h2 {
        font-size: 2em;
    }

    .post-grid, .gallery-grid {
        grid-template-columns: 1fr; /* Один столбец на маленьких экранах */
    }

    .gallery-item img {
        height: 250px;
    }
}

@media (max-width: 480px) {
    .hero-content h1 {
        font-size: 2em;
    }
}


