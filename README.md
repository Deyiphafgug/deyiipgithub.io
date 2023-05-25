# deyiipgithub.io
deyiipgithub.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        @import 'https://fonts.googleapis.com/css?family=Inconsolata';

html {
  min-height: 100%;
}

body {
  box-sizing: border-box;
  height: 100%;
  width: 100%;
  background-color: #000000;
  background-image: radial-gradient(#11581E, #041607), url("https://media.giphy.com/media/oEI9uBYSzLpBK/giphy.gif");
  background-repeat: repeat;
  background-size: cover;
  font-family: 'Inconsolata', Helvetica, sans-serif;
  font-size: 1.5rem;
  color: hsla(120, 100%, 75%, 0.8);
  text-shadow:
      0 0 1ex rgba(51, 255, 51, 1),
      0 0 2px rgba(255, 255, 255, 0.8);
}

.noise {
  pointer-events: none;
  position: absolute;
  width: 100%;
  height: 100%;
  background-image: radial-gradient(#11581E, #041607), url("https://media.giphy.com/media/oEI9uBYSzLpBK/giphy.gif");
background-color: #041607;
 background-repeat: repeat;
  background-size: cover;
  z-index: -1;
  opacity: .02;
}

.overlay {
  pointer-events: none;
  position: absolute;
  width: 100%;
  height: 100%;
  background:
      repeating-linear-gradient(
      180deg,
      rgba(0, 0, 0, 0) 0,
      rgba(0, 0, 0, 0.3) 50%,
      rgba(0, 0, 0, 0) 100%);
  background-size: auto 4px;
  z-index: 1;
}

.overlay::before {
  content: "";
  pointer-events: none;
  position: absolute;
  display: block;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  width: 100%;
  height: 100%;
  background-image: linear-gradient(
      0deg,
      transparent 0%,
      rgba(32, 128, 32, 0.2) 2%,
      rgba(32, 128, 32, 0.8) 3%,
      rgba(32, 128, 32, 0.2) 3%,
      transparent 100%);
  background-repeat:repeat;
  animation: scan 4.5s linear 1s infinite;
}

@keyframes scan {
  0%        { background-position: 0 -100vh; }
  35%, 100% { background-position: 0 100vh; }
}

.terminal {
  box-sizing: inherit;
  position: absolute;
  height: 100%;
  width: 100%;
  max-width: 100%;
  padding: 4rem;
  text-transform: uppercase;
}

.output {
  color: rgba(128, 255, 128, 0.8);
  text-shadow:
      0 0 1px rgba(51, 255, 51, 0.4),
      0 0 2px rgba(255, 255, 255, 0.8);
}

.output::before {
  content: "> ";
}

/*
.input {
  color: rgba(192, 255, 192, 0.8);
  text-shadow:
      0 0 1px rgba(51, 255, 51, 0.4),
      0 0 2px rgba(255, 255, 255, 0.8);
}

.input::before {
  content: "$ ";
}
*/

a {
  color: #fff;
  text-decoration: none;
}

a::before {
  content: "[";
}

a::after {
  content: "]";
}

.errorcode {
  color: white;
}
img{
 display: inline;
 width: 300px;
 float: right;
}
.a{
  width: 250px;
}
    </style>
</head>
<body>
  <div class="">
    <div class="noise"></div>
    <div class="overlay"></div>
    <div class="terminal">
    </div>
      <img src="https://i.imgur.com/AQvmdcJ.jpg" alt="">
<div>
 <span> <h1>My name is  <div class="errorcode">Deyiphafgug</div></h1> </span>
</div>

  <p class="output"> Siz ateşi istediniz ben size cehennemi getirdim...</p>
  
  <p class="output"> Ben kimim ?</p>
  
  <p class="#">Başarısızlıkları bahane edip yılmayan ne olursa olsun başarmak için birşeylerden mahrum kalmaya alışmış bir gencim kısaca. Hayattan tek beklentisi itibar olan parayla hiçbir bağlantısı kalmamış birisiyim.</p>
  
  <p class="output"> Amacım ne?</p>
  <p class="#"> misyonumuz gereği türk halkını korumak ve elimizden gelen her konuda bilgilendirmek</p>
  <p class="output"> Ne iş ile uğraşıyorum ?</p>
  <img class="#"src="https://i.imgur.com/zoOQxhx.png" alt="">
 
  <p class="#"> -photoshop</p>
  <p class="#"> -yazılım</p>
  <p class="#"> -siber güvenlik</p>
  <p class="#"> -grafik tasarım</p>

</div>

</body>
</html>
