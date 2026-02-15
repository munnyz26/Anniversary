# <!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Sweet Love — Sochea 💞 Bora</title>

<style>
body{
  margin:0;
  font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Arial;
  background:radial-gradient(circle at top,#1a0f1f,#09080d);
  color:#fff;
  display:flex;
  align-items:center;
  justify-content:center;
  min-height:100vh;
}

.card{
  width:min(920px,94vw);
  background:rgba(255,255,255,.06);
  border:1px solid rgba(255,255,255,.14);
  border-radius:26px;
  padding:26px 20px;
  text-align:center;
  box-shadow:0 20px 60px rgba(0,0,0,.45);
}

.topflowers{
  font-size:22px;
  letter-spacing:3px;
  margin-bottom:6px;
}

h1{
  font-size:38px;
  margin:10px 0 6px;
}

.sub{
  opacity:.9;
  margin-bottom:18px;
}

.heartwrap{
  display:flex;
  justify-content:center;
  margin:18px 0;
}

.heart{
  width:150px;
  height:130px;
  position:relative;
  transform:rotate(-45deg);
  animation:pulse 1.1s infinite;
  filter:drop-shadow(0 12px 22px rgba(255,105,180,.35));
}

.heart:before,
.heart:after{
  content:"";
  position:absolute;
  width:150px;
  height:130px;
  background:linear-gradient(135deg,#ff5fb4,#ff9ad5);
  border-radius:80px 80px 0 0;
}

.heart:before{
  left:75px;
  transform:rotate(90deg);
  transform-origin:0 100%;
}

.heart:after{
  left:0;
  top:0;
}

@keyframes pulse{
  0%,100%{transform:rotate(-45deg) scale(1)}
  50%{transform:rotate(-45deg) scale(1.12)}
}

.poem{
  max-width:720px;
  margin:0 auto 14px;
  line-height:1.9;
  font-size:16px;
  opacity:.95;
}

.bottomflowers{
  font-size:24px;
  margin-top:10px;
}

.footer{
  margin-top:8px;
  font-size:15px;
  opacity:.9;
}
</style>
</head>

<body>

<div class="card">

  <div class="topflowers">
    🌸🌷💮🪷💗💖💞🪷💮🌷🌸🌸🌷💮🪷
  </div>

  <h1>Sochea 💞 Bora</h1>

  <div class="sub">
    💗 First Love: 15 May 2024 &nbsp;|&nbsp; 15 Feb 2026 💗<br>
    🌸 Together: 1 Year 9 Months 🌸
  </div>

  <div class="heartwrap">
    <div class="heart"></div>
  </div>

  <div class="poem">
    🌷 From the moment our hearts met, everything felt gentle and right.<br>
    💮 Every smile we share becomes a memory I treasure.<br>
    🌸 Through days and dreams, your love is my sweetest place.<br>
    🪷 Hand in hand, our story keeps blooming forever.<br>
    💞 I love you more with every heartbeat… always.
  </div>

  <div class="bottomflowers">
    💗💖💞🌸🌷💮🪷💗💖💞🌸🌷💮🪷
  </div>

  <div class="footer">
    Sweet Love Forever 💞
  </div>

</div>

<script>
const emojis=["🌸","🌷","💮","🪷","💗","💖","💞"];
setInterval(()=>{
  document.title=emojis[Math.floor(Math.random()*emojis.length)]+" Sweet Love";
},900);
</script>

</body>
</html>
