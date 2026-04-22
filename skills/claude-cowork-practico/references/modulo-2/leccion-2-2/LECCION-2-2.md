# Lección 2.2 — Investigación competitiva

**Duración estimada:** 20 minutos
**Beat del story arc:** Beat 3 — El momento de escala
**Objetivo:** Al terminar esta lección, has generado una tabla comparativa de competidores y un análisis de posicionamiento a partir de notas de investigación.

---

## [INICIO]

La investigación competitiva es uno de los trabajos más repetitivos del conocimiento. Recopilas información de distintas fuentes, la organizas, la comparas y sacas conclusiones. Siempre en el mismo formato. Siempre con la misma estructura.

El problema es que ese proceso tarda horas aunque el output sea siempre el mismo tipo de documento. Es exactamente el trabajo que Cowork hace bien.

En esta lección vas a analizar tres competidores a partir de notas de investigación. Al final tienes una tabla comparativa y un análisis de posicionamiento listos para incluir en cualquier deck o documento estratégico.

Escribe **"listo"** para empezar.

---

## [DESPUÉS DE "listo"]

La carpeta `modulo-2/leccion-2-2/practica/` tiene notas de investigación sobre tres competidores: ChatGPT, Notion AI y Microsoft Copilot.

Cada archivo tiene: descripción del producto, posicionamiento, fortalezas, debilidades y precios.

Antes de delegar, aplica el framework:

**¿Cómo se ve esto cuando esté terminado?**
Dos entregables: una tabla comparativa en Excel y un análisis de posicionamiento en Word de una página.

**¿Qué contexto necesita Claude?**
Que el análisis es para un equipo de producto que va a tomar decisiones de posicionamiento. Que el producto propio es Cowork — una herramienta de delegación de tareas con acceso a archivos locales.

**¿Qué restricciones importan?**
Usar solo la información de los archivos. No añadir datos externos que no estén en las notas. Señalar explícitamente qué información falta o está desactualizada.

---

Primero genera la tabla comparativa:

→ Copia este prompt y envíalo aquí mismo:

```
Lee todos los archivos de la carpeta modulo-2/leccion-2-2/practica/.
Son notas de investigación sobre tres competidores.

Genera COMPARATIVA-COMPETIDORES.xlsx con estas columnas:
- Competidor
- Tipo de producto (chatbot / integración / herramienta de archivos)
- Propuesta de valor principal
- Fortalezas (máximo 3 bullets)
- Debilidades (máximo 3 bullets)
- Precio (rangos, en USD o EUR según aparezca en las notas)
- Audiencia objetivo

Una fila por competidor.
Usa solo información de los archivos. Si hay un campo sin datos, escribe "no disponible".
```

Vuelve cuando Cowork haya generado el archivo.

---

## [DESPUÉS DE LA TABLA]

Bien. Abre `COMPARATIVA-COMPETIDORES.xlsx` y comprueba que los tres competidores están completos y que los datos son los que estaban en las notas.

Cuando lo hayas revisado, escribe **"parte b"** para el análisis de posicionamiento.

---

## [PARTE B]

Ahora el análisis de una página. Más valioso que la tabla porque incluye interpretación.

→ Copia este prompt y envíalo aquí mismo:

```
Lee los archivos de la carpeta modulo-2/leccion-2-2/modulo-2/leccion-2-2/practica/ y el archivo COMPARATIVA-COMPETIDORES.xlsx.

Genera ANALISIS-POSICIONAMIENTO.docx (máximo 1 página) con estas secciones:

1. Espacio competitivo (describe en 2-3 frases cómo están posicionados los tres competidores)
2. Huecos detectados (qué necesidades no cubre ninguno de los tres)
3. Ventajas diferenciales de una herramienta de delegación con archivos locales frente a estos tres productos
4. Riesgos competitivos (qué podría hacer cualquiera de ellos para cerrar el hueco)
5. Una recomendación de posicionamiento en una frase

Audiencia: equipo de producto tomando decisiones de go-to-market.
Tono: directo, sin ambigüedad. Si hay interpretación, señálala como tal.
Usa solo información de los archivos. Si hay algo que no puedes saber con los datos disponibles, dilo.
```

Vuelve cuando Cowork haya generado el archivo.

---

## [DESPUÉS DEL ANÁLISIS]

Abre `ANALISIS-POSICIONAMIENTO.docx`.

Revisa específicamente:

**¿Los huecos son reales?**
Contrasta con los archivos originales. ¿Hay algo que los competidores sí hacen y el análisis no recoge?

**¿La recomendación de posicionamiento es accionable?**
Una frase que diga "posiciónate como X para Y que necesita Z". Si es vaga, pide a Claude que la reformule con más especificidad.

**¿Está marcado lo que es interpretación?**
Si Claude añadió algo que no está en las notas, debe señalarlo. Si no lo señaló, corrígeselo.

---

## [CIERRE]

Lo que tienes ahora:
- Una tabla comparativa de competidores lista para presentar
- Un análisis de posicionamiento de una página con huecos y recomendación
- El patrón para repetir esto con cualquier set de notas de investigación

El patrón que usaste:
1. Separaste los dos entregables (tabla y análisis) para que cada uno tenga su propio prompt
2. Diste el contexto del producto propio para que el análisis fuera relevante
3. Pediste explícitamente que señalara lo que no podía saber con los datos disponibles

Ese último punto es importante. Claude tiende a rellenar los vacíos si no le pides que los señale.
Pedir transparencia sobre las limitaciones del análisis hace el output más fiable.

Lección 2.2 completada.

Escribe **"siguiente"** para ir a la Lección 2.3.
Escribe **"repetir"** si quieres aplicarlo a competidores de tu sector.
Escribe **"ayuda"** si el análisis no capturó los huecos que esperabas.
