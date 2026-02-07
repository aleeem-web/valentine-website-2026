<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Nimmie ❤️</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:Poppins,sans-serif}
body{
  background:linear-gradient(135deg,#ff9a9e,#fad0c4);
  color:#fff;
  overflow-x:hidden;
}
.container{
  max-width:900px;
  margin:auto;
  padding:40px 20px;
  text-align:center;
}
h1{
  font-family:'Playfair Display',serif;
  font-size:2.8rem;
  margin-bottom:10px;
  animation:fade 2s;
}
.subtitle{
  opacity:.9;
  margin-bottom:30px;
}
.btn{
  background:#fff;
  color:#ff5e78;
  padding:14px 28px;
  border-radius:30px;
  text-decoration:none;
  font-weight:600;
  display:inline-block;
  margin:20px 0;
}
.section{
  margin:50px 0;
}
.card{
  background:rgba(255,255,255,.18);
  backdrop-filter:blur(10px);
  border-radius:20px;
  padding:25px;
  margin:20px 0;
}
.card h2{margin-bottom:10px}
.gallery{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(140px,1fr));
  gap:15px;
}
.gallery img{
  width:100%;
  height:220px;
  object-fit:cover;
  border-radius:15px;
  transition:.3s;
}
.gallery img:hover{transform:scale(1.05)}
.final{
  font-size:1.2rem;
  line-height:1.8;
}
footer{
  margin-top:60px;
  font-size:.9rem;
  opacity:.8;
}
.heart{
  position:fixed;
  bottom:-10px;
  font-size:20px;
  animation:float 6s linear infinite;
}
@keyframes fade{from{opacity:0}to{opacity:1}}
@keyframes float{
  0%{transform:translateY(0);opacity:0}
  10%{opacity:1}
  100%{transform:translateY(-100vh);opacity:0}
}
</style>
</head>

<body>

<!-- Music -->
<iframe style="display:none"
src="https://www.youtube.com/embed/0xq6cQwZKxw?autoplay=1&loop=1&playlist=0xq6cQwZKxw">
</iframe>

<div class="container">
  <h1>Nimmie ❤️</h1>
  <p class="subtitle">This page exists… because you do.</p>

  <a href="#question" class="btn">Tap gently 🌹</a>

  <div class="section card">
    <h2>🌹 Rose Day</h2>
    <p>If feelings had a color, they’d bloom like this.</p>
  </div>

  <div class="section card">
    <h2>🍫 Chocolate Day</h2>
    <p>Sweet moments are better when shared with you.</p>
  </div>

  <div class="section card">
    <h2>🤗 Hug Day</h2>
    <p>Some comforts don’t need arms — just presence.</p>
  </div>

  <div class="section card">
    <h2>❤️ Valentine’s Day</h2>
    <p class="final">
      I don’t promise perfection.<br>
      I promise honesty, effort,<br>
      and a heart that chooses you.
    </p>
  </div>

  <div id="question" class="section card">
    <h2>💌 Nimmie…</h2>
    <p class="final"><b>Will you be my Valentine?</b></p>
  </div>

  <div class="section">
    <h2>📸 Us</h2>
    <div class="gallery">
      <img src="images1.jpg">
      <img src="images2.jpg">
      <img src="images3.jpg">
      <img src="images4.jpg">
      <img src="images5.jpg">
      <img src="images6.jpg">
    </div>
  </div>

  <footer>
    Made with ❤️ by Aleem<br>
    Feb 14
  </footer>
</div>

<script>
setInterval(()=>{
  const h=document.createElement("div");
  h.className="heart";
  h.innerHTML="❤️";
  h.style.left=Math.random()*100+"vw";
  h.style.fontSize=Math.random()*20+15+"px";
  document.body.appendChild(h);
  setTimeout(()=>h.remove(),6000);
},500);
</script>

</body>
</html>
