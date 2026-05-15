---
slide_id: S07
slide_type: anexo
section: casos
action_title: "Cómo un agente le habla a Stripe en 2026."
position: 7
status: draft
evidences: []
content:
  eyebrow: ""
  subtitle: "Hay dos interfaces. Ambas son nativas para agentes."
  body_html: |
    <style>
      .s07.anexo-slide .body { top: 320px !important; bottom: 100px !important; overflow: visible !important; }
      .s07 { padding-top: 0; }
      .s07 .cols { display: grid; grid-template-columns: 1fr 1px 1fr; gap: 28px; align-items: start; }
      .s07 .divider-v { background: var(--rule); width: 1px; height: 260px; }
      .s07 .col-h { font-family: var(--mono); font-size: 16px; font-weight: 700; color: var(--ink); margin-bottom: 10px; }
      .s07 .codebox { background: #F2F2F2; border-radius: 4px; padding: 14px 16px; font-family: var(--mono); font-size: 13px; color: var(--ink); line-height: 1.7; margin-bottom: 10px; white-space: pre-wrap; }
      .s07 .codebox .c { color: #4D8060; }
      .s07 .code-note { font-family: var(--mono); font-size: 13px; color: var(--ink-soft); margin-bottom: 12px; }
      .s07 .rule { height: 1px; background: var(--rule); margin: 16px 0; }
      .s07 .footer { font-size: 22px; font-weight: 400; color: var(--ink); line-height: 1.45; }
      .s07 .footer .mono { font-family: var(--mono); font-size: 20px; }
      .s07 .footer .coral-line { color: var(--coral); font-family: var(--mono); font-size: 20px; }
    </style>
    <div class="s07">
      <div class="cols">
        <div>
          <div class="col-h">CLI — comando directo</div>
          <div class="codebox">$ stripe get          <span class="c"># interfaz directa · el agente ya sabe qué llamar</span>
      /v1/payment_intents/  <span class="c"># objeto Stripe: PaymentIntent · estado operativo del pago</span>
      pi_3QxYzAbCdEf...     <span class="c"># id del pago que quiero verificar</span></div>
          <div class="code-note">El agente empieza por la ruta.</div>
        </div>
        <div class="divider-v"></div>
        <div>
          <div class="col-h">MCP — protocolo descubrible</div>
          <div class="codebox">tool: fetch_stripe_resources  <span class="c"># herramienta disponible expuesta por Stripe MCP</span>
    resource: payment_intent/     <span class="c"># objeto específico que contiene el estado</span>
      pi_3QxYzAbCdEf...           <span class="c"># id del pago que quiero verificar</span></div>
          <div class="code-note">El agente empieza por la tarea, no por la ruta.</div>
        </div>
      </div>
      <div class="rule"></div>
      <div class="footer">
        En cualquiera de los dos casos el sistema valida: <span class="mono">estado · monto · moneda · referencia</span>.<br>
        Si coincide, autoriza. &nbsp;&nbsp;<span class="coral-line">Webhook: payment_intent.succeeded</span>
      </div>
    </div>
  caption: ""
---

# CLI y MCP

Fiel a `propuesta_visual.md` slide 5.
