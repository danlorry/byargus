# Argus — byargus.com

Landing page para Argus, monitor GEO/AI-SEO de marcas en ChatGPT, Claude, Perplexity y Gemini.

## Stack
- HTML + Tailwind CSS (CDN)
- Netlify Forms para captura de emails (gratis hasta 100 envíos/mes)
- Deploy automático en Netlify

## Archivos
- `index.html` — landing principal
- `gracias.html` — página tras envío de formulario

## Formularios
Dos formularios capturan a `Forms` en el dashboard de Netlify:
- `waitlist` (hero)
- `waitlist-bottom` (CTA final)

Ambos redirigen a `/gracias.html` después del envío.
