# APOLO 5 — Landing page

Sitio estático, adaptable a móvil y listo para publicarse en **GitHub Pages**.

## Archivos
- `index.html`: estructura y contenido del sitio.
- `styles.css`: identidad visual, diseño adaptable y estilos.
- `script.js`: navegación móvil y barra de progreso.
- `assets/apolo5-logo.png`: logo oficial proporcionado por el equipo.
- `assets/rocket-launch.jpg`: arte visual del lanzamiento.

## Publicar en GitHub Pages
1. Descomprime el ZIP.
2. Crea un repositorio en GitHub (por ejemplo, `apolo5`).
3. Sube `index.html`, `styles.css`, `script.js` y la carpeta `assets` a la raíz del repositorio.
4. Abre **Settings → Pages**.
5. En **Build and deployment**, elige **Deploy from a branch**.
6. Selecciona la rama `main` y la carpeta `/ (root)`, y guarda.
7. Espera a que GitHub Pages publique el sitio. La URL aparecerá en esa misma sección.

## Personalización rápida
- Los nombres del equipo están en `index.html`, dentro de `#equipo`.
- Los textos de misión y proyecto también se editan directamente en `index.html`.
- Los colores oficiales están declarados al inicio de `styles.css` como variables CSS:
  - Negro profundo: `#000000` (fondo de interfaz: `#030711`)
  - Azul eléctrico: `#0066FF`
  - Blanco: `#FFFFFF`
- Para cambiar la imagen de lanzamiento, reemplaza `assets/rocket-launch.jpg` conservando el mismo nombre.

## Nota
El sitio no requiere frameworks, compilación ni instalación de dependencias. Google Fonts se carga desde internet; si no está disponible, se utilizan fuentes sans-serif de respaldo.
