# PostInstagramMaquivo

Proyecto para crear imágenes de productos destacados de Maquivo a partir del enlace de su anuncio. Incluye las instrucciones, la referencia visual y el logo para mantener el mismo diseño entre publicaciones.

## Uso

1. Abre esta carpeta como proyecto en Codex o en un asistente con acceso a archivos, navegación web y generación o edición de imágenes.
2. Pega el enlace público de un producto de Maquivo y escribe:

   > Crea el post de Instagram de este producto siguiendo AGENTS.md y productos-destacados/INSTRUCCIONES.md: [pega aquí el enlace].

3. El asistente leerá la ficha, obtendrá la foto del anuncio y creará la publicación usando la plantilla.
4. Encontrarás cada resultado en `productos-destacados/publicaciones/`, dentro de una carpeta con la fecha y el nombre del producto.

También puedes pedir varios productos para preparar un carrusel. Por defecto se crea una imagen por enlace.

## Archivos del proyecto

| Ruta | Contenido |
| --- | --- |
| [AGENTS.md](AGENTS.md) | Instrucciones iniciales para Codex y otros agentes. |
| [productos-destacados/INSTRUCCIONES.md](productos-destacados/INSTRUCCIONES.md) | Guía completa para transformar un enlace en una publicación. |
| [productos-destacados/recursos/plantilla-maquivo.png](productos-destacados/recursos/plantilla-maquivo.png) | Plantilla visual maestra. |
| [productos-destacados/recursos/logo-maquivo.webp](productos-destacados/recursos/logo-maquivo.webp) | Logo corporativo de Maquivo. |
| [productos-destacados/publicaciones/](productos-destacados/publicaciones/) | Carpeta donde guardar las publicaciones generadas. |

## Referencia visual

![Plantilla de productos destacados de Maquivo](productos-destacados/recursos/plantilla-maquivo.png)

Los textos y el precio de esta imagen son campos de ejemplo. No corresponden a ningún producto real.

## Requisitos y alcance

Este proyecto contiene documentación y recursos; no requiere instalar una web ni ejecutar un servidor. El asistente necesita poder consultar la ficha del producto y crear imágenes. Conectar el repositorio no añade por sí solo esas capacidades: si alguna no está disponible, deberá indicar qué falta.

La creación de imágenes no publica en Instagram. Las publicaciones deben revisarse antes de subirlas manualmente.

## Repositorio

Repositorio del proyecto: [Mikel-pasab/PostInstagramMaquivo](https://github.com/Mikel-pasab/PostInstagramMaquivo).

Selecciona este repositorio al configurar el proyecto en tu asistente. Las instrucciones de entrada están en `AGENTS.md` y la guía completa en `productos-destacados/INSTRUCCIONES.md`.

Para trabajar con una copia en el ordenador:

```bash
git clone https://github.com/Mikel-pasab/PostInstagramMaquivo.git
cd PostInstagramMaquivo
```

La elección y disponibilidad de GPT Astra dependen de la aplicación y de la cuenta. El repositorio aporta las instrucciones y los recursos; no configura ni habilita modelos.
