# Lección 3.3 — Reportes Word con estructura profesional

**Duración estimada:** 20 minutos
**Beat del story arc:** Beat 3 — El momento de escala
**Objetivo:** Al terminar esta lección, has generado un reporte Word con índice, secciones y tablas a partir de inputs desordenados de RRHH.

---

## [INICIO]

Tercer y último tipo de documento del Módulo 3.

Un informe formal para el comité de dirección no es solo texto bien escrito. Tiene índice navegable, secciones jerarquizadas, tablas para los datos y tono consistente de principio a fin. El problema es que casi siempre se construye desde notas dispersas, correos sueltos y apuntes de reunión — y convertir ese caos en un documento de ese nivel tarda horas que no aportan valor real.

En esta lección vas a convertir notas de RRHH del primer trimestre en un informe formal con portada, índice, cuatro secciones y dos tablas de datos. Al final tienes un documento listo para el comité de dirección, con los vacíos señalados en lugar de inventados.

Escribe **"listo"** para empezar.

---

## [DESPUÉS DE "listo"]

La carpeta `modulo-3/leccion-3-3/practica/` tiene un archivo: `inputs-informe-rrhh.txt`.

Son notas sin estructura de los eventos de RRHH en el primer trimestre: incorporaciones, salidas, clima laboral, formación y compensación.

En esta lección vas a convertir notas desordenadas de RRHH en un informe formal con índice, secciones y tablas listo para el comité de dirección. Antes de ejecutar, aplicamos el framework "Listo":

**¿Cómo se ve esto cuando esté terminado?**
Un Word con portada, índice automático, cuatro secciones con subsecciones, una tabla de headcount y una tabla de formación, y un apartado de conclusiones con próximos pasos.

**¿Qué contexto necesita Claude?**
Que es un informe formal para el comité de dirección. Que el tono es profesional y objetivo. Que los datos de headcount y formación deben ir en tablas para que sean fáciles de leer.

**¿Qué restricciones importan?**
No inventar métricas. Si un dato no aparece en las notas, señalarlo como "pendiente de completar". No usar adjetivos vagos como "excelente" o "muy positivo" — usar datos concretos.

---

→ Copia este prompt y envíalo aquí mismo:

```
Lee el archivo modulo-3/leccion-3-3/practica/inputs-informe-rrhh.txt.

Genera INFORME-RRHH-Q1-2024.docx con esta estructura:

Portada: título, período (Q1 2024), fecha de emisión

Índice automático con estos apartados:
1. Resumen ejecutivo
2. Movimientos de plantilla
   2.1. Incorporaciones
   2.2. Salidas
   2.3. Procesos activos
3. Clima laboral
4. Formación y desarrollo
5. Compensación
6. Conclusiones y próximos pasos

Tablas obligatorias:
- Tabla de movimientos de plantilla: nombre/perfil, fecha, tipo (incorporación/salida), notas
- Tabla de formación: programa, horas, participantes, resultado

Tono: profesional, objetivo, sin adjetivos vagos. Usa datos concretos cuando existan.
Si un dato no aparece en las notas, escribe "[pendiente de completar]" en esa celda o sección.
No inventes métricas ni conclusiones que no estén respaldadas por los datos.
```

Vuelve cuando Cowork haya generado el archivo.

---

## [DESPUÉS DE LA EJECUCIÓN]

Di una frase con los datos estructurales del archivo generado: número de secciones, si se crearon las tablas solicitadas, cuántos campos quedaron marcados como "[pendiente de completar]". No describas el diseño visual — eso el learner lo ve al abrir el archivo.

Antes de dar por bueno cualquier reporte formal generado, hay cuatro cosas que verificar:

Abre `INFORME-RRHH-Q1-2024.docx` y comprueba:

**1. ¿El índice es navegable?**
Haz clic en una entrada del índice. Debe llevarte a esa sección.
Si el índice no es interactivo, pide a Claude que regenere el documento con índice automático usando estilos de Word.

**2. ¿Las tablas tienen todos los datos de las notas?**
Abre el archivo de notas y compara con las tablas.
La tabla de movimientos debe tener: Sandra (15 enero), David (1 marzo), y la salida de Rafa (febrero).

**3. ¿Hay secciones con "[pendiente de completar]"?**
Las notas de entrada no tienen todos los datos. El informe debe señalar los vacíos, no inventar datos para rellenarlos.

**4. ¿El tono es consistente?**
Lee el resumen ejecutivo y una sección de detalle. ¿El tono es el mismo? ¿Hay adjetivos vagos que deberían ser datos concretos?

---

## [CIERRE]

Lo que tienes ahora:
- Un informe formal de RRHH con estructura profesional, tablas y secciones jerarquizadas
- El patrón para convertir cualquier set de notas desordenadas en un documento formal
- La habilidad de definir la estructura completa de un Word antes de ejecutar

El patrón que usaste:
1. Diste la estructura completa del documento con índice y subsecciones
2. Especificaste qué datos van en tablas y qué estructura tienen esas tablas
3. Pediste que señalara vacíos en lugar de rellenarlos con datos inventados

El tercer punto aplica a cualquier documento con datos reales. Un informe con "[pendiente de completar]" es más útil que uno con datos inventados que parecen correctos.

Esto completa el Módulo 3. Has generado los tres tipos de documento más comunes en entornos de trabajo: Excel, presentación y Word.

Lección 3.3 completada.

Escribe **"siguiente"** para ir al Módulo 4.
Escribe **"repetir"** si quieres generar un informe desde tus propias notas.
Escribe **"resumen"** para ver qué has aprendido en los Módulos 2 y 3.
