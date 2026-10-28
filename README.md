# Baby Karzy · web

Landing de ropa de bebé en 100% algodón pima (0 meses a 3 años). HTML estático, sin dependencias: abre `index.html` o publícalo en cualquier hosting.

## Fotos de las prendas
Las 9 prendas de "Nuestros básicos" tienen una foto por color (15 colores): `img/prendas/<prenda>/<color>.webp`. Para cambiar una foto, reemplaza el archivo con el mismo nombre; la página la carga sola, sin tocar código.

- **Pantalón sin pie, short, body manga larga y polo manga larga: ya tienen fotos reales** (WebP con fondo transparente; pantalón y short en 800x1000, unos 50-70 KB; body y polo, con bordado fino, en tamaño completo 1080x1350, unos 90-110 KB). Los PNG originales están en `img/prendas/<prenda>/originales/`. Se muestran completas, sin recortar, sobre un fondo `#FFF3F9`.
- Las otras 5 prendas siguen con imágenes de muestra (WebP 600x750). Cuando tengas sus fotos reales, súbelas con el mismo nombre y avísame para mostrarlas completas sobre el fondo suave.
- Prendas (carpetas, en el orden de la página): `pantalon-sin-pie`, `polo-manga-corta`, `polo-manga-larga`, `cafarena`, `short`, `bividi`, `body-manga-corta`, `body-manga-larga`, `pantalon-con-pie`
- Colores (archivos, en el orden de la página): `celeste`, `cielo`, `plomo-plata`, `rojo`, `azul`, `rosado`, `lila`, `palo-rosa`, `fresa`, `verde-pastel`, `blanco`, `verde-cemento`, `crema`, `beige`, `amarillo`

## Otras imágenes
| Archivo | Dónde sale | Cómo cambiarla |
|---|---|---|
| `img/logo.svg` | logo del menú y del pie, y ícono de la pestaña | reemplaza el SVG |
| `img/favicon-32.png`, `img/apple-touch-icon.png` (180), `img/icon-192.png`, `img/icon-512.png` | pestaña del navegador, iPhone y pantalla de inicio de Android (`site.webmanifest`) | PNG transparentes hechos a partir del logo |
| `img/og/baby-karzy.jpg` (1200x630) | imagen al compartir el link por WhatsApp o Facebook | reemplaza el JPG |
| `img/hero.webp` (1000x1000) y `img/hero-600.webp` (600x600) | foto de la portada (original: `img/hero.jpg`) | reemplaza ambos WebP |
| `img/tela-algodon-pima.webp` (900x900) y `-600.webp` | sección "Calidad de la tela" (original: `img/tela-algodon-pima.jpg`, recortada para quitar el texto "Interlock" de la foto) | reemplaza ambos WebP |
| `img/fachada-tienda.webp` | sección "Nuestra tienda en Gamarra" (original: `img/fachada-tienda.jpg`) | reemplaza el WebP |

## Pendiente de completar
- RUC y razón social (footer y Libro de Reclamaciones).
- Dominio real (hoy `babykarzy.com` en canonical, sitemap y robots).
- Pixel de Meta / TikTok y GTM, si los usas.
