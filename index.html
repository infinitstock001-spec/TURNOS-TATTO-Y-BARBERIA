<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Facu Tattss · Turnos</title>
<style>
:root{--bg:#0f0f10;--card:#1a1a1c;--txt:#f4f1ea;--mut:#9a968c;--ac:#ff5a1f}
*{box-sizing:border-box;margin:0}
body{background:var(--bg);color:var(--txt);font-family:system-ui,sans-serif;padding-bottom:110px}
section{padding:40px 20px;max-width:640px;margin:auto}
h1{font-size:2.6rem;line-height:1}
h2{font-size:1.6rem;margin-bottom:6px}
p.s{color:var(--mut);margin-bottom:18px}
.ac{color:var(--ac)}
#promo{background:var(--ac);color:#000;text-align:center;padding:10px;font-weight:700;font-size:.9rem}
.hero{padding-top:50px}
.btn{display:block;text-align:center;background:var(--ac);color:#000;font-weight:700;padding:15px;border-radius:10px;text-decoration:none;border:0;width:100%;font-size:1rem;margin-top:12px}
.btn.o{background:none;color:var(--txt);border:1px solid #444}
.item{background:var(--card);border-radius:12px;padding:16px;margin-bottom:12px;display:flex;justify-content:space-between;align-items:center;gap:10px;border:2px solid transparent}
.item.on{border-color:var(--ac)}
.item b{display:block}.item small{color:var(--mut)}
.item button{background:#2a2a2d;color:var(--txt);border:0;padding:10px 14px;border-radius:8px;font-weight:700;white-space:nowrap}
.item.on button{background:var(--ac);color:#000}
.grid{display:grid;grid-template-columns:1fr 1fr;gap:8px}
.grid img{width:100%;aspect-ratio:1;object-fit:cover;border-radius:10px;background:#222}
.tabs{display:flex;gap:8px;margin-bottom:12px;overflow-x:auto}
.tabs button{background:var(--card);color:var(--txt);border:0;padding:8px 14px;border-radius:20px;white-space:nowrap}
.tabs button.on{background:var(--ac);color:#000}
#bar{position:fixed;bottom:0;left:0;right:0;background:#000;padding:12px 20px;border-top:1px solid #333}
#bar .in{max-width:640px;margin:auto;display:flex;justify-content:space-between;align-items:center;gap:12px}
#bar .btn{margin:0;width:auto;padding:12px 18px}
footer{text-align:center;color:var(--mut);font-size:.8rem;padding:20px}
</style>
</head>
<body>

<div id="promo">🔥 Clientes nuevos: <span id="pct">20</span>% OFF · termina en <span id="timer"></span></div>

<section class="hero">
  <p class="ac" style="letter-spacing:3px;font-size:.8rem">BARBERÍA · TATUAJES</p>
  <h1>FACU<br><span class="ac">TATTSS</span></h1>
  <p class="s" style="margin-top:14px">Armá tu turno en 1 minuto. Elegí lo que querés y me llega directo al WhatsApp.</p>
  <a class="btn" href="#catalogo">Elegir mi servicio</a>
  <a class="btn o" href="https://instagram.com/facu_tattss" target="_blank">Ver Instagram</a>
</section>

<section id="catalogo">
  <h2>Catálogo</h2>
  <p class="s">Tocá "Agregar" en lo que quieras. El total se calcula solo.</p>
  <div id="lista"></div>
</section>

<section>
  <h2>Trabajos</h2>
  <div class="tabs" id="tabs"></div>
  <div class="grid" id="galeria"></div>
</section>

<section>
  <h2>Sobre <span class="ac">mí</span></h2>
  <p class="s">Soy Facu, barbero y tatuador de Fray Luis Beltrán, Maipú. Hago realismo, lettering y hair tattoo. [Contá acá en 2 líneas tu historia y por qué la gente se queda con vos.]</p>
</section>

<section>
  <h2>Seña para confirmar</h2>
  <p class="s">En tatuajes, la seña reserva tu lugar.</p>
  <a class="btn" id="mp" href="PEGA_ACA_TU_LINK_DE_MERCADO_PAGO" target="_blank">Pagar seña con Mercado Pago</a>
</section>

<section>
  <h2>Cursos</h2>
  <p class="s">Barbería y tatuaje, cupos limitados.</p>
  <a class="btn o" id="curso" href="#">Consultar próximo curso</a>
</section>

<footer>Fray Luis Beltrán, Maipú, Mendoza · © 2026 Facu Tattss</footer>

<div id="bar"><div class="in">
  <div><small style="color:#9a968c" id="cant">0 servicios</small><br><b id="total">$0</b></div>
  <a class="btn" id="wa" href="#">Reservar por WhatsApp</a>
</div></div>

<script>
// ====== EDITÁ SOLO ESTA PARTE ======
const WA = "5492613372398";
const DESCUENTO = 20; // % clientes nuevos
const FIN_PROMO = new Date("2026-12-07T23:59:59");
const servicios = [
  {n:"Corte completo",   d:"Corte con máquina y tijera", p:500},
  {n:"Corte premium",    d:"Corte + perfilado + styling", p:0},
  {n:"Diseño de barba",  d:"Perfilado y afeitado a navaja", p:300},
  {n:"Hair tattoo",      d:"Diseño a máquina", p:700},
  {n:"Mechas",           d:"Decoloración y color", p:0},
  {n:"Ondulación",       d:"Permanente / rizos", p:0},
  {n:"Tatuaje chico",    d:"Hasta 5 cm", p:1500},
  {n:"Tatuaje mediano",  d:"5 a 15 cm", p:0},
  {n:"Tatuaje grande",   d:"Sesiones múltiples. Se cotiza", p:0}
];
const fotos = {
  "Cortes":["fotos/corte1.jpg","fotos/corte2.jpg"],
  "Hair tattoo":["fotos/hair1.jpg","fotos/hair2.jpg"],
  "Tatuajes":["fotos/tattoo1.jpg","fotos/tattoo2.jpg"]
};
document.getElementById("curso").href = "https://wa.me/"+WA+"?text="+encodeURIComponent("Hola Facu, quiero info del próximo curso");
// ===================================

document.getElementById("pct").textContent = DESCUENTO;
const sel = new Set();
const $ = id => document.getElementById(id);
const money = n => "$" + n.toLocaleString("es-AR");

function pintar(){
  $("lista").innerHTML = servicios.map((s,i)=>`
    <div class="item ${sel.has(i)?'on':''}">
      <div><b>${s.n}</b><small>${s.d}</small><br><b class="ac">${s.p?money(s.p):'Consultar'}</b></div>
      <button onclick="alternar(${i})">${sel.has(i)?'Quitar':'Agregar'}</button>
    </div>`).join("");
  const arr=[...sel].map(i=>servicios[i]);
  const total=arr.reduce((a,s)=>a+s.p,0);
  $("cant").textContent = arr.length+" servicio"+(arr.length==1?"":"s");
  $("total").textContent = money(total);
  const lineas = arr.map(s=>"• "+s.n+(s.p?" ("+money(s.p)+")":" (a consultar)")).join("\n");
  const msg = "Hola Facu, quiero sacar turno.\n"+(lineas||"(todavía no elegí servicio)")+
    "\nTotal estimado: "+money(total)+"\nSoy cliente nuevo con promo "+DESCUENTO+"% OFF: sí/no\nDía y horario que me sirve:";
  $("wa").href = "https://wa.me/"+WA+"?text="+encodeURIComponent(msg);
}
function alternar(i){ sel.has(i)?sel.delete(i):sel.add(i); pintar(); }

function galeria(cat){
  $("galeria").innerHTML = fotos[cat].map(f=>`<img src="${f}" alt="${cat}" loading="lazy">`).join("");
  document.querySelectorAll("#tabs button").forEach(b=>b.classList.toggle("on",b.textContent==cat));
}
$("tabs").innerHTML = Object.keys(fotos).map(c=>`<button onclick="galeria('${c}')">${c}</button>`).join("");

setInterval(()=>{
  const d = FIN_PROMO - new Date();
  if(d<=0){ $("promo").style.display="none"; return; }
  $("timer").textContent = Math.floor(d/864e5)+"d "+Math.floor(d%864e5/36e5)+"h "+Math.floor(d%36e5/6e4)+"m";
},1000);

pintar(); galeria(Object.keys(fotos)[0]);
</script>
</body>
</html>
