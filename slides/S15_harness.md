---
slide_id: S15
slide_type: anexo
section: marco
action_title: "Qué es un harness."
position: 15
status: draft
evidences: []
content:
  eyebrow: ""
  subtitle: ""
  body_html: |
    <style>
      .s15.anexo-slide .body { top: 220px !important; bottom: 90px !important; overflow: visible !important; }
      .body > .s15 { padding-top: 0; max-width: 1440px; display: flex; flex-direction: column; height: 100%; box-sizing: border-box; }
      .s15 .main-row { display: grid; grid-template-columns: 1fr 1.05fr; column-gap: 60px; align-items: start; }
      .s15 .components-label { font-size: 18px; color: var(--ink); margin-bottom: 16px; font-weight: 500; }
      .s15 .row { display: grid; grid-template-columns: 200px 1fr; gap: 20px; padding: 10px 0; align-items: baseline; }
      .s15 .row .k { font-family: var(--mono); font-size: 18px; font-weight: 700; color: var(--ink); letter-spacing: 0.04em; }
      .s15 .row .v { font-size: 18px; color: var(--ink); line-height: 1.4; }
      .s15 .defs { display: flex; flex-direction: column; gap: 12px; }
      .s15 .def { border-left: 2px solid var(--coral); padding: 6px 14px; }
      .s15 .def .src { font-family: var(--mono); font-size: 13px; font-weight: 700; color: var(--coral); letter-spacing: 0.12em; text-transform: uppercase; margin-bottom: 6px; }
      .s15 .def .q { font-size: 18px; font-style: italic; color: var(--ink); line-height: 1.4; }
      .s15 .closing { font-size: 22px; font-weight: 500; color: var(--ink); line-height: 1.4; margin-top: auto; padding-top: 20px; }
      .s15 .closing .insight { color: var(--coral); }
    </style>
    <div class="s15">
      <div class="main-row">
        <div>
          <div class="components-label">Los 4 componentes mínimos:</div>
          <div class="components">
            <div class="row"><span class="k">PLANEACIÓN</span><span class="v">descomposición de tareas largas en pasos verificables</span></div>
            <div class="row"><span class="k">MEMORIA</span><span class="v">contexto activo + persistencia entre sesiones</span></div>
            <div class="row"><span class="k">HERRAMIENTAS</span><span class="v">APIs, MCP, CLIs, search, code exec</span></div>
            <div class="row"><span class="k">GUARDRAILS</span><span class="v">sandbox, límites de gasto, auditoría</span></div>
          </div>
        </div>
        <div class="defs">
          <div class="def">
            <div class="src">Mitchell Hashimoto</div>
            <div class="q">Cada vez que encuentras que un agente comete un error, diseñas una solución para que ese agente no vuelva a cometer ese mismo error.</div>
          </div>
          <div class="def">
            <div class="src">OpenAI</div>
            <div class="q">Harness engineering es diseñar entornos, intención y bucles de retroalimentación para que los agentes ejecuten trabajo confiable.</div>
          </div>
          <div class="def">
            <div class="src">LangChain · Vivek Trivedy</div>
            <div class="q">Agent = Model + Harness.</div>
          </div>
          <div class="def">
            <div class="src">Anthropic</div>
            <div class="q">El harness es el sistema de instrucciones, restricciones y orquestación que permite que un modelo actúe como agente.</div>
          </div>
        </div>
      </div>
      <div class="closing">
        El modelo es el motor. <span class="insight">El harness es lo que lo vuelve confiable.</span>
      </div>
    </div>
  caption: ""
---

# Qué es un harness

Fiel a `propuesta_visual.md` slide 12.
