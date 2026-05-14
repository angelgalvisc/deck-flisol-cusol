---
slide_id: S05
slide_type: anexo
section: casos
action_title: ""
position: 5
status: draft
evidences: []
content:
  eyebrow: "CASO B"
  subtitle: ""
  body_html: |
    <style>
      .s05.anexo-slide .body { top: 170px !important; bottom: 90px !important; overflow: visible !important; }
      .body > .s05 { padding-top: 0; max-width: 1440px; display: flex; flex-direction: column; justify-content: space-between; height: 100%; box-sizing: border-box; font-family: var(--sans); gap: 18px; }
      .s05 .top-row { display: grid; grid-template-columns: 1fr 1fr; column-gap: 80px; align-items: start; }
      .s05 .setup,
      .s05 .pivote { font-size: 22px; font-weight: 400; line-height: 1.5; color: var(--ink); }
      .s05 .top-row .pivote { text-align: right; }
      .s05 .track { display: grid; grid-template-columns: auto 1fr auto; column-gap: 32px; row-gap: 10px; align-items: center; }
      .s05 .track .l-start, .s05 .track .l-end { font-size: 14px; font-weight: 600; color: var(--mute); letter-spacing: 0.12em; text-transform: uppercase; }
      .s05 .track .l-end { justify-self: end; }
      .s05 .track .node-start, .s05 .track .node-end { font-size: 22px; font-weight: 600; color: var(--ink); }
      .s05 .track .node-end { justify-self: end; }
      .s05 .track .arrow { grid-column: 2; }
      .s05 .track .arrow svg { display: block; width: 100%; height: 12px; }
      .s05 .flows { display: flex; flex-direction: column; gap: 14px; max-width: 960px; margin: 0 auto; width: 100%; }
      .s05 .flow-row { display: grid; grid-template-columns: 160px 1fr; column-gap: 36px; align-items: baseline; padding: 16px 24px; border: 1px solid transparent; border-radius: 4px; }
      .s05 .flow-row.ready { border-color: rgba(221, 75, 41, 0.45); }
      .s05 .flow-label { font-size: 14px; font-weight: 600; color: var(--ink); letter-spacing: 0.12em; text-transform: uppercase; padding-top: 6px; }
      .s05 .flow-row.ready .flow-label { color: var(--coral); }
      .s05 .flow-content { display: flex; flex-direction: column; gap: 4px; }
      .s05 .flow-steps,
      .s05 .flow-gloss { font-size: 22px; font-weight: 500; color: var(--ink); line-height: 1.4; }
      .s05 .cifra-row { display: flex; justify-content: space-between; align-items: baseline; gap: 24px; font-size: 20px; flex-wrap: wrap; }
      .s05 .cifra-label { color: var(--mute); }
      .s05 .cifra-value { color: var(--ink); font-weight: 700; font-size: 22px; letter-spacing: -0.005em; }
    </style>
    <div class="s05">
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

# Caso B · restaurante

Fiel a `propuesta_visual.md` slide 4.
