DOCTYPE html>
<html lang="uz">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>SMM jamoasi</title>
<link href="https://fonts.googleapis.com/css2?family=Unbounded:wght@600;800&family=Manrope:wght@400;500;700&display=swap" rel="stylesheet">
<style>
:root{--bg:#f6f3ff;--ink:#1d1533;--mut:#5d5578;--card:#fff;--ac:#ff4f81;--ac2:#5b3df5;--line:#ddd6f5;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#150f26;--ink:#f1ecff;--mut:#a89fc7;--card:#201838;--line:#352a5a}}
:root[data-theme="dark"]{--bg:#150f26;--ink:#f1ecff;--mut:#a89fc7;--card:#201838;--line:#352a5a}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--ink);font-family:Manrope,system-ui,sans-serif;line-height:1.6}
.w{max-width:960px;margin:0 auto;padding:0 20px}
nav{display:flex;justify-content:space-between;align-items:center;padding:18px 0}
.logo{font-family:Unbounded,sans-serif;font-weight:800;font-size:20px}
.logo i{color:var(--ac);font-style:normal}
nav a{color:var(--ink);text-decoration:none;margin-left:18px;font-size:15px}
h1,h2{font-family:Unbounded,sans-serif;line-height:1.15;margin:0}
h1{font-size:clamp(32px,7vw,60px);font-weight:800;margin:40px 0 18px;max-width:14em}
h2{font-size:clamp(24px,4vw,34px);margin-bottom:24px}
.lead{font-size:18px;color:var(--mut);max-width:34em}
.btn{display:inline-block;background:var(--ac2);color:#fff;padding:14px 26px;border-radius:999px;text-decoration:none;font-weight:700;margin-top:24px}
.btn:focus-visible,a:focus-visible{outline:3px solid var(--ac);outline-offset:3px}
section{padding:56px 0}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:16px}
.card{background:var(--card);border:1px solid var(--line);border-radius:18px;padding:22px}
.card h3{margin:0 0 8px;font-size:18px}
.card p{margin:0;color:var(--mut)}
.team .card{text-align:center}
.av{width:64px;height:64px;border-radius:50%;margin:0 auto 12px;display:grid;place-items:center;color:#fff;font-weight:800;font-size:22px;font-family:Unbounded,sans-serif}
.steps{counter-reset:s;display:grid;gap:12px}
.steps div{background:var(--card);border:1px solid var(--line);border-radius:14px;padding:16px 20px;display:flex;gap:14px}
.steps div::before{counter-increment:s;content:counter(s);color:var(--ac);font-family:Unbounded,sans-serif;font-weight:800}
.contact{background:var(--ac2);color:#fff;border-radius:24px;padding:36px 24px;text-align:center}
.contact .btn{background:#fff;color:var(--ac2)}
.blob{position:fixed;z-index:-1;border-radius:50%;filter:blur(70px);opacity:.35;animation:fl 12s ease-in-out infinite alternate}
.b1{width:300px;height:300px;background:var(--ac);top:-60px;right:-60px}
.b2{width:260px;height:260px;background:var(--ac2);bottom:10%;left:-80px;animation-delay:-5s}
@keyframes fl{to{transform:translate(40px,60px) scale(1.2)}}
@keyframes up{from{opacity:0;transform:translateY(28px)}to{opacity:1;transform:none}}
header h1{animation:up .8s .1s both}
header .lead{animation:up .8s .3s both}
header .btn{animation:up .8s .5s both,pulse 2.4s 1.5s infinite}
@keyframes pulse{0%,100%{box-shadow:0 0 0 0 rgba(91,61,245,.5)}50%{box-shadow:0 0 0 14px rgba(91,61,245,0)}}
.rv{opacity:0;transform:translateY(28px);transition:opacity .6s,transform .6s}
.rv.in{opacity:1;transform:none}
.card,.btn,.steps div{transition:transform .25s,box-shadow .25s,opacity .6s}
.card:hover,.steps div:hover{transform:translateY(-6px) rotate(-.6deg);box-shadow:0 14px 30px rgba(91,61,245,.2)}
.btn:hover{transform:scale(1.06)}
.btn:active{transform:scale(.95)}
.av{transition:transform .4s}
.card:hover .av{transform:rotate(360deg) scale(1.1)}
#snd{background:var(--card);border:1px solid var(--line);color:var(--ink);border-radius:999px;padding:8px 14px;font:inherit;font-size:14px;cursor:pointer;margin-left:18px}
@media (prefers-reduced-motion:reduce){*{animation:none!important;transition:none!important}.rv{opacity:1;transform:none}}
#xizmat .card{cursor:pointer}
#xizmat .card small{display:block;margin-top:12px;color:var(--ac2);font-weight:700;font-size:14px}
.ov{position:fixed;inset:0;z-index:50;background:rgba(15,8,35,.55);backdrop-filter:blur(6px);display:grid;place-items:center;padding:20px;opacity:0;visibility:hidden;transition:opacity .3s,visibility .3s}
.ov.open{opacity:1;visibility:visible}
.dlg{background:var(--card);border:1px solid var(--line);border-radius:26px;padding:32px 26px;width:100%;max-width:380px;text-align:center;position:relative;transform:translateY(40px) scale(.85);opacity:0;transition:transform .5s cubic-bezier(.2,1.3,.4,1),opacity .35s}
.ov.open .dlg{transform:none;opacity:1}
.dlg h3{font-family:Unbounded,sans-serif;font-size:20px;margin:0 0 6px}
.dlg p{color:var(--mut);margin:0 0 18px}
.pr{font-family:Unbounded,sans-serif;font-weight:800;font-size:56px;color:var(--ac);line-height:1.1}
.pr span{font-size:18px;color:var(--mut);font-weight:600}
.x{position:absolute;top:12px;right:14px;background:none;border:0;font-size:26px;color:var(--mut);cursor:pointer;width:40px;height:40px;border-radius:50%}
.x:hover{background:var(--bg)}
.dlg .btn{margin-top:20px}
.ov.open .pr{animation:pop .6s .25s both}
@keyframes pop{0%{transform:scale(.6);opacity:0}70%{transform:scale(1.12)}100%{transform:scale(1);opacity:1}}
.dlg .btn{display:block}.dlg .btn+.btn{margin-top:10px}.btn.alt{background:var(--ac)}.contact .btn{margin:8px 4px 0}
footer{padding:28px 0;color:var(--mut);font-size:14px;text-align:center}
</style>
</head>
<body>
<div class="w">
<nav><div class="logo">SMM<i>.</i></div><div><a href="#xizmat">Xizmatlar</a><a href="#jamoa">Jamoa</a><a href="#aloqa">Aloqa</a><button id="snd" aria-pressed="true">🔊 Ovoz</button></div></nav>

<header>
<h1>Brendingiz ijtimoiy tarmoqlarda ko‘rinsin</h1>
<p class="lead">SMM jamoasi — Instagram, Telegram va TikTok uchun strategiya, kontent va reklama bilan shug‘ullanadigan SMM jamoasi.</p>
<a class="btn" href="#aloqa">Bepul konsultatsiya olish</a>
</header>

<section id="xizmat">
<h2>Xizmatlarimiz</h2>
<div class="grid">
<div class="card"><h3>SMM strategiya</h3><p>Auditoriya, raqobatchilar va kontent rejasi — 30 kunga oldindan.</p></div>
<div class="card"><h3>Kontent ishlab chiqarish</h3><p>Postlar, Reels va Stories: suratga olish, montaj va matn.</p></div>
<div class="card"><h3>Target reklama</h3><p>Meta va TikTok reklama kampaniyalari, har hafta hisobot bilan.</p></div>
<div class="card"><h3>Hamjamiyat boshqaruvi</h3><p>Izohlar va xabarlarga tezkor javob, brend ovozini saqlash.</p></div>
</div>
</section>

<section>
<h2>Qanday ishlaymiz</h2>
<div class="steps">
<div>Brif va audit: maqsad va hozirgi holatni aniqlaymiz.</div>
<div>Strategiya va kontent reja: sizga tasdiqlash uchun yuboramiz.</div>
<div>Ishlab chiqarish va joylash: reja bo‘yicha har kuni.</div>
<div>Hisobot: oyiga natijalar va keyingi qadamlar.</div>
</div>
</section>

<section id="jamoa" class="team">
<h2>Jamoamiz</h2>
<div class="grid">
<div class="card"><div class="av" style="background:#5b3df5">O</div><h3>Oybek</h3><p>SMM menejer</p></div>
<div class="card"><div class="av" style="background:#ff4f81">A</div><h3>Alisher</h3><p>Kontent-maker va montajchi</p></div>
<div class="card"><div class="av" style="background:#12a98b">J</div><h3>Jonibek</h3><p>Kopirayter</p></div>
<div class="card"><div class="av" style="background:#e08a00">A</div><h3>Alisher</h3><p>Targetolog</p></div>
</div>
</section>

<section id="aloqa">
<div class="contact">
<h2>Loyihangizni muhokama qilamiz</h2>
<p>Telegramda yozing, hisobni tanlang. 1 ish kuni ichida javob beramiz.</p>
<a class="btn" href="https://t.me/xamidov" target="_blank" rel="noopener">@xamidov</a> <a class="btn" href="https://t.me/mangaqaralaring" target="_blank" rel="noopener">@mangaqaralaring</a>
</div>
</section>

<footer>© 2026 SMM jamoasi · abxllvss@gmail.com</footer>
</div>
<div class="blob b1"></div><div class="blob b2"></div>
<div class="ov" id="ov" aria-hidden="true"><div class="dlg" role="dialog" aria-modal="true" aria-labelledby="dt"><button class="x" id="xb" aria-label="Yopish">×</button><h3 id="dt"></h3><p id="dd"></p><div class="pr"><b id="pv">0</b><span> $ / oy</span></div><a class="btn" id="dc" href="https://t.me/xamidov">Yozish: @xamidov</a><a class="btn alt" id="dc2" href="https://t.me/mangaqaralaring">Yozish: @mangaqaralaring</a></div></div>
<script>
(function(){
var on=true,ctx=null;
var btn=document.getElementById('snd');
function ac(){try{if(!ctx)ctx=new (window.AudioContext||window.webkitAudioContext)();if(ctx.state==='suspended')ctx.resume();}catch(e){}return ctx}
function tone(f,d,type,v,f2){if(!on)return;var c=ac();if(!c)return;var o=c.createOscillator(),g=c.createGain(),t=c.currentTime;
o.type=type||'sine';o.frequency.setValueAtTime(f,t);if(f2)o.frequency.exponentialRampToValueAtTime(f2,t+d);
g.gain.setValueAtTime(v||.08,t);g.gain.exponentialRampToValueAtTime(.0001,t+d);o.connect(g);g.connect(c.destination);o.start(t);o.stop(t+d)}
function clk(down){if(!on)return;var c=ac();if(!c)return;var t=c.currentTime;
var o=c.createOscillator(),g=c.createGain(),f=c.createBiquadFilter();
f.type='lowpass';f.frequency.value=1400;
o.type='sine';o.frequency.setValueAtTime(down?520:620,t);o.frequency.exponentialRampToValueAtTime(down?330:420,t+.07);
g.gain.setValueAtTime(.0001,t);g.gain.linearRampToValueAtTime(down?.11:.06,t+.006);g.gain.exponentialRampToValueAtTime(.0001,t+.09);
o.connect(f);f.connect(g);g.connect(c.destination);o.start(t);o.stop(t+.1)}
var S={hover:function(){tone(660,.08,'sine',.04,880)},click:function(){clk(true)},pop:function(){tone(300,.15,'sine',.07,600)},
welcome:function(){tone(523,.15,'sine',.08);setTimeout(function(){tone(659,.15,'sine',.08)},120);setTimeout(function(){tone(784,.25,'sine',.08)},240)}};
btn.addEventListener('pointerdown',function(){clk(true)});btn.addEventListener('click',function(){on=!on;btn.textContent=on?'🔊 Ovoz':'🔇 Ovoz';btn.setAttribute('aria-pressed',on);if(on){ac();clk(false)}});
btn.textContent='🔊 Ovoz';
var first=false;
['pointerdown','keydown'].forEach(function(e){document.addEventListener(e,function(){if(!first){first=true;ac();if(on&&e==='pointerdown'&&event.target!==btn)S.welcome()}},{once:false})});
document.querySelectorAll('.card,.steps div').forEach(function(el){el.addEventListener('pointerenter',function(e){if(e.pointerType==='mouse')S.hover()})});
document.querySelectorAll('.btn,nav a').forEach(function(el){el.addEventListener('pointerenter',function(e){if(e.pointerType==='mouse')S.hover()});el.addEventListener('pointerdown',function(){clk(true)});el.addEventListener('pointerup',function(){clk(false)})});
document.querySelectorAll('.card').forEach(function(el){el.addEventListener('pointerdown',S.pop)});
var els=document.querySelectorAll('.card,.steps div,.contact,section h2');
els.forEach(function(e){e.classList.add('rv')});
if('IntersectionObserver' in window){var io=new IntersectionObserver(function(en){en.forEach(function(x){if(x.isIntersecting){var i=Array.prototype.indexOf.call(x.target.parentNode.children,x.target);x.target.style.transitionDelay=(i*80)+'ms';x.target.classList.add('in');io.unobserve(x.target)}})},{threshold:.15});els.forEach(function(e){io.observe(e)})}else{els.forEach(function(e){e.classList.add('in')})}
var TG=["xamidov","mangaqaralaring"],P=[400,380,570,680],ov=document.getElementById('ov'),pv=document.getElementById('pv'),tmr;
function openM(i,card){document.getElementById('dt').textContent=card.querySelector('h3').textContent;document.getElementById('dd').textContent=card.querySelector('p').textContent;
var msg=encodeURIComponent('Salom! "'+document.getElementById('dt').textContent+'" xizmati ('+P[i]+' $/oy) bo\u2018yicha yozyapman.');['dc','dc2'].forEach(function(id,k){var a=document.getElementById(id);a.href='https://t.me/'+TG[k]+'?text='+msg;a.target='_blank';a.rel='noopener'});ov.classList.add('open');ov.setAttribute('aria-hidden','false');tone(440,.18,'sine',.07,660);setTimeout(function(){tone(660,.2,'sine',.06,880)},110);
var t0=null,to=P[i];cancelAnimationFrame(tmr);function st(ts){if(!t0)t0=ts;var k=Math.min((ts-t0)/900,1);pv.textContent=Math.round(to*(1-Math.pow(1-k,3)));if(k<1)tmr=requestAnimationFrame(st)}tmr=requestAnimationFrame(st);
document.getElementById('xb').focus()}
function closeM(){if(!ov.classList.contains('open'))return;ov.classList.remove('open');ov.setAttribute('aria-hidden','true');tone(500,.12,'sine',.05,300)}
document.querySelectorAll('#xizmat .card').forEach(function(c,i){c.setAttribute('tabindex','0');c.setAttribute('role','button');c.insertAdjacentHTML('beforeend','<small>Narxni ko\u2018rish</small>');
c.addEventListener('click',function(){openM(i,c)});c.addEventListener('keydown',function(e){if(e.key==='Enter'||e.key===' '){e.preventDefault();openM(i,c)}})});
document.getElementById('xb').addEventListener('click',closeM);
ov.addEventListener('click',function(e){if(e.target===ov)closeM()});
document.getElementById('dc').addEventListener('click',closeM);document.getElementById('dc2').addEventListener('click',closeM);
document.addEventListener('keydown',function(e){if(e.key==='Escape')closeM()});
function goTG(u){var left=false;function v(){if(document.hidden)left=true}document.addEventListener('visibilitychange',v);
try{window.location.href='tg://resolve?domain='+u}catch(e){}
setTimeout(function(){document.removeEventListener('visibilitychange',v);if(!left&&!document.hidden)window.open('https://t.me/'+u,'_blank','noopener')},1200)}
document.addEventListener('click',function(e){var a=e.target.closest&&e.target.closest('a[href*="t.me/"]');if(!a)return;var m=a.href.match(/t\.me\/([A-Za-z0-9_]+)/);if(!m)return;e.preventDefault();goTG(m[1])},true);
})();
</script>
</body>
</html>

<!--
**alisheer511/alisheer511** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
