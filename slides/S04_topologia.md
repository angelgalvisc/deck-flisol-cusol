---
slide_id: S04
slide_type: anexo
section: apertura
action_title: "La promesa se mantiene. Los entornos cambian."
position: 4
status: draft
evidences: []
content:
  eyebrow: ""
  subtitle: ""
  body_html: |
    <style>
      .s04.anexo-slide .body { top: 300px !important; bottom: 100px !important; overflow: visible !important; }
      .s04-topo { display: grid; grid-template-columns: 1fr 1px 1fr; gap: 60px; align-items: stretch; padding-top: 0; }
      .s04-topo .divider-v { background: var(--rule); width: 1px; height: 380px; align-self: center; }
      .s04-topo .col { padding: 0 16px; display: flex; flex-direction: column; align-items: flex-start; }
      .s04-topo .h { font-family: var(--mono); font-size: 22px; font-weight: 700; color: var(--ink); margin-bottom: 24px; }
      .s04-topo .diag { display: flex; justify-content: center; align-items: center; width: 100%; min-height: 260px; margin-bottom: 24px; }
      .s04-topo .diag svg { width: 100%; max-width: 500px; height: auto; }
      .s04-topo .sub { font-size: 22px; font-weight: 500; color: var(--ink); align-self: center; text-align: center; max-width: 540px; line-height: 1.35; }
      .s04-topo .sub-coral { font-size: 17px; font-weight: 500; color: var(--coral); align-self: center; text-align: center; max-width: 560px; line-height: 1.4; margin-top: 10px; }
    </style>
    <div class="s04-topo">
      <div class="col">
        <div class="h">ENTORNO 01</div>
        <div class="diag">
          <svg viewBox="0 0 540 320" preserveAspectRatio="xMidYMid meet" role="img" aria-label="Humano y Software conectados por flecha bidireccional">
            <defs>
              <marker id="arrow-start" viewBox="0 0 12 12" refX="2" refY="6" markerWidth="9" markerHeight="9" orient="auto">
                <path d="M 10 1 L 2 6 L 10 11 z" fill="#0F0E12"/>
              </marker>
              <marker id="arrow-end" viewBox="0 0 12 12" refX="10" refY="6" markerWidth="9" markerHeight="9" orient="auto">
                <path d="M 2 1 L 10 6 L 2 11 z" fill="#0F0E12"/>
              </marker>
            </defs>
            <g font-family="-apple-system, BlinkMacSystemFont, 'SF Pro Text', 'Inter', sans-serif" font-size="20" font-weight="500" fill="#0F0E12">
              <rect x="40" y="135" width="150" height="56" rx="4" fill="none" stroke="#0F0E12" stroke-width="1.2"/>
              <text x="115" y="170" text-anchor="middle">Humano</text>
              <rect x="350" y="135" width="150" height="56" rx="4" fill="none" stroke="#0F0E12" stroke-width="1.2"/>
              <text x="425" y="170" text-anchor="middle">Software</text>
              <line x1="200" y1="163" x2="340" y2="163" stroke="#0F0E12" stroke-width="1.6" marker-start="url(#arrow-start)" marker-end="url(#arrow-end)"/>
            </g>
          </svg>
        </div>
        <div class="sub">Solo el humano opera sobre el software.</div>
      </div>
      <div class="divider-v"></div>
      <div class="col">
        <div class="h">ENTORNO 02</div>
        <div class="diag">
          <svg viewBox="0 0 540 320" preserveAspectRatio="xMidYMid meet" role="img" aria-label="Humano e IA conectados con flechas bidireccionales al mismo Software">
            <defs>
              <marker id="arrow-start-2" viewBox="0 0 12 12" refX="2" refY="6" markerWidth="9" markerHeight="9" orient="auto">
                <path d="M 10 1 L 2 6 L 10 11 z" fill="#0F0E12"/>
              </marker>
              <marker id="arrow-end-2" viewBox="0 0 12 12" refX="10" refY="6" markerWidth="9" markerHeight="9" orient="auto">
                <path d="M 2 1 L 10 6 L 2 11 z" fill="#0F0E12"/>
              </marker>
            </defs>
            <g font-family="-apple-system, BlinkMacSystemFont, 'SF Pro Text', 'Inter', sans-serif" font-size="20" font-weight="500" fill="#0F0E12">
              <rect x="20" y="40" width="150" height="56" rx="4" fill="none" stroke="#0F0E12" stroke-width="1.2"/>
              <text x="95" y="75" text-anchor="middle">Humano</text>
              <rect x="20" y="224" width="150" height="56" rx="4" fill="none" stroke="#0F0E12" stroke-width="1.2"/>
              <text x="95" y="259" text-anchor="middle">IA</text>
              <rect x="370" y="132" width="150" height="56" rx="4" fill="none" stroke="#0F0E12" stroke-width="1.2"/>
              <text x="445" y="167" text-anchor="middle">Software</text>
              <line x1="185" y1="85" x2="362" y2="156" stroke="#0F0E12" stroke-width="1.6" marker-start="url(#arrow-start-2)" marker-end="url(#arrow-end-2)"/>
              <line x1="185" y1="235" x2="362" y2="164" stroke="#0F0E12" stroke-width="1.6" marker-start="url(#arrow-start-2)" marker-end="url(#arrow-end-2)"/>
              <line x1="95" y1="100" x2="95" y2="220" stroke="#0F0E12" stroke-width="1.6" marker-start="url(#arrow-start-2)" marker-end="url(#arrow-end-2)"/>
            </g>
          </svg>
        </div>
        <div class="sub">Humano e IA operan sobre el mismo software.</div>
        <div class="sub-coral">El código está dejando de ser observado línea a línea (se mantiene auditable).</div>
      </div>
    </div>
  caption: ""
---

# Cambio de topología

Fiel a `propuesta_visual.md` slide 3. Dos diagramas con cajas y flechas.
