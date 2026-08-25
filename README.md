# Leo Perez Autoservicio

Landing page de tienda online (almacén, bebidas, lácteos, limpieza, dulces y snacks) con pedidos por WhatsApp, retiro en el local, y horario real de atención (bloquea el pedido si el local está cerrado).

Sitio estático: un solo archivo `index.html` (HTML + CSS + JS, sin backend).

## Imágenes que faltan agregar

Estos archivos van **en la misma carpeta que `index.html`** (raíz del repo), con estos nombres exactos. Si no están, la página muestra un ícono de reemplazo automáticamente, pero para verse completa hay que subirlos:

### Encabezado y logo
| Archivo | Qué va ahí |
|---|---|
| `logo.png` | Logo de Leo Perez Autoservicio |
| `kiosco-dia.jpg` | Foto del local de día (se muestra de 7:00 a 20:00) |
| `kiosco-noche.jpg` | Foto del local de noche (se muestra el resto del día) |

### Fotos de productos
| Archivo | Producto |
|---|---|
| `yerba.png` | Yerba Playadito 1kg |
| `aceite.png` | Aceite Natura 900ml |
| `fideos.png` | Fideos Matarazzo 500g |
| `coca.png` | Coca-Cola 2.25L |
| `quilmes.png` | Cerveza Quilmes Six Pack Lata |
| `leche.png` | Leche La Serenísima 1L |
| `jamon.png` | Jamón Cocido Fetas 200g |
| `detergente.png` | Detergente Magistral 750ml |
| `lavandina.png` | Lavandina Ayudín 1L |
| `alfajor.png` | Alfajor Guaymallén Triple |
| `lays.png` | Papas Lays 140g |
| `milka.png` | Chocolate Milka 100g |
| `doritos.png` | Doritos Queso 140g |

## Datos a confirmar/editar en `index.html`

Buscar el bloque `CONFIGURACIÓN DEL NEGOCIO` cerca del final del archivo:

- `WHATSAPP_NUM`: confirmar que sea un número con WhatsApp activo (se armó a partir del teléfono del local).
- `WEEK_SCHEDULE`, dirección y teléfono: ya cargados con los datos reales provistos.
- Lista de `products`: reemplazar por el catálogo y precios reales.
