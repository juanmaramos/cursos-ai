# Lección 2.1 — Sintetizar múltiples documentos

**Duración estimada:** 20 minutos
**Beat del story arc:** Beat 3 — El momento de escala
**Objetivo:** Al terminar esta lección, has generado un reporte de síntesis con fuentes citadas a partir de 10 entrevistas de usuarios.

---

## [INICIO]

El Módulo 1 te enseñó el patrón básico. Esta lección lo aplica a un problema real de escala.

Tienes 10 entrevistas de usuarios. Leerlas una por una tarda 45-60 minutos. Identificar los patrones entre ellas tarda otro tanto. Redactar un reporte estructurado con citas y fuentes: otra hora más. En total, entre dos y tres horas para un entregable que el equipo de producto necesita para tomar decisiones.

En esta lección vas a delegar ese proceso completo. Al final tienes un reporte de síntesis con temas principales, contradicciones entre fuentes y preguntas sin responder — listo para compartir.

Escribe **"listo"** para empezar.

---

## [DESPUÉS DE "listo"]

La carpeta `modulo-2/leccion-2-1/practica/` tiene 10 entrevistas de usuarios reales de un proceso de discovery de producto.

Cada entrevista tiene: perfil del usuario, problema principal, uso actual, reacción al producto y objeciones.

Antes de delegar, aplica el framework:

**¿Cómo se ve esto cuando esté terminado?**
Un reporte de síntesis en Word con patrones identificados, citas textuales con nombre de archivo fuente y preguntas de producto sin responder.

**¿Qué contexto necesita Claude?**
Que los archivos son entrevistas de usuario, que el objetivo es identificar patrones —no resumir cada entrevista por separado— y que el destinatario es un equipo de producto.

**¿Qué restricciones importan?**
No inventar citas. Cada afirmación debe tener el archivo fuente entre paréntesis. No hacer un resumen por entrevista — hacer síntesis cruzada.

---

Ahora ejecuta:

→ Copia este prompt y envíalo aquí mismo:

```
Lee todos los archivos de la carpeta modulo-2/leccion-2-1/practica/.
Son 10 entrevistas de usuarios de un proceso de discovery de producto.

Genera un reporte de síntesis llamado REPORTE-DISCOVERY.docx con estas secciones:

1. Resumen ejecutivo (5-7 frases que capturen lo más importante)
2. Problemas principales (patrones que aparecen en más de una entrevista, con citas textuales y nombre del archivo fuente)
3. Comportamiento actual (cómo resuelven hoy el problema sin el producto)
4. Señales de valor (qué generó interés o entusiasmo en los usuarios)
5. Objeciones recurrentes (qué frena la adopción)
6. Segmentos diferenciados (si hay perfiles con necesidades distintas, descríbelos)
7. Preguntas sin responder para el equipo de producto

Regla: no resumir cada entrevista por separado. Sintetizar patrones entre todas.
Regla: cada afirmación debe citar el archivo fuente entre paréntesis. Ej: (entrevista-usuario-03-valentina.txt)
No inventes información que no esté en los archivos.
```

Vuelve cuando Cowork haya generado el archivo.

---

## [DESPUÉS DE LA EJECUCIÓN]

Abre `REPORTE-DISCOVERY.docx`.

Revisa con este checklist específico para síntesis de entrevistas:

**1. ¿Los patrones son reales?**
Abre dos entrevistas al azar. ¿Las citas que aparecen en el reporte están realmente en esos archivos?

**2. ¿Hay síntesis o hay resumen?**
Si el reporte describe cada entrevista por separado, Claude no sintetizó — enumeró.
Si el reporte dice "7 de 10 usuarios mencionaron X", eso es síntesis. Es lo que quieres.

**3. ¿Las objeciones son concretas?**
Las objeciones deben ser específicas: "falta de app móvil", "dudas sobre seguridad de datos".
Si son vagas ("algunos usuarios tenían dudas"), el reporte necesita un ajuste.

**4. ¿Las preguntas sin responder son accionables?**
Deben ser preguntas que el equipo de producto puede investigar o responder. No preguntas retóricas.

Si algo necesita ajuste, díselo a Claude directamente.

Cuando el reporte te convenza, escribe **"listo"**.

---

## [CIERRE]

Lo que tienes ahora:
- Un reporte de síntesis de 10 entrevistas con patrones, citas y fuentes
- La habilidad de escalar este mismo patrón a 30, 50 o 100 documentos
- El criterio para distinguir síntesis real de enumeración disfrazada

El patrón que usaste:
1. Definiste el tipo de análisis (síntesis cruzada, no resumen individual)
2. Especificaste las secciones y las reglas de citación
3. Revisaste que las citas son reales y los patrones son de verdad patrones

Esto funciona para cualquier conjunto de documentos relacionados: transcripciones de reuniones, reportes de cliente, artículos de investigación, feedback de producto.

Lección 2.1 completada.

Escribe **"siguiente"** para ir a la Lección 2.2.
Escribe **"repetir"** si quieres aplicarlo a tus propios documentos.
Escribe **"ayuda"** si el reporte generado no tiene la estructura que esperabas.
