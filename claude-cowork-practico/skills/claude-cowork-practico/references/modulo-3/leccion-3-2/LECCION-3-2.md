# Lección 3.2 — Presentaciones desde documentos dispersos

**Duración estimada:** 20 minutos
**Beat del story arc:** Beat 3 — El momento de escala
**Objetivo:** Al terminar esta lección, has generado un PowerPoint estructurado con notas del presentador a partir de notas estratégicas y datos de KPIs.

---

## [INICIO]

Preparar una presentación de revisión trimestral tarda horas. La mayor parte del tiempo no se va en diseñar — se va en decidir qué poner en cada diapositiva, en qué orden, y qué decir en cada una.

Si tienes los documentos de origen, esa estructura la puede proponer Cowork. Tú revisas, ajustas el mensaje donde tu criterio importa, y sales con un archivo listo.

En esta lección vas a convertir notas estratégicas y datos de KPIs en un PowerPoint de revisión de Q1 con ocho diapositivas, estructura narrativa y notas del presentador en cada slide. Al final tienes una presentación lista para llevar al equipo directivo.

Escribe **"listo"** para empezar.

---

## [DESPUÉS DE "listo"]

La carpeta `modulo-3/leccion-3-2/practica/` tiene dos archivos:
- `notas-estrategia-2024.txt` — notas internas del equipo directivo con prioridades, riesgos y decisiones pendientes para 2024
- `datos-kpi-q1-2024.txt` — los KPIs del primer trimestre con métricas de ingresos, rentabilidad, ventas y alertas

En esta lección vas a convertir notas dispersas y datos de KPIs en una presentación de revisión trimestral lista para presentar al equipo directivo. Antes de ejecutar, aplicamos el framework "Listo":

**¿Cómo se ve esto cuando esté terminado?**
Un PowerPoint de 8-10 diapositivas con estructura narrativa: contexto, resultados, riesgos, próximos pasos. Cada diapositiva con notas del presentador.

**¿Qué contexto necesita Claude?**
Que es una revisión de Q1 para el equipo directivo. Que el tono es directo y los datos son concretos. Que las notas del presentador deben explicar qué decir en cada diapositiva, no repetir el texto de la slide.

**¿Qué restricciones importan?**
Usar solo los datos de los archivos. No añadir benchmarks externos ni datos que no estén en las notas. Marcar las métricas que superan o no llegan a la meta.

---

→ Copia este prompt y envíalo aquí mismo:

```
Lee los archivos de la carpeta modulo-3/leccion-3-2/practica/:
- notas-estrategia-2024.txt
- datos-kpi-q1-2024.txt

Genera REVISION-Q1-2024.pptx con esta estructura:

Diapositiva 1 — Portada: título, fecha, empresa (usa "Empresa" como placeholder)
Diapositiva 2 — Contexto: dónde estábamos al cerrar 2023 y qué nos propusimos para 2024
Diapositiva 3 — Resultados de ingresos Q1: métricas clave con indicación de si superan o no la meta
Diapositiva 4 — Rentabilidad Q1: margen, progreso vs meta, qué falta
Diapositiva 5 — Equipo y ventas: headcount, productividad, pipeline y tasa de cierre
Diapositiva 6 — Riesgos activos: los tres riesgos más importantes del negocio ahora mismo
Diapositiva 7 — Decisiones pendientes para Q2: las decisiones que el directivo tiene que tomar
Diapositiva 8 — Próximos pasos: las tres acciones prioritarias con responsable y fecha si aparecen

Cada diapositiva debe tener:
- Máximo 5 bullets o datos en pantalla
- Notas del presentador: qué decir en esa diapositiva (2-4 frases, no repetir los bullets)

Usa solo datos de los archivos. Si un dato supera la meta, señálalo con ✓. Si no llega, con ⚠.
```

Vuelve cuando Cowork haya generado el archivo.

---

## [DESPUÉS DE LA EJECUCIÓN]

Di una frase con los datos estructurales del archivo generado: número de diapositivas, si todas tienen notas del presentador, y los dos o tres datos clave que verificaste contra los archivos fuente. No describas el diseño visual — eso el learner lo ve al abrir el archivo.

Antes de dar por buena cualquier presentación generada, hay cuatro cosas que verificar:

Abre `REVISION-Q1-2024.pptx` en modo presentación y comprueba:

**1. ¿La narrativa tiene sentido?**
Lee las diapositivas en orden como si las fueras a presentar. ¿El mensaje fluye? ¿Hay algún salto lógico entre diapositivas?

**2. ¿Las notas del presentador son útiles?**
Abre la vista de notas en una o dos diapositivas. ¿Explican qué decir o simplemente repiten los bullets?
Si repiten el texto de la slide, pide que las reescriba con lo que el presentador debería enfatizar.

**3. ¿Los datos están correctos?**
Verifica dos o tres métricas contra el archivo `datos-kpi-q1-2024.txt`.
Las cifras en la presentación deben coincidir exactamente con las del archivo.

**4. ¿Los indicadores ✓ y ⚠ son correctos?**
Comprueba que están donde corresponde. Un ✓ en una métrica que no llegó a la meta sería un error relevante.

Si algo necesita ajuste, díselo a Claude con el número de diapositiva y la corrección específica.

---

## [CIERRE]

Lo que tienes ahora:
- Una presentación de 8 diapositivas con estructura narrativa y notas del presentador
- Los datos de Q1 presentados de forma que el directivo puede tomar decisiones
- El patrón para generar cualquier presentación de revisión o status desde documentos existentes

El patrón que usaste:
1. Definiste la estructura diapositiva a diapositiva antes de ejecutar
2. Pediste notas del presentador separadas del texto en pantalla
3. Añadiste indicadores de meta para que los datos sean inmediatamente interpretables

Cuando defines la estructura tú, la presentación tiene tu lógica. Si lo dejas abierto, Claude elige una estructura por defecto que puede no ser la que necesitas.

Lección 3.2 completada.

Escribe **"siguiente"** para ir a la Lección 3.3.
Escribe **"repetir"** si quieres generar una presentación desde tus propios documentos.
Escribe **"ayuda"** si la estructura de la presentación no era lo que esperabas.
