# Flores Freelancer - Sitio Web Profesional

¡Bienvenido al repositorio de **Flores Freelancer**! Este es un sitio web moderno, elegante y totalmente responsivo desarrollado desde cero para ofrecer servicios de diseño y desarrollo web de manera profesional e independiente.

El proyecto destaca por una estética premium basada en una paleta de colores oscuros con acentos dorados metalizados, tipografía limpia y estructuras maquetadas con tecnologías web modernas.

---

## 🚀 Características del Proyecto

- **Estructura Multi-página Organizada:** Arquitectura limpia con separación de páginas secundarias dentro de la carpeta dedicada `assets/page/`.
- **Navegación Simétrica:** Cabecera y pie de página perfectamente equilibrados e idénticos en todas las secciones mediante el uso preciso de rutas relativas (`../` y `../../`).
- **Diseño Responsivo Intuitivo:** Adaptabilidad móvil completa para smartphones, tablets y pantallas de escritorio.
- **Secciones Implementadas:**
  - **Inicio (`index.html`):** Hero section dinámico con fondo de video integrado (`.mp4`), capa de contraste traslúcida y propuesta de valor persuasiva.
  - **Productos (`productos.html`):** Catálogo comercial estructurado de manera bidimensional mediante **CSS Grid**. Incluye 6 tarjetas de soluciones digitales con efectos dinámicos en `hover`.
  - **Contacto (`contacto.html`):** Formulario optimizado con un tono cercano (Vinculado a *Formspree*) y mapa interactivo panorámico centrado en **Merlo, Buenos Aires**.
- **Detalles Premium:** Integración de la librería oficial de iconos **Font Awesome** en el footer y configuración de favicon personalizado desde la carpeta `icon/`.

---

## 📂 Estructura de Carpetas

```text
/ Flores-Freelancer (Raíz)
│
├── index.html                  # Página principal de Inicio
├── README.md                   # Documentación oficial del proyecto
│
└── assets/                     # Recursos generales del sitio
    ├── css/
    │   ├── reset.css           # Normalización de estilos base
    │   ├── variables.css       # Variables globales (colores, fuentes)
    │   └── styles.css          # Archivo maestro de estilos CSS
    │
    ├── img/
    │   ├── logo/
    │   │   ├── logo.jpg        # Isotipo circular del header/footer
    │   │   └── free.jpg        # Logo de marca completo con relieve metálico
    │   ├── cards/              # Imágenes asignadas al catálogo de productos
    │   └── icon/
    │       └── favicon.ico     # Icono oficial para la pestaña del navegador
    │
    ├── video/
    │   └── bg-hero.mp4         # Clip de video de fondo optimizado para la sección principal
    │
    └── page/
        ├── productos.html      # Catálogo con grilla comercial en CSS Grid
        └── contacto.html       # Formulario y mapa interactivo de Google Maps

Contáctame y responderé a brevedad