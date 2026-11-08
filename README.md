# On Top — Web

Consultoría & growth delivery. Sitio de una sola página (`index.html`) con GSAP + ScrollTrigger por CDN.

## Estado
- [x] Etapa 1 — Intro (portal) + Inicio (puertas, 110%, caso Brunel, contacto)
- [x] Etapa 2 — Interfaz Asesorías para restaurantes (transición delivery, ranking, resultados, comandas, 3 pasos)
- [x] Etapa 3 — Interfaz Páginas y sistemas web (transición en código, terminal, cotizador por WhatsApp)

## Cambios rápidos
- **WhatsApp:** en `index.html`, al inicio del `<script>`: `const WHATSAPP_NUMBER = '593...'` (código de país + número, sin `+` ni espacios). Los mensajes de cada sección están justo debajo, en `WA_MSGS`.
- **Colores:** bloque `:root` al inicio del `<style>` (`--turq`, `--lime`… inicio · `--a-…` Asesorías · `--c-…` Páginas web).
- **Textos:** directamente en el HTML.

- **Precios del cotizador (opcional):** objeto `PRECIOS` debajo de `WA_MSGS`. En 0 no se muestran; con valores, el resumen muestra "desde $X".
- **Enlaces directos:** `/#asesorias` y `/#web` abren cada interfaz.

## Publicación
Vercel publica automáticamente cada push a `main`. No requiere build.
