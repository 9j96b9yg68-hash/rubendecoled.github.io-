# rubendecoled.github.io

Proyecto web de coctelería para eventos en Sevilla y Andalucía con blog SEO, publicado con GitHub Pages.

## ¿Qué es este proyecto?

Es un sitio web **estático** (solo HTML + CSS) pensado para:

- Presentar el servicio de coctelería para eventos de Rubendecoled.
- Publicar artículos tipo blog optimizados para SEO.
- Enlazar fácilmente con la web principal en Wix.

## Estructura de archivos

- `index.html`  
  Página de inicio ligera. Presenta el servicio y enlaza a:
  - Web principal en Wix.
  - Artículo del blog.

- `styles.css`  
  Hoja de estilos con diseño profesional (fondo oscuro y acentos dorados).

- `blog/como-elegir-servicio-cocteleria-evento.html`  
  Artículo SEO: **“Cómo Elegir Servicio de Coctelería para Evento | Guía 2026”**.  
  Incluye:
  - Título y meta etiquetas optimizadas.
  - Encabezados `<h1>`, `<h2>` bien estructurados.
  - Llamadas a la acción.
  - Enlaces hacia la web principal en Wix.

- `README.md`  
  Este archivo, con las instrucciones para usar el proyecto.

## Cómo publicar la web en GitHub Pages

1. Asegúrate de estar en el repositorio **`rubendecoled.github.io`**.
2. Sube todos los archivos del proyecto (index.html, styles.css, carpeta `blog`, README.md) a la rama principal (`main` o `principal`).
3. En GitHub, ve a:
   - **Ajustes (Settings)**  
   - Menú izquierdo → **Pages**
4. En la sección **Build and deployment**:
   - En **Source / Origen** selecciona **Deploy from a branch**.
   - En **Branch / Rama** elige `main` o `principal`.
   - En **Folder / Carpeta** selecciona **/ (root)**.
5. Guarda los cambios.

GitHub tardará unos segundos o minutos en publicar el sitio.

## URLs importantes

- Página principal (home):  
  `https://rubendecoled.github.io`

- Artículo del blog:  
  `https://rubendecoled.github.io/blog/como-elegir-servicio-cocteleria-evento.html`

## Cómo enlazar el blog desde Wix

En tu web de Wix puedes añadir un botón o enlace con:

- **Texto sugerido:**  
  `Guía 2026: Cómo elegir servicio de coctelería para tu evento`

- **URL del enlace:**  
  `https://rubendecoled.github.io/blog/como-elegir-servicio-cocteleria-evento.html`

## Cómo actualizar el contenido

1. Edita los archivos HTML (por ejemplo, el del blog) en tu ordenador o directamente en GitHub.
2. Guarda los cambios y haz **commit** en la rama principal.
3. GitHub Pages se actualizará automáticamente con la nueva versión.

## Añadir nuevos artículos al blog

1. Crea un nuevo archivo dentro de la carpeta `blog/`, por ejemplo:  
   `blog/cocteles-para-boda-en-sevilla.html`
2. Usa la misma estructura de HTML y SEO: `<head>` con `title`, `meta description` y un `<h1>` claro.
3. Añade un enlace desde `index.html` y, si quieres, desde otros artículos del blog.
