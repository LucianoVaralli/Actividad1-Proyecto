# Mi Ludoteca - Catálogo Estático

Una página web estática para una ludoteca, diseñada 100% con HTML5 y CSS3, sin la necesidad de utilizar JavaScript.

## Descripción del Proyecto
Este sitio presenta un catálogo interactivo de reseñas de juegos de mesa organizados en tres categorías: Estrategia, Cartas y Familiares. Al no utilizar scripts, toda la lógica de pestañas (tabs) y navegación entre pantallas ("Single Page Application") está manejada exclusivamente mediante CSS usando pseudo-clases como `:checked` en conjunto con etiquetas `<input type="radio">`.

## Estructura de Archivos
```text
ludoteca_estatica/
│
├── index.html            # Archivo principal con la estructura semántica y el contenido.
├── estilosIA.css         # Hoja de estilos con variables de paleta, grid y lógica de tabs.
├── README.md             # Este archivo.
│
├── imagenes/             # Directorio con las portadas de los juegos (.png)
│   ├── ajedrez.png
│   ├── risk.png
│   ├── truco.png
│   ├── uno.png
│   ├── oca.png
│   └── ludo.png
│
└── reglamentos/          # Reglamentos generados en PDF para su descarga (.pdf)
    ├── ajedrez.pdf
    ├── risk.pdf
    ├── truco.pdf
    ├── uno.pdf
    ├── oca.pdf
    └── ludo.pdf
```

## Pasos para Visualizar el Sitio
1. Extraé o descargá la carpeta completa (`ludoteca_estatica/`).
2. Abrí el archivo `index.html` con cualquier navegador web moderno (Chrome, Firefox, Safari, Edge).
3. Navegá por las secciones desde el header y probá filtrar los juegos seleccionando las distintas categorías. ¡Todo funciona por puro CSS!
