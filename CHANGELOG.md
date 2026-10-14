# Registro de Cambios - MyAnimeNotes

## [4.0.0] - 2026-10-14

Versión conjunta con la web 4.0.0: las dos pasan a compartir un formato de lista nuevo. La app, además, cambia de diseño entero.

### Nuevo

- Diseño nuevo en toda la app, con la portada de cada anime como protagonista. Inicio propone qué seguir viendo en una tarjeta grande teñida del color de su portada, Biblioteca es una cuadrícula de pósters con su progreso y Estadísticas se ilustra con las portadas de tu lista
- La ficha de un anime enseña sus episodios en una rejilla por temporadas: tocar uno lo deja como el último que viste, con «Deshacer» por si te equivocas
- Añadir un anime empieza buscando en el catálogo y sigue por pasos: ficha, episodios y progreso. La ficha se edita en el sitio, y los géneros y temas se eligen en una hoja
- Búsqueda dentro de Biblioteca: la cuadrícula se filtra mientras escribes, y puedes marcar varios géneros a la vez
- Con la lista vacía, Inicio te lleva a añadir el primer anime o a traer una lista de Drive o de un archivo
- Destacados pone los que estás viendo en un carrusel grande y los terminados en un estante aparte
- Actualizaciones busca sola si hay una versión nueva, enseña sus notas y descarga el APK
- Ayuda tiene buscador y una miniatura de cada control del que habla
- Acerca de dice dónde está tu lista: cuántos animes guarda el teléfono, cómo está tu copia de Drive y un acceso a la web
- Inicio saluda según la hora del día
- Al cerrar sesión se quitan del teléfono los animes que ya están en tu copia de Drive, y vuelven al iniciar sesión y traer la copia. Los que tienen cambios sin subir se quedan. Si la copia de Drive no es la que subió o trajo este teléfono, o no hay conexión para comprobarlo, no se quita ninguno
- Con la sesión iniciada, una nube tachada sobre el póster señala los animes con cambios sin subir, y el detalle dice si el anime está en tu copia de Drive

### Mejorado

- El progreso de un anime es el último episodio visto, y de ahí salen los vistos y el que sigue. Antes se guardaba el episodio que estabas viendo y se contaba como visto: con dos episodios vistos marcaba 3 de 12, y la web hasta 4. Ahora marca 2 de 12 y el siguiente es el 3, igual en la app y en la web
- El botón principal da por visto el episodio que toca, y marcar el último completa el anime
- Los botones y avisos dicen las cosas como se dirían en voz alta: «Ya vi el 3» en vez de «Vi el E3», «Te toca el 3», «17 de 28» en Biblioteca y «Traer la copia» como único nombre para traer la copia de Drive
- Los diálogos de confirmación tienen un diseño nuevo, con dos botones grandes y los datos de la copia o del archivo a la vista. El de eliminar un anime dice cuál es, y el de borrar la lista, cuántos animes se quitan
- Las fechas y los tamaños de la copia de Drive salen en español aunque el teléfono esté en otro idioma
- Cambiar de pestaña o de pantalla es más rápido y ya no deja ver un destello gris
- Tu lista y tu copia de Drive se convierten solas al abrir esta versión. Antes de guardar se comprueba el resultado contra el original, y un aviso te dice cuántos animes se convirtieron. La lista y la copia anteriores se conservan sin tocar
- La copia de Drive pasa a un archivo nuevo, para que una versión anterior de la app o de la web no pueda sobrescribirla
- Importar una lista exportada por una versión anterior la convierte al vuelo
- Con la sesión iniciada, lo que cambias en un dispositivo llega al otro al traer la copia de Drive: una ficha editada, un episodio desmarcado o un anime borrado. Antes solo llegaba el progreso cuando era mayor, y un anime borrado volvía a aparecer desde el otro dispositivo
- Si el mismo anime cambió en los dos dispositivos, se juntan los cambios: el progreso marcado en uno y la estrella puesta en el otro se conservan los dos. Solo cuando los dos cambiaron el mismo dato gana el que lleva más episodios vistos y, si llevan los mismos, el que se modificó más tarde
- Cerrar sesión y volver a entrar con la misma cuenta ya no hace perder lo que se borró en otros dispositivos mientras tanto
- Al importar un archivo, de un anime que ya tienes se queda la versión con más episodios vistos y, si llevan los mismos, la que se modificó más tarde
- Al traer la copia de Drive, el aviso final dice cuántos animes se añadieron y cuántos se quitaron
- Traer la copia de Drive ya no la vuelve a subir si el teléfono no tiene nada distinto, así que el otro dispositivo no se queda en pausa sin motivo. Lo que sí tenga distinto se sube solo

### Corregido

- Si la app se cerraba a mitad de guardar, la lista podía quedar cortada y leerse como vacía, y el siguiente cambio la guardaba así. Ahora el guardado no deja el archivo a medias, y uno que no se puede leer se aparta en vez de sobrescribirse
- Inicio ya no enseña «Tu biblioteca está vacía» durante un par de segundos al abrir la app
- La subida automática a Drive se hacía tres veces por cada cambio y reemplazaba la copia sin mirar qué había. Ahora sube una vez, y solo si la copia de Drive es la que subió o trajo este teléfono; si no, se pausa hasta que elijas cuál se queda
- Los errores de Drive se explican en español en vez de enseñar el mensaje técnico en inglés
- En el menú lateral, «atrás» cerraba la app en vez del menú
- Importar un archivo que no es una lista, o que es de una versión más nueva o demasiado antigua, explica el motivo en vez de decir «0 animes añadidos»
- El aviso de importación dice qué versión se queda de un anime que ya tienes, en vez de prometer que su información se actualiza siempre
- Si Drive no responde o rechaza el acceso, Ajustes dice que no pudo comprobar la copia y ofrece reintentar. Antes mostraba «Aún no hay copia en Drive» e invitaba a subir la lista encima de una copia que sí existía
- Cuando Google retira el permiso de Drive, la app lo vuelve a pedir en lugar de seguir fallando durante una hora con el acceso antiguo

### Eliminado

- Las listas en el formato antiguo de la versión 1 ya no se pueden importar

## [3.1.0] - 2026-07-09

### Nuevo

- Autocompletado de títulos con el catálogo público Anime Cover Catalog al añadir o editar un anime: al elegir una sugerencia se rellenan automáticamente portada, tipo, demografía, temas, géneros y episodios
- Sugerencias con miniatura y título en inglés en un menú flotante bajo el campo de título
- Enlace al catálogo de portadas de alta calidad en la sección Portada

### Mejorado

- Formulario de añadir/editar reorganizado: Información → Portada → Clasificación → Temporadas → Progreso, alineado con la versión web
- Sección "Clasificación" (antes "Categorización") con el orden Temas, Géneros y Género explícito
- Textos del control de progreso más claros ("Definir progreso actual")

### Corregido

- La versión mostrada en "Acerca de" ahora se lee dinámicamente de la app en lugar de estar fija

## [3.0.0] - 2026-05-27

### Nuevo

- Aplicación reconstruida desde cero como app nativa de Android
- Avance rápido de episodios directamente desde las tarjetas en Biblioteca e Inicio
- Filtro de "Favoritos" integrado en la Biblioteca
- Ordenar animes por progreso en la Biblioteca
- Filtros avanzados por tipo y demografía
- Opción para eliminar backup de Google Drive
- Acceso directo a Destacados, Actualizaciones y Acerca de desde el menú lateral
- Búsquedas recientes eliminables individualmente

### Mejorado

- Interfaz completamente rediseñada con animaciones más fluidas
- Nueva barra de navegación flotante en la parte inferior
- Pantalla de Ajustes con diseño de tarjetas agrupadas
- Diálogo de importar lista con vista previa del archivo y conteo de animes
- Diálogo de descargar backup con información detallada del respaldo
- Mejor rendimiento general y menor consumo de batería
- Tamaño de la aplicación reducido

## [2.1.0] - 2026-04-13

### Añadido

- Auto-sincronización automática con Google Drive al modificar datos (debounce de 2 segundos)
- Expiración de sesión por inactividad prolongada (120 minutos)
- Reintento automático de autenticación ante tokens expirados (error 401)
- Verificación silenciosa del estado del respaldo al abrir Ajustes
- Información detallada del respaldo en Ajustes: cantidad de animes, tamaño y fecha
- Foto de perfil de Google en la barra superior con indicador de sincronización animado
- Mensaje "Sesión restaurada" al reconectar una sesión persistida
- Acción "Verificar estado" en la sección de Google Drive de Ajustes

### Cambiado

- Rediseño completo de la sección Google Drive en Ajustes: encabezado con foto y datos del usuario, caja informativa del estado del respaldo y lista de acciones con iconos
- Arquitectura de proveedores refactorizada con ChangeNotifierProxyProvider para conectar AnimeProvider y CloudSyncProvider
- Servicio de sincronización refactorizado con manejo público de cliente autenticado y wrapper de reintento ante errores de autorización

## [2.0.0] - 2026-03-30

### Añadido

- Sincronización en la nube con Google Drive para respaldar y restaurar tu biblioteca
- Inicio de sesión con cuenta de Google integrado en Ajustes
- Opciones de restauración: combinar con datos locales o reemplazar completamente
- Selector de estilo de color: Azul (por defecto), Monocromático y Neutral
- Información de versión dinámica en la pantalla "Acerca de"

### Cambiado

- Rediseño completo de la interfaz con estilo Material 3 Expressive
- Nueva pantalla de Inicio con tarjetas minimalistas y carrusel de recientes mejorado
- Pantalla de Biblioteca con tarjetas redondeadas y barra de progreso visual
- Pantalla de Estadísticas con indicadores de colores semánticos
- Pantallas de Ajustes, Ayuda y Acerca de con nuevo diseño de tarjetas agrupadas
- Validaciones mejoradas de progreso al agregar o editar animes
- Tipografía y espaciado unificados en toda la aplicación

### Seguridad

- Manejo seguro de credenciales y datos de autenticación
- Validación de operaciones de respaldo antes de confirmar cambios

## [1.1.0] - 2025-09-20

### Añadido

- Modal para ver portadas de anime en pantalla completa con zoom interactivo
- Botón flotante de "volver arriba" que aparece al hacer scroll
- Icono de la app en la barra superior para ir directamente a "Acerca de"
- Nueva opción para buscar actualizaciones desde Ajustes

### Cambiado

- Comportamiento de la barra superior para ocultarse al desplazarte hacia abajo y reaparecer al subir
- Pantalla de Ajustes con mejor espaciado horizontal y secciones más organizadas
- Efecto ripple (onda) en chips informativos de detalles de anime
- Validaciones de archivo para aceptar solo JPG, JPEG, PNG y WEBP en imágenes locales
- Mensajes de error más claros para temporada/episodio actual, URLs vacías y tipos de archivo no soportados

### Corregido

- Edición de animes completados con múltiples temporadas para evitar episodios incorrectos al reabrir el formulario

## [1.0.0] - 2025-09-10

### Añadido

- Soporte inicial para dispositivos Android 8.0 en adelante
- Personalización de apariencia con temas claro, oscuro y de sistema
- Importación de lista de animes mediante archivo JSON desde la versión web
