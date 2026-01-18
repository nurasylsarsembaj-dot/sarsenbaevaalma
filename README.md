<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Алма Сарсенбаева — Fohow</title>
<meta name="description" content="Алма Сарсенбаева — профессиональный массажист компании Fohow. Узнайте о нас, наших услугах и возможностях бизнеса.">
<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #f5f5f5;
  color: #111;
}
a { text-decoration: none; }

/* ====== HEADER ====== */
header {
  position: relative;
  text-align: center;
  color: white;
}
header img.bg {
  width: 100%;
  display: block;
}
header .overlay-text {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  background: rgba(0,0,0,0.5); /* полупрозрачный черный фон */
  padding: 25px 35px;
  border-radius: 12px;
  max-width: 900px;
  font-size: 18px;
  line-height: 1.6;
  color: #fff;
}

/* ====== Главная секция ====== */
.main { max-width: 900px; margin: auto; padding: 20px; }

.card {
  background: white; 
  padding: 20px; 
  margin: 15px 0;
  border-radius: 14px; 
  font-weight: bold; 
  text-align: center; 
  cursor: pointer;
  transition: transform 0.2s, box-shadow 0.2s, background 0.2s;
}
.card:hover { 
  transform: translateY(-4px); 
  box-shadow: 0 6px 15px rgba(0,0,0,0.1);
  background: #fafafa;
}

.section {
  display: none; 
  background: white;
  padding: 20px; 
  border-radius: 14px;
  margin-bottom: 40px;
  opacity: 0; 
  transition: opacity 0.3s;
}
.section.show { display: block; opacity: 1; }
.section.hide { opacity: 0; transition: opacity 0.3s; }

.back { display: inline-block; margin-bottom: 20px; color: #bfa14a; font-weight: bold; cursor: pointer; }

.contacts { text-align: center; margin-top: 40px; }
.btn { display: inline-block; margin: 10px; padding: 14px 22px; border-radius: 30px; font-weight: bold; color: white; transition: transform 0.2s, box-shadow 0.2s; }
.btn:hover { transform: scale(1.05); box-shadow: 0 4px 10px rgba(0,0,0,0.2); }
.wh1 { background: #25D366; }
.wh2 { background: #1ebe5d; }
.inst { background: #c13584; }

.company-image { text-align: center; margin: 15px 0; }
.company-image img { width: 100%; max-width: 500px; border-radius: 10px; }

.gallery-item { width: 100%; border-radius: 10px; }
.gallery-item img, .gallery-item iframe { width: 100%; border-radius: 10px; height: auto; }

/* Сетка для галереи */
.gallery-grid {
  display: grid; 
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); 
  gap: 15px;
}

@media(max-width:600px){
  header .overlay-text { font-size: 16px; padding: 15px 20px; }
  .card { padding: 16px 10px; font-size: 16px; }
  .btn { padding: 12px 18px; font-size: 14px; }
  .company-image img { max-width: 100%; }
  .gallery-item iframe { height: 200px; }
}
</style>
</head>
<body>

<!-- ======= HEADER ======= -->
<header>
  <img class="bg" src="https://www.joyoflife.ee/media/joy-of-life/Tooted/Fohow/Fohow%20base.png" alt="Фон">
  <div class="overlay-text">
    Добро пожаловать! Рады видеть вас на нашем сайте! Меня зовут Алма Сарсенбаева,
    и вместе с моей дочерью мы являемся профессиональными массажистами компании Fohow.
    Здесь вы можете узнать больше о нас, о нашей компании и об услугах, которые мы
    с любовью предоставляем нашим клиентам. Мы будем рады помочь вам заботиться
    о здоровье и гармонии вашего тела.
  </div>
</header>

<!-- ======= Главная ======= -->
<div class="main" id="home">
  <div class="card" onclick="openSection('company')">Про компанию</div>
  <div class="card" onclick="openSection('services')">Услуги</div>
  <div class="card" onclick="openSection('gallery')">Фото и видео</div>
  <div class="card" onclick="openSection('business')">Бизнес‑возможности</div>

  <div class="contacts">
    <a class="btn wh1" href="https://wa.me/87003338541" target="_blank">WhatsApp</a>
    <a class="btn wh2" href="https://wa.me/87072711221" target="_blank">WhatsApp 2</a>
    <a class="btn inst" href="https://www.instagram.com/fohow__astana?igsh=MWd5NTNremx6bjJjNw%3D%3D&utm_source=qr" target="_blank">Instagram</a>
  </div>
</div>

<!-- ======= Про компанию ======= -->
<div class="main section" id="company">
  <div class="back" onclick="goBack()">← Назад</div>
  <h2>О компании Fohow</h2>
  <p><strong>Fohow Group Co., Ltd</strong> — крупная международная корпорация из Китая, специализирующаяся на исследованиях, производстве и распространении натуральной оздоровительной продукции на основе Традиционной китайской медицины (ТКМ).</p>
  <div class="company-image"><img src="https://i.ytimg.com/vi/RtyoRQ_TQfc/maxresdefault.jpg" alt="О компании Fohow" loading="lazy"></div>

  <h3>История компании</h3>
  <p>1995 — основатель господин Ю Фэй начал деятельность в области здоровья и натуральных продуктов.<br>
     1999 — создан первый производственный центр по выпуску оздоровительных продуктов.<br>
     2007 — корпорация официально выходит на международный рынок.<br>
     Сегодня Fohow работает более чем в 86 странах и регионах Европы, Азии, Африки и Америки, с тысячами филиалов и представительств по всему миру.</p>
  <div class="company-image"><img src="https://i.ytimg.com/vi/5I7h5QCNbRA/maxresdefault.jpg" alt="История компании" loading="lazy"></div>

  <h3>Миссия и философия</h3>
  <p>Корпорация стремится распространять культуру заботы о здоровье и долголетии, сочетая традиции ТКМ и современные научные технологии.</p>
  <ul>
    <li>Здоровье через традиции и инновации</li>
    <li>Натуральность и безопасность продукции</li>
    <li>Польза для ежедневного применения</li>
    <li>Устойчивый международный рост</li>
  </ul>

  <h3>Продукция и направления</h3>
  <p>Компания предлагает широкий спектр продукции для поддержки здоровья:</p>
  <ul>
    <li>Биологически активные добавки (БАДы) и эликсиры</li>
    <li>Натуральные пищевые добавки</li>
    <li>Растительные концентраты и экстракты</li>
    <li>Уходовые средства и оздоровительные приборы</li>
    <li>Продукты для иммунитета, энергии, очищения и регуляции баланса организма</li>
  </ul>
  <div class="company-image"><img src="https://www.info.lt/images/nuotraukos/2460225_1.jpg?202304280943" alt="Продукция Fohow" loading="lazy"></div>

  <h3>Научные исследования и производство</h3>
  <p>Fohow располагает собственной научно‑исследовательской базой:</p>
  <ul>
    <li>НИИ Ян‑Шэн Fohow – центр разработок и исследований</li>
    <li>Эко‑Агро Fohow – выращивание лекарственных растений</li>
    <li>Биотехнологические и фармацевтические производства</li>
  </ul>
  <p>Производственные процессы сертифицированы по международным стандартам ISO, GMP, HACCP, что подтверждает безопасность и качество продукции.</p>

  <h3>Международное присутствие</h3>
  <p>Компания работает в десятках стран, продукция зарегистрирована и продаётся в Европе, Азии, Америке и других регионах. Открыто более 1000 центров, филиалов и представительств по всему миру.</p>

  <h3>Культура здоровья Fohow</h3>
  <p>Fohow развивает идеи, основанные на ТКМ:</p>
  <ul>
    <li>Регуляция — восстановление баланса в организме</li>
    <li>Очистка — удаление токсинов и шлаков</li>
    <li>Восстановление — укрепление и питание тела</li>
  </ul>
</div>

<!-- ======= Услуги ======= -->
<div class="main section" id="services">
  <div class="back" onclick="goBack()">← Назад</div>
  <h2>Услуги</h2>
  <p>3 массажа за 5 000 ₸ для пенсионеров. Забота, тепло, внимание и восстановление.</p>
</div>

<!-- ======= Галерея (2 колонки, фото и видео) ======= -->
<div class="main section" id="gallery">
  <div class="back" onclick="goBack()">← Назад</div>
  <h2>Фото и видео</h2>

  <div class="gallery-grid">
    <div class="gallery-item"><img src="https://avatars.mds.yandex.net/get-altay/4699294/2a0000017b7ccf95dd1610f534a0a7a21b08/XXL_height" alt="Фото 1" loading="lazy"></div>
    <div class="gallery-item"><iframe src="https://rutube.ru/play/embed/d24bb55a2aa3c75f203d6407c242af42/" frameborder="0" allowfullscreen loading="lazy"></iframe></div>
    <div class="gallery-item"><img src="https://avatars.mds.yandex.net/get-altay/10953738/2a0000018a1971ea07aa71ab6d3f7667d0a3/XXL_height" alt="Фото 2" loading="lazy"></div>
    <div class="gallery-item"><iframe src="https://rutube.ru/play/embed/7814f896ecfb299468f8f279335dd574/" frameborder="0" allowfullscreen loading="lazy"></iframe></div>
    <div class="gallery-item"><img src="https://static.tildacdn.com/tild3732-3035-4163-b563-653034653033/1.png" alt="Фото 3" loading="lazy"></div>
    <div class="gallery-item"><img src="https://avatars.mds.yandex.net/get-altay/11471993/2a00000190aef173b84f4d02eb34ccb87c23/XXL_height" alt="Фото 4" loading="lazy"></div>
    <div class="gallery-item"><img src="https://frankfurt.apollo.olxcdn.com/v1/files/tpzr1rzubpak2-KZ/image" alt="Фото 5" loading="lazy"></div>
  </div>
</div>

<!-- ======= Бизнес ======= -->
<div class="main section" id="business">
  <div class="back" onclick="goBack()">← Назад</div>
  <h2>Бизнес с Fohow</h2>
  <p>Возможность строить доход с поддержкой компании.</p>
</div>

<script>
function openSection(id){
  document.getElementById("home").style.display="none";
  document.querySelectorAll(".section").forEach(s => s.classList.remove("show","hide"));
  const section = document.getElementById(id);
  section.style.display = "block";
  setTimeout(()=> section.classList.add("show"), 50);
}

function goBack(){
  document.querySelectorAll(".section").forEach(s => s.classList.add("hide"));
  setTimeout(() => {
    document.querySelectorAll(".section").forEach(s => s.style.display = "none");
    document.getElementById("home").style.display = "block";
  }, 300);
}
</script>

</body>
</html>
