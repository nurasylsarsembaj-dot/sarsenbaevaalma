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
  background:#111 url("https://www.joyoflife.ee/media/joy-of-life/Tooted/Fohow/Fohow%20base.png") center/cover no-repeat;
  color: white;
  text-align: center;
  padding: 40px 20px;
}

header h1 {
  margin: 0;
  font-size: 28px;
}

header p {
  max-width: 600px;
  margin: 15px auto;
  font-size: 18px;
}

/* ======= Главная секция ======= */
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

/* ======= Кнопки ======= */
.contacts {
  text-align: center;
  margin-top: 40px;
}

.btn {
  display: inline-block;
  margin: 10px;
  padding: 14px 22px;
  border-radius: 30px;
  font-weight: bold;
  color: white;
  transition: transform 0.2s;
}
.btn:hover {
  transform: scale(1.05);
}

.wh1 { background: #25D366; }
.wh2 { background: #1ebe5d; }
.inst { background: #c13584; }

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

/* ======= Адаптив ======= */
@media(max-width:600px){
  header h1 { font-size: 24px; }
  header p { font-size: 16px; }
  .btn { padding: 12px 18px; font-size: 14px; }
}
</style>
</head>
<body>

<header>
  <h1>Алма Сарсенбаева</h1>
  <p>Специалист по био-массажу Fohow</p>
</header>

<div class="main" id="home">
  <div class="card" onclick="openSection('company')">Про компанию</div>
  <div class="card" onclick="openSection('services')">Услуги</div>
  <div class="card" onclick="openSection('gallery')">Фото и видео</div>
  <div class="card" onclick="openSection('business')">Бизнес-возможности</div>

  <div class="contacts">
    <a class="btn wh1" href="https://wa.me/87003338541" target="_blank">WhatsApp</a>
    <a class="btn wh2" href="https://wa.me/87072711221" target="_blank">WhatsApp 2</a>
    <a class="btn inst" href="https://instagram.com/" target="_blank">Instagram</a>
  </div>
</div>

<!-- ======= Секции ======= -->
<div class="main section" id="company">
  <div class="back" onclick="goBack()">← Назад</div>
  <h2>О компании Fohow</h2>
  <p>Fohow Group Co., Ltd — международная корпорация, работающая на принципах традиционной китайской медицины.</p>
</div>

<div class="main section" id="services">
  <div class="back" onclick="goBack()">← Назад</div>
  <h2>Услуги</h2>
  <p>3 массажа за 5 000 ₸ для пенсионеров. Забота, тепло, внимание и восстановление.</p>
</div>

<div class="main section" id="gallery">
  <div class="back" onclick="goBack()">← Назад</div>
  <h2>Фото и видео</h2>
  <img class="gallery-img" src="https://mirazdrav.ru/templates/yootheme/cache/photo_5334552357947700508_y-29bddcff.jpeg" alt="Массаж" onclick="zoomImage(this)">
</div>

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

// Функция увеличения изображения в галерее
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
