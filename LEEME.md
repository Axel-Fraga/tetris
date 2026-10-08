# Tetris: paquete para publicar

Esta carpeta es el juego completo como página web. Súbela a un servicio de hosting gratuito y tendrás tu propio link.

## Qué contiene
- `index.html`: el juego (sonidos y música generados por código, sin archivos de audio).
- `manifest.webmanifest`, `sw.js` y los íconos `.png`: permiten instalarlo en la pantalla de inicio y jugarlo sin internet después de la primera visita.

## Opción A: Netlify (la más rápida)
1. Entra a https://app.netlify.com/drop (puede pedirte una cuenta gratis).
2. Arrastra la carpeta `tetris-web` completa.
3. Te da un link tipo `https://algo.netlify.app`.

## Opción B: GitHub Pages
1. En https://github.com crea un repositorio **público** llamado `tetris`.
2. Toca *uploading an existing file* y arrastra **los archivos de adentro** de la carpeta (no la carpeta completa), luego *Commit changes*.
3. En *Settings → Pages* elige *Deploy from a branch*, rama `main`, carpeta `/ (root)` y *Save*.
4. Tu link será `https://TU-USUARIO.github.io/tetris/`.

Si ya tienes el repositorio de Smash Friends, también puedes subir esta carpeta dentro de él con el nombre `tetris`, y el link sería `https://TU-USUARIO.github.io/smash-friends/tetris/`.

## Instalarlo en el celular
- **iPhone (Safari):** *Compartir → Añadir a pantalla de inicio*.
- **Android (Chrome):** menú de tres puntos → *Instalar app*.
Se juega en vertical.

## Actualizar
Sube el nuevo `index.html` y cambia el número de `VERSION` en `sw.js` (por ejemplo `tetris-v2`) para que los teléfonos descarguen la versión nueva.
