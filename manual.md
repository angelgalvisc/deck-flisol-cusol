---
deck_id: deck-flisol
title: Deep Agents · Harness Engineering and AutoResearch
visibility: public
client: cusol
project: deck-flisol
presentation_name: Deep Agents · charla Flisol / Cusol UIS·UTS
total_slides: 25
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
- Nueva **S08_timeline.md** (timeline · 5 fases con ecuaciones canónicas + nomenclatura).
- Nueva **S09_historia.md** (tabla histórica · cuándo se consolidó cada fase y quién la acuñó, con referencias APA verificadas).
- **S11_skin_in_the_game.md** (matriz 2×2): ejemplos del cuadrante naranja reescritos a casos generales (código, refactoring, bugs, análisis, investigación).
- Resto del contenido mantenido idéntico al deck [redacted]. Decisiones de excluir/adaptar slides fintech quedan pendientes.

## Orden canónico de slides

| SXX | tipo          | slide                                                |
|-----|---------------|------------------------------------------------------|
| S01 | cover         | [[slides/S01_portada.md]]                            |
| S02 | tesis         | [[slides/S02_promesa.md]]                            |
| S03 | comparativa   | [[slides/S03_topologia.md]]                          |
| S04 | tesis         | [[slides/S04_caso_a.md]]                             |
| S05 | tesis         | [[slides/S05_caso_b.md]]                             |
| S06 | tabla         | [[slides/S06_cli_mcp.md]]                            |
| S07 | tesis         | [[slides/S07_caso_c.md]]                             |
| S08 | timeline      | [[slides/S08_timeline.md]]                           |
| S09 | tabla         | [[slides/S09_historia.md]]                           |
| S10 | cuantitativo  | [[slides/S10_asimetria.md]]                          |
| S11 | 2x2           | [[slides/S11_skin_in_the_game.md]]                   |
| S12 | cita          | [[slides/S12_agente.md]]                             |
| S13 | cuantitativo  | [[slides/S13_horizonte.md]]                          |
| S14 | stepper       | [[slides/S14_deep_agents.md]]                        |
| S15 | cita          | [[slides/S15_harness.md]]                            |
| S16 | anexo         | [[slides/S16_harness_visual.md]]                     |
| S17 | cita          | [[slides/S17_jensen.md]]                             |
| S18 | comparativa   | [[slides/S18_harnesses_produccion.md]]               |
| S19 | anexo         | [[slides/S19_estrategia.md]]                         |
| S20 | tabla         | [[slides/S20_autoresearch.md]]                       |
| S21 | anexo         | [[slides/S21_autoresearch_visual.md]]                |
| S22 | comparativa   | [[slides/S22_apuestas.md]]                           |
| S23 | tabla         | [[slides/S23_ecosistema.md]]                         |
| S24 | stepper       | [[slides/S24_oportunidades.md]]                      |
| S25 | cierre        | [[slides/S25_cierre.md]]                             |

## Decisiones globales

- Modo `quick_draft`: sin trazabilidad rigurosa de evidencias (`E###`).
- Paleta datastrat/v1 oficial: `--ink`, `--ink-soft`, `--mute`, `--soft`, `--rule`, `--bg`, `--coral`.
- Marca `datastrat` siempre en minúscula.
- Cifras siempre en mono con unidad explícita.
- Coral aparece **una sola vez por slide** (el insight).
- Slides asumen jerarquía Minto: tesis arriba, soporte medio, evidencia abajo, cierre.

## Pendientes para próxima vuelta

- Decidir qué slides excluir/adaptar para perfil CUSOL: candidatas a salir/transformar son S05 (caso B · restaurante WhatsApp, cifras en COP), S17 (cita Jensen Huang), S22 (Stripe/Revolut), S23 (ecosistema LATAM fintech), S24 (oportunidades [redacted]). S07 (caso C · cuenta empresarial NIT) se mantiene, reframed como ángulo de emprendimiento + deep agents.
- Cambiar header derecho a fecha exacta del evento si aplica (hoy `2026-05`, podría afinarse a `2026-05-15`).
