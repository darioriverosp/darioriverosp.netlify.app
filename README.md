# darioriverosp.netlify.app

Portafolio y currículum web de **Gonzalo Dario Riveros Plaza** — soporte técnico L2, automatización de procesos y desarrollo web.

🔗 **[darioriverosp.netlify.app](https://darioriverosp.netlify.app/)** · [English version](https://darioriverosp.netlify.app/en/)

## Sobre el sitio

Sitio estático de una sola página, sin frameworks ni proceso de build: HTML, CSS y JavaScript vainilla. Se despliega directamente en Netlify desde este repositorio.

- **Bilingüe** — español (`/`) e inglés (`/en/`) con `hreflang` recíprocos
- **SEO estructurado** — JSON-LD (`Person`, `ProfilePage`, `WebSite`, `ItemList`), canonical, Open Graph y Twitter Card
- **Modo oscuro** automático vía `prefers-color-scheme`
- **Accesible** — contraste WCAG AA, navegación por teclado, `prefers-reduced-motion`
- **Ligero** — imágenes en WebP, sin dependencias de JavaScript

## Estructura

```
├── index.html          Versión en español
├── en/index.html       Versión en inglés
├── styles.css          Hoja de estilos compartida
├── 404.html            Página de error
├── images/             Imágenes optimizadas (WebP) + tarjeta social
├── robots.txt          Incluye rastreadores de IA
├── sitemap.xml         Ambas versiones de idioma
└── netlify.toml        Cabeceras de caché y seguridad
```

## Desarrollo

No hace falta instalar nada. Basta con abrir `index.html` en el navegador, o servir la carpeta:

```bash
npx serve .
```

## Contacto

- **Email** — darioriveros19@gmail.com
- **LinkedIn** — [/in/darioriverosp](https://www.linkedin.com/in/darioriverosp/)
- **Ubicación** — Mérida, Venezuela · disponible para trabajo remoto
