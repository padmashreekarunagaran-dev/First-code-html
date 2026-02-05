# First-code-html
My first html codee
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Dudu ❤️ Bubu</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
* {
  box-sizing: border-box;
  font-family: 'Segoe UI', sans-serif;
}

body {
  margin: 0;
  background: #ffd6e8;
  overflow: hidden;
}

.screen {
  display: none;
  height: 100vh;
  padding: 20px;
  overflow-y: auto;
  text-align: center;
}

.active {
  display: block;
}

h1 {
  color: #d63384;
}

p {
  color: #4a2c2a;
  font-size: 18px;
  line-height: 1.6;
  white-space: pre-wrap;
}

button {
  margin-top: 20px;
  padding: 12px 24px;
  border: none;
  border-radius: 25px;
  background: #ff5fa2;
  color: white;
  font-size: 16px;
  cursor: pointer;
}

input {
  padding: 12px;
  width: 80%;
  max-width: 300px;
  border-radius: 10px;
  border: none;
  font-size: 18px;
  text-align: center;
}

/* GIF STYLE */
.gif {
  width: 220px;
  max-width: 80%;
  margin: 20px auto;
  display: block;
}

/* Hearts */
.heart {
  position: fixed;
  width: 20px;
  height: 20px;
  background: pink;
  transform: rotate(45deg);
  animation: float 6s linear infinite;
  opacity: 0.6;
}

.heart::before,
.heart::after {
  content: '';
  width: 20px;
  height: 20px;
  background: pink;
  border-radius: 50%;
  position: absolute;
}

.heart::before {
  top: -10px;
  left: 0;
}

.heart::after {
  left: -10px;
  top: 0;
}

@keyframes float {
  0% { bottom: -10%; }
  100% { bottom: 110%; }
}
</style>
</head>

<body>

<!-- MUSIC -->
<audio id="music" loop autoplay>
  <source src="perfect.mp3" type="audio/mpeg">
</audio>

<!-- PASSWORD SCREEN -->
<div class="screen active">
  <h1>Hey Niky…🐻💕</h1>
  <p>Bubu made something just for you…  
Please don’t rush 😁</p>

  <img class="gif" src="https://media.tenor.com/l3Sl9NaGeKIAAAAj/i-love-you-so-much.gif">

  <input type="password" placeholder="Enter the password">
  <p><i>hint: it’s our day..</i></p>
  <button onclick="nextScreen()">Enter 💝</button>
</div>

<!-- LETTER 1 -->
<div class="screen">
<p>
My Love,
I don’t know how to put everything I feel into words, but I’ll try—because you deserve to know how deeply you mean to me.
From the moment you came into my life, things started feeling warmer, calmer, and somehow more meaningful. You make me smile without trying, laugh without effort, and feel safe just by being you. Even on my worst days, the thought of you gives me comfort and strength.
I love the way you care, the way you listen, and the way you understand me even when I don’t say much. You make me feel valued, respected, and truly loved. Being with you has taught me what love really feels like—not perfect, but real, honest, and beautiful.
Thank you for being my support, my happiness, my best friend, and my favorite person. Thank you for choosing me, for standing by me, and for loving me the way you do. I promise to cherish you, support you, and love you more with every passing day.
No matter where life takes us, my heart will always find its way back to you. You are my today, my tomorrow, and all the little moments in between.
</p>

<img class="gif" src="https://media.tenor.com/2bw-Zzp-mTMAAAAj/bear-hug.gif">

<button onclick="nextScreen()">Next 💌</button>
</div>

<!-- LETTER 2 -->
<div class="screen">
<p>
<h1>Niky u remember this?😃</h1>
I never dreamed that u would pop into my life....
I never wondered that u would become so close to me like no one....
I never wanted to be with anyone bcz it always ends up breaking....
I never thought of getting close to anyone bcz I was afraid of attachments
I never thought that I would miss a person so badly.....
U completely changed my feelings unexpectedly, which I thought nobody can do...
U literally don't know how I feel about u...
but I found that "I miss u " was not just a normal word
It was always said with lots of love which I was lagging to express!!!!
I just wanted to let u know that "I love you"
nd i hope, i can be urs!!!!
So yes,
Can I be urs???
</p>

<img class="gif" src="https://media.tenor.com/adYqr_srXkQAAAAj/holding-hands.gif">

<button onclick="nextScreen()">Next 💌</button>
</div>

<!-- LETTER 3 -->
<div class="screen">
<p>
<h1>when I missed you ❤️‍🩹</h1>
Idk why whn ur away,my heart feels tight
I miss ur smile.
I miss the warmth of ur hands in mine.
I miss staring into ur eyes.
i miss ur touch.
I miss u beside me.
I miss u completely.
i never new i could love someone so hard..
idk whether u feel the way I miss you
but idk wts happening within me..
maybe u can feel I'm overreacting
but idk why I'm missing u so much even after being around u..
I wish u could feel placing ur hand over ur heart
nd feel how much I miss you with every heartbeat...
at end u made me obsessed with u 🥺
</p>

<img class="gif" src="https://media.tenor.com/hbNrud38kA4AAAAj/mimibubu.gif">

<button onclick="nextScreen()">Next 💌</button>
</div>

<!-- LETTER 4 -->
<div class="screen">
<p>
<h1>when you asked me "why only me?"💗</h1>
I saw you were perfect nd so loved you,
Then I saw you weren't perfect thn I loved you more!!!
Your just like wind,can't see things but can feel lot!!!
My hands always feels incomplete without filling the gaps with your fingers
Your all mine which I would never share with anyone!!!
</p>

<img class="gif" src="https://media.tenor.com/90xN7I6NjecAAAAj/bubu-dudu-sseeyall.gif">

<button onclick="nextScreen()">Next 💌</button>
</div>

<!-- LETTER 5 -->
<div class="screen">
<p>
<h1>How much you mean to me💖</h1>
Your a cute little handsome boy...
You never fails to love, care, irritate,calm...
Your eyes decide my mood...
Your smile takes me to heaven...
Your warmth feels like home...
Holding your hands feel like mine...
Holding your arms gives strength...
Lying on your shoulders gives me peace...
Your kisses nd hugs feels like I'm your own!!!
Your name brings me smile!!!!
Your presence takes my attention!!!!
You never new how much I love you!!!!!
You never new how much I miss you!!!!
You never new how much you matter to me!!!!
Nd yeah I will never fail to give you all the love nd care you deserve
Your mine 💝
</p>

<img class="gif" src="https://media.tenor.com/QhaBUYKxgb0AAAAj/dance-gomu.gif">

<button onclick="nextScreen()">Next 💌</button>
</div>

<!-- LETTER 6 -->
<div class="screen">
<p>
<h1>Guess what niky😃</h1>
U had me at hello
I am going nowhere
No matter the pain
No matter how much it rain
No matter how much the wind blows
No matter how much ur heart broke
I am always here to heal
Whenever you need
Remember ur heart is safe
</p>

<img class="gif" src="https://media.tenor.com/zmAsQOIKdhgAAAAj/milk-and-mocha-cute.gif">

<button onclick="nextScreen()">niky click here for surprise 🎁</button>
</div>

<!-- SURPRISE -->
<div class="screen">
<p>
<h2>HAPPY VALENTINE'S DAY MY LOVE 💞</h2><br>
<h1>I LOVE YOU NIKY❣️</h1><br>
<h2>❤️Bubu always love you forever ❤️</h2>
</p>

<img class="gif" src="https://media1.tenor.com/m/LxTbPto0fdoAAAAd/bubu-rose-bubu-sweet.gif">
</div>

<script>
let screens = document.querySelectorAll('.screen');
let current = 0;

function nextScreen() {
  screens[current].classList.remove('active');
  current++;
  screens[current].classList.add('active');
}

// Hearts generator
setInterval(() => {
  let heart = document.createElement('div');
  heart.className = 'heart';
  heart.style.left = Math.random() * 100 + 'vw';
  heart.style.animationDuration = (Math.random() * 3 + 4) + 's';
  document.body.appendChild(heart);
  setTimeout(() => heart.remove(), 7000);
}, 500);
</script>

</body>
</html>
