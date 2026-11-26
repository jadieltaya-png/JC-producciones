# JC · Jadiel Cárdenas — Productor audiovisual

Portafolio estático, interactivo y adaptable a móvil, listo para GitHub Pages. No necesita instalar dependencias, servidor de aplicación ni compilación.

## Publicar en GitHub Pages

1. Descomprime el ZIP.
2. En https://github.com/new crea un repositorio público llamado `jc-portafolio`.
3. En el repositorio elige **Add file → Upload files**. Arrastra `index.html`, `styles.css`, `script.js`, `README.md`, `.nojekyll` (opcional) y la carpeta `assets` conservando su estructura. No subas únicamente el ZIP ni la carpeta contenedora `JC-Portafolio`: `index.html` debe estar en la raíz del repositorio. Si el navegador no admite arrastrar una carpeta, crea `assets` y carga los archivos allí, o usa GitHub Desktop.
4. Pulsa **Commit changes**.
5. Abre **Settings → Pages**. En **Build and deployment**, elige **Deploy from a branch**, selecciona `main` y `/ (root)`, y pulsa **Save**.
6. Cuando finalice la publicación, GitHub mostrará la URL. Habitualmente será `https://TU-USUARIO.github.io/jc-portafolio/`.

## Personalización

- `index.html`: nombre, textos, servicios y secciones. El nombre está escrito como Jadiel Cárdenas según el encargo.
- `styles.css`: diseño, versión móvil y colores. La variable `--accent` define el verde lima.
- `script.js`: lista de proyectos, filtros, ventanas de detalle, menú, formulario. Escribe tu correo real entre las comillas de `CONTACT_EMAIL` para habilitar el enlace de correo y el botón de abrir correo. No se inventó ninguna dirección.
- `assets/`: portadas SVG originales de muestra y un video MP4 de motion graphics de demostración (sin audio). Reemplaza las portadas y el reel por tus fotografías y videos reales y actualiza sus rutas y descripciones en `script.js`. Las piezas conceptuales están señaladas como tales; no representan clientes o trabajos realizados.

## Qué funciona

Menú móvil, navegación por secciones, filtros de proyectos, detalles en ventanas modales, reproducción del video, selección de servicios, validación de formulario y generación, copia y descarga de una solicitud de proyecto. El formulario no envía información a un servidor; con el correo configurado abre el cliente de correo del visitante. Para envíos automáticos se requiere un servicio externo.

Puedes abrir `index.html` directamente para una vista previa. Para probarlo mediante HTTP, ejecuta `python -m http.server 8000` desde esta carpeta y visita `http://localhost:8000`.

## Fotografías añadidas

Se incluyen las diez fotografías proporcionadas en `assets/fotografias/`. Las imágenes conservan sus archivos originales. Cada una aparece en el filtro Fotografía y se puede abrir en una ventana de detalle sin recorte. Se mantienen los seis proyectos originales y el resto de la página. Antes de publicar, asegúrate de tener permiso para mostrar las fotografías y retratos públicamente.

## Documentos de diseño añadidos

En el filtro **Diseño** encontrarás el moodboard De Una Licorería (1 página) y el manual Verosé (25 páginas). Ambos PDF originales se conservan sin modificaciones en `assets/documentos/`. Cada documento se puede consultar página a página dentro del portafolio, abrir como PDF o descargar. Las vistas previas JPG son locales y no requieren servicios externos. Se conservan los 16 proyectos anteriores.

Al actualizar un repositorio existente, reemplaza `index.html`, `styles.css`, `script.js` y `README.md`, y carga también la carpeta `assets/documentos/` completa con sus subcarpetas. Si publicas desde cero, sube todo el ZIP descomprimido.
