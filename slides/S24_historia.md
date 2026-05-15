---
slide_id: S24
slide_type: anexo
section: marco
action_title: "Cuándo nació cada fase."
position: 24
status: draft
evidences: []
content:
  eyebrow: ""
  subtitle: "Cada disciplina se consolidó cuando la anterior maduró."
  body_html: |
    <style>
      .s24.anexo-slide .body { top: 240px !important; bottom: 70px !important; overflow: visible !important; }
      .body > .s24 { padding-top: 0; max-width: 1380px; font-family: var(--sans); }
      .s24 .row-h { display: grid; grid-template-columns: 180px 240px 1fr; column-gap: 28px; padding: 8px 0; font-family: var(--mono); font-size: 12px; font-weight: 700; color: var(--mute); letter-spacing: 0.1em; text-transform: uppercase; border-bottom: 1px solid var(--ink); }
      .s24 .row { display: grid; grid-template-columns: 180px 240px 1fr; column-gap: 28px; padding: 10px 0; align-items: baseline; border-bottom: 1px solid var(--rule); }
      .s24 .row:last-of-type { border-bottom: none; }
      .s24 .row .fase { font-family: var(--mono); font-size: 17px; font-weight: 700; color: var(--ink); letter-spacing: 0.02em; }
      .s24 .row .when { font-family: var(--mono); font-size: 13px; color: var(--mute); line-height: 1.4; }
      .s24 .row .when strong { color: var(--ink); font-weight: 700; }
      .s24 .row .idea { font-size: 17px; color: var(--ink); line-height: 1.4; font-weight: 400; }
      .s24 .row.coral .fase { color: var(--coral); }
      .s24 .row.coral .idea { color: var(--ink); font-weight: 500; }
      .s24 .row.coral .idea em { color: var(--coral); font-style: normal; font-weight: 600; }
      .s24 .refs { margin-top: 24px; padding-top: 16px; border-top: 1px solid var(--rule); }
      .s24 .refs-h { font-family: var(--mono); font-size: 11px; font-weight: 700; color: var(--mute); letter-spacing: 0.1em; text-transform: uppercase; margin-bottom: 10px; }
      .s24 .refs-list { font-family: var(--mono); font-size: 11px; color: var(--mute); line-height: 1.6; }
      .s24 .refs-list .ref { margin-bottom: 4px; }
      .s24 .refs-list .marker { color: var(--coral); font-weight: 700; margin-right: 8px; }
      .s24 .refs-list .url { color: var(--ink); }
      .s24 .row .marker-inline { color: var(--coral); font-weight: 700; font-family: var(--mono); font-size: 11px; vertical-align: super; margin-left: 4px; }
    </style>
    <div class="s24">
      <div class="row-h">
        <div>Fase</div>
        <div>Cuándo se consolidó</div>
        <div>La idea central</div>
      </div>
      <div class="row">
        <div class="fase">data<span class="marker-inline">1</span></div>
        <div class="when"><strong>~2010s</strong><br>era big data · GFS (2003) + MapReduce (2004)</div>
        <div class="idea">estructurar el mundo en un dataset</div>
      </div>
      <div class="row">
        <div class="fase">model<span class="marker-inline">2</span></div>
        <div class="when"><strong>2017</strong><br>Transformers · Vaswani et al.</div>
        <div class="idea">entrenar pesos óptimos sobre ese dataset</div>
      </div>
      <div class="row">
        <div class="fase">context<span class="marker-inline">3</span></div>
        <div class="when"><strong>sep 2025</strong><br>Anthropic</div>
        <div class="idea">curar qué tokens condicionan al modelo</div>
      </div>
      <div class="row">
        <div class="fase">harness<span class="marker-inline">4</span></div>
        <div class="when"><strong>mar 2026</strong><br>Vivek Trivedy · LangChain</div>
        <div class="idea">envolver el modelo con un loop gobernado · <em>Agent = Model + Harness</em></div>
      </div>
      <div class="row coral">
        <div class="fase">autoresearch<span class="marker-inline">5</span></div>
        <div class="when"><strong>mar 2026</strong><br>Andrej Karpathy</div>
        <div class="idea">y ahora, <em>que el sistema diseñe sus propios experimentos</em></div>
      </div>
      <div class="refs">
        <div class="refs-h">Fuentes (APA 7)</div>
        <div class="refs-list">
          <div class="ref"><span class="marker">1a</span>Ghemawat, S., Gobioff, H., &amp; Leung, S.-T. (2003). The Google file system. <em>SOSP '03</em>. <span class="url">research.google/pubs/the-google-file-system</span></div>
          <div class="ref"><span class="marker">1b</span>Dean, J., &amp; Ghemawat, S. (2004). MapReduce: Simplified data processing on large clusters. <em>OSDI '04</em>. <span class="url">research.google/pubs/mapreduce-simplified-data-processing-on-large-clusters</span></div>
          <div class="ref"><span class="marker">2</span>Vaswani, A., et al. (2017). Attention is all you need. <em>NeurIPS 2017</em>. <span class="url">arxiv.org/abs/1706.03762</span></div>
          <div class="ref"><span class="marker">3</span>Rajasekaran, P., Dixon, E., Ryan, C., &amp; Hadfield, J. (2025). Effective context engineering for AI agents. <em>Anthropic Engineering</em>. <span class="url">anthropic.com/engineering/effective-context-engineering-for-ai-agents</span></div>
          <div class="ref"><span class="marker">4</span>Trivedy, V. (2026, March 10). The anatomy of an agent harness. <em>LangChain Blog</em>. <span class="url">langchain.com/blog/the-anatomy-of-an-agent-harness</span></div>
          <div class="ref"><span class="marker">5</span>Karpathy, A. (2026). <em>autoresearch</em> [Software]. GitHub. <span class="url">github.com/karpathy/autoresearch</span></div>
        </div>
      </div>
    </div>
  caption: ""
---

# Cuándo nació cada fase

Slide nuevo, exclusiva del deck Flisol.

Tabla compañera del timeline (S20). Mientras S20 muestra la estructura formal (ecuaciones), esta (S21) muestra el arco histórico — cuándo se acuñó cada disciplina, quién y dónde está la referencia primaria. Ambas slides funcionan como síntesis al final del deck (tras autoresearch en S18-S19), antes del bloque de cierre.

Referencias verificadas (URLs 200 OK):

1. **data** — Ghemawat, S., Gobioff, H., & Leung, S.-T. (2003). *The Google file system*. SOSP '03. https://research.google/pubs/the-google-file-system/ + Dean, J., & Ghemawat, S. (2004). *MapReduce: Simplified data processing on large clusters*. OSDI '04. https://research.google/pubs/mapreduce-simplified-data-processing-on-large-clusters/
2. **model** — Vaswani, A., et al. (2017). *Attention is all you need*. NeurIPS 2017. https://arxiv.org/abs/1706.03762
3. **context** — Rajasekaran, P., Dixon, E., Ryan, C., & Hadfield, J. (2025, September 29). *Effective context engineering for AI agents*. Anthropic Engineering. https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents
4. **harness** — Trivedy, V. (2026, March 10). *The anatomy of an agent harness*. LangChain Blog. https://www.langchain.com/blog/the-anatomy-of-an-agent-harness
5. **autoresearch** — Karpathy, A. (2026). *autoresearch: AI agents running research on single-GPU nanochat training automatically* [Software repository]. GitHub. https://github.com/karpathy/autoresearch

**Nota sobre harness:** atribución primaria a Vivek Trivedy (LangChain, marzo 2026) por *The Anatomy of an Agent Harness*, donde formaliza la fórmula "Agent = Model + Harness". Mitchell Hashimoto también usó el término en feb 2026 (*My AI adoption journey*) pero Trivedy es la referencia más sustantiva y disciplinaria.
