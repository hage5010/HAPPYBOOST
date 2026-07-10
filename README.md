# HAPPYBOOST
<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HAPPYBOOST</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Zen+Maru+Gothic:wght@400;700;900&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Zen Maru Gothic',sans-serif;
}

body{
background:#fffdf9;
color:#333;
overflow-x:hidden;
}

header{
height:100vh;
display:flex;
justify-content:center;
align-items:center;
flex-direction:column;
background:linear-gradient(135deg,#FFE36D,#FFD1E8,#AEEBFF);
text-align:center;
}

h1{
font-size:70px;
font-weight:900;
color:white;
text-shadow:0 5px 15px rgba(0,0,0,.2);
}

header p{
font-size:22px;
margin-top:20px;
color:white;
}

.button{
margin-top:50px;
display:inline-block;
padding:18px 45px;
background:white;
color:#ff66a3;
border-radius:50px;
text-decoration:none;
font-size:20px;
font-weight:bold;
transition:.3s;
}

.button:hover{
transform:scale(1.08);
}

section{
padding:100px 10%;
}

.title{
font-size:40px;
margin-bottom:40px;
color:#ff66a3;
}

.member{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:30px;
}

.card{
background:white;
border-radius:20px;
padding:30px;
box-shadow:0 10px 25px rgba(0,0,0,.08);
transition:.3s;
}

.card:hover{
transform:translateY(-10px);
}

.card img{
width:100%;
border-radius:15px;
margin-bottom:20px;
}

.card h2{
margin-bottom:10px;
}

.music{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:30px;
}

.song{
background:#fff;
padding:30px;
border-radius:20px;
box-shadow:0 10px 20px rgba(0,0,0,.08);
}

footer{
background:#222;
color:white;
padding:50px;
text-align:center;
}

.sns a{
color:white;
margin:0 15px;
font-size:20px;
text-decoration:none;
}

</style>

</head>
<body>

<header>

<h1>HAPPYBOOST</h1>

<p>
HAPPY少女をもっと好きになるファンサイト
</p>

<a href="#about" class="button">
START
</a>

</header>

<section id="about">

<h2 class="title">
HAPPY少女とは？
</h2>

<p>

北海道札幌を拠点に活動するアイドルグループ。
ライブで笑顔と元気を届ける最高のグループです！

</p>

</section>

<section>

<h2 class="title">
おすすめ楽曲
</h2>

<div class="music">

<div class="song">

<h3>Coming Soon...</h3>

<p>
ここにおすすめ曲を紹介！
</p>

</div>

<div class="song">

<h3>Coming Soon...</h3>

<p>
MVリンクも掲載予定！
</p>

</div>

</div>

</section>

<section>

<h2 class="title">
メンバー紹介
</h2>

<div class="member">

<div class="card">

<img src="images/member1.jpg">

<h2>佐野なつき</h2>

<p>
ここにプロフィールを書く
</p>

</div>

</div>

</section>

<footer>

<p>Official Link</p>

<div class="sns">

<a href="https://happy-girls.jp/" target="_blank">
公式サイト
</a>

<a href="#">
X
</a>

<a href="#">
YouTube
</a>

<a href="#">
TikTok
</a>

</div>

<br>

<p>
© HAPPYBOOST
</p>

</footer>

</body>
</html>
HAPPYBOOST/
│
├── index.html
├── style.css
├── script.js
│
├── images/
│   ├── logo.png
│   ├── member1.jpg
│   ├── hero.jpg
│   └── ...
│
└── assets/
    ├── sakura.png
    └── heart.png
    HAPPYBOOST/
├── index.html
├── style.css
├── script.js
├── images/
├── assets/
└── README.md（GitHub公開手順付き）