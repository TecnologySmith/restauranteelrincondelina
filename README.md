# Restaurante El Rincón de Lina — sitio web

Sitio estático listo para GitHub Pages.

## Archivos que debes reemplazar
- `assets/logo.png`: logo entregado por el restaurante.
- `menu/menu.pdf`: coloca aquí el PDF real del menú.
- `galeria/`: agrega `foto-1.jpg` hasta `foto-6.jpg` y luego sustituye los bloques de galería en `index.html` por imágenes reales.

## Publicación
1. Sube toda esta carpeta a un repositorio de GitHub.
2. En Settings > Pages selecciona Deploy from a branch y la rama `main`, carpeta `/root`.
3. Conecta tu dominio personalizado desde GitHub Pages.
4. Antes de publicar, reemplaza el dominio de ejemplo en `sitemap.xml` por el dominio real.
5. Registra el dominio en Google Search Console y envía `sitemap.xml`.

## SEO
La página incluye title, meta description, keywords, Open Graph, datos estructurados Schema.org de tipo Restaurant, dirección, teléfono y redes sociales.

## WhatsApp
Todos los botones llevan al número 311 878 4744 con el mensaje:
"Vengo de la página web y necesito más información".

## Importante sobre "subir"
En una web estática de GitHub Pages no existe un panel de administración para subir archivos directamente desde la página. Esta versión está preparada para que el menú y las fotos se actualicen reemplazando archivos dentro del repositorio. Si quieres un panel donde el restaurante pueda subir menú y fotos sin tocar GitHub, hay que añadir un backend/CMS (por ejemplo Supabase, Firebase o un panel privado).
