# Lección 2.3 — De notas de reunión a entregable ejecutivo

**Duración estimada:** 20 minutos
**Beat del story arc:** Beat 3 — El momento de escala
**Objetivo:** Al terminar esta lección, has convertido notas dispersas de distintos canales en un documento estructurado listo para compartir con el equipo.

---

## [INICIO]

Las notas de reunión son el input más caótico que existe.

Tienes notas rápidas tomadas a mano, mensajes de WhatsApp exportados, emails de confirmación de cliente. Todo habla del mismo proyecto pero en formatos completamente distintos. Convertir eso en un documento estructurado que puedas compartir tarda más tiempo del que debería.

En esta lección vas a convertir tres archivos de un proyecto de campaña en un único entregable ejecutivo. Al final tienes un documento con acuerdos tomados, decisiones pendientes y próximos pasos — listo para enviar al equipo.

Escribe **"listo"** para empezar.

---

## [DESPUÉS DE "listo"]

La carpeta `modulo-2/leccion-2-3/practica/` tiene tres archivos de un mismo proyecto de campaña de marketing:
- Notas rápidas de una reunión de equipo
- Un resumen de conversación de WhatsApp
- Un email de confirmación del cliente

Son el mismo proyecto visto desde tres canales distintos. Hay información que solo aparece en uno, hay cosas que se repiten, hay una contradicción sobre el canal TikTok.

Antes de delegar, aplica el framework:

**¿Cómo se ve esto cuando esté terminado?**
Un documento Word de una página con: decisiones tomadas, pendientes con responsable, preguntas abiertas y próximos pasos con fecha.

**¿Qué contexto necesita Claude?**
Que los tres archivos son del mismo proyecto. Que el destinatario es el equipo que asistió a las reuniones. Que las contradicciones entre fuentes deben señalarse, no resolverse.

**¿Qué restricciones importan?**
No inventar decisiones que no estén en los archivos. Si hay información contradictoria, señalarla sin resolverla. Los pendientes deben tener un responsable nombrado si aparece en las notas.

---

→ Copia este prompt y envíalo aquí mismo:

```
Lee los tres archivos de la carpeta modulo-2/leccion-2-3/practica/.
Son notas del mismo proyecto de campaña de marketing: notas de reunión, WhatsApp y email del cliente.

Genera ACTA-CAMPANA-VERANO.docx con estas secciones:

1. Decisiones confirmadas (solo las que están explícitamente acordadas en los documentos)
2. Pendientes con responsable (tarea + nombre + fecha si aparece)
3. Contradicciones o puntos sin cerrar (información que difiere entre fuentes)
4. Preguntas que el equipo necesita responder antes de avanzar
5. Próximos pasos con fecha

Tono: directo, para el equipo del proyecto.
Si una decisión aparece solo en un documento y no está confirmada en otro, márcala como "pendiente de confirmar".
No resuelvas contradicciones — señálalas para que el equipo las resuelva.
```

Vuelve cuando Cowork haya generado el archivo.

---

## [DESPUÉS DE LA EJECUCIÓN]

Abre `ACTA-CAMPANA-VERANO.docx`.

Este tipo de documento tiene un riesgo específico: Claude puede presentar como decisión confirmada algo que solo apareció en las notas rápidas pero no fue ratificado por el cliente.

Verifica estos tres puntos:

**1. ¿Las decisiones del cliente están en el email, no solo en las notas internas?**
El email del cliente es la fuente más fiable. Si algo está en las notas pero no en el email, no es una decisión confirmada.

**2. ¿Está señalada la contradicción de TikTok?**
Las notas internas mencionan evaluar TikTok. El email del cliente dice explícitamente que no quieren TikTok.
Si el documento no señala esta contradicción, pide la corrección.

**3. ¿Los pendientes tienen responsable?**
Algunos pendientes aparecen con nombre en las notas. Deben aparecer en el acta.
Si están sin responsable cuando en las notas sí lo tienen, señálaselo a Claude.

Cuando el documento esté correcto, escribe **"listo"**.

---

## [CIERRE]

Lo que tienes ahora:
- Un acta estructurada generada a partir de tres fuentes en formatos distintos
- La habilidad de convertir cualquier combinación de notas, mensajes y emails en un documento usable
- El criterio para distinguir una decisión confirmada de algo que está pendiente de confirmar

El patrón que usaste:
1. Definiste las secciones con precisión (decisiones, pendientes, contradicciones, próximos pasos)
2. Pediste explícitamente que señalara contradicciones en lugar de resolverlas
3. Verificaste las decisiones contra la fuente más fiable (el email del cliente)

Este mismo patrón funciona para actas de consejo, reuniones de equipo, llamadas de ventas o cualquier proyecto con inputs de varios canales.

Lección 2.3 completada. Con esto completas el Módulo 2.

Escribe **"siguiente"** para ir al Módulo 3.
Escribe **"repetir"** si quieres aplicarlo a tus propias notas de reunión.
Escribe **"resumen"** para ver qué has aprendido en el Módulo 2.
