---
slide_id: S27
slide_type: anexo
section: marco
action_title: "Cómo evolucionó la ingeniería de IA."
position: 27
status: draft
evidences: []
content:
  eyebrow: ""
  subtitle: "En veinte años pasamos de etiquetar datasets a construir sistemas que diseñan sus propios experimentos."
  body_html: |
    <style>
      .s27.anexo-slide .body { top: 270px !important; bottom: 80px !important; overflow: visible !important; }
      .s27 { padding-top: 0; }
      .s27 .timeline { display: flex; justify-content: center; padding: 24px 0 0 0; }
      .s27 .timeline-grid { display: grid; grid-template-columns: repeat(5, 1fr); width: 1240px; column-gap: 0; position: relative; }
      .s27 .timeline-line { position: absolute; top: 14px; left: 10%; right: 10%; height: 1px; background: var(--ink); z-index: 0; }
      .s27 .col { display: flex; flex-direction: column; align-items: center; text-align: center; position: relative; z-index: 1; padding: 0 6px; }
      .s27 .cap-dot { width: 14px; height: 14px; border-radius: 50%; background: var(--ink); margin-bottom: 18px; }
      .s27 .col.coral .cap-dot { background: var(--coral); width: 18px; height: 18px; margin-bottom: 16px; }
      .s27 .name { font-family: var(--mono); font-size: 17px; font-weight: 700; color: var(--ink); letter-spacing: 0.02em; margin-bottom: 4px; }
      .s27 .verb { font-family: var(--mono); font-size: 15px; color: var(--mute); margin-bottom: 22px; letter-spacing: 0.02em; }
      .s27 .eq { font-family: var(--mono); font-size: 15px; color: var(--ink); line-height: 1.55; min-height: 72px; }
      .s27 .eq em { font-style: italic; color: var(--mute); }
      .s27 .nomen { margin-top: 36px; padding-top: 18px; border-top: 1px solid var(--rule); display: flex; justify-content: center; }
      .s27 .nomen-inner { width: 1240px; }
      .s27 .nomen-h { font-family: var(--mono); font-size: 13px; font-weight: 700; color: var(--ink); letter-spacing: 0.1em; text-transform: uppercase; margin-bottom: 10px; }
      .s27 .nomen-body { font-family: var(--mono); font-size: 13.5px; color: var(--mute); line-height: 1.75; }
      .s27 .nomen-body strong { color: var(--ink); font-weight: 700; }
      .s27 .nomen-body .phase { display: inline-block; min-width: 110px; color: var(--coral); font-weight: 700; }
    </style>
    <div class="s27">
      <div class="timeline">
        <div class="timeline-grid">
          <div class="timeline-line"></div>
          <div class="col">
            <div class="cap-dot"></div>
            <div class="name">data</div>
            <div class="verb">estructura</div>
            <div class="eq">D = {(x,y)}<br>~ P<sub>world</sub></div>
          </div>
          <div class="col">
            <div class="cap-dot"></div>
            <div class="name">model</div>
            <div class="verb">entrena</div>
            <div class="eq">θ* = argmin<sub>θ</sub><br>E<sub>D</sub>[L(f<sub>θ</sub>(x), y)]</div>
          </div>
          <div class="col">
            <div class="cap-dot"></div>
            <div class="name">context</div>
            <div class="verb">cura</div>
            <div class="eq">y ~ P<sub>θ*</sub>(· | c)<br>c = C(q, M<sub>q</sub>, T, E)</div>
          </div>
          <div class="col">
            <div class="cap-dot"></div>
            <div class="name">harness</div>
            <div class="verb">opera</div>
            <div class="eq">a<sub>t</sub> ~ π<sub>θ*</sub>(s<sub>t</sub>, c<sub>t</sub>)<br>o<sub>t</sub> = τ( G(a<sub>t</sub>) )</div>
          </div>
          <div class="col coral">
            <div class="cap-dot"></div>
            <div class="name">autoresearch</div>
            <div class="verb">experimenta</div>
            <div class="eq">Δ ~ π<sub>θ*</sub>(z, A)<br>keep T<sub>Δ</sub>(z) <em>si</em> m' &lt; m</div>
          </div>
        </div>
      </div>
      <div class="nomen">
        <div class="nomen-inner">
          <div class="nomen-h">Nomenclatura</div>
          <div class="nomen-body">
            <span class="phase">data</span> <strong>D</strong> dataset · <strong>x, y</strong> entrada / salida · <strong>P<sub>world</sub></strong> distribución del mundo<br>
            <span class="phase">model</span> <strong>θ</strong> pesos del modelo · <strong>θ*</strong> pesos óptimos tras entrenamiento · <strong>E<sub>D</sub>[·]</strong> esperanza sobre D · <strong>L</strong> función de pérdida · <strong>f<sub>θ</sub></strong> modelo<br>
            <span class="phase">context</span> <strong>(·)</strong> argumento sobre el que se distribuye (placeholder) · <strong>P<sub>θ*</sub></strong> distribución del modelo entrenado · <strong>c</strong> contexto · <strong>C(·)</strong> función de curación · <strong>q</strong> query · <strong>M<sub>q</sub></strong> memoria · <strong>T</strong> tools · <strong>E</strong> evidencia<br>
            <span class="phase">harness</span> <strong>a<sub>t</sub></strong> acción · <strong>π<sub>θ*</sub></strong> política del modelo entrenado · <strong>s<sub>t</sub></strong> estado · <strong>c<sub>t</sub></strong> contexto en t · <strong>o<sub>t</sub></strong> observación · <strong>τ</strong> tool · <strong>G</strong> validación (guardrail) · <strong>t</strong> paso<br>
            <span class="phase">autoresearch</span> <strong>Δ</strong> cambio propuesto · <strong>z</strong> configuración editable · <strong>A</strong> arena (spec + espacio editable + métrica + presupuesto + regla) · <strong>T<sub>Δ</sub>(·)</strong> operación que aplica Δ a z · <strong>m = M(z)</strong> valor de la métrica · <strong>M</strong> métrica
          </div>
        </div>
      </div>
    </div>
  caption: ""
---

# Timeline · evolución de la ingeniería de IA

Slide nuevo, exclusiva del deck Flisol.

Mapa mental: data → model → context → harness → autoresearch.
Cada fase incorporó las variables de la anterior y abrió una nueva. Las ecuaciones son las canónicas del manifiesto Agentic_Engineering (forma compacta para presentación).

Fuente conceptual: manifiesto Agentic_Engineering (8 disciplinas; aquí presentamos las 5 primeras, que cubren el arco de la charla).
