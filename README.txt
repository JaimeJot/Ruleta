# Ruleta — versión instalable (PWA)

Esta carpeta contiene la ruleta preparada para instalarse como aplicación web (PWA).

Archivos principales:
- `index.html`: entrada de la aplicación.
- `background.jpeg`: fondo original.
- `manifest.webmanifest`: configuración de instalación.
- `service-worker.js`: permite cargar la aplicación sin conexión después de haberla visitado/instalado.
- `icons/`: iconos de la aplicación.

IMPORTANTE:
Para que el navegador permita instalarla como aplicación, debe publicarse mediante HTTPS (por ejemplo, GitHub Pages).
Abrir `index.html` directamente desde los archivos del teléfono sirve para probar la ruleta, pero no activa la instalación PWA.

La ruleta original se mantiene en `ruleta.html`.
