# Cómo crear tu propia skill en Cowork

Una skill es un archivo markdown que le da a Claude instrucciones persistentes
sobre cómo hacer un tipo de tarea específico para ti.

## Cuándo vale la pena crear una skill

Cuando repites el mismo tipo de tarea más de 3 veces por semana.
Cuando el resultado de Claude es bueno pero siempre necesitas el mismo tipo de ajuste.
Cuando tienes un estilo, formato o estructura que Claude debería recordar.

## Estructura de una skill (plantilla)

```markdown
# Skill: [Nombre de la tarea]

## Cuándo usar esta skill
[1-2 frases describiendo cuándo aplicarla]

## Contexto que necesita Claude
[Lista de lo que debes darle para que funcione]

## Instrucciones para Claude
[Pasos, estructura, formato esperado]

## Tono / Restricciones
[Cómo debe sonar el output. Qué debe evitar.]

## Ejemplo de output esperado
[Un ejemplo corto del resultado que quieres]
```

## Cómo activarla en Cowork

1. Guarda el archivo de skill en tu carpeta de trabajo (ej: `mis-skills/SKILL-BRIEFINGS.md`)
2. Cuando vayas a usar la skill, dile a Claude: 
   "Lee el archivo mis-skills/SKILL-BRIEFINGS.md y úsalo para crear un briefing de [tema]."
3. Claude leerá las instrucciones y aplicará el formato que definiste.

## Tu tarea en esta lección

Crea una skill para una tarea que repites en tu trabajo.
Usa la plantilla de arriba. Guárdala en esta carpeta con el nombre `MI-SKILL.md`.
Después, pruébala con una tarea real.
