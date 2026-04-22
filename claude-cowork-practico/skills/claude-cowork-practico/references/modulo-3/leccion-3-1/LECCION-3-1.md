# Lección 3.1 — Excel con fórmulas desde datos reales

**Duración estimada:** 20 minutos
**Beat del story arc:** Beat 3 — El momento de escala
**Objetivo:** Al terminar esta lección, has generado un Excel funcional con fórmulas, totales y formato a partir de datos en texto plano y un CSV de referencia.

---

## [INICIO]

Módulo 3. Hasta ahora has sintetizado documentos y extraído información. Ahora creas archivos estructurados desde cero.

Excel es donde más trabajo manual se concentra en la mayoría de las organizaciones. Alguien manda datos en texto plano, en un correo, en un PDF escaneado. Tú los tienes que convertir en una hoja con columnas, fórmulas y totales. Ese proceso — copiar, formatear, cuadrar — es exactamente lo que Cowork puede hacer por ti.

En esta lección vas a convertir gastos de marzo anotados en texto libre en un Excel con dos pestañas, fórmulas reales y un registro de los datos ambiguos. Al final tienes un archivo que puedes abrir, editar y compartir directamente.

Escribe **"listo"** para empezar.

---

## [DESPUÉS DE "listo"]

La carpeta `modulo-3/leccion-3-1/practica/` tiene dos archivos:
- `gastos-marzo-sin-formato.txt` — los gastos de marzo anotados en texto libre, tal como los mandó cada equipo
- `gastos-febrero-referencia.csv` — el formato que se usó en febrero, con columnas y estructura

En esta lección vas a convertir datos de gastos en bruto en un Excel estructurado con fórmulas. Antes de ejecutar, aplicamos el framework "Listo":

**¿Cómo se ve esto cuando esté terminado?**
Un Excel con los gastos de marzo organizados, con las mismas columnas que el de febrero, fórmulas de suma por categoría y por equipo, y una pestaña de resumen.

**¿Qué contexto necesita Claude?**
Que el CSV de febrero es la referencia de formato. Que los datos de texto tienen información que necesita interpretación (algunos importes tienen comas decimales, otros puntos).

**¿Qué restricciones importan?**
No inventar datos. Si un importe es ilegible o ambiguo, marcarlo en una columna "revisar". No redondear sin avisar.

---

→ Copia este prompt y envíalo aquí mismo:

```
Lee los archivos de la carpeta modulo-3/leccion-3-1/practica/:
- gastos-febrero-referencia.csv (usa como referencia de formato y columnas)
- gastos-marzo-sin-formato.txt (son los datos a procesar)

Genera GASTOS-MARZO-2024.xlsx con:

Pestaña 1 — Detalle:
- Mismas columnas que el CSV de febrero: Fecha, Equipo, Categoría, Descripción, Importe EUR, Responsable
- Todos los gastos de marzo organizados en esas columnas
- Formato de fecha: AAAA-MM-DD
- Columna adicional "Revisar" (sí/no) para importes ambiguos o datos que no pudiste leer con claridad

Pestaña 2 — Resumen:
- Total de gastos por Equipo (Ventas, Marketing, Operaciones)
- Total de gastos por Categoría
- Gran total del mes
- Fórmulas SUMA que referencien los datos de la Pestaña 1 (no valores fijos)

No inventes importes. Si un dato es ambiguo, ponlo en la columna "Revisar".
```

Vuelve cuando Cowork haya generado el archivo.

---

## [DESPUÉS DE LA EJECUCIÓN]

Di una frase con los datos estructurales del archivo generado: número de filas procesadas, qué contiene cada pestaña, cuántos elementos quedaron en "Revisar" y por qué motivo. No describas el diseño visual — eso el learner lo ve al abrir el archivo.

Después presenta el enlace al archivo y el checklist de revisión:

**1. ¿Están todos los gastos?**
Cuenta las filas de la Pestaña 1. El archivo de texto tiene 21 líneas de gastos.
Si hay menos filas, algún gasto no se procesó.

**2. ¿Las fórmulas funcionan?**
Haz clic en una celda de total en la Pestaña 2. Debe mostrar una fórmula SUMA, no un número fijo.
Si muestra un número fijo, pide a Claude que reemplace los valores por fórmulas.

**3. ¿Hay elementos marcados en "Revisar"?**
El archivo de texto tiene algunos importes con formato inconsistente (comas y puntos mezclados).
Deben aparecer en la columna "Revisar". Si no aparecen, es posible que Claude haya tomado decisiones arbitrarias.

**4. ¿Los totales cuadran?**
Suma manualmente los totales de una categoría y compara con el Excel.

Si algo necesita corrección, díselo a Claude con el dato específico.

---

## [CIERRE]

Lo que tienes ahora:
- Un Excel con 21 gastos procesados, organizados, formateados y con fórmulas
- Una pestaña de resumen con totales por equipo y categoría
- Un registro de los datos ambiguos que necesitan revisión manual

El patrón que usaste:
1. Diste el CSV de referencia como modelo de formato — esto evita que Claude invente columnas
2. Pediste fórmulas que referencien los datos, no valores fijos — así el Excel es editable
3. Añadiste la columna "Revisar" como válvula de seguridad para datos ambiguos

Ese tercer punto es especialmente importante en finanzas y contabilidad. Claude no debe resolver ambigüedades silenciosamente. Debe señalarlas para que tú decidas.

Lección 3.1 completada.

Escribe **"siguiente"** para ir a la Lección 3.2.
Escribe **"repetir"** si quieres aplicarlo a tus propios datos de gastos o cualquier tabla de datos.
Escribe **"ayuda"** si las fórmulas no funcionaron correctamente.
