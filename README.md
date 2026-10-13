# ArysPache Peluquería — web

Web de una sola página para ArysPache Peluquería (C. Esperanza, 1 · Las Rozas de Madrid).

- `index.html`: toda la web (HTML, CSS y JS en un único archivo, sin dependencias).
- `aviso-legal.html` y `privacidad.html`: páginas legales (estilos en `legal.css`).
- `fotos/`: imágenes. Mira `fotos/LEEME.md` para los nombres de archivo.

## Pendiente antes de publicar
- [ ] Precios "Desde" de cada servicio (buscar `[PRECIO]`).
- [ ] Fotos reales (ver `fotos/LEEME.md`) y retirar la etiqueta `[SUSTITUIR POR FOTOS REALES DE INSTAGRAM]`.
- [x] Páginas de Aviso legal y Política de privacidad (enlazadas en el pie).
- [ ] Completar en ambas páginas el titular, NIF y email (buscar `[NOMBRE`, `[NIF]`, `[EMAIL`).
- [ ] Al tener dominio, cambiar `og:image` e `image` (JSON-LD) a URLs absolutas.

## Publicar
Al ser estático, sirve en GitHub Pages, Netlify o cualquier hosting: basta con subir `index.html` y la carpeta `fotos/`.
