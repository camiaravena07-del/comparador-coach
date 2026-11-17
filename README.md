# Comparador de tamaño · Coach Perú

Prototipo del widget **"Ver tamaño real"** para la ficha de producto de coach.com.pe (piloto: Cartera Brooklyn 34, CCU00).

- `index.html`: demo navegable (GitHub Pages).
- `snippet-cms.html`: bloque listo para pegar en un elemento *HTML Code* de Page Builder en la ficha del producto.

## Qué hace
- **¿Qué cabe?**: la cartera junto a objetos cotidianos a escala real, con niveles Ligero / Medio / Lleno.
- **Comparar**: la cartera sobre una silueta (estatura 1,50–1,85 m y talla ajustables) o al lado de celular, pasaporte, botella y laptop 14".
- Colores, zoom, botón *Agregar al carrito* conectado al botón real de la ficha.
- Eventos `dataLayer`: `axv_size_viz` (open, tab, compare, level, color, add_to_cart).

## Cómo escala
Usa el ancho de la ficha (34,5 cm) contra el ancho del cuerpo detectado en la foto. En coach.com.pe el fondo de la foto se recorta en el navegador; fuera del sitio usa un modo simplificado.
