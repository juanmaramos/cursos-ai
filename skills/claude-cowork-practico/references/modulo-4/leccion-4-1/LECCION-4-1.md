# Lección 4.1 — Sub-agentes: trabajo en paralelo

**Duración estimada:** 20 minutos
**Beat del story arc:** Beat 4 — El sistema propio
**Objetivo:** Al terminar esta lección, entiendes cuándo Cowork paraleliza tareas automáticamente, cómo estructurar un prompt multi-parte para aprovecharlo, y cuáles son sus límites reales.

---

## [INICIO]

Módulo 4. Hasta aquí has trabajado con tareas de una sola parte: organiza esto, sintetiza esto, genera este documento.

El problema con ese modelo es que sigue siendo lineal. Envías una tarea, esperas el resultado, envías la siguiente. Si tienes cinco tareas independientes entre sí, tardas cinco rondas completas.

En este módulo trabajas de otra forma: asignas un bloque de trabajo, Cowork lo divide en partes independientes y ejecuta varias a la vez.

En esta lección vas a entender cómo funcionan los sub-agentes y cuándo Cowork los activa automáticamente. Al final sabes estructurar tareas multi-parte para aprovecharlo — y cuándo no merece la pena.

Escribe **"listo"** para empezar.

---

## [DESPUÉS DE "listo"]

### Qué son los sub-agentes

Cuando Cowork recibe una tarea que tiene partes independientes entre sí, puede dividirla y ejecutar varias partes a la vez. Cada parte se ejecuta como un sub-agente.

Ejemplo: si le pides que genere tres informes distintos de tres carpetas distintas, puede generarlos en paralelo en lugar de uno tras otro.

No es algo que tú configures manualmente. Cowork decide cuándo paralelizar según la estructura de la tarea que le das.

Tu trabajo es estructurar el prompt de forma que esas partes independientes sean visibles.

---

### Cuándo paraleliza Cowork (y cuándo no)

**Paraleliza cuando:**
- Las partes no dependen entre sí (el resultado de A no es input de B)
- Cada parte opera sobre archivos distintos
- Las partes tienen el mismo tipo de output

**No paraleliza cuando:**
- Una parte necesita el resultado de otra (primero la tabla, luego el análisis)
- Las partes comparten los mismos archivos de origen y podrían generar conflictos
- La tarea tiene una lógica secuencial clara

La señal de que estás estructurando bien el prompt: puedes enumerar las partes y ninguna depende de la anterior.

---

### Cómo estructurar un prompt multi-parte

→ Copia este prompt y envíalo aquí mismo:

```
Tengo tres tareas independientes. Ejecútalas en paralelo si es posible:

Tarea 1: Lee los archivos de modulo-2/leccion-2-1/practica/.
Genera un resumen de 5 frases de los hallazgos principales de las entrevistas.
Guárdalo como RESUMEN-ENTREVISTAS.md en esta carpeta.

Tarea 2: Lee los archivos de modulo-2/leccion-2-2/practica/.
Genera una lista de los tres puntos de diferenciación más importantes frente a los competidores.
Guárdala como DIFERENCIACION.md en esta carpeta.

Tarea 3: Lee los archivos de modulo-2/leccion-2-3/practica/.
Extrae todos los pendientes con responsable y fecha que aparezcan en los documentos.
Guárdalos como PENDIENTES-CAMPANA.md en esta carpeta.

Las tres tareas son independientes. No necesitas el resultado de una para hacer las otras.
```

Vuelve cuando Cowork haya terminado las tres tareas.

---

## [DESPUÉS DE LA EJECUCIÓN]

Abre los tres archivos generados.

Comprueba:
1. ¿Se generaron los tres? Si falta alguno, Cowork procesó las tareas en secuencia y una puede haber fallado silenciosamente.
2. ¿El contenido es correcto para cada carpeta? Cada resumen debe referirse a los archivos de su carpeta correspondiente, no mezclar información.
3. ¿Cuánto tardó? Si las tres tareas tardaron notablemente menos que si las hubieras ejecutado una por una, hubo paralelización real.

---

### Los límites que necesitas conocer

**Límite 1 — No todo se paraleliza**
Si el prompt tiene dependencias entre partes, Cowork las ejecuta en secuencia. No hay forma de forzar la paralelización si las partes no son realmente independientes.

**Límite 2 — Más partes no siempre significa más velocidad**
A partir de cierto número de sub-agentes simultáneos, la ganancia de tiempo se reduce. Para tareas de 2-4 partes la mejora es clara. Para 10+ partes puede variar.

**Límite 3 — El control de calidad es tu responsabilidad**
Cuando Cowork trabaja en paralelo, tú revisas el resultado de cada parte por separado. No hay un paso de integración automático salvo que lo pidas explícitamente.

---

## [CIERRE]

Lo que tienes ahora:
- El concepto de sub-agentes sin mistificar: Cowork decide cuándo paralelizar, tú estructuras el prompt para que pueda hacerlo
- El criterio para saber cuándo un prompt es paralelizable: las partes son independientes entre sí
- Los límites reales para no sobreestimar qué resuelve esta función

El patrón que usaste:
1. Enumeraste las tareas claramente
2. Indicaste que son independientes
3. Revisaste cada output por separado

Lección 4.1 completada.

Escribe **"siguiente"** para ir a la Lección 4.2 (skills personalizadas).
Escribe **"repetir"** si quieres practicar con tus propias tareas en paralelo.
Escribe **"ayuda"** si alguna de las tres tareas no generó output correcto.
