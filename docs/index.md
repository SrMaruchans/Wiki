<p style="text-align:center; margin:0 0 1rem 0;"><img src="assets/logo-wolfland.png" alt="Wolfland Network" width="480" style="display:inline-block; max-width:100%; height:auto;"></p>

# Bienvenido

Esta es la wiki oficial de **Wolfland Network**, un servidor de Minecraft **Survival Custom** para **Java y Bedrock**. Aquí encontrarás todo lo necesario para unirte, conocer las normas, descubrir los comandos y rangos, y mantenerte al día con las novedades de la comunidad.

<div class="wf-ip-card">
  <div class="wf-ip-header">
    <span class="wf-ip-dot"></span>
    <span>IP del servidor</span>
    <span class="wf-ip-badge">Java &amp; Bedrock</span>
  </div>
  <div class="wf-ip-body">
    <div class="wf-ip-row">
      <div class="wf-ip-info">
        <span class="wf-edition wf-edition-java">Java</span>
        <code class="wf-ip-code">play.wolfland.pro</code>
      </div>
      <button type="button" class="wf-copy-btn" onclick="copyServerIp(this, 'play.wolfland.pro')">
        <svg viewBox="0 0 24 24" width="15" height="15" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="9" y="9" width="13" height="13" rx="2" ry="2"></rect><path d="M5 15H4a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v1"></path></svg>
        <span class="wf-copy-text">Copiar IP</span>
      </button>
    </div>
    <div class="wf-ip-row">
      <div class="wf-ip-info">
        <span class="wf-edition wf-edition-bedrock">Bedrock</span>
        <code class="wf-ip-code">play.wolfland.pro</code>
        <span class="wf-port-wrap">Puerto: <code class="wf-ip-code">19132</code></span>
      </div>
      <button type="button" class="wf-copy-btn" onclick="copyServerIp(this, 'play.wolfland.pro:19132')">
        <svg viewBox="0 0 24 24" width="15" height="15" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="9" y="9" width="13" height="13" rx="2" ry="2"></rect><path d="M5 15H4a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v1"></path></svg>
        <span class="wf-copy-text">Copiar IP + Puerto</span>
      </button>
    </div>
  </div>
</div>

<style>
.md-typeset .wf-ip-card { --wf-bg: linear-gradient(145deg,rgba(255,83,0,.07),rgba(34,28,25,.72)); --wf-sh: 0 8px 24px rgba(0,0,0,.25); --wf-div: rgba(241,231,224,.09); --wf-mut: #d9cbc1; --wf-jf: #ff8c52; --wf-bf: #7dd3fc; --wf-bb: linear-gradient(180deg,rgba(255,83,0,.22),rgba(255,83,0,.12)); --wf-bfg: #ffb085; --wf-ob: rgba(34,197,94,.22); --wf-obr: #4ade80; --wf-of: #86efac; margin: 1.4rem 0 1.6rem; border-radius: 12px; border: 1px solid rgba(255,83,0,.28); background: var(--wf-bg); box-shadow: var(--wf-sh); overflow: hidden; }
[data-md-color-scheme="default"] .md-typeset .wf-ip-card { --wf-bg: #faf6f3; --wf-sh: 0 6px 20px rgba(58,48,42,.08); --wf-div: rgba(58,48,42,.09); --wf-mut: #5c4d44; --wf-jf: #cc4200; --wf-bf: #0369a1; --wf-bb: linear-gradient(180deg,rgba(255,83,0,.15),rgba(255,83,0,.08)); --wf-bfg: #cc4200; --wf-ob: rgba(46,125,50,.16); --wf-obr: #2e7d32; --wf-of: #1b5e20; }
.md-typeset .wf-ip-header { display: flex; align-items: center; gap: .55rem; padding: .72rem 1.1rem; background: rgba(255,83,0,.11); border-bottom: 1px solid rgba(255,83,0,.18); font-weight: 700; font-size: .92rem; }
.md-typeset .wf-ip-dot { width: 9px; height: 9px; border-radius: 50%; background: #22c55e; box-shadow: 0 0 8px rgba(34,197,94,.75); }
.md-typeset .wf-ip-badge { margin-left: auto; font-size: .72rem; font-weight: 600; padding: .16rem .6rem; border-radius: 999px; color: var(--wf-mut); border: 1px solid var(--wf-div); }
.md-typeset .wf-ip-row { display: flex; align-items: center; justify-content: space-between; gap: .85rem; padding: .9rem 1.1rem; flex-wrap: wrap; }
.md-typeset .wf-ip-row + .wf-ip-row { border-top: 1px solid var(--wf-div); }
.md-typeset .wf-ip-info { display: flex; align-items: center; gap: .55rem; flex-wrap: wrap; }
.md-typeset .wf-edition { min-width: 76px; text-align: center; font-size: .72rem; font-weight: 700; text-transform: uppercase; padding: .2rem .55rem; border-radius: 6px; }
.md-typeset .wf-edition-java { background: rgba(255,83,0,.14); color: var(--wf-jf); border: 1px solid rgba(255,83,0,.32); }
.md-typeset .wf-edition-bedrock { background: rgba(56,189,248,.14); color: var(--wf-bf); border: 1px solid rgba(56,189,248,.3); }
.md-typeset .wf-ip-code { font-family: var(--md-code-font-family, monospace); font-size: .88rem; padding: .24rem .6rem; border-radius: 6px; background: var(--md-code-bg-color); border: 1px solid var(--wf-div); }
.md-typeset .wf-port-wrap { font-size: .84rem; display: inline-flex; align-items: center; gap: .35rem; }
.md-typeset .wf-copy-btn { appearance: none; display: inline-flex; align-items: center; justify-content: center; gap: .45rem; padding: .5rem 1.05rem; border-radius: 999px; border: 1px solid rgba(255,83,0,.5); background: var(--wf-bb); color: var(--wf-bfg); font: 600 .8rem/1.2 inherit; white-space: nowrap; cursor: pointer; transition: transform .16s ease, box-shadow .2s ease, background .2s ease, color .2s ease; }
.md-typeset .wf-copy-btn:hover { background: linear-gradient(180deg,#ff6a1f,#FF5300); border-color: #ff7a33; color: #fff; transform: translateY(-1px); box-shadow: 0 4px 14px rgba(255,83,0,.4); }
.md-typeset .wf-copy-btn:active { transform: scale(.97); }
.md-typeset .wf-copy-btn.is-copied { background: var(--wf-ob); border-color: var(--wf-obr); color: var(--wf-of); transform: none; box-shadow: none; }
.md-typeset .wf-ip-card ~ p:has(> .md-button), .md-typeset .cta-buttons.center { display: flex; flex-wrap: wrap; justify-content: center; align-items: center; gap: .75rem; margin: 1.4rem 0; text-align: center; }
.md-typeset .wf-ip-card ~ p:has(> .md-button) .md-button { margin: 0; }
@media (max-width: 560px) { .md-typeset .wf-copy-btn { width: 100%; } }
</style>

<script>
window.copyServerIp = (btn, text) => {
  const label = btn.querySelector('.wf-copy-text');
  btn.dataset.orig ??= label.textContent;
  const done = () => {
    clearTimeout(btn._t);
    btn.classList.add('is-copied');
    label.textContent = '¡Copiado!';
    btn._t = setTimeout(() => { btn.classList.remove('is-copied'); label.textContent = btn.dataset.orig; }, 1800);
  };
  if (navigator.clipboard && window.isSecureContext) return navigator.clipboard.writeText(text).then(done);
  const ta = Object.assign(document.createElement('textarea'), { value: text });
  document.body.append(ta); ta.select(); document.execCommand('copy'); ta.remove(); done();
};
</script>

[:fontawesome-brands-discord: Unirse al Discord](https://discord.com/invite/jCmngqZRFV){ .md-button .md-button--primary }
[:fontawesome-solid-store: Ir a la Tienda](https://wolfland.tebex.store/){ .md-button }
{: .cta-buttons .center }

<style>
.md-typeset .wf-steps { display: grid; grid-template-columns: repeat(auto-fit, minmax(210px, 1fr)); gap: .9rem; margin: 1.1rem 0 1.6rem; }
.md-typeset .wf-step { position: relative; display: flex; flex-direction: column; gap: .3rem; padding: 1.1rem; border-radius: 12px; border: 1px solid rgba(255,83,0,.28); background: linear-gradient(145deg, rgba(255,83,0,.09), transparent 70%); color: inherit; transition: transform .16s ease, box-shadow .2s ease, border-color .2s ease; }
.md-typeset .wf-step strong { font-size: .98rem; }
.md-typeset .wf-step > span:not(.wf-step-num) { font-size: .82rem; color: var(--md-default-fg-color--light); line-height: 1.45; }
.md-typeset .wf-step-num { display: inline-flex; align-items: center; justify-content: center; width: 30px; height: 30px; border-radius: 50%; background: #FF5300; color: #fff; font-weight: 700; font-size: .9rem; margin-bottom: .3rem; }
.md-typeset .wf-step:hover, .md-typeset a.wf-card:hover { transform: translateY(-2px); border-color: #FF5300; box-shadow: 0 6px 18px rgba(255,83,0,.22); }
.md-typeset .wf-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: .8rem; margin: .8rem 0 1.4rem; }
.md-typeset .wf-card { display: flex; align-items: flex-start; gap: .85rem; padding: .95rem 1rem; border-radius: 12px; border: 1px solid var(--md-default-fg-color--lightest); background: var(--md-code-bg-color); color: inherit; transition: transform .16s ease, box-shadow .2s ease, border-color .2s ease; }
.md-typeset .wf-card-icon { flex: 0 0 auto; display: inline-flex; align-items: center; justify-content: center; width: 40px; height: 40px; border-radius: 10px; background: rgba(255,83,0,.14); color: #FF5300; }
.md-typeset .wf-card-body { display: flex; flex-direction: column; gap: .15rem; min-width: 0; }
.md-typeset .wf-card-body strong { font-size: .95rem; }
.md-typeset .wf-card-body > span { font-size: .8rem; color: var(--md-default-fg-color--light); line-height: 1.4; }
[data-md-color-scheme="slate"] .md-typeset .wf-card-icon { color: #ff8c52; }
.md-typeset .wf-soon { display: inline-block; margin-left: .35rem; padding: .05rem .5rem; border-radius: 999px; background: rgba(255,83,0,.18); color: #FF5300; font-size: .62rem; font-weight: 700; letter-spacing: .03em; text-transform: uppercase; vertical-align: middle; }
[data-md-color-scheme="slate"] .md-typeset .wf-soon { color: #ff8c52; }
.md-typeset .wf-timeline { position: relative; margin: 1.2rem 0 1.6rem; padding-left: 1.6rem; border-left: 2px solid rgba(255,83,0,.35); }
.md-typeset .wf-tl-item { position: relative; padding: 0 0 1.15rem 0; }
.md-typeset .wf-tl-item:last-child { padding-bottom: 0; }
.md-typeset .wf-tl-item::before { content: ""; position: absolute; left: calc(-1.6rem - 7px); top: .3rem; width: 12px; height: 12px; border-radius: 50%; background: #FF5300; box-shadow: 0 0 0 4px rgba(255,83,0,.2); }
.md-typeset .wf-tl-item.is-next::before { left: calc(-1.6rem - 9px); top: .2rem; width: 16px; height: 16px; box-shadow: 0 0 0 5px rgba(255,83,0,.28), 0 0 14px rgba(255,83,0,.55); }
.md-typeset .wf-tl-date { display: block; font-size: .72rem; font-weight: 700; letter-spacing: .04em; text-transform: uppercase; color: #FF5300; }
[data-md-color-scheme="slate"] .md-typeset .wf-tl-date { color: #ff8c52; }
.md-typeset .wf-tl-item strong { display: block; margin: .1rem 0 .15rem; }
.md-typeset .wf-tl-item p { margin: 0; font-size: .86rem; color: var(--md-default-fg-color--light); }
.md-typeset .wf-tl-item p strong { display: inline; margin: 0; color: var(--md-default-fg-color); }
.md-typeset .wf-values { display: grid; grid-template-columns: repeat(auto-fit, minmax(210px, 1fr)); gap: .8rem; margin: .8rem 0 1.4rem; }
.md-typeset .wf-value { display: flex; flex-direction: column; gap: .35rem; padding: 1rem; border-radius: 12px; border: 1px solid var(--md-default-fg-color--lightest); background: linear-gradient(160deg, rgba(255,83,0,.07), transparent 65%); }
.md-typeset .wf-value strong { font-size: .95rem; }
.md-typeset .wf-value > span:last-child { font-size: .82rem; color: var(--md-default-fg-color--light); line-height: 1.45; }
.md-typeset .wf-chips { display: flex; flex-wrap: wrap; gap: .5rem; margin: .8rem 0 1.4rem; }
.md-typeset .wf-chip { display: inline-flex; align-items: center; gap: .3rem; padding: .32rem .8rem; border-radius: 999px; font-size: .8rem; border: 1px solid rgba(255,83,0,.3); background: rgba(255,83,0,.08); }
.md-typeset .wf-chip code { font-size: .75rem; padding: 0 .3rem; }
</style>

## :material-rocket-launch: Empieza por aquí { #empieza }

Sigue estos tres pasos para empezar a jugar:

<div class="wf-steps">
  <a class="wf-step" href="unirse/">
    <span class="wf-step-num">1</span>
    <strong>Entra al servidor</strong>
    <span>Consigue la IP y sigue los pasos para Java o Bedrock.</span>
  </a>
  <a class="wf-step" href="reglas/">
    <span class="wf-step-num">2</span>
    <strong>Conoce las reglas</strong>
    <span>Léelas con calma: pueden cambiar sin previo aviso.</span>
  </a>
  <a class="wf-step" href="comandos/">
    <span class="wf-step-num">3</span>
    <strong>Descubre qué puedes hacer</strong>
    <span>Comandos, rangos y beneficios para disfrutar al máximo.</span>
  </a>
</div>

### Para jugadores

<div class="wf-grid">
  <a class="wf-card" href="reglas/">
    <span class="wf-card-icon"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/><polyline points="9 12 11 14 15 10"/></svg></span>
    <span class="wf-card-body"><strong>Reglas</strong><span>Normas del servidor y del Discord, sanciones y apelaciones.</span></span>
  </a>
  <a class="wf-card" href="comandos/">
    <span class="wf-card-icon"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><polyline points="4 17 10 11 4 5"/><line x1="12" y1="19" x2="20" y2="19"/></svg></span>
    <span class="wf-card-body"><strong>Comandos</strong><span>Todos los comandos disponibles, organizados por categoría.</span></span>
  </a>
  <a class="wf-card" href="rangos/">
    <span class="wf-card-icon"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><circle cx="12" cy="8" r="7"/><polyline points="8.21 13.89 7 23 12 20 17 23 15.79 13.88"/></svg></span>
    <span class="wf-card-body"><strong>Rangos</strong><span>Staff, premium, media y rangos exclusivos.</span></span>
  </a>
  <a class="wf-card" href="rangos-premium/">
    <span class="wf-card-icon"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg></span>
    <span class="wf-card-body"><strong>Rangos Premium</strong><span>Compara beneficios, kits y comandos de cada rango.</span></span>
  </a>
  <a class="wf-card" href="eventos/">
    <span class="wf-card-icon"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="3" y="4" width="18" height="18" rx="2" ry="2"/><line x1="16" y1="2" x2="16" y2="6"/><line x1="8" y1="2" x2="8" y2="6"/><line x1="3" y1="10" x2="21" y2="10"/></svg></span>
    <span class="wf-card-body"><strong>Eventos</strong><span>Torneos, concursos y actividades de la comunidad.</span></span>
  </a>
  <a class="wf-card" href="noticias/">
    <span class="wf-card-icon"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M18 8A6 6 0 0 0 6 8c0 7-3 9-3 9h18s-3-2-3-9"/><path d="M13.73 21a2 2 0 0 1-3.46 0"/></svg></span>
    <span class="wf-card-body"><strong>Noticias</strong><span>Las últimas actualizaciones del servidor.</span></span>
  </a>
</div>

### Comunidad y equipo

<div class="wf-grid">
  <a class="wf-card" href="https://discord.com/invite/jCmngqZRFV" target="_blank" rel="noopener">
    <span class="wf-card-icon"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M21 11.5a8.38 8.38 0 0 1-.9 3.8 8.5 8.5 0 0 1-7.6 4.7 8.38 8.38 0 0 1-3.8-.9L3 21l1.9-5.7a8.38 8.38 0 0 1-.9-3.8 8.5 8.5 0 0 1 4.7-7.6 8.38 8.38 0 0 1 3.8-.9h.5a8.48 8.48 0 0 1 8 8v.5z"/></svg></span>
    <span class="wf-card-body"><strong>Discord</strong><span>Únete, abre tickets y habla con la comunidad y el staff.</span></span>
  </a>
  <a class="wf-card" href="https://wolfland.tebex.store/" target="_blank" rel="noopener">
    <span class="wf-card-icon"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M6 2L3 6v14a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2V6l-3-4z"/><line x1="3" y1="6" x2="21" y2="6"/><path d="M16 10a4 4 0 0 1-8 0"/></svg></span>
    <span class="wf-card-body"><strong>Tienda oficial</strong><span>Rangos y beneficios. Es el único lugar válido para comprar.</span></span>
  </a>
  <a class="wf-card" href="staff/">
    <span class="wf-card-icon"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/></svg></span>
    <span class="wf-card-body"><strong>Staff</strong><span>Conoce al equipo que cuida el servidor.</span></span>
  </a>
  <a class="wf-card" href="postulaciones/">
    <span class="wf-card-icon"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"/><circle cx="9" cy="7" r="4"/><path d="M23 21v-2a4 4 0 0 0-3-3.87"/><path d="M16 3.13a4 4 0 0 1 0 7.75"/></svg></span>
    <span class="wf-card-body"><strong>Postulaciones</strong><span>Requisitos y proceso para formar parte del equipo.</span></span>
  </a>
  <a class="wf-card" href="rangos-media/">
    <span class="wf-card-icon"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><polygon points="23 7 16 12 23 17 23 7"/><rect x="1" y="5" width="15" height="14" rx="2" ry="2"/></svg></span>
    <span class="wf-card-body"><strong>Creadores de contenido</strong><span>Rangos media y requisitos para streamers y youtubers.</span></span>
  </a>
  <a class="wf-card" href="servicios/">
    <span class="wf-card-icon"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="2" y="7" width="20" height="14" rx="2" ry="2"/><path d="M16 21V5a2 2 0 0 0-2-2h-4a2 2 0 0 0-2 2v16"/></svg></span>
    <span class="wf-card-body"><strong>Servicios</strong><span>Para creadores y artistas que quieren ofrecer sus servicios.</span></span>
  </a>
</div>

---

## :material-information-outline: Sobre Wolfland Network { #sobre-nosotros }

**Wolfland Network** es un servidor de Minecraft **Survival Custom**: la experiencia clásica de supervivencia, con contenido y mecánicas propias, pensada para que explorar, progresar y jugar en comunidad sea cada vez mejor. Somos un **servidor pequeño con el objetivo de ser grande**, y trabajamos cada día para lograrlo.

### Nuestra historia

Wolfland tiene una historia de esfuerzo, caídas y regresos. Este es nuestro camino:

<div class="wf-timeline">
  <div class="wf-tl-item">
    <span class="wf-tl-date">Los inicios</span>
    <strong>TheWolfes</strong>
    <p>Todo empezó con un Realm de Minecraft Bedrock y solo 10 jugadores. Nuestra comunidad vivía en un grupo de Messenger de Facebook.</p>
  </div>
  <div class="wf-tl-item">
    <span class="wf-tl-date">Diciembre de 2023</span>
    <strong>Nace Wolfland</strong>
    <p>Surge la idea de Wolfland y, desde entonces, el proyecto no se ha detenido.</p>
  </div>
  <div class="wf-tl-item">
    <span class="wf-tl-date">Marzo de 2024</span>
    <strong>Primer cierre</strong>
    <p>Tuvimos que cerrar por problemas que no pudimos resolver a tiempo.</p>
  </div>
  <div class="wf-tl-item">
    <span class="wf-tl-date">Noviembre de 2024</span>
    <strong>Volvemos a intentarlo</strong>
    <p>Con muy poco presupuesto lo preparamos todo en una sola semana y abrimos el <strong>2 de diciembre</strong>. Desde ahí, seguimos adelante.</p>
  </div>
  <div class="wf-tl-item">
    <span class="wf-tl-date">Junio de 2025</span>
    <strong>Segundo cierre</strong>
    <p>Al ser una sola persona la encargada de todo, el estrés era demasiado y decidimos parar.</p>
  </div>
  <div class="wf-tl-item">
    <span class="wf-tl-date">Enero y marzo de 2026</span>
    <strong>Nueva apertura</strong>
    <p>En enero anunciamos otra apertura y abrimos en marzo de 2026.</p>
  </div>
  <div class="wf-tl-item">
    <span class="wf-tl-date">Julio de 2026</span>
    <strong>Mantenimiento indefinido</strong>
    <p>Pausamos el servidor para mejorar muchas cosas y traer una mejor calidad.</p>
  </div>
  <div class="wf-tl-item is-next">
    <span class="wf-tl-date">Diciembre de 2026 <span class="wf-soon">Próximamente</span></span>
    <strong>Reapertura: el prime de Wolfland</strong>
    <p>Volvemos con todo lo que mejoramos durante el mantenimiento. <strong>¡Se viene el prime de Wolfland!</strong></p>
  </div>
</div>

!!! quote "Sin rendirnos"
    Hemos recibido críticas, enojos e incluso malos deseos, y hemos atravesado problemas personales. **Aun así, no nos hemos rendido.** Cada pausa fue una oportunidad para volver mejores, y cada regreso es posible gracias a quienes creen en este proyecto.

**Esperamos que formes parte de esta comunidad y de todo lo que viene.**

!!! abstract "Nuestro compromiso"
    Daremos lo mejor para que la comunidad de Wolfland Network sea **la mejor de todas**, mejorando y trayendo cosas nuevas. **Nuestra prioridad es la comodidad y la jugabilidad de nuestros miembros.**

### Lo que nos define

<div class="wf-values">
  <div class="wf-value">
    <span class="wf-card-icon"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M4 15s1-1 4-1 5 2 8 2 4-1 4-1V3s-1 1-4 1-5-2-8-2-4 1-4 1z"/><line x1="4" y1="22" x2="4" y2="15"/></svg></span>
    <strong>Perseverancia</strong>
    <span>Desde diciembre de 2023 no nos hemos rendido, y seguimos adelante.</span>
  </div>
  <div class="wf-value">
    <span class="wf-card-icon"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"/><circle cx="9" cy="7" r="4"/><path d="M23 21v-2a4 4 0 0 0-3-3.87"/><path d="M16 3.13a4 4 0 0 1 0 7.75"/></svg></span>
    <strong>Comunidad</strong>
    <span>Queremos que sea la mejor de todas, hecha entre todos.</span>
  </div>
  <div class="wf-value">
    <span class="wf-card-icon"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><line x1="6" y1="12" x2="10" y2="12"/><line x1="8" y1="10" x2="8" y2="14"/><line x1="15" y1="13" x2="15.01" y2="13"/><line x1="18" y1="11" x2="18.01" y2="11"/><rect x="2" y="6" width="20" height="12" rx="2"/></svg></span>
    <strong>Comodidad y jugabilidad</strong>
    <span>Es nuestra prioridad: que jugar aquí sea fácil y agradable.</span>
  </div>
  <div class="wf-value">
    <span class="wf-card-icon"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><polyline points="23 6 13.5 15.5 8.5 10.5 1 18"/><polyline points="17 6 23 6 23 12"/></svg></span>
    <strong>Mejora constante</strong>
    <span>Seguimos mejorando y trayendo cosas nuevas.</span>
  </div>
</div>

### Qué hace especial a nuestro Survival Custom

Un survival pensado para que cada día tengas algo nuevo que hacer. Te invitamos a descubrirlo:

<div class="wf-grid">
  <div class="wf-card wf-card-static">
    <span class="wf-card-icon"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M3 21V8l3 2V5l3 2V4h6v3l3-2v5l3-2v13z"/><path d="M10 21v-5a2 2 0 0 1 4 0v5"/></svg></span>
    <span class="wf-card-body"><strong>Mazmorras</strong><span>Mazmorras llenas de desafíos para explorar.</span></span>
  </div>
  <div class="wf-card wf-card-static">
    <span class="wf-card-icon"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M12 2a8 8 0 0 0-8 8c0 2.5 1.2 4.3 3 5.5V19a1 1 0 0 0 1 1h8a1 1 0 0 0 1-1v-3.5c1.8-1.2 3-3 3-5.5a8 8 0 0 0-8-8z"/><circle cx="9" cy="11" r="1.2"/><circle cx="15" cy="11" r="1.2"/><line x1="10" y1="20" x2="10" y2="22"/><line x1="14" y1="20" x2="14" y2="22"/></svg></span>
    <span class="wf-card-body"><strong>Jefes customizados</strong><span>Jefes personalizados que ponen a prueba tus habilidades.</span></span>
  </div>
  <div class="wf-card wf-card-static">
    <span class="wf-card-icon"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><polyline points="20 12 20 22 4 22 4 12"/><rect x="2" y="7" width="20" height="5"/><line x1="12" y1="22" x2="12" y2="7"/><path d="M12 7H7.5a2.5 2.5 0 0 1 0-5C11 2 12 7 12 7z"/><path d="M12 7h4.5a2.5 2.5 0 0 0 0-5C13 2 12 7 12 7z"/></svg></span>
    <span class="wf-card-body"><strong>Kits épicos</strong><span>Kits épicos disponibles, además de los de los rangos de pago.</span></span>
  </div>
  <div class="wf-card wf-card-static">
    <span class="wf-card-icon"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M14.7 6.3a1 1 0 0 0 0 1.4l1.6 1.6a1 1 0 0 0 1.4 0l3.77-3.77a6 6 0 0 1-7.94 7.94l-6.91 6.91a2.12 2.12 0 0 1-3-3l6.91-6.91a6 6 0 0 1 7.94-7.94l-3.76 3.76z"/></svg></span>
    <span class="wf-card-body"><strong>Trabajos mejorados</strong><span>Un sistema de trabajos mejorado para progresar mientras juegas.</span></span>
  </div>
  <div class="wf-card wf-card-static">
    <span class="wf-card-icon"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="3" y="11" width="18" height="11" rx="2" ry="2"/><path d="M7 11V7a5 5 0 0 1 10 0v4"/></svg></span>
    <span class="wf-card-body"><strong>Protecciones mejoradas</strong><span>Un sistema de protecciones mejorado para cuidar tus terrenos y construcciones.</span></span>
  </div>
  <div class="wf-card wf-card-static">
    <span class="wf-card-icon"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><circle cx="6" cy="10" r="2"/><circle cx="10" cy="6" r="2"/><circle cx="14" cy="6" r="2"/><circle cx="18" cy="10" r="2"/><path d="M12 12c-3 0-6 3-6 6 0 2 2 3 3.5 2.5.9-.3 1.5-.5 2.5-.5s1.6.2 2.5.5c1.5.5 3.5-.5 3.5-2.5 0-3-3-6-6-6z"/></svg></span>
    <span class="wf-card-body"><strong>Mascotas</strong><span>Mascotas para acompañarte en tu aventura.</span></span>
  </div>
  <div class="wf-card wf-card-static">
    <span class="wf-card-icon"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><polygon points="3 11 22 2 13 21 11 13 3 11"/></svg></span>
    <span class="wf-card-body"><strong>Monturas <span class="wf-soon">Próximamente</span></strong><span>Monturas para recorrer el mundo.</span></span>
  </div>
  <div class="wf-card wf-card-static">
    <span class="wf-card-icon"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><circle cx="12" cy="12" r="10"/><polygon points="16.24 7.76 14.12 14.12 7.76 16.24 9.88 9.88 16.24 7.76"/></svg></span>
    <span class="wf-card-body"><strong>Mundo de exploración</strong><span>Un mundo principal con estructuras y biomas mejorados, creado para explorar.</span></span>
  </div>
  <div class="wf-card wf-card-static">
    <span class="wf-card-icon"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><polyline points="23 6 13.5 15.5 8.5 10.5 1 18"/><polyline points="17 6 23 6 23 12"/></svg></span>
    <span class="wf-card-body"><strong>Rankup</strong><span>Un sistema de rankup para avanzar y progresar.</span></span>
  </div>
  <div class="wf-card wf-card-static">
    <span class="wf-card-icon"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="3" y="4" width="18" height="18" rx="2" ry="2"/><line x1="16" y1="2" x2="16" y2="6"/><line x1="8" y1="2" x2="8" y2="6"/><line x1="3" y1="10" x2="21" y2="10"/></svg></span>
    <span class="wf-card-body"><strong>Recompensas diarias</strong><span>Entra cada día y recibe tus recompensas.</span></span>
  </div>
  <div class="wf-card wf-card-static">
    <span class="wf-card-icon"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><polyline points="17 1 21 5 17 9"/><path d="M3 11V9a4 4 0 0 1 4-4h14"/><polyline points="7 23 3 19 7 15"/><path d="M21 13v2a4 4 0 0 1-4 4H3"/></svg></span>
    <span class="wf-card-body"><strong>Tradeos y crafteos</strong><span>Muchos tradeos y crafteos que mejoran la experiencia y el progreso.</span></span>
  </div>
  <div class="wf-card wf-card-static">
    <span class="wf-card-icon"><svg viewBox="0 0 24 24" width="22" height="22" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><polygon points="13 2 3 14 12 14 11 22 21 10 12 10 13 2"/></svg></span>
    <span class="wf-card-body"><strong>Mejoras constantes</strong><span>Con cada día que pasa, el servidor mejora más.</span></span>
  </div>
</div>

Y además, estos sistemas te esperan en el servidor:

<div class="wf-chips">
  <span class="wf-chip">Mundos de recursos</span>
  <span class="wf-chip">Misiones <code>/quest</code></span>
  <span class="wf-chip">Subastas <code>/ah</code></span>
  <span class="wf-chip">Tiendas con cofres (ShopChest)</span>
  <span class="wf-chip">Warps personales</span>
  <span class="wf-chip">Bóvedas personales <code>/pv</code></span>
  <span class="wf-chip">Cajas con llaves legendarias</span>
</div>

### Ficha del servidor

| Dato | Detalle |
|------|---------|
| **Modo de juego** | Survival Custom |
| **Ediciones** | Java y Bedrock |
| **IP** | `play.wolfland.pro` |
| **Puerto Bedrock** | `19132` |
| **Idiomas** | Español e inglés |
| **Inicio del proyecto** | Diciembre de 2023 |
| **Comunidad** | [Discord](https://discord.com/invite/jCmngqZRFV) |
| **Tienda oficial** | [wolfland.tebex.store](https://wolfland.tebex.store/) |

---

## :material-help-circle-outline: Preguntas frecuentes { #faq }

??? question "¿Puedo jugar desde Bedrock?"
    Sí. Wolfland Network acepta **Java y Bedrock**. En Bedrock usa la IP `play.wolfland.pro` con el puerto `19132`. Los pasos están en [Cómo unirse](unirse.md).

??? question "¿Qué idiomas se usan en el servidor?"
    Los idiomas oficiales son el **español** y el **inglés**. Usa uno de ellos en el chat público.

??? question "¿Dónde puedo comprar rangos?"
    **Solo en la [tienda oficial](https://wolfland.tebex.store/).** Cualquier compra fuera de ella no está permitida ni se reconoce. Más detalles en las [reglas de la tienda](reglas.md#4-tienda-oficial-tebex).

??? question "¿Cómo contacto con el staff o abro un ticket?"
    Entra a nuestro [Discord](https://discord.com/invite/jCmngqZRFV) y abre un ticket. Es el canal oficial para soporte, reportes y apelaciones.

??? question "¿Cómo puedo formar parte del staff?"
    Las postulaciones se hacen por ticket en el Discord y tienen requisitos. Revísalos en [Postulaciones](postulaciones.md).

??? question "¿Puedo ser creador de contenido del servidor?"
    Sí, si cumples los requisitos. Mira los rangos media en [Creadores de contenido](rangos-media.md).

??? question "¿Dónde veo las novedades?"
    En la sección de [Noticias](noticias.md) y en el [Discord](https://discord.com/invite/jCmngqZRFV).

---

## :material-heart: Te esperamos { #te-esperamos }

**Esperamos que formes parte de esta comunidad.** Aquí hay un lugar para ti: explora, construye, haz amigos y vive la aventura con nosotros. ¡Te estamos esperando en Wolfland!

[:fontawesome-brands-discord: Unirme al Discord](https://discord.com/invite/jCmngqZRFV){ .md-button .md-button--primary }
[:material-login: Cómo unirse](unirse.md){ .md-button }
{: .cta-buttons .center }
