# BOH Landing - brandatta.com.ar/boh

Este paquete está preparado para publicar la landing en:

https://brandatta.com.ar/boh/

## Estructura

- `/boh/index.html`
- `/boh/styles.css`
- `/boh/script.js`
- `/index.html` opcional, con redirección a `/boh/`

## Escenario recomendado

Si `brandatta.com.ar` ya apunta a un sitio publicado con GitHub Pages, copiá la carpeta `boh` dentro del root de ese sitio/repo.

La URL final será:

https://brandatta.com.ar/boh/

## Alternativa con repo dedicado

Si vas a usar un repo separado llamado `boh` como GitHub Pages Project Site, podés usar directamente los archivos que están dentro de la carpeta `/boh` como root del repo.

En ese caso, GitHub Pages normalmente publicará el proyecto bajo `/boh/` cuando el dominio custom esté asociado al sitio principal.

## Nota sobre dominio custom

No se configura un CNAME como `brandatta.com.ar/boh`, porque el CNAME solo admite dominios, no rutas internas.  
La ruta `/boh/` se logra por estructura de carpetas o por Project Site.

## Personalización rápida

Cambiar el email del CTA en `/boh/index.html` buscando:

mailto:brandatta.interfaces@gmail.com

Cambiar colores principales desde `/boh/styles.css`:

- `--brand`
- `--brand-2`
- `--bg`
- `--surface`


## Cambios v2

- Todas las tarjetas de módulos ahora navegan a una sección de detalle dentro de la misma landing.
- Se agregó una capa `Detalle funcional` con anchors por módulo.
- Se redujo el tamaño del título principal del hero.
- Se agregaron estilos de hover y links `Ver detalle`.
