---
slide_id: S17
slide_type: anexo
section: marco
action_title: "Por qué pasar de agentes a deep agents."
position: 17
status: draft
evidences: []
content:
  eyebrow: ""
  subtitle: "Cuando el horizonte de tarea crece, un agente simple deja de bastar."
  body_html: |
    <style>
      .s17.anexo-slide .body { top: 280px !important; bottom: 100px !important; overflow: visible !important; }
      .s17 { padding-top: 0; }
      .s17 .top-row { display: grid; grid-template-columns: 1fr auto; column-gap: 64px; align-items: center; margin-bottom: 36px; }
      .s17 .stages { display: flex; flex-direction: column; gap: 4px; }
      .s17 .stage { display: grid; grid-template-columns: 320px 70px auto; align-items: baseline; padding: 4px 0; }
      .s17 .stage .k { font-family: var(--sans); font-size: 25px; font-weight: 500; color: var(--ink); }
      .s17 .stage .arrow { font-family: var(--mono); font-size: 22px; color: var(--rule); }
      .s17 .stage .v { font-family: var(--sans); font-size: 25px; color: var(--ink); }
      .s17 .callout { border: 1px solid var(--coral); padding: 28px 32px; max-width: 400px; text-align: center; font-size: 24px; font-weight: 600; color: var(--ink); line-height: 1.35; }
      .s17 .closing { font-size: 18px; color: var(--ink); line-height: 1.55; max-width: 900px; }
      .s17 .closing .insight { color: var(--coral); }
    </style>
    <div class="s17">
      <div class="top-row">
        <div class="stages">
          <div class="stage"><span class="k">más tiempo</span><span class="arrow">──→</span><span class="v">exige planeación</span></div>
          <div class="stage"><span class="k">más contexto</span><span class="arrow">──→</span><span class="v">exige gestión de contexto</span></div>
          <div class="stage"><span class="k">más subtareas</span><span class="arrow">──→</span><span class="v">exige delegación</span></div>
          <div class="stage"><span class="k">más sesiones</span><span class="arrow">──→</span><span class="v">exige memoria</span></div>
          <div class="stage"><span class="k">más herramientas</span><span class="arrow">──→</span><span class="v">exige harness</span></div>
          <div class="stage"><span class="k">más riesgo</span><span class="arrow">──→</span><span class="v">exige evaluación y control</span></div>
        </div>
        <div class="callout">Deep agents = agentes con harness para trabajo largo.</div>
      </div>
      <div class="closing">
        No necesitamos deep agents porque el modelo "piense más".<br>
        Los necesitamos porque el trabajo ya dura más, se ramifica más y se rompe más.<br><br>
        Cuando el horizonte crece, el cuello de botella deja de ser el modelo. Pasa a ser <span class="insight">el sistema que lo contiene</span>.
      </div>
    </div>
  caption: ""
---
