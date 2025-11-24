# 🎨 Sistema de Diseño - The Reel Café

## Variables CSS (framework.css)

Este documento describe el sistema de diseño estandarizado del proyecto The Reel Café implementado con variables CSS (Custom Properties).

---

## 📦 Tabla de Contenidos

1. [Colores](#colores)
2. [Tipografías](#tipografías)
3. [Espaciados](#espaciados)
4. [Border Radius](#border-radius)
5. [Componentes](#componentes)
6. [Sombras](#sombras)
7. [Transiciones](#transiciones)
8. [Clases Utilitarias](#clases-utilitarias)
9. [Uso en HTML](#uso-en-html)

---

## 🎨 Colores

### Colores Principales

```css
--color-primary: #d99c45; /* Dorado/Naranja principal */
--color-primary-dark: #935719; /* Marrón oscuro */
--color-primary-darker: #6b3410; /* Marrón más oscuro */
--color-primary-darkest: #4a2208; /* Marrón muy oscuro */
```

**Uso:**

- `--color-primary`: Botones principales, headers, footers
- `--color-primary-dark`: Hover states, secciones destacadas
- `--color-primary-darker`: Botones de cancelar, elementos secundarios
- `--color-primary-darkest`: Hover de botones secundarios

### Colores de Texto

```css
--color-text-primary: #000000; /* Texto principal */
--color-text-secondary: #6b6b6b; /* Texto secundario */
--color-text-tertiary: #999999; /* Placeholders */
--color-text-light: #333333; /* Texto claro */
--color-text-movie: #1e0e62; /* Títulos de películas */
```

### Colores de Fondo

```css
--color-bg-primary: #ffffff; /* Fondo principal */
--color-bg-secondary: #f5f5f5; /* Fondo secundario */
--color-bg-tertiary: #e0e0e0; /* Fondo terciario */
--color-bg-gray: #d9d9d9; /* Gris para elementos */
```

### Colores de Acento

```css
--color-star: #ffd700; /* Dorado para estrellas */
--color-youtube: #ff0000; /* Rojo de YouTube */
```

---

## 📝 Tipografías

### Familias de Fuentes

```css
--font-primary: "Poppins", sans-serif; /* Fuente principal */
--font-title: "Prociono", serif; /* Títulos del sitio */
--font-search: "Montserrat", sans-serif; /* Buscador */
--font-movie: "DM Sans", sans-serif; /* Info de películas */
```

### Tamaños de Fuente

```css
--font-size-xs: 14px; /* Extra pequeño */
--font-size-sm: 16px; /* Pequeño */
--font-size-md: 18px; /* Mediano */
--font-size-lg: 20px; /* Grande */
--font-size-xl: 24px; /* Extra grande */
--font-size-2xl: 28px; /* 2X grande */
--font-size-3xl: 36px; /* 3X grande */
--font-size-4xl: 48px; /* 4X grande */
--font-size-5xl: 56px; /* 5X grande */
--font-size-6xl: 64px; /* 6X grande */
--font-size-huge: 128px; /* Enorme (sliders) */
```

### Pesos de Fuente

```css
--font-weight-normal: 400; /* Normal */
--font-weight-medium: 500; /* Mediano */
--font-weight-semibold: 600; /* Semi-negrita */
--font-weight-bold: 700; /* Negrita */
```

---

## 📏 Espaciados

```css
--spacing-xs: 8px; /* Extra pequeño */
--spacing-sm: 12px; /* Pequeño */
--spacing-md: 20px; /* Mediano */
--spacing-lg: 30px; /* Grande */
--spacing-xl: 40px; /* Extra grande */
--spacing-2xl: 60px; /* 2X grande */
--spacing-3xl: 80px; /* 3X grande */
```

**Uso:**

- Padding interno de componentes
- Márgenes entre elementos
- Gaps en flex/grid

---

## 🔲 Border Radius

```css
--radius-sm: 5px; /* Pequeño */
--radius-md: 8px; /* Mediano */
--radius-lg: 12px; /* Grande */
--radius-xl: 14px; /* Extra grande */
--radius-2xl: 16px; /* 2X grande */
--radius-round: 25px; /* Redondeado */
--radius-pill: 100px; /* Píldora (botones) */
--radius-circle: 50%; /* Círculo (avatares) */
```

---

## 🧩 Componentes

### Tamaños de Header y Footer

```css
--header-height: 180px;
--footer-height: 165px;
--search-bar-width: 571px;
--search-bar-height: 50px;
```

### Anchos Máximos de Contenedores

```css
--container-sm: 1100px; /* Pequeño */
--container-md: 1400px; /* Mediano */
--container-lg: 1440px; /* Grande */
--container-xl: 1575px; /* Extra grande */
```

### Tamaños de Avatares

```css
--avatar-xs: 41px; /* Extra pequeño */
--avatar-sm: 44px; /* Pequeño */
--avatar-md: 67px; /* Mediano (header) */
--avatar-lg: 287px; /* Grande (perfil) */
```

### Tamaños de Posters

```css
--poster-sm-width: 108px;
--poster-sm-height: 143px;
--poster-md-width: 256px;
--poster-md-height: 380px;
--poster-lg-width: 362px;
--poster-lg-height: 537px;
```

---

## 🌑 Sombras

```css
--shadow-sm: 0 2px 8px rgba(0, 0, 0, 0.1); /* Pequeña */
--shadow-md: 0 4px 12px rgba(0, 0, 0, 0.1); /* Mediana */
--shadow-lg: 0 8px 24px rgba(0, 0, 0, 0.15); /* Grande */
```

**Uso:**

- Cards de películas
- Modales
- Elementos elevados

---

## ⚡ Transiciones

```css
--transition-fast: 0.2s ease; /* Rápida */
--transition-normal: 0.3s ease; /* Normal */
--transition-slow: 0.5s ease; /* Lenta */
```

**Uso en CSS:**

```css
.button {
  transition: background-color var(--transition-normal);
}
```

---

## 🛠️ Clases Utilitarias

### Display

```html
<div class="d-flex">Flex container</div>
<div class="d-grid">Grid container</div>
<div class="d-block">Block element</div>
<div class="d-none">Hidden</div>
```

### Flex

```html
<div class="d-flex justify-center align-center">
  Centrado horizontal y vertical
</div>

<div class="d-flex justify-between">Espacio entre elementos</div>

<div class="d-flex flex-column gap-md">Columna con gap mediano</div>
```

### Texto

```html
<p class="text-center">Texto centrado</p>
<p class="text-primary">Texto color primario</p>
<p class="text-secondary">Texto color secundario</p>
```

### Colores de Fondo

```html
<div class="bg-primary">Fondo primario</div>
<div class="bg-white">Fondo blanco</div>
<div class="bg-gray">Fondo gris</div>
```

### Border Radius

```html
<div class="rounded">Radio mediano</div>
<div class="rounded-lg">Radio grande</div>
<div class="rounded-full">Círculo</div>
```

### Sombras

```html
<div class="shadow-sm">Sombra pequeña</div>
<div class="shadow-md">Sombra mediana</div>
```

### Otros

```html
<div class="w-full">Ancho completo</div>
<div class="h-full">Alto completo</div>
<div class="cursor-pointer">Cursor pointer</div>
<div class="overflow-hidden">Overflow oculto</div>
<div class="transition">Transición suave</div>
```

---

## 💻 Uso en HTML

### Ejemplo 1: Botón con Variables

```css
.btn-custom {
  background-color: var(--color-primary);
  color: var(--color-text-primary);
  padding: var(--spacing-md) var(--spacing-xl);
  border-radius: var(--radius-md);
  font-size: var(--font-size-md);
  transition: background-color var(--transition-normal);
}

.btn-custom:hover {
  background-color: var(--color-primary-dark);
  color: var(--color-white);
}
```

### Ejemplo 2: Card con Variables

```css
.movie-card {
  background-color: var(--color-bg-primary);
  border-radius: var(--radius-lg);
  padding: var(--spacing-xl);
  box-shadow: var(--shadow-md);
  max-width: var(--container-sm);
}
```

### Ejemplo 3: Usando Clases Utilitarias

```html
<div class="d-flex justify-between align-center gap-lg">
  <h2 class="text-primary">Título</h2>
  <button class="bg-primary rounded cursor-pointer">Botón</button>
</div>
```

---

## 🎯 Beneficios del Sistema

### 1. **Mantenibilidad**

- Cambiar un color en un solo lugar actualiza todo el sitio
- Fácil de entender y modificar

### 2. **Consistencia**

- Todos los componentes usan los mismos valores
- Diseño coherente en todo el proyecto

### 3. **Escalabilidad**

- Agregar nuevos componentes es más rápido
- Reutilización de valores estandarizados

### 4. **Temas**

- Fácil implementar modo oscuro
- Cambiar tema completo modificando `:root`

### 5. **Documentación**

- Las variables son auto-documentadas
- Nombres descriptivos facilitan el desarrollo

---

## 🔄 Cómo Cambiar el Tema

Para cambiar el tema del sitio, solo necesitas modificar las variables en `framework.css`:

```css
:root {
  /* Cambiar color primario de dorado a azul */
  --color-primary: #2563eb;
  --color-primary-dark: #1e40af;
  --color-primary-darker: #1e3a8a;
}
```

¡Y automáticamente todo el sitio se actualizará! 🎉

---

## 📚 Referencias

- [MDN - CSS Custom Properties](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties)
- [CSS Variables Guide](https://css-tricks.com/guides/css-custom-properties/)

---

**Desarrollado por:** 2025B - Aplicaciones Web - Grupo 2  
**Última actualización:** 2025
