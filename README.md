<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Urban Kinda | where style meets individuality</title>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Lora:wght@400;500;600&family=Outfit:wght@400;500;600&family=Pinyon+Script&display=swap">
<style>
:root{--bg:#fff;--ink:#1a1a1a;--muted:#5c5c5c;--bar:#d9d9d9;--maroon:#6b0f1a;--maroon-ink:#fff;--card:#f4f2f1;--line:#e0dcda;--green:#25d366;--brown:#4a2c17;
box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#161314;--ink:#f1ecea;--muted:#b3aaa7;--bar:#2a2526;--maroon:#a3283a;--card:#221e1f;--line:#3a3334;--brown:#e8c9a8}}
:root[data-theme="white"]{--bg:#161314;--ink:#f1ecea;--muted:#b3aaa7;--bar:#2a2526;--maroon:#a3283a;--card:#221e1f;--line:#3a3334;--brown:#e8c9a8}
html{scroll-behavior:smooth;scroll-padding-top:calc(90px + env(safe-area-inset-top,0px))}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--ink);font-family:Outfit,system-ui,sans-serif;line-height:1.55}
h1,h2,h3{font-family:Lora,Georgia,serif;font-weight:500;line-height:1.2;margin:0}
a{color:inherit;text-decoration:none}
button{font:inherit;cursor:pointer;color:inherit}
:focus-visible{outline:3px solid var(--maroon);outline-offset:2px}
.wrap{max-width:1100px;margin:0 auto;padding:0 20px}
header{position:sticky;top:env(safe-area-inset-top,0px);z-index:20;background:var(--bar);box-shadow:0 3px 4px rgba(0,0,0,.25)}
.nav{display:flex;align-items:center;justify-content:space-between;gap:16px;min-height:72px}
.logo{font-family:'Pinyon Script',cursive;font-size:30px;line-height:.85;text-align:center}
.logo span{display:block;margin-left:22px}
nav ul{display:flex;gap:36px;list-style:none;margin:0;padding:0;font-family:Lora,serif;font-size:18px}
nav a{padding:6px 2px;border-bottom:2px solid transparent}
nav a.on,nav a:hover{color:var(--brown);border-color:var(--brown)}
.icons{display:flex;gap:6px}
.ib{background:none;border:0;width:44px;height:44px;border-radius:50%;display:grid;place-items:center;position:relative}
.ib:hover{background:rgba(0,0,0,.08)}
.ib svg{width:26px;height:26px;fill:none;stroke:currentColor;stroke-width:2}
.badge{position:absolute;top:2px;right:0;background:var(--maroon);color:#fff;font-size:11px;min-width:18px;height:18px;border-radius:9px;display:grid;place-items:center;padding:0 4px}
.badge:empty{display:none}
#menu{display:none}
.call{display:flex;align-items:center;gap:10px;padding:14px 0 0;font-weight:600}
.call i{width:28px;height:28px;border-radius:50%;background:var(--green);display:grid;place-items:center}
.call svg{width:16px;height:16px;fill:#fff}
.hero{display:grid;grid-template-columns:1.1fr 1fr;align-items:end;gap:20px;padding-top:10px}
.hero .copy{align-self:center;padding:20px 0}
.script{font-family:'Pinyon Script',cursive;font-size:30px;color:var(--maroon);margin:0}
.hero h1{font-size:clamp(30px,4.4vw,44px);max-width:12ch;margin:4px 0 16px}
.hero p{max-width:46ch;margin:0 0 22px;font-size:15px}
.btn{display:inline-block;background:var(--maroon);color:var(--maroon-ink);border:0;border-radius:4px;padding:11px 20px;font-weight:600;font-size:14px;box-shadow:0 4px 10px rgba(107,15,26,.35)}
.btn:hover{filter:brightness(1.15)}
.btn.ghost{background:none;color:var(--ink);border:1px solid var(--ink);box-shadow:none}
.hero img{width:100%;max-width:440px;justify-self:end;display:block}
section{padding:56px 0}
section h2{font-size:30px;margin-bottom:6px}
.sub{color:var(--muted);margin:0 0 22px}
.tools{display:flex;flex-wrap:wrap;gap:10px;align-items:center;margin-bottom:22px}
.chip{border:1px solid var(--line);background:var(--card);border-radius:20px;padding:7px 16px;font-size:14px}
.chip[aria-pressed="true"]{background:var(--maroon);color:#fff;border-color:var(--maroon)}
select{margin-left:auto;font:inherit;padding:8px 10px;border-radius:6px;border:1px solid var(--line);background:var(--card);color:var(--ink)}
.grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(210px,1fr));gap:20px}
.card{background:var(--card);border-radius:8px;overflow:hidden;display:flex;flex-direction:column}
.ph{aspect-ratio:4/5;position:relative;display:grid;place-items:center;font-family:'Pinyon Script',cursive;font-size:34px;color:rgba(255,255,255,.85)}
.tag{position:absolute;top:10px;left:10px;background:var(--maroon);color:#fff;font:600 12px Outfit;padding:3px 9px;border-radius:3px}
.heart{position:absolute;top:6px;right:6px;background:rgba(255,255,255,.9);color:#222;border:0;width:38px;height:38px;border-radius:50%;display:grid;place-items:center}
.heart svg{width:20px;height:20px;fill:none;stroke:currentColor;stroke-width:2}
.heart[aria-pressed="true"]{color:var(--maroon)}
.heart[aria-pressed="true"] svg{fill:var(--maroon)}
.info{padding:14px;display:flex;flex-direction:column;gap:8px;flex:1}
.info h3{font-size:17px}
.price b{font-size:16px}.price s{color:var(--muted);margin-left:6px;font-size:14px}
.sizes{display:flex;gap:6px}
.sizes button{border:1px solid var(--line);background:var(--bg);border-radius:4px;min-width:34px;height:30px;font-size:13px}
.sizes button[aria-pressed="true"]{background:var(--ink);color:var(--bg);border-color:var(--ink)}
.info .btn{margin-top:auto;width:100%;box-shadow:none}
.empty{grid-column:1/-1;padding:30px;text-align:center;color:var(--muted)}
.about{display:grid;grid-template-columns:1fr 1fr;gap:40px;align-items:start}
.about p{max-width:60ch}
.about ul{list-style:none;padding:0;margin:0;display:grid;gap:14px}
.about li{border-left:3px solid var(--maroon);padding-left:14px}
form.news{display:flex;gap:10px;flex-wrap:wrap}
form.news input{flex:1;min-width:220px;padding:11px 12px;border:1px solid var(--line);border-radius:4px;background:var(--card);color:var(--ink);font:inherit}
footer{border-top:1px solid var(--line);padding:26px 0;color:var(--muted);font-size:14px}
.ov{position:fixed;inset:0;background:rgba(0,0,0,.5);z-index:40;display:none}
.ov.open{display:block}
.search{position:fixed;top:0;left:0;right:0;z-index:41;background:var(--bg);padding:calc(20px + env(safe-area-inset-top,0px)) 20px 20px;display:none;box-shadow:0 8px 20px rgba(0,0,0,.3)}
.search.open{display:block}
.search input{width:100%;max-width:700px;display:block;margin:0 auto;padding:14px;font:inherit;font-size:18px;border:2px solid var(--maroon);border-radius:6px;background:var(--card);color:var(--ink)}
#sres{max-width:700px;margin:10px auto 0;display:grid;gap:4px}
#sres button{text-align:left;background:none;border:0;padding:10px;border-radius:6px;display:flex;justify-content:space-between}
#sres button:hover{background:var(--card)}
.drawer{position:fixed;top:0;right:0;bottom:0;width:min(400px,100%);background:var(--bg);z-index:41;transform:translateX(100%);transition:transform .25s;display:flex;flex-direction:column;padding:calc(18px + env(safe-area-inset-top,0px)) 18px calc(18px + env(safe-area-inset-bottom,0px))}
.drawer.open{transform:none}
.drawer header{position:static;background:none;box-shadow:none;display:flex;justify-content:space-between;align-items:center}
.drawer h2{font-size:24px}
.list{flex:1;overflow:auto;margin:14px 0;display:grid;gap:12px;align-content:start}
.row{display:grid;grid-template-columns:54px 1fr auto;gap:12px;align-items:center;background:var(--card);padding:10px;border-radius:8px}
.row .sw{width:54px;height:66px;border-radius:5px}
.row small{color:var(--muted);display:block}
.qty{display:flex;align-items:center;gap:8px;margin-top:4px}
.qty button{width:28px;height:28px;border:1px solid var(--line);background:var(--bg);border-radius:50%}
.rm{background:none;border:0;color:var(--muted);text-decoration:underline;font-size:13px}
.total{display:flex;justify-content:space-between;font-size:18px;font-weight:600;margin-bottom:12px}
.drawer .btn{width:100%;text-align:center}
#toast{position:fixed;left:50%;bottom:calc(24px + env(safe-area-inset-bottom,0px));transform:translate(-50%,20px);background:var(--ink);color:var(--bg);padding:10px 18px;border-radius:6px;opacity:0;transition:.2s;z-index:60;pointer-events:none;font-size:14px}
#toast.show{opacity:1;transform:translate(-50%,0)}
@media (max-width:820px){
 #menu{display:grid}
 nav{position:absolute;top:100%;left:0;right:0;background:var(--bar);display:none;padding:8px 20px 16px;box-shadow:0 6px 8px rgba(0,0,0,.2)}
 nav.open{display:block}
 nav ul{flex-direction:column;gap:4px}
 .hero,.about{grid-template-columns:1fr}
 .hero img{justify-self:center;max-width:320px}
 select{margin-left:0}
}
@media (prefers-reduced-motion:reduce){*{transition:none!important;scroll-behavior:auto!important}}
</style>
</head>
<body>
<header>
 <div class="wrap nav">
  <a href="#home" class="logo" aria-label="Urban Kinda home">Urban<span>Kinda</span></a>
  <nav id="nav" aria-label="Main">
   <ul>
    <li><a href="#home" class="on">Home</a></li>
    <li><a href="#shop" data-cat="Sale">Sale</a></li>
    <li><a href="#shop" data-cat="All">Categories</a></li>
    <li><a href="#about">About Us</a></li>
   </ul>
  </nav>
  <div class="icons">
   <button class="ib" id="sbtn" aria-label="Search"><svg viewBox="0 0 24 24"><circle cx="10" cy="10" r="7"/><path d="M15 15l6 6"/></svg></button>
   <button class="ib" id="wbtn" aria-label="Wishlist"><svg viewBox="0 0 24 24"><path d="M12 21C5 15 3 11.5 3 8.5A4.5 4.5 0 0 1 12 6a4.5 4.5 0 0 1 9 2.5C21 11.5 19 15 12 21z"/></svg><span class="badge" id="wc"></span></button>
   <button class="ib" id="cbtn" aria-label="Cart"><svg viewBox="0 0 24 24"><path d="M5 8h14l-1 13H6z"/><path d="M9 8V6a3 3 0 0 1 6 0v2"/></svg><span class="badge" id="cc"></span></button>
   <button class="ib" id="menu" aria-label="Menu" aria-expanded="false"><svg viewBox="0 0 24 24"><path d="M3 6h18M3 12h18M3 18h18"/></svg></button>
  </div>
 </div>
</header>

<main id="home">
 <div class="wrap">
  <a class="call" href="tel:+639123456789" aria-label="Call or message us"><i><svg viewBox="0 0 24 24"><path d="M6.6 10.8a15 15 0 0 0 6.6 6.6l2.2-2.2c.3-.3.7-.4 1-.2 1.100.4 2.300.6 3.600.6.600 0 1 .4 1 1V20c0 .6-.4 1-1 1A17 17 0 0 1 3 4c0-.6.4-1 1-1h3.500c.600 0 1 .4 1 1 0 1.300.2 2.500.6 3.600.1.300 0 .7-.2 1z"/></svg></i>+6391 2345 6789</a>
  <div class="hero">
   <div class="copy">
    <p class="script">Urban kind.a</p>
    <h1>where style meets individuality.</h1>
    <p>At Urban Kinda, clothing is how you tell your story. We curate comfortable, quality, trend-forward pieces that fit your personality, mood, and lifestyle: stylish, affordable, and made to help you feel your best in every moment.</p>
    <a href="#shop" class="btn">Shop Now</a>
   </div>
   <img alt="Two models wearing Urban Kinda pieces" src="   <img alt="Two models wearing Urban Kinda pieces" src="C:\Users\Administrator\Desktop\URBAN KIND A\s.png">
  </div>
 </div>

 <section id="shop">
  <div class="wrap">
   <h2>Shop the collection</h2>
   <p class="sub">Tap the heart to save a piece, pick a size, then add it to your bag.</p>
   <div class="tools" id="chips"></div>
   <div class="grid" id="grid"></div>
  </div>
 </section>

 <section id="about" style="background:var(--card)">
  <div class="wrap about">
   <div>
    <h2>About Urban Kinda</h2>
    <p>We started Urban Kinda for people who dress to match their mood, not a rulebook. Every piece is picked to be comfortable, good quality, and easy to mix with what you already own.</p>
   </div>
   <ul>
    <li><b>Affordable.</b> Trend-forward pieces without the heavy price tag.</li>
    <li><b>Comfortable.</b> Fits made for all-day wear.</li>
    <li><b>Yours.</b> Styled your way, whatever the mood.</li>
   </ul>
  </div>
 </section>

 <section>
  <div class="wrap">
   <h2>Get new drops first</h2>
   <p class="sub">Join the list for new arrivals and sale alerts.</p>
   <form class="news" id="news"><input type="email" required placeholder="Your email" aria-label="Email address"><button class="btn" type="submit">Subscribe</button></form>
  </div>
 </section>
</main>

<footer><div class="wrap">© 2026 Urban Kinda · +6391 2345 6789</div></footer>

<div class="ov" id="ov"></div>
<div class="search" id="search" role="dialog" aria-label="Search">
 <input id="sin" type="search" placeholder="Search tops, pants, jackets..." aria-label="Search products">
 <div id="sres"></div>
</div>
<aside class="drawer" id="drawer" role="dialog" aria-label="Panel">
 <header><h2 id="dt">Your bag</h2><button class="ib" id="dx" aria-label="Close"><svg viewBox="0 0 24 24"><path d="M5 5l14 14M19 5L5 19"/></svg></button></header>
 <div class="list" id="dl"></div>
 <div id="df"></div>
</aside>
<div id="toast" role="status"></div>

<script>
var P=[
{id:1,n:"Ribbed Black Tank",c:"Tops",p:350,c1:"#2b2b2b"},
{id:2,n:"Boxy Graphic Tee",c:"Tops",p:420,o:560,c1:"#7a5c4a"},
{id:3,n:"Camel Utility Jacket",c:"Jackets",p:1850,c1:"#a87b55"},
{id:4,n:"Faux Leather Cargo Pants",c:"Pants",p:1290,o:1590,c1:"#1d1d1f"},
{id:5,n:"Wide-Leg Trousers",c:"Pants",p:890,c1:"#4b4b52"},
{id:6,n:"Oversized Bomber",c:"Jackets",p:1650,o:2100,c1:"#6b0f1a"},
{id:7,n:"Cropped Knit Top",c:"Tops",p:480,c1:"#c9a9a0"},
{id:8,n:"Washed Denim Jacket",c:"Jackets",p:1490,c1:"#5d7691"}];
var CATS=["All","Sale","Tops","Pants","Jackets"],S={cat:"All",sort:"def",size:{}},W=[],C=[];
function ld(){try{W=JSON.parse(localStorage.getItem("uk-w")||"[]");C=JSON.parse(localStorage.getItem("uk-c")||"[]")}catch(e){}}
function sv(){try{localStorage.setItem("uk-w",JSON.stringify(W));localStorage.setItem("uk-c",JSON.stringify(C))}catch(e){}}
function $(i){return document.getElementById(i)}
function peso(n){return "₱"+n.toLocaleString("en-PH")}
function toast(t){var e=$("toast");e.textContent=t;e.classList.add("show");clearTimeout(toast.t);toast.t=setTimeout(function(){e.classList.remove("show")},1800)}
function chips(){$("chips").innerHTML=CATS.map(function(c){return '<button class="chip" aria-pressed="'+(S.cat==c)+'" data-c="'+c+'">'+c+'</button>'}).join("")+'<select id="sort" aria-label="Sort"><option value="def">Sort: Featured</option><option value="lo">Price: low to high</option><option value="hi">Price: high to low</option></select>';$("sort").value=S.sort}
function grid(){
 var L=P.filter(function(p){return S.cat=="All"||(S.cat=="Sale"?p.o:p.c==S.cat)});
 if(S.sort=="lo")L.sort(function(a,b){return a.p-b.p});if(S.sort=="hi")L.sort(function(a,b){return b.p-a.p});
 $("grid").innerHTML=L.length?L.map(function(p){var z=S.size[p.id]||"M",w=W.indexOf(p.id)>-1;
 return '<article class="card"><div class="ph" style="background:'+p.c1+'">Kinda'+(p.o?'<span class="tag">Sale</span>':'')+'<button class="heart" data-w="'+p.id+'" aria-pressed="'+w+'" aria-label="Save '+p.n+'"><svg viewBox="0 0 24 24"><path d="M12 21C5 15 3 11.5 3 8.5A4.5 4.5 0 0 1 12 6a4.5 4.5 0 0 1 9 2.5C21 11.5 19 15 12 21z"/></svg></button></div><div class="info"><h3>'+p.n+'</h3><div class="price"><b>'+peso(p.p)+'</b>'+(p.o?'<s>'+peso(p.o)+'</s>':'')+'</div><div class="sizes" role="group" aria-label="Size">'+["S","M","L"].map(function(s){return '<button data-s="'+p.id+':'+s+'" aria-pressed="'+(z==s)+'">'+s+'</button>'}).join("")+'</div><button class="btn" data-a="'+p.id+'">Add to bag</button></div></article>'}).join(""):'<p class="empty">No pieces here yet. Try another category.</p>'}
function badges(){$("wc").textContent=W.length||"";$("cc").textContent=C.reduce(function(a,i){return a+i.q},0)||""}
function open(t){$("ov").classList.add("open");if(t=="search"){$("search").classList.add("open");$("sin").value="";sres("");$("sin").focus()}else{$("drawer").classList.add("open");panel(t)}}
function close(){["ov","search","drawer"].forEach(function(i){$(i).classList.remove("open")});$("drawer").dataset.t=""}
function sres(q){q=q.trim().toLowerCase();var r=q?P.filter(function(p){return (p.n+" "+p.c).toLowerCase().indexOf(q)>-1}):[];
 $("sres").innerHTML=q&&!r.length?'<p class="empty">Nothing matches "'+q.replace(/</g,"")+'". Try "jacket" or "tank".</p>':r.map(function(p){return '<button data-go="'+p.id+'"><span>'+p.n+'</span><b>'+peso(p.p)+'</b></button>'}).join("")}
function panel(t){$("drawer").dataset.t=t;var d=$("dl"),f=$("df");
 if(t=="cart"){$("dt").textContent="Your bag";
  d.innerHTML=C.length?C.map(function(i,x){var p=P[i.id-1];return '<div class="row"><div class="sw" style="background:'+p.c1+'"></div><div><b>'+p.n+'</b><small>Size '+i.s+' · '+peso(p.p)+'</small><div class="qty"><button data-q="'+x+':-1" aria-label="Less">−</button>'+i.q+'<button data-q="'+x+':1" aria-label="More">+</button></div></div><button class="rm" data-r="'+x+'">Remove</button></div>'}).join(""):'<p class="empty">Your bag is empty. Add a piece from the shop.</p>';
  var tot=C.reduce(function(a,i){return a+P[i.id-1].p*i.q},0);
  f.innerHTML=C.length?'<div class="total"><span>Total</span><span>'+peso(tot)+'</span></div><a class="btn" id="co" href="tel:+639123456789">Order by call or text</a>':''}
 else{$("dt").textContent="Saved pieces";
  d.innerHTML=W.length?W.map(function(id){var p=P[id-1];return '<div class="row"><div class="sw" style="background:'+p.c1+'"></div><div><b>'+p.n+'</b><small>'+peso(p.p)+'</small></div><button class="rm" data-uw="'+id+'">Remove</button></div>'}).join(""):'<p class="empty">Nothing saved yet. Tap a heart on any piece.</p>';f.innerHTML=''}}
document.addEventListener("click",function(e){var t=e.target.closest("button,a");if(!t)return;
 if(t.dataset.c){S.cat=t.dataset.c;chips();grid()}
 else if(t.dataset.cat){S.cat=t.dataset.cat;chips();grid();$("nav").classList.remove("open")}
 else if(t.dataset.w){var id=+t.dataset.w,k=W.indexOf(id);if(k>-1){W.splice(k,1);toast("Removed from saved")}else{W.push(id);toast("Saved")}sv();badges();grid()}
 else if(t.dataset.s){var a=t.dataset.s.split(":");S.size[a[0]]=a[1];grid()}
 else if(t.dataset.a){var id=+t.dataset.a,s=S.size[id]||"M",f=C.filter(function(i){return i.id==id&&i.s==s})[0];if(f)f.q++;else C.push({id:id,s:s,q:1});sv();badges();toast(P[id-1].n+" added to bag")}
 else if(t.dataset.q){var a=t.dataset.q.split(":"),i=C[+a[0]];i.q+=+a[1];if(i.q<1)C.splice(+a[0],1);sv();badges();panel("cart")}
 else if(t.dataset.r){C.splice(+t.dataset.r,1);sv();badges();panel("cart")}
 else if(t.dataset.uw){W.splice(W.indexOf(+t.dataset.uw),1);sv();badges();grid();panel("wish")}
 else if(t.dataset.go){close();S.cat="All";chips();grid();$("shop").scrollIntoView()}
 else if(t.id=="sbtn")open("search");else if(t.id=="wbtn")open("wish");else if(t.id=="cbtn")open("cart");
 else if(t.id=="dx")close();
 else if(t.id=="menu"){var n=$("nav").classList.toggle("open");t.setAttribute("aria-expanded",n)}
 else if(t.tagName=="A"&&$("nav").contains(t))$("nav").classList.remove("open")});
$("ov").onclick=close;
document.addEventListener("keydown",function(e){if(e.key=="Escape")close()});
document.addEventListener("change",function(e){if(e.target.id=="sort"){S.sort=e.target.value;grid()}});
$("sin").addEventListener("input",function(e){sres(e.target.value)});
$("news").addEventListener("submit",function(e){e.preventDefault();e.target.reset();toast("You're on the list")});
ld();chips();grid();badges();
</script>
</body>
</html>
