---
slide_id: S14
slide_type: anexo
section: marco
action_title: "Dónde los agentes realmente crean valor."
position: 14
status: draft
evidences: []
content:
  eyebrow: ""
  subtitle: "Importan cuando entran en cadenas verificables de decisión, ejecución y consecuencia."
  body_html: |
    <style>
      .s14.anexo-slide .body { top: 280px !important; bottom: 60px !important; overflow: visible !important; }
      .s14 { padding-top: 0; display: flex; justify-content: center; }
      .s14 .matrix-wrap { position: relative; }
      .s14 .y-axis { position: absolute; left: -64px; top: 0; height: 460px; display: flex; flex-direction: column; justify-content: space-between; font-family: var(--mono); font-size: 20px; color: var(--mute); }
      .s14 .y-label { writing-mode: vertical-rl; transform: rotate(180deg); position: absolute; left: -106px; top: 110px; font-family: var(--mono); font-size: 19px; color: var(--mute); letter-spacing: 0.05em; }
      .s14 .matrix { display: grid; grid-template-columns: 1fr 1fr; grid-template-rows: 1fr 1fr; width: 1140px; height: 460px; border: 1px solid var(--ink); }
      .s14 .q { padding: 20px 26px; border-right: 1px solid var(--ink); border-bottom: 1px solid var(--ink); }
      .s14 .q.right { border-right: none; }
      .s14 .q.bottom { border-bottom: none; }
      .s14 .q.coral { background: rgba(221, 75, 41, 0.08); }
      .s14 .q-label { font-family: var(--mono); font-size: 17px; font-weight: 700; color: var(--ink); margin-bottom: 12px; letter-spacing: 0.04em; }
      .s14 .q-label.coral { color: var(--coral); }
      .s14 .q-list { font-size: 19px; color: var(--ink); line-height: 1.5; list-style: none; padding: 0; margin: 0; }
      .s14 .q-list li { margin-bottom: 2px; }
      .s14 .x-axis { display: flex; justify-content: space-between; align-items: center; width: 1140px; margin-top: 16px; font-family: var(--mono); font-size: 20px; color: var(--mute); }
      .s14 .x-axis span:nth-child(2) { font-size: 19px; letter-spacing: 0.05em; }
    </style>
    <div class="s14">
      <div class="matrix-wrap">
        <div class="y-label">Complejidad operativa</div>
        <div class="y-axis"><span>alta</span><span>baja</span></div>
        <div class="matrix">
          <div class="q">
            <div class="q-label">Juicio humano</div>
            <ul class="q-list">
              <li>alta ambigüedad</li>
              <li>criterio experto</li>
              <li>baja estandarización</li>
            </ul>
          </div>
          <div class="q right coral">
            <div class="q-label coral">ZONA DE MAYOR VALOR PARA AGENTES</div>
            <ul class="q-list">
              <li>generación de código con tests automáticos</li>
              <li>refactoring guiado por métricas</li>
              <li>diagnóstico y triage de bugs</li>
              <li>análisis de datos con métrica clara</li>
              <li>investigación con citas verificables</li>
            </ul>
          </div>
          <div class="q bottom">
            <div class="q-label">Uso conversacional</div>
            <ul class="q-list">
              <li>atención</li>
              <li>orientación</li>
              <li>respuesta</li>
            </ul>
          </div>
          <div class="q right bottom">
            <div class="q-label">Automatización simple</div>
            <ul class="q-list">
              <li>reglas claras</li>
              <li>tareas repetibles</li>
              <li>bajo riesgo</li>
              <li>ejecución lineal</li>
            </ul>
          </div>
        </div>
        <div class="x-axis">
          <span>baja</span>
          <span>Verificabilidad</span>
          <span>alta</span>
        </div>
      </div>
    </div>
  caption: ""
---
