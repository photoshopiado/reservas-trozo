# Reservas Trozo

Página de reservas de Trozo Grilled Burger: la burger del mes, cupo limitado, pago por transferencia y comprobante.

- `index.html` — la página (GSAP + ScrollTrigger + Lenis van en `js/`, sin depender de CDNs).
- `apertura.json` — **lo único que se cambia cada mes**: nombre, descripción, precio, foto, ingredientes, fecha, hora, cierre, cupo y datos de la cuenta. `endpoint` es la URL de la aplicación web de Google Apps Script que guarda las reservas; vacío = modo de prueba.
- `img/` — foto de la burger (`burger-1600.jpg`, `burger-900.jpg`) y su recorte sin fondo (`burger-cut.webp`, `burger-cut-700.webp`).

Las reservas llegan a la hoja «Trozo · Reservas web» en Google Drive y de ahí a la app de comandas.
