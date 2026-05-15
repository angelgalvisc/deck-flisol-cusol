---
slide_id: S10
slide_type: anexo
section: casos
action_title: ""
position: 10
status: draft
evidences: []
content:
  eyebrow: "CASO B"
  subtitle: ""
  body_html: |
    <style>
      .s10.anexo-slide .body { top: 170px !important; bottom: 90px !important; overflow: visible !important; }
      .body > .s10 { padding-top: 0; max-width: 1440px; display: flex; flex-direction: column; justify-content: space-between; height: 100%; box-sizing: border-box; font-family: var(--sans); gap: 18px; }
      .s10 .top-row { display: grid; grid-template-columns: 1fr 1fr; column-gap: 80px; align-items: start; }
      .s10 .setup,
      .s10 .pivote { font-size: 22px; font-weight: 400; line-height: 1.5; color: var(--ink); }
      .s10 .top-row .pivote { text-align: right; }
      .s10 .track { display: grid; grid-template-columns: auto 1fr auto; column-gap: 32px; row-gap: 10px; align-items: center; }
      .s10 .track .l-start, .s10 .track .l-end { font-size: 14px; font-weight: 600; color: var(--mute); letter-spacing: 0.12em; text-transform: uppercase; }
      .s10 .track .l-end { justify-self: end; }
      .s10 .track .node-start, .s10 .track .node-end { font-size: 22px; font-weight: 600; color: var(--ink); }
      .s10 .track .node-end { justify-self: end; }
      .s10 .track .arrow { grid-column: 2; }
      .s10 .track .arrow svg { display: block; width: 100%; height: 12px; }
      .s10 .flows { display: flex; flex-direction: column; gap: 14px; max-width: 960px; margin: 0 auto; width: 100%; }
      .s10 .flow-row { display: grid; grid-template-columns: 160px 1fr; column-gap: 36px; align-items: baseline; padding: 16px 24px; border: 1px solid transparent; border-radius: 4px; }
      .s10 .flow-row.ready { border-color: rgba(221, 75, 41, 0.45); }
      .s10 .flow-label { font-size: 14px; font-weight: 600; color: var(--ink); letter-spacing: 0.12em; text-transform: uppercase; padding-top: 6px; }
      .s10 .flow-row.ready .flow-label { color: var(--coral); }
      .s10 .flow-content { display: flex; flex-direction: column; gap: 4px; }
      .s10 .flow-steps,
      .s10 .flow-gloss { font-size: 22px; font-weight: 500; color: var(--ink); line-height: 1.4; }
      .s10 .cifra-row { display: flex; justify-content: space-between; align-items: baseline; gap: 24px; font-size: 20px; flex-wrap: wrap; }
      .s10 .cifra-label { color: var(--mute); }
      .s10 .cifra-value { color: var(--ink); font-weight: 700; font-size: 22px; letter-spacing: -0.005em; }
    </style>
    <div class="s10">
      <div class="top-row">
        <div class="setup">Un restaurante vende por WhatsApp.<br>Antes de preparar y despachar, necesita confirmar el pago.</div>
        <div class="pivote">El pedido llega por conversación.<br>La verificación del pago sigue siendo manual.</div>
      </div>
      <div class="track">
        <span class="l-start">Mismo inicio</span>
        <span class="spacer"></span>
        <span class="l-end">Mismo final</span>
        <span class="node-start">pedido WhatsApp</span>
        <span class="arrow"><svg viewBox="0 0 1000 12" preserveAspectRatio="none"><line x1="0" y1="6" x2="988" y2="6" stroke="#0F0E12" stroke-width="1" vector-effect="non-scaling-stroke"/><polygon points="988,1 1000,6 988,11" fill="#0F0E12"/></svg></span>
        <span class="node-end">despacho</span>
      </div>
      <div class="flows">
        <div class="flow-row">
          <div class="flow-label">Hoy</div>
          <div class="flow-content">
            <div class="flow-steps">transferencia &nbsp;→&nbsp; pantallazo &nbsp;→&nbsp; revisión humana</div>
            <div class="flow-gloss">pago existe, pero no como estado verificable</div>
          </div>
        </div>
        <div class="flow-row ready">
          <div class="flow-label">Agent-ready</div>
          <div class="flow-content">
            <div class="flow-steps">cobro Push/QR/link &nbsp;→&nbsp; estado de pago verificable</div>
            <div class="flow-gloss">el agente puede validar monto, referencia y estado</div>
          </div>
        </div>
      </div>
      <div class="cifra-row">
        <span class="cifra-label">Ventas originadas o cerradas por canales conversacionales</span>
        <span class="cifra-value">~COP $20–30 billones</span>
      </div>
    </div>
  caption: ""
---
