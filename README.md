# Leapmotor B03X · Manual de casa

**Web:** https://javeintimilla.github.io/manual_b03x/

Manual del B03X en castellano para consultar rápido desde el móvil, la tablet, el PC o el navegador del coche. Web estática sin compilación: se sube tal cual a GitHub Pages.

## Accesos directos

| Qué | Enlace |
|---|---|
| Testigos del cuadro | [#/b3-2](https://javeintimilla.github.io/manual_b03x/#/b3-2) |
| Emergencias en carretera | [#/b6-6](https://javeintimilla.github.io/manual_b03x/#/b6-6) |
| Desbloqueos de emergencia | [#/b6-7](https://javeintimilla.github.io/manual_b03x/#/b6-7) |
| Configuración inicial | [#/b4](https://javeintimilla.github.io/manual_b03x/#/b4) |
| Calendario de cargas | [#/b2-2](https://javeintimilla.github.io/manual_b03x/#/b2-2) |
| PDF completo | [docs/B03X_guia_completa_castellano.pdf](https://javeintimilla.github.io/manual_b03x/docs/B03X_guia_completa_castellano.pdf) |

## Estructura

- `index.html`: página única. Lee `version.json` sin caché y carga el resto con `?v=versión`.
- `version.json`: número de versión publicado. Se sube en cada actualización.
- `css/styles.css`: estilos, tema claro y oscuro, animaciones.
- `js/app.js`: enrutado por hash, índice lateral en acordeón, buscador y renderizado.
- `data/manual.json`: todo el contenido (6 bloques, 47 apartados, consultas rápidas).
- `icons/testigos/`: iconos de testigos en SVG, dibujados para esta guía.
- `docs/`: el PDF completo, enlazado desde la web.

## Actualizar

1. Subir los ficheros modificados a su carpeta (**Add file → Upload files**).
2. Editar `version.json` y subir el número (`1.4.0` → `1.4.1`).
3. Recargar la web. En el pie del menú lateral aparece la versión cargada: si coincide, estás viendo lo último.

Sin cambiar la versión también se actualiza, pero GitHub Pages mantiene la caché hasta 10 minutos.

## Enlaces directos

Cada bloque y apartado tiene su propia URL: `#/b1` es el bloque 1 y `#/b6-7` el apartado 7 del bloque 6. Sirven para guardar favoritos o mandarlos por WhatsApp.

## Atajos

- `/` abre el buscador; flechas e `Intro` para elegir resultado; `Esc` para cerrar.
- El botón de sol y luna cambia entre tema claro y oscuro, y se recuerda en cada dispositivo.

## Configuración de GitHub Pages

Settings → Pages → Deploy from a branch → `main` / `(root)`.

---

Resumen propio del manual oficial en inglés (edición de julio de 2026), más nuestra configuración y plan de carga. No reproduce textos ni ilustraciones del manual original, que son propiedad de Leapmotor. Ante cualquier duda, manda el manual oficial.
