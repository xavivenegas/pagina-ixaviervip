# Página web de ixaviervip

Página personal hecha desde cero con **HTML y CSS** (sin frameworks) para mi proyecto musical **ixaviervip**: artista independiente de música electrónica. Reúne mis canciones con reproductor, mis enlaces a plataformas y redes, una sección «Sobre mí» y mi contacto.

Es un proyecto de práctica para aprender a estructurar una web, enlazar archivos, usar multimedia y aplicar estilos.

## Contenido de la página

- **Cabecera** con el nombre y una descripción corta.
- **Menú** que lleva a cada sección con enlaces internos.
- **Enlaces** para escucharme (Spotify, Apple Music, Amazon Music) y seguirme (TikTok, Instagram, canal de WhatsApp).
- **Canciones**: una tarjeta por tema, con portada, título, fecha y reproductor de audio.
- **Sobre mí** y **Contacto**.
- **Pie de página** con los derechos.

## Estructura del proyecto

```
.
├── index.html        # Página principal
├── css/
│   └── style.css     # Hoja de estilos
├── img/              # Portadas y foto (no incluidas en el repositorio)
└── audio/            # Canciones en .wav (no incluidas en el repositorio)
```

`index.html` va en la carpeta principal porque los servidores web lo abren automáticamente como página de inicio. Los archivos se enlazan con rutas relativas (`css/style.css`, `img/...`, `audio/...`).

> Las carpetas `img/` y `audio/` pesan decenas de MB, así que **no están en este repositorio** (ver `.gitignore`). Sin ellas la página se ve sin portadas ni audio.

## Etiquetas HTML usadas

| Etiqueta | Para qué la uso |
| --- | --- |
| `<header>`, `<nav>`, `<section>`, `<article>`, `<footer>` | Estructura semántica de la página |
| `<h1>` a `<h3>` | Títulos y subtítulos |
| `<p>`, `<strong>`, `<em>`, `<br>` | Texto, énfasis y saltos de línea |
| `<a>` | Enlaces externos, internos (`#canciones`) y de correo (`mailto:`) |
| `<img>` | Portadas y foto, siempre con `alt` |
| `<audio controls>` | Reproductor de cada canción |
| `<ul>` y `<li>` | Listas de enlaces |
| `<!-- -->` | Comentarios para recordar qué hace cada parte |

## Estilos con CSS

- **Tema oscuro**: fondo `#0f0f14` y texto claro `#eaeaf2`.
- **Cabecera** centrada con degradado (`linear-gradient`).
- **Título** con la fuente [Tiny5 Duo](https://fonts.google.com/) de Google Fonts, tamaño adaptable con `clamp()`.
- **Menú** con `display: flex` y `position: sticky` para que se quede arriba al bajar.
- **Secciones** centradas con `max-width` y `margin: auto`.
- **Listas de enlaces** sin viñetas y en fila con flexbox.

## Lo que he aprendido

- Organizar un proyecto en carpetas (`css`, `img`, `audio`) y usar rutas relativas.
- Añadir imágenes y audio, y por qué un archivo `.wav` pesa mucho más que un `.mp3`.
- Cargar una fuente externa de Google Fonts y aplicarla con CSS.
- Maquetar con flexbox y comentar el código en HTML y CSS.
- Validar el HTML con el [validador del W3C](https://validator.w3.org/).

## Ideas pendientes

- Presentar cada canción como tarjeta (portada a la izquierda, texto y audio a la derecha).
- Añadir una versión para móvil con `@media`.
- Reducir el peso de las portadas y recortar los audios a una preview corta.
- Publicarla con GitHub Pages.

## Cómo verla en local

1. Descarga o clona el repositorio.
2. Añade tus propias carpetas `img/` y `audio/` con los archivos que usa `index.html`.
3. Abre `index.html` en el navegador (o usa la extensión *Live Preview* de VS Code).

## Créditos

- Fuente **Tiny5 Duo**, de Stefan Schmidt, con licencia OFL, servida por Google Fonts.
- Música, portadas y foto: © ixaviervip.
