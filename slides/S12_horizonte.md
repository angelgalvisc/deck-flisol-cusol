---
slide_id: S12
slide_type: anexo
section: evidencia
action_title: "El horizonte de tarea de los agentes se expande."
position: 12
status: draft
evidences: []
content:
  eyebrow: ""
  subtitle: "La frontera ya no es solo responder mejor. Es sostener trabajo útil durante más tiempo."
  body_html: |
    <style>
      .s12.anexo-slide .body { top: 230px !important; bottom: 90px !important; overflow: visible !important; }
      .body > .s12 { padding-top: 0; display: flex; flex-direction: column; font-family: var(--sans); }
      .s12 .chart { display: flex; justify-content: center; }
      .s12 .chart svg { width: 1200px; max-width: 100%; height: auto; }
      .s12 .below { display: flex; flex-direction: column; gap: 12px; margin-top: 10px; }
      .s12 .row-1 { display: grid; grid-template-columns: 820px 1fr; gap: 40px; align-items: start; }
      .s12 .read-box { border-left: 2px solid var(--coral); padding: 10px 14px; }
      .s12 .read-box .h { font-family: var(--mono); font-size: 12px; font-weight: 700; color: var(--coral); letter-spacing: 0.1em; text-transform: uppercase; margin-bottom: 4px; }
      .s12 .read-box .b { font-size: 15px; color: var(--ink); line-height: 1.45; }
      .s12 .sources { font-family: var(--mono); font-size: 11px; color: var(--mute); line-height: 1.5; padding-top: 4px; }
      .s12 .sources .h { font-weight: 700; color: var(--mute); letter-spacing: 0.1em; text-transform: uppercase; margin-bottom: 4px; }
      .s12 .insight { font-size: 18px; font-weight: 500; color: var(--ink); line-height: 1.4; }
    </style>
    <div class="s12">
      <div class="chart">
        <svg role="img" aria-labelledby="s10-title s10-desc" viewBox="0 0 1320 500" preserveAspectRatio="xMidYMid meet">
          <title id="s10-title">Horizonte de tarea al 50% de éxito (METR TH1.1)</title>
          <desc id="s10-desc">Eje X temporal mar 2023 a feb 2026. Eje Y logarítmico de 1 minuto a 100 horas. Modelos pre-frontera muted; Opus 4.6 y Mythos resaltados en coral. Líneas de referencia en 8h y 40h.</desc>

          <line x1="120" y1="60" x2="120" y2="420" stroke="#0F0E12" stroke-width="1"/>
          <line x1="120" y1="420" x2="1140" y2="420" stroke="#0F0E12" stroke-width="1"/>

          <g font-family="SF Mono, JetBrains Mono, monospace" font-size="18" fill="#56555A">
            <text x="108" y="425" text-anchor="end">1min</text>
            <text x="108" y="325" text-anchor="end">10min</text>
            <text x="108" y="240" text-anchor="end">1h</text>
            <text x="108" y="145" text-anchor="end">10h</text>
            <text x="108" y="65" text-anchor="end">100h</text>
          </g>

          <g stroke="#A1A5AA" stroke-width="0.8" stroke-dasharray="3,4">
            <line x1="120" y1="170" x2="1140" y2="170"/>
            <line x1="120" y1="100" x2="1140" y2="100"/>
          </g>
          <g font-family="SF Mono, JetBrains Mono, monospace" font-size="13" fill="#56555A">
            <text x="128" y="164">8h · jornada</text>
            <text x="128" y="94">40h · semana</text>
          </g>

          <g>
            <circle cx="180" cy="368" r="5" fill="#56555A"/>
            <circle cx="380" cy="252" r="5" fill="#56555A"/>
            <circle cx="500" cy="215" r="5" fill="#56555A"/>
            <circle cx="620" cy="210" r="5" fill="#56555A"/>
            <circle cx="780" cy="178" r="5" fill="#56555A"/>
          </g>
          <g font-family="SF Mono, JetBrains Mono, monospace" font-size="16" fill="#56555A">
            <text x="192" y="372">GPT-4 0314 · 3.5min</text>
            <text x="392" y="256">Claude 3.7 · 59m</text>
            <text x="512" y="219">o3 · 2h01m</text>
            <text x="632" y="214">GPT-5 · 2h17m</text>
            <text x="792" y="182">Opus 4.5 · 4h49m</text>
          </g>

          <circle cx="940" cy="135" r="9" fill="#DD4B29"/>
          <text x="956" y="128" font-family="-apple-system, BlinkMacSystemFont, sans-serif" font-size="22" font-weight="700" fill="#DD4B29">Opus 4.6 · 14.5h</text>
          <circle cx="1080" cy="92" r="9" fill="#DD4B29"/>
          <text x="1094" y="98" font-family="-apple-system, BlinkMacSystemFont, sans-serif" font-size="22" font-weight="700" fill="#DD4B29">Mythos · 16h+</text>

          <g font-family="SF Mono, JetBrains Mono, monospace" font-size="18" fill="#56555A">
            <text x="180" y="450" text-anchor="middle">mar 2023</text>
            <text x="500" y="450" text-anchor="middle">2024</text>
            <text x="780" y="450" text-anchor="middle">2025</text>
            <text x="1080" y="450" text-anchor="middle">feb 2026</text>
          </g>

          <text x="120" y="488" font-family="SF Mono, JetBrains Mono, monospace" font-size="14" fill="#56555A">METR TH1.1 · horizonte se duplica cada ~7 meses (post-2023: ~4.3 meses)</text>
        </svg>
      </div>

      <div class="below">
        <div class="row-1">
          <div class="read-box">
            <div class="h">Cómo leer el eje Y</div>
            <div class="b">Cada punto = duración humana estimada de la tarea en que el modelo logra 50% de éxito. Mide dificultad de tarea — no tiempo real de ejecución de la IA.</div>
          </div>
          <div class="sources">
            <div class="h">Fuentes</div>
            METR, Task-Completion Time Horizons of Frontier AI Models, 2026<br>
            METR, Time Horizon 1.1, 2026<br>
            Kwa et al., Measuring AI Ability to Complete Long Software Tasks, arXiv, 2025/2026<br>
            * Mythos Preview: METR LinkedIn post, evaluación temprana marzo 2026
          </div>
        </div>
        <div class="insight">Si el horizonte crece, el trabajo deja de parecer una consulta. Empieza a parecerse a una operación.</div>
      </div>
    </div>
  caption: ""
---

# Horizonte de tarea

Versión data-viz purist con líneas de referencia, anotación de doubling time y modelos pre-frontera muted.
