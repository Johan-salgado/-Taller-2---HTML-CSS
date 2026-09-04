# Taller 2 - HTML + CSS

Proyecto desarrollado para el **Taller 2 - HTML + CSS** de la asignatura
**Programación en Ambiente Web I**, Facultad de Ingeniería, Unidad Central
del Valle del Cauca (UCEVA).

**Docente:** Jesus David Mejia Vergara

## Descripción

Este repositorio contiene el desarrollo de **dos páginas web** aplicando los
conocimientos adquiridos en los módulos de HTML y CSS. Cada proyecto aplica
buenas prácticas de estructuración semántica y estilos limpios, utilizando la
librería **Pico CSS** (modo *classless*) como base de diseño.

Las temáticas escogidas fueron:

1. 🎮 **Catálogo de Videojuegos**
2. 🎬 **Catálogo de Películas o Series**

## Tecnologías utilizadas

- **HTML5** – estructura semántica del sitio (`nav`, `header`, `main`,
  `section`, `article`, `footer`).
- **CSS3** – estilos personalizados en `styles.css` (flexbox, selectores,
  cascada y herencia).
- **Pico CSS** – sistema de estilos classless como base visual.

## Estructura del proyecto

```
├── catalogo-videojuegos/
│   ├── index.html      # Estructura principal del catálogo de videojuegos
│   └── styles.css       # Estilos personalizados
│
├── catalogo-peliculas-series/
│   ├── index.html      # Estructura principal del catálogo de películas y series
│   └── styles.css       # Estilos personalizados
│
└── README.md             # Documentación del proyecto
```

## 🎮 Catálogo de Videojuegos

Página web que presenta un catálogo de videojuegos, permitiendo visualizar
los títulos disponibles, consultar sus reseñas y calificaciones, y enviar
sugerencias de nuevos juegos mediante un formulario de contacto.

**Secciones:**

- **Catálogo** – tarjetas con los videojuegos disponibles (imagen, género y
  precio).
- **Reseñas** – tabla con las calificaciones y el estado de cada juego.
- **Sugerir un Juego** – formulario de contacto para proponer nuevos títulos.

## 🎬 Catálogo de Películas o Series

Página web que presenta un catálogo de películas y series, permitiendo
visualizar los títulos disponibles con su año y calificación, consultar el
historial de últimos agregados, y añadir nuevos títulos mediante un
formulario.

**Secciones:**

- **Catálogo** – tarjetas con las películas y series disponibles (imagen,
  género, año y calificación).
- **Últimos Agregados** – listado con los movimientos recientes del catálogo.
- **Calificaciones** – tabla con la calificación y el estado (vista /
  pendiente) de cada título.
- **Agregar Película o Serie** – formulario para registrar nuevos títulos.

## Cómo visualizarlo

1. Clona el repositorio.
2. Abre el `index.html` del proyecto que quieras revisar
   (`catalogo-videojuegos/` o `catalogo-peliculas-series/`) en tu navegador.

No requiere instalación de dependencias adicionales; los estilos de Pico CSS
se cargan desde un CDN.

## Autores

- Johan Eliu Salgado Castro - 230232033
- Jose Daniel Tenorio Rivas - 230232009

## Licencia

Proyecto académico desarrollado con fines educativos.
