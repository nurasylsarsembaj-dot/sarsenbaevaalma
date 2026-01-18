<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Алма Сарсенбаева — Fohow</title>
<style>
/* ======= Общие стили ======= */
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #f5f5f5;
  color: #111;
}

a {
  text-decoration: none;
}

header {
  position: relative;
  background: url("https://www.joyoflife.ee/media/joy-of-life/Tooted/Fohow/Fohow%20base.png") center/cover no-repeat;
  color: white;
  text-align: center;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
}

.hero-overlay {
  background: rgba(0,0,0,0.5);
  padding: 40px 20px;
  border-radius: 15px;
  max-width: 900px;
}

header h1 {
  font-size: 42px;
  margin: 0 0 20px 0;
}

.name-highlight {
  color: #bfa14a;
  font-weight: bold;
}

.hero-subtitle {
  font-size: 18px;
  line-height: 1.6;
  margin-bottom: 20px;
}

.hero-buttons .btn {
  margin: 10px;
  padding: 14px 22px;
  font-weight: bold;
  border-radius: 30px;
  transition: transform 0.2s;
  color: white;
}

.hero-buttons .btn:hover {
  transform: scale(1.05);
}

.wh1 { background: #25D366; }
.wh2 { background: #1ebe5d; }
.inst { background: #c13584; }

/* ======= Главная карточки ======= */
.main {
  max-width: 900px;
  margin: auto;
  padding: 20px;
}

.card {
  background: white;
  padding: 20px;
  margin: 15px 0;
  border-radius: 14px;
  cursor: pointer;
  font-weight: bold;
  text-align: center;
  transition: transform 0.2s, box-shadow 0.2s;
}
.card:hover {
  transform: translateY(-4px);
  box-shadow: 0 6px 15px rgba(0,0,0,0.1);
}

.section {
  display: none;
  background: white;
  padding: 20px;
  border-radius: 14px;
  opacity: 0;
  transition: opacity 0.3s;
}

.section.show {
  display: block;
  opacity: 1;
}

/* ======= Кнопка назад ======= */
.back {
  display: inline-block;
  margin-bottom: 20px;
  color: #bfa14a;
  font-weight: bold;
  cursor: pointer;
}

/* ======= Галерея ======= */
.gallery-img {
  width: 100%;
  border-radius: 10px;
  cursor: pointer;
  transition: transform 0.2s;
}
.gallery-img:hover {
  transform: scale(1.02);
}

/* ======= Изображения внутри компании ======= */
.company-image {
  text-align: center;
  margin: 15px 0;
}

.company-image img {
  width: 100%;
  max-width: 500px;
  border-radius: 10px;
}

/* ======= Адаптив ======= */
@media(max-width:600px){
  header h1 { font-size: 28px; }
  .hero-subtitle { font-size: 16px; }
  .hero-buttons .btn { padding: 12px 18px; font-size: 14px; }
  .company-image img { max-width: 100%; }
}
</style>
</head>
<body>

<!-- ======= Главный экран ======= -->
<header>
  <div class="hero-overlay">
    <h1><span class="name-highlight">Алма Сарсенбаева</span></h1>
    <p class="hero-subtitle">
      Добро пожаловать!<br>
      Рады видеть вас на нашем сайте!<br>
      Меня зовут Алма Сарсенбаева, и вместе с моей дочерью мы являемся профессиональными массажистами компании Fohow.<br>
      Здесь вы можете узнать больше о нас, о нашей компании и об услугах, которые мы с любовью предоставляем нашим клиентам.<br>
      Мы будем рады помочь вам заботиться о здоровье и гармонии вашего тела.
    </p>
    <div class="hero-buttons">
      <a class="btn wh1" href="https://wa.me/87003338541" target="_blank">WhatsApp</a>
      <a class="btn wh2" href="https://wa.me/87072711221" target="_blank">WhatsApp 2</a>
      <a class="btn inst" href="https://instagram.com/" target="_blank">Instagram</a>
    </div>
  </div>
</header>

<!-- ======= Главная карточки ======= -->
<div class="main" id="home">
  <div class="card" onclick="openSection('company')">Про компанию</div>
  <div class="card" onclick="openSection('services')">Услуги</div>
  <div class="card" onclick="openSection('gallery')">Фото и видео</div>
  <div class="card" onclick="openSection('business')">Бизнес-возможности</div>
</div>

<!-- ======= Секция: Про компанию ======= -->
<div class="main section" id="company">
  <div class="back" onclick="goBack()">← Назад</div>
  <h2>О компании Fohow</h2>

  <p>
    Fohow — международная компания, которая сочетает традиционную китайскую медицину и современные технологии, создавая натуральные продукты для здоровья и красоты.
  </p>

  <h3>История компании</h3>
  <p>
    Компания была основана в 1995 году и с тех пор активно развивается на международном рынке.
    Сегодня Fohow представлена в более чем 80 странах мира.
  </p>
  <div class="company-image">
    <img src="https://i.ytimg.com/vi/RtyoRQ_TQfc/maxresdefault.jpg" alt="История компании Fohow">
  </div>

  <h3>Миссия и философия</h3>
  <p>
    Мы стремимся делать здоровье доступным каждому, используя безопасные и проверенные натуральные компоненты.
    Наши принципы: натуральность, инновации, качество, гармония тела и духа.
  </p>
  <div class="company-image">
    <img src="https://i.ytimg.com/vi/MotIRWPEbbU/maxresdefault.jpg" alt="Миссия и философия Fohow">
  </div>

  <h3>Продукция</h3>
  <ul>
    <li>Биодобавки и витамины</li>
    <li>Средства для иммунитета</li>
    <li>Натуральные экстракты и концентраты</li>
    <li>Уходовые продукты для красоты</li>
  </ul>
  <div class="company-image">
    <img src="https://sun9-26.userapi.com/c849220/v849220455/1b3a7/m-sbX1q9-wE.jpg" alt="Продукция Fohow">
  </div>

  <h3>Научные исследования и производство</h3>
  <p>
    Компания имеет собственные научно-исследовательские центры и производства с международными сертификатами качества ISO и GMP.
  </p>
  <div class="company-image">
    <img src="https://i.ytimg.com/vi/t_EHWHbNU50/maxresdefault.jpg?sqp=-oaymwEmCIAKENAF8quKqQMa8AEB-AH-DoACuAiKAgwIABABGDUgXShlMA8=&rs=AOn4CLCoUqtLvszMDh6uzUYqARYdP58YGQ" alt="Лаборатория и производство Fohow">
  </div>

  <h3>Культура здоровья</h3>
  <p>
    Философия Fohow основана на трёх шагах: регуляция → очистка → восстановление, что отражено во всех продуктах компании.
  </p>
  <div class="company-image">
    <img src="https://via.placeholder.com/500x200?text=Регуляция+→+Очистка+→+Восстановление" alt="Культура здоровья Fohow">
  </div>
</div>

<!-- ======= Секция: Услуги ======= -->
<div class="main section" id="services">
  <div class="back" onclick="goBack()">← Назад</div>
  <h2>Услуги</h2>
  <p>3 массажа за 5 000 ₸ для пенсионеров. Забота, тепло, внимание и восстановление.</p>
</div>

<!-- ======= Секция: Галерея ======= -->
<div class="main section" id="gallery">
  <div class="back" onclick="goBack()">← Назад</div>
  <h2>Фото и видео</h2>
  <img class="gallery-img" src="https://mirazdrav.ru/templates/yootheme/cache/photo_5334552357947700508_y-29bddcff.jpeg" alt="Массаж" onclick="zoomImage(this)">
</div>

<!-- ======= Секция: Бизнес ======= -->
<div class="main section" id="business">
  <div class="back" onclick="goBack()">← Назад</div>
  <h2>Бизнес с Fohow</h2>
  <p>Возможность строить доход с поддержкой компании.</p>
</div>

<!-- ======= Скрипт ======= -->
<script>
function openSection(id){
  document.getElementById("home").style.display="none";
  document.querySelectorAll(".section").forEach(s => s.classList.remove("show"));
  const section = document.getElementById(id);
  section.style.display = "block";
  setTimeout(()=> section.classList.add("show"), 50);
}

function goBack(){
  document.querySelectorAll(".section").forEach(s => s.classList.remove("show"));
  setTimeout(() => {
    document.querySelectorAll(".section").forEach(s => s.style.display = "none");
    document.getElementById("home").style.display = "block";
  }, 300);
}

function zoomImage(img){
  const overlay = document.createElement("div");
  overlay.style.position = "fixed";
  overlay.style.top = 0;
  overlay.style.left = 0;
  overlay.style.width = "100%";
  overlay.style.height = "100%";
  overlay.style.background = "rgba(0,0,0,0.8)";
  overlay.style.display = "flex";
  overlay.style.alignItems = "center";
  overlay.style.justifyContent = "center";
  overlay.style.cursor = "zoom-out";
  overlay.onclick = ()=> document.body.removeChild(overlay);

  const zoomedImg = document.createElement("img");
  zoomedImg.src = img.src;
  zoomedImg.style.maxWidth = "90%";
  zoomedImg.style.maxHeight = "90%";
  zoomedImg.style.borderRadius = "10px";
  overlay.appendChild(zoomedImg);

  document.body.appendChild(overlay);
}
</script>

</body>
</html>
