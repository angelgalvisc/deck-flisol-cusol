---
slide_id: S20
slide_type: anexo
section: mejora
action_title: "Autoresearch Engineering."
position: 20
status: draft
evidences: []
content:
  eyebrow: ""
  subtitle: ""
  body_html: |
    <style>
      .s20.anexo-slide .body { top: 230px !important; bottom: 90px !important; overflow: visible !important; }
      .body > .s20 { padding-top: 0; max-width: 1300px; display: flex; flex-direction: column; height: 100%; box-sizing: border-box; font-family: var(--sans); }
      .s20 .intro { font-size: 20px; font-weight: 400; color: var(--ink); line-height: 1.45; margin-bottom: 22px; }
      .s20 .section-h { font-family: var(--mono); font-size: 13px; font-weight: 700; color: var(--mute); letter-spacing: 0.08em; text-transform: uppercase; margin-bottom: 10px; margin-top: 14px; }
      .s20 .primitives { margin-bottom: 4px; }
      .s20 .primitive { display: grid; grid-template-columns: 40px 240px 1fr; column-gap: 16px; padding: 4px 0; align-items: baseline; }
      .s20 .primitive .n { font-size: 18px; font-weight: 600; color: var(--coral); }
      .s20 .primitive .k { font-size: 18px; font-weight: 600; color: var(--ink); }
      .s20 .primitive .v { font-size: 18px; font-weight: 400; color: var(--ink); }
      .s20 .results { margin-bottom: 4px; }
      .s20 .result { margin-bottom: 14px; }
      .s20 .result .who { font-size: 18px; font-weight: 600; color: var(--ink); margin-bottom: 4px; }
      .s20 .result .data { font-size: 18px; font-weight: 400; color: var(--ink); line-height: 1.5; margin-left: 16px; }
      .s20 .result .stars { font-family: var(--mono); font-size: 15px; color: var(--mute); }
      .s20 .closing { margin-top: auto; font-size: 22px; color: var(--ink); line-height: 1.45; font-weight: 500; }
      .s20 .closing .insight { color: var(--coral); }
    </style>
    <div class="s20">
      <div class="intro">
        El patrón donde el agente se mejora a sí mismo:
        propone, prueba, mide, conserva lo que mejora, descarta lo que no.
      </div>
      <div class="section-h">Las 3 primitivas · Karpathy, mar 2026</div>
      <div class="primitives">
        <div class="primitive"><span class="n">1.</span><span class="k">Archivo editable</span><span class="v">un solo archivo que el agente puede modificar</span></div>
        <div class="primitive"><span class="n">2.</span><span class="k">Métrica escalar</span><span class="v">un solo número objetivo que decide si mejoró</span></div>
        <div class="primitive"><span class="n">3.</span><span class="k">Ciclo con tiempo fijo</span><span class="v">cada experimento dura lo mismo</span></div>
      </div>
      <div class="section-h">Resultados públicos</div>
      <div class="results">
        <div class="result">
          <div class="who">Karpathy (mar 2026)</div>
          <div class="data">
            · 700 experimentos en 2 días &nbsp;·&nbsp; 20 mejoras genuinas &nbsp;·&nbsp; +11% speedup sobre código ya optimizado
          </div>
        </div>
        <div class="result">
          <div class="who">Shopify (Tobi Lütke, CEO)</div>
          <div class="data">
            · Liquid (motor de tiendas Shopify) &nbsp;·&nbsp; <strong>+53% más rápido</strong> &nbsp;·&nbsp; 40+ métricas operativas en Shopify, todas mejoradas<br>
            Open source: <span class="stars">github.com/karpathy/autoresearch · 11.7k stars</span>
          </div>
        </div>
      </div>
      <div class="closing">
        El harness sostiene el trabajo. Autoresearch lo mejora <span class="insight">iterativamente para optimizar una métrica</span>.
      </div>
    </div>
  caption: ""
---

# Autoresearch Engineering

Fiel a `propuesta_visual.md` slide 16.
