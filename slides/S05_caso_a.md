---
slide_id: S05
slide_type: anexo
section: casos
action_title: ""
position: 5
status: draft
evidences: []
content:
  eyebrow: "CASO A"
  subtitle: ""
  body_html: |
    <style>
      .s05.anexo-slide .body { top: 170px !important; bottom: 100px !important; overflow: visible !important; }
      .body > .s05 { padding-top: 0; max-width: 1440px; display: flex; flex-direction: column; justify-content: space-between; height: 100%; box-sizing: border-box; font-family: var(--sans); gap: 20px; }
      .s05 .top-row { display: grid; grid-template-columns: 1fr 1fr; column-gap: 80px; align-items: start; }
      .s05 .setup,
      .s05 .pivote { font-size: 22px; font-weight: 400; line-height: 1.5; color: var(--ink); }
      .s05 .top-row .pivote { text-align: right; }
      .s05 .coral-line { color: var(--coral); font-weight: 600; }
      .s05 .track { display: grid; grid-template-columns: auto 1fr auto; column-gap: 32px; row-gap: 10px; align-items: center; }
      .s05 .track .l-start, .s05 .track .l-end { font-size: 14px; font-weight: 600; color: var(--mute); letter-spacing: 0.12em; text-transform: uppercase; }
      .s05 .track .l-end { justify-self: end; }
      .s05 .track .node-start, .s05 .track .node-end { font-size: 22px; font-weight: 600; color: var(--ink); }
      .s05 .track .node-end { justify-self: end; }
      .s05 .track .arrow { grid-column: 2; }
      .s05 .track .arrow svg { display: block; width: 100%; height: 12px; }
      .s05 .flows { display: flex; flex-direction: column; gap: 14px; max-width: 1180px; margin: 0 auto; width: 100%; }
      .s05 .flow-row { display: grid; grid-template-columns: 180px 1fr; column-gap: 36px; align-items: baseline; padding: 16px 24px; border: 1px solid transparent; border-radius: 4px; }
      .s05 .flow-row.ready { border-color: rgba(221, 75, 41, 0.45); }
      .s05 .flow-label { font-size: 14px; font-weight: 600; color: var(--ink); letter-spacing: 0.12em; text-transform: uppercase; padding-top: 6px; }
      .s05 .flow-row.ready .flow-label { color: var(--coral); }
      .s05 .flow-content { display: flex; flex-direction: column; gap: 4px; }
      .s05 .flow-steps { font-size: 20px; font-weight: 500; color: var(--ink); line-height: 1.4; }
      .s05 .agents { display: grid; grid-template-columns: 1fr 1fr; column-gap: 40px; }
      .s05 .agent { display: flex; flex-direction: column; gap: 6px; }
      .s05 .agent .role { font-family: var(--mono); font-size: 13px; font-weight: 700; color: var(--mute); letter-spacing: 0.1em; text-transform: uppercase; margin-bottom: 2px; }
      .s05 .agent .role .time { color: var(--ink); font-weight: 700; margin-left: 6px; }
      .s05 .agent.deep .role { color: var(--coral); }
      .s05 .agent.deep .role .time { color: var(--coral); }
      .s05 .agent .desc { font-size: 17px; font-weight: 400; color: var(--ink); line-height: 1.45; }
      .s05 .agent .desc strong { font-weight: 600; }
      .s05 .cifra-row { display: flex; justify-content: space-between; align-items: baseline; gap: 24px; font-size: 20px; flex-wrap: wrap; padding-top: 8px; }
      .s05 .cifra-label { color: var(--mute); }
      .s05 .cifra-value { color: var(--ink); font-weight: 700; font-size: 22px; letter-spacing: -0.005em; }
    </style>
    <div class="s05">
      <div class="top-row">
        <div class="setup">Una empresa quiere detectar y priorizar oportunidades de negocio con el sector estatal.</div>
        <div class="pivote"><span class="coral-line">La revisión manual no escala.</span><br>Cientos de páginas por pliego, pocos días para detectar requisitos con precisión.</div>
      </div>
      <div class="track">
        <span class="l-start">Mismo inicio</span>
        <span class="spacer"></span>
        <span class="l-end">Mismo final</span>
        <span class="node-start">SECOP II</span>
        <span class="arrow"><svg viewBox="0 0 1000 12" preserveAspectRatio="none"><line x1="0" y1="6" x2="988" y2="6" stroke="#0F0E12" stroke-width="1" vector-effect="non-scaling-stroke"/><polygon points="988,1 1000,6 988,11" fill="#0F0E12"/></svg></span>
        <span class="node-end">propuesta</span>
      </div>
      <div class="flows">
        <div class="flow-row">
          <div class="flow-label">Hoy</div>
          <div class="flow-content">
            <div class="flow-steps">lectura humana &nbsp;→&nbsp; priorización por experiencia &nbsp;→&nbsp; cruce manual con cientos de páginas</div>
          </div>
        </div>
        <div class="flow-row ready">
          <div class="flow-label">Agent-ready</div>
          <div class="flow-content">
            <div class="agents">
              <div class="agent">
                <div class="role">Agente · scout <span class="time">· &lt; 5 min</span></div>
                <div class="desc">monitorea SECOP, filtra y prioriza con UNSPSC + keywords + rúbrica corporativa. Entrega <strong>top viables del día</strong>.</div>
              </div>
              <div class="agent deep">
                <div class="role">Deep Agent · analista <span class="time">· &lt; 15 min</span></div>
                <div class="desc">cruza pliego vs RUP, perfil financiero y experiencia. Entrega <strong>recomendación OFERTAR / NO OFERTAR + plan de acción</strong>.</div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="cifra-row">
        <span class="cifra-label">Procesos nuevos en SECOP II</span>
        <span class="cifra-value">~5.000 / día · ~1,9 M / año (2025)</span>
      </div>
    </div>
  caption: ""
---

# Caso A · licitaciones públicas

Slide nuevo, exclusiva del deck Flisol.

Patrón A/B/C de casos (reenumerado tras reorden para CUSOL):
- **A (licitaciones SECOP II): agente proactivo (scout) + deep agent (analista)** — multi-agente con división de trabajo
- B (restaurante WhatsApp): agente reactivo conversacional
- C (cuenta empresarial NIT): agente de onboarding asistido — ángulo emprendimiento

Generalizado para cualquier industria que oferta en contratación pública del estado colombiano. El skill base que implementa este patrón (`Skill_Hartmann`) es industria-agnóstico en código; solo cambian los archivos Markdown de perfil/rúbrica/keywords por sector.

Cifras verificadas vía API SODA (dataset `p6dx-8zbt` en datos.gov.co, Colombia Compra Eficiente):
- 2024: 1.598.413 procesos únicos → ~4.379/día
- 2025: 1.854.988 procesos únicos → ~5.082/día
- Se usa el dato 2025 (~5.000/día · 1,9 M/año) por ser el más reciente verificable.
