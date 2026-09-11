# Cotización BLACKMOUTH

Cotización general de servicios de BLACKMOUTH: gestión de redes sociales,
página web y pauta en Google Ads. Incluye planes, comparación, trabajo previo,
garantía y condiciones.

Publicada en https://blackmouthagency-dev.github.io/cotizacion-blackmouth/

## Estructura

- `index.html`: la cotización.
- `media/`: logos, portadas de los manuales y los 4 reels con sus pósters. Van
  como archivos aparte, no incrustados en el HTML, para que el celular muestre la
  página de inmediato y cada video se descargue solo cuando alguien le da play.
- `og.jpg`: vista previa al compartir el enlace.

Las tarjetas de "Trabajo previo" enlazan a los manuales, publicados en
https://blackmouthagency-dev.github.io/manuales-blackmouth/

## Notas

- Lleva `noindex, nofollow`. La cotización se comparte por enlace y no debería
  salir en buscadores. Para volverla indexable, borrar esa línea del `<head>`.
