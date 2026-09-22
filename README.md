# Leapmotor B03X · Manual de casa

Web estática del manual en castellano. Sin compilación: se sube tal cual a GitHub Pages.

## Estructura

- `index.html`: página única.
- `css/styles.css`: estilos, tema claro y oscuro, animaciones.
- `js/app.js`: enrutado por hash (`#/b3-2`), índice lateral, buscador y renderizado.
- `data/manual.json`: todo el contenido (6 bloques, 47 apartados, accesos rápidos).
- `icons/testigos/`: iconos de testigos en SVG, dibujados para esta guía.
- `docs/`: el PDF completo, enlazado desde la web.

## Publicar

1. Crear el repositorio (por ejemplo `b03x-manual`) y subir el contenido de esta carpeta a la raíz.
2. Settings → Pages → Deploy from a branch → `main` / `(root)`.
3. Queda en `https://<usuario>.github.io/](https://javeintimilla.github.io/b03x-manual/`.

## Enlaces directos

Cada apartado tiene su propia URL: `#/b1` es el bloque 1 y `#/b6-7` el apartado 7 del bloque 6.
Sirven para guardar favoritos o mandarlos por WhatsApp.

## Atajos

- `/` abre el buscador; flechas y `Intro` para elegir resultado; `Esc` para cerrar.
