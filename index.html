<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover" />
  <meta name="description" content="Painel Técnico de Segurança do Trabalho - SST" />
  <meta name="author" content="Vytor Vilar" />
  <meta http-equiv="X-Content-Type-Options" content="nosniff" />
  <meta http-equiv="Referrer-Policy" content="strict-origin-when-cross-origin" />

  <title>SST • Painel Técnico</title>
  <link rel="icon" type="image/png" href="icone.png" />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">

  <!-- libs -->
  <script defer src="https://cdn.jsdelivr.net/npm/xlsx@0.18.5/dist/xlsx.full.min.js"></script>
  <script defer src="https://cdn.jsdelivr.net/npm/jspdf@2.5.1/dist/jspdf.umd.min.js"></script>
  <script defer src="https://cdn.jsdelivr.net/npm/jspdf-autotable@3.8.2/dist/jspdf.plugin.autotable.min.js"></script>

  <style>
    :root{
  /* ===== PALETA PREMIUM (LIGHT) ===== */
  --bg: #f6f7fb;
  --fg: #0f172a;
  --muted: #64748b;

  --card: rgba(255,255,255,0.78);
  --card-solid:#ffffff;

  --border: rgba(15, 23, 42, 0.10);
  --border-strong: rgba(15, 23, 42, 0.14);

  --primary:#1b7c4b;
  --primary-700:#166534;
  --accent:#22c55e;

  --ok:#16a34a;
  --warn:#eab308;
  --err:#dc2626;

  /* ===== SOMBRAS / GLASS ===== */
  --shadow: 0 18px 45px rgba(15, 23, 42, 0.12);
  --shadow-soft: 0 10px 22px rgba(15, 23, 42, 0.10);
  --shadow-inset: inset 0 1px 0 rgba(255,255,255,0.85);

  --radius: 18px;
  --radius-sm: 14px;

  --topbar-h: 70px;

  /* Fundo “glass” das imagens */
  --img-bg: rgba(255,255,255,0.55);
  --img-border: rgba(15, 23, 42, 0.12);
  --img-grid: rgba(15, 23, 42, 0.04);
}

*{ box-sizing:border-box; }
html,body{ height:100%; }

body{
  margin:0;
  font-family: Inter,system-ui,-apple-system,Segoe UI,Roboto,sans-serif;
  color:var(--fg);

  /* Background premium com 3 layers */
  background:
    radial-gradient(1200px 650px at 15% -10%, rgba(34,197,94,.22), transparent 60%),
    radial-gradient(1000px 650px at 110% 0%, rgba(27,124,75,.18), transparent 55%),
    linear-gradient(180deg, rgba(255,255,255,0.75), rgba(246,247,251,1)),
    var(--bg);
}

a{ color:inherit; text-decoration:none; }
.container{ width:min(1120px, 100%); margin:0 auto; padding: 0 14px; }

/* ===== TOPBAR (mais premium) ===== */
.topbar{
  position: sticky;
  top:0;
  z-index: 50;
  height: var(--topbar-h);
  display:flex;
  align-items:center;

  backdrop-filter: blur(14px);
  -webkit-backdrop-filter: blur(14px);

  background: rgba(246,247,251,0.78);
  border-bottom: 1px solid var(--border);
}

.topbar-inner{
  display:flex;
  align-items:center;
  justify-content:space-between;
  gap:12px;
  width:100%;
}

.brand{
  display:flex;
  align-items:center;
  gap:10px;
  min-width: 220px;
}

.logo{
  width:44px; height:44px;
  border-radius: 16px;
  background: linear-gradient(135deg, var(--primary), var(--accent));
  box-shadow: var(--shadow-soft);
  display:grid;
  place-items:center;
  color:#fff;
  font-weight:900;
  letter-spacing:.6px;
  user-select:none;
}

.brand h1{
  font-size: 14px;
  line-height: 1.1;
  margin:0;
}

.brand small{
  display:block;
  color: var(--muted);
  font-weight:700;
  margin-top:2px;
}

.top-actions{
  display:flex;
  align-items:center;
  gap:8px;
  flex-wrap:wrap;
  justify-content:flex-end;
}

/* ===== NAV TABS (mais clean) ===== */
.tabs{
  display:flex;
  gap:8px;
  overflow:auto;
  padding: 12px 0;
  scrollbar-width: thin;
}

.tab{
  border:1px solid var(--border);
  background: rgba(255,255,255,0.72);
  color: var(--fg);
  padding: 10px 13px;
  border-radius: 999px;
  cursor:pointer;
  transition: transform .18s, box-shadow .18s, background .18s;
  white-space: nowrap;
  user-select:none;
  box-shadow: 0 6px 14px rgba(15,23,42,0.06);
}

.tab:hover{
  transform: translateY(-1px);
  box-shadow: 0 10px 22px rgba(15,23,42,0.10);
}

.tab[aria-selected="true"]{
  background: linear-gradient(135deg, var(--primary), var(--accent));
  border-color: transparent;
  color:#fff;
  font-weight: 800;
  box-shadow: var(--shadow);
}

/* ===== COMMON UI ===== */
.btn{
  border:none;
  cursor:pointer;
  padding: 10px 12px;
  border-radius: 14px;
  transition: transform .18s, box-shadow .18s, filter .18s;
  display:inline-flex;
  align-items:center;
  gap:8px;
  font-weight:800;
}

.btn:active{ transform: translateY(1px); }

.btn-primary{
  background: linear-gradient(135deg, var(--primary), var(--accent));
  color:#fff;
  box-shadow: var(--shadow-soft);
}

.btn-primary:hover{
  filter: brightness(1.03);
  box-shadow: var(--shadow);
  transform: translateY(-1px);
}

.btn-ghost{
  background: rgba(255,255,255,0.72);
  border: 1px solid var(--border);
  color: var(--fg);
  box-shadow: 0 8px 18px rgba(15,23,42,0.07);
}

.btn-ghost:hover{
  transform: translateY(-1px);
  box-shadow: 0 12px 26px rgba(15,23,42,0.10);
}

.pill{
  display:inline-flex;
  align-items:center;
  gap:8px;
  padding: 8px 10px;
  border-radius: 999px;
  border:1px solid var(--border);
  background: rgba(255,255,255,0.70);
  color: var(--muted);
  font-weight:800;
  font-size: 12px;
  box-shadow: 0 8px 18px rgba(15,23,42,0.06);
}

/* ===== CARDS PREMIUM (glass) ===== */
.card{
  background: var(--card);
  border: 1px solid var(--border);
  border-radius: var(--radius);
  box-shadow: var(--shadow);
  padding: 14px;

  backdrop-filter: blur(10px);
  -webkit-backdrop-filter: blur(10px);

  position: relative;
}

.card::before{
  content:"";
  position:absolute;
  inset:0;
  border-radius: inherit;
  pointer-events:none;
  box-shadow: var(--shadow-inset);
}

.grid{
  display:grid;
  grid-template-columns: repeat(auto-fill, minmax(240px, 1fr));
  gap: 14px;
}

.row{
  display:flex;
  gap:10px;
  flex-wrap:wrap;
  align-items:center;
}

.muted{ color: var(--muted); }

.badge{
  display:inline-flex;
  align-items:center;
  gap:6px;
  padding: 6px 10px;
  border-radius: 999px;
  background: rgba(22,163,74,0.12);
  color: rgba(22,163,74,0.95);
  font-weight: 900;
  font-size: 12px;
}

/* ===== INPUTS MAIS PREMIUM ===== */
input, select, textarea{
  width:100%;
  padding: 12px 12px;
  border-radius: 14px;
  border: 1px solid var(--border);
  background: rgba(255,255,255,0.72);
  color: var(--fg);
  outline:none;
  box-shadow: 0 8px 18px rgba(15,23,42,0.05);
}

input:focus, select:focus, textarea:focus{
  border-color: rgba(34,197,94,0.45);
  box-shadow: 0 0 0 4px rgba(34,197,94,0.16), 0 10px 22px rgba(15,23,42,0.08);
}

/* ===== MAIN ===== */
main{ padding: 14px 0 110px; }
section{ display:none; }
section.active{ display:block; }

.section-head{
  display:flex;
  align-items:flex-start;
  justify-content:space-between;
  gap:12px;
  margin: 14px 0;
}

.section-head h2{
  margin:0;
  font-size: 18px;
  letter-spacing: .2px;
}

/* =======================================================
   ✅ FUNDO DAS IMAGENS PADRONIZADO (GLASS / CLEAN)
   ======================================================= */
.epi{
  display:flex;
  flex-direction:column;
  gap:10px;
  transition: transform .18s, box-shadow .18s;
}

.epi:hover{
  transform: translateY(-2px);
}

.epi-img{
  height: 175px;
  border-radius: 16px;
  border: 1px solid var(--img-border);
  box-shadow: 0 10px 24px rgba(15,23,42,0.08);
  overflow:hidden;

  /* glass + padrão leve */
  background:
    linear-gradient(180deg, rgba(255,255,255,0.75), rgba(255,255,255,0.38)),
    radial-gradient(circle at 30% 20%, rgba(34,197,94,0.10), transparent 45%),
    radial-gradient(circle at 70% 80%, rgba(27,124,75,0.10), transparent 46%),
    repeating-linear-gradient(
      45deg,
      transparent 0px,
      transparent 10px,
      var(--img-grid) 10px,
      var(--img-grid) 12px
    ),
    var(--img-bg);

  display:grid;
  place-items:center;

  backdrop-filter: blur(10px);
  -webkit-backdrop-filter: blur(10px);
}

.epi-img img{
  max-width: 92%;
  max-height: 92%;
  object-fit: contain;
  transition: transform .22s ease, filter .22s ease;
  filter: drop-shadow(0 10px 18px rgba(15,23,42,0.18));
}

.epi:hover .epi-img img{
  transform: scale(1.05);
  filter: drop-shadow(0 14px 26px rgba(15,23,42,0.22));
}

.epi h3{
  margin:0;
  font-size: 13px;
  line-height: 1.25;
  min-height: 34px;
}

/* ===== ACCORDION ===== */
.accordion{ display:flex; flex-direction:column; gap:10px; }
.acc-item{
  border:1px solid var(--border);
  border-radius: var(--radius-sm);
  overflow:hidden;
  background: rgba(255,255,255,0.70);
  box-shadow: 0 10px 22px rgba(15,23,42,0.06);
}

.acc-btn{
  width:100%;
  text-align:left;
  padding: 12px 12px;
  background: transparent;
  border:none;
  cursor:pointer;
  color: var(--fg);
  font-weight: 900;
  display:flex;
  justify-content:space-between;
  gap:10px;
  align-items:center;
}

.acc-body{
  display:none;
  padding: 0 12px 12px;
  color: var(--muted);
  font-weight: 700;
  line-height: 1.45;
}

.acc-item.active .acc-body{ display:block; }

/* ===== CHAT ===== */
.chat-fab{
  position: fixed;
  right: 18px;
  bottom: 18px;
  z-index: 120;
}

.chat-box{
  position: fixed;
  right: 18px;
  bottom: 78px;
  z-index: 121;
  width: 340px;
  max-width: calc(100vw - 36px);
  height: 460px;
  display:none;
  flex-direction:column;
  background: rgba(255,255,255,0.80);
  border: 1px solid var(--border);
  border-radius: 18px;
  box-shadow: var(--shadow);
  overflow:hidden;
  backdrop-filter: blur(12px);
  -webkit-backdrop-filter: blur(12px);
}

.chat-box.active{ display:flex; }

.chat-top{
  padding: 10px 12px;
  display:flex;
  justify-content:space-between;
  align-items:center;
  border-bottom:1px solid var(--border);
  font-weight: 950;
}

.chat-msgs{
  padding: 12px;
  overflow:auto;
  display:flex;
  flex-direction:column;
  gap:10px;
}

.bubble{
  max-width: 85%;
  padding: 10px 12px;
  border-radius: 14px;
  border: 1px solid var(--border);
  background: rgba(246,247,251,0.85);
  color: var(--fg);
  font-weight: 700;
  line-height: 1.35;
}

.me{ align-self:flex-end; }
.me .bubble{
  background: linear-gradient(135deg, var(--primary), var(--accent));
  border-color: transparent;
  color:#fff;
}

.chat-input{
  border-top:1px solid var(--border);
  padding: 10px;
  display:flex;
  gap:8px;
}

/* ===== FLOATING PANEL ===== */
.fab-panel{
  position: fixed;
  left: 18px;
  bottom: 18px;
  z-index: 120;
  display:flex;
  flex-direction:column;
  gap:10px;
  align-items:flex-start;
}

.fab-main{
  width: 54px;
  height: 54px;
  border-radius: 999px;
  display:grid;
  place-items:center;
  background: linear-gradient(135deg, var(--primary), var(--accent));
  color:#fff;
  border:none;
  box-shadow: var(--shadow-soft);
  cursor:pointer;
  transition: transform .18s, box-shadow .18s;
}

.fab-main:hover{
  transform: translateY(-1px);
  box-shadow: var(--shadow);
}

.fab-actions{
  display:none;
  flex-direction:column;
  gap:8px;
}

.fab-panel.open .fab-actions{ display:flex; }

.fab-action{
  border-radius: 999px;
  padding: 10px 12px;
  border:1px solid var(--border);
  background: rgba(255,255,255,0.78);
  color: var(--fg);
  cursor:pointer;
  box-shadow: 0 10px 22px rgba(15,23,42,0.08);
  font-weight: 900;
  display:flex;
  align-items:center;
  gap:8px;
  backdrop-filter: blur(10px);
  -webkit-backdrop-filter: blur(10px);
}

/* ===== TOAST ===== */
.toast{
  position: fixed;
  right: 18px;
  bottom: 92px;
  z-index: 200;
  padding: 12px 14px;
  border-radius: 14px;
  border:1px solid var(--border);
  background: #111827;
  color:#fff;
  box-shadow: var(--shadow-soft);
  opacity:0;
  transform: translateY(10px);
  transition: .25s;
  pointer-events:none;
  font-weight: 900;
}

.toast.show{ opacity:1; transform: translateY(0); }
.toast.ok{ background: var(--ok); }
.toast.err{ background: var(--err); }
.toast.warn{ background: var(--warn); color:#111827; }

/* ===== PASSWORD MODAL ===== */
.backdrop{
  position: fixed;
  inset:0;
  background: rgba(15,23,42,.55);
  display:none;
  align-items:center;
  justify-content:center;
  z-index: 999;
  padding: 14px;
}

.backdrop.active{ display:flex; }

.modal{
  width: 420px;
  max-width: 100%;
  background: rgba(255,255,255,0.86);
  border: 1px solid var(--border);
  border-radius: 20px;
  box-shadow: var(--shadow);
  padding: 18px;
  backdrop-filter: blur(14px);
  -webkit-backdrop-filter: blur(14px);
}

.modal h3{ margin: 0 0 6px; }
.modal .hint{ color: var(--muted); margin: 0 0 12px; font-weight: 750; }

.pass-row{ display:flex; gap:8px; align-items:center; }
.pass-row input{ flex: 1; }

.err{
  margin: 10px 0 0;
  color: rgba(220,38,38,0.95);
  font-weight: 950;
  display:none;
}
.err.show{ display:block; }

footer{
  border-top: 1px solid var(--border);
  padding: 16px 0;
  color: var(--muted);
}

/* ===== MOBILE ===== */
@media (max-width: 680px){
  .brand{ min-width: auto; }
  .topbar-inner{ gap:10px; }
  .tabs{ padding-top: 8px; }
}

  </style>
</head>

<body>
  <!-- ====== APP (fica oculto até liberar senha) ====== -->
  <div id="app" hidden>
    <header class="topbar">
      <div class="container topbar-inner">
        <div class="brand">
          <div class="logo" aria-hidden="true">SST</div>
          <div>
            <h1>Painel Técnico • Segurança do Trabalho</h1>
            <small>Versão 3.0 • Ultra Master</small>
          </div>
        </div>

        <div class="top-actions">
          <span class="pill" id="statusPill" title="Status do sistema">✅ Online</span>
          <button class="btn btn-ghost" id="pdfBtn" title="Salvar PDF da seção atual">🧾 PDF</button>
        </div>
      </div>
    </header>

    <div class="container">
      <nav class="tabs" aria-label="Navegação principal" role="tablist">
        <button class="tab" role="tab" data-tab="epis" aria-selected="true" title="Catálogo de EPIs">📒 EPIs</button>
        <button class="tab" role="tab" data-tab="riscos" aria-selected="false" title="Avaliação de Riscos">🧪 Riscos</button>
        <button class="tab" role="tab" data-tab="empresas" aria-selected="false" title="Gerador de frases por empresa">🏢 Frases</button>
        <button class="tab" role="tab" data-tab="treinamento" aria-selected="false" title="Plano de Ação 5W2H">📚 5W2H</button>
        <button class="tab" role="tab" data-tab="riscos_empresas" aria-selected="false" title="Riscos por empresa">📋 Riscos/Empresa</button>
        <button class="tab" role="tab" data-tab="nrs" aria-selected="false" title="Normas Regulamentadoras">📖 NRs</button>
        <button class="tab" role="tab" data-tab="painel_tecnico" aria-selected="false" title="Painel técnico e FAQ">🛠 Painel</button>
      </nav>
    </div>

    <main class="container" id="main">
      <!-- ===== EPIs ===== -->
      <section id="epis" class="active" aria-label="Catálogo de EPIs">
        <div class="section-head">
          <div>
            <h2>Catálogo de EPIs</h2>
            <div class="muted" id="epiCount">—</div>
          </div>
          <div class="row">
            <button class="btn btn-ghost" id="clearEpiBtn" title="Limpar busca e filtro">❌ Limpar</button>
          </div>
        </div>

        <div class="card">
          <div class="row">
            <input id="searchInput" type="text" placeholder="Buscar por nome, CA ou categoria..." aria-label="Buscar EPIs" />
            <select id="categoryFilter" aria-label="Filtrar por categoria">
              <option value="">Todas as categorias</option>
            </select>
          </div>
          <div class="muted" style="margin-top:6px; font-weight:900;">
            Dica: clique em “Copiar” para copiar rapidamente.
          </div>
        </div>

        <div style="height:12px"></div>
        <div id="catalog" class="grid" aria-live="polite"></div>
      </section>

      <!-- ===== RISCOS ===== -->
      <section id="riscos" aria-label="Avaliação de Riscos">
        <div class="section-head">
          <div>
            <h2>Avaliação de Riscos</h2>
            <div class="muted">Modelos prontos para copiar</div>
          </div>
          <div class="row">
            <select id="riskFilter" aria-label="Filtro de riscos" title="Filtrar por tipo de risco">
              <option value="todos">Todos</option>
              <option value="fisico">Físico 📘</option>
              <option value="biologico">Biológico 🧬</option>
              <option value="quimico">Químico 🧪</option>
            </select>
          </div>
        </div>

        <div class="grid" id="riskCards"></div>
      </section>

      <!-- ===== FRASES EMPRESA ===== -->
      <section id="empresas" aria-label="Frases com Empresa">
        <div class="section-head">
          <div>
            <h2>Gerador de Frases com Empresa</h2>
            <div class="muted">Um nome por linha</div>
          </div>
          <div class="row">
            <button class="btn btn-primary" id="genPhrasesBtn" title="Gerar frases">⚡ Gerar</button>
            <button class="btn btn-ghost" id="exportTxtBtn" title="Exportar TXT">📄 TXT</button>
          </div>
        </div>

        <div class="grid">
          <div class="card">
            <textarea id="nomes" rows="10" placeholder="Ex: João Silva"></textarea>
          </div>

          <div class="card">
            <input id="empresa" type="text" placeholder="Nome da empresa" />
            <input id="data" type="text" placeholder="Data" />
            <div class="muted" style="font-weight:950;">Formato gerado:</div>
            <div class="muted">Nome, Empresa, , , Data</div>
          </div>
        </div>

        <div style="height:12px"></div>
        <div class="card">
          <div style="display:flex; justify-content:space-between; gap:10px; flex-wrap:wrap;">
            <div style="font-weight:950;">Resultado</div>
            <button class="btn btn-ghost" id="copyPhrasesBtn" title="Copiar tudo">📋 Copiar</button>
          </div>
          <pre id="resultado" style="margin:10px 0 0; white-space:pre-wrap; word-break:break-word; color:var(--fg); font-weight:850;">—</pre>
        </div>
      </section>

      <!-- ===== 5W2H ===== -->
      <section id="treinamento" aria-label="Plano de ação 5W2H">
        <div class="section-head">
          <div>
            <h2>Plano de Ação 5W2H</h2>
            <div class="muted">Clique em copiar para usar no laudo/treinamento</div>
          </div>
        </div>

        <div class="grid" id="w2hGrid"></div>
      </section>

      <!-- ===== RISCOS POR EMPRESA ===== -->
      <section id="riscos_empresas" aria-label="Riscos por Empresa">
        <div class="section-head">
          <div>
            <h2>Riscos por Empresa</h2>
            <div class="muted">Buscar por risco, empresa ou setor</div>
          </div>
        </div>

        <div class="card">
          <input id="buscaRiscos" type="text" placeholder="Buscar..." />
        </div>

        <div style="height:12px"></div>
        <div id="listaRiscosEmpresas" class="grid"></div>
      </section>

      <!-- ===== NRs ===== -->
      <section id="nrs" aria-label="Normas Regulamentadoras">
        <div class="section-head">
          <div>
            <h2>Normas Regulamentadoras</h2>
            <div class="muted">Resumo rápido + copiar título</div>
          </div>
        </div>

        <div class="grid" id="nrGrid"></div>
      </section>

      <!-- ===== PAINEL TÉCNICO ===== -->
      <section id="painel_tecnico" aria-label="Painel Técnico">
        <div class="section-head">
          <div>
            <h2>Painel Técnico</h2>
            <div class="muted">Modelos + FAQ (accordion)</div>
          </div>
        </div>

        <div class="grid">
          <div class="card">
            <h3 style="margin-top:0; font-weight:950;">📂 Modelos prontos</h3>
            <ul style="margin:0; padding-left:18px; line-height:1.7; font-weight:900; color:var(--fg);">
              <li><a href="https://drive.google.com/drive/folders/1TGYf5eNYzIcKbtL5x2BRb-pmc5VYGQQ-?usp=drive_link" target="_blank" rel="noreferrer" title="Abrir pasta no Drive">📄 PPP</a></li>
              <li><a href="https://drive.google.com/drive/folders/1y0iZMFTM9yVcs771L3o6ldhY_YIcinC9?usp=drive_link" target="_blank" rel="noreferrer" title="Abrir pasta no Drive">📝 Ordem de Serviços</a></li>
              <li><a href="https://drive.google.com/drive/folders/17GqBa56ZkdBW7OTaDcfnaaSeZQyw1u0j?usp=drive_link" target="_blank" rel="noreferrer" title="Abrir pasta no Drive">📜 Certificados</a></li>
            </ul>
            <div style="height:10px"></div>
            <div class="muted" style="font-weight:900;">Dica: mantenha esses links sempre atualizados.</div>
          </div>

          <div class="card">
            <h3 style="margin-top:0; font-weight:950;">❓ FAQ</h3>
            <div class="accordion" id="faq"></div>
          </div>
        </div>
      </section>

      <footer>
        <div class="row" style="justify-content:space-between">
          <div>
            <strong style="color:var(--fg)">© 2026 — Sistema Técnico SST</strong><br />
            <span>Desenvolvido por <strong style="color:var(--fg)">Vytor Vilar</strong></span>
          </div>
          <div class="muted" style="font-weight:950;">
            Atalhos: <span class="badge" title="Alt+1">Alt+1</span> … <span class="badge" title="Alt+7">Alt+7</span>
          </div>
        </div>

    <!-- ===== FLOATING PANEL (expansível) ===== -->
    <div class="fab-panel" id="fabPanel" aria-label="Painel flutuante">
      <button class="fab-main" id="fabMain" title="Abrir painel">☰</button>
      <div class="fab-actions">
        <button class="fab-action" id="fabTop" title="Voltar ao topo">⬆️ Topo</button>
        <button class="fab-action" id="fabPdf" title="Salvar PDF da seção atual">🧾 PDF</button>
      </div>
    </div>

    <!-- ===== CHAT ===== -->
    <button class="btn btn-primary chat-fab" id="chatFab" title="Abrir chat de ajuda">💬 Ajuda</button>

    <div class="chat-box" id="chatBox" role="dialog" aria-label="Chat de Ajuda" aria-hidden="true">
      <div class="chat-top">
        <span>Chat de Ajuda • SST</span>
        <button class="btn btn-ghost" id="chatClose" title="Fechar chat">✖</button>
      </div>
      <div class="chat-msgs" id="chatMsgs" aria-live="polite"></div>
      <div class="chat-input">
        <input id="chatInput" type="text" placeholder="Pergunte sobre EPI, NR-06, CA..." />
        <button class="btn btn-primary" id="chatSend" title="Enviar mensagem">Enviar</button>
      </div>
    </div>

    <!-- ===== TOAST ===== -->
    <div class="toast" id="toast" role="status" aria-live="polite"></div>
  </div>

  <!-- ===== SENHA (bloqueia tudo) ===== -->
  <div class="backdrop" id="passBackdrop" role="dialog" aria-modal="true" aria-label="Acesso restrito">
    <div class="modal">
      <h3>🔒 Acesso restrito</h3>
      <p class="hint">Digite a senha para liberar o painel.</p>

      <div class="pass-row">
        <input id="passInput" type="password" placeholder="Senha..." autocomplete="off" />
        <button class="btn btn-ghost" id="passToggle" title="Mostrar/ocultar senha">👁</button>
      </div>

      <div style="height:10px"></div>
      <div class="row" style="justify-content:flex-end">
        <button class="btn btn-primary" id="passConfirm" title="Confirmar senha">Confirmar</button>
      </div>

      <div class="err" id="passErr">Senha incorreta. Tente novamente.</div>
      <div class="muted" style="margin-top:10px; font-weight:900;">
        Dica: você pode trocar a senha no JS em <code>SENHA_CORRETA</code>.
      </div>
    </div>
  </div>

  <script>
    /* =====================
       CONFIG / UTIL
    ====================== */
    const SENHA_CORRETA = "SG393";

    const SOUND = {
      click: "click.mp3",
      ok: "success.mp3"
    };

    function playSound(type){
      const src = type === "ok" ? SOUND.ok : SOUND.click;
      try{
        const a = new Audio(src);
        a.volume = 0.35;
        a.play().catch(()=>{});
      }catch(_){}
    }

    function toast(msg, kind="ok"){
      const t = document.getElementById("toast");
      t.textContent = msg;
      t.className = "toast show " + (kind || "");
      playSound(kind === "ok" ? "ok" : "click");
      setTimeout(()=> t.classList.remove("show"), 1700);
    }

    async function copyText(text){
      try{
        await navigator.clipboard.writeText(text);
        toast("Copiado!", "ok");
      }catch(e){
        const ta = document.createElement("textarea");
        ta.value = text;
        document.body.appendChild(ta);
        ta.select();
        document.execCommand("copy");
        ta.remove();
        toast("Copiado!", "ok");
      }
    }

    /* ✅ COPIAR UNIVERSAL (resolve TODOS os botões) */
    document.addEventListener("click", (e) => {
      const btn = e.target.closest("[data-copy]");
      if(!btn) return;
      const raw = btn.getAttribute("data-copy") || "";
      try{
        const text = decodeURIComponent(raw);
        copyText(text);
      }catch(_){
        copyText(raw);
      }
    });

    function setTheme(next){
      document.documentElement.setAttribute("data-theme", next);
      localStorage.setItem("theme", next);
    }

    function initTheme(){
      const saved = localStorage.getItem("theme");
      if(saved === "dark" || saved === "light"){
        setTheme(saved);
        return;
      }
      const prefersDark = window.matchMedia && window.matchMedia("(prefers-color-scheme: dark)").matches;
      setTheme(prefersDark ? "dark" : "light");
    }

    

    /* =====================
       PASSWORD GATE (real)
    ====================== */
    const app = document.getElementById("app");
    const passBackdrop = document.getElementById("passBackdrop");
    const passInput = document.getElementById("passInput");
    const passErr = document.getElementById("passErr");
    const passToggle = document.getElementById("passToggle");
    const passConfirm = document.getElementById("passConfirm");

    function showPass(){
      passBackdrop.classList.add("active");
      passInput.value = "";
      passErr.classList.remove("show");
      setTimeout(()=> passInput.focus(), 50);
    }
    function hidePass(){
      passBackdrop.classList.remove("active");
    }
    function unlock(){
      sessionStorage.setItem("acessoLiberado", "true");
      hidePass();
      app.hidden = false;
      toast("Acesso liberado.", "ok");
    }
    function confirmPass(){
      if(passInput.value === SENHA_CORRETA){
        unlock();
      }else{
        passErr.classList.add("show");
        passInput.value = "";
        passInput.focus();
        toast("Senha incorreta.", "err");
      }
    }

    passToggle.addEventListener("click", ()=>{
      const isPass = passInput.type === "password";
      passInput.type = isPass ? "text" : "password";
      passToggle.textContent = isPass ? "🙈" : "👁";
      playSound("click");
    });

    passConfirm.addEventListener("click", confirmPass);
    passInput.addEventListener("keydown", (e)=>{
      if(e.key === "Enter") confirmPass();
    });

    function boot(){
      initTheme();

      const allowed = sessionStorage.getItem("acessoLiberado") === "true";
      if(!allowed){
        app.hidden = true;
        showPass();
      }else{
        app.hidden = false;
      }
    }

    /* =====================
       NAV / SECTIONS
    ====================== */
    function showSection(id){
      document.querySelectorAll("main section").forEach(s => s.classList.remove("active"));
      const el = document.getElementById(id);
      if(el) el.classList.add("active");

      document.querySelectorAll(".tab").forEach(b=>{
        const active = b.dataset.tab === id;
        b.setAttribute("aria-selected", active ? "true" : "false");
      });
    }

    document.querySelectorAll(".tab").forEach(btn=>{
      btn.addEventListener("click", ()=>{
        showSection(btn.dataset.tab);
        playSound("click");
      });
    });

    // atalhos Alt+1..Alt+7
    document.addEventListener("keydown", (e)=>{
      if(!e.altKey) return;
      const map = {
        "1":"epis","2":"riscos","3":"empresas","4":"treinamento",
        "5":"riscos_empresas","6":"nrs","7":"painel_tecnico"
      };
      if(map[e.key]){
        showSection(map[e.key]);
        toast("Seção: " + map[e.key], "ok");
      }
    });

    /* =====================
       FLOATING PANEL
    ====================== */
    const fabPanel = document.getElementById("fabPanel");
    document.getElementById("fabMain").addEventListener("click", ()=>{
      fabPanel.classList.toggle("open");
      playSound("click");
    });
    document.getElementById("fabTop").addEventListener("click", ()=>{
      window.scrollTo({ top: 0, behavior: "smooth" });
      playSound("click");
    }); 
    document.getElementById("fabPdf").addEventListener("click", exportSectionPDF);

    document.getElementById("pdfBtn").addEventListener("click", exportSectionPDF);

    /* =====================
       DATA (EPIs / Riscos)
    ====================== */
    const epis = [
      { categoria: "🥾 Calçados", nome: "Botina de Elástico com Bico de PVC - Fujiwara", ca: "48.413", imagem: "https://d3bhvz7al37iy6.cloudfront.net/Custom/Content/Products/10/68/1068213_bota-seguranca-bracol-microfibra-composite-eletricista-38530_z2_638430758882818688.webp" },
      { categoria: "🥾 Calçados", nome: "Bota de Segurança ComBico de PVC ModeloLeve e Muito Conforto", ca: "45.258", imagem: "https://d3bhvz7al37iy6.cloudfront.net/Custom/Content/Products/10/68/1068213_bota-seguranca-bracol-microfibra-composite-eletricista-38530_z2_638430758882818688.webp" },
      { categoria: "🥾 Calçados", nome: "Sapato de Amarrar em Couro com Palmilha - Fujiwara (Branco/Preto)", ca: "41.858", imagem: "https://images.tcdn.com.br/img/img_prod/1033319/sapato_de_amarrar_fujiwara_linha_usafe_em_couro_com_palmilha_ca_41858_4098usas4600us_171_1_370dd8cc6d1594636c42615405c0579d.jpg" },
      { categoria: "🥾 Calçados", nome: "Sapato Antiderrapante Impermeável - Steelflex", ca: "38.590", imagem: "https://btequipamentos.agilecdn.com.br/111067_1_1.jpg?v=220-858371529" },
      { categoria: "🥾 Calçados", nome: "Bota de PVC Meio Cano (Branco/Preto) - Bracol", ca: "37.456", imagem: "https://lojaagrometal.fbitsstatic.net/img/p/bota-pvc-preto-cano-medio-39-com-forro-ca-36-025-innpro-73005/259515.jpg?w=1000&h=1000&v=no-change&qs=ignore" },
      { categoria: "🥾 Calçados", nome: "Bota de Seguranca em couro Nobuck com cadarço Dubai Eletrista bico PVC- Bracol", ca: "48.383", imagem: "https://http2.mlstatic.com/D_NQ_NP_761173-MLB89078178731_072025-O-bota-botina-de-seguranca-coturno-nobuck-marluvas-epi-com-ca.webp" },
      { categoria: "🥾 Calçados", nome: "Bota de Segurança Bicode Composite NR10Eletricista - Bracol", ca: "38.530", imagem: "https://imgs.search.brave.com/esoJvDJc19lu3PTbzs5h7fqKk5SlIa6SfFq74C2gxaw/rs:fit:500:0:1:0/g:ce/aHR0cHM6Ly9odHRw/Mi5tbHN0YXRpYy5j/b20vRF9RX05QXzJY/XzY0MDA1OS1NTEI4/MDQ0NDk1MTk1MV8x/MTIwMjQtRS1ib3Rh/LWJvdGluYS1zZWd1/cmFuY2EtYnJhY29s/LWVsZXRyaWNpc3Rh/LW5yMTAtYmljby1j/b21wb3NpdGUud2Vi/cA" },
      { categoria: "🧤 Luvas", nome: "Luva de Algodão Tricotada Mesclada - Volk", ca: "25.773", imagem: "https://i.imgur.com/xN1BFLa.png" },
      { categoria: "🧤 Luvas", nome: "Luva de Malha Neotato PU Preta - Volk", ca: "30.916", imagem: "https://i.imgur.com/c9CLP9E.png" },
      { categoria: "🧤 Luvas", nome: "Luva de Látex Multiuso para Uso Químico/Biológico (Amarela/Azul) - Danny", ca: "39.564", imagem: "https://i.imgur.com/hsiXIQa.png" },
      { categoria: "🧤 Luvas", nome: "Luva Pegasus PRO Coleta de Lixo e Serviços Gerais Bicolor - Volk", ca: "28.709", imagem: "https://i.imgur.com/BAbfvB6.png" },
      { categoria: "🧤 Luvas", nome: "Luva de Látex Neoprene - Volk", ca: "37.900", imagem: "https://i.imgur.com/y79Qsop.png" },
      { categoria: "🧤 Luvas", nome: "Luva Nitrílica Verde para Uso Químico/Biológico 35cm - Delta Plus", ca: "42.938", imagem: "https://i.imgur.com/qDHZ4XW.png" },
      { categoria: "🧤 Luvas", nome: "Luva PVC Forrada Cano Longo Palma Áspera - Danny", ca: "37.559", imagem: "https://i.imgur.com/6ML7rLO.png" },
      { categoria: "🧤 Luvas", nome: "Luva Malha de Aço - Danny", ca: "6.257", imagem: "https://i.imgur.com/nWzDsXA.png" },
      { categoria: "🧤 Luvas", nome: "Luva de Vaqueta Petroleira Crua - Protcap", ca: "15.061", imagem: "https://i.imgur.com/iX5fA0r.png" },
      { categoria: "🧤 Luvas", nome: "Luva Coral Resistência a Cortes e Furos até 350º - Danny", ca: "15.366", imagem: "https://i.imgur.com/be6AUx2.png" },
      { categoria: "🧤 Luvas", nome: "Luva de Segurança Confort Térmica Látex com Forro para Limpeza - Danny", ca: "15.532", imagem: "https://i.imgur.com/eSHbHzh.png" },
      { categoria: "🧤 Luvas", nome: "Luva de Látex Cano Longo Longatex - Danny", ca: "9.567", imagem: "https://i.imgur.com/bTvGvC9.png" },
      { categoria: "🧤 Luvas", nome: "Luva Resistente ao Corte Nível 5 Cut Smart - Volk", ca: "47.068", imagem: "https://i.imgur.com/ZlWIPQb.png" },
      { categoria: "🧤 Luvas", nome: "Luva Hand Nítrilo Lona - Handex", ca: "44.524", imagem: "https://i.imgur.com/fcOGOPT.png" },
      { categoria: "🧤 Luvas", nome: "Luva Hand Oil Cut - Handex", ca: "39.416", imagem: "https://i.imgur.com/50GGoXw.png" },
      { categoria: "🧤 Luvas", nome: "Luva De Raspa", ca: "10.074", imagem: "https://imgs.search.brave.com/7DZ1k3hMEXbJdMexzAI0qt_s1V3pFI5BXoPgs4MqbXE/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9pbWFn/ZXMudGNkbi5jb20u/YnIvaW1nL2ltZ19w/cm9kLzEyNjI0NzEv/bHV2YV9taXN0YV9k/ZV92YXF1ZXRhX3Jh/c3BhX2Nhbm9fbG9u/Z29fcF8yMF9jbXNf/Y19hXzQwMzE5XzI4/MTVfMV9lNzVmMzM2/ZWU5NjY4NjQ3ZDUz/YzY1N2VlNzhiNGZj/NC5qcGc" },
      { categoria: "🦾 Mangotes", nome: "Mangote Anti-Corte e Térmico 45cm - Delta Plus", ca: "41.361", imagem: "https://www.americanvek.com.br/cdn/shop/files/mangote-de-protecao-40cm-anticorte-nivel-5-com-fio-de-aco-seiki-ca39062-peca-1172807310_500x246.jpg?v=1749676771" },
      { categoria: "🦾 Mangotes", nome: "Mangote de Raspa Soldador com Elásticos 40cm - Zanel", ca: "16.073", imagem: "https://www.ferpam.com.br/media/mf_webp/jpg/media/catalog/product/cache/7f3660905effcfdd27a3ab16f16ab037/t/_/t_redu_o_13_-compressed.webp" },
      { categoria: "🦺 Aventais", nome: "Avental de Raspa 120x60cm sem Emendas - Zanel", ca: "13.989", imagem: "https://imgs.search.brave.com/0Zf1kLnKjFiMTVXbOqNhkYkugcJFzkH7wcKaLdcJIxg/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9kM2Jo/dno3YWwzN2l5Ni5j/bG91ZGZyb250Lm5l/dC9DdXN0b20vQ29u/dGVudC9Qcm9kdWN0/cy8xMC82Ni8xMDY2/OTUzX2F2ZW50YWwt/ZW0tcmFzcGEtMTIw/eDcwLWNtLXphbmVsLWF2LTEyMDcwc2Ut/c2VtLWVtZW5kYXMtY29tLXRpcmFzLWVtLXJhc3BhLWUtZml2/ZWxhcy1tZXRhbGljYXMtY2EtMTM5ODlf/bDFfNjM4MjEyMzc3/NTY1MjE0NzUyLndl/YnA" },
      { categoria: "🦺 Aventais", nome: "Avental de PVC Branco - Maicol", ca: "37.729", imagem: "https://imgs.search.brave.com/Tl0cjZhWvJU0qdYADZvGZzDa4lv8fAXe1oUrvqYtL-Y/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly93d3cuYXN0cm9kaXN0cmlidWlkb3JhLmNvbS9tZWRpYS90bXAvd2Vi/cC9jYXRhbG9nL3Byb2R1Y3QvY2FjaGUvMS9pbWFnZS82MDB4LzlkZjc4ZWFiMzM1MjVkMDhkNmU1ZmI4ZDI3MTM2ZTk1L2Evdi9hdmVudGFsX2RlX3B2Y19jb21fZm9ycm9fMV8xNV94XzBfNjVfY21fYnJhbmNvXzBfMzBfbW1fLV9tYWljb2xfY2FfLV8zNzcyOV80XzIud2Vi/cA" },
      { categoria: "🦺 Aventais", nome: "Avental De Proteção De PVC Cores Balask - Branco", ca: "6.429", imagem: "https://http2.mlstatic.com/D_NQ_NP_786060-MLU76630545889_052024-O.webp" },
      { categoria: "🦺 Aventais", nome: "Avental De Proteção De PVC Cores Balask - Preto", ca: "6.429", imagem: "https://http2.mlstatic.com/D_NQ_NP_729531-MLU72636555305_112023-O.webp" },
      { categoria: "🦺 Aventais", nome: "Avental de Vinil Transparente Tira Soldada", ca: "38.316", imagem: "https://d3bhvz7al37iy6.cloudfront.net/Custom/Content/Products/10/51/1051169_avental-de-vinil-transparente-tira-soldada-ca-37475_z1_638821262518773542.webp" },
      { categoria: "😷 Máscaras", nome: "Máscara PFF1 com ProSafety - Delta Plus", ca: "38.501", imagem: "https://imgs.search.brave.com/DxGkuYzi-TIuHYfvbCkTB8x9QKqlQhpQQ-y0PQ0o2kk/rs:fit:500:0:1:0/g:ce/aHR0cHM6Ly9kM2Jo/dno3YWwzN2l5Ni5j/bG91ZGZyb250Lm5l/dC9DdXN0b20vQ29u/dGVudC9Qcm9kdWN0/cy8xMC80OC8xMDQ4OTA2X21hc2NhcmEtcGZmMS1jb20tdmFsdnVsYS1wcm8tYWdyby1kZWx0YS1wbHVzLWNhaXhhLWNvbS0xMDBfbTlfNjM3MzU5NjY3MzQyNzE0NjUzLndlYnA" },
      { categoria: "😷 Máscaras", nome: "Máscara N95 PF2 - Nutriex Safety", ca: "46.868", imagem: "https://imgs.search.brave.com/rVZe6d37VK0knK_LSb7UFBTtuzXH6Qqo2R5MgyT5oaw/rs:fit:500:0:1:0/g:ce/aHR0cHM6Ly9odHRwMi5tbHN0YXRpYy5j/b20vRF9OUV9OUF84NDk5NDctTUxCNTI0NzgxMjI3OTNfMTEyMDIyLVYud2VicA" },
      { categoria: "😷 Máscaras", nome: "Máscara PFF2 - Delta Plus", ca: "38.503", imagem: "https://imgs.search.brave.com/ArpzaLtlElyrzt2dTe03WbqKAxJPbC_SIKyTP1WDyE0/rs:fit:500:0:1:0/g:ce/aHR0cHM6Ly9jZG4ubGVyb3ltZXJsaW4uY29tLmJyL3Byb2R1Y3RzL21hc2NhcmFfZGVzY2FydGF2ZWxfcGZmMl9zX19jX192YWx2dWxhX19kZWx0YV9wbHVzXzkwNTk5NTIzX2IwZjVfNjAweDYwMC5qcGc" },
      { categoria: "📌 Epis", nome: "Creme Protetor Luva Quimica 3em1 - Nutriex", ca: "43.802", imagem: "https://www.astrodistribuidora.com/media/tmp/webp/catalog/product/cache/1/image/600x/9df78eab33525d08d6e5fb8d27136e95/s/a/sabonete_desengraxante_esfoliante_limpa_m_os_biodegrad_vel_fast_orange_bombona_4l_-_luvex_img_1_1__png.webp" },
      { categoria: "📌 Epis", nome: "Cinturao de Segurança Steelflex com 1 ponto CQCT1111 + Talabarte Duplo em Y Com Fita Tubular", ca: "45.069", imagem:"https://d3bhvz7al37iy6.cloudfront.net/Custom/Content/Products/10/53/1053591_cinturao-de-seguranca-steelflex-com-1-ponto-cqct1111-talabarte-duplo-em-y-com-fita-tubular-_m3_637826022890604517.webp" },
      { categoria: "📌 Epis", nome: "Macacão de Seguranca Branco - SteelFlex", ca: "39.707", imagem: "https://d3bhvz7al37iy6.cloudfront.net/Custom/Content/Products/10/48/1048195_macacao-de-seguranca-steelflex-branco-ca-39707_m3_637358851517696820.webp" },
      { categoria: "📌 Epis", nome: "Luva Vinil Sem Pó Descartavel c/100 - Descarpack", ca: "44.050", imagem: "https://loja.descarpack.com.br/media/catalog/product/l/u/luva-vinil-procedimento-nao-cirurgico-sem-po-p-descarpack-0541101-1-para-que-indicado_2.jpg?auto=webp&format=pjpg&width=1600&height=2000&fit=cover" },
      { categoria: "📌 Epis", nome: "Mascara De Solda", ca: "14.199", imagem:"https://imgs.search.brave.com/6o8YB6x03WKJrBtO2_BuSUmWMVKMKN9z0SuQb3nWjkQ/rs:fit:500:0:1:0/g:ce/aHR0cHM6Ly9hYnJhZmVyLmFnaWxlY2RuLmNvbS5ici8xMDY1N190aHVtYl8xLmpwZz92PTI5NS0yMDE4OTAwNzM5" },
      { categoria: "🧥 Vestuário Térmico", nome: "Japona Térmica Frigorífica Azul Marinho - Maicol", ca: "10.975", imagem: "https://safetytrab.com.br/wp-content/uploads/2018/04/Japona-Termica-Camara-Fria-Baixa-Temperatura-Maicol-CA-10975.jpg.webp" },
      { categoria: "🧥 Vestuário Térmico", nome: "Calça De Nylon Térmica Impermeável Para Câmara Fria - Maicol", ca: "10.976", imagem: "https://http2.mlstatic.com/D_NQ_NP_2X_948835-MLB78618348261_082024-F.webp" },
      { categoria: "🧥 Vestuário Térmico", nome: "Capuz Balaclava Térmico para Câmara Fria Suedine - Maicol", ca: "10.979", imagem: "https://images.tcdn.com.br/img/img_prod/626581/capuz_balaclava_suedine_maicol_1063_variacao_6239_1_af993d65a8dc368e7488518fa0726ba8.png" },
      { categoria: "🧥 Vestuário Térmico", nome: "Meião Térmico - Maicol", ca: "10.977", imagem: "https://safetytrab.com.br/wp-content/uploads/2018/04/Mei%C3%A3o-T%C3%A9rmico-para-C%C3%A2mara-Fria-Maicol.jpg.webp" },
      { categoria: "🧥 Vestuário Térmico", nome: "Luva Térmica Frigorífica em Nylon Baixa Temperatura -35º - Maicol", ca: "10.978", imagem: "https://safetytrab.com.br/wp-content/uploads/2018/04/Luva-de-Seguran%C3%A7a-T%C3%A9rmica-em-Nylon-Maicol-CA-10.978.jpg.webp" },
      { categoria: "🧥 Vestuário Térmico", nome: "Bota Térmica", ca: "42.632", imagem: "https://imgs.search.brave.com/7OIbzTUng5IX3dKP7w3I89Qba4cqHmwbnv9T__waCxU/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9kMXFsMGEzZTNqOW1jeC5j/bG91ZGZyb250Lm5l/dC9DdXN0b20vQ29u/dGVudC9Qcm9kdWN0/cy84Ni84MS84NjgxX2JvdGEtZnJpZ29yaWZpY2EtYnJhbmNhLWN1cnRhLWJyYWNvbC00MDEwYmRnbTQ2MDBfczNfNjM4Nzk5ODgxNDYwMDYzNjcwLndlYnA" },
      { categoria: "👷‍ Vestuário", nome: "Camisa Com Refletivo Para Eletricista Cinza - Maicol", ca: "44.108", imagem: "https://d1ql0a3e3j9mcx.cloudfront.net/Custom/Content/Products/57/86/5786_camisa-eletricista-nr10-cinza-com-refletivo-maicol_l1_637934046958088869.webp" },
      { categoria: "👷‍ Vestuário", nome: "Calça Classe 2 Cinza Com Refletivo - Maicol", ca: "44.109", imagem: "https://d1ql0a3e3j9mcx.cloudfront.net/Custom/Content/Products/58/38/5838_calca-eletricista-nr10-com-refletivo-maicol_z1_637934927655407307.webp" },
      { categoria: "👷‍ Vestuário", nome: "Blusão PVC Forrado Com Capuz", ca: "29.790", imagem: "https://www.ledan.com.br/slideWF/images/calca-e-blusao-pvc-forrado/calca-e-blusao-pvc-forrado1.jpg" },
      { categoria: "👷‍ Vestuário", nome: "Calça De Chuva Em PVC Forrada Amarela", ca: "37.536", imagem: "https://d3bhvz7al37iy6.cloudfront.net/Custom/Content/Products/10/46/1046987_calca-de-chuva-em-pvc-forrada-amarela-ca-28191-_z4_637669591007837495.webp" },
      { categoria: "🦺 Colete", nome: "Colete Tipo X Laranja Steelflex", ca: "38.175", imagem: "https://www.steelflex.pro/wp-content/uploads/2021/08/COLETE-REFLETIVO-X1.png" },
      { categoria: "🦺 Colete", nome: "Colete SteelFlex Refletivo Laranja Fluorescente", ca: "42.716", imagem: "https://www.steelflex.pro/wp-content/uploads/2021/08/colete-refletivo-4-bolsos-laranja.png" },
      { categoria: "🛡 Proteção Facial", nome: "Protetor Facial Jabre Carneira Hipoalergênica com Regulagem por Catraca Tamanho 8 - Delta Plus", ca: "47.620", imagem: "https://images.tcdn.com.br/img/img_prod/1033319/protetor_facial_jabre_8_delta_plus_ca_47620_1699_1_04f95abaf05adc053f1561dba26a2d78.jpg" },
      { categoria: "🛡 Proteção Facial", nome: "Protetor Facial com Carneira Hipoalergênica com regulagem e fácil ajuste - Delta Plus", ca: "10.975", imagem: "https://d3bhvz7al37iy6.cloudfront.net/Custom/Content/Products/10/67/1067058_protetor-facial-jabre-delta-plus-carneira-hipoalergenica-com-regulagem-ajuste-facil-tamanho-8-ca-47620_z1_638227684320944177.webp" },
      { categoria: "🛡 Proteção Facial", nome: "Protetor Facial Telado Dystray - Ideal Para Roçadeira", ca: "36.802", imagem: "https://elastobor.vtexassets.com/arquivos/ids/213582/PROTETOR-F%EF%BF%BDCIL-DYSTRAY-TELADO-COM-CATRACA.jpg?v=637557443744600000" },
      { categoria: "👓 Óculos", nome: "Óculos de Segurança Ampla Visão - Galeras Clear", ca: "35.268", imagem: "https://hiperfer.cdn.magazord.com.br/img/2023/07/produto/13687/14734-1-oculos-de-seguranca-com-ampla-visao-galeras-clear-deltaplus.jpg?ims=500x500" },
      { categoria: "👓 Óculos", nome: "Óculos Proteção Sobrepor Antirrisco Hekla Incolor - Delta Plus", ca: "38.253", imagem: "https://ccp.vteximg.com.br/arquivos/ids/240080-535-535/oculos-de-proteco-delta-plus-hekla-clear-ca-38253-D_NQ_NP_873213-MLB26641061700_012018-F.jpg?v=636843803319300000" },
      { categoria: "👓 Óculos", nome: "Óculos de Segurança tipo RJ Vvision 100 incolor - Volk", ca: "42.716", imagem: "https://volkdobrasil.com.br/wp-content/uploads/2024/08/oculos-vvision100-incolor-600x600.jpg" },
      { categoria: "🎧 Proteção Auditiva", nome: "Abafador de Ruído Combat 10DB - Maicol", ca: "10.977", imagem: "https://images.tcdn.com.br/img/img_prod/860085/abafador_concha_combat_10db_prosafety_ca_19405_175_1_20201214023621.jpg" },
      { categoria: "🎧 Proteção Auditiva", nome: "Abafador de Ruído SoftSlim 18DB - Camper", ca: "33.135", imagem: "https://images.tcdn.com.br/img/img_prod/652260/abafador_de_ruido_18_db_soft_slim_cod_800200_camper_5653_1_829cc44eecca796fb5e0ca7592040551_20230823104822.jpg" },
      { categoria: "🎧 Proteção Auditiva", nome: "Abafador de Ruído ConfortPlus 26DB - Camper", ca: "48.054", imagem: "https://images.tcdn.com.br/img/img_prod/652260/abafador_de_ruidos_26_db_confort_plus_camper_4258_1_29963934d741bf4bf802579cf35404ff_20230823104818.jpg" },
      { categoria: "🎧 Proteção Auditiva", nome: "Abafador de Ruído Combat 10DB - Delta Plus", ca: "19.405", imagem: "https://cdn.leroymerlin.com.br/products/abafador_de_ruido_combat_delta_plus_90599383_893d_600x600.jpeg" },
      { categoria: "🎧 Proteção Auditiva", nome: "Abafador Concha Interlagos 23DB - Delta Plus", ca: "35.003", imagem: "https://d3bhvz7al37iy6.cloudfront.net/Custom/Content/Products/10/51/1051099_abafador-concha-interlagos-cz-delta-plus-intergr-ca-35003_z27_638303840084340681.webp" }
    ];

    const riscosModelos = [
      { tipo:"fisico", titulo:"📘 FÍSICO - Parte 1", texto:"De acordo com a inspeção realizada no ambiente de trabalho e atividades executadas pelo trabalhador, e de acordo com a NR 15 da portaria 3.214/78 do M.T.E, o mesmo está exposto a agentes ambientais nocivos à saúde ao risco Físico." },
      { tipo:"fisico", titulo:"📘 FÍSICO - Parte 2", texto:"As atividades de trabalho realizadas neste LTCAT não são consideradas de Condições Especiais de Trabalho e, portanto, não são prejudiciais à saúde ou integridade física dos trabalhadores segundo os requisitos do Decreto Federal 3048/1999 e seu Anexo IV." },
      { tipo:"biologico", titulo:"🧬 BIOLÓGICO - Parte 1", texto:"De acordo com a inspeção realizada no ambiente de trabalho e atividades executadas pelo trabalhador, e de acordo com a NR 15 da portaria 3.214/78 do M.T.E, o mesmo está exposto a agentes ambientais nocivos à saúde ao risco Biológico." },
      { tipo:"biologico", titulo:"🧬 BIOLÓGICO - Parte 2", texto:"As atividades de trabalho realizadas neste LTCAT não são consideradas de Condições Especiais de Trabalho e, portanto, não são prejudiciais à saúde ou integridade física dos trabalhadores segundo os requisitos do Decreto Federal 3048 / 1999 e seu Anexo IV." },
      { tipo:"biologico", titulo:"🧬 BIOLÓGICO - Parte 3", texto:"As atividades de trabalho realizadas neste LTCAT são consideradas de Condições Especiais de Trabalho e, portanto, são prejudiciais à saúde ou integridade física dos trabalhadores segundo os requisitos do Decreto Federal 3048 / 1999 e seu Anexo IV." },
      { tipo:"quimico", titulo:"🧪 QUÍMICO - Parte 1", texto:"De acordo com a inspeção realizada no ambiente de trabalho e atividades executadas pelo trabalhador, e de acordo com a NR 15 da portaria 3.214/78 do M.T.E, o mesmo está exposto a agentes ambientais nocivos à saúde ao risco Químico." },
      { tipo:"quimico", titulo:"🧪 QUÍMICO - Parte 2", texto:"As atividades de trabalho realizadas neste LTCAT não são consideradas de Condições Especiais de Trabalho e, portanto, não são prejudiciais à saúde ou integridade física dos trabalhadores segundo os requisitos do Decreto Federal 3048 / 1999 e seu Anexo IV." },
      { tipo:"quimico", titulo:"🧪 QUÍMICO - Parte 3", texto:"As atividades de trabalho realizadas neste LTCAT são consideradas de Condições Especiais de Trabalho e, portanto, são prejudiciais à saúde ou integridade física dos trabalhadores segundo os requisitos do Decreto Federal 3048 / 1999 e seu Anexo IV." },
    ];

    const riscosEmpresas = [
      { emoji:"🔊", risco:"RUÍDO", empresa:"FAP INDÚSTRIA E COMÉRCIO DE ACRÍLICOS LTDA", setor:"Dobra" },
      { emoji:"🌫", risco:"POEIRA", empresa:"FAP INDÚSTRIA E COMÉRCIO DE ACRÍLICOS LTDA", setor:"Polimento" },
      { emoji:"🛠", risco:"FERRAMENTAS MANUAIS/MÁQUINAS E EQUIPAMENTOS", empresa:"FAP INDÚSTRIA E COMÉRCIO DE ACRÍLICOS LTDA", setor:"Produção" },
      { emoji:"🧼", risco:"PRODUTOS DOMISSANITÁRIOS DE LIMPEZA", empresa:"FAP INDÚSTRIA E COMÉRCIO DE ACRÍLICOS LTDA", setor:"Limpeza" },
      { emoji:"👷‍♂️", risco:"TRABALHO EM ALTURA", empresa:"JF CONSTRUCAO E PAVIMENTAÇÃO LTDA", setor:"Obra" },
      { emoji:"🧺", risco:"TINTAS/DILUENTES", empresa:"PREST-MAC COMERCIAL E INDUSTRIAL LTDA", setor:"Pintura" },
      { emoji:"⚡", risco:"TRABALHO COM ELETRICIDADE", empresa:"WGL SOLUÇÕES EM TECNOLOGIAS E SERVIÇOS LTDA", setor:"Manutenção/Elétrica (Preventiva/Corretiva)" },
      { emoji:"🧴", risco:"LUBRIFICANTES", empresa:"PREST-MAC COMERCIAL E INDUSTRIAL LTDA", setor:"Produção" },
      { emoji:"✨", risco:"PRODUTOS QUÍMICOS DE ESTÉTICA", empresa:"ELENICE GERALDO DOS SANTOS CABELEIREIROS LTDA", setor:"Salão" },
      { emoji:"🍔", risco:"MANIPULAÇÃO DE ALIMENTOS", empresa:"PÃES E DOCES CHALÉ DOCILE LTDA", setor:"Cozinha" },
      { emoji:"🚗", risco:"CONDUÇÃO DE VEÍCULOS AUTOMOTORES", empresa:"POLICOMP COMERCIO DE COMPONENTES", setor:"Estoque/Transporte" },
      { emoji:"🔩", risco:"FUMOS METÁLICOS DE ESTANHO", empresa:"POLICOMP COMERCIO DE COMPONENTES", setor:"Técnico" },
      { emoji:"💥", risco:"RADIAÇÃO NÃO IONIZANTE", empresa:"SPADA MIDIA E EVENTOS LTDA", setor:"Obra/Serralheria" },
      { emoji:"😸🐶", risco:"PRODUTOS QUÍMICOS DE BELEZA PARA CÃES E GATOS", empresa:"CAROL PET SHOP COMERCIO DE RACOES ACESSORIOS BANHO E TOSA LTDA", setor:"Banho e Tosa" },
      { emoji:"📦", risco:"TRABALHOS DE SEPARAÇÃO DE EMBALAGENS", empresa:"MONTE VIRGINNE COMÉRCIO DE SUCATAS DE PLÁSTICOS LTDA ME", setor:"Produção/Separação" },
      { emoji:"❄", risco:"FRIO", empresa:"LANCHONETE E ESFIHARIA NOVA ALIANCA LTDA", setor:"Cozinha" },
      { emoji:"🧴", risco:"ÓLEO SINTÉTICO", empresa:"DELTA ROTULADORAS EIRELI", setor:"Fábrica" },
      { emoji:"🗜", risco:"ESTANHO", empresa:"RAUL SANTOS FERREIRA", setor:"Produção" },
      { emoji:"🩹", risco:"ACIDENTES", empresa:"RIO BONITO COMERCIO E SERVICOS PARA PISCINAS LTDA", setor:"Assistencia" },
      { emoji:"⚕️", risco:"VIRUS E BACTÉRIAS", empresa:"RIO BONITO COMERCIO E SERVICOS PARA PISCINAS LTDA", setor:"Externo" },
      { emoji:"💦", risco:"CLORO", empresa:"RIO BONITO COMERCIO E SERVICOS PARA PISCINAS LTDA", setor:"Externo" },
    ];

    const w2h = [
      { k:"What (O Quê)", v:"Treinamento de NR-06" },
      { k:"Who (Quem)", v:"Coordenador da empresa" },
      { k:"When (Quando)", v:"Permanente" },
      { k:"Where (Onde)", v:"Ambiente laboral" },
      { k:"Why (Porquê)", v:"Conscientizar os colaboradores sobre o uso de EPI." },
      { k:"How (Como)", v:"Palestra NR-06, treinamento de EPI." },
      { k:"How much (Custo)", v:"***" }
    ];

    const nrs = [
      { t:"NR-06 — Equipamentos de Proteção Individual (EPI)", d:"Regulamenta fornecimento, uso e conservação dos EPIs, incluindo CA." },
      { t:"NR-07 — PCMSO / Saúde Ocupacional", d:"Diretrizes para controle médico de saúde ocupacional e exames." },
      { t:"NR-10 — Eletricidade", d:"Requisitos mínimos para segurança em instalações e serviços elétricos." },
      { t:"NR-12 — Máquinas e Equipamentos", d:"Medidas de prevenção de acidentes com máquinas e proteções." },
      { t:"NR-18 — Construção", d:"Condições de segurança e bem-estar no canteiro de obras." },
      { t:"NR-23 — Incêndio / Brigada", d:"Prevenção e combate a princípios de incêndio e evacuação." },
      { t:"NR-33 — Espaço Confinado", d:"Reconhecer, avaliar e controlar riscos em espaço confinado." },
      { t:"NR-35 — Trabalho em Altura", d:"Requisitos para trabalhos acima de 2 metros, com planejamento e AR." }
    ];

    const faq = [
      { q:"Quando é necessário renovar os EPIs?", a:"Sempre que o CA vencer, houver desgaste ou prazo do fabricante expirar." },
      { q:"Qual a validade do ASO?", a:"Admissional: antes da função; Periódico: anual/bienal; Retorno: após afastamento ≥ 30 dias; Mudança de função: se alterar riscos; Demissional: até a rescisão." },
      { q:"Quem deve elaborar o PCMSO?", a:"Somente Médico do Trabalho registrado no CRM." },
      { q:"O que é o PGR e quem deve elaborá-lo?", a:"Programa de Gerenciamento de Riscos elaborado por Engenheiro ou Técnico de Segurança do Trabalho." },
      { q:"Qual a periodicidade do treinamento NR-06 (EPI)?", a:"Na admissão, mudança de função, introdução de novos riscos e periodicamente (mínimo 1 vez ao ano)." },
      { q:"O que deve constar na ficha de EPI?", a:"Nome, CA, data de entrega, prazo de troca, assinaturas e instruções de uso." }
    ];

    /* =====================
       RENDER: EPIs
    ====================== */
    const catalog = document.getElementById("catalog");
    const categoryFilter = document.getElementById("categoryFilter");
    const searchInput = document.getElementById("searchInput");
    const epiCount = document.getElementById("epiCount");

    function renderEpis(list){
      catalog.innerHTML = list.map((e, i)=>`
        <div class="card epi" role="article" aria-label="EPI ${i+1}">
          <div class="epi-img">
            <img src="${e.imagem}" alt="${e.nome}" loading="lazy">
          </div>
          <div class="muted" style="font-weight:950;">${e.categoria}</div>
          <h3>${e.nome}</h3>
          <div class="row" style="justify-content:space-between; gap:8px;">
            <span class="badge" title="Certificado de Aprovação">CA Nº: ${e.ca}</span>
            <button class="btn btn-ghost" title="Copiar CA" data-copy="${encodeURIComponent(e.ca)}">📋 Copiar</button>
          </div>
        </div>
      `).join("");

      epiCount.textContent = `${list.length} item(ns) exibido(s)`;
    }

    function populateCategories(){
      const cats = [...new Set(epis.map(x=>x.categoria))].sort((a,b)=>a.localeCompare(b));
      cats.forEach(c=>{
        const op = document.createElement("option");
        op.value = c;
        op.textContent = c;
        categoryFilter.appendChild(op);
      });
    }

    function filterEpis(){
      const q = searchInput.value.toLowerCase().trim();
      const cat = categoryFilter.value;
      const filtered = epis.filter(e=>{
        const okQ =
          e.nome.toLowerCase().includes(q) ||
          e.ca.toLowerCase().includes(q) ||
          e.categoria.toLowerCase().includes(q);
        const okC = !cat || e.categoria === cat;
        return okQ && okC;
      });
      renderEpis(filtered);
    }

    document.getElementById("clearEpiBtn").addEventListener("click", ()=>{
      searchInput.value = "";
      categoryFilter.value = "";
      filterEpis();
      toast("Filtros limpos!", "ok");
    });

    searchInput.addEventListener("input", filterEpis);
    categoryFilter.addEventListener("change", filterEpis);

    /* =====================
       RENDER: Riscos
    ====================== */
    const riskCards = document.getElementById("riskCards");
    function renderRiskCards(list){
      riskCards.innerHTML = list.map(r=>`
        <div class="card" data-risk="${r.tipo}">
          <div style="font-weight:950; margin-bottom:8px;">${r.titulo}</div>
          <div class="muted" style="font-weight:850; line-height:1.4;">${r.texto}</div>
          <div style="height:10px"></div>
          <button class="btn btn-primary" title="Copiar texto" data-copy="${encodeURIComponent(r.texto)}">Copiar</button>
        </div>
      `).join("");
    }
    document.getElementById("riskFilter").addEventListener("change", (e)=>{
      const v = e.target.value;
      const list = v === "todos" ? riscosModelos : riscosModelos.filter(x=>x.tipo===v);
      renderRiskCards(list);
      playSound("click");
    });

    /* =====================
       RENDER: 5W2H
    ====================== */
    const w2hGrid = document.getElementById("w2hGrid");
    function renderW2H(){
      w2hGrid.innerHTML = w2h.map(x=>`
        <div class="card">
          <div style="font-weight:950;">${x.k}</div>
          <div class="muted" style="margin-top:6px; font-weight:850;">${x.v}</div>
          <div style="height:10px"></div>
          <button class="btn btn-primary" title="Copiar" data-copy="${encodeURIComponent(x.v)}">Copiar</button>
        </div>
      `).join("");
    }

    /* =====================
       RENDER: Riscos por Empresa
    ====================== */
    const listaRiscosEmpresas = document.getElementById("listaRiscosEmpresas");
    function renderRiscosEmpresas(list){
      listaRiscosEmpresas.innerHTML = list.map(i=>`
        <div class="card">
          <div style="font-weight:950;">${i.emoji} ${i.risco}</div>
          <div class="muted" style="margin-top:6px; font-weight:850;">${i.empresa} • Setor: ${i.setor}</div>
          <div style="height:10px"></div>
          <button class="btn btn-ghost" title="Copiar empresa" data-copy="${encodeURIComponent(i.empresa)}">📋 Copiar empresa</button>
        </div>
      `).join("");
    }
    document.getElementById("buscaRiscos").addEventListener("input", (e)=>{
      const t = e.target.value.toLowerCase();
      const f = riscosEmpresas.filter(i => (i.risco+" "+i.empresa+" "+i.setor).toLowerCase().includes(t));
      renderRiscosEmpresas(f);
    });

    /* =====================
       RENDER: NRs
    ====================== */
    const nrGrid = document.getElementById("nrGrid");
    function renderNRs(){
      nrGrid.innerHTML = nrs.map(n=>`
        <div class="card">
          <div style="font-weight:950;">
            <span class="nr-title">${n.t}</span>
          </div>
          <div class="muted" style="margin-top:6px; font-weight:850; line-height:1.4;">${n.d}</div>
          <div style="height:10px"></div>
          <button class="btn btn-primary" title="Copiar título" data-copy="${encodeURIComponent(n.t)}">Copiar</button>
        </div>
      `).join("");
    }

    /* =====================
       FAQ
    ====================== */
    const faqEl = document.getElementById("faq");
    function renderFAQ(){
      faqEl.innerHTML = faq.map((x, idx)=>`
        <div class="acc-item">
          <button class="acc-btn" title="Abrir/fechar" aria-expanded="false" data-acc="${idx}">
            ${x.q}
            <span>▾</span>
          </button>
          <div class="acc-body">${x.a}</div>
        </div>
      `).join("");
    }
    document.addEventListener("click", (e)=>{
      const b = e.target.closest(".acc-btn");
      if(!b) return;
      const item = b.closest(".acc-item");
      item.classList.toggle("active");
      const expanded = item.classList.contains("active");
      b.setAttribute("aria-expanded", expanded ? "true" : "false");
      playSound("click");
    });

    /* =====================
       Frases Empresa
    ====================== */
    const resultado = document.getElementById("resultado");
    function gerarFrases(){
      const nomes = document.getElementById("nomes").value
        .split("\n").map(s=>s.trim()).filter(Boolean);
      const empresa = document.getElementById("empresa").value.trim();
      const data = document.getElementById("data").value.trim();

      const out = nomes.map(nome => `${nome}, ${empresa}, , , ${data}`).join("\n");
      resultado.textContent = out || "—";
      toast("Frases geradas.", "ok");
    }

    document.getElementById("genPhrasesBtn").addEventListener("click", gerarFrases);
    document.getElementById("copyPhrasesBtn").addEventListener("click", ()=>{
      copyText(resultado.textContent || "");
    });

    document.getElementById("exportTxtBtn").addEventListener("click", ()=>{
      const content = resultado.textContent || "";
      const blob = new Blob([content], { type: "text/plain;charset=utf-8" });
      const url = URL.createObjectURL(blob);
      const a = document.createElement("a");
      a.href = url;
      a.download = "frases_empresa.txt";
      document.body.appendChild(a);
      a.click();
      a.remove();
      URL.revokeObjectURL(url);
      toast("TXT exportado.", "ok");
    });

    /* =====================
       PDF (seção atual)
    ====================== */
    function getActiveSection(){
      return document.querySelector("main section.active");
    }

    async function exportSectionPDF(){
      const sec = getActiveSection();
      if(!sec){
        toast("Nenhuma seção ativa.", "err");
        return;
      }

      const title = sec.querySelector("h2") ? sec.querySelector("h2").textContent.trim() : "SST";
      const text = sec.innerText.trim();

      const { jsPDF } = window.jspdf || {};
      if(!jsPDF){
        toast("jsPDF não carregou.", "err");
        return;
      }

      const doc = new jsPDF({ unit:"pt", format:"a4" });
      const margin = 36;
      const maxW = 595 - margin*2;

      doc.setFont("helvetica", "bold");
      doc.setFontSize(14);
      doc.text(title, margin, 48);

      doc.setFont("helvetica", "normal");
      doc.setFontSize(10);

      const lines = doc.splitTextToSize(text, maxW);
      let y = 70;

      for(const line of lines){
        if(y > 800){
          doc.addPage();
          y = 48;
        }
        doc.text(line, margin, y);
        y += 14;
      }

      doc.save((title || "sst").replace(/\s+/g,"_").toLowerCase() + ".pdf");
      toast("PDF salvo.", "ok");
    }

    /* =====================
       CHAT (local simples)
    ====================== */
    const chatFab = document.getElementById("chatFab");
    const chatBox = document.getElementById("chatBox");
    const chatClose = document.getElementById("chatClose");
    const chatMsgs = document.getElementById("chatMsgs");
    const chatInput = document.getElementById("chatInput");
    const chatSend = document.getElementById("chatSend");

    function chatAdd(text, who="bot"){
      const wrap = document.createElement("div");
      wrap.className = who === "me" ? "me" : "bot";
      wrap.innerHTML = `<div class="bubble">${text}</div>`;
      chatMsgs.appendChild(wrap);
      chatMsgs.scrollTop = chatMsgs.scrollHeight;
    }

    function answerLocal(q){
      const m = q.toLowerCase();
      if(m.includes("nr-06") || m.includes("epi")){
        return "NR-06 trata do EPI: fornecimento, treinamento, uso correto e CA. Quer que eu gere um texto padrão para laudo/OS?";
      }
      if(m.includes("aso")){
        return "ASO: admissional antes da função; periódico conforme risco; retorno após afastamento ≥ 30 dias; mudança de função quando altera risco; demissional até rescisão.";
      }
      if(m.includes("pgr")){
        return "PGR é o Programa de Gerenciamento de Riscos. Em geral é elaborado por Engenheiro ou Técnico de Segurança do Trabalho.";
      }
      if(m.includes("ca")){
        return "CA (Certificado de Aprovação) é o registro do EPI aprovado. Se vencer, substitui e registra nova entrega.";
      }
      return "Me diga o tema (EPI, CA, ASO, NR, PGR, PCMSO) que eu te respondo com um texto pronto.";
    }

    function sendChat(){
      const q = chatInput.value.trim();
      if(!q) return;
      chatAdd(q, "me");
      chatInput.value = "";
      setTimeout(()=> chatAdd(answerLocal(q), "bot"), 220);
    }

    chatFab.addEventListener("click", ()=>{
      chatBox.classList.toggle("active");
      chatBox.setAttribute("aria-hidden", chatBox.classList.contains("active") ? "false" : "true");
      playSound("click");
      if(chatBox.classList.contains("active")) setTimeout(()=> chatInput.focus(), 50);
    });
    chatClose.addEventListener("click", ()=>{
      chatBox.classList.remove("active");
      chatBox.setAttribute("aria-hidden", "true");
      playSound("click");
    });
    chatSend.addEventListener("click", sendChat);
    chatInput.addEventListener("keydown", (e)=>{
      if(e.key === "Enter"){
        e.preventDefault();
        sendChat();
      }
    });

    /* =====================
       INIT
    ====================== */
    window.addEventListener("DOMContentLoaded", ()=>{
      boot();

      populateCategories();
      renderEpis(epis);
      renderRiskCards(riscosModelos);
      renderW2H();
      renderRiscosEmpresas(riscosEmpresas);
      renderNRs();
      renderFAQ();

      document.getElementById("statusPill").textContent = "✅ Online";
    });
  </script>
</body>
</html>
