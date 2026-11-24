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
.md-typeset .wf-step { position: relative; display: flex; flex-direction: column; gap: .3rem; padding: 1.1rem 1.1rem 1.1rem 1.1rem; border-radius: 12px; border: 1px solid rgba(255,83,0,.28); background: linear-gradient(145deg, rgba(255,83,0,.09), transparent 70%); color: inherit; transition: transform .16s ease, box-shadow .2s ease, border-color .2s ease; }
.md-typeset .wf-step strong { font-size: .98rem; }
.md-typeset .wf-step > span:not(.wf-step-num) { font-size: .82rem; color: var(--md-default-fg-color--light); line-height: 1.45; }
.md-typeset .wf-step-num { display: inline-flex; align-items: center; justify-content: center; width: 30px; height: 30px; border-radius: 50%; background: #FF5300; color: #fff; font-weight: 700; font-size: .9rem; margin-bottom: .3rem; }
.md-typeset .wf-step:hover, .md-typeset .wf-card:hover { transform: translateY(-2px); border-color: #FF5300; box-shadow: 0 6px 18px rgba(255,83,0,.22); }
.md-typeset .wf-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: .8rem; margin: .8rem 0 1.4rem; }
.md-typeset .wf-card { display: flex; align-items: flex-start; gap: .85rem; padding: .95rem 1rem; border-radius: 12px; border: 1px solid var(--md-default-fg-color--lightest); background: var(--md-code-bg-color); color: inherit; transition: transform .16s ease, box-shadow .2s ease, border-color .2s ease; }
.md-typeset .wf-card-icon { flex: 0 0 auto; display: inline-flex; align-items: center; justify-content: center; width: 40px; height: 40px; border-radius: 10px; background: rgba(255,83,0,.14); color: #FF5300; }
.md-typeset .wf-card-body { display: flex; flex-direction: column; gap: .15rem; min-width: 0; }
.md-typeset .wf-card-body strong { font-size: .95rem; }
.md-typeset .wf-card-body span { font-size: .8rem; color: var(--md-default-fg-color--light); line-height: 1.4; }
[data-md-color-scheme="slate"] .md-typeset .wf-card-icon { color: #ff8c52; }
.md-typeset .wf-timeline { position: relative; margin: 1.2rem 0 1.6rem; padding-left: 1.6rem; border-left: 2px solid rgba(255,83,0,.35); }
.md-typeset .wf-tl-item { position: relative; padding: 0 0 1.15rem 0; }
.md-typeset .wf-tl-item:last-child { padding-bottom: 0; }
.md-typeset .wf-tl-item::before { content: ""; position: absolute; left: calc(-1.6rem - 7px); top: .3rem; width: 12px; height: 12px; border-radius: 50%; background: #FF5300; box-shadow: 0 0 0 4px rgba(255,83,0,.2); }
.md-typeset .wf-tl-date { display: block; font-size: .72rem; font-weight: 700; letter-spacing: .04em; text-transform: uppercase; color: #FF5300; }
[data-md-color-scheme="slate"] .md-typeset .wf-tl-date { color: #ff8c52; }
.md-typeset .wf-tl-item strong { display: block; margin: .1rem 0 .15rem; }
.md-typeset .wf-tl-item p { margin: 0; font-size: .86rem; color: var(--md-default-fg-color--light); }
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

**Wolfland Network** es un servidor de Minecraft **Survival Custom**: la experiencia clásica de supervivencia, con contenido y mecánicas propias. Somos un **servidor pequeño con el objetivo de ser grande**, y trabajamos cada día para lograrlo.

### Nuestra historia

<div class="wf-timeline">
  <div class="wf-tl-item">
    <span class="wf-tl-date">Diciembre de 2023</span>
    <strong>Nace el proyecto</strong>
    <p>Wolfland Network empieza su camino como un proyecto pequeño, con grandes ganas de crecer.</p>
  </div>
  <div class="wf-tl-item">
    <span class="wf-tl-date">Pausas y reaperturas</span>
    <strong>Nunca nos hemos rendido</strong>
    <p>Hubo momentos en los que el servidor se pausó. Cada vez volvimos a abrir y seguimos adelante.</p>
  </div>
  <div class="wf-tl-item">
    <span class="wf-tl-date">Hoy</span>
    <strong>Seguimos creciendo</strong>
    <p>Continuamos mejorando el servidor y trayendo novedades para toda nuestra comunidad.</p>
  </div>
</div>

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

### Qué encontrarás en el servidor

<div class="wf-chips">
  <span class="wf-chip">Mundos de recursos</span>
  <span class="wf-chip">Misiones <code>/quest</code></span>
  <span class="wf-chip">Trabajos <code>/jobs</code></span>
  <span class="wf-chip">Subastas <code>/ah</code></span>
  <span class="wf-chip">Tiendas con cofres (ShopChest)</span>
  <span class="wf-chip">Warps personales</span>
  <span class="wf-chip">Protección de terrenos</span>
  <span class="wf-chip">Bóvedas personales <code>/pv</code></span>
  <span class="wf-chip">Kits periódicos</span>
  <span class="wf-chip">Cajas con llaves legendarias</span>
</div>

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
