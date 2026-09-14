# Ludoteca — Sitio web estático

## Descripción
Sitio web estático para reseñar juegos de mesa de una ludoteca. El catálogo está dividido en **Estrategia**, **Cartas** y **Familiares**. La selección de categorías funciona únicamente con HTML/CSS mediante enlaces internos y `:target`, sin JavaScript.

## Estructura
```text
ludoteca_estatica/
├── index.html
├── estilosIA.css
├── README.md
├── imagenes/
│   ├── ajedrez.svg
│   ├── risk.svg
│   ├── truco.svg
│   ├── uno.svg
│   ├── oca.svg
│   └── ludo.svg
└── reglamentos/
    ├── ajedrez.pdf
    ├── risk.pdf
    ├── truco.pdf
    ├── uno.pdf
    ├── oca.pdf
    └── ludo.pdf
```

## Visualización
1. Descargar/descomprimir el proyecto.
2. Abrir `index.html` en cualquier navegador moderno.
3. No hace falta instalar dependencias ni ejecutar un servidor.
4. Las portadas son ilustraciones SVG locales, por lo que no dependen de imágenes externas.
5. Los reglamentos son archivos PDF reales y están enlazados desde cada reseña.

## Tecnologías
- HTML5
- CSS3
- SVG para las portadas
- PDF para los reglamentos
- Sin JavaScript ni scripts
