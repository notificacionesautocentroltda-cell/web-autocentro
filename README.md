# Página web de Autocentro

Sitio estático de https://web.autocentroltda.com.co (taller automotriz, Neiva).

- `site/`: la página (index.html, política de datos, imágenes, videos y fuentes).
- `Caddyfile`: servidor web con HTTPS automático.
- `docker-compose.yml`: proyecto Docker del VPS; descarga este repositorio y lo sirve con Caddy.

Para actualizar la página: subir los cambios a `site/` y reiniciar el proyecto Docker en el VPS.
