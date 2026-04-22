# Lección 4.2 — Skills personalizadas

**Duración estimada:** 25 minutos
**Beat del story arc:** Beat 4 — El sistema propio
**Objetivo:** Al terminar esta lección, has creado tu propia skill en markdown y la has aplicado a una tarea real con mejor resultado que sin ella.

---

## [INICIO]

Hasta ahora le has dado instrucciones a Claude tarea por tarea. Cada vez que quieres un briefing, un resumen o un informe, repites las mismas instrucciones. Eso funciona para tareas ocasionales. Para tareas recurrentes, es fricción que se acumula.

Una skill es una forma de escribir esas instrucciones una sola vez. Cualquier prompt futuro puede referenciarla. Si quieres cambiar el formato de tus briefings, cambias la skill una vez — no cada prompt individualmente.

En esta lección vas a crear tu propia skill de briefing y aplicarla a un caso real. Al final tienes una skill funcional en tu carpeta de trabajo que puedes usar desde mañana.

Escribe **"listo"** para empezar.

---

## [DESPUÉS DE "listo"]

### Qué es una skill en Cowork

Una skill es un archivo markdown en tu carpeta de trabajo.
Describe cómo quieres que Claude haga un tipo de tarea específico: la estructura, el tono, las reglas y un ejemplo del output esperado.

Cuando quieres usar la skill, le dices a Claude: "Lee el archivo [nombre-skill].md y aplícalo para hacer X."

Claude lee la skill, interioriza las instrucciones y produce el output con tu formato y tu estilo.

---

### Cuándo vale la pena crear una skill

Crea una skill cuando:
- Haces el mismo tipo de tarea más de 3 veces por semana
- El resultado de Claude es bueno pero siempre necesitas el mismo tipo de ajuste
- Tienes un estilo o estructura que Claude debería mantener sin que tengas que repetirlo

No crees una skill para tareas que haces una sola vez o que varían completamente cada vez.

---

### Estructura de una skill

Tienes en la carpeta `modulo-4/leccion-4-2/practica/` dos archivos:
- `EJEMPLO-SKILL-BRIEFING.md` — una skill de ejemplo ya creada (para briefings de contenido)
- `INSTRUCCIONES-CREAR-TU-SKILL.md` — la plantilla y el proceso

Ábrelo desde aquí directamente:

[Genera un enlace computer:// al archivo EJEMPLO-SKILL-BRIEFING.md en modulo-4/leccion-4-2/practica/ usando la ruta real de la carpeta del curso montada. Texto del enlace: "Abrir EJEMPLO-SKILL-BRIEFING.md"]

Cuando lo hayas leído, escribe **"leído"**.

---

## [DESPUÉS DE "leído"]

Ahora vamos a hacer dos cosas:

**Parte A** — Probar la skill de ejemplo con una tarea real
**Parte B** — Crear tu propia skill para una tarea de tu trabajo

---

### Parte A: Probar la skill de ejemplo

→ Copia este prompt y envíalo aquí mismo:

```
Lee el archivo modulo-4/leccion-4-2/practica/EJEMPLO-SKILL-BRIEFING.md.
Usa las instrucciones de ese archivo para crear un briefing de contenido con estos datos:

Tema: lanzamiento de un nuevo plan de suscripción anual con descuento del 30%
Red social: LinkedIn
Objetivo: conversión (llevar tráfico a la página de precios)
Audiencia: profesionales independientes y pequeñas empresas
Restricciones del cliente: no mencionar competidores, tono directo sin exclamaciones

Guarda el resultado como modulo-4/leccion-4-2/practica/BRIEFING-PRUEBA.md
```

Vuelve cuando Cowork haya generado el archivo.

---

## [DESPUÉS DE LA PARTE A]

Abre `BRIEFING-PRUEBA.md`.

Compara la estructura con la skill de ejemplo. ¿Tiene las mismas secciones? ¿El tono coincide con lo que describiste en la skill?

Si el output sigue la skill correctamente, la mecánica funciona. Si tiene secciones de más o de menos, revisa si la skill tenía esas secciones definidas o si Claude tomó decisiones adicionales.

Cuando estés conforme, escribe **"parte b"**.

---

## [PARTE B]

Ahora crea tu propia skill.

Piensa en una tarea que repites en tu trabajo. Puede ser: resúmenes de reuniones, análisis de feedback, emails a clientes, reportes de estado de proyecto, lo que sea.

→ Copia este prompt y envíalo aquí mismo:

```
Voy a crear una skill para [describe la tarea que repites].

El output que quiero es: [describe el resultado]
La estructura que quiero: [enumera las secciones o pasos]
El tono: [describe cómo debe sonar]
Las reglas que siempre aplico: [lo que siempre haces igual]
Un ejemplo de output bueno: [describe o escribe un ejemplo]

Con esa información, genera el archivo MI-SKILL.md en la carpeta modulo-4/leccion-4-2/practica/,
siguiendo la estructura del archivo INSTRUCCIONES-CREAR-TU-SKILL.md.
```

Vuelve cuando Cowork haya generado el archivo.

---

## [DESPUÉS DE LA PARTE B]

Abre `MI-SKILL.md` y léela como si fueras Claude recibiéndola por primera vez.

Pregúntate: ¿si leo esto sin contexto previo, sé exactamente cómo hacer la tarea?

Si hay ambigüedad — instrucciones que se podrían interpretar de dos formas — corrígelas antes de usar la skill.

Prueba la skill con una tarea real:

→ Copia este prompt, ajústalo a tu tarea y envíalo aquí mismo:

```
Lee el archivo modulo-4/leccion-4-2/practica/MI-SKILL.md.
Usa las instrucciones de ese archivo para [describe la tarea concreta].
Guarda el resultado como modulo-4/leccion-4-2/practica/PRUEBA-MI-SKILL.md.
```

---

## [CIERRE]

Lo que tienes ahora:
- Una skill de ejemplo aplicada y verificada con output correcto
- Tu propia skill creada para una tarea real de tu trabajo
- El patrón para iterar skills: prueba, ajusta la ambigüedad, vuelve a probar

El criterio para saber cuándo crear una skill: tarea recurrente (más de 3 veces por semana) más un ajuste que siempre repites = buen caso de uso para una skill. Si la tarea varía cada vez, no vale la pena.

El patrón que usaste:
1. Definiste la tarea, la estructura, el tono y las reglas antes de escribir la skill
2. Probaste con un caso concreto antes de usarla en producción
3. Revisaste la skill como si fueras el que la recibe, no el que la escribió

Una skill que se usa durante semanas evoluciona. Cada vez que el output no es exactamente lo que quieres, ajusta la skill. No el prompt.

Lección 4.2 completada.

Escribe **"siguiente"** para ir a la Lección 4.3.
Escribe **"repetir"** si quieres crear otra skill para una segunda tarea recurrente.
Escribe **"ayuda"** si la skill no produce el formato que esperabas.
