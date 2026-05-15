---
slide_id: S12
slide_type: anexo
section: casos
action_title: ""
position: 12
status: draft
evidences: []
content:
  eyebrow: ""
  subtitle: ""
  body_html: |
    <style>
      .s12.anexo-slide .body { top: 120px !important; bottom: 90px !important; overflow: visible !important; }
      .body > .s12 { padding-top: 0; max-width: 1440px; display: flex; flex-direction: column; gap: 14px; font-family: var(--sans); height: 100%; box-sizing: border-box; }
      .s12 .eyebrow-line { font-family: var(--mono); font-size: 13px; font-weight: 500; letter-spacing: 0.08em; color: var(--mute); }
      .s12 .setup { font-size: 22px; font-weight: 400; line-height: 1.4; color: var(--ink); }
      .s12 .observation { font-size: 22px; font-weight: 400; line-height: 1.4; color: var(--ink); }
      .s12 .rule { height: 1px; background: var(--rule); }
      .s12 .section-h { font-family: var(--mono); font-size: 13px; font-weight: 700; color: var(--ink); letter-spacing: 0.1em; text-transform: uppercase; margin-bottom: 10px; }
      .s12 .hoy-flow { display: grid; grid-template-columns: 1fr auto 1.6fr auto 1.4fr auto 1fr; column-gap: 24px; row-gap: 0; align-items: start; }
      .s12 .hoy-flow .stage-h { font-size: 22px; font-weight: 600; color: var(--ink); margin-bottom: 12px; }
      .s12 .hoy-flow .arrow { font-family: var(--mono); font-size: 20px; color: var(--ink); padding-top: 2px; line-height: 1; }
      .s12 .hoy-flow .items { font-size: 18px; color: var(--ink-soft); line-height: 1.55; }
      .s12 .closing-text { font-size: 16px; color: var(--ink); line-height: 1.45; margin-top: 12px; }
      .s12 .synthesis { font-size: 20px; font-weight: 400; line-height: 1.5; color: var(--ink); max-width: 1320px; }
      .s12 .synthesis .accent { color: var(--coral); }
      .s12 .cifras { display: flex; flex-direction: column; gap: 4px; padding-top: 4px; }
      .s12 .bottom-group { margin-top: 40px; display: flex; flex-direction: column; gap: 14px; }
      .s12 .cifras .cifra-row { display: grid; grid-template-columns: auto 1fr auto; column-gap: 20px; align-items: center; }
      .s12 .cifras .cifra-label { font-family: var(--mono); font-size: 13px; font-weight: 500; color: var(--mute); letter-spacing: 0.08em; text-transform: uppercase; white-space: nowrap; }
      .s12 .cifras .cifra-line { height: 1px; background: var(--rule); }
      .s12 .cifras .cifra-value { font-family: var(--mono); font-size: 20px; font-weight: 700; color: var(--ink); white-space: nowrap; letter-spacing: -0.005em; }
    </style>
    <div class="s12">
      <div class="eyebrow-line">CASO C · Cuenta de ahorros empresarial</div>
      <div class="setup">Una empresa nueva quiere abrir una cuenta de ahorros mediante un proceso 100% digital. La cuenta de ahorros debe estar asociada al NIT.</div>

      <div class="rule"></div>

      <div class="observation">Sigue siendo una operación regulada y fragmentada.</div>

      <div class="rule"></div>

      <div>
        <div class="section-h">Hoy · proceso fragmentado</div>
        <div class="hoy-flow">
          <div>
            <div class="stage-h">Solicitud</div>
            <div class="items"></div>
          </div>
          <div class="arrow">→</div>
          <div>
            <div class="stage-h">Documentos</div>
            <div class="items">Cámara de comercio<br>RUT<br>Composición accionaria<br>Balance inicial<br>Tarjeta profesional del contador<br>Antecedentes del contador</div>
          </div>
          <div class="arrow">→</div>
          <div>
            <div class="stage-h">Validación</div>
            <div class="items">Representante legal<br>Beneficiarios finales<br>Riesgo / cumplimiento<br>Revisión humana</div>
          </div>
          <div class="arrow">→</div>
          <div>
            <div class="stage-h">Activación</div>
            <div class="items">Cuenta lista para operar</div>
          </div>
        </div>
      </div>

      <div class="bottom-group">
        <div class="rule"></div>

        <div>
          <div class="section-h">Lo que cambia con deep agents</div>
          <div class="synthesis">Un deep agent puede sostener la operación completa — reúne requisitos, verifica documentos, consulta sistemas, valida estados, escala excepciones y deja evidencia. No es atención automatizada: es <span class="accent">operación interna asistida por agentes</span>.</div>
        </div>

        <div class="cifras">
        <div class="cifra-row">
          <span class="cifra-label">Sociedades nuevas con NIT PJ / año</span>
          <span class="cifra-line"></span>
          <span class="cifra-value">~82.500</span>
        </div>
        <div class="cifra-row">
          <span class="cifra-label">Ventas anualizadas potenciales</span>
          <span class="cifra-line"></span>
          <span class="cifra-value">COP $2–4 billones</span>
        </div>
        </div>
      </div>
    </div>
  caption: ""
---

# Caso C · cuenta de ahorros empresarial

Proceso fragmentado vs operación sostenida por deep agent.
