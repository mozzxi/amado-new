# amado-new
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Веб-разработчик — портфолио, проекты, контакты">
  <title>Web Developer | Портфолио</title>
  <link rel="stylesheet" href="styles/main.css">
  <link rel="icon" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'><text y='.9em' font-size='90'>💻</text></svg>">
</head>
<body>
  <header class="header">
    <nav class="nav container">
      <a href="#" class="nav__logo">&lt;dev/&gt;</a>
      <ul class="nav__list">
        <li><a href="#about" class="nav__link">Обо мне</a></li>
        <li><a href="#skills" class="nav__link">Навыки</a></li>
        <li><a href="#projects" class="nav__link">Проекты</a></li>
        <li><a href="#contact" class="nav__link">Контакты</a></li>
      </ul>
      <button class="theme-toggle" aria-label="Переключить тему">🌙</button>
    </nav>
  </header>

  <main>
    <!-- Hero -->
    <section class="hero">
      <div class="container">
        <h1 class="hero__title">
          Привет, я <span class="accent">Веб-разработчик</span>
        </h1>
        <p class="hero__subtitle">
          Создаю современные, быстрые и адаптивные веб-приложения
        </p>
        <div class="hero__actions">
          <a href="#projects" class="btn btn--primary">Смотреть проекты</a>
          <a href="#contact" class="btn btn--outline">Связаться</a>
        </div>
      </div>
    </section>

    <!-- About -->
    <section id="about" class="section">
      <div class="container">
        <h2 class="section__title">Обо мне</h2>
        <p class="section__text">
          Более 3 лет опыта в веб-разработке. Специализируюсь на создании
          SPA, REST API и адаптивных интерфейсов. Люблю чистый код и
          продуманный UX.
        </p>
      </div>
    </section>

    <!-- Skills -->
    <section id="skills" class="section section--alt">
      <div class="container">
        <h2 class="section__title">Навыки</h2>
        <div class="skills">
          <div class="skill-card">HTML5</div>
          <div class="skill-card">CSS3 / SCSS</div>
          <div class="skill-card">JavaScript (ES6+)</div>
          <div class="skill-card">TypeScript</div>
          <div class="skill-card">React / Vue</div>
          <div class="skill-card">Node.js</div>
          <div class="skill-card">Git / GitHub</div>
          <div class="skill-card">REST API</div>
        </div>
      </div>
    </section>

    <!-- Projects -->
    <section id="projects" class="section">
      <div class="container">
        <h2 class="section__title">Проекты</h2>
        <div class="projects">
          <article class="project-card">
            <h3>Todo App</h3>
            <p>SPA для управления задачами с localStorage.</p>
            <div class="project-card__tags">
              <span>JavaScript</span><span>CSS</span>
            </div>
            <a href="#" class="project-card__link">Демо →</a>
          </article>
          <article class="project-card">
            <h3>Weather Dashboard</h3>
            <p>Погодное приложение с OpenWeather API.</p>
            <div class="project-card__tags">
              <span>API</span><span>Fetch</span>
            </div>
            <a href="#" class="project-card__link">Демо →</a>
          </article>
          <article class="project-card">
            <h3>Portfolio Site</h3>
            <p>Адаптивный сайт-портфолио с тёмной темой.</p>
            <div class="project-card__tags">
              <span>HTML</span><span>CSS</span>
            </div>
            <a href="#" class="project-card__link">Демо →</a>
          </article>
        </div>
      </div>
    </section>

    <!-- Contact -->
    <section id="contact" class="section section--alt">
      <div class="container">
        <h2 class="section__title">Связаться со мной</h2>
        <form class="contact-form" id="contactForm">
          <input type="text" name="name" placeholder="Ваше имя" required>
          <input type="email" name="email" placeholder="Email" required>
          <textarea name="message" rows="5" placeholder="Сообщение" required></textarea>
          <button type="submit" class="btn btn--primary">Отправить</button>
        </form>
      </div>
    </section>
  </main>

  <footer class="footer">
    <div class="container">
      <p>© <span id="year"></span> Web Developer. Сделано с ❤️</p>
    </div>
  </footer>

  <script src="scripts/main.js"></script>
</body>
</html>
