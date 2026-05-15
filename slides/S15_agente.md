---
slide_id: S15
slide_type: anexo
section: marco
action_title: "La IA del Entorno 02 tiene muchas formas."
position: 15
status: draft
evidences: []
content:
  eyebrow: ""
  subtitle: ""
  body_html: |
    <style>
      .s15.anexo-slide .body { top: 230px !important; bottom: 90px !important; overflow: visible !important; }
      .body > .s15 { padding-top: 0; max-width: 1400px; margin: 0 auto; display: flex; flex-direction: column; gap: 28px; }
      .s15 .grid { display: grid; grid-template-columns: repeat(4, 1fr); gap: 24px; align-items: start; }
      .s15 .cell { display: flex; flex-direction: column; align-items: center; text-align: center; padding: 14px 12px 18px; border: 1px solid var(--rule); border-radius: 6px; background: var(--bg); }
      .s15 .cell.coral { border: 2px solid var(--coral); padding: 13px 11px 17px; }
      .s15 .cell img { width: 100%; max-width: 200px; height: auto; display: block; mix-blend-mode: multiply; }
      .s15 .cell .k { font-family: var(--mono); font-size: 22px; font-weight: 700; color: var(--ink); letter-spacing: -0.005em; margin-top: 6px; }
      .s15 .cell.coral .k { color: var(--coral); }
      .s15 .cell .v { font-size: 24px; color: var(--mute); line-height: 1.3; margin-top: 8px; min-height: 90px; }
      .s15 .cell.coral .v { color: var(--ink); font-weight: 500; }
      .s15 .quote { font-size: 26px; font-weight: 400; color: var(--ink); font-style: italic; line-height: 1.5; max-width: 1280px; margin: 0 auto; text-align: center; }
      .s15 .quote .q { color: var(--coral); font-style: normal; }
      .s15 .cite { font-family: var(--mono); font-size: 12px; color: var(--mute); margin-top: 8px; text-align: center; }
    </style>
    <div class="s15">
      <div class="grid">
        <div class="cell">
          <img src="../assets/s11_chatbot.png" alt="Chatbot" />
          <div class="k">Chatbot</div>
          <div class="v">conversa, responde</div>
        </div>
        <div class="cell">
          <img src="../assets/s11_copilot.png" alt="Copilot" />
          <div class="k">Copilot</div>
          <div class="v">sugiere · el humano ejecuta</div>
        </div>
        <div class="cell">
          <img src="../assets/s11_workflow.png" alt="Workflow" />
          <div class="k">Workflow</div>
          <div class="v">ejecuta una secuencia predefinida</div>
        </div>
        <div class="cell coral">
          <img src="../assets/s11_agente.png" alt="Agente" />
          <div class="k">AGENTE</div>
          <div class="v">decide su propio camino y usa herramientas dinámicamente</div>
        </div>
      </div>
      <div>
        <div class="quote">
          <span class="q">«</span> Los agentes son sistemas donde los LLMs dirigen dinámicamente sus propios procesos y uso de herramientas, manteniendo control sobre cómo cumplen las tareas. <span class="q">»</span>
        </div>
        <div class="cite">─ Anthropic, Building Effective Agents (dic 2024)</div>
      </div>
    </div>
  caption: ""
---

# Qué es un agente

Taxonomía visual de las cuatro formas de IA en el Entorno 02. Cada celda lleva una ilustración:
- Chatbot: robot con burbujas de diálogo
- Copilot: robot sugiriendo a humano que opera el panel
- Workflow: robot ejecutando pasos predefinidos en pizarra
- AGENTE: robot con tools/skills/memory/security alrededor (coral · diferenciador clave)

Coral solo en la celda AGENTE — única llamada visual. Cita de Anthropic abajo cierra la definición canónica.
