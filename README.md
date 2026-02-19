# Landing Page.

Proyecto de réplica y maquetación de la Landing Page Figma Land para prueba técnica.
Centrada en interfaz de usuario responsiva y en un diseño **Pixel Perfect**

**Ver aquí: [Página desplegada](https://sabenitez-unal.github.io/landing-page/)**:

## Tecnologías utilizadas.
- **HTML 5**: Con estructura semántica y accesible.
- **TailwindCSS**: Framework basado en NodeJS para creación de diseño ágil y moderno.
- **FontAwesome**: Libreria de íconos utilizados.

## Las principales características.
- **Layout Responsivo**: Adaptación total desde dispositivos móviles hasta pantallas de escritorio (Mobile First).
- **Corte de Sección Personalizado**: Implementación de un diseño en "V" mediante SVG para el Hero.
- **Formulario Dinámico**: Maquetación de formulario de contacto con estados de focus y validación básica.
- **Optimización de Capas**: Manejo avanzado de z-index y posicionamiento absoluto/relativo.
- **Inversión de Orden (Flexbox/Grid)**: Los elementos cambian su orden jerárquico en móviles para mejorar la experiencia de usuario (UX).

## Instalación

**1. Clonar el repositorio:**
    ```git clone https://github.com/sabenitez-unal/landing-page.git```

**2. Instalar dependencias (Se necesita Node.js):**
    ```npm install```

**3. Compilar el CSS de Tailwind:**
    ```npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch```

## Uso
Puedes abrir el proyecto de dos maneras:
1. abre el archivo index.html con tu navegador.
2. Utiliza una extensión de 'Live Server' en tu editor de código.
    - Ejemplo: Live Server de Visual Studio Code.
