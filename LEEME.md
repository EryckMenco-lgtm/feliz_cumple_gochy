# Sorpresa de cumpleaños para Victor (Gochy) 💌 — Guía rápida

## Contenido del zip
- `index.html`  → la página (todo el código; la sección **CONFIGURACIÓN** está al inicio del `<script>`)
- `fotos/foto1.jpg … foto7.jpg` → tus 7 fotos (ya recortadas y optimizadas)
- `fotos/abrazo-poster.jpg` y `video/abrazo.mp4` → el video del abrazo
- `voz/mensaje.mp3` → tu mensaje de voz (se reproduce dentro del sobre)
- `musica/cancion.mp3` → **música de prueba generada (piano suave)**. Reemplázala por la canción de ustedes con el mismo nombre.

## 1. Lo que debes cambiar en `index.html` (busca `CONFIGURACIÓN`)
| Campo | Qué poner |
|---|---|
| `nombre` / `apodo` | Victor / Gochy (ya puestos) |
| `yo` | **Tu nombre** (firma de la carta; ahora dice "Tu amor") |
| `anioInicio` | Año de inicio (ya está en 2026) |
| `amoDeElla` | 3–5 cosas que amas de él (`amoDe`) |
| `fotos[].frase` | La frase manuscrita de cada foto |
| `sobre.mensajes` | Los textos que salen al abrir el sobre; `sobre.audio` = ruta del audio (o `null`) |
| `carta` | Edita/añade frases; cada frase aparece una a una |
| `textoFecha` | Texto de la portada bajo su nombre (ahora: "Hoy, tu cumpleaños") |

## 2. Cambiar fotos y música
- Foto: reemplaza el archivo en `fotos/` con el mismo nombre (o cambia la ruta en `CONFIG.fotos`). Para más fotos, copia un bloque `{ src, frase, pos }`.
- `pos` mueve el recorte (ej. `"50% 20%"` muestra más la parte de arriba).
- Música: guarda tu mp3 como `musica/cancion.mp3`.
- Video: reemplaza `video/abrazo.mp4` (mejor ≤ 5 MB).
> En iPhone el volumen lo controla el teléfono, así que el fade de volumen no se nota allí.

## 3. Publicar gratis (Netlify Drop, lo más fácil)
1. Descomprime el zip (debe quedar una carpeta con `index.html`, `fotos`, `musica`, `video`).
2. Entra a https://app.netlify.com/drop e inicia sesión.
3. Arrastra **la carpeta completa** a la página.
4. Copia el enlace (puedes cambiar el nombre del sitio en *Site settings → Change site name*).
5. Ábrelo en tu celular y pruébalo completo **antes** del día.

Alternativa: GitHub Pages (sube los archivos a un repo → Settings → Pages) o Render (Static Site).

## 4. Convertir el enlace en QR
- Entra a https://www.qr-code-generator.com o https://goqr.me, pega el enlace y descarga el QR en PNG/SVG (alta resolución).
- Pruébalo escaneando con la cámara del celular antes de imprimir.

## 5. Texto para la tarjeta impresa
> **Feliz cumpleaños.**
> Preparé algo especial para ti.
> Escanea con tu cámara. 💌
>
> *(Sube el volumen y ponte cómoda: dura unos minutos.)*

## Consejos
- Ábrela por primera vez en un celular con internet (las fuentes y el confeti cargan por internet).
- El audio inicia al tocar “Toca para comenzar”: es normal, los móviles lo exigen.
- Si quieres probar en tu computadora, haz doble clic en `index.html`.
