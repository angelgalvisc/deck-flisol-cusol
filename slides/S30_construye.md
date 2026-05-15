---
slide_id: S30
slide_type: anexo
section: aterrizaje
action_title: "Construye un producto desde Colombia."
position: 30
status: draft
evidences: []
content:
  eyebrow: ""
  subtitle: ""
  body_html: |
    <style>
      .s30.anexo-slide .body { top: 200px !important; bottom: 90px !important; overflow: visible !important; }
      .body > .s30 { padding-top: 0; max-width: 1400px; display: flex; flex-direction: column; gap: 26px; font-family: var(--sans); }
      .s30 .palanca { display: grid; grid-template-columns: 90px 1fr; column-gap: 28px; align-items: start; }
      .s30 .palanca .n { font-family: var(--mono); font-size: 64px; font-weight: 700; color: var(--ink); line-height: 0.9; }
      .s30 .palanca .col { display: flex; flex-direction: column; gap: 8px; }
      .s30 .palanca .h { font-size: 26px; font-weight: 600; color: var(--ink); line-height: 1.2; }
      .s30 .palanca .sub { font-size: 16px; color: var(--mute); line-height: 1.45; }
      .s30 .datasets { display: grid; grid-template-columns: 160px 1fr; column-gap: 16px; row-gap: 6px; margin-top: 6px; }
      .s30 .datasets .dn { font-family: var(--mono); font-size: 16px; font-weight: 700; color: var(--ink); }
      .s30 .datasets .dd { font-size: 16px; color: var(--ink); line-height: 1.45; }
      .s30 .datasets .dd .mute { color: var(--mute); }
      .s30 .action-line { font-family: var(--mono); font-size: 13px; color: var(--mute); letter-spacing: 0.06em; text-transform: uppercase; margin-top: 8px; }
      .s30 .agent-vs { display: grid; grid-template-columns: 1fr 1fr; column-gap: 32px; margin-top: 6px; }
      .s30 .agent-vs .col-head { font-family: var(--mono); font-size: 13px; font-weight: 700; letter-spacing: 0.08em; text-transform: uppercase; margin-bottom: 6px; }
      .s30 .agent-vs .left .col-head { color: var(--mute); }
      .s30 .agent-vs .right .col-head { color: var(--ink); }
      .s30 .agent-vs .desc { font-size: 15px; color: var(--ink); line-height: 1.45; }
      .s30 .agent-vs .desc ul { margin: 6px 0 0 0; padding-left: 16px; }
      .s30 .agent-vs .desc li { padding: 2px 0; }
      .s30 .rule { height: 1px; background: var(--rule); }
      .s30 .section-label { font-family: var(--mono); font-size: 13px; font-weight: 700; color: var(--mute); letter-spacing: 0.1em; text-transform: uppercase; margin-bottom: 8px; }
      .s30 .datasets a.dn { text-decoration: none; color: var(--ink); border-bottom: 1px solid var(--mute); padding-bottom: 1px; }
      .s30 .datasets a.dn:hover { color: var(--coral); border-bottom-color: var(--coral); }
    </style>
    <div class="s30">
      <div class="section-label">OPORTUNIDADES PARA TI · 2 / 2 · CONSTRUYE</div>
      <div class="palanca">
        <span class="n">3</span>
        <div class="col">
          <div class="h">Construye sobre data pública colombiana</div>
          <div class="sub">Tres puertas de entrada a la data pública del país. Ninguna pide trámite. El patrón <em>scout + analista</em> del Caso A funciona en cualquiera de ellas.</div>
          <div class="datasets">
            <a class="dn" href="https://www.datos.gov.co/">datos.gov.co</a>
            <span class="dd">Socrata SODA · REST · SDKs en Python, R, JS, .NET <span class="mute">· catálogo central del Estado (miles de datasets)</span></span>
            <a class="dn" href="https://microdatos.dane.gov.co/">DANE</a>
            <span class="dd">microdatos.dane.gov.co + Geoportal (ArcGIS REST) <span class="mute">· censo, encuestas oficiales, geo</span></span>
            <a class="dn" href="https://www.datos.gov.co/Gastos-Gubernamentales/SECOP-II-Contratos-Electr-nicos/jbjy-vk9h">SECOP II</a>
            <span class="dd">1,9M procesos/año <span class="mute">· contratación pública</span></span>
          </div>
          <div class="action-line">acción · dataset abierto + pregunta que se repite en una industria + automatización del Caso A = primer producto vendible</div>
        </div>
      </div>

      <div class="rule"></div>

      <div class="palanca">
        <span class="n">4</span>
        <div class="col">
          <div class="h">Emprende con deep agents — no con chatbots</div>
          <div class="sub">Un chatbot responde una pregunta. Un deep agent sostiene una operación de horas. Cualquier trabajo humano de 4-8 horas es un producto posible.</div>
          <div class="agent-vs">
            <div class="left">
              <div class="col-head">Agente normal</div>
              <div class="desc">Trabaja por solicitud:
                <ul>
                  <li>loop corto · piensa → herramienta → responde</li>
                  <li>estado vive en el contexto de la solicitud</li>
                  <li>horizonte: segundos a minutos</li>
                  <li>pensado para <strong>responder</strong></li>
                  <li>entrega: una respuesta</li>
                </ul>
              </div>
            </div>
            <div class="right">
              <div class="col-head">Deep agent</div>
              <div class="desc">Trabaja por misión:
                <ul>
                  <li>escribe un plan, lo ejecuta, delega a sub-agentes</li>
                  <li>estado vive en archivos persistentes</li>
                  <li>horizonte: horas a días</li>
                  <li>pensado para <strong>entregar</strong></li>
                  <li>entrega: un artefacto verificable (PR, informe, reporte)</li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>

    </div>
  caption: ""
---
