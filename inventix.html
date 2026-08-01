<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
<title>INVENTIX</title>
<style>
:root{--navy:#0F2747;--blue:#1E4DBC;--orange:#F5A623;--navy2:#0A1E38;--success:#1A9A54;--danger:#D63031;--warn:#E17B00;--purple:#6C3FCB}
*{box-sizing:border-box;margin:0;padding:0;-webkit-tap-highlight-color:transparent}
body{font-family:Arial,sans-serif;background:var(--navy2);color:#F0F0F0;min-height:100vh;max-width:480px;margin:0 auto}
@keyframes fadeIn{from{opacity:0;transform:translateY(8px)}to{opacity:1;transform:translateY(0)}}
@keyframes scanLine{0%{top:5%}50%{top:85%}100%{top:5%}}
input,select{width:100%;background:#0A1E38;border:1.5px solid #1E4DBC44;border-radius:10px;color:#F0F0F0;font-size:13px;padding:11px 14px;font-family:Arial;outline:none;-webkit-appearance:none}
input:focus{border-color:var(--orange)}
.btn{display:flex;align-items:center;justify-content:center;gap:8px;width:100%;padding:14px;border:none;border-radius:12px;font-size:14px;font-weight:800;cursor:pointer;margin-bottom:10px;font-family:Arial;transition:all .15s}
.btn:active{transform:scale(.97)}
.btn-primary{background:var(--orange);color:var(--navy)}
.btn-ghost{background:transparent;border:1.5px solid #333;color:#777}
.card{background:var(--navy);border:1px solid #1E4DBC22;border-radius:14px;padding:16px;margin-bottom:12px}
.lbl{display:block;font-size:10px;font-weight:800;color:#4A6FA5;text-transform:uppercase;letter-spacing:.6px;margin-bottom:5px}
.sep{display:flex;align-items:center;gap:10px;margin:14px 0}
.sep-line{flex:1;height:1px;background:#1E4DBC22}
.sep span{font-size:11px;color:#4A6FA5;white-space:nowrap}
.g2{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-bottom:12px}
.g3{display:grid;grid-template-columns:1fr 1fr 1fr;gap:8px;margin-bottom:12px}
.mb{margin-bottom:12px}
.alert{border-radius:10px;padding:11px 14px;margin-bottom:12px;font-size:12px;line-height:1.5}
.alert-e{background:#D6303115;border:1px solid #D6303144;color:#D63031}
.alert-w{background:#E17B0015;border:1px solid #E17B0044;color:#E17B00}
.alert-s{background:#1A9A5415;border:1px solid #1A9A5444;color:#1A9A54}
.alert-b{background:#1E4DBC15;border:1px solid #1E4DBC44;color:#88AAEE}
#toast{position:fixed;top:20px;left:50%;transform:translateX(-50%);padding:11px 20px;font-size:13px;font-weight:700;z-index:2000;display:none;border-radius:12px;white-space:nowrap;max-width:90vw;overflow:hidden;box-shadow:0 8px 32px #00000066;color:#fff}

/* SCANNER */
#scan-overlay{position:fixed;inset:0;background:#000;z-index:900;display:none;flex-direction:column}
#scan-overlay.on{display:flex}
#scan-hdr{background:#00000099;padding:14px 16px;display:flex;justify-content:space-between;align-items:center;flex-shrink:0}
#vid-wrap{flex:1;position:relative;overflow:hidden;background:#000;display:flex;align-items:center;justify-content:center}
#cam-video{width:100%;height:100%;object-fit:cover;display:block}
#cam-canvas{display:none}
.sframe{position:absolute;width:270px;height:180px;border:2.5px solid var(--orange);border-radius:14px;box-shadow:0 0 0 9999px #00000077;pointer-events:none}
.sline{position:absolute;left:8px;right:8px;height:2.5px;background:linear-gradient(90deg,transparent,var(--orange),transparent);animation:scanLine 2s linear infinite;border-radius:2px}
.co{position:absolute;width:22px;height:22px;border-color:var(--orange);border-style:solid}
.co.tl{top:-2px;left:-2px;border-width:4px 0 0 4px;border-radius:4px 0 0 0}
.co.tr{top:-2px;right:-2px;border-width:4px 4px 0 0;border-radius:0 4px 0 0}
.co.bl{bottom:-2px;left:-2px;border-width:0 0 4px 4px;border-radius:0 0 0 4px}
.co.br{bottom:-2px;right:-2px;border-width:0 4px 4px 0;border-radius:0 0 4px 0}
#scan-hint{background:#00000099;padding:10px 16px;text-align:center;font-size:12px;color:#aaa;flex-shrink:0}
#scan-status-txt{font-size:11px;color:var(--orange);text-align:center;padding:4px 0}
#manual-row{background:#00000099;padding:10px 16px;display:flex;gap:8px;flex-shrink:0}
#manual-row input{background:#ffffff15;border-color:#ffffff22;color:#fff}
#manual-row button{flex-shrink:0;padding:0 18px;background:var(--orange);border:none;color:var(--navy);border-radius:8px;font-size:16px;font-weight:900;cursor:pointer}
#cam-err{display:none;position:absolute;inset:0;flex-direction:column;align-items:center;justify-content:center;padding:28px;text-align:center;background:#000099}

/* NAV */
#bottom-nav{position:fixed;bottom:0;left:50%;transform:translateX(-50%);width:100%;max-width:480px;background:var(--navy);border-top:1px solid #1E4DBC33;display:flex;z-index:100}
.nav-btn{flex:1;padding:10px 4px 8px;border:none;background:transparent;cursor:pointer;display:flex;flex-direction:column;align-items:center;gap:2px}
.nav-lbl{font-size:9px;font-weight:700;color:#4A6FA5}
.nav-lbl.on{color:var(--orange)}

/* PAGES */
.page{display:none;padding:14px;padding-bottom:88px;animation:fadeIn .2s ease}
.page.on{display:block}

/* KPI */
.kpi-grid{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-bottom:14px}
.kpi{background:var(--navy);border-radius:12px;padding:14px 12px;text-align:center;border-top:3px solid}
.kpi-val{font-size:26px;font-weight:900;font-family:monospace;line-height:1}
.kpi-lbl{font-size:9px;color:#4A6FA5;font-weight:700;margin-top:4px;text-transform:uppercase}

/* CARDS */
.vert-tab{flex-shrink:0;padding:8px 14px;border-radius:20px;border:1.5px solid #1E4DBC33;background:transparent;color:#4A6FA5;font-size:11px;font-weight:800;cursor:pointer;white-space:nowrap}
.vert-tab.on{border-color:var(--orange);background:var(--orange);color:var(--navy)}
.vertical-card{background:var(--navy);border:1px solid #1E4DBC22;border-radius:14px;padding:14px;margin-bottom:10px;display:flex;align-items:center;gap:14px;cursor:pointer}
.vertical-card:active{opacity:.8}
.vert-icon{width:46px;height:46px;border-radius:12px;display:flex;align-items:center;justify-content:center;font-size:22px;flex-shrink:0}
.mov-row{display:flex;justify-content:space-between;align-items:center;padding:12px 14px;background:var(--navy);border:1px solid #1E4DBC22;border-radius:10px;margin-bottom:8px;border-left:3px solid}
.scan-btn{background:linear-gradient(135deg,var(--navy),#1a2d5a);border:2px dashed var(--orange)88;border-radius:16px;padding:28px 20px;text-align:center;cursor:pointer;margin-bottom:16px}
.scan-btn:active{opacity:.8}
.kx-row{background:var(--navy);border:1px solid #1E4DBC22;border-radius:12px;padding:13px;margin-bottom:8px;border-left:3px solid}
.big-num{font-size:44px!important;font-weight:900!important;text-align:center!important;font-family:monospace!important;padding:18px!important;border-width:2px!important}
.vs-num{width:28px;height:28px;border-radius:50%;background:var(--purple);display:flex;align-items:center;justify-content:center;font-size:12px;font-weight:900;flex-shrink:0;color:#fff}
.verify-step{display:flex;gap:12px;padding:10px 0;border-bottom:1px solid #ffffff11}
.verify-step:last-child{border-bottom:none}
</style>
</head>
<body>

<div id="toast"></div>

<!-- ══ SCANNER — API NATIVA DEL NAVEGADOR ══ -->
<div id="scan-overlay">
  <div id="scan-hdr">
    <div style="display:flex;align-items:center;gap:10px">
      <div style="width:40px;height:40px;background:linear-gradient(135deg,var(--navy),var(--blue));border-radius:10px;display:flex;align-items:center;justify-content:center;font-size:22px">🛡️</div>
      <div>
        <div style="font-size:13px;font-weight:800">INVENTIX Scanner</div>
        <div id="scan-status-txt">Iniciando cámara...</div>
      </div>
    </div>
    <button onclick="closeScanner()" style="background:#ffffff15;border:none;color:#fff;border-radius:10px;padding:8px 16px;font-size:13px;font-weight:800;cursor:pointer">✕ Cerrar</button>
  </div>

  <div id="vid-wrap">
    <video id="cam-video" playsinline muted autoplay></video>
    <canvas id="cam-canvas"></canvas>
    <!-- Marco de escaneo -->
    <div class="sframe">
      <div class="sline"></div>
      <div class="co tl"></div><div class="co tr"></div>
      <div class="co bl"></div><div class="co br"></div>
    </div>
    <!-- Error cámara -->
    <div id="cam-err">
      <div style="font-size:48px;margin-bottom:14px">📵</div>
      <div style="font-weight:800;font-size:16px;margin-bottom:8px">Sin acceso a cámara</div>
      <div style="color:#777;font-size:12px;line-height:1.7;margin-bottom:16px" id="cam-err-msg"></div>
      <div style="background:#F5A62322;border:1px solid #F5A62344;border-radius:10px;padding:12px;font-size:11px;color:#F5A623;text-align:left">
        <b>Usa el campo manual de abajo</b> para ingresar el código, o asegúrate de que el link tenga <b>https://</b>
      </div>
    </div>
  </div>

  <div id="scan-hint">Centra el código en el recuadro naranja</div>
  <div id="manual-row">
    <input id="manual-inp" type="text" inputmode="text" placeholder="O escribe el UPC / código aquí..." onkeydown="if(event.key==='Enter'){doManual();}" autocomplete="off">
    <button onclick="doManual()">→</button>
  </div>
</div>

<!-- ══ HOME ══ -->
<div class="page on" id="pg-home">
  <div style="background:linear-gradient(160deg,var(--navy2),var(--navy));margin:-14px -14px 0;padding:28px 20px 20px">
    <div style="display:flex;align-items:center;justify-content:center;gap:12px;margin-bottom:10px">
      <div style="width:52px;height:52px;background:linear-gradient(135deg,var(--navy),var(--blue));border-radius:12px;display:flex;align-items:center;justify-content:center;font-size:28px;border:1.5px solid #F5A62333">🛡️</div>
      <div>
        <div style="font-size:24px;font-weight:900;letter-spacing:-1px">INVENTI<span style="color:var(--orange)">X</span></div>
        <div style="font-size:9px;color:#4A6FA5;letter-spacing:1.5px;text-transform:uppercase;font-weight:700">Inteligencia Operativa</div>
      </div>
    </div>
    <div style="font-size:11px;color:#4A6FA5;text-align:center;font-style:italic;margin-bottom:16px">Transforma tu inventario en una operación inteligente</div>
    <div class="kpi-grid" id="home-kpis"></div>
    <div id="home-alert"></div>
  </div>
  <div style="height:14px"></div>
  <div style="font-size:10px;font-weight:800;color:#4A6FA5;text-transform:uppercase;letter-spacing:.8px;margin-bottom:10px">Módulos</div>
  <div id="vert-list"></div>
</div>

<!-- ══ APP ══ -->
<div class="page" id="pg-app">
  <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:14px">
    <div>
      <div style="font-size:17px;font-weight:900" id="app-title">Operaciones</div>
      <div style="font-size:11px;color:#4A6FA5" id="app-sub"></div>
    </div>
    <button onclick="goTo('pg-home');renderHome()" style="background:transparent;border:1px solid #1E4DBC33;color:#4A6FA5;border-radius:8px;padding:7px 12px;font-size:11px;cursor:pointer">← Inicio</button>
  </div>
  <div style="display:flex;gap:6px;overflow-x:auto;padding-bottom:4px;margin-bottom:14px" id="proc-tabs"></div>
  <div class="scan-btn" onclick="openScanner('app')">
    <div style="font-size:52px;margin-bottom:10px">📷</div>
    <div style="font-weight:800;color:var(--orange);font-size:17px;margin-bottom:4px" id="scan-btn-lbl">Escanear producto</div>
    <div style="font-size:12px;color:#4A6FA5">Toca para abrir la cámara</div>
  </div>
  <div class="sep"><div class="sep-line"></div><span>o ingresa el código</span><div class="sep-line"></div></div>
  <div style="display:flex;gap:8px;margin-bottom:16px">
    <input id="app-manual" type="text" placeholder="UPC o ID del producto" inputmode="text" onkeydown="if(event.key==='Enter')manualSearch()">
    <button onclick="manualSearch()" style="background:var(--orange);border:none;color:var(--navy);border-radius:10px;padding:0 18px;font-size:18px;font-weight:900;cursor:pointer">→</button>
  </div>
  <div id="app-movs"></div>
</div>

<!-- ══ REGISTRAR ══ -->
<div class="page" id="pg-reg">
  <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:16px">
    <div style="font-size:16px;font-weight:900" id="reg-title">Registrar</div>
    <button id="reg-back" style="background:transparent;border:1px solid #1E4DBC33;color:#4A6FA5;border-radius:8px;padding:7px 12px;font-size:11px;cursor:pointer">✕</button>
  </div>
  <div id="reg-prod-card" class="card" style="margin-bottom:16px;border-left:4px solid var(--orange)"></div>
  <div id="reg-campos"></div>
  <div id="reg-cad-alert" style="display:none" class="alert alert-e"></div>
  <button class="btn btn-primary" id="reg-save-btn" onclick="saveReg()">✅ Guardar</button>
  <button class="btn btn-ghost" onclick="goTo('pg-app')">← Cancelar</button>
</div>

<!-- ══ VERIFY ══ -->
<div class="page" id="pg-verify">
  <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:16px">
    <div>
      <div style="font-size:17px;font-weight:900">INVENTIX VERIFY</div>
      <div style="font-size:11px;color:#8B6FD4">Validación en tiempo real · Complemento SAP</div>
    </div>
    <button onclick="goTo('pg-home');renderHome()" style="background:transparent;border:1px solid #6C3FCB33;color:#8B6FD4;border-radius:8px;padding:7px 12px;font-size:11px;cursor:pointer">← Inicio</button>
  </div>
  <div style="background:linear-gradient(135deg,#1a0a3a,#2D1B69);border:1px solid #6C3FCB44;border-radius:16px;padding:18px;margin-bottom:14px">
    <div style="font-size:11px;color:#8B6FD4;font-weight:800;text-transform:uppercase;letter-spacing:.8px;margin-bottom:8px">¿Por qué Verify?</div>
    <div style="font-size:13px;font-weight:700;margin-bottom:6px">SAP llega hasta la pantalla — no baja al piso</div>
    <div style="font-size:11px;color:#aaa;line-height:1.7">Inventix Verify valida series, lotes y FEFO en el proceso físico donde SAP no llega.</div>
  </div>
  <div class="scan-btn" onclick="openScanner('verify')" style="border-color:#6C3FCB88">
    <div style="font-size:52px;margin-bottom:10px">📷</div>
    <div style="font-weight:800;color:#A888FF;font-size:17px;margin-bottom:4px">Escanear serie / lote</div>
    <div style="font-size:12px;color:#8B6FD4">Valida en tiempo real contra el pedido</div>
  </div>
  <div class="sep"><div class="sep-line"></div><span>o ingresa el código</span><div class="sep-line"></div></div>
  <div style="display:flex;gap:8px;margin-bottom:16px">
    <input id="verify-manual" type="text" placeholder="Serie / Lote / IMEI..." onkeydown="if(event.key==='Enter')verifySearch()">
    <button onclick="verifySearch()" style="background:var(--purple);border:none;color:#fff;border-radius:10px;padding:0 18px;font-size:18px;font-weight:900;cursor:pointer">✓</button>
  </div>
  <div id="verify-resultado" style="display:none;margin-bottom:14px"></div>
  <div class="card">
    <div style="font-size:11px;font-weight:800;color:#8B6FD4;text-transform:uppercase;letter-spacing:.8px;margin-bottom:12px">Proceso de validación</div>
    <div class="verify-step"><div class="vs-num">1</div><div><div style="font-size:12px;font-weight:800">Escanear serie en el rack</div><div style="font-size:10px;color:#777;margin-top:2px">Lee el código del producto físico</div></div></div>
    <div class="verify-step"><div class="vs-num">2</div><div><div style="font-size:12px;font-weight:800">Validación contra pedido</div><div style="font-size:10px;color:#777;margin-top:2px">Compara con la lista autorizada</div></div></div>
    <div class="verify-step"><div class="vs-num">3</div><div><div style="font-size:12px;font-weight:800">✅ OK o ❌ Alerta inmediata</div><div style="font-size:10px;color:#777;margin-top:2px">El operador sabe al instante</div></div></div>
    <div class="verify-step"><div class="vs-num">4</div><div><div style="font-size:12px;font-weight:800">Evidencia digital automática</div><div style="font-size:10px;color:#777;margin-top:2px">Usuario · Hora · Serie · Resultado</div></div></div>
  </div>
  <div style="font-size:10px;font-weight:800;color:#4A6FA5;text-transform:uppercase;letter-spacing:.8px;margin-bottom:8px">Historial</div>
  <div id="verify-hist"></div>
</div>

<!-- ══ KARDEX ══ -->
<div class="page" id="pg-kardex">
  <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:16px">
    <div>
      <div style="font-size:17px;font-weight:900">Kardex Virtual</div>
      <div style="font-size:11px;color:#4A6FA5" id="kx-cnt">0 movimientos</div>
    </div>
    <button onclick="goTo('pg-home');renderHome()" style="background:transparent;border:1px solid #1E4DBC33;color:#4A6FA5;border-radius:8px;padding:7px 12px;font-size:11px;cursor:pointer">← Inicio</button>
  </div>
  <div class="alert alert-b" style="font-size:11px;margin-bottom:14px">ℹ️ El kardex se genera automáticamente con cada movimiento. Sin captura manual.</div>
  <div style="display:flex;gap:6px;overflow-x:auto;padding-bottom:6px;margin-bottom:14px" id="kx-filtros"></div>
  <div id="kx-lista"></div>
</div>

<!-- ══ NAV ══ -->
<div id="bottom-nav">
  <button class="nav-btn" onclick="goTo('pg-home');renderHome()"><span style="font-size:20px">🏠</span><span class="nav-lbl on" id="nl-home">Inicio</span></button>
  <button class="nav-btn" onclick="goTo('pg-app');renderApp()"><span style="font-size:20px">📦</span><span class="nav-lbl" id="nl-app">Operación</span></button>
  <button class="nav-btn" onclick="goTo('pg-verify')"><span style="font-size:20px">✅</span><span class="nav-lbl" id="nl-verify">Verify</span></button>
  <button class="nav-btn" onclick="goTo('pg-kardex');renderKardex()"><span style="font-size:20px">📊</span><span class="nav-lbl" id="nl-kx">Kardex</span></button>
</div>

<script>
// ══ DATOS ══
const VERTS={
  core:  {id:"core",  icon:"🛡️",nombre:"INVENTIX CORE",  color:"#1E4DBC",sub:"Inventarios, entradas y salidas",            procesos:["ENTRADA","SALIDA","INVENTARIO"],extras:[]},
  food:  {id:"food",  icon:"🥩",nombre:"INVENTIX FOOD",  color:"#2ECC71",sub:"FEFO, caducidades y trazabilidad",           procesos:["ENTRADA","SALIDA","INVENTARIO"],extras:["lote","cad","temp"]},
  verify:{id:"verify",icon:"✅",nombre:"INVENTIX VERIFY",color:"#6C3FCB",sub:"Validación series, lotes y embarques",       procesos:["VERIFICAR"],                   extras:["serie"]},
  pharma:{id:"pharma",icon:"💊",nombre:"INVENTIX PHARMA",color:"#8B6FD4",sub:"COFEPRIS, cuarentena y lotes",              procesos:["ENTRADA","SALIDA","INVENTARIO"],extras:["lote","cad","reg"]},
  tech:  {id:"tech",  icon:"📱",nombre:"INVENTIX TECH",  color:"#F5A623",sub:"Series, IMEI y trazabilidad",               procesos:["ENTRADA","SALIDA","INVENTARIO"],extras:["serie"]},
};

const CAT={
  core:[
    {upc:"7500001000001",id:"WB-38-NG",desc:"Watch Band Milanese 38mm",var:"NEGRO",ubic:"RACK-A3-N2",min:20,max:200,reorden:50},
    {upc:"7500001000002",id:"WB-42-NG",desc:"Watch Band Milanese 42mm",var:"NEGRO",ubic:"RACK-A3-N2",min:15,max:150,reorden:40},
    {upc:"7500001000003",id:"CAB-USB-1M",desc:"Cable USB-C 1M",var:"NEGRO",ubic:"RACK-B1",min:10,max:100,reorden:25},
  ],
  food:[
    {upc:"7501111000001",id:"JAM-250-FR",desc:"Jamón serrano 250g",var:"FRESCO",ubic:"REFRI-1",min:5,max:50,reorden:12,lote:"L-F001",cad:"2026-07-15"},
    {upc:"7501111000002",id:"YOG-125-FR",desc:"Yogurt 125g Fresa",var:"FRESA",ubic:"REFRI-2",min:10,max:100,reorden:25,lote:"L-F002",cad:"2026-06-28"},
    {upc:"7501111000003",id:"LEC-1L-ENT",desc:"Leche entera 1L",var:"ENTERA",ubic:"ANAQ-1",min:20,max:200,reorden:50,lote:"L-F003",cad:"2026-07-02"},
    {upc:"7501111000004",id:"CRE-200-NAT",desc:"Crema 200ml",var:"NATURAL",ubic:"REFRI-1",min:8,max:80,reorden:20,lote:"L-F004",cad:"2026-07-10"},
    {upc:"7501111000005",id:"MAN-500-SL",desc:"Mantequilla 500g",var:"SIN SAL",ubic:"REFRI-1",min:3,max:30,reorden:8,lote:"L-F005",cad:"2026-09-01"},
  ],
  verify:[
    {upc:"SN-A54-001",id:"SN-A54-001",desc:"Samsung Galaxy A54",var:"128GB NEGRO",ubic:"ZONA-EMBAR",serie:"SN-A54-001",autorizado:true},
    {upc:"SN-A54-002",id:"SN-A54-002",desc:"Samsung Galaxy A54",var:"128GB NEGRO",ubic:"ZONA-EMBAR",serie:"SN-A54-002",autorizado:true},
    {upc:"SN-A54-003",id:"SN-A54-003",desc:"Samsung Galaxy A54",var:"128GB AZUL",ubic:"ZONA-EMBAR",serie:"SN-A54-003",autorizado:false},
  ],
  pharma:[
    {upc:"7503333000001",id:"PARA-500",desc:"Paracetamol 500mg c/10",var:"TABLETAS",ubic:"RACK-P1",min:50,max:500,reorden:120,lote:"L-COFE-001",cad:"2027-03-15",reg:"COFEPRIS-2024-001"},
    {upc:"7503333000002",id:"IBUP-400",desc:"Ibuprofeno 400mg c/20",var:"CÁPSULAS",ubic:"RACK-P2",min:40,max:400,reorden:100,lote:"L-COFE-002",cad:"2027-06-30",reg:"COFEPRIS-2024-002"},
  ],
  tech:[
    {upc:"7502222000001",id:"CAB-UC-1M",desc:"Cable USB-C 1M",var:"NEGRO",ubic:"RACK-T1",min:20,max:200,reorden:50,serie:"SN-CAB-001"},
    {upc:"7502222000002",id:"AUD-BT-01",desc:"Audífonos Bluetooth",var:"NEGRO",ubic:"RACK-T2",min:10,max:100,reorden:25,serie:"SN-AUD-001"},
    {upc:"7502222000003",id:"CAR-20W-BL",desc:"Cargador 20W",var:"BLANCO",ubic:"RACK-T3",min:25,max:250,reorden:60,serie:"SN-CAR-001"},
  ],
};

// ══ ESTADO ══
let vert="core", proc="ENTRADA";
let cats=[...CAT.core];
let entradas=[],salidas=[],conteos=[],kardex=[],verHist=[];
let prodAct=null, scanMode="app", camStream=null, scanLoop=null;
let kxF="TODOS";

// ══ HELPERS ══
const now=()=>{const d=new Date();return`${pad(d.getDate())}/${pad(d.getMonth()+1)}/${d.getFullYear()} ${pad(d.getHours())}:${pad(d.getMinutes())}`;};
const hoy=()=>{const d=new Date();return`${pad(d.getDate())}/${pad(d.getMonth()+1)}/${d.getFullYear()}`;};
const pad=n=>String(n).padStart(2,'0');
const fmtCad=c=>{if(!c)return null;const d=new Date(c);const dias=Math.ceil((d-new Date())/86400000);return{str:`${pad(d.getDate())}/${pad(d.getMonth()+1)}/${d.getFullYear()}`,dias};};
const stock=id=>entradas.filter(e=>e.id_interno===id).reduce((s,e)=>s+e.cantidad,0)-salidas.filter(s=>s.id_interno===id).reduce((s,x)=>s+x.cantidad,0);
const vib=()=>{try{navigator.vibrate&&navigator.vibrate([80]);}catch(e){}};
const el=id=>document.getElementById(id);
const addKx=r=>kardex.unshift(r);
const navMap={"pg-home":"nl-home","pg-app":"nl-app","pg-verify":"nl-verify","pg-kardex":"nl-kx"};

const toast=(msg,bg="#1A9A54")=>{
  const t=el("toast");t.textContent=msg;t.style.background=bg;t.style.display="block";
  clearTimeout(window._tt);window._tt=setTimeout(()=>t.style.display="none",3000);
};

// ══ NAV ══
const goTo=pid=>{
  document.querySelectorAll(".page").forEach(p=>p.classList.remove("on"));
  el(pid).classList.add("on");window.scrollTo(0,0);
  document.querySelectorAll(".nav-lbl").forEach(l=>l.classList.remove("on"));
  if(navMap[pid])el(navMap[pid]).classList.add("on");
};

// ══ VERTICAL ══
const setVert=v=>{
  vert=v;cats=[...CAT[v]||[]].concat(cats.filter(p=>p._custom));
  proc=(VERTS[v]?.procesos||["ENTRADA"])[0];
  if(v==="verify"){goTo("pg-verify");return;}
  goTo("pg-app");renderApp();
};

// ══ SCANNER — NATIVO, SIN LIBRERÍAS ══
const openScanner=mode=>{
  scanMode=mode;
  el("scan-overlay").classList.add("on");
  el("cam-err").style.display="none";
  el("cam-video").style.display="block";
  el("scan-status-txt").textContent="Solicitando acceso a cámara...";

  navigator.mediaDevices.getUserMedia({
    video:{facingMode:"environment",width:{ideal:1280},height:{ideal:720}}
  }).then(stream=>{
    camStream=stream;
    const video=el("cam-video");
    video.srcObject=stream;
    video.play();
    el("scan-status-txt").textContent="Apunta al código de barras";

    // Usar BarcodeDetector si está disponible (Chrome Android moderno)
    if("BarcodeDetector" in window){
      const detector=new BarcodeDetector({formats:["ean_13","ean_8","code_128","qr_code","upc_a","upc_e","code_39","code_93","itf","aztec","data_matrix"]});
      let lastCode="", lastTime=0;
      scanLoop=setInterval(async()=>{
        if(!camStream)return;
        try{
          const codes=await detector.detect(video);
          if(codes.length>0){
            const code=codes[0].rawValue;
            const now_=Date.now();
            if(code===lastCode&&now_-lastTime<2000)return;
            lastCode=code;lastTime=now_;
            vib();closeScanner();handleCode(code);
          }
        }catch(e){}
      },300);
      el("scan-status-txt").textContent="✅ Escáner activo — apunta al código";
    } else {
      // BarcodeDetector no disponible — mostrar aviso pero mantener cámara encendida
      el("scan-status-txt").textContent="Cámara activa · Usa el campo manual para el código";
    }
  }).catch(err=>{
    el("cam-err").style.display="flex";
    el("cam-video").style.display="none";
    el("cam-err-msg").textContent=err.message||"Permiso denegado";
    el("scan-status-txt").textContent="Sin cámara — usa el campo manual ↓";
  });
};

const closeScanner=()=>{
  el("scan-overlay").classList.remove("on");
  if(scanLoop){clearInterval(scanLoop);scanLoop=null;}
  if(camStream){camStream.getTracks().forEach(t=>t.stop());camStream=null;}
};

const doManual=()=>{
  const v=el("manual-inp").value.trim();
  if(!v)return;
  el("manual-inp").value="";
  closeScanner();
  handleCode(v);
};

const handleCode=code=>{
  if(!code)return;
  if(scanMode==="verify"){verifyCode(code);return;}
  buscar(code);
};

// ══ BUSCAR ══
const buscar=code=>{
  const p=cats.find(x=>x.upc===code||x.id===code||x.serie===code);
  if(p){prodAct=p;mostrarForm(p,proc);goTo("pg-reg");toast(`✅ ${p.desc}`);}
  else{
    const desc=prompt(`Código: ${code}\n¿Descripción del producto?`);
    if(!desc)return;
    const nuevo={upc:code,id:"P-"+code.slice(-4),desc,var:"GENÉRICO",ubic:"SIN UB",min:0,max:999,reorden:0,_custom:true};
    cats.push(nuevo);prodAct=nuevo;
    mostrarForm(nuevo,proc);goTo("pg-reg");
    toast(`✅ "${desc}" agregado`);
  }
};

const manualSearch=()=>{const v=el("app-manual").value.trim();if(!v)return;el("app-manual").value="";buscar(v);};

// ══ FORM REGISTRO ══
const mostrarForm=(p,proceso)=>{
  proc=proceso;
  const cfg=VERTS[vert]||VERTS.core;
  const cad=p.cad?fmtCad(p.cad):null;
  const stk=stock(p.id);

  el("reg-title").textContent=proceso;
  el("reg-back").onclick=()=>goTo("pg-app");
  const saveBtn=el("reg-save-btn");
  saveBtn.style.background=proceso==="SALIDA"?"var(--danger)":"var(--orange)";
  saveBtn.textContent=proceso==="SALIDA"?"📤 Confirmar salida":proceso==="INVENTARIO"?"📋 Guardar conteo":"📥 Confirmar entrada";

  el("reg-prod-card").innerHTML=`
    <div style="display:flex;justify-content:space-between;align-items:flex-start">
      <div style="flex:1">
        <div style="font-family:monospace;font-size:10px;color:#4A6FA5">${p.upc}</div>
        <div style="font-size:16px;font-weight:900;margin-top:3px">${p.desc}</div>
        <div style="font-size:12px;color:${cfg.color};margin-top:2px">${p.var}</div>
        <div style="font-size:11px;color:#4A6FA5;margin-top:2px">📍 ${p.ubic}</div>
        ${cad?`<div style="margin-top:8px;padding:6px 10px;border-radius:8px;font-size:11px;font-weight:700;
          background:${cad.dias<7?"#D6303115":cad.dias<30?"#E17B0015":"#1A9A5415"};
          color:${cad.dias<7?"#D63031":cad.dias<30?"#E17B00":"#1A9A54"};
          border:1px solid ${cad.dias<7?"#D6303133":cad.dias<30?"#E17B0033":"#1A9A5433"}">
          ${cad.dias<7?"🔴":cad.dias<30?"🟡":"🟢"} Cad: ${cad.str}${cad.dias<30?` (${cad.dias}d)`:""}</div>`:""}
        ${proceso==="SALIDA"?`<div style="margin-top:10px;padding:10px;background:#ffffff08;border-radius:8px;display:flex;justify-content:space-between">
          <span style="font-size:11px;color:#4A6FA5">Stock disponible</span>
          <span style="font-size:20px;font-weight:900;font-family:monospace;color:${stk>0?"var(--success)":"var(--danger)"}">${stk}</span>
        </div>`:""}
      </div>
      <div style="font-size:40px;margin-left:12px">${cfg.icon}</div>
    </div>`;

  let html=`<label class="lbl">${proceso==="INVENTARIO"?"Conteo físico *":"Cantidad *"}</label>
    <input type="number" id="rf-cant" min="0" placeholder="0" class="big-num mb" inputmode="numeric"
      style="border-color:${proceso==="SALIDA"?"var(--danger)":"var(--orange)"}">`;

  if(proceso!=="SALIDA"){
    html+=`<div class="g2"><div><label class="lbl">Ubicación</label><input type="text" id="rf-ubic" value="${p.ubic||""}" placeholder="RACK-A1"></div>`;
    if(cfg.extras.includes("lote"))html+=`<div><label class="lbl">Lote</label><input type="text" id="rf-lote" value="${p.lote||""}" placeholder="L-001"></div></div>`;
    else html+=`<div><label class="lbl">OC</label><input type="text" id="rf-oc" placeholder="OC-001"></div></div>`;
    if(cfg.extras.includes("cad"))html+=`<div class="g2"><div><label class="lbl">Caducidad</label><input type="date" id="rf-cad" value="${p.cad||""}" oninput="chkCad()"></div><div><label class="lbl">Proveedor</label><input type="text" id="rf-prov" placeholder="Proveedor"></div></div>`;
    if(cfg.extras.includes("temp"))html+=`<label class="lbl">Temperatura °C</label><input type="number" id="rf-temp" placeholder="-2" step="0.1" class="mb">`;
    if(cfg.extras.includes("reg"))html+=`<label class="lbl">Reg. sanitario</label><input type="text" id="rf-reg" value="${p.reg||""}" placeholder="COFEPRIS" class="mb">`;
    if(cfg.extras.includes("serie"))html+=`<label class="lbl">Número de serie</label><input type="text" id="rf-serie" value="${p.serie||""}" placeholder="SN-001" class="mb">`;
  }else{
    html+=`<div class="g2"><div><label class="lbl">Canal</label><input type="text" id="rf-canal" placeholder="TIENDA-01"></div><div><label class="lbl">OC</label><input type="text" id="rf-oc" placeholder="PED-001"></div></div>`;
  }
  el("reg-campos").innerHTML=html;
  el("reg-cad-alert").style.display="none";
  setTimeout(()=>el("rf-cant").focus(),300);
};

const chkCad=()=>{
  const v=el("rf-cad")?.value,a=el("reg-cad-alert");if(!v||!a)return;
  const i=fmtCad(v);
  if(i.dias<=0){a.style.display="block";a.className="alert alert-e";a.textContent="🔴 PRODUCTO VENCIDO";}
  else if(i.dias<=7){a.style.display="block";a.className="alert alert-e";a.textContent=`⚠️ Vence en ${i.dias} días`;}
  else if(i.dias<=30){a.style.display="block";a.className="alert alert-w";a.textContent=`⚠️ Próximo a vencer: ${i.dias} días`;}
  else a.style.display="none";
};

const saveReg=()=>{
  const cant=parseInt(el("rf-cant")?.value)||0;
  if(cant<=0){toast("⚠️ Ingresa una cantidad","#E17B00");return;}
  if(proc==="SALIDA"&&cant>stock(prodAct.id)){toast("❌ Stock insuficiente","#D63031");return;}
  const loteFefo=proc==="SALIDA"?(()=>{
    const ls=entradas.filter(e=>e.id_interno===prodAct.id&&e.lote)
      .sort((a,b)=>new Date(a.cad||"9999")-new Date(b.cad||"9999"));
    return ls[0]?.lote||prodAct.lote||"";
  })():"";
  const reg={
    id:Date.now(),ts:now(),upc:prodAct.upc,id_interno:prodAct.id,
    desc:prodAct.desc,var:prodAct.var,cantidad:cant,proceso:proc,vertical:vert,
    ubicacion:el("rf-ubic")?.value||prodAct.ubic||"",
    lote:el("rf-lote")?.value||loteFefo||prodAct.lote||"",
    caducidad:el("rf-cad")?.value||"",oc:el("rf-oc")?.value||"",
    proveedor:el("rf-prov")?.value||"",temperatura:el("rf-temp")?.value||"",
    reg_sanitario:el("rf-reg")?.value||"",serie:el("rf-serie")?.value||prodAct.serie||"",
    canal:el("rf-canal")?.value||"",fefo:proc==="SALIDA"?"✅ FEFO OK":"",estado:"OK",
  };
  if(proc==="ENTRADA")entradas.push(reg);
  else if(proc==="SALIDA")salidas.push(reg);
  else conteos.push(reg);
  addKx(reg);vib();
  toast(proc==="SALIDA"?`📤 Salida: ${cant} pzas`:`📥 Entrada: ${cant} pzas`,
    proc==="SALIDA"?"#D63031":"#1A9A54");
  prodAct=null;goTo("pg-app");renderApp();
};

// ══ VERIFY ══
const verifyCode=code=>{
  code=(code||"").trim();
  const p=CAT.verify.find(x=>x.serie===code||x.upc===code||x.id===code);
  const ts=now();
  let html,resultado,color;
  if(!p){html=`<div class="alert alert-w">⚠️ Código <b style="font-family:monospace">${code}</b> no encontrado en el pedido.</div>`;resultado="NO ENCONTRADO";color="#E17B00";}
  else if(!p.autorizado){html=`<div class="alert alert-e">❌ <b style="font-family:monospace">${code}</b> — ${p.desc} — <b>NO AUTORIZADA</b></div>`;resultado="NO AUTORIZADO";color="#D63031";}
  else{html=`<div class="alert alert-s">✅ <b style="font-family:monospace">${code}</b> — ${p.desc} ${p.var} — <b>AUTORIZADA ✓</b></div>`;resultado="AUTORIZADO";color="#1A9A54";addKx({id:Date.now(),ts,upc:code,id_interno:p.id,desc:p.desc,var:p.var,cantidad:1,proceso:"VERIFICAR",vertical:"verify",estado:"OK",serie:code});}
  verHist.unshift({ts,code,desc:p?.desc||"",resultado,color});
  vib();el("verify-resultado").style.display="block";el("verify-resultado").innerHTML=html;
  renderVerHist();
};
const verifySearch=()=>{const v=el("verify-manual").value.trim();if(!v)return;el("verify-manual").value="";verifyCode(v);};
const renderVerHist=()=>{
  const c=el("verify-hist");
  if(!verHist.length){c.innerHTML='<div style="text-align:center;padding:20px;color:#4A6FA5;font-size:12px">Sin validaciones aún</div>';return;}
  c.innerHTML=verHist.slice(0,8).map(v=>`<div class="kx-row" style="border-left-color:${v.color}">
    <div style="display:flex;justify-content:space-between;align-items:center">
      <div>
        <div style="font-family:monospace;font-size:12px;font-weight:800;color:${v.color}">${v.code}</div>
        ${v.desc?`<div style="font-size:10px;color:#4A6FA5;margin-top:2px">${v.desc}</div>`:""}
        <div style="font-size:9px;color:#333;margin-top:1px">${v.ts}</div>
      </div>
      <div style="background:${v.color}22;color:${v.color};border:1px solid ${v.color}33;border-radius:6px;padding:3px 10px;font-size:10px;font-weight:800;flex-shrink:0;margin-left:10px">${v.resultado}</div>
    </div>
  </div>`).join("");
};

// ══ RENDER APP ══
const renderApp=()=>{
  const cfg=VERTS[vert]||VERTS.core;
  el("app-title").textContent=cfg.nombre;
  el("app-sub").textContent=cfg.sub;
  el("proc-tabs").innerHTML=cfg.procesos.map(p=>`<button class="vert-tab ${proc===p?"on":""}"
    onclick="proc='${p}';renderApp()"
    style="${proc===p?`background:${cfg.color};border-color:${cfg.color};color:${cfg.id==="tech"?"#0F2747":"#fff"}`:""}">${p}</button>`).join("");
  const movs=[...entradas,...salidas,...conteos].filter(m=>m.vertical===vert).reverse().slice(0,10);
  const cmap={"ENTRADA":"#1A9A54","SALIDA":"#D63031","INVENTARIO":"#6C3FCB"};
  const c=el("app-movs");
  if(!movs.length){c.innerHTML=`<div style="text-align:center;padding:32px;color:#4A6FA5;font-size:13px">Sin registros aún.<br>Escanea o ingresa un producto.</div>`;return;}
  c.innerHTML=`<div style="font-size:10px;font-weight:800;color:#4A6FA5;text-transform:uppercase;letter-spacing:.8px;margin-bottom:10px">Últimos movimientos</div>`+
  movs.map(m=>`<div class="mov-row" style="border-left-color:${cmap[m.proceso]||cfg.color}">
    <div style="flex:1;min-width:0">
      <div style="font-size:12px;font-weight:800;color:${cfg.color};white-space:nowrap;overflow:hidden;text-overflow:ellipsis">${m.desc}</div>
      <div style="font-size:10px;color:#4A6FA5;margin-top:2px">${m.proceso} · ${m.ts.split(" ")[1]}${m.lote?" · "+m.lote:""}${m.serie?" · "+m.serie:""}</div>
    </div>
    <div style="font-size:20px;font-weight:900;color:${m.proceso==="SALIDA"?"#D63031":"#1A9A54"};font-family:monospace;margin-left:10px;flex-shrink:0">${m.proceso==="SALIDA"?"−":"+"}${m.cantidad}</div>
  </div>`).join("");
};

// ══ KARDEX ══
const PC={"ENTRADA":"#1A9A54","SALIDA":"#D63031","INVENTARIO":"#6C3FCB","VERIFICAR":"#8B6FD4"};
const PI={"ENTRADA":"📥","SALIDA":"📤","INVENTARIO":"📋","VERIFICAR":"✅"};
const renderKardex=()=>{
  el("kx-cnt").textContent=`${kardex.length} movimiento${kardex.length!==1?"s":""}`;
  const filtros=["TODOS","ENTRADA","SALIDA","INVENTARIO","VERIFICAR"];
  el("kx-filtros").innerHTML=filtros.map(f=>`<button onclick="kxF='${f}';renderKardex()"
    style="padding:5px 14px;border-radius:20px;border:none;white-space:nowrap;cursor:pointer;font-size:10px;font-weight:700;
    background:${kxF===f?"var(--orange)":"var(--navy)"};color:${kxF===f?"var(--navy)":"#4A6FA5"}">${f}</button>`).join("");
  const lista=kxF==="TODOS"?kardex:kardex.filter(k=>k.proceso===kxF);
  const c=el("kx-lista");
  if(!lista.length){c.innerHTML='<div style="text-align:center;padding:32px;color:#4A6FA5;font-size:13px">Sin movimientos aún</div>';return;}
  c.innerHTML=lista.map(k=>{
    const color=PC[k.proceso]||"#4A6FA5",icon=PI[k.proceso]||"•",v=VERTS[k.vertical||"core"];
    return`<div class="kx-row" style="border-left-color:${color}">
      <div style="display:flex;gap:10px">
        <div style="width:34px;height:34px;border-radius:50%;background:${color}22;display:flex;align-items:center;justify-content:center;font-size:16px;flex-shrink:0">${icon}</div>
        <div style="flex:1;min-width:0">
          <div style="display:flex;justify-content:space-between;align-items:flex-start">
            <div style="display:flex;gap:6px;align-items:center;flex-wrap:wrap">
              <span style="font-size:10px;font-weight:800;text-transform:uppercase;color:${color}">${k.proceso}</span>
              ${v?`<span style="font-size:9px;background:${v.color}22;color:${v.color};border:1px solid ${v.color}33;border-radius:10px;padding:1px 7px;font-weight:700">${v.icon}</span>`:""}
            </div>
            <span style="font-size:9px;color:#333;flex-shrink:0">${k.ts}</span>
          </div>
          <div style="font-family:monospace;font-size:11px;color:var(--orange);margin-top:3px">${k.id_interno}<span style="color:#4A6FA5"> · ${k.cantidad} pzas</span></div>
          <div style="font-size:10px;color:#4A6FA5;margin-top:1px">${k.desc||""}${k.lote?" · "+k.lote:""}${k.serie?" · "+k.serie:""}</div>
        </div>
      </div>
    </div>`;
  }).join("");
};

// ══ HOME ══
const renderHome=()=>{
  const allProds=Object.values(CAT).flat().filter((p,i,a)=>a.findIndex(x=>x.id===p.id)===i);
  const totalStock=allProds.reduce((s,p)=>s+Math.max(0,stock(p.id)),0);
  const movHoy=kardex.filter(k=>k.ts.startsWith(hoy())).length;
  const sinStock=allProds.filter(p=>stock(p.id)<=0).length;
  const verOK=verHist.filter(v=>v.resultado==="AUTORIZADO").length;
  el("home-kpis").innerHTML=`
    <div class="kpi" style="border-top-color:var(--orange)"><div class="kpi-val" style="color:var(--orange)">${totalStock}</div><div class="kpi-lbl">Stock total</div></div>
    <div class="kpi" style="border-top-color:${sinStock>0?"var(--danger)":"#333"}"><div class="kpi-val" style="color:${sinStock>0?"var(--danger)":"#4A6FA5"}">${sinStock}</div><div class="kpi-lbl">Sin stock</div></div>
    <div class="kpi" style="border-top-color:var(--success)"><div class="kpi-val" style="color:var(--success)">${movHoy}</div><div class="kpi-lbl">Movs. hoy</div></div>
    <div class="kpi" style="border-top-color:#8B6FD4"><div class="kpi-val" style="color:#8B6FD4">${verOK}</div><div class="kpi-lbl">Verify OK</div></div>`;
  el("home-alert").innerHTML=sinStock>0?`<div class="alert alert-e" style="font-size:11px;margin-bottom:12px">⚠️ ${sinStock} producto${sinStock>1?"s":""} sin stock</div>`:"";
  el("vert-list").innerHTML=Object.values(VERTS).map(v=>`
    <div class="vertical-card" onclick="setVert('${v.id}')">
      <div class="vert-icon" style="background:${v.color}22;border:1.5px solid ${v.color}33">${v.icon}</div>
      <div style="flex:1"><div style="font-size:13px;font-weight:800;color:${v.color}">${v.nombre}</div><div style="font-size:11px;color:#4A6FA5;margin-top:2px">${v.sub}</div></div>
      <div style="color:#4A6FA5;font-size:18px">›</div>
    </div>`).join("");
};

// ══ INIT ══
renderHome();
</script>
</body>
</html>
