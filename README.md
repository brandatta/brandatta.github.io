# Brandatta Operations Hub - Landing Page

Sitio estático listo para publicar en GitHub Pages.

## Archivos

- `index.html`: estructura principal de la landing.
- `styles.css`: estilos visuales responsive.
- `script.js`: menú mobile.
- `README.md`: estas instrucciones.

## Cómo publicarlo en GitHub Pages

1. Crear un repositorio nuevo en GitHub.
2. Subir estos archivos al root del repositorio.
3. Ir a `Settings > Pages`.
4. En `Build and deployment`, elegir:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Guardar y esperar a que GitHub publique la URL.

## Personalización rápida

- Cambiar el email del CTA en `index.html` buscando:
  `mailto:brandatta.interfaces@gmail.com`
- Cambiar textos de módulos directamente en los `<article class="module-card">`.
- Cambiar colores principales desde `styles.css`, variables:
  `--brand`, `--brand-2`, `--bg`, `--surface`.
