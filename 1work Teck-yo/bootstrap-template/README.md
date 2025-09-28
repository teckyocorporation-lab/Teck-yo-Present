# Plantilla Bootstrap 5

Plantilla de tienda online utilizando Bootstrap 5 con componentes predefinidos y sistema de grid.

## 🚀 Características

- **Framework**: Bootstrap 5.3.0
- **Diseño**: Componentes predefinidos
- **Responsive**: Sistema de grid responsive
- **Iconos**: Font Awesome 6.0
- **JavaScript**: Bootstrap JS incluido

## 📁 Archivos

- `index.html` - Página principal con toda la funcionalidad

## 🎨 Componentes Incluidos

### Navbar
- Logo de la tienda
- Navegación colapsable
- Botones de acción
- Responsive con toggler

### Hero Section
- Jumbotron con gradiente
- Título y subtítulo
- Botón de llamada a la acción
- Imagen de fondo

### Productos
- Grid de tarjetas
- Hover effects personalizados
- Precios y botones
- Layout responsive

### Características
- Iconos en círculos
- Descripción de beneficios
- Sistema de columnas

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
3. Modifica las clases de Bootstrap según necesites

## 🎯 Personalización

### Cambiar Colores
```html
<!-- Cambiar color primario -->
class="btn-primary" → class="btn-success"
class="text-primary" → class="text-success"
```

### Modificar Grid
```html
<!-- Cambiar columnas -->
col-lg-3 → col-lg-4
col-md-6 → col-md-4
```

### Ajustar Espaciado
```html
<!-- Cambiar padding/margin -->
py-5 → py-4
mb-5 → mb-4
```

## 📱 Sistema de Grid Bootstrap

### Breakpoints
- `xs` - < 576px
- `sm` - ≥ 576px
- `md` - ≥ 768px
- `lg` - ≥ 992px
- `xl` - ≥ 1200px
- `xxl` - ≥ 1400px

### Clases de Columnas
- `col-12` - 12 columnas (100%)
- `col-md-6` - 6 columnas en md+
- `col-lg-3` - 3 columnas en lg+
- `col-auto` - Ancho automático

## 🔧 Componentes Útiles

### Cards
```html
<div class="card">
  <div class="card-body">
    <h5 class="card-title">Título</h5>
    <p class="card-text">Contenido</p>
  </div>
</div>
```

### Buttons
```html
<button class="btn btn-primary">Primario</button>
<button class="btn btn-outline-secondary">Secundario</button>
```

### Forms
```html
<div class="input-group">
  <input type="text" class="form-control">
  <button class="btn btn-primary">Buscar</button>
</div>
```

### Utilities
- `d-flex` - Display flex
- `justify-content-center` - Centrado horizontal
- `align-items-center` - Centrado vertical
- `text-center` - Texto centrado

## 🎨 Clases de Color

### Backgrounds
- `bg-primary` - Fondo primario
- `bg-light` - Fondo claro
- `bg-dark` - Fondo oscuro

### Text
- `text-primary` - Texto primario
- `text-muted` - Texto atenuado
- `text-white` - Texto blanco

### Buttons
- `btn-primary` - Botón primario
- `btn-outline-primary` - Botón outline
- `btn-lg` - Botón grande

## 📄 Documentación

- [Bootstrap 5 Docs](https://getbootstrap.com/docs/5.3/)
- [Bootstrap Components](https://getbootstrap.com/docs/5.3/components/)
- [Bootstrap Utilities](https://getbootstrap.com/docs/5.3/utilities/)
