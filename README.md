# On Top — Web

Consultoría & growth delivery. Sitio de una sola página (`index.html`) con GSAP + ScrollTrigger por CDN.

## Estado
- [x] Etapa 1 — Intro (portal) + Inicio (puertas, 110%, caso Brunel, contacto)
- [ ] Etapa 2 — Interfaz Asesorías para restaurantes
- [ ] Etapa 3 — Interfaz Páginas y sistemas web (cotizador)

## Cambios rápidos
- **WhatsApp:** en `index.html`, al inicio del `<script>`: `const WHATSAPP_NUMBER = '593...'` (código de país + número, sin `+` ni espacios).
- **Colores:** bloque `:root` al inicio del `<style>`.
- **Textos:** directamente en el HTML. Los mensajes de WhatsApp de cada botón están en `data-wa="..."`.

## Publicación
Vercel publica automáticamente cada push a `main`. No requiere build.
