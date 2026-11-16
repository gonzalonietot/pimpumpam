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

En GitHub, elegí **GitHub Actions** en **Settings → Pages → Build and
deployment → Source**. El workflow compila Astro y publica `dist/` con
cada push a `main`. Si ya subiste el cambio, podés ejecutarlo desde
**Actions → Deploy Astro to GitHub Pages → Run workflow**.

En **Settings → Pages → Custom domain** debe figurar
`pimpumpamsolucionescreativas.com.ar`.
