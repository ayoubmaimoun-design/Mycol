# Mycol<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>موقعي الاحترافي</title>

<style>
body{
  margin:0;
  font-family:Arial;
  background:#0f172a;
  color:white;
}

header{
  display:flex;
  justify-content:space-between;
  align-items:center;
  padding:20px;
  background:#1e293b;
}

.logo{
  font-size:24px;
  color:#38bdf8;
  font-weight:bold;
}

nav a{
  color:white;
  text-decoration:none;
  margin:10px;
}

.hero{
  text-align:center;
  padding:80px 20px;
}

.hero h1{
  font-size:45px;
  color:#38bdf8;
}

.hero p{
  font-size:20px;
  color:#cbd5e1;
}

.btn{
  display:inline-block;
  margin-top:20px;
  padding:12px 30px;
  background:#38bdf8;
  color:black;
  border-radius:10px;
  text-decoration:none;
  font-weight:bold;
}

.cards{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
  gap:20px;
  padding:40px;
}

.card{
  background:#1e293b;
  padding:25px;
  border-radius:12px;
  transition:0.3s;
}

.card:hover{
  transform:translateY(-10px);
}

footer{
  text-align:center;
  padding:20px;
  background:#1e293b;
  margin-top:30px;
}
</style>
</head>

<body>

<header>
  <div class="logo">MY WEBSITE</div>
  <nav>
    <a href="#">الرئيسية</a>
    <a href="#">الخدمات</a>
    <a href="#">اتصل بنا</a>
  </nav>
</header>

<section class="hero">
  <h1>مرحباً بك 👋</h1>
  <p>موقع احترافي تم إنشاؤه على GitHub</p>
  <a class="btn" href="#">ابدأ الآن</a>
</section>

<section class="cards">

  <div class="card">
    <h2>💻 برمجة</h2>
    <p>تعلم تطوير المواقع خطوة بخطوة</p>
  </div>

  <div class="card">
    <h2>🎮 ألعاب</h2>
    <p>إنشاء ألعاب بسيطة وممتعة</p>
  </div>

  <div class="card">
    <h2>💰 ربح</h2>
    <p>تعلم كيفية الربح من الإنترنت</p>
  </div>

</section>

<footer>
  © 2026 جميع الحقوق محفوظة
</footer>

</body>
</html>
