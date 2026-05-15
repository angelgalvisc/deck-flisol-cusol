---
slide_id: S25
slide_type: anexo
section: aterrizaje
action_title: "Domina la disciplina antes de que se vuelva commodity."
position: 25
status: draft
evidences: []
content:
  eyebrow: ""
  subtitle: ""
  body_html: |
    <style>
      .s25.anexo-slide .body { top: 200px !important; bottom: 90px !important; overflow: visible !important; }
      .body > .s25 { padding-top: 0; max-width: 1400px; display: flex; flex-direction: column; gap: 30px; font-family: var(--sans); }
      .s25 .palanca { display: grid; grid-template-columns: 90px 1fr; column-gap: 28px; align-items: start; }
      .s25 .palanca .n { font-family: var(--mono); font-size: 64px; font-weight: 700; color: var(--ink); line-height: 0.9; }
      .s25 .palanca.lead .n { color: var(--coral); }
      .s25 .palanca .col { display: flex; flex-direction: column; gap: 10px; }
      .s25 .palanca .h { font-size: 26px; font-weight: 600; color: var(--ink); line-height: 1.2; }
      .s25 .palanca .sub { font-size: 16px; color: var(--mute); line-height: 1.45; }
      .s25 .triplet { display: grid; grid-template-columns: 130px 1fr; column-gap: 16px; row-gap: 6px; margin-top: 6px; }
      .s25 .triplet .lab { font-family: var(--mono); font-size: 12px; font-weight: 700; color: var(--mute); letter-spacing: 0.08em; text-transform: uppercase; padding-top: 3px; }
      .s25 .triplet .val { font-size: 16px; color: var(--ink); line-height: 1.45; }
      .s25 .triplet .val .paper { font-family: var(--mono); font-weight: 700; }
      .s25 .stack-table { display: grid; grid-template-columns: 130px 1fr; column-gap: 16px; row-gap: 8px; margin-top: 6px; }
      .s25 .stack-table .repo { font-family: var(--mono); font-size: 16px; font-weight: 700; color: var(--ink); padding-top: 2px; }
      .s25 .stack-table .trait { font-size: 15px; color: var(--ink); line-height: 1.45; }
      .s25 .stack-table .trait .mute { color: var(--mute); }
      .s25 .stack-table .url { font-family: var(--mono); font-size: 14px; color: var(--coral); margin-left: 6px; letter-spacing: 0.02em; text-decoration: underline; text-decoration-color: var(--coral); text-underline-offset: 3px; font-weight: 600; }
      .s25 .stack-table .url::before { content: "↗ "; font-weight: 700; }
      .s25 .stack-table .url:hover { color: var(--ink); text-decoration-color: var(--ink); }
      .s25 .triplet .val a.paper { color: var(--ink); text-decoration: underline; text-decoration-color: var(--mute); text-underline-offset: 3px; font-family: var(--mono); font-weight: 700; }
      .s25 .triplet .val a.paper:hover { color: var(--coral); text-decoration-color: var(--coral); }
      .s25 .section-label { font-family: var(--mono); font-size: 13px; font-weight: 700; color: var(--mute); letter-spacing: 0.1em; text-transform: uppercase; margin-bottom: 8px; }
      .s25 .action-line { font-family: var(--mono); font-size: 13px; color: var(--mute); letter-spacing: 0.06em; text-transform: uppercase; margin-top: 8px; }
      .s25 .action-line code { font-family: var(--mono); background: var(--soft); padding: 2px 8px; border-radius: 2px; color: var(--ink); font-weight: 700; text-transform: none; letter-spacing: 0; }
      .s25 .rule { height: 1px; background: var(--rule); }
    </style>
    <div class="s25">
      <div class="section-label">OPORTUNIDADES PARA TI · 1 / 2 · APRENDE</div>
      <div class="palanca lead">
        <span class="n">1</span>
        <div class="col">
          <div class="h">Aprende harness engineering · ninguna universidad lo está enseñando</div>
          <div class="sub">En el modelo no tenemos ventajas competitivas. Pero en el harness tenemos cómo construir — y la disciplina apenas se está nombrando.</div>
          <div class="triplet">
            <div class="lab">por qué ahora</div>
            <div class="val">Dos referencias fundacionales: <a class="paper" href="https://www.anthropic.com/research/building-effective-agents">Building Effective Agents</a> (Anthropic, 2024) y <a class="paper" href="https://www.anthropic.com/engineering/effective-harnesses-for-long-running-agents">Effective harnesses for long-running agents</a> (Anthropic, 2026). No hay décadas de teoría que arrastrar.</div>
            <div class="lab">cuánto cuesta</div>
            <div class="val">6-8 semanas intensivas. Leer ambos papers, ver tutoriales, escribir tu primer agente, modificar un harness abierto. Ventana rara: hoy un estudiante puede saber más que su profesor.</div>
          </div>
        </div>
      </div>

      <div class="rule"></div>

      <div class="palanca">
        <span class="n">2</span>
        <div class="col">
          <div class="h">Lee un harness abierto entero</div>
          <div class="sub">Cinco harnesses con código abierto, cada uno con una decisión de diseño distinta. Leer uno completo es la curva de aprendizaje más rápida que existe.</div>
          <div class="stack-table">
            <span class="repo">Hermes</span>
            <span class="trait">learning loop · memoria persistente <span class="mute">· aprende entre sesiones (Nous Research, MIT)</span> <a class="url" href="https://github.com/nousresearch/hermes-agent">nousresearch/hermes-agent</a></span>
            <span class="repo">OpenClaw</span>
            <span class="trait">el original · <strong>TypeScript / Node.js</strong> · ~371k LoC <span class="mute">· multi-canal nativo (WhatsApp, Slack, Discord, Telegram, iMessage…)</span> <a class="url" href="https://github.com/openclaw/openclaw">openclaw/openclaw</a></span>
            <span class="repo">NanoClaw</span>
            <span class="trait">aislamiento + comprensible <span class="mute">· cada agente en un contenedor Linux (Docker o Apple Container) · si el agente hace algo raro, no toca tu máquina</span> <a class="url" href="https://github.com/nanocoai/nanoclaw">nanocoai/nanoclaw</a></span>
            <span class="repo">PicoClaw</span>
            <span class="trait">embedded · Go · &lt;10MB RAM <span class="mute">· corre en Raspberry Pi Zero (~$10 USD) · ideal para dispositivos en campo</span> <a class="url" href="https://github.com/sipeed/picoclaw">sipeed/picoclaw</a></span>
            <span class="repo">NullClaw</span>
            <span class="trait">ultra-minimal · <strong>Zig</strong> · binario 678KB · 1MB RAM <span class="mute">· arranca en 2ms · cabe en cualquier microcontrolador</span> <a class="url" href="https://github.com/nullclaw/nullclaw">nullclaw/nullclaw</a></span>
          </div>
          <div class="action-line">acción · <code>git clone</code> · README + tres archivos clave · un fin de semana</div>
        </div>
      </div>
    </div>
  caption: ""
---

# Aprende · oportunidades 1/2

Reemplaza S22-S23-S24 originales (apuestas/ecosistema/oportunidades [redacted]). Primera slide del cierre orientada a CUSOL.

Palanca 1 · harness engineering como skill. Foundational papers nombrados:
- ReAct (Yao et al., 2022): https://arxiv.org/abs/2210.03629 — fundacional para el patrón razonar-actuar-observar.
- Building Effective Agents (Anthropic, 2024): https://www.anthropic.com/research/building-effective-agents — guía canónica de patrones de agentes en producción.

Palanca 2 · harnesses open source verificados (mayo 2026):
- OpenClaw (lanzado 30-ene-2026, 500k LoC)
- NanoClaw (containers Linux para aislamiento)
- PicoClaw (Sipeed, Go, <10MB RAM, hardware $10)
- NullClaw / ZeroClaw / IronClaw (variantes minimalistas)
- Hermes (Nous Research, feb-2026, MIT)

El coral va en el número "1" — único uso de coral en el slide, marcando la palanca más importante.
