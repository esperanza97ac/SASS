## Sass Demo Repository
Este repositorio contiene el código fuente y los ejemplos prácticos utilizados para una exposición breve sobre Sass, enfocada en sus funciones y características principales para mejorar y agilizar el flujo de trabajo en CSS.

## Contenido de la Demo
La demostración cubre los conceptos fundamentales que permiten escribir un código CSS más limpio, mantenible y modular:

Variables: Almacenamiento centralizado de colores, fuentes y medidas.

Anidamiento (Nesting): Estructura jerárquica del código para reflejar el DOM de HTML.

Mixins: Bloques de código reutilizables que aceptan argumentos.

Funciones y Operaciones: Cálculos matemáticos y manipulación de valores directamente en las hojas de estilo.

## Estructura del Proyecto
```text
mi-proyecto-sass/
├── scss/
│   ├── _base.scss         # Estilos base y reseteos
│   ├── _components.scss   # Componentes reutilizables (botones, tarjetas)
│   ├── _mixins.scss       # Mixins y funciones
│   └── main.scss          # Archivo principal que importa los parciales
├── css/
│   ├── main.css           # CSS compilado (salida)
│   └── main.css.map       # Mapa de rutas para depuración
└── index.html             # Página de ejemplo para visualizar estilos

Requisitos Previos
Para compilar y ejecutar este proyecto en tu máquina local, necesitas tener instalado sass compiler.

Node.js (opcional, si prefieres usar npm)

Un compilador de Sass. La forma más sencilla es mediante la extensión de Live Sass Compiler en Visual Studio Code.
