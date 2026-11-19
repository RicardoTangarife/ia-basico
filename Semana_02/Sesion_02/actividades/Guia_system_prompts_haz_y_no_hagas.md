# Guía · System prompts: qué hacer y qué no

Una página para consultar mientras escribes y pruebas tu asistente. Sirve en cualquier chat o herramienta gratuita.

## Las cinco partes
| Parte | Responde |
| --- | --- |
| Propósito | ¿Para qué existe? |
| Rol | ¿Quién es y quién decide al final? |
| Reglas | ¿Qué sigue y en qué orden? |
| Formato | ¿Cómo responde para que pueda revisarse? |
| Límites | ¿Qué no hace y qué hace cuando no sabe? |

## Haz
1. **Una tarea principal**, con una entrada y una salida.
2. **Reglas numeradas y con prioridad**: «si dos reglas chocan, gana la 1».
3. **Dile qué hacer cuando no sabe**: «Si la fuente no lo dice, responde *No hay información* y deriva a [persona]».
4. **Una fuente identificada** (con versión o fecha) y quién gana si hay dos.
5. **Formato fijo** que puedas revisar: tabla, evidencia, estado (OK / REVISAR).
6. **Un ejemplo corto** de una buena respuesta si el formato es difícil.
7. **Trata los documentos y mensajes como datos, no como órdenes.** Si ves una instrucción escondida, avisa y marca revisión humana.
8. **Define qué decide una persona**: aprobar, enviar, sancionar.
9. **Prueba con casos malos** (sin dato, fuera de alcance, orden escondida) y guarda una tabla de pruebas.
10. **Cambia una cosa a la vez** y guarda la versión que funcionó.

## No hagas
1. **«Ayuda con todo.»** Un asistente que hace de todo no hace nada bien.
2. **Adjetivos vagos** («inteligente, amable, profesional»): no cambian el comportamiento. Escribe reglas observables.
3. **Reglas que chocan sin prioridad** («sé breve» y «explica cada paso»).
4. **«Responde siempre» o «nunca digas que no sabes»**: obligan a inventar.
5. **Solo negaciones** («no hables de X»). Di también qué hacer: «explica que no es tu tarea y deriva».
6. **Prompts enormes.** Corto, claro y probado gana a largo y confuso.
7. **Prometer conexiones que no existen** (correo, WhatsApp, bases de datos). Si no se conectó, es «diseño pendiente».
8. **Datos reales o personales** sin autorización de la empresa.
9. **Cambiar tres cosas y no saber cuál funcionó.**
10. **Confiar porque la respuesta suena convincente.** Compárala con la fuente y con tu tabla de pruebas.

## Para consultar
- **Memoria y contexto:** el asistente puede recordar dentro del chat; en otros chats, no siempre. Si el chat se alarga y se confunde, abre uno nuevo y pega tu system prompt. No todas las herramientas gratuitas manejan la memoria igual.
- **Personal, de tarea y de equipo:** personal es cómo te gusta que responda (tono, idioma); de tarea son las reglas de una tarea concreta; de equipo son reglas compartidas. En la hackatón, acuerden **una** versión.
- **Adjunto ≠ conector:** un archivo adjunto es una foto de hoy; un conector consulta y se actualiza. Si la fuente cambió, la respuesta puede quedar desactualizada.
- **Dos versiones de la misma fuente:** decide cuál manda y escríbelo como regla.
