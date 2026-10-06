# Invitación · Natalia & Benjamín

Invitación web al matrimonio de Natalia Caris Pino y Benjamín Cáceres Abarca.
Sábado 30 de enero de 2027 · Iglesia San Francisco Javier, Peralillo.

Sitio estático (HTML + imágenes), sin compilación. Se publica en Vercel.

- `index.html` — la invitación
- `generador/` — crea el link personalizado de cada invitado (nombre y cupos)
- `img/` — imágenes
- `og.jpg` — vista previa al compartir el link en WhatsApp

## Links personalizados
Cada link termina en `#g…` con el nombre y los cupos codificados.
Se generan en `/generador`. También funciona `#pase3` para cambiar solo los cupos.

## Dominio
Si el dominio de Vercel cambia, actualiza `og:image` y `og:url` en `index.html`.
