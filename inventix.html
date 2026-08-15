<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
<meta name="theme-color" content="#0F2747">
<link rel="manifest" href="manifest.json">
<title>INVENTIX Core v1.4</title>
<style>
:root{
  --navy:#0F2747;--navy2:#08192f;--blue:#1E4DBC;--orange:#F5A623;
  --success:#1A9A54;--danger:#D63031;--purple:#6C3FCB;--text:#F0F4FA;--muted:#7894bd;
}
*{box-sizing:border-box;margin:0;padding:0;-webkit-tap-highlight-color:transparent}
body{font-family:Arial,sans-serif;background:var(--navy2);color:var(--text);max-width:520px;margin:auto;min-height:100vh}
header{padding:20px 16px;background:linear-gradient(160deg,#0A1E38,#0F2747);position:sticky;top:0;z-index:10;border-bottom:1px solid #1E4DBC44}
.brand{font-size:25px;font-weight:900}.brand span{color:var(--orange)}
.sub{font-size:11px;color:var(--muted);margin-top:3px}
main{padding:14px 14px 90px}
.card{background:var(--navy);border:1px solid #1E4DBC2d;border-radius:14px;padding:14px;margin-bottom:12px}
h2{font-size:16px;margin-bottom:10px}
label{display:block;font-size:10px;font-weight:800;color:var(--muted);text-transform:uppercase;margin:8px 0 5px}
input,select{width:100%;background:#0A1E38;border:1.5px solid #1E4DBC55;border-radius:10px;color:white;padding:11px 12px;font-size:14px;outline:none}
input:focus,select:focus{border-color:var(--orange)}
.grid2{display:grid;grid-template-columns:1fr 1fr;gap:8px}
.btn{width:100%;padding:12px;border:none;border-radius:10px;font-weight:900;font-size:14px;margin-top:10px;cursor:pointer}
.primary{background:var(--orange);color:var(--navy)}
.secondary{background:#1E4DBC;color:white}
.danger{background:var(--danger);color:white}
.ghost{background:transparent;color:var(--muted);border:1px solid #1E4DBC44}
.kpis{display:grid;grid-template-columns:repeat(2,1fr);gap:8px;margin-bottom:12px}
.kpi{background:var(--navy);border-radius:12px;padding:14px;text-align:center;border-top:3px solid var(--orange)}
.kpi:nth-child(2){border-top-color:var(--success)} .kpi:nth-child(3){border-top-color:var(--blue)} .kpi:nth-child(4){border-top-color:var(--purple)}
.kpi strong{display:block;font-size:24px}.kpi small{color:var(--muted);font-size:10px}
.tabs{display:flex;gap:6px;overflow:auto;margin-bottom:12px}
.tab{white-space:nowrap;border:1px solid #1E4DBC44;background:transparent;color:var(--muted);border-radius:20px;padding:8px 12px;font-weight:800}
.tab.on{background:var(--orange);color:var(--navy);border-color:var(--orange)}
.page{display:none}.page.on{display:block}
.row{background:#0B203C;border-left:3px solid var(--blue);padding:10px;border-radius:8px;margin:7px 0;font-size:12px}
.row b{color:white}.row .meta{color:var(--muted);margin-top:4px;line-height:1.5}
.ok{border-left-color:var(--success)} .out{border-left-color:var(--danger)} .verify{border-left-color:var(--purple)}
.badge{display:inline-block;padding:3px 7px;border-radius:10px;background:#1E4DBC33;color:#9bb8e8;font-size:10px;font-weight:800}
.note{font-size:11px;color:var(--muted);line-height:1.5}
.statusline{display:flex;gap:8px;align-items:center;flex-wrap:wrap;margin-top:8px}
.pill{display:inline-block;padding:5px 8px;border-radius:999px;font-size:10px;font-weight:900;background:#16365f;color:#c8d8ef}
.pill.ok{background:#123f2a;color:#8fe0ad}.pill.bad{background:#512026;color:#ffadb1}
.summary4{display:grid;grid-template-columns:repeat(2,1fr);gap:8px;margin:10px 0}
.summary4>div{background:#0A1E38;border-radius:10px;padding:10px;text-align:center;border:1px solid #1E4DBC44}
.summary4 strong{display:block;font-size:18px}.summary4 small{font-size:9px;color:var(--muted)}
.toolbar{display:flex;gap:8px}.toolbar .btn{margin-top:0}
nav{position:fixed;bottom:0;left:50%;transform:translateX(-50%);width:100%;max-width:520px;display:grid;grid-template-columns:repeat(5,1fr);background:var(--navy);border-top:1px solid #1E4DBC44;z-index:20}
nav button{background:transparent;border:none;color:var(--muted);padding:10px 2px;font-size:10px;font-weight:800}
nav button span{display:block;font-size:20px;margin-bottom:2px}
nav button.on{color:var(--orange)}
.toast{display:none;position:fixed;top:76px;left:50%;transform:translateX(-50%);z-index:99;background:#111f32;color:white;padding:10px 14px;border-radius:10px;box-shadow:0 8px 24px #0008;font-size:12px;max-width:90%}
.scanner{display:none;position:fixed;inset:0;z-index:100;background:#000;flex-direction:column}
.scanner.on{display:flex}.scanner video{width:100%;height:65vh;object-fit:cover}
.scanbar{padding:12px;background:#071629}.scanbar button{padding:10px;border:0;border-radius:8px;font-weight:800}
hr{border:0;border-top:1px solid #1E4DBC33;margin:12px 0}
</style>
</head>
<body>
<div id="toast" class="toast"></div>

<div id="scanner" class="scanner">
  <div class="scanbar">
    <b>INVENTIX Scanner</b>
    <button id="closeScanner" style="float:right">Cerrar</button>
  </div>
  <video id="video" playsinline muted autoplay></video>
  <div class="scanbar">
    <div class="note">Centra el código. Si el navegador no soporta lectura automática, usa captura manual.</div>
    <input id="scanManual" placeholder="UPC / código">
    <button id="scanManualBtn" class="btn primary">Usar código</button>
  </div>
</div>

<header>
  <div class="brand">INVENTI<span>X</span> CORE</div>
  <div class="sub">v1.4 · Import/Export + conteo + Verify</div>
</header>

<main>
<section id="home" class="page on">
  <div class="kpis">
    <div class="kpi"><strong id="kStock">0</strong><small>Stock total</small></div>
    <div class="kpi"><strong id="kSku">0</strong><small>SKUs activos</small></div>
    <div class="kpi"><strong id="kMov">0</strong><small>Movimientos</small></div>
    <div class="kpi"><strong id="kVerify">0</strong><small>Verify OK</small></div>
  </div>
  <div class="card">
    <h2>Entorno de ejecución</h2>
    <div class="statusline">
      <span id="secureBadge" class="pill">Comprobando...</span>
      <span id="cameraBadge" class="pill">Cámara</span>
    </div>
    <div id="secureNote" class="note" style="margin-top:8px"></div>
  </div>
  <div class="card">
    <h2>Prueba de persistencia</h2>
    <div class="note">Haz una entrada o salida, cierra completamente Chrome y vuelve a abrir la misma URL. El movimiento y la existencia deben continuar.</div>
  </div>
  <div class="card">
    <h2>Respaldo completo</h2>
    <div class="toolbar">
      <button id="exportBtn" class="btn secondary">Exportar</button>
      <button id="importBtn" class="btn ghost">Importar</button>
    </div>
    <input id="importFile" type="file" accept=".json,application/json" style="display:none">
    <div class="note" style="margin-top:8px">El respaldo JSON permite recuperar datos aunque cambies de teléfono o limpies el navegador.</div>
  </div>
</section>

<section id="inventory" class="page">
  <div class="card">
    <h2>Inventario</h2>
    <div class="toolbar">
      <button id="importInvBtn" class="btn secondary">📥 Importar CSV</button>
      <button id="exportInvBtn" class="btn ghost">📤 Exportar CSV</button>
    </div>
    <input id="importInvFile" type="file" accept=".csv,text/csv,.txt,text/plain" style="display:none">
    <div class="note" style="margin-top:8px">Columnas aceptadas: UPC/CODIGO/SKU, DESCRIPCION, EXISTENCIA/CANTIDAD/QTY/STOCK y UBICACION.</div>
    <hr>
    <div id="inventoryList"></div>
  </div>

  <div class="card">
    <h2>Toma física</h2>
    <label>UPC / SKU</label><input id="pCode" placeholder="Código">
    <div class="grid2">
      <div><label>Cantidad contada</label><input id="pQty" type="number" min="1" inputmode="numeric"></div>
      <div><label>Ubicación</label><input id="pLoc" placeholder="LOCAL01 / A-01"></div>
    </div>
    <label>Responsable</label><input id="pUser" placeholder="Nombre">
    <button id="physicalScan" class="btn secondary">📷 Escanear UPC</button>
    <button id="savePhysical" class="btn primary">✅ Registrar conteo</button>
    <button id="exportPhysicalBtn" class="btn ghost">📤 Exportar toma física</button>
    <div id="physicalList"></div>
  </div>
</section>

<section id="entry" class="page">
  <div class="card">
    <h2>Registrar entrada</h2>
    <div class="grid2">
      <div><label>Folio OC</label><input id="eOC" placeholder="OC / Orden de compra"></div>
      <div><label>Factura proveedor</label><input id="eInvoice" placeholder="Factura / remisión"></div>
    </div>
    <label>UPC / SKU</label><input id="eCode" placeholder="Código">
    <label>Descripción</label><input id="eDesc" placeholder="Producto">
    <div class="grid2">
      <div><label>Cantidad</label><input id="eQty" type="number" min="1" inputmode="numeric"></div>
      <div><label>Ubicación</label><input id="eLoc" placeholder="A-01-01"></div>
    </div>
    <label>Responsable</label><input id="eUser" placeholder="Nombre">
    <button id="entryScan" class="btn secondary">📷 Escanear UPC</button>
    <button id="saveEntry" class="btn primary">✅ Guardar entrada</button>
  </div>
</section>

<section id="exit" class="page">
  <div class="card">
    <h2>Registrar salida</h2>
    <div class="grid2">
      <div><label>Folio OV</label><input id="sOV" placeholder="OV / Pedido"></div>
      <div><label>Documento salida</label><input id="sDoc" placeholder="Factura / remisión"></div>
    </div>
    <label>UPC / SKU</label><input id="sCode" placeholder="Código">
    <div class="grid2">
      <div><label>Cantidad</label><input id="sQty" type="number" min="1" inputmode="numeric"></div>
      <div><label>Ubicación</label><input id="sLoc" placeholder="A-01-01"></div>
    </div>
    <label>Picker</label><input id="sUser" placeholder="Nombre">
    <button id="exitScan" class="btn secondary">📷 Escanear UPC</button>
    <button id="saveExit" class="btn primary">✅ Guardar salida</button>
  </div>
</section>

<section id="kardex" class="page">
  <div class="card">
    <h2>Kardex virtual</h2>
    <div id="kardexList"></div>
  </div>
  <div class="card">
    <h2>Orden esperada</h2>
    <div class="toolbar">
      <button id="importVerifyBtn" class="btn secondary">📥 Importar orden CSV</button>
      <button id="exportVerifyBtn" class="btn ghost">📤 Exportar resultado</button>
    </div>
    <input id="importVerifyFile" type="file" accept=".csv,text/csv,.txt,text/plain" style="display:none">
    <div class="note" style="margin-top:8px">Columnas: OC/OV (opcional), CODIGO/UPC/SERIE, CANTIDAD/QTY y DESCRIPCION.</div>
    <div class="summary4">
      <div><strong id="vTotalExpected">0</strong><small>TOTAL ORDEN</small></div>
      <div><strong id="vScanned">0</strong><small>ESCANEADOS OK</small></div>
      <div><strong id="vMissing">0</strong><small>FALTAN</small></div>
      <div><strong id="vNoExiste">0</strong><small>NO EXISTE / EXCESO</small></div>
    </div>
    <div id="verifyExpectedList"></div>
  </div>

  <div class="card">
    <h2>Verify trazable</h2>
    <div class="grid2">
      <div><label>Referencia OC</label><input id="vOC" placeholder="OC / origen"></div>
      <div><label>Referencia OV</label><input id="vOV" placeholder="OV / pedido"></div>
    </div>
    <div class="grid2">
      <div><label>Documento</label><input id="vDoc" placeholder="Factura / remisión"></div>
      <div><label>Responsable</label><input id="vUser" placeholder="Validador"></div>
    </div>
    <label>Serie / lote / IMEI</label><input id="vCode" placeholder="Código a validar">
    <button id="verifyScan" class="btn secondary">📷 Escanear código</button>
    <button id="verifyBtn" class="btn primary">✅ Validar y registrar</button>
    <div class="note" style="margin-top:8px">En esta etapa Verify guarda la referencia documental de cada lectura. El cruce esperado vs escaneado se agregará después.</div>
    <div id="verifyList"></div>
  </div>
</section>
</main>

<nav>
<button data-page="home" class="on"><span>🏠</span>Inicio</button>
<button data-page="inventory"><span>📦</span>Inventario</button>
<button data-page="entry"><span>➕</span>Entrada</button>
<button data-page="exit"><span>➖</span>Salida</button>
<button data-page="kardex"><span>📊</span>Kardex</button>
</nav>

<script>
const STORAGE_KEY = 'inventix_core_v1_1';
let state = { inventory:{}, kardex:[], verify:[], verifyExpected:{}, physicalCounts:[] };

function nowISO(){ return new Date().toISOString(); }
function fmtDate(iso){ return new Date(iso).toLocaleString('es-MX'); }

function load(){
  try{
    const raw = localStorage.getItem(STORAGE_KEY);
    if(raw){
      const parsed = JSON.parse(raw);
      state = {
        inventory: parsed.inventory || {},
        kardex: parsed.kardex || [],
        verify: parsed.verify || [],
        verifyExpected: parsed.verifyExpected || {},
        physicalCounts: parsed.physicalCounts || []
      };
    }
  }catch(e){ console.error(e); }
  renderAll();
}

function save(){
  localStorage.setItem(STORAGE_KEY, JSON.stringify(state));
  renderAll();
}

function toast(msg, bad=false){
  const t=document.getElementById('toast');
  t.textContent=msg; t.style.display='block'; t.style.background=bad?'#7d1f24':'#113c2a';
  clearTimeout(window.__tt); window.__tt=setTimeout(()=>t.style.display='none',2200);
}

function cleanCode(v){ return String(v||'').trim().toUpperCase(); }
function qty(v){ const n=Number(v); return Number.isFinite(n)?n:0; }

function normHeader(v){
  return String(v||'').trim().toUpperCase().normalize('NFD').replace(/[\u0300-\u036f]/g,'').replace(/\s+/g,' ');
}
function parseCSV(raw){
  raw=String(raw||'').replace(/\r/g,'').trim(); if(!raw) return [];
  const first=raw.split('\n')[0]||'';
  const counts={',':(first.match(/,/g)||[]).length,';':(first.match(/;/g)||[]).length,'\t':(first.match(/\t/g)||[]).length};
  const sep=Object.entries(counts).sort((a,b)=>b[1]-a[1])[0][0];
  const rows=[]; let row=[],cell='',quoted=false;
  for(let i=0;i<raw.length;i++){
    const ch=raw[i];
    if(ch==='"'){ if(quoted && raw[i+1]==='"'){cell+='"';i++;} else quoted=!quoted; }
    else if(ch===sep && !quoted){row.push(cell);cell='';}
    else if(ch==='\n' && !quoted){row.push(cell);rows.push(row);row=[];cell='';}
    else cell+=ch;
  }
  row.push(cell); rows.push(row);
  const headers=(rows.shift()||[]).map(normHeader);
  return rows.filter(r=>r.some(x=>String(x).trim()!=='')).map(r=>{
    const o={}; headers.forEach((h,i)=>o[h]=String(r[i]??'').trim()); return o;
  });
}
function pick(row, aliases){
  for(const a of aliases){ const k=Object.keys(row).find(x=>normHeader(x)===normHeader(a)); if(k && String(row[k]).trim()!=='') return String(row[k]).trim(); }
  return '';
}
function csvEscape(v){ const s=String(v??''); return /[",;\n]/.test(s)?'"'+s.replace(/"/g,'""')+'"':s; }
function downloadText(filename, content, type='text/csv;charset=utf-8'){
  const blob=new Blob(['\ufeff'+content],{type}); const a=document.createElement('a');
  a.href=URL.createObjectURL(blob); a.download=filename; document.body.appendChild(a); a.click(); a.remove();
  setTimeout(()=>URL.revokeObjectURL(a.href),1000);
}
function dateTag(){ return new Date().toISOString().slice(0,10); }
function expectedSummary(){
  const rows=Object.values(state.verifyExpected||{});
  const total=rows.reduce((a,x)=>a+Number(x.expected||0),0);
  const scanned=rows.reduce((a,x)=>a+Math.min(Number(x.scanned||0),Number(x.expected||0)),0);
  const missing=rows.reduce((a,x)=>a+Math.max(Number(x.expected||0)-Number(x.scanned||0),0),0);
  const bad=state.verify.filter(x=>x.result==='NO EXISTE'||x.result==='EXCEDENTE').length;
  return {total,scanned,missing,bad};
}

function addMovement(type, code, quantity, location, user, desc='', reference='', documentNo=''){
  code=cleanCode(code); quantity=qty(quantity);
  reference=String(reference||'').trim().toUpperCase();
  documentNo=String(documentNo||'').trim().toUpperCase();

  if(!reference) { toast(type==='ENTRADA'?'Ingresa el folio de OC':'Ingresa el folio de OV',true); return false; }
  if(!code || quantity<=0) { toast('Falta código o cantidad válida',true); return false; }

  // Prevención de doble toque: misma operación exacta en una ventana corta.
  const last=state.kardex[0];
  if(last && last.type===type && last.code===code && Number(last.qty)===quantity &&
     String(last.reference||'')===reference && (Date.now()-new Date(last.time).getTime())<3000){
    toast('Movimiento duplicado evitado',true);
    return false;
  }

  let prod = state.inventory[code] || {code,desc:desc||code,qty:0,locations:{}};
  if(desc) prod.desc=desc;

  if(type==='ENTRADA'){
    prod.qty += quantity;
    const loc=location||'SIN UBICACIÓN';
    prod.locations[loc]=(prod.locations[loc]||0)+quantity;
  } else {
    if(prod.qty < quantity) { toast('Stock insuficiente',true); return false; }
    prod.qty -= quantity;
    const loc=location||'SIN UBICACIÓN';
    const locQty=prod.locations[loc]||0;
    if(locQty < quantity) { toast('Stock insuficiente en esa ubicación',true); return false; }
    prod.locations[loc]=locQty-quantity;
  }

  state.inventory[code]=prod;
  state.kardex.unshift({
    id: crypto.randomUUID ? crypto.randomUUID() : String(Date.now()+Math.random()),
    type, code, desc:prod.desc, qty:quantity, location:location||'', user:user||'Sin responsable',
    reference, documentNo, time:nowISO(), balance:prod.qty
  });
  save();
  toast(type==='ENTRADA'?'Entrada guardada':'Salida guardada');
  return true;
}

function renderAll(){
  const products=Object.values(state.inventory);
  document.getElementById('kStock').textContent=products.reduce((a,p)=>a+Number(p.qty||0),0);
  document.getElementById('kSku').textContent=products.filter(p=>p.qty>0).length;
  document.getElementById('kMov').textContent=state.kardex.length;
  document.getElementById('kVerify').textContent=state.verify.filter(x=>x.result==='OK').length;

  const inv=document.getElementById('inventoryList');
  inv.innerHTML=products.length?products.sort((a,b)=>a.code.localeCompare(b.code)).map(p=>{
    const locs=Object.entries(p.locations||{}).filter(([,q])=>q!==0).map(([l,q])=>`${l}: ${q}`).join(' · ')||'Sin ubicación';
    return `<div class="row ${p.qty>0?'ok':'out'}"><b>${p.code}</b> · ${escapeHtml(p.desc)} <span class="badge">${p.qty} pzas</span><div class="meta">${escapeHtml(locs)}</div></div>`
  }).join(''):'<div class="note">Sin inventario todavía. Importa CSV o agrega productos manualmente desde Entrada.</div>';

  const kx=document.getElementById('kardexList');
  kx.innerHTML=state.kardex.length?state.kardex.map(m=>`
    <div class="row ${m.type==='ENTRADA'?'ok':'out'}">
      <b>${m.type}</b> · ${escapeHtml(m.reference||(m.type==='ENTRADA'?'SIN OC':'SIN OV'))} · ${m.code} · ${m.qty} pzas
      <div class="meta">${escapeHtml(m.desc)}<br>${m.documentNo?'Documento: '+escapeHtml(m.documentNo)+'<br>':''}${escapeHtml(m.location||'Sin ubicación')} · ${escapeHtml(m.user)}<br>${fmtDate(m.time)} · Saldo ${m.balance}</div>
    </div>`).join(''):'<div class="note">Sin movimientos.</div>';

  const pc=document.getElementById('physicalList');
  if(pc){
    pc.innerHTML=(state.physicalCounts||[]).slice(0,20).map(p=>`
      <div class="row"><b>${escapeHtml(p.code)}</b> · ${p.qty} pzas
      <div class="meta">${escapeHtml(p.location||'Sin ubicación')} · ${escapeHtml(p.user||'Sin responsable')}<br>${fmtDate(p.time)}</div></div>`
    ).join('') || '<div class="note">Sin conteos físicos todavía.</div>';
  }

  const vs=expectedSummary();
  const vals=[vs.total,vs.scanned,vs.missing,vs.bad];
  ['vTotalExpected','vScanned','vMissing','vNoExiste'].forEach((id,i)=>{
    const el=document.getElementById(id); if(el) el.textContent=vals[i];
  });
  const vel=document.getElementById('verifyExpectedList');
  if(vel){
    const rows=Object.values(state.verifyExpected||{});
    vel.innerHTML=rows.length?rows.slice(0,40).map(x=>{
      const diff=Number(x.expected||0)-Number(x.scanned||0);
      const status=x.scanned>x.expected?'EXCEDENTE':diff<=0?'COMPLETO':'FALTAN '+diff;
      return `<div class="row ${diff<=0&&x.scanned<=x.expected?'ok':x.scanned>x.expected?'out':'verify'}">
        <b>${escapeHtml(x.code)}</b> · ${x.scanned||0}/${x.expected} · ${status}
        <div class="meta">${escapeHtml(x.desc||'')}${x.reference?'<br>Ref: '+escapeHtml(x.reference):''}</div>
      </div>`;
    }).join(''):'<div class="note">Importa una orden para comparar esperado vs escaneado.</div>';
  }

  const vl=document.getElementById('verifyList');
  vl.innerHTML=state.verify.slice(0,30).map(v=>`
    <div class="row verify">
      <b>${escapeHtml(v.code)}</b> · ${v.result}
      <div class="meta">
        ${v.oc?'OC: '+escapeHtml(v.oc)+'<br>':''}
        ${v.ov?'OV: '+escapeHtml(v.ov)+'<br>':''}
        ${v.documentNo?'Documento: '+escapeHtml(v.documentNo)+'<br>':''}
        ${escapeHtml(v.user||'Sin responsable')}<br>${fmtDate(v.time)}
      </div>
    </div>`).join('');
}

function escapeHtml(s){
  return String(s??'').replace(/[&<>"']/g,c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#039;'}[c]));
}

document.querySelectorAll('nav button').forEach(btn=>btn.addEventListener('click',()=>{
  document.querySelectorAll('.page').forEach(p=>p.classList.remove('on'));
  document.querySelectorAll('nav button').forEach(b=>b.classList.remove('on'));
  document.getElementById(btn.dataset.page).classList.add('on'); btn.classList.add('on');
}));

document.getElementById('saveEntry').addEventListener('click',()=>{
  const btn=document.getElementById('saveEntry'); btn.disabled=true;
  const ok=addMovement('ENTRADA',eCode.value,eQty.value,eLoc.value,eUser.value,eDesc.value,eOC.value,eInvoice.value);
  if(ok){ eQty.value=''; }
  setTimeout(()=>btn.disabled=false,800);
});
document.getElementById('saveExit').addEventListener('click',()=>{
  const btn=document.getElementById('saveExit'); btn.disabled=true;
  const ok=addMovement('SALIDA',sCode.value,sQty.value,sLoc.value,sUser.value,'',sOV.value,sDoc.value);
  if(ok){ sQty.value=''; }
  setTimeout(()=>btn.disabled=false,800);
});
document.getElementById('verifyBtn').addEventListener('click',()=>{
  const code=cleanCode(vCode.value);
  const oc=String(vOC.value||'').trim().toUpperCase();
  const ov=String(vOV.value||'').trim().toUpperCase();
  const documentNo=String(vDoc.value||'').trim().toUpperCase();
  const user=String(vUser.value||'').trim();
  if(!code) return toast('Ingresa o escanea serie/lote/IMEI',true);
  if(!user) return toast('Ingresa responsable de validación',true);

  let result='OK';
  const exp=state.verifyExpected[code];
  if(Object.keys(state.verifyExpected||{}).length){
    if(!exp) result='NO EXISTE';
    else{
      exp.scanned=Number(exp.scanned||0)+1;
      if(exp.scanned>Number(exp.expected||0)) result='EXCEDENTE';
      else if(exp.scanned===Number(exp.expected||0)) result='COMPLETO';
    }
  }
  state.verify.unshift({code,result,oc,ov,documentNo,user,time:nowISO()});
  save(); vCode.value='';
  toast(result==='NO EXISTE'?'Código no existe en la orden':
        result==='EXCEDENTE'?'Excedente detectado':
        result==='COMPLETO'?'Código completo':'Lectura registrada',
        result==='NO EXISTE'||result==='EXCEDENTE');
});

document.getElementById('exportBtn').addEventListener('click',()=>{
  const blob=new Blob([JSON.stringify(state,null,2)],{type:'application/json'});
  const a=document.createElement('a'); a.href=URL.createObjectURL(blob);
  a.download='inventix_respaldo_'+new Date().toISOString().slice(0,10)+'.json'; a.click(); URL.revokeObjectURL(a.href);
});
document.getElementById('importBtn').addEventListener('click',()=>importFile.click());
document.getElementById('importFile').addEventListener('change',async(e)=>{
  const f=e.target.files[0]; if(!f)return;
  try{ const obj=JSON.parse(await f.text()); state={inventory:obj.inventory||{},kardex:obj.kardex||[],verify:obj.verify||[],verifyExpected:obj.verifyExpected||{},physicalCounts:obj.physicalCounts||[]}; save(); toast('Respaldo restaurado'); }
  catch(err){ toast('Archivo de respaldo inválido',true); }
});

let scanTarget=null, stream=null, scanTimer=null;
async function openScanner(targetId){
  scanTarget=document.getElementById(targetId);
  document.getElementById('scanner').classList.add('on');
  try{
    if(!navigator.mediaDevices || !navigator.mediaDevices.getUserMedia){
      document.getElementById('scanner').classList.remove('on');
      toast('Este archivo local no puede abrir la cámara. Ábrelo desde una URL HTTPS o desde una app instalada.',true);
      return;
    }
    stream=await navigator.mediaDevices.getUserMedia({video:{facingMode:{ideal:'environment'}},audio:false});
    video.srcObject=stream;
    if('BarcodeDetector' in window){
      const detector=new BarcodeDetector({formats:['ean_13','ean_8','code_128','code_39','upc_a','upc_e','itf']});
      scanTimer=setInterval(async()=>{
        try{
          const codes=await detector.detect(video);
          if(codes[0]?.rawValue){ useScanned(codes[0].rawValue); }
        }catch(e){}
      },500);
    }
  }catch(e){
    document.getElementById('scanner').classList.remove('on');
    toast('La cámara necesita un contexto seguro. Publica Inventix por HTTPS (GitHub Pages) o instálalo como app/PWA.',true);
  }
}
function useScanned(code){
  if(scanTarget) scanTarget.value=code;
  closeScanner(); toast('Código capturado');
}
function closeScanner(){
  clearInterval(scanTimer); scanTimer=null;
  if(stream){stream.getTracks().forEach(t=>t.stop());stream=null;}
  document.getElementById('scanner').classList.remove('on');
}
document.getElementById('entryScan').addEventListener('click',()=>openScanner('eCode'));
document.getElementById('exitScan').addEventListener('click',()=>openScanner('sCode'));
document.getElementById('verifyScan').addEventListener('click',()=>openScanner('vCode'));
document.getElementById('physicalScan').addEventListener('click',()=>openScanner('pCode'));
document.getElementById('closeScanner').addEventListener('click',closeScanner);
document.getElementById('scanManualBtn').addEventListener('click',()=>useScanned(scanManual.value));


document.getElementById('importInvBtn').addEventListener('click',()=>importInvFile.click());
document.getElementById('importInvFile').addEventListener('change',async e=>{
  const f=e.target.files[0]; if(!f)return;
  try{
    const rows=parseCSV(await f.text()); if(!rows.length) return toast('CSV de inventario vacío',true);
    if(!confirm('La importación cargará el archivo como nueva base de inventario. ¿Continuar?')) return;
    const inv={};
    for(const r of rows){
      const code=cleanCode(pick(r,['UPC','CODIGO','CÓDIGO','SKU','SERIE'])); if(!code) continue;
      const desc=pick(r,['DESCRIPCION','DESCRIPCIÓN','PRODUCTO'])||code;
      const q=qty(pick(r,['EXISTENCIA','CANTIDAD','QTY','STOCK']));
      const loc=pick(r,['UBICACION','UBICACIÓN','LOCATION'])||'SIN UBICACIÓN';
      if(!inv[code]) inv[code]={code,desc,qty:0,locations:{}};
      inv[code].desc=desc; inv[code].qty+=q; inv[code].locations[loc]=(inv[code].locations[loc]||0)+q;
    }
    state.inventory=inv; save(); toast('Inventario importado: '+Object.keys(inv).length+' códigos');
  }catch(err){ console.error(err); toast('No se pudo importar inventario',true); }
  e.target.value='';
});
document.getElementById('exportInvBtn').addEventListener('click',()=>{
  const rows=[['CODIGO','DESCRIPCION','EXISTENCIA','UBICACION','EXISTENCIA_UBICACION']];
  Object.values(state.inventory).forEach(p=>{
    const locs=Object.entries(p.locations||{});
    if(!locs.length) rows.push([p.code,p.desc,p.qty,'',p.qty]);
    else locs.forEach(([l,q])=>rows.push([p.code,p.desc,p.qty,l,q]));
  });
  downloadText('inventix_inventario_'+dateTag()+'.csv',rows.map(r=>r.map(csvEscape).join(',')).join('\n'));
});

document.getElementById('savePhysical').addEventListener('click',()=>{
  const code=cleanCode(pCode.value), q=qty(pQty.value);
  if(!code||q<=0) return toast('Falta código o cantidad contada',true);
  state.physicalCounts.unshift({
    id:crypto.randomUUID?crypto.randomUUID():String(Date.now()+Math.random()),
    code,qty:q,location:String(pLoc.value||'').trim(),user:String(pUser.value||'').trim(),time:nowISO()
  });
  save(); pQty.value=''; toast('Conteo físico registrado');
});
document.getElementById('exportPhysicalBtn').addEventListener('click',()=>{
  const rows=[['CODIGO','CANTIDAD_FISICA','UBICACION','RESPONSABLE','FECHA_HORA']];
  (state.physicalCounts||[]).forEach(p=>rows.push([p.code,p.qty,p.location,p.user,p.time]));
  downloadText('inventix_toma_fisica_'+dateTag()+'.csv',rows.map(r=>r.map(csvEscape).join(',')).join('\n'));
});

document.getElementById('importVerifyBtn').addEventListener('click',()=>importVerifyFile.click());
document.getElementById('importVerifyFile').addEventListener('change',async e=>{
  const f=e.target.files[0]; if(!f)return;
  try{
    const rows=parseCSV(await f.text()); if(!rows.length) return toast('CSV de orden vacío',true);
    const expected={};
    for(const r of rows){
      const code=cleanCode(pick(r,['CODIGO','CÓDIGO','UPC','SERIE','IMEI','SKU'])); if(!code) continue;
      const q=Math.max(1,qty(pick(r,['CANTIDAD','QTY','CANTIDAD OC','TOTAL']))||1);
      const desc=pick(r,['DESCRIPCION','DESCRIPCIÓN','PRODUCTO']);
      const ref=pick(r,['OC','OV','ORDEN','PEDIDO','REFERENCIA']);
      if(!expected[code]) expected[code]={code,expected:0,scanned:0,desc,reference:ref};
      expected[code].expected+=q;
      if(desc) expected[code].desc=desc;
      if(ref) expected[code].reference=ref;
    }
    state.verifyExpected=expected; state.verify=[]; save();
    toast('Orden cargada: '+Object.keys(expected).length+' códigos');
  }catch(err){ console.error(err); toast('No se pudo importar la orden',true); }
  e.target.value='';
});
document.getElementById('exportVerifyBtn').addEventListener('click',()=>{
  const rows=[['CODIGO','DESCRIPCION','REFERENCIA','ESPERADO','ESCANEADO','DIFERENCIA','STATUS']];
  Object.values(state.verifyExpected||{}).forEach(x=>{
    const diff=Number(x.expected||0)-Number(x.scanned||0);
    const st=x.scanned>x.expected?'EXCEDENTE':diff<=0?'COMPLETO':'FALTAN';
    rows.push([x.code,x.desc||'',x.reference||'',x.expected,x.scanned||0,diff,st]);
  });
  state.verify.filter(x=>x.result==='NO EXISTE').forEach(x=>rows.push([x.code,'','',0,1,-1,'NO EXISTE']));
  downloadText('inventix_verify_resultado_'+dateTag()+'.csv',rows.map(r=>r.map(csvEscape).join(',')).join('\n'));
});

function renderEnvironment(){
  const secure=window.isSecureContext || location.hostname==='localhost';
  const sb=document.getElementById('secureBadge'), cb=document.getElementById('cameraBadge'), sn=document.getElementById('secureNote');
  if(sb){ sb.textContent=secure?'HTTPS / contexto seguro':'Archivo local / sin HTTPS'; sb.className='pill '+(secure?'ok':'bad'); }
  const cameraReady=!!(navigator.mediaDevices&&navigator.mediaDevices.getUserMedia);
  if(cb){ cb.textContent=cameraReady?'API cámara disponible':'API cámara bloqueada'; cb.className='pill '+(cameraReady?'ok':'bad'); }
  if(sn){ sn.textContent=secure
    ?'Entorno apto para solicitar permiso de cámara. Usa Escanear UPC o Verify.'
    :'Para evitar capturar UPC de 13 dígitos manualmente, publica este paquete en GitHub Pages (HTTPS) o instálalo como app/PWA.'; }
}
if('serviceWorker' in navigator && window.isSecureContext){
  window.addEventListener('load',()=>navigator.serviceWorker.register('./service-worker.js').catch(()=>{}));
}
renderEnvironment();

load();
</script>
</body>
</html>