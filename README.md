<!DOCTYPE html>
<html lang="uk">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>WebStudio</title>
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/modern-normalize/1.1.0/modern-normalize.min.css"
    />
    <link rel="stylesheet" href="./css/styles.css" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Raleway:wght@700&family=Roboto:wght@400;500;700;900&display=swap"
      rel="stylesheet"
    />
  </head>

  <body>
    <header>
      <div class="container main-nav">
        <nav class="main-nav">
          <a href="./index.html" class="logo"><span class="logo-text">Web</span>Studio</a>
          <ul class="site-nav list">
            <li class="nav">
              <a href="#" class="link">Студія</a>
            </li>
            <li class="nav">
              <a href="./portfolio.html" class="link">Портфоліо</a>
            </li>
            <li class="nav">
              <a href="#" class="link">Контакти</a>
            </li>
          </ul>
        </nav>
        <ul class="contacts list">
          <li class="contact">
            <a href="#" class="link-contacts">info@devstudio.com</a>
          </li>
          <li class="contact">
            <a href="#" class="link-contacts">+38 096 111 11 11</a>
          </li>
        </ul>
      </div>
    </header>
    <main>
      <section class="section hero">
        <div class="container">
          <h1 class="hero-title">Ефективні рішення для вашого бізнесу</h1>
          <button type="button" class="button">Замовити послугу</button>
        </div>
      </section>
      <section class="section">
        <div class="container">
          <h2 class="visually-hidden">Наші переваги</h2>
          <ul class="section-features list">
            <li class="features">
              <h3 class="features-title">Увага до дітей</h3>
              <p class="text">
                Ідейні міркування, і навіть початок повсякденної роботи з формування позиції.
              </p>
            </li>
            <li class="features">
              <h3 class="features-title">Пунктуальність</h3>
              <p class="text">
                Завдання організації, особливо рамки і місце навчання кадрів тягне у себе.
              </p>
            </li>
            <li class="features">
              <h3 class="features-title">Планування</h3>
              <p class="text">Так само консультація з широким активом значною мірою зумовлює.</p>
            </li>
            <li class="features">
              <h3 class="features-title">Сучасні технології</h3>
              <p class="text">
                Значимість цих проблем настільки очевидна, що реалізація планових завдань.
              </p>
            </li>
          </ul>
        </div>
      </section>
      <section class="section">
        <div class="container">
          <h2 class="section-work">Чим ми займаємося</h2>
          <ul class="work list">
            <li class="work-img">
              <img
                src="./images/img1.jpg"
                alt="Людина пише код на планшеті з клавіатури"
                width="370"
              />
            </li>
            <li class="work-img">
              <img
                src="./images/img2.jpg"
                alt="Людина розробляє макет телефона на комп'ютері"
                width="370"
              />
            </li>
            <li class="work-img">
              <img src="./images/img3.jpg" alt="Людина працює на планшеті" width="370" />
            </li>
          </ul>
        </div>
      </section>
      <section class="section section-team">
        <div class="container">
          <h2 class="team">Наша команда</h2>
          <ul class="items-team list">
            <li class="team-image">
              <img
                src="./images/img4.jpg"
                alt="Чоловік в коричневій сорочці посміхається"
                width="270"
              />
              <div class="card">
                <h3 class="title">Ігор Дем'яненко</h3>
                <p class="subtitle">Product Designer</p>
              </div>
            </li>
            <li class="team-image">
              <img src="./images/img5.jpg" alt="Дівчина блондинка посміхається" width="270" />
              <div class="card">
                <h3 class="title">Ольга Рєпіна</h3>
                <p class="subtitle">Frontend Developer</p>
              </div>
            </li>
            <li class="team-image">
              <img src="./images/img6.jpg" alt="Чоловік в білій сорочці посміхається" width="270" />
              <div class="card">
                <h3 class="title">Микола Тарасов</h3>
                <p class="subtitle">Marketing</p>
              </div>
            </li>
            <li class="team-image">
              <img
                src="./images/img7.jpg"
                alt="Чоловік в чорній сорочці склав руки перед собою "
                width="270"
              />
              <div class="card">
                <h3 class="title">Михайло Єрмаков</h3>
                <p class="subtitle">UI Designer</p>
              </div>
            </li>
          </ul>
        </div>
      </section>
    </main>
    <footer class="footer">
      <div class="container">
        <a href="./index.html" class="logo-footer"><span class="logo-web">Web</span>Studio</a>
        <address>
          <ul class="link-items list">
            <li class="link-adress">
              <a
                href="https://goo.gl/maps/CPtrU1FHBa2aNyZL9"
                target="_blank"
                rel="noopener noreferrer nofollow"
                class="link-adress"
                >м. Київ, пр-т Лесі Українки, 26</a
              >
            </li>
            <li class="link-name">
              <a href="#" class="link-item">info@devstudio.com</a>
            </li>
            <li class="link-name">
              <a href="#" class="link-item">+38 096 111 11 11</a>
            </li>
          </ul>
        </address>
      </div>
    </footer>
  </body>
</html>
