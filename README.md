# Sitio Personal — Luis Saucedo

Sitio publicado en: https://luis1828.github.io/mi-sitio/

Este repositorio contiene un sitio estático (solo HTML) con las siguientes páginas:
- `index.html` — Página principal con foto, presentación, formación y habilidades.
- `proyectos.html` — Descripción detallada de 3 proyectos realizados.
- `contacto.html` — Información de contacto y un formulario (utiliza `mailto:`).

## URL pública del sitio (ya desplegado)

El sitio está publicado y accesible en: https://luis1828.github.io/mi-sitio/

## Cómo publicar en GitHub Pages (resumen)

1. Crear el repositorio (puedes usar el enlace de GitHub Classroom provisto por el docente).
2. Subir los archivos a la rama `main` (ejemplo):
   ```bash
   git init
   git add index.html proyectos.html contacto.html README.md
   git commit -m "Agregar sitio personal - entrega"
   git branch -M main
   git remote add origin https://github.com/Luis1828/mi-sitio.git
   git push -u origin main
   ```
3. En GitHub: `Settings` → `Pages` (o `Pages & deployments`) → seleccionar la rama `main` y carpeta `/ (root)` → Guardar.
4. La URL pública será: `https://Luis1828.github.io/mi-sitio/`.
5. (Opcional) Si usas GitHub Classroom, pega la URL pública en la tarea del classroom para completar la entrega.

## Validación W3C

- Estos archivos usan semántica HTML (header, nav, main, section, article, figure, footer).
- Para validar con W3C: https://validator.w3.org/ seleccionar la pestaña "Validate by URL" y pegar la URL del sitio: https://luis1828.github.io/mi-sitio/

## Personalización (recomendado)

- Reemplaza la imagen placeholder por tu foto profesional (mismo nombre `foto.jpg` u otra ruta).
- Actualiza el correo en `contacto.html` (`mailto:`) y los enlaces a GitHub/LinkedIn.
- Si necesitas recibir mensajes desde el formulario sin usar `mailto:`, considera usar Formspree, Netlify Forms o un backend simple.

---
Repositorio del estudiante: https://github.com/Luis1828/mi-sitio
Sitio en GitHub Pages (publicado): https://luis1828.github.io/mi-sitio/
