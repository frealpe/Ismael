# Ismael.config — Configuración del marco

> Fuente única de la configuración de ESTE proyecto. La editas a mano o con el ritual `config`
> (`Ismael/SKILL.md`). El **auto-arranque** y el **mapa de documentación** se GENERAN de aquí —
> no los edites por separado. Todo lo accionable va en **tablas**; la prosa solo explica.

## Meta

| Parámetro | Valor |
| --- | --- |
| idioma | es |
| módulos | pendiente |
| persistencia | git |
| persistencia_cmd | — |
| kit_origen | `https://github.com/frealpe/Ismael` |
| kit_sello | `74db7eea461d83c5b70adcdeccbc5fff31668210` |
| remitente | — |
| remitente_publico | — |

## Rutas

| Ruta | Valor | Qué es |
| --- | --- | --- |
| kit | Ismael | El marco vendorizado (`SKILL.md`, `guide.md`, `core/`, `modules/`). |
| base | bitacora | Raíz de los docs instanciados. |
| loader | CLAUDE.md, AGENTS.md | **Puertas** de auto-arranque, siempre en la raíz. GENERADO. Lista separada por comas. |

## Nombres (rol → archivo)

| Rol | Archivo | Origen |
| --- | --- | --- |
| entry | guia-agente.md | núcleo |
| gotchas | memory.md | núcleo |
| charter | design.md | núcleo |
| manual | manual.md | núcleo |
| protocol | protocol.md | núcleo |
| state | latest.md | núcleo |
| handover | handover.md | núcleo |
| index | index.md | núcleo |
| history_dir | history/ | núcleo |
| session | sesion-{NNN}-{YYYY-MM-DD}.md | núcleo |
| audit | audit.md | núcleo |
| correspondence | cartas.md | núcleo |
| letter | carta-{NNN}-{YYYY-MM-DD}.md | núcleo |
| correspondence_dir | correspondencia/ | núcleo |
| artifacts_dir | artefactos/ | núcleo |
| specs | — | producto |
| specs_dir | — | producto |
| architecture | — | producto |
| effort | — | producto |

## Features (toggles)

| Feature | Valor | Origen |
| --- | --- | --- |
| session_greeting | on | núcleo |
| audit_log | on | núcleo |
| audit_every_n_sessions | 10 | núcleo |
| correspondence_log | on | núcleo |
| manual_doc | on | núcleo |
| effort_log | off | producto |
| effort_unit | — | producto |

## Presupuestos

| Doc (rol) | Máx. líneas |
| --- | --- |
| entry | 250 |
| gotchas | 400 |
| state | 100 |
| handover | 90 |
| SKILL.md (enrutador del kit) | 400 |

## Wording de rituales

| Ritual | Parámetro | Texto |
| --- | --- | --- |
| checkpoint | trigger | antes de un cambio interrumpible |
| abrir | saludo | 1-3 líneas: última sesión + estado handover + próximo paso |
| habla | trato | tú |
