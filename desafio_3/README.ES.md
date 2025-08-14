# Perfil de Enlaces Sociales

Este proyecto implementa una tarjeta de perfil con enlaces a redes sociales, incluyendo una animación de carga tipo "skeleton" para mejorar la experiencia de usuario.

## Contenido del Proyecto

### Estructura de Archivos

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

## Tecnologías Utilizadas

- **HTML5**: Estructura semántica para el contenido
- **CSS3**: Estilos y animaciones
    - Variables CSS para gestión de colores y espaciados
    - Flexbox y Grid para maquetación
    - Animaciones con @keyframes
    - Media queries para diseño responsive
- **JavaScript**: Funcionalidad básica para simular carga y recargar la página

## Características Implementadas

### 1. Diseño Responsive

El diseño se adapta a diferentes tamaños de pantalla mediante media queries, ajustando el tamaño de la imagen de perfil y los espaciados.

### 2. Animación de Carga (Skeleton Loading)

Se implementó un estado de carga tipo "skeleton" que:
- Muestra un esqueleto de la interfaz mientras se carga el contenido real
- Incluye una animación de gradiente que se desplaza horizontalmente
- Mejora la percepción de velocidad para el usuario
- Se reemplaza automáticamente por el contenido real después de 2 segundos

### 3. Accesibilidad

- Estructura semántica con elementos HTML apropiados
- Atributos ARIA para mejorar la experiencia de usuarios con lectores de pantalla
- Contraste adecuado entre texto y fondo
- Textos alternativos para imágenes

### 4. Optimización de Rendimiento

- Precarga de fuentes para evitar FOUT (Flash of Unstyled Text)
- Atributo "decoding" para optimizar la decodificación de imágenes
- Estructura CSS organizada con variables para mantenibilidad
