# On Top — Web

Consultoría & growth delivery. Sitio de una sola página (`index.html`) con GSAP + ScrollTrigger por CDN.

## Estado
- [x] Etapa 1 — Intro (portal) + Inicio (puertas, 110%, caso Brunel, contacto)
- [x] Etapa 2 — Interfaz Asesorías para restaurantes (transición delivery, ranking, resultados, comandas, 3 pasos)
- [ ] Etapa 3 — Interfaz Páginas y sistemas web (cotizador)

## Cambios rápidos
- **WhatsApp:** en `index.html`, al inicio del `<script>`: `const WHATSAPP_NUMBER = '593...'` (código de país + número, sin `+` ni espacios). Los mensajes de cada sección están justo debajo, en `WA_MSGS`.
- **Colores:** bloque `:root` al inicio del `<style>` (variables `--turq`, `--lime`… para el inicio y `--a-…` para Asesorías).
- **Textos:** directamente en el HTML.

## Publicación
Vercel publica automáticamente cada push a `main`. No requiere build.
