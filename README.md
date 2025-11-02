<!doctype html>
<html lang="ru">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Plastremont.kz — Ремонт пластиковых окон и дверей</title>
  <meta name="description" content="Ремонт пластиковых окон и дверей — монтаж, замена уплотнителя, навесов, стеклопакетов. Быстро и качественно." />
  <style>
    :root {
      --blue: #0670c8;
      --dark: #0b2433;
      --muted: #6b7a86;
      --card: #ffffff;
      --radius: 14px;
    }
    * { box-sizing: border-box; }
    body {
      font-family: Inter, Roboto, Arial, sans-serif;
      margin: 0;
      color: #122;
      line-height: 1.45;
      background: #f6f8fb;
    }
    .container { max-width: 1100px; margin: 0 auto; padding: 28px; }

    /* Header */
    header {
      background: linear-gradient(180deg, var(--blue), #0b6fbf);
      color: #fff;
      padding: 26px 0;
      border-radius: 12px;
    }
    .row { display: flex; align-items: center; justify-content: space-between; gap: 16px; }
    .brand { display: flex; align-items: center; gap: 14px; }
    .brand img {
      width: 56px;
      height: 56px;
      object-fit: cover;
      border-radius: 10px;
      background: #fff;
      padding: 6px;
    }
    h1.site-title { font-size: 28px; margin: 0; }
    .phone {
      font-weight: 600;
      background: rgba(255,255,255,0.12);
      padding: 10px 14px;
      border-radius: 10px;
    }

    /* Hero */
    .hero {
      display: grid;
      grid-template-columns: 1fr 420px;
      gap: 26px;
      align-items: center;
      margin-top: 20px;
    }
    .hero .intro { color: #fff; }
    .hero h2 { font-size: 36px; margin: 0 0 12px; }
    .hero p { margin: 0 0 18px; opacity: 0.95; }
    .cta {
      display: inline-block;
      padding: 12px 18px;
      border-radius: 10px;
      background: #fff;
      color: var(--blue);
      font-weight: 700;
      text-decoration: none;
    }
    .hero img { width: 100%; border-radius: 12px; display: block; }

    /* Services */
    section.services {
      margin-top: 30px;
      background: var(--card);
      padding: 22px;
      border-radius: 12px;
      box-shadow: 0 6px 20px rgba(11,20,30,0.06);
    }
    .services h3 { margin-top: 0; }
    .services-grid {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 12px;
      padding-top: 8px;
    }
    .service { display: flex; gap: 12px; align-items: flex-start; }
    .bullet {
      width: 10px;
      height: 10px;
      background: var(--blue);
      border-radius: 50%;
      margin-top: 6px;
    }

    /* About */
    .about {
      display: flex;
      gap: 18px;
      align-items: center;
      margin-top: 20px;
    }
    .about img {
      width: 180px;
      border-radius: 12px;
      object-fit: cover;
    }

    /* Gallery */
    .gallery {
      margin-top: 18px;
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 12px;
    }
    .gallery img {
      width: 100%;
      height: 120px;
      object-fit: cover;
      border-radius: 10px;
    }

    /* Contact */
    .contact {
      margin-top: 22px;
      display: grid;
      grid-template-columns: 1fr 360px;
      gap: 18px;
    }
    .card {
      background: var(--card);
      padding: 18px;
      border-radius: 12px;
      box-shadow: 0 6px 18px rgba(10,20,30,0.04);
    }
    form label {
      display: block;
      font-size: 14px;
      margin-bottom: 6px;
      color: var(--muted);
    }
    form input, form textarea {
      width: 100%;
      padding: 10px;
      border-radius: 8px;
      border: 1px solid #e6eef6;
      margin-bottom: 12px;
    }
    form button {
      background: var(--blue);
      color: #fff;
      border: none;
      padding: 12px 14px;
      border-radius: 10px;
      font-weight: 700;
      cursor: pointer;
    }

    footer {
      margin-top: 28px;
      text-align: center;
      color: var(--muted);
      font-size: 14px;
      padding-bottom: 40px;
    }

    @media (max-width: 980px) {
      .hero { grid-template-columns: 1fr; }
      .contact { grid-template-columns: 1fr; }
      .about { flex-direction: column; }
      .services-grid { grid-template-columns: 1fr; }
      .gallery { grid-template-columns: repeat(2, 1fr); }
    }
    @media (max-width: 560px) {
      .gallery { grid-template-columns: 1fr; }
    }
  </style>
</head>
<body>
  <header>
    <div class="container">
      <div class="row">
        <div class="brand">
          <img src="grok_image_l5qla7.jpg" alt="plastremont.kz logo" />
          <div>
            <div style="font-size:13px;opacity:0.9">Пластиковые окна и двери</div>
            <h1 class="site-title">plastremont.kz</h1>
          </div>
        </div>
        <div class="phone">+7 (700) 600 0415</div>
      </div>

      <div class="hero">
        <div class="intro">
          <h2>Ремонт пластиковых окон и дверей</h2>
          <p>Любой вид сложности — от замены уплотнителя до установки нового стеклопакета. Быстро и качественно по всему городу.</p>
          <a class="cta" href="#contact">Заказать выезд мастера</a>
        </div>
        <img src="hero.jpg" alt="Мастер ремонтирует окно">
      </div>
    </div>
  </header>

  <main class="container">
    <section class="services card" id="services">
      <h3>Наши услуги</h3>
      <div class="services-grid">
        <div class="service"><div class="bullet"></div>Установка поворотно-откидного открытия</div>
        <div class="service"><div class="bullet"></div>Замена уплотнителя</div>
        <div class="service"><div class="bullet"></div>Замена резинок на окна</div>
        <div class="service"><div class="bullet"></div>Замена навесов</div>
        <div class="service"><div class="bullet"></div>Пластиковые откосы</div>
        <div class="service"><div class="bullet"></div>Утепление, устранение продувания</div>
        <div class="service"><div class="bullet"></div>Замена стеклопакетов</div>
      </div>
    </section>

    <section class="about" id="about">
      <img src="team.jpg" alt="Команда Plastremont.kz">
      <div>
        <h3>О компании</h3>
        <p>Компания предоставляет качественный ремонт пластиковых окон и дверей любой сложности. Мы работаем быстро, аккуратно и даем гарантию на выполненные работы.</p>
      </div>
    </section>

    <section class="gallery" id="works">
      <img src="work1.jpg" alt="Пример работы">
      <img src="work2.jpg" alt="Пример работы">
      <img src="work3.jpg" alt="Пример работы">
    </section>

    <section class="contact" id="contact">
      <div class="card">
        <h3>Свяжитесь с нами</h3>
        <form>
          <label>Ваше имя</label>
          <input type="text" placeholder="Введите имя">
          <label>Телефон</label>
          <input type="text" placeholder="+7 (___) ___-____">
          <label>Комментарий</label>
          <textarea rows="3" placeholder="Опишите проблему..."></textarea>
          <button type="submit">Отправить заявку</button>
        </form>
      </div>
      <div class="card">
        <h3>Контакты</h3>
        <p>Телефон: <b>+7 (700) 600
