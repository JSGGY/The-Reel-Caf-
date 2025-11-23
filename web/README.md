# The Reel Café

Proyecto de aplicación web para una comunidad de cinéfilos donde pueden descubrir películas, compartir reseñas y conectar con otros usuarios.

## Páginas Implementadas

### 1. **index.html** - Página Principal (Sin iniciar sesión)

- Header con logo, buscador y botones de navegación
- Sección hero con bienvenida y descripción del sitio
- Sección de películas destacadas con slider
- Footer

### 2. **home-logged.html** - Página Principal (Usuario logeado)

- Header con avatar de usuario
- Feed social con reseñas de personas que sigues
- Sección de películas destacadas
- Footer

### 3. **login.html** - Iniciar Sesión

- Formulario de login con correo y contraseña
- Imagen decorativa
- Link a registro

### 4. **register.html** - Crear Cuenta

- Formulario de registro con username, correo y contraseñas
- Imagen decorativa
- Validación de contraseña

### 5. **movie-search.html** - Búsqueda de Películas

- Resultados de búsqueda
- Tarjetas de películas con información básica
- Botón para ampliar información

### 6. **movie-detail.html** - Detalle de Película

- Información completa de la película (poster, sinopsis, director, duración)
- Reproductor de trailer (placeholder)
- Calificación promedio
- Sección de reseñas de usuarios
- Botón para escribir reseña

### 7. **user-profile.html** - Perfil de Usuario

- Avatar grande del usuario
- Información del perfil (nombre, seguidores)
- Reseñas publicadas por el usuario
- Botones para editar perfil y reseñas

### 8. **admin-users.html** - Panel de Administración de Usuarios

- Buscador de usuarios
- Tabla con lista de usuarios (username, correo, rol)
- Botones de gestión: editar perfil, eliminar cuenta, desactivar/activar cuenta

### 9. **home-admin.html** - Panel de Control de Administrador

- Header con avatar y botón de cerrar sesión
- Título de bienvenida personalizado
- Panel de control con imagen destacada
- Dos botones principales: Gestionar usuarios y Gestionar películas
- Sección de películas destacadas

### 10. **admin-movies.html** - Panel de Administración de Películas

- Buscador de películas
- Tabla con lista de películas (poster, título, duración)
- Botones para editar película y publicar nueva

### 11. **admin-movie-edit.html** - Editar Película Existente

- Formulario prellenado con datos de la película (The Batman)
- Campo de poster con imagen actual
- Campos: Título, Sinópsis, Director, Duración, Trailer URL
- Botones: Guardar y Cancelar

### 12. **admin-movie-new.html** - Publicar Nueva Película

- Formulario vacío con placeholders
- Campo de poster con ícono de subida
- Campos: Título, Sinópsis, Director, Duración, Trailer URL
- Botones: Publicar y Cancelar

### 13. **write-review.html** - Escribir Reseña de Película

- Información de la película (poster, sinopsis, director, duración)
- Textarea grande para escribir la reseña
- Input para ingresar calificación (0-5)
- Botones: Publicar y Cancelar

### 14. **user-search.html** - Búsqueda de Usuario

- Resultados de búsqueda de usuarios
- Avatar grande y nombre del usuario
- Link al perfil del usuario

### 15. **user-public-profile.html** - Perfil Público de Usuario

- Vista de perfil de otro usuario (Will Ferrell)
- Avatar, nombre y número de seguidores
- Lista de reseñas publicadas con likes
- Botones: Seguir y Volver

### 16. **edit-review.html** - Editar Reseña Existente

- Sidebar con información del perfil
- Formulario de edición con poster de la película
- Textarea con reseña actual
- Input de calificación prellenado
- Botón: Guardar

### 17. **edit-profile.html** - Editar Perfil de Usuario

- Upload de foto de perfil con preview
- Formulario con campos: Username, Correo, Contraseña actual, Contraseña nueva
- Botones: Confirmar y Cancelar

### 18. **movie-detail-logged.html** - Detalle de Película (Usuario Logeado)

- Igual que movie-detail.html pero con header de usuario logeado
- Botón "Escribir reseña" funcional
- Sección de reseñas de otros usuarios

## Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: Estilos personalizados con sistema de diseño
- **CSS Variables**: Sistema de variables para colores, tipografías y espaciados
- **Google Fonts**: Poppins, Prociono, Montserrat, DM Sans

## Características del Diseño

### Sistema de Diseño

El proyecto usa un sistema de variables CSS en `framework.css` que estandariza:

- **Colores**: Primarios, secundarios, de texto y fondos
- **Tipografías**: 4 familias con 10 tamaños estandarizados
- **Espaciados**: 7 niveles de espaciado consistente
- **Border Radius**: 8 niveles de redondeo
- **Sombras**: 3 niveles de elevación
- **Transiciones**: 3 velocidades de animación
- **Clases utilitarias**: Helpers para desarrollo rápido

Ver `DESIGN-SYSTEM.md` para documentación completa.

### Tipografía

- **Prociono**: Título principal del sitio
- **Poppins**: Títulos y textos generales
- **Montserrat**: Buscador
- **DM Sans**: Información de películas

### Responsive Design

- Diseño adaptable para desktop, tablet y móvil
- Breakpoints: 1440px, 1200px, 992px, 768px

## Estructura de Archivos

```
web/
├── index.html              # Página principal sin login
├── home-logged.html        # Página principal con login (usuario)
├── home-admin.html         # Panel de control (administrador)
├── login.html              # Inicio de sesión
├── register.html           # Registro de usuario
├── movie-search.html       # Búsqueda de películas
├── movie-detail.html       # Detalle de película (sin login)
├── movie-detail-logged.html # Detalle de película (logeado)
├── write-review.html       # Escribir reseña
├── user-profile.html       # Perfil de usuario propio
├── user-search.html        # Búsqueda de usuario
├── user-public-profile.html # Perfil público de otro usuario
├── edit-review.html        # Editar reseña
├── edit-profile.html       # Editar perfil
├── admin-users.html        # Admin: Gestión de usuarios
├── admin-movies.html       # Admin: Lista de películas
├── admin-movie-edit.html   # Admin: Editar película
├── admin-movie-new.html    # Admin: Nueva película
├── styles.css              # Estilos CSS (2400+ líneas)
├── framework.css           # Sistema de variables CSS
├── README.md               # Documentación
├── CREDENTIALS.md          # Credenciales de prueba
└── DESIGN-SYSTEM.md        # Documentación del sistema de diseño
```

## Funcionalidades

### Usuario No Registrado

- Ver películas destacadas
- Buscar películas
- Ver detalles de películas
- Acceder a login y registro

### Usuario Registrado

- Todo lo anterior, más:
- Ver feed social con reseñas de usuarios que sigue
- Escribir y editar reseñas de películas
- Ver y editar su perfil (username, correo, contraseña, foto)
- Buscar y seguir a otros usuarios
- Ver perfiles públicos de otros usuarios con sus reseñas

### Administrador

- Todo lo de usuario registrado, más:
- Acceder al panel de control administrativo
- Gestionar usuarios (editar, eliminar, desactivar/activar)
- Gestionar películas (agregar, editar, eliminar)
- Ver lista completa de películas con posters
- Formularios para editar y crear películas

## Instalación y Uso

1. Clonar o descargar el repositorio
2. Abrir `index.html` en un navegador web
3. No requiere servidor, funciona con archivos estáticos

## Notas Importantes

- Este proyecto usa solo HTML y CSS, sin JavaScript
- Las imágenes se cargan desde URLs de Figma (válidas por 7 días)
- Los botones y links son decorativos (no funcionales sin backend)
- Para producción, reemplazar las URLs de imágenes con assets locales

## Credenciales de Acceso

Ver archivo `CREDENTIALS.md` para detalles completos.

### Usuario Normal:

- **Email:** usuario@reelcafe.com
- **Contraseña:** usuario123
- **Acceso:** home-logged.html

### Administrador:

- **Email:** admin@reelcafe.com
- **Contraseña:** admin123
- **Acceso:** home-admin.html

## Navegación Rápida

### Como Usuario Normal:

1. `index.html` → Click "INICIO SESION" → Simular login
2. Abrir directamente `home-logged.html`
3. Ver película: `movie-detail-logged.html`
4. Escribir reseña: `write-review.html`
5. Ver perfil: `user-profile.html`
6. Editar perfil: `edit-profile.html`
7. Editar reseña: `edit-review.html`
8. Buscar usuario: `user-search.html`
9. Ver perfil público: `user-public-profile.html`

### Como Administrador:

1. `index.html` → Click "INICIO SESION" → Simular login admin
2. Abrir directamente `home-admin.html`
3. Gestionar usuarios: `admin-users.html`
4. Gestionar películas: `admin-movies.html`
   - Editar: `admin-movie-edit.html`
   - Nueva: `admin-movie-new.html`

## Sistema de Variables CSS

El proyecto implementa un sistema completo de diseño con variables CSS:

```css
/* Ejemplo de uso */
.mi-boton {
  background-color: var(--color-primary);
  padding: var(--spacing-md);
  border-radius: var(--radius-md);
  transition: all var(--transition-normal);
}
```

### Beneficios:

- ✅ Código más mantenible
- ✅ Consistencia en todo el proyecto
- ✅ Fácil cambio de tema
- ✅ Desarrollo más rápido con clases utilitarias

## Créditos

- Diseño: Figma - The Reel Café
- Desarrollo: 2025B - Aplicaciones Web - Grupo 2
- Arquitectura CSS: Sistema de diseño con variables
- Total de archivos HTML: 18 páginas
- Total de líneas CSS: 2400+ líneas
- Variables CSS: 80+ variables estandarizadas
