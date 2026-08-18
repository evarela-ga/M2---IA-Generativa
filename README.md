# M2 - IA Generativa

Sitio estático de una clase narrada de **IA Estratégica para Líderes**, preparado para publicar directamente en GitHub Pages.

Conserva la misma arquitectura visual y de interacción de **M1 - Fundamentos de la IA**:

- estética oscura inspirada en reproductores de streaming;
- botón principal de reproducción;
- barra de progreso navegable;
- retroceso y avance de 30 segundos;
- capítulos clickeables;
- texto sincronizado con resaltado amarillo;
- selección automática de voces en español, priorizando `es-AR`;
- botón para compartir el link;
- diseño responsive para escritorio y celular.

## Archivos

- `index.html` — interfaz principal.
- `styles.css` — diseño responsive.
- `content.js` — guion narrado de M2.
- `app.js` — reproducción, progreso, capítulos y sincronización.
- `.nojekyll` — evita procesamiento de Jekyll.

## Publicar en GitHub Pages

1. Crear un repositorio nuevo o una carpeta/ruta para M2.
2. Subir todos los archivos de esta carpeta a la raíz del repositorio.
3. Abrir **Settings → Pages**.
4. En **Build and deployment**, seleccionar **Deploy from a branch**.
5. Elegir `main` y `/ (root)`.
6. Guardar y compartir la URL pública.

## Audio / voces

La narración utiliza la Web Speech API (`speechSynthesis`). El sitio prioriza voces `es-AR` disponibles en el dispositivo y luego otras voces en español. La voz exacta puede variar entre dispositivos.

Para una voz idéntica para todos los alumnos, se puede reemplazar la síntesis por un MP3 neuronal pregrabado manteniendo la misma interfaz.

## Navegadores recomendados

- Chrome actualizado
- Edge actualizado
- Safari actualizado
