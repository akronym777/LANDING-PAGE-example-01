# Tu Negocio Digital - Landing Page Base Editable

Una plantilla profesional y completamente editable para crear landing pages, blogs, portafolios y tiendas e-commerce usando HTML5 y CSS3.

## 📋 Características

✅ **Diseño Responsivo** - Se adapta a todos los dispositivos (móvil, tablet, desktop)  
✅ **HTML5 Semántico** - Código limpio y bien estructurado  
✅ **CSS3 Moderno** - Efectos, animaciones y gradientes  
✅ **Fácil de Editar** - Comentarios claros en el código  
✅ **Velocidad Optimizada** - Carga rápida sin dependencias externas  
✅ **SEO Friendly** - Meta tags y estructura correcta  
✅ **GitHub Pages Ready** - Listo para desplegar gratis  

## 🚀 Estructura del Proyecto

```
LANDING-PAGE-example-01/
├── index.html          # Archivo principal HTML
├── styles.css          # Estilos CSS
├── README.md           # Este archivo
└── assets/            # (Opcional) Carpeta para imágenes, fuentes, etc.
    ├── images/
    └── fonts/
```

## 📝 Cómo Usar

### 1. Clonar o Descargar
```bash
git clone https://github.com/akronym777/LANDING-PAGE-example-01.git
cd LANDING-PAGE-example-01
```

### 2. Personalizar el Contenido

Abre `index.html` y edita:

- **Título del Sitio**: Busca `<title>` y cambia el texto
- **Logo/Marca**: Edita el `.logo` en la navegación
- **Textos**: Reemplaza los títulos y descripciones
- **Servicios**: Modifica los 6 servicios en la sección de servicios
- **Precios**: Actualiza los planes y precios
- **Contacto**: Usa tu email en el formulario

### 3. Personalizar Colores

En `styles.css`, busca la sección `:root` y modifica:

```css
:root {
    --color-primary: #007bff;        /* Color principal (azul) */
    --color-secondary: #6c757d;      /* Color secundario (gris) */
    --color-success: #28a745;        /* Verde */
    --color-danger: #dc3545;         /* Rojo */
    /* ... otros colores */
}
```

### 4. Agregar Imágenes

Crea una carpeta `assets/images/` y agrega tus fotos. Luego inserta en HTML:

```html
<img src="assets/images/tu-imagen.jpg" alt="Descripción">
```

### 5. Desplegar en GitHub Pages

1. Asegúrate de que el repositorio sea **público**
2. Ve a **Settings** → **Pages**
3. Selecciona **Main Branch** como fuente
4. Tu sitio estará en: `https://akronym777.github.io/LANDING-PAGE-example-01`

## 🎨 Secciones Incluidas

### 📍 Navegación
- Menú sticky con enlaces internos
- Logo/Marca del negocio

### 🏠 Hero Section
- Banner principal con efecto degradado
- Botones de llamada a acción
- Animaciones de entrada

### 🛍️ Servicios
- 6 tarjetas con servicios ofrecidos
- Iconos emoji personalizables
- Efectos hover

### ⭐ Características
- Ventajas de tu negocio
- Diseño tipo "feature boxes"
- Borde izquierdo decorativo

### 💰 Precios
- 3 planes de precios
- Plan destacado más grande
- Listas de características

### 📧 Contacto
- Formulario con validación básica
- Campos: nombre, email, mensaje
- Estilos modernos

### 🔗 Footer
- Información de copyright
- Enlaces a redes sociales

## 🔧 Personalización Avanzada

### Cambiar Tipografía

En `styles.css`, modifica:
```css
--font-family: 'Tu Fuente', sans-serif;
```

### Agregar Google Fonts

En `index.html`, antes de `<link rel="stylesheet" href="styles.css">`:
```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
```

### Agregar Animaciones Personalizadas

En `styles.css`, crea nuevas keyframes:
```css
@keyframes miAnimacion {
    from { opacity: 0; }
    to { opacity: 1; }
}

.elemento {
    animation: miAnimacion 0.5s ease;
}
```

## 📱 Breakpoints Responsivos

El sitio está optimizado para:
- **Desktop**: 1200px+
- **Tablet**: 768px - 1199px
- **Móvil**: Menos de 768px
- **Móvil Pequeño**: Menos de 480px

## 🛒 Para E-commerce

Si quieres agregar funcionalidad de tienda:

1. **Productos**: Crea una sección con grid de productos
2. **Carrito**: Integra con Stripe, PayPal o WooCommerce
3. **Backend**: Usa GitHub + servicios como Netlify Functions

Ejemplo básico de producto:
```html
<div class="producto">
    <img src="assets/images/producto.jpg" alt="Producto">
    <h3>Nombre del Producto</h3>
    <p class="precio">$99</p>
    <button class="btn btn-primary">Agregar al Carrito</button>
</div>
```

## 📚 Recursos Útiles

- [MDN Web Docs](https://developer.mozilla.org)
- [CSS-Tricks](https://css-tricks.com)
- [Unsplash](https://unsplash.com) - Imágenes gratis
- [FontAwesome](https://fontawesome.com) - Iconos
- [Google Fonts](https://fonts.google.com) - Tipografías

## ❓ Preguntas Frecuentes

**¿Cómo cambio el dominio?**
- Compra un dominio y configúralo en Settings → Pages → Custom Domain

**¿Puedo agregar más secciones?**
- Sí, copia la estructura de una sección existente y personaliza

**¿Cómo agrego JavaScript?**
- Crea un archivo `script.js` e inclúyelo en el `<head>` con `<script src="script.js"></script>`

**¿Es compatible con SEO?**
- Sí, tiene estructura HTML5 semántica. Agrega meta tags en `<head>`

## 📄 Licencia

Este proyecto es de código abierto y está disponible para uso personal y comercial.

## 👨‍💻 Autor

Creado para ayudarte a construir tu presencia digital profesional.

---

¡Empieza a personalizar ahora y sube tu sitio web! 🚀

**Necesitas ayuda?** Revisa los comentarios en el código HTML y CSS para entender cada sección.
