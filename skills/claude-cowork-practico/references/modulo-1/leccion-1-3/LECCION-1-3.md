# Lección 1.3 — Cómo revisar el trabajo de Claude

**Duración estimada:** 20 minutos
**Beat del story arc:** Beat 2 — La primera victoria (consolidación)
**Objetivo:** Al terminar esta lección, sabes cuándo aceptar el resultado de Claude, cuándo pedir una revisión y cuándo añadir contexto para mejorar el output.

---

## [INICIO]

En la Lección 1.2 generaste un resumen ejecutivo. Ahora la pregunta es: ¿cómo sabes si está bien?

Esta es la habilidad que más diferencia a quienes aprovechan bien Cowork de quienes no. No es revisar cada palabra — es saber qué verificar, cuándo confiar y cuándo pedir una corrección con el dato exacto.

En esta lección vas a trabajar con un resumen ejecutivo que tiene errores reales. Al final sabes identificar los tres tipos de resultado que Cowork produce y cómo responder a cada uno sin rehacer el trabajo desde cero.

Escribe **"listo"** para empezar.

---

## [DESPUÉS DE "listo"]

### Los tres tipos de resultado

Cuando Cowork termina una tarea, el resultado es uno de estos tres:

**Tipo A — Listo para usar**
El output cumple lo que pediste. Puedes compartirlo, enviarlo o guardarlo directamente.
No necesitas revisión adicional.

**Tipo B — Necesita un ajuste pequeño**
El output tiene la estructura correcta pero hay algo concreto que cambiar: un dato incorrecto, una sección que falta, un tono que no es el tuyo.
Díselo a Claude directamente. No rehaces todo desde cero.

**Tipo C — Necesita rehacerse**
El output no se parece a lo que pediste. Suele pasar cuando faltó contexto en el prompt original.
En este caso, no sirve corregir el output. Hay que mejorar el prompt y volver a ejecutar.

La clave es identificar cuál de los tres tienes antes de decidir qué hacer.

---

### Qué revisar siempre (en 2 minutos)

Para cualquier documento generado por Claude, revisa estos cuatro puntos:

**1. Datos críticos**
Los números, fechas, nombres y decisiones que aparecen en el documento son correctos.
Claude puede cometer errores con datos concretos si los interpreta de varios archivos con información conflictiva.

**2. Fuentes citadas**
Si el documento cita archivos fuente, abre uno de ellos y verifica que la cita es fiel al original.
Claude no inventa citas habitualmente, pero puede parafrasear de forma imprecisa.

**3. Secciones completas**
Están todas las secciones que pediste. Ninguna está vacía o con contenido genérico.

**4. Tono y audiencia**
El tono es el que especificaste. Si pediste "directo para directivo" y el resultado suena como un correo informal, hay que ajustar.

---

## [EJERCICIO]

Tienes en la carpeta `modulo-1/leccion-1-3/practica/` un archivo llamado `RESUMEN-EJEMPLO-CON-ERRORES.md`.

Es un resumen ejecutivo del proyecto de la Lección 1.2, pero tiene tres errores de contenido intencionales — datos incorrectos y una contradicción no detectada.

No los busques tú. Delégalo.

→ Copia este prompt y envíalo aquí mismo:

```
Compara el archivo modulo-1/leccion-1-3/practica/RESUMEN-EJEMPLO-CON-ERRORES.md
con los archivos originales de modulo-1/leccion-1-2/practica/.

Encuentra errores de contenido: datos incorrectos, cifras que no coinciden
con los originales, o contradicciones entre documentos no detectadas.

Lista cada error con:
- Qué dice el resumen
- Qué dicen los archivos originales
- En qué archivo original está la información correcta
```

Vuelve cuando Claude haya completado el análisis.

---

## [DESPUÉS DEL ANÁLISIS]

Revisa lo que encontró Claude. Los tres errores reales son:

1. **CRM incorrecto** — el resumen dice Salesforce. Marcos eligió HubSpot (llamada del 22 de enero).
2. **Presupuesto incorrecto** — el resumen dice 48.000 EUR. El presupuesto aprobado es 54.000 EUR.
3. **Contradicción no detectada** — el resumen dice "ninguna". Hay una real: el gestor de contenidos necesita 2-4 semanas adicionales, en conflicto con el deadline del 15 de abril.

¿Los encontró todos? Si sí, el prompt de verificación funcionó. Si faltó alguno, es señal de que hay que ser más explícito sobre qué tipo de error buscar — eso también es parte de aprender a revisar.

Ahora corrígelos en una sola instrucción.

→ Copia este prompt y envíalo aquí mismo:

```
En el archivo modulo-1/leccion-1-3/practica/RESUMEN-EJEMPLO-CON-ERRORES.md
hay tres errores de contenido. Corrígelos:
1. CRM: cambia Salesforce por HubSpot
2. Presupuesto: cambia 48.000 EUR por 54.000 EUR
3. Contradicciones: añade la tensión real entre el plazo del gestor de contenidos
   (2-4 semanas adicionales) y el deadline del 15 de abril

Guarda el resultado como modulo-1/leccion-1-3/practica/RESUMEN-CORREGIDO.md.
No cambies nada más.
```

Vuelve cuando Cowork haya generado el archivo.

---

## [DESPUÉS DE LA CORRECCIÓN]

Abre `RESUMEN-CORREGIDO.md` y confirma que los tres puntos están corregidos.

Si están correctos, el ejercicio está completo.

Si alguno no se corrigió bien, díselo a Claude con el dato exacto:
> "En la sección de presupuesto sigue apareciendo 48.000 EUR. El dato correcto es 54.000 EUR según el archivo presupuesto Q1 2024.txt."

Así es como se itera: corrección puntual, fuente clara, sin rehacer el documento entero.

---

## [CIERRE]

Lo que tienes ahora:
- Los tres tipos de resultado (listo, ajuste pequeño, rehacer)
- Los cuatro puntos que revisar siempre en cualquier output
- La práctica de corregir sin rehacer: corrección puntual con fuente, en lugar de empezar desde cero

El Módulo 1 está completo.

Has organizado archivos, generado un resumen ejecutivo y aprendido a revisar el trabajo de Claude. Eso es lo que cuesta 2-3 horas hacerlo manualmente. Lo hiciste en tres lecciones.

A partir del Módulo 2 el trabajo se pone más complejo: más documentos, más fuentes, outputs más exigentes. El patrón es el mismo.

Escribe **"siguiente"** para ir al Módulo 2.
Escribe **"repetir"** si quieres practicar la revisión con un documento tuyo.
Escribe **"resumen"** para ver qué has aprendido en el Módulo 1.
