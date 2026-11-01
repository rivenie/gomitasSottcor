# Gomitas Sottcor Labs · Tienda web

Sitio estático (HTML, CSS y JS sin dependencias). Pedidos por WhatsApp, sin pasarela de pago.

## Archivos
- `index.html`: versión principal (Opción 2, portada dinámica).
- `opcion-1.html`: versión alternativa (Opción 1).
- `img/`: frascos, logo e imágenes de las líneas.

## Antes de publicar
Edita el bloque `CONFIG` al inicio del `<script>` en `index.html` (y en `opcion-1.html` si la usas):
- `whatsapp`: número con código de país, sin + ni espacios (ej. `51987654321`).
- `precioBase`: precio por frasco para cada línea.
- `precios`: precio específico por producto, por ejemplo `"a-colageno": 59.90`.

## Publicar en GitHub Pages
1. Crea un repositorio y sube todo el contenido de esta carpeta (index.html en la raíz, junto a la carpeta img).
2. En el repositorio: Settings → Pages → Source: "Deploy from a branch", rama `main`, carpeta `/ (root)`.
3. En unos minutos el sitio queda en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.
