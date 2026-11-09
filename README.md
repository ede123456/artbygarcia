# ARTBYGARCIA Makeup Studio — entrega final

Sitio completo con el diseño aprobado. HTML, CSS y JavaScript; no necesita instalación, compilación ni backend.

## Abrir en Codex
Descomprime el ZIP y abre la carpeta artbygarcia en Codex. Lee AGENTS.md y CONTINUAR-EN-CODEX.md. Ejecuta:

```sh
python -m http.server 3000 --directory dist
```

Visita http://localhost:3000. También puedes abrir dist/index.html directamente.

## Conservar exactamente el diseño
No rediseñar. Las tipografías están incluidas localmente: DM Sans 400/500/600 y Cormorant Garamond 400/500/600 normal, 400/500 italic. No depende de Google Fonts ni debe sustituirse por las fuentes de respaldo. fonts.css carga los ocho archivos TTF. Sus avisos de licencia están en FONT-LICENSES.txt.

Mantener todos los colores, encuadres, espacios y tamaños declarados en dist/styles.css. Sus reglas finales reflejan los ajustes aprobados. DISENO-APROBADO.json registra los hashes de todos los archivos del sitio para comprobar que no se alteraron durante la transferencia.

## Contenido y comportamiento
- Foto grupal de fondo en inicio, título y textos centrados.
- Glam RD$ 2,200; Soft glam RD$ 2,000; Novias RD$ 2,500; Social RD$ 1,800.
- Nombres arriba de cada galería; tres fotografías reales por servicio.
- Botones transparentes, redondeados, con texto y borde marrón claro. Los botones de servicios tienen tamaño compacto.
- Portafolio de 12 imágenes con filtros y ampliación.
- Sobre mí con fotografía y biografía proporcionadas.
- WhatsApp flotante verde en la esquina inferior derecha: +1 (809) 969-2405. Enlaces con mensaje preparado; no envían ni confirman citas automáticamente.
- Galería con Anterior, Siguiente, Escape y deslizamiento horizontal.
- Prioridad celular; menú móvil y escritorio adaptable. Sin flechas ni barra negra inferior.

## Archivos
- dist/index.html: estructura y contenido.
- dist/styles.css: diseño exacto aprobado.
- dist/app.js: galerías, filtros, menú y WhatsApp.
- dist/fonts.css y dist/assets/fonts/: tipografías locales.
- dist/assets/: 14 fotografías WebP proporcionadas por el usuario, sin alteración de rostros.

## Publicar
Sube el contenido de dist a un hosting estático. No contiene credenciales ni configuración vinculada a la cuenta de ChatGPT. No requiere migración de framework.

## Validación
JavaScript validado; 14 imágenes y 8 fuentes comprobadas. Versión base revisada en navegador de escritorio y a 390 px; menú, modal, navegación y filtros probados. Mantener una prueba final en iOS/Android real antes de la entrega comercial.
