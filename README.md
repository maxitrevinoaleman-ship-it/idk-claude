# Dulce Cactus

Página web de una sola vista para una tienda de galletas artesanales. Muestra el menú, arma un carrito y genera el pedido listo para enviar por WhatsApp.

## Características

- Menú de galletas con ilustraciones hechas en SVG (sin imágenes externas).
- Carrito con cantidades, subtotales y total en pesos mexicanos (MXN).
- Botón "Ordenar pedido" que abre WhatsApp con el pedido ya redactado.
- El carrito se guarda en el navegador (localStorage); no hay servidor ni registro.
- Modo claro y oscuro con botón en el encabezado. Recuerda la elección y respeta el tema del sistema.
- Animaciones al agregar galletas: la galleta vuela al carrito, el contador late y los botones responden.
- Barra superior con desenfoque (backdrop-filter) optimizado y respaldo para navegadores sin soporte.
- Diseño responsivo pensado para celular, con fuente Rubik.
- Respeta la preferencia de menos movimiento (prefers-reduced-motion).
- Incluye Aviso de privacidad y Términos y condiciones.

## Uso

Todo vive en `index.html`, sin dependencias ni paso de compilación. Para verla en local basta con abrir el archivo en el navegador. En producción se sirve con GitHub Pages.

## Configuración

Los datos editables están al inicio del `<script>` en `index.html`:

- `WHATSAPP`: número al que se envía el pedido, con código de país.
- `PRODUCTOS`: lista de galletas (nombre, descripción, precio e ilustración).
- Datos del negocio usados en el Aviso de privacidad y los Términos.

## Créditos

Hecho por Max. Colaborador: /home/charly
