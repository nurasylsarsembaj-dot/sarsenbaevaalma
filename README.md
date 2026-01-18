<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Алма Сарсенбаева — био-массаж Fohow</title>

<style>
body{
    margin:0;
    font-family:Arial,sans-serif;
    scroll-behavior:smooth;
    color:#222;
}

/* HEADER */
header{
    position:fixed;
    top:0;
    width:100%;
    background:rgba(255,255,255,0.95);
    padding:8px 16px;
    display:flex;
    justify-content:space-between;
    align-items:center;
    z-index:1000;
    box-shadow:0 2px 6px rgba(0,0,0,0.1);
}
header nav a{
    margin:0 8px;
    font-size:14px;
    font-weight:bold;
    color:#333;
    text-decoration:none;
}

/* SECTIONS */
section{
    padding:70px 20px;
    max-width:1100px;
    margin:auto;
}
section:first-of-type{
    padding-top:110px; /* чтобы меню не перекрывало */
}
h2{
    text-align:center;
    margin-bottom:30px;
}

/* HERO */
.hero{
    height:70vh; /* было слишком большое */
    background:url("https://www.joyoflife.ee/media/joy-of-life/Tooted/Fohow/Fohow%20base.png") center/cover no-repeat;
    position:relative;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
}
.hero::after{
    content:"";
    position:absolute;
    inset:0;
    background:rgba(0,0,0,0.45);
}
.hero-content{
    position:relative;
    z-index:2;
    color:#fff;
    max-width:700px;
}
.hero h1{font-size:32px;margin-bottom:15px;}
.hero p{font-size:18px;}

/* CARDS */
.card{
    background:#f5f5f5;
    padding:22px;
    border-radius:10px;
}

/* GRID */
.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
    gap:20px;
}

/* GALLERY */
.gallery iframe,.gallery img{
    width:100%;
    height:260px;
    border-radius:10px;
    border:none;
}

/* BUTTONS */
.btn{
    display:inline-block;
    padding:12px 22px;
    border-radius:6px;
    margin:6px;
    font-weight:bold;
    text-decoration:none;
}
.btn-whatsapp{background:#25D366;color:#fff;}
.btn-gold{
    background:#111;
    color:#d4af37;
    border:1px solid #d4af37;
}
.btn-instagram{background:#C13584;color:#fff;}

/* FOOTER */
footer{
    background:#eee;
    padding:20px;
    text-align:center;
    font-size:14px;
}

/* MOBILE */
@media(max-width:600px){
    header nav a{font-size:12px;margin:0 5px;}
    .hero h1{font-size:24px;}
}
</style>
</head>

<body>

<header>
    <div><b>FOHOW</b></div>
    <nav>
        <a href="#company">Компания</a>
        <a href="#services">Услуги</a>
        <a href="#gallery">Фото/Видео</a>
        <a href="#business">Бизнес</a>
        <a href="#contacts">Контакты</a>
    </nav>
</header>

<!-- HERO (БЕЗ КНОПОК) -->
<section class="hero" id="hero">
    <div class="hero-content">
        <h1>Алма Сарсенбаева</h1>
        <p>Био-массаж Fohow — восстановление энергии и забота о здоровье</p>
    </div>
</section>

<section id="company">
<h2>О компании Fohow</h2>
<div class="card">
Fohow Group Co., Ltd — международная корпорация, основанная на традиционной китайской медицине и принципах Ян-Шэн.
</div>
</section>

<section id="services">
<h2>Услуги и акция</h2>
<div class="card">
<b>С заботой о старшем поколении</b><br><br>
✨ <b>3 дня — 3 массажа всего за <span style="color:#b08d2d;font-size:20px;">5 000 ₸</span></b><br><br>
✔ Лечебный массаж<br>
✔ Спокойная, бережная работа<br>
✔ Травяной чай<br>
✔ Уютная атмосфера и внимание
</div>
</section>

<section id="gallery">
<h2>Фото и видео</h2>
<div class="grid gallery">

<iframe src="https://rutube.ru/play/embed/b43cd989b54e6f93daadc0759f8ec9ee/"></iframe>
<img src="https://mirazdrav.ru/templates/yootheme/cache/photo_5334552357947700508_y-29bddcff.jpeg">

<iframe src="https://rutube.ru/play/embed/25545ed4fe86b820225a2a93329910bc/"></iframe>
<img src="https://world-fenix.ru/ssl/u/d0/4bfcce524811efab668d7432dabdfa/-/874e3714-52d2-4a08-b97d-4605d51db3a0.jpg">

<iframe src="https://rutube.ru/play/embed/a947fe006f9c6c73b6ab667dce8896ea/"></iframe>
<img src="https://avatars.mds.yandex.net/get-altay/14185024/2a00000193b0c99ecdc6de176f05f56946ad/orig">

</div>
</section>

<section id="business">
<h2>Бизнес-возможности</h2>
<div class="card">
Партнёрство с Fohow — возможность развивать собственный бизнес с поддержкой международной компании.
</div>
</section>

<section id="contacts">
<h2>Контакты</h2>

<a class="btn btn-gold" href="https://wa.me/87003338541">
WhatsApp (основной)
</a>

<a class="btn btn-whatsapp" href="https://wa.me/87072711221">
WhatsApp (акция)
</a>

<a class="btn btn-instagram" href="https://instagram.com">
Instagram
</a>

</section>

<footer>
© 2026 Алма Сарсенбаева • Fohow
</footer>

</body>
</html>
