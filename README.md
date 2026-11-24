# ELIXIR — concepto de tienda de ropa

Proyecto de práctica HTML y CSS, organizado con BEM y un CSS orquestador.

## Estructura
- `index.html`: contenido y estructura de inicio.
- `css/styles.css`: importa los demás CSS.
- `css/base/global.css`: variables, reset y reglas generales.
- `css/components/header.css`: encabezado y navegación.
- `css/components/main.css`: Hero, colección, tarjetas y editorial.
- `css/components/footer.css`: pie de página.
- `assets/images/`: imágenes locales.
- `figma/`: wireframes SVG importables como referencia de diseño.

## Imágenes
Añade archivos con estos nombres en `assets/images/`:
- `hero.jpg`
- `product-1.jpg`
- `product-2.jpg`
- `product-3.jpg`
- `product-4.jpg`
- `editorial.jpg`

Las imágenes son marcadores; sustituye por imágenes propias o con licencia apropiada.

## BEM
- Bloque: `product-card`
- Elemento: `product-card__title`
- El elemento se relaciona con el bloque mediante `__`.

## Responsive
Media queries en `main.css` y `header.css` ajustan el diseño a pantallas menores.

## Figma
Los SVG en `figma/` son bocetos vectoriales para importar en Figma y sirven como base para diseñar desktop, tablet y móvil. No son un archivo nativo `.fig`.
