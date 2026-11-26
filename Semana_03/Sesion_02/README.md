# Semana 3 · Sesión 2 (sesión 5 del curso) · Guardrails: lo que hay entre tú y el modelo

**Tema:** un system prompt es una petición, no un candado. Construyes **guardrails** alrededor de un asistente que lee correos de acudientes (reglas, un clasificador que escoge una letra y una verificación de la salida), **mides** qué cambian (errores graves frente a trabajo humano) y comparas lo que hace un modelo por API frente a ChatGPT, Gemini o Claude. El taller es **guiado**.

## Qué lograrás
- Explicar qué es un guardrail y qué capa atrapa cada tipo de problema, incluidos los **errores del propio modelo**.
- Construir un clasificador con categorías claras y ejemplos, y una verificación con reglas de negocio.
- Medir con una tabla qué cambia con las capas y cuánto trabajo humano cuesta.
- Explicar por qué el mismo modelo responde distinto por API y en una app.

## Materiales
| Material | Archivo |
| --- | --- |
| Presentación (un solo archivo: descárgalo y ábrelo en el navegador) | [`presentacion/Sesion05_Capa2_basico_IA.html`](presentacion/Sesion05_Capa2_basico_IA.html) |
| Taller 6 · Guardrails (guiado) | [`actividades/Taller6_Guardrails.md`](actividades/Taller6_Guardrails.md) |
| Cuaderno de Colab | [`notebooks/S3S2_Guardrails.ipynb`](notebooks/S3S2_Guardrails.ipynb) · [Abrir en Colab](https://colab.research.google.com/github/RicardoTangarife/ia-basico/blob/main/Semana_03/Sesion_02/notebooks/S3S2_Guardrails.ipynb) |
| Guía · Qué hacer y qué no en un system prompt | [`../../Semana_02/Sesion_02/actividades/Guia_system_prompts_haz_y_no_hagas.md`](../../Semana_02/Sesion_02/actividades/Guia_system_prompts_haz_y_no_hagas.md) |

## Antes de la sesión
- Ten tu clave de Groq guardada en 🔑 Secretos (la misma de la sesión anterior; en el cuaderno nuevo solo activa **Acceso desde el cuaderno**).
- Ten a mano tu **registro de la sesión 4**: lo que falló por API y no fallaba en ChatGPT.

## Al terminar
Guarda tu asistente con guardrails, la tabla de resultados y una frase tuya: *«La capa que más me ayudó fue… y lo que no atrapa es…»*.
