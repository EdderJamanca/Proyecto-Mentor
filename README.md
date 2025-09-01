# Simple Omelette Recipe - Frontend Project

This project is a responsive web page that displays a recipe card for a simple omelette. It was created as a frontend development exercise to demonstrate HTML and CSS skills.

## Project Overview

The project consists of a single-page recipe card with a clean, modern design that adapts to different screen sizes. The recipe card includes:

- Recipe title and description
- Preparation time information
- Ingredients list
- Step-by-step cooking instructions
- Nutritional information

## Technologies Used

- HTML5
- CSS3
- Responsive design with media queries
- Custom fonts (Outfit and Young Serif)

## Project Structure

```
PROYECTOMENTOR/
├── assets/
│   ├── fonts/
│   │   ├── outfit/           # Outfit font files
│   │   └── young-serif/      # Young Serif font files
│   └── images/
│       ├── favicon-32x32.png # Favicon
│       └── image-omelette.jpeg # Main recipe image
├── css/
│   ├── normalize.css         # CSS reset/normalize
│   └── style.css             # Custom styles
├── index.html                # Main HTML file
└── README.md                 # Project documentation
```

## Features

- Fully responsive design that works on mobile, tablet, and desktop screens
- Semantic HTML structure
- Custom typography with preloaded web fonts
- Accessible color scheme with appropriate contrast
- Organized CSS with custom properties (variables)
- Detailed recipe information with clear sections

## Design Details

### Colors

The project uses a carefully selected color palette:
- White: `hsl(0, 0%, 100%)`
- Stone tones: from light `hsl(30, 54%, 90%)` to dark `hsl(24, 5%, 18%)`
- Brown accent: `hsl(14, 45%, 36%)`
- Rose accents: from light `hsl(330, 100%, 98%)` to dark `hsl(332, 51%, 32%)`

### Typography

Two main font families are used:
- **Outfit** (sans-serif): Used for body text and some headings
- **Young Serif** (serif): Used for main headings

Text presets are defined for consistent typography throughout the project:
- Text Preset 1: Large headings (40-48px)
- Text Preset 2: Medium headings (28px)
- Text Preset 3: Small headings (20px)
- Text Preset 4: Body text (16px)

### Responsive Design

The layout adapts to different screen sizes:
- Mobile: Full-width card with minimal padding
- Tablet (768px+): Added padding and adjusted spacing
- Desktop (1440px+): Maximum width of 736px with centered layout

## How to Use

1. Clone or download this repository
2. Open the `index.html` file in any modern web browser
3. The recipe card will display properly on any device size

## Development Notes

- CSS custom properties (variables) are used for consistent colors, spacing, and typography
- Media queries ensure proper display across different device sizes
- Semantic HTML elements improve accessibility and SEO
- Preloaded fonts prevent layout shifts during page load

## Credits

- Fonts: Outfit and Young Serif
- Design inspiration: Frontend Mentor challenges
