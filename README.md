# Baby Karzy · web

Landing de ropa de bebé en 100% algodón pima (0 meses a 3 años). HTML estático, sin dependencias: abre `index.html` o publícalo en cualquier hosting.

## Fotos de las prendas (hoy son imágenes de muestra)
Las 9 prendas de "Nuestros básicos" tienen una foto por color (15 colores): `img/prendas/<prenda>/<color>.webp`. Para poner las fotos reales, reemplaza el archivo con el mismo nombre (WebP, 600x750, ideal menos de 60 KB). La página las carga sola, sin tocar código.

- Prendas (carpetas, en el orden de la página): `pantalon-sin-pie`, `polo-manga-corta`, `polo-manga-larga`, `cafarena`, `short`, `bividi`, `body-manga-corta`, `body-manga-larga`, `pantalon-con-pie`
- Colores (archivos, en el orden de la página): `verde-cemento`, `fresa`, `lila`, `palo-rosa`, `rosado`, `azul`, `cielo`, `celeste`, `plomo-plata`, `rojo`, `beige`, `amarillo`, `hueso`, `aqua`, `blanco`

## Otras imágenes
| Archivo | Dónde sale | Medidas |
|---|---|---|
| `img/hero.svg` | portada (ilustración referencial de dos bebés) | ya incluida |
| `img/hero.webp` | portada: si subes este archivo (foto real), reemplaza a la ilustración sola | 900x1125 (4:5), < 150 KB |
| `img/logo.webp` | menú | alto ~88 px |
| `img/fachada-tienda.webp` | sección "Nuestra tienda en Gamarra" (recorte de `img/fachada-tienda.jpg`, sin las franjas de dirección y contacto) | ya incluida |
| `img/algodon-pima.webp` | sección "Calidad de la tela" | 800x800 |
| `img/og/baby-karzy.jpg` | vista previa al compartir | 1200x630 |

## Pendiente de completar
- RUC y razón social (footer y Libro de Reclamaciones).
- Dominio real (hoy `babykarzy.com` en canonical, sitemap y robots).
- Pixel de Meta / TikTok y GTM, si los usas.
