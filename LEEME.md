# KORZA — cómo editar

Sube TODA esta carpeta a GitHub (index.html, productos.json, img/, manifest, sw.js, robots.txt, sitemap.xml).

## Reemplaza (una vez)
`https://TU-USUARIO.github.io/TU-REPO/` por la URL real de tu página en: index.html (canonical, og:url, og:image), robots.txt y sitemap.xml.

## productos.json (todo el contenido editable)
- `p`: perfumes. `"out": true` = agotado, `"off": true` = oculto. Fotos en `img/`.
- `cfg.tiktok` / `cfg.instagram`: enlaces completos (https://...) para el footer.
- `cfg.analytics`: tu dominio en Plausible (ej. `korza.com`) para medir clics en Agregar y Finalizar pedido.
- `envios`: `{"ciudad":"Bogotá","costo":12000,"dias":"2-3 días"}` — se muestra el estimado en el carrito al escribir la ciudad.
- `testimonios`: `{"nombre":"Laura","texto":"Llegó rápido y original."}` — la sección aparece sola cuando hay al menos uno.

## Panel de administración
Abre `tu-pagina/#admin`, edita precios/agotado y pulsa "Descargar productos.json"; súbelo a GitHub reemplazando el anterior.
