# Mesón El Duque

Web estática independiente en HTML, CSS y JavaScript vanilla. Abre `index.html` con Live Server. Sin compilación ni dependencias de producción. Repositorio: https://github.com/pabloldl/mesonelduque. La subida del código no implica desplegar la web.

## Contenido

Consulta `creditos.html` para fuentes y licencias. Fotografías ilustrativas identificadas en la interfaz: no son platos o instalaciones del mesón. Se revisaron visualmente las fotografías originales disponibles y las nuevas incorporaciones. Se conservaron todos los originales, incluidas una fotografía de ambiente y otra de mercado descartadas por falta de representatividad. El rediseño utiliza cinco imágenes diferentes, sin repeticiones, en WebP responsive: portada, collage asimétrico de tres imágenes y detalle dulce. No hay material real autorizado del establecimiento, por lo que la sección del mesón se adapta a su ubicación sin simular instalaciones.

Carta digital comprobada por descarga HTTP desde Odibo (nombre y localidad coinciden). Su vigencia y gestión por los titulares no están confirmadas; el sitio remite al servicio externo sin reproducir precios. Teléfono corroborado en fuentes independientes; no comprobado mediante llamada. Horarios omitidos por discrepancias. No se han usado fotografías de terceros del establecimiento sin autorización.

Cada HTML público incluye exactamente una etiqueta `noindex, nofollow`. No se añade un bloqueo de rastreo que impida leer esa directiva.

## Rediseño

Nueva composición de cartel gastronómico, tipografía Anybody en titulares e Instrument Sans en textos. Paleta crema #FFF8E8, naranja #F07835, tomate #D94432, oliva #657A3B y negro #26231F. Variante tomate más oscura en botones para contraste de texto pequeño. Portada sin texto sobre los platos, collage con proporciones diferentes, carta como cartel enlazado y footer naranja compacto. Animaciones por entrada y hover, sin movimiento constante. Originales y licencias conservados. No hay dependencias de producción.

Se compararon las fuentes y composiciones locales de Puerta del Parque, Tasquita El Callejón, Café-Pub Andalucía, Café Pub La Luna, Bar Cafetería El Encuentro y Frutería Tamara; no se copiaron archivos, fotos ni componentes. Abbracciame no está disponible como proyecto local, por lo que no se pudo comparar directamente.

Herramientas de comprobación locales en `.qa/`, excluidas por `.gitignore`. No forman parte de los archivos necesarios para servir la web.

## Verificación ejecutada

Chrome y WebKit locales, mediante Playwright: anchos 375, 390, 768, 1440 y 1920 px. Sin desbordamiento horizontal, errores de JavaScript, respuestas HTTP de error en recursos locales ni anclas inexistentes. Fotografías y fuentes cargadas. Menú móvil: apertura, cierre con Escape y cierre al seleccionar un enlace. Navegación disponible sin JavaScript y movimiento reducido comprobado. Una etiqueta robots en cada HTML público. Capturas y resultados por motor en `.qa/`. WebKit es una comprobación del motor, no una prueba en Safari de un iPhone físico. La consulta de Google Maps abre una búsqueda por nombre, calle y municipio; no se ha validado un identificador de ficha de Google Business.
