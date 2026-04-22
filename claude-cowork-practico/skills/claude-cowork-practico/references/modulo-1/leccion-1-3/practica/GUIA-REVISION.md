# Guía de revisión — Lección 1.3

El resumen `RESUMEN-EJEMPLO-CON-ERRORES.md` tiene tres errores intencionales.
Tu tarea: encontrarlos y corregirlos sin rehacer el documento desde cero.

---

## Pista

Lee el resumen y luego contrasta con los archivos originales del proyecto.
Los errores son de contenido (datos incorrectos), no de formato.

---

## Los errores (no leer hasta intentarlo)

<details>
<summary>Ver respuestas</summary>

**Error 1 — Presupuesto**
El resumen dice 48.000 EUR. El documento original dice 54.000 EUR (con HubSpot año 1), que es el presupuesto aprobado por Marcos.

**Error 2 — CRM**
El resumen dice Salesforce. Marcos eligió HubSpot en la llamada del 22 de enero.

**Error 3 — Contradicciones**
El resumen dice "ninguna detectada". Pero hay una contradicción real: la propuesta de gestor de contenidos (Ana) dice que necesita 2-4 semanas adicionales, lo que entra en conflicto con el deadline del 15 de abril confirmado por Marcos.

</details>

---

## Tu tarea

Después de encontrar los errores, escribe un prompt a Claude que corrija solo los tres puntos incorrectos.
No le pidas que rehaga el documento completo.

Ejemplo de prompt bien escrito:
```
En el archivo RESUMEN-EJEMPLO-CON-ERRORES.md hay tres errores de contenido.
Corrígelos:
1. El CRM elegido es HubSpot, no Salesforce. Fuente: llamada-marcos-22ene.txt
2. El presupuesto aprobado es 54.000 EUR con HubSpot. Fuente: presupuesto Q1 2024.txt
3. Hay una contradicción entre el plazo del 15 de abril y las semanas adicionales que necesita el gestor de contenidos. Añádelo en la sección "Contradicciones detectadas".
Guarda el archivo corregido como RESUMEN-CORREGIDO.md.
```
