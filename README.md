# Medstock-web

Landing page de **MedBox**, la app para llevar el inventario del botiquín de casa (caducidades, escaneo por C.N., prospectos sin conexión).

Sitio estático sin build ni dependencias — listo para publicarse tal cual con **GitHub Pages**. Páginas:

- `index.html` — landing principal.
- `privacy.html` — política de privacidad.
- `terms.html` — términos y condiciones de uso.

Enlazadas entre sí y accesibles desde el footer de la página principal.

## Publicarlo con GitHub Pages

1. En este repositorio, ve a **Settings → Pages**.
2. En "Build and deployment" → **Source**, elige **Deploy from a branch**.
3. Selecciona la rama `main` y la carpeta `/ (root)`.
4. Guarda. En un par de minutos el sitio estará disponible en `https://devaro95.github.io/Medstock-web/`.

## Editar el contenido

- `index.html` — estructura y textos de la página principal.
- `privacy.html` / `terms.html` — textos legales.
- `styles.css` — estilos (usa la misma paleta de color que la app: teal `#1A5E63`).

Antes de publicitarla de verdad, actualiza:
- El enlace de descarga en la sección `#descarga` cuando la app esté publicada en Google Play.
- El email de contacto (`hola@medbox.app`) por uno real.
- Los textos legales de `privacy.html` y `terms.html` — son un punto de partida razonable, no asesoramiento legal; conviene que los revise un profesional antes de publicar la app.
