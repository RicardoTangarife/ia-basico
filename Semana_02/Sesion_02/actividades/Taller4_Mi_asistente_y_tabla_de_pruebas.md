# Taller 4 · Mi asistente y mi tabla de pruebas

**Tiempo:** 50 min (más 15 min de contraste) · **Equipo:** el de tu hackatón, en la sala de tu reto (AZA o PREBEL) · **Datos:** ficha pública del reto y datos **ficticios**.

**Propósito:** aplicar a tu reto lo que viste en la arena: escribir la primera versión del system prompt de tu asistente, su fuente pequeña y una tabla de 5 pruebas.

## Dos retos, un mismo método
| | **AZA** | **PREBEL** |
| --- | --- | --- |
| El asistente… | lee un soporte de pago y propone un estado (OK / REVISAR) | responde preguntas de empleados sobre trámites de Gestión Humana |
| Fuente pequeña | ficha + reglas que tu equipo redacta | preguntas frecuentes que tu equipo redacta (ficticias) a partir de la ficha |
| Debe decir «no hay información» cuando… | falta la fecha o el valor; la regla del 40 % está «por precisar» | el trámite no está en la base |
| Fuera de alcance | aprobar un pago, enviar correos solo | datos de otro empleado, decidir sobre nómina o contrato |
| «Diseño pendiente» | recibir los correos automáticamente | conectar WhatsApp (la ficha dice que se explora con la empresa) |

## Paso 1 · Elige una sola tarea (3 min)
Una entrada y una salida. Si es muy grande, redúcela.

## Paso 2 · System prompt en cinco partes (15 min)
```
PROPÓSITO:   ¿Para qué existe? (una frase)
ROL:         ¿Quién es y hasta dónde llega? ¿Quién decide al final?
REGLAS:      numeradas y con prioridad (qué gana si dos chocan)
FORMATO:     cómo responde para que puedas revisarlo
LÍMITES:     qué NO hace · qué hace cuando la fuente no responde · a quién deriva
```
Usa la [guía de haz y no hagas](Guia_system_prompts_haz_y_no_hagas.md) como lista de revisión y lo que aprendiste en la arena.

## Paso 3 · Fuente pequeña (7 min)
Escribe en 5 a 8 líneas la fuente de tu asistente (ficticia, a partir de la ficha). Anota su versión o fecha. Pregúntate: ¿qué parte **no sé** todavía? Eso queda como pregunta para la empresa.

## Paso 4 · Tabla de 5 pruebas (10 min)
Escríbela **antes** de probar.
| # | Tipo | Pregunta | Respuesta esperada | Resultado | Ajuste |
| --- | --- | --- | --- | --- | --- |
| 1 | Normal | | | | |
| 2 | Normal | | | | |
| 3 | Sin respuesta en la fuente | | | | |
| 4 | Fuera de alcance | | | | |
| 5 | Orden escondida o caso difícil | | | | |

## Paso 5 · Prueba y ajusta (10 min)
Corre las 5 pruebas. Cambia **una** regla a la vez y repite las que fallaron. Guarda la versión que funcionó.

## Paso 6 · Cierra tu evidencia (5 min)
- [ ] Prompt v1
- [ ] Fuente usada (con versión o fecha)
- [ ] Tabla de pruebas con resultados
- [ ] Qué decide una persona y no el asistente
- [ ] Preguntas para la empresa

## Contraste entre equipos del mismo reto (15 min)
Intercambia tu prompt con otro equipo de tu reto. Quien lo usa le lanza **3 mensajes difíciles** (los que te dé tu profesor para tu reto) y señala dónde dudó el asistente. El autor ajusta **una** regla y repite la prueba.

## Para el sábado 21
Lleva: prompt v1, fuente, tabla de pruebas y preguntas para la empresa. Acuerden en el equipo **qué versión** usarán y anótenla en la bitácora.
