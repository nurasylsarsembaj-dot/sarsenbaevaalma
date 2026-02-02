<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Алма Сарсенбаева — FOHOW</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background: #f6f9f3;
      color: #222;
    }

    .container {
      max-width: 900px;
      margin: 0 auto;
      padding: 40px 20px;
      text-align: center;
    }

    .leaves {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 180px;
      background: linear-gradient(to bottom, #e8f2dc, transparent);
      z-index: -1;
    }

    .avatar {
      width: 140px;
      height: 140px;
      border-radius: 50%;
      object-fit: cover;
      margin: 0 auto 20px;
      display: block;
      border: 4px solid #7bb321;
    }

    h1 {
      font-size: 22px;
      margin-bottom: 5px;
    }

    h2 {
      font-size: 16px;
      font-weight: normal;
      margin-top: 0;
    }

    h3 {
      margin-top: 30px;
    }

    .divider {
      margin: 25px auto;
      width: 80px;
      height: 1px;
      background: #ccc;
      position: relative;
    }

    .divider::after {
      content: "♥";
      position: absolute;
      top: -10px;
      left: 50%;
      transform: translateX(-50%);
      background: #f6f9f3;
      padding: 0 8px;
      font-size: 14px;
    }

    .highlight {
      color: #6fae1c;
      font-weight: bold;
      margin: 20px 0;
      line-height: 1.5;
    }

    ul {
      list-style: none;
      padding: 0;
      margin: 0;
    }

    ul li {
      margin: 12px 0;
      line-height: 1.5;
    }

    ul li::before {
      content: "◆";
      color: #2d74da;
      margin-right: 8px;
    }

    .faq {
      text-align: left;
      max-width: 600px;
      margin: 30px auto;
      font-weight: bold;
    }

    .faq p {
      margin: 12px 0;
    }

    .social-buttons {
      margin: 30px 0;
      display: flex;
      gap: 15px;
      justify-content: center;
      flex-wrap: wrap;
    }

    .btn {
      display: inline-block;
      padding: 16px 34px;
      border-radius: 40px;
      text-decoration: none;
      color: #fff;
      font-size: 18px;
      min-width: 220px;
    }

    .btn.whatsapp {
      background: #25d366;
    }

    .btn.instagram {
      background: linear-gradient(45deg, #f58529, #dd2a7b, #8134af);
    }

    footer {
      margin-top: 40px;
      font-size: 14px;
      color: #444;
    }
  </style>
</head>

<body>
  <div class="leaves"></div>

  <div class="container">
    <!-- Фото -->
    <img src="avatar.jpg" alt="Алма Сарсенбаева" class="avatar">

    <!-- Заголовок -->
    <h1>Мен – Алма Сарсенбаева</h1>
    <h2>
      FOHOW корпорациясының серіктесімін.<br>
      Жеке парақшама қош келдіңіз!
    </h2>

    <div class="divider"></div>

    <!-- Текст -->
    <p class="highlight">
      Мен сізді экологиялық, денсаулыққа арналған бизнеске шақырамын!<br>
      Адамдардың өз ағзасына деген көзқарасын өзгертетін компанияға.
    </p>

    <div class="divider"></div>

    <!-- Преимущества -->
    <h3>Компания артықшылықтары:</h3>
    <ul>
      <li>Ғылыми жетістіктерге негізделген жоғары сапалы өнімдер</li>
      <li>FOHOW — 2023 жылғы әлемдік бренд</li>
      <li>Қазақстандағы үздік өнімдер</li>
      <li>Корпорацияға 17 жыл</li>
      <li>Әлемнің 90 елінде 2000+ өкіл</li>
      <li>Halal, Kosher, GMP, QS, FDA, ISO9001 сертификаттары</li>
      <li>Үлкен әрі тұрақты табысқа шығу мүмкіндігі</li>
    </ul>

    <div class="divider"></div>

    <!-- FAQ -->
    <div class="faq">
      <p>＋ FOHOW бизнесінің артықшылықтары қандай?</p>
      <p>＋ FOHOW корпорациясының артықшылықтары қандай?</p>
      <p>＋ FOHOW серіктесі болу үшін не керек?</p>
    </div>

    <div class="divider"></div>

    <!-- Кнопки -->
    <div class="social-buttons">
      <a class="btn whatsapp" href="https://wa.me/87003338541" target="_blank">
        WhatsApp
      </a>

      <a class="btn instagram"
         href="https://www.instagram.com/fohow__astana"
         target="_blank">
        Instagram
      </a>
    </div>

    <!-- Футер -->
    <footer>
      Алма Сарсенбаева<br>
      FOHOW корпорациясының серіктесі
    </footer>
  </div>
</body>
</html>
