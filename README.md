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

header {
  background:#111 url("https://www.joyoflife.ee/media/joy-of-life/Tooted/Fohow/Fohow%20base.png") center/cover no-repeat;
  color: white;
  text-align: center;
  padding: 40px 20px;
}

header h1 { margin: 0; font-size: 32px; color: #bfa14a; }

header p { max-width: 600px; margin: 15px auto; font-size: 18px; color: red; }

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

.gallery-video, .gallery-img { width: 100%; margin: 10px 0; border-radius: 10px; }
.gallery-video iframe { width: 100%; height: 315px; border-radius: 10px; }

@media(max-width:600px){
  header h1 { font-size: 24px; }
  header p { font-size: 16px; }
  .btn { padding: 12px 18px; font-size: 14px; }
  .company-image img { max-width: 100%; }
  .gallery-video iframe { height: 200px; }
}
</style>
</head>
<body>

<header>
  <h1>Алма Сарсенбаева</h1>
  <p>
    Добро пожаловать! Рады видеть вас на нашем сайте! Меня зовут Алма Сарсенбаева,
    и вместе с моей дочерью мы являемся профессиональными массажистами компании Fohow.
    Здесь вы можете узнать больше о нас, о нашей компании и об услугах, которые мы
    с любовью предоставляем нашим клиентам. Мы будем рады помочь вам заботиться
    о здоровье и гармонии вашего тела.
  </p>
</header>

<div class="main" id="home">
  <button class="card" onclick="openSection('company')">Про компанию</button>
  <button class="card" onclick="openSection('services')">Услуги</button>
  <button class="card" onclick="openSection('gallery')">Фото и видео</button>
  <button class="card" onclick="openSection('business')">Бизнес‑возможности</button>

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
  <p>Fohow — международная компания, которая сочетает традиционную китайскую медицину и современные технологии, создавая натуральные продукты для здоровья и красоты.</p>

  <h3>История компании</h3>
  <p>Компания была основана в 1995 году и с тех пор активно развивается на международном рынке. Сегодня Fohow представлена в более чем 80 странах мира.</p>
  <div class="company-image"><img src="https://i.ytimg.com/vi/RtyoRQ_TQfc/maxresdefault.jpg" alt="История компании" loading="lazy"></div>

  <h3>Миссия и философия</h3>
  <p>Мы стремимся делать здоровье доступным каждому, используя безопасные и проверенные натуральные компоненты. Наши принципы: натуральность, инновации, качество, гармония тела и духа.</p>
  <div class="company-image"><img src="https://i.ytimg.com/vi/MotIRWPEbbU/maxresdefault.jpg" alt="Миссия и философия" loading="lazy"></div>

  <h3>Продукция</h3>
  <ul>
    <li>Биодобавки и витамины</li>
    <li>Средства для иммунитета</li>
    <li>Натуральные экстракты и концентраты</li>
    <li>Уходовые продукты для красоты</li>
  </ul>
  <div class="company-image"><img src="https://sun9-26.userapi.com/c849220/v849220455/1b3a7/m-sbX1q9-wE.jpg" alt="Продукция Fohow" loading="lazy"></div>

  <h3>Научные исследования и производство</h3>
  <p>Компания имеет собственные научно-исследовательские центры и производства с международными сертификатами качества ISO и GMP.</p>
  <div class="company-image"><img src="https://i.ytimg.com/vi/t_EHWHbNU50/maxresdefault.jpg?sqp=-oaymwEmCIAKENAF8quKqQMa8AEB-AH-DoACuAiKAgwIABABGDUgXShlMA8=&rs=AOn4CLCoUqtLvszMDh6uzUYqARYdP58YGQ" alt="Лаборатория и производство" loading="lazy"></div>

  <h3>Культура здоровья</h3>
  <p>Философия Fohow основана на трёх шагах: регуляция → очистка → восстановление.</p>
  <div class="company-image"><img src="https://via.placeholder.com/500x200?text=Регуляция+→+Очистка+→+Восстановление" alt="Культура здоровья" loading="lazy"></div>
</div>

<!-- ======= Услуги ======= -->
<div class="main section" id="services">
  <div class="back" onclick="goBack()">← Назад</div>
  <h2>Услуги</h2>
  <p>3 массажа за 5 000 ₸ для пенсионеров. Забота, тепло, внимание и восстановление.</p>
</div>

<!-- ======= Галерея (видео и фото) ======= -->
<div class="main section" id="gallery">
  <div class="back" onclick="goBack()">← Назад</div>
  <h2>Фото и видео</h2>

  <div class="gallery-video">
    <iframe src="https://rutube.ru/play/embed/3376eb8379982a5d4e5a6b91b1d4f57a/" frameborder="0" allowfullscreen loading="lazy"></iframe>
  </div>
  <div class="gallery-video">
    <iframe src="https://rutube.ru/play/embed/c91f1adba6ef3c1da6254d309bfe2f90/" frameborder="0" allowfullscreen loading="lazy"></iframe>
  </div>

  <div class="gallery-img"><img src="https://avatars.mds.yandex.net/get-altay/11873493/2a00000192e41aa34901c8ee8890e2c1879d/orig" alt="Фото 1" loading="lazy"></div>
  <div class="gallery-img"><img src="https://avatars.mds.yandex.net/get-altay/11873493/2a00000192e41aa34901c8ee8890e2c1879d/orig" alt="Фото 2" loading="lazy"></div>
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
  document.querySelectorAll(".section").forEach(s => {
    s.classList.remove("show","hide");
  });
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
