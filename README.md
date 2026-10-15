# email-marketing · Solocruceros

Plantillas HTML de email para las campañas de Solocruceros.

## Plantillas

| Archivo | Uso |
|---|---|
| `templates/solocruceros-base.html` | Plantilla base: cabecera con logo, imagen principal, titular + CTA, 2 tarjetas de crucero, banda de contacto y pie legal. |

## Características

- Maquetación con tablas, ancho 600 px, responsive (las columnas se apilan por debajo de 620 px).
- Compatible con Outlook (condicionales MSO y botón VML).
- Lista para Mailchimp:
  - Etiquetas de fusión: `*|FNAME|*`, `*|MC_PREVIEW_TEXT|*`, `*|ARCHIVE|*`, `*|UNSUB|*`, `*|UPDATE_PROFILE|*`, `*|LIST:ADDRESSLINE|*`, `*|REWARDS|*`.
  - Zonas editables `mc:edit` (`logo`, `hero_image`, `hero_text`, `hero_cta`, `section_title`, `card_1`, `card_2`, `contact_band`, `footer`).

## Colores (ajustar a la marca)

| Token | Hex | Uso |
|---|---|---|
| Azul marino | `#0b2545` | Cabecera, pie, titulares |
| Azul mar | `#1b6ca8` | Enlaces, etiquetas |
| Coral | `#f2545b` | Botón CTA, precios |
| Fondo | `#eef3f7` | Fondo exterior |

## Antes de enviar

1. Sustituir las imágenes `via.placeholder.com` (logo, imagen principal, tarjetas) por las definitivas, a doble resolución (p. ej. 1200 px de ancho para la principal).
2. Cambiar los enlaces `https://www.solocruceros.com` por las URLs concretas de cada oferta (con UTM si aplica).
3. Revisar el texto alternativo (`alt`) de cada imagen.
4. Enviar una prueba y revisar en Gmail, Outlook y móvil.
