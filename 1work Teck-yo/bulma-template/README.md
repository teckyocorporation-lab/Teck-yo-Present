# Plantilla Bulma CSS

Plantilla de tienda online utilizando Bulma CSS con diseño moderno y componentes predefinidos.

## 🚀 Características

- **Framework**: Bulma 0.9.4
- **Diseño**: Moderno y limpio
- **Responsive**: Mobile-first approach
- **Iconos**: Font Awesome 6.0
- **JavaScript**: Vanilla JS para interactividad

## 📁 Archivos

- `index.html` - Página principal con toda la funcionalidad

## 🎨 Componentes Incluidos

### Navbar
- Logo de la tienda
- Navegación responsive
- Botones de acción
- Burger menu para móviles

### Hero Section
- Sección hero con gradiente
- Título y subtítulo
- Botón de llamada a la acción
- Layout en columnas

### Productos
- Grid de tarjetas
- Hover effects personalizados
- Precios y botones
- Sistema de columnas

### Características
- Iconos con gradientes
- Descripción de beneficios
- Layout en 3 columnas

### Newsletter
- Sección de suscripción
- Input group
- Botón de acción

### Footer
- Grid de enlaces
- Información de contacto
- Separador y copyright

## 🛠️ Uso

1. Abre `index.html` en tu navegador
2. Personaliza los textos, colores e imágenes
3. Modifica las clases de Bulma según necesites

## 🎯 Personalización

### Cambiar Colores
```html
<!-- Cambiar color primario -->
class="is-primary" → class="is-success"
class="has-text-primary" → class="has-text-success"
```

### Modificar Grid
```html
<!-- Cambiar columnas -->
is-3 → is-4
is-6 → is-8
```

### Ajustar Espaciado
```html
<!-- Cambiar padding/margin -->
py-5 → py-4
mb-6 → mb-4
```

## 📱 Sistema de Grid Bulma

### Breakpoints
- `mobile` - < 768px
- `tablet` - ≥ 768px
- `desktop` - ≥ 1024px
- `widescreen` - ≥ 1216px
- `fullhd` - ≥ 1408px

### Clases de Columnas
- `is-12` - 12 columnas (100%)
- `is-6` - 6 columnas (50%)
- `is-4` - 4 columnas (33.33%)
- `is-3` - 3 columnas (25%)

## 🔧 Componentes Útiles

### Cards
```html
<div class="card">
  <div class="card-content">
    <h5 class="title is-5">Título</h5>
    <p class="subtitle is-6">Subtítulo</p>
  </div>
</div>
```

### Buttons
```html
<button class="button is-primary">Primario</button>
<button class="button is-outlined">Outline</button>
```

### Forms
```html
<div class="field has-addons">
  <div class="control is-expanded">
    <input class="input" type="text">
  </div>
  <div class="control">
    <button class="button is-primary">Buscar</button>
  </div>
</div>
```

### Layout
```html
<div class="columns">
  <div class="column is-6">Columna 1</div>
  <div class="column is-6">Columna 2</div>
</div>
```

## 🎨 Clases de Color

### Backgrounds
- `has-background-primary` - Fondo primario
- `has-background-light` - Fondo claro
- `has-background-dark` - Fondo oscuro

### Text
- `has-text-primary` - Texto primario
- `has-text-grey` - Texto gris
- `has-text-white` - Texto blanco

### Buttons
- `is-primary` - Botón primario
- `is-outlined` - Botón outline
- `is-large` - Botón grande

## 🔧 Utilidades

### Display
- `is-hidden` - Oculto
- `is-block` - Display block
- `is-flex` - Display flex

### Spacing
- `p-5` - Padding 5
- `m-3` - Margin 3
- `px-4` - Padding horizontal 4

### Typography
- `title is-1` - Título grande
- `subtitle is-4` - Subtítulo
- `has-text-centered` - Texto centrado

## 📱 Responsive Utilities

### Visibility
- `is-hidden-mobile` - Oculto en móvil
- `is-hidden-tablet` - Oculto en tablet
- `is-hidden-desktop` - Oculto en desktop

### Sizing
- `is-12-mobile` - 12 columnas en móvil
- `is-6-tablet` - 6 columnas en tablet
- `is-4-desktop` - 4 columnas en desktop

## 🎨 Efectos Personalizados

### Hover Effects
```css
.card-hover:hover {
  transform: translateY(-5px);
}
```

### Gradientes
```css
.hero-gradient {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
```

### Iconos
```css
.feature-icon {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
```

## 📄 Documentación

- [Bulma Docs](https://bulma.io/documentation/)
- [Bulma Components](https://bulma.io/documentation/components/)
- [Bulma Utilities](https://bulma.io/documentation/utilities/)
