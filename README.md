# Karatel-test
Karatel.com
<!DOCTYPE html>
<html lang="ru">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta
      name="description"
      content="KARATEL TEST — современный игровой проект в стиле Black Russia с автомобилями, сервером, новостями, личным кабинетом и администрацией."
    />
    <title>KARATEL TEST</title>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800;900&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <div class="page-shell">
      <header class="topbar">
        <div class="container nav-wrap">
          <div class="brand" aria-label="KARATEL TEST">
            <span class="brand-mark">K</span>
            <span>KARATEL TEST</span>
          </div>

          <nav class="main-nav" aria-label="Основная навигация">
            <a href="#home">Главная</a>
            <a href="#servers">Серверы</a>
            <a href="#news">Новости</a>
            <a href="#auth">Вход</a>
            <a href="#support">Поддержка</a>
          </nav>

          <div class="nav-actions">
            <button class="ghost-btn">Профиль</button>
            <button class="primary-btn">Играть</button>
          </div>
        </div>
      </header>

      <main>
        <section class="hero" id="home">
          <div class="hero-overlay"></div>
          <div class="container hero-content">
            <div class="hero-copy">
              <span class="eyebrow">BLACK RUSSIA / GTA STYLE</span>
              <h1>Карьера, улицы, адреналин и жизнь в городе.</h1>
              <p>
                KARATEL TEST — это открытый игровой мир с реалистичными автомобилями,
                нелинейными заданиями, атмосферой ночного мегаполиса и динамикой,
                которая держит игрока в напряжении каждый час.
              </p>
              <div class="hero-actions">
                <a href="#servers" class="primary-btn">Выбрать сервер</a>
                <a href="#download" class="ghost-btn">Скачать лаунчер</a>
              </div>
              <ul class="hero-stats">
                <li><strong>24/7</strong><span>онлайн</span></li>
                <li><strong>3</strong><span>активных сервера</span></li>
                <li><strong>12k+</strong><span>игроков</span></li>
              </ul>
            </div>

            <div class="hero-panel">
              <div class="status-card glass-card">
                <div class="status-head">
                  <span class="status-dot"></span>
                  <span>Статус проекта</span>
                </div>
                <div class="status-body">
                  <div>
                    <small>Сервер</small>
                    <strong>Night City</strong>
                  </div>
                  <div>
                    <small>Карта</small>
                    <strong>Open World 1.9</strong>
                  </div>
                  <div>
                    <small>Режим</small>
                    <strong>Classic RP</strong>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </section>

        <section class="section" id="servers">
          <div class="container">
            <div class="section-header">
              <span class="eyebrow">Список серверов</span>
              <h2>Выбери стиль игры</h2>
            </div>

            <div class="server-grid">
              <article class="server-card featured">
                <div class="server-topline">
                  <span class="badge orange">Рекомендуем</span>
                  <span class="players">1287 онлайн</span>
                </div>
                <h3>Night City</h3>
                <p>Город с бешеным темпом, плотной экономикой, рейдами и динамикой событий.</p>
                <ul>
                  <li>Ставки на бизнес</li>
                  <li>Автомобили и тюнинг</li>
                  <li>Улицы и преступность</li>
                </ul>
                <button class="primary-btn full">Подключиться</button>
              </article>

              <article class="server-card">
                <div class="server-topline">
                  <span class="badge">Classic</span>
                  <span class="players">712 онлайн</span>
                </div>
                <h3>Metro Drift</h3>
                <p>Фокус на гонках, скорости, кастомизации и живых уличных заездах.</p>
                <ul>
                  <li>Трофейные машины</li>
                  <li>Дрифт-гонки</li>
                  <li>Карьера и репутация</li>
                </ul>
                <button class="ghost-btn full">Подробнее</button>
              </article>

              <article class="server-card">
                <div class="server-topline">
                  <span class="badge">Hardcore</span>
                  <span class="players">455 онлайн</span>
                </div>
                <h3>Shadow District</h3>
                <p>Люди, которые любят риск, бандитские маршруты и непростой ритм города.</p>
                <ul>
                  <li>Ночные рейды</li>
                  <li>Темные сделки</li>
                  <li>Сложная экономика</li>
                </ul>
                <button class="ghost-btn full">Подробнее</button>
              </article>
            </div>
          </div>
        </section>

        <section class="section alt" id="news">
          <div class="container">
            <div class="section-header">
              <span class="eyebrow">Новости проекта</span>
              <h2>Что происходит в мире KARATEL</h2>
            </div>

            <div class="news-grid">
              <article class="news-item card">
                <div class="news-image news-1"></div>
                <div class="news-content">
                  <span class="news-date">15.11.2026</span>
                  <h3>Добавлены новые модели автомобилей и улучшения метеорологической системы.</h3>
                  <p>Теперь в городе появилось больше транспорта, а уровень погоды стал ещё живее и атмосфернее.</p>
                </div>
              </article>

              <article class="news-item card">
                <div class="news-image news-2"></div>
                <div class="news-content">
                  <span class="news-date">08.11.2026</span>
                  <h3>Обновлён серверный тикет поддержки и система клубных событий.</h3>
                  <p>События стали больше, а система наград — прозрачнее и понятнее для игроков.</p>
                </div>
              </article>

              <article class="news-item card">
                <div class="news-image news-3"></div>
                <div class="news-content">
                  <span class="news-date">01.11.2026</span>
                  <h3>Запущен сезон тюнинга: новые комплектующие, задний свет и мелкая кастомизация.</h3>
                  <p>Игроки получили расширенный набор деталей и ещё больше вариантов для сборки уникального авто.</p>
                </div>
              </article>
            </div>
          </div>
        </section>

        <section class="section auth-section" id="auth">
          <div class="container auth-grid">
            <div class="auth-panel card">
              <span class="eyebrow">Регистрация</span>
              <h3>Создай аккаунт</h3>
              <form class="auth-form">
                <label>
                  <span>Никнейм</span>
                  <input type="text" placeholder="Введите ник" />
                </label>
                <label>
                  <span>Email</span>
                  <input type="email" placeholder="example@mail.ru" />
                </label>
                <label>
                  <span>Пароль</span>
                  <input type="password" placeholder="Минимум 8 символов" />
                </label>
                <button type="submit" class="primary-btn full">Зарегистрироваться</button>
              </form>
            </div>

            <div class="auth-panel card">
              <span class="eyebrow">Вход</span>
              <h3>Добро пожаловать обратно</h3>
              <form class="auth-form">
                <label>
                  <span>Логин</span>
                  <input type="text" placeholder="Ваш логин / email" />
                </label>
                <label>
                  <span>Пароль</span>
                  <input type="password" placeholder="Ваш пароль" />
                </label>
                <div class="auth-row">
                  <label class="checkbox"><input type="checkbox" /> Запомнить меня</label>
                  <a href="#">Забыли пароль?</a>
                </div>
                <button type="submit" class="ghost-btn full">Войти</button>
              </form>
            </div>
          </div>
        </section>

        <section class="section profile-section">
          <div class="container">
            <div class="section-header">
              <span class="eyebrow">Личный кабинет</span>
              <h2>Профиль игрока</h2>
            </div>

            <div class="profile-layout card">
              <div class="profile-overview">
                <div class="avatar-ring">
                  <div class="avatar">KT</div>
                </div>
                <div>
                  <span class="profile-label">Игровой ник</span>
                  <h3>NightRider_77</h3>
                  <p>Уровень 42 • VIP 4 • Офицер клуба</p>
                </div>
              </div>

              <div class="profile-metrics">
                <div class="metric">
                  <span>Деньги</span>
                  <strong>2 450 000 ₽</strong>
                </div>
                <div class="metric">
                  <span>Авто</span>
                  <strong>14</strong>
                </div>
                <div class="metric">
                  <span>Репутация</span>
                  <strong>9.8</strong>
                </div>
                <div class="metric">
                  <span>Заданий</span>
                  <strong>186</strong>
                </div>
              </div>
            </div>
          </div>
        </section>

        <section class="section download-section" id="download">
          <div class="container download-box card">
            <div>
              <span class="eyebrow">Лаунчер</span>
              <h2>Скачай APK для Android</h2>
              <p>
                Быстрый старт, автоматическая проверка обновлений и доступ к серверу с любого смартфона.
              </p>
            </div>
            <div class="download-actions">
              <button class="primary-btn large">Скачать APK</button>
              <small>Версия 2.4.1 • 71 МБ</small>
            </div>
          </div>
        </section>

        <section class="section support-section" id="support">
          <div class="container">
            <div class="section-header">
              <span class="eyebrow">Поддержка игроков</span>
              <h2>Частые вопросы и помощь</h2>
            </div>

            <div class="faq-grid">
              <details open class="faq-item card">
                <summary>Как войти на сервер?</summary>
                <p>После регистрации откройте раздел «Вход» и выберите нужный сервер, после чего активируйте игровой клиент.</p>
              </details>

              <details class="faq-item card">
                <summary>Есть ли поддержка для Android?</summary>
                <p>Да. Для всех устройств Android доступен отдельный лаунчер, который автоматически обновляет клиент и сохраняет прогресс.</p>
              </details>

              <details class="faq-item card">
                <summary>Как получить VIP / бонусы?</summary>
                <p>VIP и бонусные привилегии выдаются за активность, донаты и участие в игровых событиях проекта.</p>
              </details>

              <details class="faq-item card">
                <summary>Где писать в техподдержку?</summary>
                <p>Напишите в тикет через форму поддержки либо в Telegram-канал проекта, доступный в разделе помощи.</p>
              </details>
            </div>
          </div>
        </section>

        <section class="section admin-panel-section">
          <div class="container admin-box card">
            <div class="admin-head">
              <div>
                <span class="eyebrow">Панель администратора</span>
                <h2>Личный кабинет владельца и администраторов</h2>
              </div>
              <button class="primary-btn" id="adminToggle">Показать панель</button>
            </div>

            <div class="admin-panel" id="adminPanel" hidden>
              <div class="admin-stats">
                <div class="metric">
                  <span>Игроков онлайн</span>
                  <strong>1842</strong>
                </div>
                <div class="metric">
                  <span>Предупреждений</span>
                  <strong>28</strong>
                </div>
                <div class="metric">
                  <span>Банлист</span>
                  <strong>9</strong>
                </div>
                <div class="metric">
                  <span>Анонсы</span>
                  <strong>12</strong>
                </div>
              </div>

              <div class="admin-actions">
                <button class="ghost-btn">Управление событиями</button>
                <button class="ghost-btn">Бан / Разбан</button>
                <button class="ghost-btn">Редактор новостей</button>
                <button class="ghost-btn">Шаблоны сообщений</button>
              </div>
            </div>
          </div>
        </section>
      </main>

      <footer class="footer">
        <div class="container footer-wrap">
          <div>
            <div class="brand" aria-label="KARATEL TEST">
              <span class="brand-mark">K</span>
              <span>KARATEL TEST</span>
            </div>
            <p>Открытый мир, стиль и энергия ночного города.</p>
          </div>

          <div class="footer-links">
            <a href="#servers">Серверы</a>
            <a href="#news">Новости</a>
            <a href="#auth">Регистрация</a>
            <a href="#support">Поддержка</a>
          </div>
        </div>
      </footer>
    </div>

    <script src="script.js"></script>
  </body>
</html>















































































































































































































































































































