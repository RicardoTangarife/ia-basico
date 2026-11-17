# Taller 1 · ¿Pregunta o inventa?

**Tiempo:** 30 min · **Equipos:** grupos de 4-5 *Datos:** [`datos_practica`](../../datos_practica/) (ficticios)

**Propósito:** comprobar qué hace una IA cuando le falta un dato y corregir su configuración para que no invente.

## Parte A · Primera prueba (8 min)
1. Abre un chat **nuevo** en tu herramienta.
2. Sube `comprobante_04.pdf` y escribe solo: «Extrae el nombre, la fecha, el valor y el concepto del pago».
3. Anota la respuesta. ¿Aparece una fecha? ¿Está realmente en el comprobante?

## Parte B · Primera configuración (10 min)
1. Abre un chat nuevo y pega esta configuración de partida:
   ```
   ROL: Eres asistente de la secretaría de la Academia Sol Mayor.
   CONTEXTO: Recibes comprobantes de pago de mensualidades.
   REGLAS:
    1. Extrae solo: nombre, fecha, valor, concepto.
    2. Cita el texto exacto de donde sacaste cada dato.
   FORMATO: tabla Dato | Valor | Evidencia.
   ```
2. Sube de nuevo `comprobante_04.pdf` con el mensaje «Procesa el archivo adjunto».
3. Anota: ¿cambió algo respecto a la parte A?

## Parte C · Corrígela (8 min)
1. Agrega a la configuración **una regla** para que, cuando falte un dato, la IA lo diga en lugar de inventarlo.
2. Agrega una regla sobre **cuándo debe detenerse y pedirte revisión**.
3. Vuelve a probar con `comprobante_04.pdf` y con uno que sí tenga todos los datos (`comprobante_01.pdf`).

## Parte D · Decide (4 min)
Responde en una frase cada una:
- ¿Qué información de este caso **no** habrías compartido si fuera real?
- ¿Qué dato necesita **verificación** tuya antes de aceptarlo?
- ¿Cuándo debe **detenerse** el asistente?

## Qué guardar
- Las dos versiones de la configuración.
- Una salida de cada versión.
- La regla que agregaste y por qué.
