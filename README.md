# Pim Pum Pam

Sitio web de Pim Pum Pam Soluciones Creativas, con su catálogo de regalos
personalizados y canales de contacto. Desarrollado en Astro.

`npm install` instala Node.js 24 dentro del proyecto. Los comandos de Astro
usan esa versión local.

```sh
npm install
npm run dev
```

`npm run build` genera el sitio estático en `dist/`. Usá `npm run preview`
para revisar esa compilación localmente.

La página está en `src/pages/index.astro`, los estilos en `src/styles/`
y las imágenes en `public/images/`.

Para publicar en GitHub Pages, usá GitHub Actions como fuente y publicá
la salida de `npm run build`. El dominio personalizado se conserva en
`public/CNAME`.
