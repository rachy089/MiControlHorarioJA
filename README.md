# Mi control horario en CICOM

App web minimalista de control horario (Juan Alfonso).

## Funciones

- **Botón único de fichaje**: muestra «Entrada»; al fichar pasa a «Salida» con la hora de entrada debajo. Registra fecha y hora exactas automáticamente.
- **Historial de la semana** (lunes a domingo) con navegación entre semanas, total de horas por día y por semana, y progreso frente al objetivo.
- **Edición**: añadir fichajes manuales, editar y eliminar.
- **Informe semanal en CSV** (separador `;`, se abre directamente en Excel en español).
- **Dashboard**: horas de hoy, semana y mes, media diaria, saldos frente al objetivo, gráficos por día (semana y mes), por semana (últimas 12) y por mes (últimos 12).
- **Exportar a Excel (.xlsx)**: mes en vigor, mes pasado o total del año hasta hoy (hojas Resumen, Mensual, Semanal, Diario y Fichajes).
- **Copia de seguridad** en JSON (exportar / importar).

## Datos

Los fichajes se guardan en el `localStorage` del navegador: cada dispositivo/navegador tiene sus propios datos. Usa «Exportar copia» para guardarlos o pasarlos a otro dispositivo.

## Publicación

Es un único `index.html` sin dependencias de compilación (SheetJS se carga desde cdnjs). Se publica con GitHub Pages desde la rama `main`, carpeta raíz.
