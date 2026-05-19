# Uber Wait Tracker + Goodies

App simple para GitHub Pages con múltiples cronómetros por zona y checklist de goodies consumidos.

## Archivos

- `index.html`
- `manifest.json`
- `service-worker.js`
- `icon.svg`

## Cómo subir a GitHub Pages

1. Crea un repositorio en GitHub llamado `uber-wait-tracker`.
2. Sube estos archivos en la raíz del repositorio.
3. En GitHub ve a `Settings > Pages`.
4. En `Build and deployment`, selecciona:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Guarda.
6. Abre la URL de GitHub Pages.

## iPhone

1. Abre la URL en Safari.
2. Toca el botón de compartir.
3. Toca `Add to Home Screen`.

El cronómetro usa timestamps, así que si el teléfono apaga la pantalla, al volver calcula el tiempo real transcurrido.
