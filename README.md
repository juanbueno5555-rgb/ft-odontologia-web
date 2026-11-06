# FT Odontología Integral — Sitio web

Landing page de una sola página para la clínica FT Odontología Integral (Bogotá).
Diseño de sonrisa y rehabilitación oral.

## Estructura

```
index.html    Página completa (HTML + CSS + JS embebidos, sin build)
```

Todo el sitio vive en un único archivo autocontenido: no hay dependencias locales,
bundler ni paso de compilación. Las únicas referencias externas son Google Fonts
y los enlaces de WhatsApp/Instagram.

## Desarrollo local

Abrir `index.html` en el navegador, o servirlo con cualquier servidor estático:

```powershell
npx serve .
```

## Deploy

Cloudflare Pages (plan gratuito), upload directo de assets:

1. Workers & Pages → Create → Pages → Upload assets
2. Arrastrar la carpeta que contiene `index.html`
3. Deploy

El sitio queda publicado en `https://<proyecto>.pages.dev`.

## Contacto

- WhatsApp: +57 305 477 3406
- Instagram: [@rehabilitacionintegralft](https://www.instagram.com/rehabilitacionintegralft)
- Dirección: Calle 125 #20-70, Bogotá
