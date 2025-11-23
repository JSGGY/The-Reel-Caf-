# 🔐 Credenciales de Acceso - The Reel Café

## Usuarios de Prueba

### 👤 Usuario Normal

**Nombre de usuario:** usuario  
**Correo:** usuario@reelcafe.com  
**Contraseña:** usuario123  
**Páginas accesibles:**

- Página principal con feed social (home-logged.html)
- Perfil de usuario (user-profile.html)
- Búsqueda de películas (movie-search.html)
- Detalle de películas (movie-detail.html)
- Escribir reseñas

---

### 👨‍💼 Administrador

**Nombre de usuario:** admin  
**Correo:** admin@reelcafe.com  
**Contraseña:** admin123  
**Páginas accesibles:**

- Todo lo del usuario normal, más:
- Panel de control de administrador (home-admin.html)
- Gestión de usuarios (admin-users.html)
- Gestión de películas (admin-movies.html)
- Editar película (admin-movie-edit.html)
- Nueva película (admin-movie-new.html)

---

## Flujo de Navegación

### Para Usuario Normal:

1. Inicia en `index.html`
2. Click en "INICIO SESION" → `login.html`
3. Ingresa credenciales de usuario normal
4. Redirige a `home-logged.html` (página principal con feed)

### Para Administrador:

1. Inicia en `index.html`
2. Click en "INICIO SESION" → `login.html`
3. Ingresa credenciales de administrador
4. Redirige a `home-admin.html` (panel de control)
5. Desde allí puede acceder a:
   - "Gestionar usuarios" → `admin-users.html`
   - "Gestionar películas" → `admin-movies.html`
     - "Editar película" → `admin-movie-edit.html`
     - "Publicar nueva" → `admin-movie-new.html`

---

## Notas Importantes

- Este proyecto es solo HTML/CSS, las credenciales son indicativas
- Para simular el login como admin, abre directamente `home-admin.html`
- Para simular el login como usuario, abre directamente `home-logged.html`
- El botón "CERRAR SESIÓN" redirige a `index.html`
- No hay validación real de credenciales (requeriría JavaScript/Backend)

---

## Páginas Principales

### Públicas (sin login):

- `index.html` - Página principal
- `login.html` - Iniciar sesión
- `register.html` - Crear cuenta
- `movie-search.html` - Búsqueda de películas
- `movie-detail.html` - Detalle de película

### Usuario Logeado:

- `home-logged.html` - Inicio con feed social
- `user-profile.html` - Perfil de usuario

### Administrador:

- `home-admin.html` - Panel de control
- `admin-users.html` - Gestión de usuarios
- `admin-movies.html` - Lista de películas
- `admin-movie-edit.html` - Editar película
- `admin-movie-new.html` - Nueva película
