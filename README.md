# Crisxlift App

App de entrenamiento para los atletas de las asesorías Crisxlift.
El atleta entra con su código CX, ve su rutina, registra series (kg, reps, RPE)
y al terminar comparte su informe como imagen o PDF.

- Los registros se guardan solo en el móvil del atleta. No se pide ningún dato personal.
- Se puede instalar en la pantalla de inicio (Safari: Compartir → «Añadir a pantalla de inicio»).

## Archivos

- `index.html` — la app.
- `manifest.webmanifest`, `sw.js`, `icons/` — para instalarla como app y abrirla sin conexión.
- `vendor/` — librerías para crear la imagen (html2canvas) y el PDF (jsPDF).
