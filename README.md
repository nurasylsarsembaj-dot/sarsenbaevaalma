<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<title>Алма Сарсенбаева — Fohow</title>

<style>
body{
  margin:0;
  font-family:Arial,sans-serif;
  background:#f5f5f5;
}

header{
  background:#111;
  color:white;
  padding:40px 20px;
  text-align:center;
  background-image:url("https://www.joyoflife.ee/media/joy-of-life/Tooted/Fohow/Fohow%20base.png");
  background-size:cover;
  background-position:center;
}

header h1{margin:0;font-size:28px;}
header p{max-width:600px;margin:15px auto;}

.main{
  max-width:900px;
  margin:auto;
  padding:20px;
}

.card{
  background:white;
  padding:20px;
  margin:15px 0;
  border-radius:14px;
  cursor:pointer;
  font-weight:bold;
}

.section{
  display:none;
  background:white;
  padding:20px;
  border-radius:14px;
}

.back{
  display:inline-block;
  margin-bottom:20px;
  color:#bfa14a;
  font-weight:bold;
  cursor:pointer;
}

.contacts{
  text-align:center;
  margin-top:40px;
}

.btn{
  display:inline-block;
  margin:10px;
  padding:14px 22px;
  border-radius:30px;
  text-decoration:none;
  font-weight:bold;
}

.wh1{background:#25D366;color:white;}
.wh2{background:#1ebe5d;color:white;}
.inst{background:#c13584;color:white;}
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

<!-- ПРО КОМПАНИЮ -->
<div class="main section" id="company">
  <div class="back" onclick="goBack()">← Назад</div>
  <h2>О компании Fohow</h2>
  <p>Fohow Group Co., Ltd — международная корпорация, работающая на принципах традиционной китайской медицины.</p>
</div>

<!-- УСЛУГИ -->
<div class="main section" id="services">
  <div class="back" onclick="goBack()">← Назад</div>
  <h2>Услуги</h2>
  <p>3 массажа за 5 000 ₸ для пенсионеров. Забота, тепло, внимание и восстановление.</p>
</div>

<!-- ГАЛЕРЕЯ -->
<div class="main section" id="gallery">
  <div class="back" onclick="goBack()">← Назад</div>
  <h2>Фото и видео</h2>
  <img src="https://mirazdrav.ru/templates/yootheme/cache/photo_5334552357947700508_y-29bddcff.jpeg" width="100%">
</div>

<!-- БИЗНЕС -->
<div class="main section" id="business">
  <div class="back" onclick="goBack()">← Назад</div>
  <h2>Бизнес с Fohow</h2>
  <p>Возможность строить доход с поддержкой компании.</p>
</div>

<script>
function openSection(id){
  document.getElementById("home").style.display="none";
  document.querySelectorAll(".section").forEach(s=>s.style.display="none");
  document.getElementById(id).style.display="block";
}
function goBack(){
  document.querySelectorAll(".section").forEach(s=>s.style.display="none");
  document.getElementById("home").style.display="block";
}
</script>

</body>
</html>
