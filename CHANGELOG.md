# Registro de Cambios - MyAnimeNotes

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
