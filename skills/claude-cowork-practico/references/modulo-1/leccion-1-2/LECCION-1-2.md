# Lección 1.2 — Tu primera delegación real

**Duración estimada:** 25 minutos
**Beat del story arc:** Beat 2 — La primera victoria
**Objetivo:** Al terminar esta lección, has organizado una carpeta caótica y generado un resumen ejecutivo en una sola sesión de Cowork.

**Archivos necesarios:**
- `modulo-1/leccion-1-2/practica/` — carpeta con 10 archivos de práctica mezclados (notas de reunión, brief, feedback, facturas)
- Este archivo de lección

---

## [INICIO]

Lección 1.2 — Tu primera delegación real.

Hasta ahora entiendes qué es Cowork y cómo funciona el framework "Listo". Ahora lo vas a usar con archivos reales.

Esta lección tiene dos partes:
- Parte A: organizas una carpeta caótica
- Parte B: sintetizas esos archivos en un resumen ejecutivo

Al final tienes un entregable que puedes compartir. No un ejercicio — trabajo real.

Escribe **"listo"** para empezar.

---

## [DESPUÉS DE "listo"]

Bien. Primero, mira la carpeta `modulo-1/leccion-1-2/practica/`.

Tiene 10 archivos. Nombres inconsistentes, fechas mezcladas, tipos de documento distintos. Esto es lo que tienes en tu carpeta de trabajo real la mayor parte del tiempo.

Antes de pedirle algo a Claude, aplica el framework "Listo":

**Pregunta 1: ¿Cómo se ve esto cuando esté terminado?**
Piénsalo un momento. No escribas nada todavía.

Una posible respuesta: subcarpetas por tipo de documento, archivos renombrados con fecha y descripción, un log de qué se movió.

**Pregunta 2: ¿Qué contexto necesita Claude?**
En este caso: que no borre nada, que use el formato de fecha AAAA-MM-DD, y que cree el log en un archivo separado.

**Pregunta 3: ¿Qué restricciones importan?**
La más importante siempre: no borrar archivos. Solo mover y renombrar.

Ahora escribe el prompt. Usa esta base y ajústala:

→ Copia este prompt y envíalo aquí mismo:

```
Organiza todos los archivos de la carpeta modulo-1/leccion-1-2/practica/.
Agrúpalos en subcarpetas por tipo de documento.
Renombra cada archivo con el formato AAAA-MM-DD-descripcion-breve.
No borres nada. Solo mueve y renombra.
Cuando termines, crea un archivo llamado LOG-ORGANIZACION.md
que liste cada archivo: nombre original → nombre nuevo → carpeta destino.
```

Vuelve cuando Cowork haya terminado.

---

## [DESPUÉS DE LA PARTE A]

Revisa el resultado antes de continuar.

Abre `LOG-ORGANIZACION.md`. Comprueba tres cosas:
1. ¿Están todos los archivos originales? No debe faltar ninguno.
2. ¿Los nombres tienen sentido? Si no los entiendes, pide a Claude que los renombre con más claridad.
3. ¿Las subcarpetas tienen lógica para tu forma de trabajar?

Si algo no está bien, díselo a Claude directamente:
> "El archivo X está en la carpeta equivocada. Muévelo a Y."
> "Renombra los archivos de la carpeta Z con descripciones más específicas."

Esto es revisar sin micromanagear: corriges el resultado, no el proceso.

Cuando el resultado te convenza, escribe **"parte b"**.

---

## [PARTE B]

Ahora tienes 10 archivos organizados. El siguiente paso es convertirlos en algo útil.

Vas a pedirle a Claude que los lea todos y genere un resumen ejecutivo.

Un resumen ejecutivo tiene una estructura concreta:
- Contexto: de dónde viene esta información
- Temas principales: qué aparece en múltiples documentos
- Contradicciones o tensiones: dónde los documentos no coinciden
- Preguntas sin responder: qué falta saber
- Próximos pasos sugeridos

→ Copia este prompt y envíalo aquí mismo:

```
Lee todos los archivos de la carpeta modulo-1/leccion-1-2/practica/.
Crea un resumen ejecutivo en formato Word llamado RESUMEN-EJECUTIVO.docx.

Incluye estas secciones:
1. Contexto (de dónde viene esta información, en 2-3 frases)
2. Temas principales (con citas textuales y el nombre del archivo fuente)
3. Contradicciones o tensiones entre documentos
4. Preguntas que quedan sin responder
5. Próximos pasos sugeridos

Tono: profesional, directo. Audiencia: un directivo que no leyó los documentos originales.
```

Envía el prompt. Vuelve cuando Cowork haya generado el archivo.

---

## [CIERRE DE LECCIÓN]

Abre `RESUMEN-EJECUTIVO.docx`.

Lo que tienes ahora:
- Una carpeta organizada con criterio
- Un documento estructurado listo para compartir
- Un log de cada decisión que tomó Claude

Esto es lo que tardabas 2-3 horas en hacer manualmente. Lo hiciste en una sesión.

El patrón que usaste:
1. Definiste qué significa "listo"
2. Diste contexto y restricciones
3. Revisaste el resultado sin rehacer el trabajo desde cero
4. Iteraste solo donde era necesario

Ese patrón funciona para cualquier tarea de Cowork. En las próximas lecciones lo vas a aplicar con más complejidad.

Lección 1.2 completada.

Escribe **"siguiente"** para ir a la Lección 1.3, o **"repetir"** si quieres practicar con tus propios archivos.

---

## [SI ESCRIBE "repetir"]

Bien. Apunta a una carpeta real de tu computadora.

Usa el mismo framework: qué significa listo, qué contexto necesita Claude, qué restricciones importan.

El único cambio en el prompt: reemplaza `modulo-1/leccion-1-2/practica/` con la ruta de tu carpeta.

Cuando termines, escribe **"siguiente"** para continuar.
