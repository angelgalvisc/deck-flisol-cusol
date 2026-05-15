---
deck_id: deck-flisol
title: Deep Agents · Harness Engineering and AutoResearch
visibility: public
client: cusol
project: deck-flisol
presentation_name: Deep Agents · charla Flisol / Cusol UIS·UTS
total_slides: 28
aesthetic: datastrat/v1
delivery_mode: quick_draft
created: 2026-05-13
updated: 2026-05-14
status: draft
lang: es
coord: "Flisol · Cusol · 2026"
topbar_right: "2026-05"
bottom_left: "Flisol | datastrat"
---

# deck-flisol

## Tesis (versión académica)

Los agentes dejaron de ser "chat más inteligente": son sistemas que operan sobre fuentes de verdad verificables, dirigidos por un harness y, en el límite, capaces de mejorarse a sí mismos mediante autoresearch. La charla mapea cómo evolucionó la ingeniería de IA en cinco fases (data → model → context → harness → autoresearch), muestra tres casos concretos (licitaciones, conversación, onboarding), y deja al público con un mapa mental y rutas para empezar.

## Origen

Derivado del deck [redacted] original (`[redacted]`). Cambios principales aplicados en esta versión:

- Headers globales: `Flisol · Cusol · 2026` / `2026-05` / `Flisol | datastrat`.
- Nueva **S04_caso_a.md** (Caso A · Licitaciones públicas SECOP II, multi-agente: scout + deep agent · industria-agnóstico). Reordenado al inicio del bloque de casos para liderar con la pieza más fuerte para CUSOL; reenumerado de C → A para que la letra coincida con la posición.
- Nueva **S20_timeline.md** (timeline · 5 fases con ecuaciones canónicas + nomenclatura). Movida al final del recorrido conceptual para funcionar como síntesis tras el deep dive de autoresearch (no como apertura) — pedagógicamente mejor para audiencia CUSOL.
- Nueva **S21_historia.md** (tabla histórica · cuándo se consolidó cada fase y quién la acuñó, con referencias APA verificadas). Compañera de S20, también movida al final.
- **S09_skin_in_the_game.md** (matriz 2×2): ejemplos del cuadrante naranja reescritos a casos generales (código, refactoring, bugs, análisis, investigación).
- Resto del contenido mantenido idéntico al deck [redacted]. Decisiones de excluir/adaptar slides fintech quedan pendientes.

## Orden canónico de slides

| SXX | tipo          | slide                                                |
|-----|---------------|------------------------------------------------------|
| S01 | cover         | [[slides/S01_portada.md]]                            |
| S02 | agenda        | [[slides/S02_agenda_books.md]]                       |
| S03 | tesis         | [[slides/S03_promesa.md]]                            |
| S04 | comparativa   | [[slides/S04_topologia.md]]                          |
| S05 | tesis         | [[slides/S05_caso_a.md]]                             |
| S06 | tesis         | [[slides/S06_caso_b.md]]                             |
| S07 | tabla         | [[slides/S07_cli_mcp.md]]                            |
| S08 | tesis         | [[slides/S08_caso_c.md]]                             |
| S09 | cuantitativo  | [[slides/S09_asimetria.md]]                          |
| S10 | 2x2           | [[slides/S10_skin_in_the_game.md]]                   |
| S11 | cita          | [[slides/S11_agente.md]]                             |
| S12 | cuantitativo  | [[slides/S12_horizonte.md]]                          |
| S13 | stepper       | [[slides/S13_deep_agents.md]]                        |
| S14 | cita          | [[slides/S14_harness.md]]                            |
| S15 | anexo         | [[slides/S15_harness_visual.md]]                     |
| S16 | cita          | [[slides/S16_jensen.md]]                             |
| S17 | comparativa   | [[slides/S17_harnesses_produccion.md]]               |
| S18 | visual        | [[slides/S18_harness_logos.md]]                      |
| S19 | anexo         | [[slides/S19_estrategia.md]]                         |
| S20 | tabla         | [[slides/S20_autoresearch.md]]                       |
| S21 | anexo         | [[slides/S21_autoresearch_visual.md]]                |
| S22 | visual        | [[slides/S22_timeline_visual.md]]                    |
| S23 | timeline      | [[slides/S23_timeline.md]]                           |
| S24 | tabla         | [[slides/S24_historia.md]]                           |
| S25 | anexo         | [[slides/S25_aprende.md]]                            |
| S26 | anexo         | [[slides/S26_construye.md]]                          |
| S27 | manifesto     | [[slides/S27_manifesto.md]]                          |
| S28 | cierre        | [[slides/S28_cierre.md]]                             |

## Decisiones globales

- Modo `quick_draft`: sin trazabilidad rigurosa de evidencias (`E###`).
- Paleta datastrat/v1 oficial: `--ink`, `--ink-soft`, `--mute`, `--soft`, `--rule`, `--bg`, `--coral`.
- Marca `datastrat` siempre en minúscula.
- Cifras siempre en mono con unidad explícita.
- Coral aparece **una sola vez por slide** (el insight).
- Slides asumen jerarquía Minto: tesis arriba, soporte medio, evidencia abajo, cierre.

## Pendientes para próxima vuelta

- S22 (Stripe/Revolut), S23 (ecosistema LATAM fintech), S24 (oportunidades [redacted]) **eliminados** — eran artefactos del deck [redacted], irrelevantes para CUSOL. Reemplazados por dos slides nuevos: S22_oportunidades_empezar (palancas 1-2: harnesses abiertos + data pública) y S23_oportunidades_posicionarte (palancas 3-4: harness engineering + deep agents para emprender).
- Decidir si excluir S05 (caso B · restaurante WhatsApp, cifras en COP) y S15 (cita Jensen Huang) — pendiente. S07 (caso C · cuenta empresarial NIT) se mantiene, reframed como ángulo de emprendimiento + deep agents.
- Cambiar header derecho a fecha exacta del evento si aplica (hoy `2026-05`, podría afinarse a `2026-05-15`).
