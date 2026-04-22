# Lección 4.4 — Investigación web: qué funciona y qué no

**Duración estimada:** 20 minutos
**Beat del story arc:** Beat 4 — El sistema propio
**Objetivo:** Al terminar esta lección, sabes qué tipo de tareas de investigación web puedes delegar a Cowork, cuáles no, y cómo estructurar esas tareas para reducir el riesgo de resultados incompletos.

---

## [INICIO]

Esta lección es distinta a las anteriores. No termina con un entregable perfecto que puedes compartir directamente.

Termina con criterio claro sobre cuándo usar esta función y cuándo no.

El acceso a contenido web es útil. También es la función más inconsistente de Cowork. Necesitas saber los dos lados antes de usarla en un contexto de trabajo real.

Escribe **"listo"** para empezar.

---

## [DESPUÉS DE "listo"]

### Qué puede hacer Cowork con la web

Cowork puede acceder al contenido de páginas web y extraer información de ellas. No abre un navegador visible — lee el texto de una página directamente, de forma programática, sin renderizarla. Por eso funciona bien en páginas con contenido estático y falla en páginas que dependen de JavaScript dinámico o de que el usuario esté logueado.

Casos donde funciona bien:
- Páginas públicas con información estática (páginas de precios, webs corporativas, perfiles de LinkedIn públicos)
- Búsquedas de información que está en múltiples páginas del mismo tipo
- Recopilación de datos públicos para investigación (competidores, noticias, publicaciones)

Casos donde falla o es poco fiable:
- Páginas que requieren login o autenticación
- Webs con mucho JavaScript dinámico que carga contenido tras el scroll
- Flujos de múltiples pasos (formularios, procesos de compra)
- Páginas que detectan y bloquean bots

### La regla práctica

Usa el acceso web de Cowork para investigación pública. No lo uses para flujos críticos o que requieren login.

Si el resultado es incorrecto o incompleto, no es un error de tu prompt. Es una limitación de la herramienta con ese tipo de página.

---

### Parte A: Un caso que funciona

Vamos a hacer una búsqueda de información pública que es un buen caso de uso.

→ Copia este prompt y envíalo aquí mismo:

```
Busca información pública sobre el precio y las características principales
de los planes de pago de estas tres herramientas:
- Notion (notion.so/pricing)
- Monday.com (monday.com/pricing)
- Asana (asana.com/pricing)

Para cada herramienta, extrae:
- Nombre de los planes disponibles
- Precio por usuario/mes (plan de pago más básico)
- Las 3 funcionalidades principales que destacan en su página de precios

Guarda el resultado como PRECIOS-HERRAMIENTAS.md con una tabla comparativa.
Indica la fecha en que extrajiste la información y señala si alguna página no te fue accesible.
```

Vuelve cuando Cowork haya terminado.

---

## [DESPUÉS DE LA PARTE A]

Abre `PRECIOS-HERRAMIENTAS.md`.

Revisa:
- ¿Están las tres herramientas? Si alguna no aparece, la página puede haber sido inaccesible.
- ¿Los precios parecen razonables? Contrasta mentalmente con lo que sabes o con una búsqueda rápida tuya.
- ¿Hay alguna nota de que algo no fue accesible? Si la hay, es buena señal: Cowork está siendo transparente sobre sus límites.

Esta es la forma correcta de usar el navegador: investigación pública, con verificación tuya antes de usar los datos en algo importante.

Escribe **"parte b"** cuando hayas revisado el archivo.

---

## [PARTE B]

Ahora el lado opuesto: lo que no funciona.

No lo vamos a ejecutar — la lección es conceptual — pero es igual de importante que sepas reconocerlo.

**Caso 1 — Login requerido**
Si le pides a Cowork que entre a tu cuenta de Notion y extraiga el contenido de tus páginas, no va a funcionar. Cowork no tiene tus credenciales y no debería tenerlas.

**Caso 2 — Formularios o procesos de varios pasos**
Si le pides que complete un formulario de contacto o que haga una reserva, la fiabilidad es baja. Este tipo de automatización requiere herramientas específicas (Zapier, Make, n8n) que no son Cowork.

**Caso 3 — Datos críticos sin verificación**
Si usas directamente los precios que extrajo Cowork en una propuesta a un cliente sin verificarlos, asumes el riesgo de que los datos sean incorrectos o estén desactualizados. Los precios de SaaS cambian con frecuencia.

La regla no cambia: la automatización del navegador es una herramienta de primer borrador, no de entregable final.

---

## [CIERRE]

Lo que tienes ahora:
- El criterio claro sobre qué tareas de navegación valen la pena y cuáles no
- Un ejemplo real de extracción de datos públicos con resultado verificable
- La costumbre de pedir que señale lo que no fue accesible — eso es más valioso que un resultado aparentemente completo

El patrón que usaste:
1. Tarea de investigación pública con páginas de precios accesibles
2. Pediste que señalara lo que no pudo acceder
3. Verificaste los datos antes de usarlos

El acceso web de Cowork es inconsistente. Funciona bien en páginas públicas con contenido estático, falla en páginas complejas o con login. Úsalo para investigación pública, no para flujos críticos.

Lección 4.4 completada. Con esto termina el Módulo 4.

Escribe **"siguiente"** para ir al Módulo 5 (aplicaciones por rol).
Escribe **"repetir"** si quieres probar con otras páginas públicas de tu sector.
Escribe **"resumen"** para ver qué has aprendido en el Módulo 4.
