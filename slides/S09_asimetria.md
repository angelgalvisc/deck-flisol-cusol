---
slide_id: S09
slide_type: anexo
section: marco
action_title: "Asimetría de la verificación."
position: 9
status: draft
evidences: []
content:
  eyebrow: ""
  subtitle: "La IA automatiza primero las tareas que puede verificar bien."
  body_html: |
    <style>
      .s09.anexo-slide .body { top: 300px !important; bottom: 100px !important; overflow: visible !important; }
      .s09 { padding-top: 0; }
      .s09 .chart { display: flex; justify-content: center; padding: 24px 0; }
      .s09 .source { font-size: 13px; color: var(--mute); margin-top: 24px; font-family: var(--mono); }
      .s09 .source em { font-style: italic; }
    </style>
    <div class="s09">
      <div class="chart">
        <svg role="img" aria-labelledby="s07-title s07-desc" viewBox="0 0 1100 270" preserveAspectRatio="xMidYMax meet" style="width: 1100px; max-width: 100%;">
          <title id="s07-title">Asimetría de la verificación</title>
          <desc id="s07-desc">Cinco dominios distribuidos sobre un eje de verificabilidad de baja a alta. Legal y Riesgo a la izquierda con puntos pequeños. Pagos al centro. Código y Matemáticas a la derecha con puntos grandes.</desc>
          <g font-family="SF Mono, JetBrains Mono, monospace" font-size="22" fill="#0F0E12" text-anchor="middle" font-weight="500">
            <text x="110" y="96">Legal</text>
            <text x="330" y="96">Riesgo</text>
            <text x="550" y="96">Pagos</text>
            <text x="770" y="96">Código</text>
            <text x="990" y="96">Matemáticas</text>
          </g>
          <circle cx="110" cy="160" r="6"  fill="#0F0E12"/>
          <circle cx="330" cy="160" r="9"  fill="#0F0E12"/>
          <circle cx="550" cy="160" r="14" fill="#DD4B29"/>
          <circle cx="770" cy="160" r="18" fill="#0F0E12"/>
          <circle cx="990" cy="160" r="20" fill="#0F0E12"/>
          <line x1="80" y1="200" x2="1020" y2="200" stroke="#0F0E12" stroke-width="1"/>
          <g font-family="SF Mono, JetBrains Mono, monospace" font-size="22" fill="#56555A" font-weight="500">
            <text x="80"  y="238">baja</text>
            <text x="550" y="238" text-anchor="middle">Verificabilidad</text>
            <text x="1020" y="238" text-anchor="end">alta</text>
          </g>
        </svg>
      </div>
      <div class="source">Basado en: Jason Wei<br><em>"Asymmetry of verification and verifier's law"</em></div>
    </div>
  caption: ""
---

# Asimetría de la verificación

Fiel a `propuesta_visual.md` slide 7.
