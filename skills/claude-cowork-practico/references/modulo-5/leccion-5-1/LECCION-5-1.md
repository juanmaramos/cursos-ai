# Lección 5.1 — Cowork para PMs

**Duración estimada:** 25 minutos
**Beat del story arc:** Beat 5 — El rol amplificado
**Objetivo:** Al terminar esta lección, has aplicado Cowork a dos tareas centrales del trabajo de un PM: síntesis de research de usuarios y preparación de un PRD a partir de inputs dispersos.

---

## [INICIO]

Módulo 5. El último módulo del curso. Hasta aquí has aprendido el sistema. Ahora lo aplicas a tu rol.

Este módulo tiene tres lecciones, una por perfil. Para llevarte directamente a la tuya, necesito saber cuál es.

Escribe **"listo"** para continuar.

---

## [DESPUÉS DE "listo"]

Usa AskUserQuestion con estos parámetros:
- **Pregunta:** "¿Cuál es tu perfil profesional?"
- **Opción A:** "Product Manager de producto"
- **Opción B:** "Founder o co-founder"
- **Opción C:** "Otro rol (marketing, ops, finanzas, RRHH, recruiting, administración...)"

---

## [SI ELIGE OPCIÓN A — Product Manager]

Si eres PM, sigue leyendo.

El trabajo de un PM tiene dos partes que consumen tiempo desproporcionado al valor que generan: sintetizar research de usuarios y redactar documentos de producto. Convertir inputs crudos en entregables utilizables lleva horas que no escalan cuando hay diez entrevistas, veinte tickets y tres stakeholders esperando.

En esta lección vas a aplicar Cowork a las dos: primero sintetizas entrevistas de usuarios, luego conviertes ese research en la estructura de un PRD. Al final tienes dos entregables reales y el patrón para replicarlo en tu próximo ciclo de discovery.

Escribe **"listo"** para empezar.

---

## [SI ELIGE OPCIÓN B — Founder]

"Tu lección es la 5.2. Escribe **'siguiente'** y arrancamos directamente ahí."

---

## [SI ELIGE OPCIÓN C — Otro rol]

"Tu lección es la 5.3 — cubre todos los perfiles de ops, marketing, finanzas, RRHH, consultoría y similares. Escribe **'siguiente'** y vamos directos ahí."

---

## [DESPUÉS DE "listo"]

La carpeta `modulo-5/leccion-5-1/practica/` tiene dos archivos:
- `notas-entrevistas-producto.txt` — notas de 12 entrevistas de un sprint de discovery para una app de gastos para freelancers
- `prd-borrador.txt` — un PRD en borrador con secciones incompletas y preguntas abiertas

Vas a trabajar con los dos en esta lección.

---

### Parte A: Síntesis de research para alimentar decisiones de producto

El problema habitual: tienes las notas de las entrevistas pero el equipo de ingeniería necesita una síntesis con prioridades claras, no un dump de observaciones.

Aplica el framework antes de delegar:

**¿Cómo se ve esto cuando esté terminado?**
Un documento de síntesis de research con: patrones de dolor priorizados, comportamiento actual del usuario, señales que apuntan a funcionalidades concretas y preguntas que el equipo de producto necesita responder.

**¿Qué contexto necesita Claude?**
Que es para un equipo de producto. Que el objetivo no es describir cada entrevista — es identificar qué aprender de ellas para tomar decisiones de producto.

→ Copia este prompt y envíalo aquí mismo:

```
Lee el archivo modulo-5/leccion-5-1/practica/notas-entrevistas-producto.txt.
Son notas de 12 entrevistas de usuario de un sprint de discovery.

Genera SINTESIS-RESEARCH.md con estas secciones:

1. Top 3 dolores por frecuencia (con número de menciones y cita representativa)
2. Comportamiento actual del usuario (cómo resuelven el problema hoy sin el producto)
3. Señales de funcionalidades prioritarias (qué pedían los usuarios, agrupado por tema)
4. Segmentos con necesidades distintas (si los hay)
5. Preguntas críticas para el equipo de producto antes de priorizar

Tono: directo, para un equipo de ingeniería y diseño que va a tomar decisiones de sprint.
Cada afirmación con el número de usuarios que la mencionaron si es posible determinarlo.
```

Vuelve cuando Cowork haya generado el archivo.

---

## [DESPUÉS DE LA PARTE A]

Abre `SINTESIS-RESEARCH.md`.

Comprueba que los dolores tienen frecuencia (número de usuarios) y no solo descripción. Eso es lo que convierte una observación en una señal accionable.

Cuando el documento esté correcto, escribe **"parte b"**.

---

## [PARTE B]

Ahora el PRD.

El borrador que tienes tiene estructura pero secciones incompletas y varias preguntas abiertas. La síntesis de research que acabas de generar responde algunas de esas preguntas.

→ Copia este prompt y envíalo aquí mismo:

```
Lee estos dos archivos:
- modulo-5/leccion-5-1/practica/prd-borrador.txt (PRD en borrador con secciones incompletas)
- SINTESIS-RESEARCH.md (síntesis del research que acabo de generar)

Genera PRD-ACTUALIZADO.md con el PRD completo:
1. Rellena las secciones incompletas usando la información del research
2. Responde las preguntas abiertas del borrador con los datos del research cuando sea posible
3. Si una pregunta abierta no tiene respuesta en el research, mantenla como pregunta abierta y señala qué información haría falta para responderla
4. Añade una sección "Decisiones de diseño pendientes" con las preguntas que el equipo aún necesita resolver

Tono: preciso, sin ambigüedad. Es un documento de referencia para el equipo, no una propuesta.
```

Vuelve cuando Cowork haya generado el archivo.

---

## [CIERRE]

Lo que tienes ahora:
- Una síntesis de research con dolores priorizados por frecuencia, lista para presentar al equipo
- Un PRD actualizado con las secciones del borrador rellenadas con datos del research
- El patrón para mantener el PRD actualizado a medida que llega nuevo research

El patrón que usaste:
1. Síntesis primero — convierte las notas en señales accionables
2. PRD después — usa la síntesis como input para completar el documento de producto
3. Señala lo que falta — las preguntas sin respuesta son tan útiles como las respondidas

Un PM que puede sintetizar 12 entrevistas y actualizar un PRD en una sesión tiene más tiempo para hacer las conversaciones con los usuarios que generaron ese research.

Lección 5.1 completada.

Escribe **"siguiente"** para ir a la Lección 5.2.
Escribe **"repetir"** si quieres aplicar este flujo a tu propio research y PRD.
Escribe **"ayuda"** si el PRD actualizado no refleja correctamente el research.
