# Inventario Osuna Maruri

App web para llevar el inventario de los muebles de la casa (focos, tornillos, baterías, herramientas…).

**Abrir la app:** https://th3alonso21.github.io/inventario-osuna-maruri/

## Cómo funciona
- **Inventario:** todo lo que hay, por mueble y ubicación (o por categoría), con buscador y avisos de poco stock.
- **Alta rápida:** foto + nombre + cantidad para registrar cosas una tras otra.
- **Movimientos:** historial de quién agregó o sacó qué y cuándo.
- **Configuración:** muebles, ubicaciones, categorías, personas con acceso y respaldo en CSV.

## Detalles técnicos
- Un solo archivo: `index.html` (HTML + JS, sin compilar).
- Datos en Firebase Firestore (proyecto `inventario-osuna-maruri`), en tiempo real.
- Acceso con cuenta de Google; solo los correos en la lista de acceso pueden leer o escribir (ver `firestore.rules`).
- Para cambiar la app: edita `index.html` y súbelo; GitHub Pages se actualiza en 1–2 minutos.
