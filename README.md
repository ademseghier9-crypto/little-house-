# little-house-<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Little House | مقهى ليتل هاوس</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;600;800&family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
<style>
:root{--bg:#10121B;--pu:#8065F5;--cy:#29C7D8;--tx:#F3F4F6;--card:#1C2030;--warm:#E9A66A;--mut:#a4a8b8;color-scheme:dark;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
*,*::before,*::after{box-sizing:inherit;margin:0}
html{scroll-behavior:smooth;scroll-padding-top:84px}
body{background:var(--bg);color:var(--tx);font-family:Cairo,Tajawal,sans-serif;line-height:1.7;overflow-x:hidden}
body.en{font-family:Inter,Cairo,sans-serif}
a{color:inherit;text-decoration:none}
.wrap{max-width:1100px;margin:auto;padding:0 20px}
section{padding:72px 0}
h2{font-size:clamp(1.6rem,4vw,2.3rem);font-weight:800;margin-bottom:8px}
h2 span,.hero h1 span{background:linear-gradient(90deg,var(--pu),var(--cy));-webkit-background-clip:text;background-clip:text;color:transparent}
.sub{color:var(--mut);margin-bottom:32px}
.btn{display:inline-flex;align-items:center;gap:8px;padding:12px 26px;border-radius:999px;border:0;cursor:pointer;font:inherit;font-weight:700;transition:.3s;color:#fff;background:linear-gradient(90deg,var(--pu),var(--cy));box-shadow:0 8px 24px rgba(128,101,245,.35)}
.btn:hover{transform:translateY(-3px);box-shadow:0 12px 30px rgba(41,199,216,.4)}
.btn.o{background:transparent;border:2px solid var(--pu);box-shadow:none}
.card{display:block;background:var(--card);border-radius:20px;padding:24px;box-shadow:0 10px 30px rgba(0,0,0,.35);transition:.3s;border:1px solid rgba(255,255,255,.05)}
.card:hover{transform:translateY(-5px);border-color:var(--pu)}
nav{position:sticky;top:env(safe-area-inset-top,0px);z-index:20;background:rgba(16,18,27,.88);backdrop-filter:blur(12px);border-bottom:1px solid rgba(255,255,255,.06)}
nav .wrap{display:flex;align-items:center;gap:16px;min-height:68px;flex-wrap:wrap}
.brand{display:flex;align-items:center;gap:10px;font-weight:800;font-size:1.1rem}
.brand img{width:44px;height:44px;border-radius:50%;box-shadow:0 0 0 2px var(--cy)}
.links{display:flex;gap:18px;margin-inline:auto;overflow-x:auto;max-width:100%;scrollbar-width:none;font-size:.95rem}
.links a{white-space:nowrap;color:var(--mut);transition:.3s}.links a:hover{color:var(--cy)}
.lang{background:var(--card);color:var(--tx);border:1px solid var(--pu);border-radius:999px;padding:6px 14px;cursor:pointer;font:inherit;font-weight:700}
.hero{position:relative;padding:90px 0 80px;overflow:hidden}
.hero::before,.hero::after{content:"";position:absolute;width:420px;height:420px;border-radius:50%;filter:blur(110px);opacity:.45}
.hero::before{background:var(--pu);top:-120px;inset-inline-start:-100px}
.hero::after{background:var(--cy);bottom:-160px;inset-inline-end:-100px}
.hero .wrap{position:relative;z-index:1;display:grid;grid-template-columns:1.1fr .9fr;gap:40px;align-items:center}
.hero h1{font-size:clamp(2rem,5.5vw,3.5rem);font-weight:800;line-height:1.25;margin-bottom:16px}
.hero p{color:var(--mut);margin-bottom:26px;max-width:520px}
.badge{display:inline-block;padding:6px 16px;border-radius:999px;background:rgba(41,199,216,.12);color:var(--cy);font-weight:700;margin-bottom:18px;font-size:.9rem}
.cta{display:flex;gap:12px;flex-wrap:wrap}
.stage{position:relative;aspect-ratio:1;max-width:420px;margin:auto;width:100%;border-radius:32px;background:linear-gradient(145deg,#1C2030,#141726);box-shadow:0 20px 60px rgba(0,0,0,.5),inset 0 0 0 1px rgba(255,255,255,.07);overflow:hidden}
.ic{position:absolute;display:grid;place-items:center;border-radius:50%;background:var(--card);box-shadow:0 0 40px rgba(128,101,245,.45);animation:fl 5s ease-in-out infinite}
.i1{width:46%;height:46%;font-size:4.5rem;top:8%;inset-inline-start:27%}
.i2{width:34%;height:34%;font-size:3.2rem;bottom:8%;inset-inline-start:8%;box-shadow:0 0 40px rgba(233,166,106,.5);animation-delay:1s}
.i3{width:34%;height:34%;font-size:3.2rem;bottom:8%;inset-inline-end:8%;box-shadow:0 0 40px rgba(41,199,216,.5);animation-delay:2s}
@keyframes fl{50%{transform:translateY(-12px)}}
.tabs{display:flex;gap:10px;flex-wrap:wrap;margin-bottom:24px}
.tab{padding:8px 18px;border-radius:999px;border:1px solid rgba(255,255,255,.12);background:transparent;color:var(--tx);cursor:pointer;font:inherit;transition:.3s}
.tab.on,.tab:hover{background:var(--warm);color:#10121B;border-color:var(--warm);font-weight:700}
.items{display:grid;grid-template-columns:repeat(auto-fill,minmax(260px,1fr));gap:14px}
.it{display:flex;justify-content:space-between;gap:12px;align-items:center;background:var(--card);padding:16px 20px;border-radius:16px;border-inline-start:4px solid var(--warm);transition:.3s}
.it:hover{transform:translateY(-3px)}
.pr{color:var(--warm);font-weight:800;white-space:nowrap}
.note{color:var(--mut);font-size:.9rem;margin-top:16px}
.grid3{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:20px}
.big{font-size:2.4rem;display:block;margin-bottom:6px}
.alt{background:#141726}
form{display:grid;gap:14px;max-width:560px}
input,select{background:#10121B;border:1px solid rgba(255,255,255,.12);color:var(--tx);border-radius:12px;padding:12px 14px;font:inherit}
footer{padding:28px 0;text-align:center;color:var(--mut);border-top:1px solid rgba(255,255,255,.06)}
@media(max-width:800px){.hero .wrap{grid-template-columns:1fr}.stage{max-width:300px}section{padding:52px 0}.links{order:3;width:100%}.nav-cta{display:none}}
@media(prefers-reduced-motion:reduce){*{animation:none!important;transition:none!important}}
</style>
</head>
<body>
<nav><div class="wrap">
<a class="brand" href="#home"><img src="data:image/jpeg;base64,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" alt="Little House"><span>Little House</span></a>
<div class="links">
<a href="#home" data-ar="الرئيسية" data-en="Home"></a>
<a href="#menu" data-ar="الطعام والمشروبات" data-en="Food &amp; Drinks"></a>
<a href="#gaming" data-ar="باقات الألعاب" data-en="Gaming"></a>
<a href="#book" data-ar="الحجز" data-en="Booking"></a>
<a href="#about" data-ar="من نحن" data-en="About"></a>
<a href="#contact" data-ar="تواصل معنا" data-en="Contact"></a>
</div>
<button class="lang" id="lb" type="button">EN</button>
<a class="btn nav-cta" href="#book" data-ar="احجز جلستك" data-en="Book your session"></a>
</div></nav>

<header class="hero" id="home"><div class="wrap">
<div>
<span class="badge" data-ar="🕒 مفتوح 24 ساعة / 7 أيام" data-en="🕒 Open 24/7"></span>
<h1><span data-ar="نكهة تستحق التجربة..." data-en="Great Taste."></span><br><span data-ar="ومتعة بلا حدود" data-en="Epic Gaming."></span></h1>
<p data-ar="قهوة، برغر ووجبات خفيفة لذيذة، مع أجواء ألعاب وإضاءات تجعل كل زيارة تجربة لا تُنسى." data-en="Coffee, burgers and tasty snacks in a cozy, neon-lit gaming atmosphere that makes every visit unforgettable."></p>
<div class="cta">
<a class="btn" href="tel:0558149735" data-ar="📞 اطلب الآن" data-en="📞 Order now"></a>
<a class="btn o" href="#menu" data-ar="شاهد القائمة" data-en="View menu"></a>
</div></div>
<div class="stage" aria-hidden="true"><div class="ic i1">🎮</div><div class="ic i2">☕</div><div class="ic i3">🍔</div></div>
</div></header>

<section id="menu"><div class="wrap">
<h2><span data-ar="قائمة الطعام والمشروبات" data-en="Food &amp; Drinks Menu"></span></h2>
<p class="sub" data-ar="الأسعار بالدينار الجزائري (دج)" data-en="Prices in Algerian dinars (DA)"></p>
<div class="tabs" id="tabs"></div>
<div class="items" id="items"></div>
<p class="note" id="cnote"></p>
</div></section>

<section id="gaming" class="alt"><div class="wrap">
<h2><span data-ar="باقات الألعاب" data-en="Gaming Packages"></span></h2>
<p class="sub" data-ar="اتصل بنا لمعرفة العروض والأسعار الحالية" data-en="Call us for current offers and prices"></p>
<div class="grid3">
<div class="card"><span class="big">🎮</span><h3 data-ar="جلسة فردية" data-en="Solo session"></h3><p class="sub" data-ar="العب بمفردك على جهازك المفضل." data-en="Play on your favorite console, on your own."></p></div>
<div class="card"><span class="big">🕹️</span><h3 data-ar="جلسة الأصدقاء" data-en="Friends session"></h3><p class="sub" data-ar="تحدَّ أصدقاءك في أجواء ممتعة." data-en="Challenge your friends in a fun setting."></p></div>
<div class="card"><span class="big">🌙</span><h3 data-ar="جلسة ليلية" data-en="Night session"></h3><p class="sub" data-ar="نحن مفتوحون 24 ساعة، فالمتعة لا تتوقف." data-en="We never close, so the fun never stops."></p></div>
</div></div></section>

<section id="book"><div class="wrap">
<h2><span data-ar="احجز جلستك" data-en="Book your session"></span></h2>
<p class="sub" data-ar="املأ البيانات وسيفتح تطبيق الرسائل لإرسال طلبك." data-en="Fill in your details and your messaging app will open with your request."></p>
<form id="bf" class="card">
<input id="bn" required data-ph-ar="الاسم" data-ph-en="Name">
<input id="bd" type="datetime-local" required>
<select id="bg"><option>1</option><option>2</option><option>3</option><option>4</option><option>5+</option></select>
<button class="btn" type="submit" data-ar="إرسال الطلب" data-en="Send request"></button>
</form></div></section>

<section id="about" class="alt"><div class="wrap">
<h2><span data-ar="من نحن" data-en="About us"></span></h2>
<div class="grid3">
<div class="card"><span class="big">☕</span><h3 data-ar="مذاق مميز" data-en="Great food"></h3><p class="sub" data-ar="برغر، تاكوس، سلطات، معكرونة، حلويات ومشروبات منعشة." data-en="Burgers, tacos, salads, pasta, desserts and refreshing drinks."></p></div>
<div class="card"><span class="big">🎮</span><h3 data-ar="متعة اللعب" data-en="Gaming fun"></h3><p class="sub" data-ar="أجواء عصرية للألعاب مع أصدقائك." data-en="A modern gaming vibe to enjoy with friends."></p></div>
<div class="card"><span class="big">🕒</span><h3>24/7</h3><p class="sub" data-ar="مفتوح في كل وقت، نهارًا وليلًا." data-en="Open at any time, day and night."></p></div>
</div></div></section>

<section id="contact"><div class="wrap">
<h2><span data-ar="تواصل معنا" data-en="Contact us"></span></h2>
<div class="grid3">
<a class="card" href="tel:0558149735"><span class="big">📞</span><b dir="ltr">0558 149 735</b></a>
<a class="card" href="tel:0774941630"><span class="big">📞</span><b dir="ltr">0774 941 630</b></a>
<a class="card" target="_blank" rel="noopener" href="https://www.google.com/maps/search/?api=1&amp;query=Little+House+caf%C3%A9+Alg%C3%A9rie"><span class="big">📍</span><b data-ar="افتح الموقع في خرائط جوجل" data-en="Open in Google Maps"></b></a>
<div class="card"><span class="big">🕒</span><b data-ar="مفتوح 24 ساعة / 7 أيام" data-en="Open 24 hours, 7 days a week"></b></div>
</div></div></section>
<footer>© Little House</footer>

<script>
const D=`b|burger|برغر|🍔
Burger classique|برغر كلاسيك|300
Chicken Burger|برغر دجاج|400
Burger mixte|برغر مشكل|500
t|tacos|تاكوس|🌯
Tacos M|تاكوس M|500
Tacos L|تاكوس L|700
Tacos XL|تاكوس XL|900
Tacos XXL|تاكوس XXL|1200
s|snacks|سناك|🥪
Panini|بانيني|300
Hot dog|هوت دوغ|300
Croque Mr|كروك مسيو|400
Crêpe salée|كريب مالح|400
Parisien|باريزيان|450
sa|salads|سلطات|🥗
Végétarienne|سلطة نباتية|250
Tomate mozzarella|طماطم موزاريلا|400
Salade au thon|سلطة التونة|500
Salade de riz|سلطة الأرز|550
Salade niçoise|سلطة نيسواز|550
Salade de pâtes|سلطة المعكرونة|600
Salade césar|سلطة سيزر|800
p|mains|أطباق رئيسية|🍗
Poulet pané|دجاج مقرمش|900
Steak à cheval|ستيك بالبيض|1000
Suprême de poulet|سوبريم دجاج|1300
Cordon bleu|كوردون بلو|1500
Foie|كبدة|1600
pa|pasta|معكرونة|🍝
Pâtes au choix|معكرونة حسب الاختيار|900
g|gratins|غراتان|🧀
Gratin poulet|غراتان دجاج|400
Gratin viande|غراتان لحم|500
d|desserts|حلويات|🍰
Fondant / brownie|فوندان / براوني|200
Entremets|أنتريميه|250
Tarte|تارت|200
Glace|بوظة|150
Salade de fruits|سلطة فواكه|300
Crêpe|كريب|400
Pancake|بانكيك|400
Gaufre|غوفر|500
h|hot drinks|مشروبات ساخنة|☕
Thé maison|شاي البيت|100
Infusion|أعشاب|250
Café|قهوة|300
Café au lait|قهوة بالحليب|350
Cappuccino|كابتشينو|400
Chocolat chaud|شوكولا ساخنة|450
c|cold drinks|مشروبات باردة|🍹
Eau|ماء|100
Eau pétillante|ماء غازي|150
Diabolo|ديابولو|200
Soda|صودا|200
Mojito|موهيتو|400
Pina colada|بينا كولادا|450
Jus de fruits|عصير فواكه|500
Milkshake|ميلك شيك|500`;
const N={b:["Meat of your choice, lettuce, tomato, caramelized onion, cheese","لحم حسب الاختيار، خس، طماطم، بصل مكرمل، جبن"],t:["Meat of your choice, cheese sauce, fries","لحم حسب الاختيار، صلصة الجبن، بطاطا"],p:["Served with salad, sautéed vegetables, rice or fries","تُقدَّم مع سلطة أو خضار سوتيه أو أرز أو بطاطا مقلية"],pa:["Tagliatelle, spaghetti, penne or macaroni · Sauces: bolognese, arrabbiata, 4 cheeses, curry","تالياتيلي أو سباغيتي أو بيني أو مكرونة · الصلصات: بولونيز، أرابياتا، 4 أجبان، كاري"],g:["Béchamel and cheese","بشاميل وجبن"]};
const C=[];let cur=null;
D.split("\n").forEach(l=>{const a=l.split("|");if(a.length==4){cur={k:a[0],en:a[1],ar:a[2],i:a[3],it:[]};C.push(cur)}else cur.it.push(a)});
let lang="ar",ck="b";
const $=s=>document.querySelector(s);
function render(){
 $("#tabs").innerHTML=C.map(c=>`<button class="tab ${c.k==ck?"on":""}" data-k="${c.k}" type="button">${c.i} ${lang=="ar"?c.ar:c.en[0].toUpperCase()+c.en.slice(1)}</button>`).join("");
 const c=C.find(x=>x.k==ck);
 $("#items").innerHTML=c.it.map(a=>`<div class="it"><b>${lang=="ar"?a[1]:a[0]}</b><span class="pr">${a[2]} ${lang=="ar"?"دج":"DA"}</span></div>`).join("");
 const n=N[ck];$("#cnote").textContent=n?n[lang=="ar"?1:0]:"";
}
function setLang(l){
 lang=l;const d=document.documentElement;d.lang=l;d.dir=l=="ar"?"rtl":"ltr";document.body.classList.toggle("en",l=="en");
 document.querySelectorAll("[data-ar]").forEach(e=>e.innerHTML=e.dataset[l]);
 document.querySelectorAll("[data-ph-ar]").forEach(e=>e.placeholder=e.dataset[l=="ar"?"phAr":"phEn"]);
 $("#lb").textContent=l=="ar"?"EN":"عربي";render();
 try{localStorage.setItem("lh-lang",l)}catch(e){}
}
$("#lb").onclick=()=>setLang(lang=="ar"?"en":"ar");
$("#tabs").onclick=e=>{const b=e.target.closest(".tab");if(b){ck=b.dataset.k;render()}};
$("#bf").onsubmit=e=>{e.preventDefault();
 const m=(lang=="ar"?"حجز جلسة":"Session booking")+` - ${$("#bn").value} - ${$("#bd").value} - ${$("#bg").value}`;
 location.href="sms:0558149735?body="+encodeURIComponent(m)};
let s="ar";try{s=localStorage.getItem("lh-lang")||"ar"}catch(e){}
setLang(s);
</script>
</body>
</html>
