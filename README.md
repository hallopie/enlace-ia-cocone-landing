# Landing de Inscripciones · Kinder Cocone
Landing page de captación de leads desarrollada por Somos Enlace IA.

## Qué hace
Convierte visitas de redes sociales y búsquedas en leads calificados (nombre, niño, teléfono, nivel de interés) que se envían automáticamente a Make.com para seguimiento por WhatsApp.

## Cómo usarlo
1. El papá o mamá llega desde Instagram/Facebook/Google y llena el formulario de la Sección 7.
2. El formulario envía los datos al webhook de Make.com (ver `WEBHOOK_URLS.md`, no compartido en este repo público).
3. Make.com guarda el lead en Airtable y dispara el mensaje automático de bienvenida por WhatsApp.

## Estado
- [x] Demo publicado — revisión del cliente
- [ ] Aprobado por cliente
- [ ] Conectado a Make (PROD)
- [ ] Go-live

## Estructura
`index.html` es un archivo único autocontenido — el logo va incrustado en base64 dentro del HTML, así que **no depende de la carpeta `assets/`** para verse. Puedes abrirlo directo con doble clic o subir solo ese archivo a GitHub y funciona igual.

`assets/logo-cocone.png` se conserva en el repo como referencia — útil cuando el cliente mande el logo en alta resolución y haya que actualizar el base64 incrustado.

## Pendientes antes de producción
- Confirmar con el cliente el logo en alta resolución (versión actual en `assets/logo-cocone.png` extraída de foto de celular — funcional para el demo, pero pixelada si se agranda mucho).
- Fotos reales de Cocone para Hero, Programas y Testimonio (por ahora sin imágenes — solo color de fondo).
- Autorización del papá/mamá del testimonio (Patricia G. es un ejemplo del manual, confirmar si es real o placeholder).
- Conectar `WEBHOOK_URL` en `index.html` al escenario DEV de Make, luego a PROD tras aprobación.

## Contacto
Somos Enlace IA · www.quieroaprenderia.com
administracion@somosenlaceia.com
