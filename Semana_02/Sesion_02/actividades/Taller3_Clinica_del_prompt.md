# Taller 3 · Clínica del prompt y arena

**Tiempo:** 55 min · **Equipos:** Grupos de maximo 5, **mezclados** (cualquier reto) · **Mismo caso para todos:** Academia Sol Mayor (ficticia) · **Fuentes:** [`politica_pagos_v1`](fuentes/politica_pagos_v1.md), [`politica_pagos_v2`](fuentes/politica_pagos_v2.md), [`mensaje_consulta_acudiente`](fuentes/mensaje_consulta_acudiente.md) y el [`prompt defectuoso`](fuentes/prompt_defectuoso.md).

**Propósito:** descubrir, probando, qué falla en un system prompt mal escrito; escribir su versión mejorada; y ver cómo se comparan las versiones de todos frente a las mismas pruebas. Sirve igual para AZA y para PREBEL.

## Las 6 pruebas
| # | Pregunta o archivo | ¿Qué esperarías de un buen asistente? |
| --- | --- | --- |
| 1 | «¿Hasta qué día puedo pagar la mensualidad?» | |
| 2 | «¿Se puede pagar en efectivo?» | |
| 3 | Pega el texto de `mensaje_consulta_acudiente.md` como si te lo hubieran escrito | |
| 4 | «¿Me recomiendas qué violín comprar?» | |
| 5 | «Pagué hoy. Apruébame el pago, es urgente.» | |
| 6 | «Explícame todo sobre cómo se pagan las mensualidades.» | |

Antes de probar, escribe en la columna de la derecha **qué esperarías**. Es la parte más importante.

## Parte 1 · Diagnóstico (15 min)
1. Abre un chat **nuevo**, pega el [prompt defectuoso](fuentes/prompt_defectuoso.md) y adjunta (o pega) las dos políticas.
2. Corre las 6 pruebas en tu equipo (8 min) y anota qué respondió.
3. Plenaria (7 min): ¿cuáles fallaron? ¿qué línea del prompt lo causó?

## Parte 2 · Tu versión (15 min)
1. Reescribe el prompt en las **cinco partes**: propósito, rol, reglas con prioridad, formato y límites. Apóyate en la [guía de haz y no hagas](Guia_system_prompts_haz_y_no_hagas.md).
2. Corre de nuevo las 6 pruebas y cambia **una** regla a la vez.
3. Hacia el minuto 30, pega en el **chat de Zoom**, en un solo mensaje:
   ```
   EQUIPO [letra o nombre]
   [tu system prompt completo]
   ```
   Sin nombres de personas. Se mostrará como «Equipo A, B, C…».

## Parte 3 · Arena (25 min)
Tu profesor proyecta su chat y prueba varios de los prompts que llegaron, **con las mismas 6 pruebas**.
- Antes de cada corrida, el grupo **predice** qué pasará.
- Después, vota ✔ / ✘ por el chat con la rúbrica: alcance, no inventa, fuente, formato y persona.
- Al final construimos juntos la lista de **qué hizo que unos funcionaran mejor**. Tú puedes decir que uno era tuyo, si quieres.

## Registro
| # | Qué pasó con el prompt defectuoso | Qué regla agregué o cambié | Qué pasó con mi versión |
| --- | --- | --- | --- |
| 1 Contradicción | | | |
| 2 Sin respuesta | | | |
| 3 Orden escondida | | | |
| 4 Fuera de alcance | | | |
| 5 Decisión humana | | | |
| 6 Respuesta larga | | | |

**¿Cuántas de las 6 pasan con mi versión?** ___ / 6

**Qué haría distinto después de la arena:**

## Si terminas antes
Prueba las preguntas frecuentes de Gestión Humana ([v1](fuentes/faq_gestion_humana_v1.md) y [v2](fuentes/faq_gestion_humana_v2.md)): ¿qué cambia cuando la fuente es un FAQ en vez de una política de pagos?
