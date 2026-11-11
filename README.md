# ixaviervip — Página web (Versión 2)

Página personal de música de **ixaviervip**, hecha con HTML y CSS puro, sin frameworks.

> **Versión 2**: rediseño completo de la página. La versión 1 sigue disponible en el historial de commits de este repositorio.

## Novedades de la versión 2

- Nuevo diseño con foto de portada (hero) y tipografías **Bodoni Moda** (títulos) y **Space Mono** (textos pequeños).
- Estilos organizados con **variables CSS** (`:root`) para cambiar colores y medidas fácilmente.
- Enlaces a plataformas y redes en formato **píldora** (Spotify, Apple Music, Amazon Music, TikTok, Instagram, WhatsApp).
- **Tabla de canciones** con portada, título, fecha y reproductor de audio.
- **Formulario de contacto** conectado con [Formspree](https://formspree.io).
- **Bilingüe**: español (`index.html`) e inglés (`en.html`) con selector de idioma en el menú.
- Diseño adaptable a móvil (`@media`).

## Estructura

```
├── index.html        # Página en español
├── en.html           # Página en inglés
├── css/
│   └── style.css     # Estilos (compartidos por ambos idiomas)
├── img/              # Portadas y foto hero (no incluido en el repositorio)
└── audio/            # Canciones .wav (no incluido en el repositorio)
```

Las carpetas `img/` y `audio/` están en `.gitignore`, por eso no se suben a GitHub.

## Cómo verla

Abre `index.html` en el navegador (o con la extensión Live Server de VS Code).

## Contacto

xaviervenegas55@gmail.com
