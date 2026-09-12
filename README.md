# Invitación de boda — Viviana & César

Invitación digital de boda, 24 de octubre de 2026.

## Contenido

- **`index.html`** — la invitación completa y autocontenida (HTML + CSS + JS en un solo archivo).
  Incluye la foto de portada, la música y las 10 fotos del carrusel ya embebidas como
  `data:` URIs, así que este único archivo funciona en cualquier hosting estático sin
  archivos adicionales.
- **`assets/fotos/`** — las fotos originales (respaldo), por si se necesitan reemplazar
  o editar más adelante.
- **`assets/audio/`** — la pista de audio original (respaldo).

## Publicar / actualizar el sitio

Sube (o vuelve a subir) **solo `index.html`** al hosting:

- **Netlify Drop**: arrastra `index.html` a [app.netlify.com/drop](https://app.netlify.com/drop)
  (con sesión iniciada, para poder actualizarlo después desde la pestaña *Deploys*).
- **GitHub Pages**: en este mismo repositorio, entra a **Settings → Pages**, elige la rama
  `main` y la carpeta `/ (root)`. El sitio queda publicado en
  `https://jacquelinedevcreator.github.io/InvitacionVivianaCesar/`.

## Confirmaciones de asistencia

Cada confirmación se guarda automáticamente en una Hoja de Google (vía Apps Script) —
ahí está el conteo real. `index.html` no necesita ninguna otra pieza para funcionar.
