# Lección 0.2 — Instalación y tu primera carpeta

**Duración estimada:** 15 minutos
**Beat del story arc:** Beat 1 — El reconocimiento
**Objetivo:** Al terminar esta lección, tienes Claude Desktop instalado, una carpeta de trabajo seleccionada y has confirmado que Cowork puede leer tus archivos.

---

## [INICIO]

Estás dentro de Cowork. Antes de seguir, una orientación rápida de lo que ves en el panel lateral:

- **Progress** — muestra en qué está trabajando Cowork cuando ejecuta una tarea que tarda varios pasos. Si ves círculos completándose, Cowork está en marcha.
- **Working Folders** — las carpetas de tu ordenador a las que Cowork tiene acceso. Aquí aparece la carpeta del curso. Cuando conectes tu carpeta de trabajo en esta lección, la verás aparecer aquí.
- **Context / Skills** — las capacidades extra que Cowork tiene instaladas. Los skills de documento (Word, Excel, PowerPoint) que verificarás al final de esta lección aparecen aquí.

No necesitas tocar nada ahora. Solo saber qué es cada cosa antes de usarlo.

Esta lección va sobre algo distinto: tu carpeta de trabajo propia.

La carpeta del curso es para aprender. Tu carpeta de trabajo es donde vas a hacer tu trabajo real — documentos, reportes, proyectos. Son dos carpetas separadas y las dos pueden estar activas en Cowork.

Esta lección tiene dos pasos: crear tu carpeta de trabajo y verificar que Claude puede leer y escribir en ella.

Escribe **"listo"** para empezar.

---

## [DESPUÉS DE "listo"]

### Paso 1 — Crea tu carpeta de trabajo

Fuera de Cowork, en tu sistema de archivos, crea una carpeta nueva. Puedes llamarla `claude-cowork` o como prefieras. Ponla donde tengas acceso rápido — escritorio o Documentos funciona bien.

Cuando la tengas creada, copia su ruta:

- **Mac:** clic derecho en la carpeta → mantén pulsada `Option` → "Copiar '[nombre]' como nombre de ruta"
- **Windows:** `Shift` + clic derecho en la carpeta → "Copiar como ruta de acceso"

Luego pega la ruta aquí en el chat. Claude solicitará acceso automáticamente.

---

## [DESPUÉS DE "carpeta lista"]

Llama a `request_cowork_directory` con la ruta que el learner acaba de pegar. El learner ve una confirmación y aprueba.

Cuando esté montada, confirma al learner con este texto exacto:

"Carpeta conectada. Ahora verificamos que Claude puede leer y escribir en ella."

Luego continúa con el Paso 2.

### Paso 2 — Verificar que funciona

Vamos a confirmar que Claude puede leer y escribir en tu carpeta de trabajo.

→ Copia este prompt y envíalo aquí mismo:

```
Lista todos los archivos y carpetas que hay en mi carpeta de trabajo.
Si está vacía, dímelo. Luego crea un archivo llamado TEST.md
con el texto "Conexión verificada." dentro.
```

---

## [DESPUÉS DE LA VERIFICACIÓN]

Si Claude listó la carpeta y creó `TEST.md`, la conexión funciona. Puedes borrar ese archivo — era solo para confirmar.

Si recibiste un error, hay dos causas habituales:
- La carpeta no está seleccionada. Ve al selector de Cowork y vuelve a añadirla.
- Permisos bloqueados. En Mac: Preferencias del sistema → Privacidad y seguridad → Acceso completo al disco → añade Claude Desktop.

Escribe **"ayuda"** si el error persiste.

---

## [CIERRE — PASO FINAL: VERIFICAR SKILLS]

Antes de terminar esta lección hay un paso más: verificar que tienes los skills necesarios para las lecciones siguientes.

Este curso genera documentos Word, Excel y PowerPoint. Para eso Cowork necesita tres skills instalados. Compruébalo ahora:

→ Copia este prompt y envíalo aquí mismo:

```
Verifica si tienes disponibles los skills "docx", "xlsx" y "pptx".
Para cada uno, dime si está instalado o no.
Si alguno falta, dime cómo instalarlo.
```

---

## [DESPUÉS DE LA VERIFICACIÓN DE SKILLS]

Si los tres skills están disponibles, todo listo.

Si falta alguno, instálalo antes de continuar: haz clic en el ícono **+** → **Skills** → busca el skill que falta y actívalo.

Cuando los tres estén activos, escribe **"siguiente"**.

---

## [CIERRE]

Lo que tienes ahora:
- Una carpeta de trabajo conectada a Cowork
- Confirmación de que Claude puede leer y escribir en ella
- Los skills de documento instalados y listos

El entorno está listo. A partir de aquí, cada lección ocurre dentro de Cowork con archivos reales.

Lección 0.2 completada.

Escribe **"siguiente"** para ir a la Lección 0.3 (el cambio de mentalidad).
Escribe **"ayuda"** si algo no funcionó.
