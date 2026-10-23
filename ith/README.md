# Tarjeta digital ITH · Eduardo Amigo Ferrari

Sitio estático (HTML + CSS + JS, sin dependencias ni build). Abre `index.html` en el navegador para verlo.

## Estructura
- `index.html` — la tarjeta: animación de circuito hidráulico, manómetros, botón "Guardar contacto", giro a la cara del QR, compartir.
- `assets/eduardo-amigo-ith.vcf` — contacto descargable (iPhone y Android).
- `assets/qr-contacto.png` — QR que guarda el contacto directo (funciona sin internet).
- `assets/qr-pagina-web.png` — QR a https://www.ith.cl/eduardo/ (usar cuando la página esté publicada ahí).
- `assets/og.jpg` — imagen que aparece al compartir el enlace por WhatsApp/LinkedIn.
- `assets/tarjeta-compartir.png` — imagen 1080x1350 para enviar directo.

## Publicar (elige una)
1. **ith.cl**: subir la carpeta completa a `https://www.ith.cl/eduardo/`.
2. **Netlify Drop** (1 minuto, gratis): arrastrar la carpeta a https://app.netlify.com/drop y se obtiene un enlace https.
3. **GitHub Pages**: crear un repositorio, subir la carpeta, Settings → Pages → rama `main`.

Si la URL final no es `https://www.ith.cl/eduardo/`, cambia la línea `og:image` en `index.html` y regenera el QR web.

## Trucos
- `.../#qr` abre la tarjeta directamente en la cara del QR (útil para mostrar en persona).
- Respeta "reducir movimiento" del sistema: sin animaciones para quien lo tenga activado.
