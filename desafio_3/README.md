# Social Links Profile

This project implements a profile card with social media links, including a skeleton loading animation to improve the user experience.

## Project Contents

### File Structure

```
desafio_3/
├── assets/
│   ├── fonts/                    # Fuentes Inter (variable y estáticas)
│   │   ├── static/               # Versiones estáticas de Inter
│   │   ├── Inter-VariableFont_slnt,wght.ttf
│   │   ├── OFL.txt               # Licencia de la fuente
│   │   └── README.txt            # Documentación de la fuente
│   └── images/                   # Imágenes del proyecto
│       ├── avatar-jessica.jpeg   # Foto de perfil
│       └── favicon-32x32.png     # Favicon
├── css/
│   ├── normalize.css             # Reset CSS para consistencia entre navegadores
│   └── styles.css                # Estilos personalizados
├── index.html                    # Archivo HTML principal
└── README.md                     # Este archivo
```

## Technologies Used

- HTML5: Semantic structure for content
- CSS3: Styles and animations
  - CSS variables for color and spacing management
  - Flexbox and Grid for layout
  - Animations with @keyframes
  - Media queries for responsive design
- JavaScript: Basic functionality to simulate loading and reload the page

## Implemented Features

### 1. Responsive Design

The design adapts to different screen sizes via media queries, adjusting the profile image size and spacing.

### 2. Skeleton Loading Animation

A "skeleton" loading state is implemented that:
- Displays a skeleton of the interface while the real content loads
- Includes a gradient animation that moves horizontally
- Improves the user’s perceived loading speed
- Automatically switches to the real content after 2 seconds

### 3. Accessibility

- Semantic structure with appropriate HTML elements
- ARIA attributes to improve the experience for screen reader users
- Adequate contrast between text and background
- Alternative text for images

### 4. Performance Optimization

- Font preloading to avoid FOUT (Flash of Unstyled Text)
- The "decoding" attribute to optimize image decoding
- Well-organized CSS structure with variables for maintainability
