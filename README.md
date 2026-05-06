<!DOCTYPE html>
<!-- saved from url=(0032)http://127.0.0.1:5500/index.html -->
<html lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">

<title>Luxury Kitty Party Invitation ✨</title>

<link href="./Kitty Party Invitation card✨_files/css2" rel="stylesheet">

<style>

*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  -webkit-tap-highlight-color:transparent;
}

:root{
  --purple:#7d5fff;
  --pink:#ff8fcf;
  --mint:#9ef0cf;
  --gold:#ffd76d;
  --white:#ffffff;
  --dark:#3c3158;
}

html{
  scroll-behavior:smooth;
}

body{
  min-height:100vh;

  background:
  linear-gradient(
  135deg,
  #f5ebff 0%,
  #fceeff 40%,
  #ebfff6 100%
  );

  font-family:'Poppins',sans-serif;

  display:flex;
  justify-content:center;
  align-items:center;

  overflow-x:hidden;

  position:relative;

  padding:
  max(20px,env(safe-area-inset-top))
  max(20px,env(safe-area-inset-right))
  max(20px,env(safe-area-inset-bottom))
  max(20px,env(safe-area-inset-left));
}

/* BACKGROUND GLOW */

.blur{
  position:fixed;
  width:280px;
  height:280px;
  border-radius:50%;
  filter:blur(90px);
  opacity:.28;
  z-index:0;
  animation:move 10s ease-in-out infinite alternate;
}

.blur1{
  background:#c8a5ff;
  top:-60px;
  left:-60px;
}

.blur2{
  background:#b6ffe4;
  bottom:-60px;
  right:-60px;
}

@keyframes move{
  100%{
    transform:
    translateY(40px)
    translateX(20px);
  }
}

/* FLOATING EMOJIS */

.bg{
  position:fixed;
  z-index:0;
  opacity:.16;
  animation:float 6s ease-in-out infinite;
  pointer-events:none;
}

.bg1{
  top:8%;
  left:5%;
  font-size:60px;
}

.bg2{
  top:72%;
  right:5%;
  font-size:70px;
  animation-delay:1s;
}

.bg3{
  top:28%;
  right:10%;
  font-size:50px;
  animation-delay:2s;
}

.bg4{
  bottom:8%;
  left:10%;
  font-size:65px;
  animation-delay:1.5s;
}

@keyframes float{
  0%,100%{
    transform:translateY(0);
  }
  50%{
    transform:translateY(-18px);
  }
}

/* CARD */

.card{
  width:min(92vw,480px);

  background:
  rgba(255,255,255,.72);

  backdrop-filter:blur(16px);
  -webkit-backdrop-filter:blur(16px);

  border-radius:30px;

  overflow:hidden;

  position:relative;
  z-index:2;

  border:1px solid rgba(255,255,255,.4);

  box-shadow:
  0 20px 60px rgba(125,95,255,.22);

  animation:cardEnter 1s ease;
}

@keyframes cardEnter{
  from{
    opacity:0;
    transform:
    translateY(40px)
    scale(.96);
  }

  to{
    opacity:1;
    transform:
    translateY(0)
    scale(1);
  }
}

/* TOP BORDER */

.topbar,
.bottombar{
  height:14px;

  background:
  linear-gradient(
  90deg,
  transparent,
  #ffd76d,
  #fff2b0,
  #ffd76d,
  transparent
  );
}

/* INNER */

.inner{
  padding:34px 26px;
}

/* TAG */

.tag{
  text-align:center;

  font-family:'Great Vibes',cursive;

  color:#58a082;

  font-size:30px;

  margin-bottom:8px;
}

.join{
  text-align:center;

  letter-spacing:5px;

  text-transform:uppercase;

  font-size:10px;

  color:#777;

  margin-bottom:14px;
}

/* TITLE */

.title{
  text-align:center;

  font-family:'Great Vibes',cursive;

  font-size:clamp(54px,13vw,84px);

  color:var(--purple);

  line-height:1;

  transition:.35s;

  cursor:pointer;

  text-shadow:
  0 10px 25px rgba(125,95,255,.22);
}

.title:hover{
  transform:scale(1.04);
}

/* HEEL */

.heel{
  text-align:center;

  font-size:58px;

  margin:18px 0;

  animation:heelFloat 3s ease-in-out infinite;

  cursor:pointer;
}

@keyframes heelFloat{
  0%,100%{
    transform:
    translateY(0)
    rotate(-5deg);
  }

  50%{
    transform:
    translateY(-10px)
    rotate(2deg);
  }
}

/* DIVIDER */

.divider{
  display:flex;
  align-items:center;
  gap:10px;
  margin:18px 0;
}

.line{
  flex:1;
  height:1px;

  background:
  linear-gradient(
  to right,
  transparent,
  #ffd76d,
  transparent
  );
}

.gem{
  color:#ffd76d;
}

/* THOUGHT */

.thought{
  position:relative;

  overflow:hidden;

  border-radius:22px;

  padding:22px;

  text-align:center;

  cursor:pointer;

  transition:.35s;

  background:
  linear-gradient(
  135deg,
  rgba(255,255,255,.55),
  rgba(255,255,255,.25)
  );

  border:1px solid rgba(255,255,255,.4);

  margin-bottom:22px;
}

.thought:hover{
  transform:translateY(-4px);

  box-shadow:
  0 14px 30px rgba(125,95,255,.14);
}

.thought::before{
  content:'';

  position:absolute;

  top:0;
  left:-100%;

  width:100%;
  height:100%;

  background:
  linear-gradient(
  90deg,
  transparent,
  rgba(255,255,255,.45),
  transparent
  );

  transition:.8s;
}

.thought:hover::before{
  left:100%;
}

.thought-label{
  font-size:10px;

  letter-spacing:4px;

  text-transform:uppercase;

  color:#d29b00;

  margin-bottom:10px;
}

.thought-text{
  font-family:'Great Vibes',cursive;

  color:var(--purple);

  font-size:30px;

  line-height:1.4;

  transition:.3s;
}

.tap{
  margin-top:10px;

  font-size:10px;

  letter-spacing:2px;

  color:#888;
}

/* COUNTDOWN */

.countdown{
  display:grid;

  grid-template-columns:repeat(4,1fr);

  gap:10px;

  margin:24px 0 14px;
}

.box{
  background:
  rgba(255,255,255,.65);

  backdrop-filter:blur(10px);

  border-radius:18px;

  padding:16px 8px;

  text-align:center;

  border:1px solid rgba(255,255,255,.45);

  transition:.35s;

  position:relative;

  overflow:hidden;
}

.box:hover{
  transform:translateY(-4px);
}

.box::after{
  content:'';

  position:absolute;

  width:150%;
  height:2px;

  top:0;
  left:-150%;

  background:
  linear-gradient(
  to right,
  transparent,
  white,
  transparent
  );

  animation:shine 3s linear infinite;
}

@keyframes shine{
  100%{
    left:150%;
  }
}

.num{
  display:block;

  font-family:'Cinzel',serif;

  color:var(--purple);

  font-size:clamp(22px,5vw,34px);

  animation:pulse 2s ease-in-out infinite;
}

@keyframes pulse{
  0%,100%{
    transform:scale(1);
  }

  50%{
    transform:scale(1.08);
  }
}

.lab{
  margin-top:5px;

  font-size:9px;

  text-transform:uppercase;

  letter-spacing:2px;

  color:#c09000;
}

.count-message{
  text-align:center;

  font-family:'Great Vibes',cursive;

  color:var(--purple);

  font-size:32px;

  margin-bottom:22px;

  animation:glow 3s ease-in-out infinite;
}

@keyframes glow{
  0%,100%{
    opacity:.7;
  }

  50%{
    opacity:1;

    text-shadow:
    0 0 18px rgba(160,120,255,.45);
  }
}

/* DATE */

.date{
  border-radius:22px;

  padding:20px;

  text-align:center;

  background:
  linear-gradient(
  135deg,
  rgba(255,255,255,.55),
  rgba(255,255,255,.25)
  );

  border:1px solid rgba(255,255,255,.4);

  margin-bottom:20px;
}

.date-main{
  font-family:'Cinzel',serif;

  color:var(--purple);

  letter-spacing:3px;

  font-size:20px;
}

.date-sub{
  margin-top:8px;

  color:#666;

  letter-spacing:1px;

  font-size:12px;
}

/* BUTTONS */

.buttons{
  display:flex;
  flex-direction:column;
  gap:12px;

  margin-bottom:20px;
}

.btn{
  border:none;

  border-radius:18px;

  padding:15px;

  cursor:pointer;

  transition:.35s;

  color:white;

  font-size:12px;

  letter-spacing:2px;

  text-transform:uppercase;

  font-weight:600;
}

.btn:hover{
  transform:
  translateY(-3px)
  scale(1.02);
}

.btn1{
  background:
  linear-gradient(
  135deg,
  #ff8fcf,
  #b38dff
  );
}

.btn2{
  background:
  linear-gradient(
  135deg,
  #84f7d0,
  #8eb6ff
  );
}

.btn3{
  background:
  linear-gradient(
  135deg,
  #ffc58f,
  #ff8fb2
  );
}

/* RSVP */

.rsvp a{
  display:block;

  text-align:center;

  text-decoration:none;

  padding:16px;

  border-radius:18px;

  background:
  linear-gradient(
  135deg,
  #7d5fff,
  #a785ff
  );

  color:white;

  letter-spacing:4px;

  font-size:12px;

  font-weight:600;

  transition:.35s;
}

.rsvp a:hover{
  transform:
  translateY(-3px)
  scale(1.02);
}

/* POPUP */

.popup{
  position:fixed;

  inset:0;

  background:
  rgba(30,20,50,.5);

  backdrop-filter:blur(6px);

  display:flex;
  justify-content:center;
  align-items:center;

  opacity:0;

  pointer-events:none;

  transition:.35s;

  z-index:999;
}

.popup.active{
  opacity:1;
  pointer-events:all;
}

.popup-box{
  width:90%;
  max-width:360px;

  background:white;

  border-radius:28px;

  padding:34px 24px;

  text-align:center;

  transform:scale(.86);

  transition:.35s;
}

.popup.active .popup-box{
  transform:scale(1);
}

.popemoji{
  font-size:58px;
  margin-bottom:14px;
}

.poptitle{
  font-family:'Great Vibes',cursive;

  color:var(--purple);

  font-size:42px;

  margin-bottom:14px;
}

.popbody{
  color:#666;

  line-height:1.8;

  margin-bottom:20px;
}

.close{
  border:none;

  border-radius:14px;

  padding:12px 28px;

  cursor:pointer;

  background:
  linear-gradient(
  135deg,
  #7d5fff,
  #b18fff
  );

  color:white;

  font-weight:600;
}

/* FLOATING HEARTS */

.float{
  position:fixed;

  pointer-events:none;

  z-index:99999;

  animation:floatUp 2.5s ease-out forwards;
}

@keyframes floatUp{
  100%{
    transform:
    translateY(-220px)
    scale(.3);

    opacity:0;
  }
}

/* CONFETTI */

.confetti{
  position:fixed;

  width:12px;
  height:12px;

  top:-20px;

  z-index:99999;

  animation:fall linear forwards;
}

@keyframes fall{
  100%{
    transform:
    translateY(110vh)
    rotate(720deg);

    opacity:0;
  }
}

/* MOBILE */

@media(max-width:600px){

  body{
    align-items:flex-start;
    padding-top:24px;
  }

  .inner{
    padding:28px 18px;
  }

  .thought-text{
    font-size:24px;
  }

  .count-message{
    font-size:26px;
    line-height:1.3;
  }

  .date-main{
    font-size:16px;
  }

  .popup-box{
    padding:28px 18px;
  }

}

</style>
</head>

<body>

<div class="blur blur1"></div>
<div class="blur blur2"></div>

<div class="bg bg1">🦋</div>
<div class="bg bg2">🌸</div>
<div class="bg bg3">✨</div>
<div class="bg bg4">💖</div>

<div class="card">

<div class="topbar"></div>

<div class="inner">

<div class="tag">
Friends, Fun &amp; Beautiful Memories
</div>

<div class="join">
Join us for a magical evening
</div>

<div class="title" onclick="showPopup(&#39;title&#39;)">
Kitty Party
</div>

<div class="heel" onclick="showPopup(&#39;heel&#39;)">
👠
</div>

<div class="divider">
<div class="line"></div>
<div class="gem">✦ ✧ ✦</div>
<div class="line"></div>
</div>

<div class="thought" onclick="nextThought()">

<div class="thought-label">
Beautiful Thought
</div>

<div class="thought-text" id="thoughtText">
Life becomes magical when beautiful souls gather together ✨
</div>

<div class="tap">
tap to change ↺
</div>

</div>

<div class="countdown">

<div class="box">
<span class="num" id="days">04</span>
<div class="lab">Days</div>
</div>

<div class="box">
<span class="num" id="hours">16</span>
<div class="lab">Hours</div>
</div>

<div class="box">
<span class="num" id="mins">49</span>
<div class="lab">Mins</div>
</div>

<div class="box">
<span class="num" id="secs">32</span>
<div class="lab">Secs</div>
</div>

</div>

<div class="count-message" id="countMsg">🌸 The magical evening is getting closer 🌸</div>

<div class="date">

<div class="date-main">
MON | 11 · 05 | 3:45 PM
</div>

<div class="date-sub">
Monday • Mercury Banquet Hall • Be Glamorous 💜
</div>

</div>

<div class="buttons">

<button class="btn btn1" onclick="confetti()">
🎉 Celebrate
</button>

<button class="btn btn2" onclick="showPopup(&#39;menu&#39;)">
🍰 Sneak Peek
</button>

<button class="btn btn3" onclick="sendLove()">
💌 Send Love
</button>

</div>

<div class="rsvp">
<a href="tel:+917017583731">
RSVP NOW
</a>
</div>

</div>

<div class="bottombar"></div>

</div>

<!-- POPUP -->

<div class="popup" id="popup" onclick="closePopup(event)">

<div class="popup-box">

<div class="popemoji" id="popemoji">
✨
</div>

<div class="poptitle" id="poptitle">
Hello
</div>

<div class="popbody" id="popbody">
Welcome
</div>

<button class="close" onclick="closePopup()">
Close
</button>

</div>

</div>

<script>

/* THOUGHTS */

const thoughts = [

"Life becomes magical when beautiful souls gather together ✨",

"Queens don't compete — they celebrate each other 👑",

"A room full of laughter is a room full of memories 🌸",

"Sparkle wherever you go darling ✨",

"Tea tastes sweeter with friends beside you ☕",

"Good friends create unforgettable moments 💖",

"Some evenings deserve glam, heels & endless laughter 👠",

"Beautiful hearts create beautiful memories 🌺",

"Glow differently when surrounded by love 💎",

"Every party becomes special because of people like you ✨",

"Collect moments, not things 💕",

"Tonight is about joy, sparkle & friendship 🌸"

];

let t = 0;

function nextThought(){

  t = (t + 1) % thoughts.length;

  const el = document.getElementById("thoughtText");

  el.style.opacity = 0;

  setTimeout(()=>{

    el.innerHTML = thoughts[t];

    el.style.opacity = 1;

  },250);

  createFloat('✨');

}

/* POPUP DATA */

const data = {

title:{
emoji:'✨',
title:'A Special Invitation',
body:'Some evenings become unforgettable because of the people attending them — and your presence will make this celebration magical 💜'
},

heel:{
emoji:'👠',
title:'Walk In Like Royalty',
body:'Tonight is your moment to shine brighter than ever. Wear confidence, carry elegance & let your smile steal the spotlight ✨'
},

menu:{
emoji:'🍰',
title:'A Feast Awaits You',
body:'From delicious snacks to desserts and endless chai conversations — every corner of this evening is prepared with love ☕💖'
}

};

function showPopup(key){

  document.getElementById('popemoji').innerHTML =
  data[key].emoji;

  document.getElementById('poptitle').innerHTML =
  data[key].title;

  document.getElementById('popbody').innerHTML =
  data[key].body;

  document.getElementById('popup')
  .classList.add('active');

  confetti();

}

function closePopup(e){

  if(
    !e ||
    e.target.id === 'popup'
  ){

    document.getElementById('popup')
    .classList.remove('active');

  }

}

/* COUNTDOWN */

function updateCountdown(){

  const target =
  new Date('2026-05-11T15:45:00');

  const now = new Date();

  const diff = target - now;

  if(diff <= 0){

    document.getElementById('countMsg').innerHTML =
    '💖 The celebration has begun gorgeous! 💖';

    return;

  }

  const d =
  Math.floor(diff / 86400000);

  const h =
  Math.floor((diff % 86400000)/3600000);

  const m =
  Math.floor((diff % 3600000)/60000);

  const s =
  Math.floor((diff % 60000)/1000);

  document.getElementById('days').innerHTML =
  String(d).padStart(2,'0');

  document.getElementById('hours').innerHTML =
  String(h).padStart(2,'0');

  document.getElementById('mins').innerHTML =
  String(m).padStart(2,'0');

  document.getElementById('secs').innerHTML =
  String(s).padStart(2,'0');

  if(d > 5){

    document.getElementById('countMsg').innerHTML =
    '✨ Counting moments until we celebrate together ✨';

  }

  else if(d > 1){

    document.getElementById('countMsg').innerHTML =
    '🌸 The magical evening is getting closer 🌸';

  }

  else{

    document.getElementById('countMsg').innerHTML =
    '🎉 It’s almost party time beautiful 🎉';

  }

}

updateCountdown();

setInterval(updateCountdown,1000);

/* CONFETTI */

const colors = [
'#d8b4ff',
'#b9ffe3',
'#ffd6ec',
'#ffe38f',
'#ffffff'
];

function confetti(count = 70){

  for(let i=0;i<count;i++){

    setTimeout(()=>{

      const el =
      document.createElement('div');

      el.className = 'confetti';

      el.style.left =
      Math.random()*100 + 'vw';

      el.style.background =
      colors[
        Math.floor(
          Math.random()*colors.length
        )
      ];

      el.style.animationDuration =
      2 + Math.random()*2 + 's';

      el.style.transform =
      `rotate(${Math.random()*360}deg)`;

      document.body.appendChild(el);

      setTimeout(()=>{
        el.remove();
      },4000);

    },i*20);

  }

}

/* FLOATING EMOJIS */

function createFloat(emoji){

  const el =
  document.createElement('div');

  el.className = 'float';

  el.innerHTML = emoji;

  el.style.left =
  Math.random()*window.innerWidth + 'px';

  el.style.top =
  window.innerHeight - 100 + 'px';

  el.style.fontSize =
  20 + Math.random()*20 + 'px';

  document.body.appendChild(el);

  setTimeout(()=>{
    el.remove();
  },2500);

}

/* LOVE */

function sendLove(){

  const arr = [
  '💜',
  '✨',
  '🌸',
  '💕',
  '🦋',
  '💎'
  ];

  for(let i=0;i<16;i++){

    setTimeout(()=>{

      createFloat(
        arr[
          Math.floor(
            Math.random()*arr.length
          )
        ]
      );

    },i*120);

  }

}

/* AUTO MAGIC */

setInterval(()=>{

  const arr = [
  '✨',
  '🌸',
  '💖',
  '🦋'
  ];

  createFloat(
    arr[
      Math.floor(
        Math.random()*arr.length
      )
    ]
  );

},2500);

/* TOUCH EFFECT */

document.querySelectorAll(
'.btn,.thought,.title,.heel'
).forEach(el=>{

  el.addEventListener('touchstart',()=>{

    el.style.transform='scale(.96)';

  });

  el.addEventListener('touchend',()=>{

    setTimeout(()=>{
      el.style.transform='';
    },120);

  });

});

/* LOAD CONFETTI */

window.addEventListener('load',()=>{

  setTimeout(()=>{
    confetti(40);
  },700);

});

</script>

<!-- Code injected by live-server -->
<script>
	// <![CDATA[  <-- For SVG support
	if ('WebSocket' in window) {
		(function () {
			function refreshCSS() {
				var sheets = [].slice.call(document.getElementsByTagName("link"));
				var head = document.getElementsByTagName("head")[0];
				for (var i = 0; i < sheets.length; ++i) {
					var elem = sheets[i];
					var parent = elem.parentElement || head;
					parent.removeChild(elem);
					var rel = elem.rel;
					if (elem.href && typeof rel != "string" || rel.length == 0 || rel.toLowerCase() == "stylesheet") {
						var url = elem.href.replace(/(&|\?)_cacheOverride=\d+/, '');
						elem.href = url + (url.indexOf('?') >= 0 ? '&' : '?') + '_cacheOverride=' + (new Date().valueOf());
					}
					parent.appendChild(elem);
				}
			}
			var protocol = window.location.protocol === 'http:' ? 'ws://' : 'wss://';
			var address = protocol + window.location.host + window.location.pathname + '/ws';
			var socket = new WebSocket(address);
			socket.onmessage = function (msg) {
				if (msg.data == 'reload') window.location.reload();
				else if (msg.data == 'refreshcss') refreshCSS();
			};
			if (sessionStorage && !sessionStorage.getItem('IsThisFirstTime_Log_From_LiveServer')) {
				console.log('Live reload enabled.');
				sessionStorage.setItem('IsThisFirstTime_Log_From_LiveServer', true);
			}
		})();
	}
	else {
		console.error('Upgrade your browser. This Browser is NOT supported WebSocket for Live-Reloading.');
	}
	// ]]>
</script>

<div class="float" style="left: 636.532px; top: 713px; font-size: 26.2696px;">🦋</div></body></html>
