# Nails Art & Hair Care — propuesta digital

Sitio con disponibilidad en vivo, membresías y pago en línea para
**Nails Art & Hair Care AVEDA** (ARTZ Pedregal, local 236, CDMX).

- **En vivo:** https://nails-art-hair-care.vercel.app
- **Propuesta comercial:** `propuesta/Propuesta-Nails-Art-Hair-Care.pdf` (10 páginas)

## Estructura
- `index.html` — el sitio completo (HTML/CSS/JS en un archivo)
- `assets/img/` — logo y fotos, tomadas de sus redes públicas
- `assets/js/qrcode.js` — generador de QR (MIT, Kazuhiko Arase)
- `propuesta/` — fuente del PDF y capturas (excluida del deploy)

## Cargar precios reales
En `index.html`, arreglo `SERVICIOS`: cambiar `precio:null` por el número.
Aparecen solos en el catálogo y en el paso 1 de la reserva.

## Datos verificados (Facebook, Instagram, Fresha)
**Segundo Nivel** (en el directorio de la plaza aparecen como AVEDA) ·
Horario L-V 9–19 · Sáb 9–17 · Dom 11–17 · Tel 55 3869 0683 ·
Citas 55 2653 2946 · WhatsApp 55 3082 3589 · aveda.artz@gmail.com ·
IG @artznailsandhaircare

## Deploy
`vercel --prod` desde la raíz.
