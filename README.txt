MUJER BONITA — Demo de tienda (exportación)

Cómo abrir:
  1. Descomprime la carpeta completa.
  2. Abre index.html en Chrome, Edge o Safari (doble clic funciona).
     Para mejor rendimiento sírvela con un servidor local, p. ej.:
       npx serve .      o      python3 -m http.server 8080

Estructura:
  index.html   Página completa (portada, mundos Dama/Caballero/Niños, catálogos, fichas, quiz, carrito, checkout)
  js/          Runtime de la interfaz (support.js) y componente de imágenes (image-slot.js)
  img/         Todas las fotos: campañas MB-01…MB-21, packshots MB-22…MB-41 y fotos propias de ropa/accesorios

Requiere internet para: tipografías de Google Fonts y librería React (CDN). Las imágenes locales funcionan sin conexión.
Configuración rápida (en index.html, bloque data-props): moneda (USD / Bs. / Ambas), barra de anuncio, mínimo al mayor (12).