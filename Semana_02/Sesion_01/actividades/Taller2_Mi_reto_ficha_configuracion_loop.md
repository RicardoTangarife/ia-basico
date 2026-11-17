# Taller 2 · Mi reto: ficha, configuración y loop

**Tiempo:** 65 min (más 25 min de contraste) · **Equipo:** el de tu hackatón (o individual) · **Datos:** solo la **ficha pública** del reto y datos **ficticios** que tú inventes o los de [`datos_practica`](../../datos_practica/).

**Propósito:** dejar listas las bases de tu solución para el reto. Aquí no te decimos cómo resolverlo: tú tomas las decisiones. Nosotros te acompañamos con preguntas.

## Paso 1 · Ficha de necesidad (10 min)
Completa con tus palabras (una o dos frases cada una):

| Aspecto | Tu respuesta |
| --- | --- |
| Necesidad: ¿quién necesita hacer qué y por qué es importante? | |
| Entrada: ¿qué información entra? ¿cómo conseguirías una muestra permitida o ficticia? | |
| Salida: ¿qué resultado concreto necesitan? ¿cómo sabrías que es correcto? | |
| Alcance: ¿qué UNA tarea vas a resolver primero? ¿qué queda fuera? | |
| Decisión humana: ¿qué decide una persona, no la IA? | |
| Cuidado de datos: ¿qué es sensible y cómo lo vas a manejar? | |

## Paso 2 · Configuración (15 min)
Escribe tu configuración con estas secciones. Piensa: ¿qué debe recordar la herramienta **cada vez**?

```
ROL:
CONTEXTO:
REGLAS:
FORMATO DE SALIDA:
LÍMITES:
```

Pistas (para pensar, no para copiar):
- ¿Qué dato **no** quieres que se invente nunca? Escribe una regla.
- ¿Qué debe hacer si falta información?
- ¿Qué parte de las reglas del reto aún no está clara? La configuración debe decir que **pregunte**, no que adivine.

## Paso 3 · Loop con parada (15 min)
Escribe 3 pasos: preparar → comprobar contra tus criterios → pedir tu revisión. Define:
- **Cuándo se detiene:** (cumple el formato / falta un dato / necesita tu autorización).
- **Cuántos intentos admite:** ______.

## Paso 4 · Pruébalo (15 min)
1. Inventa **2 casos** parecidos a los del reto y **1 caso problemático** (dato faltante, contradicción, error de lectura).
2. Ejecútalos con tu configuración y tu loop.
3. Anota qué salió bien, qué falló y qué corriges.

## Paso 5 · Guarda tu evidencia (10 min)
- [ ] Instrucción inicial
- [ ] Una salida
- [ ] Versión corregida
- [ ] Qué se pudo comprobar y qué no

## Mentoría
Mientras el profesor atiende a otro equipo, repite una comprobación con tu caso problemático o revisa que cada regla tenga un caso que la pruebe.

## Contraste entre pares (25 min)
Intercambia tu configuración con otro equipo. Quien la usa señala **dónde dudó**. Ajusta esa parte y repite la prueba.
