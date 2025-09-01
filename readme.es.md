# Receta Simple de Tortilla - Proyecto Frontend

Este proyecto es una página web responsiva que muestra una tarjeta de receta para una tortilla simple. Fue creado como un ejercicio de desarrollo frontend para demostrar habilidades en HTML y CSS.

## Descripción General del Proyecto

El proyecto consiste en una tarjeta de receta de una sola página con un diseño limpio y moderno que se adapta a diferentes tamaños de pantalla. La tarjeta de receta incluye:

- Título y descripción de la receta
- Información del tiempo de preparación
- Lista de ingredientes
- Instrucciones paso a paso para cocinar
- Información nutricional

## Tecnologías Utilizadas

- HTML5
- CSS3
- Diseño responsivo con media queries
- Fuentes personalizadas (Outfit y Young Serif)

## Estructura del Proyecto

```
PROYECTOMENTOR/
├── assets/
│   ├── fonts/
│   │   ├── outfit/           # Archivos de fuente Outfit
│   │   └── young-serif/      # Archivos de fuente Young Serif
│   └── images/
│       ├── favicon-32x32.png # Favicon
│       └── image-omelette.jpeg # Imagen principal de la receta
├── css/
│   ├── normalize.css         # CSS reset/normalize
│   └── style.css             # Estilos personalizados
├── index.html                # Archivo HTML principal
└── README.md                 # Documentación del proyecto
```

## Características

- Diseño completamente responsivo que funciona en pantallas móviles, tablets y escritorio
- Estructura HTML semántica
- Tipografía personalizada con fuentes web precargadas
- Esquema de colores accesible con contraste apropiado
- CSS organizado con propiedades personalizadas (variables)
- Información detallada de la receta con secciones claras

## Detalles de Diseño

### Colores

El proyecto utiliza una paleta de colores cuidadosamente seleccionada:
- Blanco: `hsl(0, 0%, 100%)`
- Tonos piedra: desde claro `hsl(30, 54%, 90%)` hasta oscuro `hsl(24, 5%, 18%)`
- Acento marrón: `hsl(14, 45%, 36%)`
- Acentos rosa: desde claro `hsl(330, 100%, 98%)` hasta oscuro `hsl(332, 51%, 32%)`

### Tipografía

Se utilizan dos familias de fuentes principales:
- **Outfit** (sans-serif): Utilizada para texto del cuerpo y algunos encabezados
- **Young Serif** (serif): Utilizada para encabezados principales

Se definen preajustes de texto para una tipografía consistente en todo el proyecto:
- Preajuste de Texto 1: Encabezados grandes (40-48px)
- Preajuste de Texto 2: Encabezados medianos (28px)
- Preajuste de Texto 3: Encabezados pequeños (20px)
- Preajuste de Texto 4: Texto del cuerpo (16px)

### Diseño Responsivo

El diseño se adapta a diferentes tamaños de pantalla:
- Móvil: Tarjeta de ancho completo con padding mínimo
- Tablet (768px+): Padding añadido y espaciado ajustado
- Escritorio (1440px+): Ancho máximo de 736px con diseño centrado

## Cómo Usar

1. Clonar o descargar este repositorio
2. Abrir el archivo `index.html` en cualquier navegador web moderno
3. La tarjeta de receta se mostrará correctamente en cualquier tamaño de dispositivo

## Notas de Desarrollo

- Se utilizan propiedades personalizadas de CSS (variables) para colores, espaciado y tipografía consistentes
- Las media queries aseguran una visualización adecuada en diferentes tamaños de dispositivos
- Los elementos HTML semánticos mejoran la accesibilidad y el SEO
- Las fuentes precargadas evitan cambios de diseño durante la carga de la página

## Créditos

- Fuentes: Outfit y Young Serif
- Inspiración de diseño: Desafíos de Frontend Mentor
