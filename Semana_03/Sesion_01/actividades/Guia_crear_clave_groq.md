# Guía · Crear tu clave de Groq y guardarla en Colab

Una **API key** es la contraseña con la que un servicio sabe que eres tú. Con ella tu cuaderno de Colab puede llamar a un modelo de IA. **Es tuya y no se comparte.**

## Paso a paso
| # | Qué hacer | Dónde |
| --- | --- | --- |
| 1 | Crea una cuenta **gratuita** (puedes entrar con tu cuenta de Google). No pide tarjeta. | [console.groq.com](https://console.groq.com) |
| 2 | Entra a **API Keys → Create API Key**. Ponle de nombre `estudia`. | [console.groq.com/keys](https://console.groq.com/keys) |
| 3 | **Copia** la clave (empieza por `gsk_`). Solo se muestra una vez. | Groq |
| 4 | Abre el cuaderno de la sesión en Colab. | [Colab](https://colab.research.google.com/) |
| 5 | En la barra izquierda abre **🔑 Secretos** → **Agregar nuevo secreto**. | Colab |
| 6 | **Nombre:** `GROQ_API_KEY` · **Valor:** pega tu clave. | Colab |
| 7 | Activa el interruptor **Acceso desde el cuaderno**. Sin esto, el cuaderno no puede leerla. | Colab |
| 8 | Ejecuta la celda *Conecta el cuaderno con tu clave* y pulsa **🔍 Probar mi clave**. Debes ver ✅. | Cuaderno |

## Reglas de oro
- ❌ Nunca pegues la clave dentro de una celda ni la mandes por el chat de la clase o por WhatsApp.
- 🔁 Si se te escapa: entra a Groq, pulsa **Revoke** en esa clave y crea otra.
- ✅ Los Secretos son por cuenta de Google: sirven para **todos** tus cuadernos. Solo activa el interruptor en cada cuaderno nuevo.
- Solo datos **ficticios**: lo que envías viaja a un servicio externo.
- Groq tiene límites gratuitos (por minuto y por día). El cuaderno tiene un **medidor** (`medidor()`) que te dice cuánto te queda.
- Revisa las condiciones de edad del servicio. Si eres menor de 18 o no puedes crear la cuenta, trabaja con un compañero que sí pueda y sigue la clase en pantalla.

## Si algo falla
| Mensaje | Qué significa | Qué hacer |
| --- | --- | --- |
| «No encontré el secreto GROQ_API_KEY» | El nombre no coincide o falta el interruptor | Revisa que el nombre sea exactamente `GROQ_API_KEY` y activa *Acceso desde el cuaderno* |
| 401 | Clave incorrecta | Cópiala de nuevo, completa y sin espacios; o crea otra |
| 403 | Tu cuenta no tiene permiso | Revisa las condiciones del servicio; avisa a tu profesor |
| 429 o «Límite por minuto» | Llegaste al límite | Espera un minuto; el cuaderno reintenta solo |
| Respuesta vacía | El modelo gastó los tokens «pensando» | Elige otro modelo en el menú o sube `max_tokens` |
