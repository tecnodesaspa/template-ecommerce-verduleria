# Fresh Harvest — Template ecommerce

Template de verdulería con 15 páginas HTML existentes.

## Alcance

Incluye catálogo, detalle, compra, cuenta y páginas legales. El menú usa JavaScript compartido; el perfil y los pedidos contienen datos de ejemplo.

Los precios, contactos y datos de cliente son ejemplos para personalizar. La presencia de un formulario o botón no garantiza una integración con servicios externos.

## Tecnologías y estructura

- HTML para las páginas.
- Tailwind CSS mediante CDN; no requiere compilar estilos para la vista previa.
- Estilos y configuración visual incluidos en los propios HTML.
- JavaScript local: `main.js`.
- Fuentes, iconos o imágenes externas según cada pantalla; se necesita conexión para cargar esos recursos.

## Vista previa local

Desde esta carpeta, inicia un servidor estático. Por ejemplo, con Node.js y npm disponibles:

```sh
npx --yes http-server . -p 8000
```

Abre [la pantalla inicial](http://localhost:8000/index.html) en el navegador. No hay un package.json ni un paso de build propio del template.

La navegación existente usa el prefijo absoluto `/template-ecommerce-verduleria/`. La URL anterior permite inspeccionar la pantalla inicial; para recorrer los enlaces sin modificarlos, configura tu servidor o sitio contenedor para servir esta carpeta bajo ese prefijo. Las rutas de los archivos se conservan tal como están.

## Páginas incluidas

Las rutas son relativas a esta carpeta.

| Archivo | Título de la pantalla |
| --- | --- |
| `carrito/index.html` | Fresh Harvest - Carrito |
| `confirmacion/index.html` | Fresh Harvest - Order Confirmation |
| `contacto/index.html` | Fresh Harvest - Contact |
| `detalle-producto/index.html` | Fresh Harvest - Product Detail |
| `index.html` | Fresh Harvest |
| `login/index.html` | Fresh Harvest - Login |
| `nosotros/index.html` | Fresh Harvest - About Us |
| `pago/index.html` | Fresh Harvest Checkout |
| `pedido/index.html` | Fresh Harvest - Order Details |
| `perfil/index.html` | Fresh Harvest - Mi Perfil |
| `politicas/index.html` | Fresh Harvest - Política de Privacidad |
| `productos/index.html` | Fresh Harvest - Product Catalog |
| `recuperar/index.html` | Fresh Harvest - Password Recovery |
| `registro/index.html` | Fresh Harvest - Registro |
| `terminos/index.html` | Fresh Harvest - Terms and Conditions |

## Personalización

- Edita los textos, contactos e imágenes en los HTML.
- Ajusta la configuración de Tailwind y los bloques de estilos de cada HTML.
- Los importes del template están presentados en CLP. Mantén el formato sin decimales y los contactos de ejemplo para Chile al personalizarlo.
- Comprueba los cambios en móvil, tablet y escritorio.

## Integración

Antes de usar el template en una tienda operativa, conecta los servicios que correspondan: catálogo, inventario, autenticación, pedidos, pagos y contacto. Revisa las rutas y sustituye el contenido de muestra y los textos legales por los del negocio.
