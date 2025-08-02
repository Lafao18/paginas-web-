# Mi Vecino - Restaurante 🍽️

Una página web moderna y responsiva para el restaurante "Mi Vecino" construida con HTML5, CSS3 y JavaScript vanilla.

## ✨ Características

### 🎨 Diseño Profesional
- **Diseño responsivo** que se adapta perfectamente a cualquier dispositivo (móvil, tablet, desktop)
- **Navegación fluida** entre secciones con efectos de scroll suave
- **Animaciones elegantes** que mejoran la experiencia del usuario
- **Paleta de colores cálida** que refleja la esencia del restaurante

### 📱 Funcionalidades Interactivas
- **Menú de navegación fijo** que cambia de apariencia al hacer scroll
- **Menú móvil hamburguesa** para dispositivos pequeños
- **Sistema de categorías** para el menú de comidas (Entradas, Principales, Postres, Bebidas)
- **Formulario de contacto** funcional con validación
- **Botones flotantes** de WhatsApp y volver arriba
- **Redes sociales** integradas en el footer

### 🔧 Secciones Incluidas
1. **Inicio** - Hero section con llamadas a la acción
2. **Sobre Nosotros** - Historia del restaurante con estadísticas animadas
3. **Nuestras Delicias** - Menú interactivo por categorías
4. **¿Por Qué Elegirnos?** - Características destacadas con iconos
5. **Galería** - Showcase visual del restaurante
6. **Ubicación** - Información de contacto y mapa
7. **Contacto** - Formulario funcional y métodos de contacto

## 🚀 Cómo usar

### Opción 1: Servidor Local Simple
```bash
# Si tienes Python 3 instalado
python -m http.server 8000

# Si tienes Python 2 instalado
python -m SimpleHTTPServer 8000

# Si tienes Node.js instalado
npx http-server

# Si tienes PHP instalado
php -S localhost:8000
```

Luego abre tu navegador en `http://localhost:8000`

### Opción 2: Abrir directamente
Simplemente abre el archivo `index.html` en tu navegador web favorito.

## 📁 Estructura del Proyecto

```
mi-vecino-restaurant/
│
├── index.html          # Página principal
├── styles.css          # Estilos CSS
├── script.js           # Funcionalidad JavaScript
└── README.md           # Este archivo
```

## 🎯 Características Técnicas

### Responsive Design
- **Mobile First**: Diseñado primero para móviles y luego escalado
- **Breakpoints**: 
  - Mobile: < 480px
  - Tablet: < 768px
  - Desktop: > 768px

### Optimizaciones
- **Lazy Loading**: Carga diferida de imágenes pesadas
- **Debounced Scroll**: Optimización de eventos de scroll
- **CSS Animations**: Animaciones suaves con CSS
- **Performance**: Código optimizado para carga rápida

### Accesibilidad
- **Navegación por teclado**: Soporte completo
- **Focus indicators**: Indicadores visuales claros
- **Semantic HTML**: Estructura semántica correcta
- **Contrast ratios**: Colores accesibles

## 🛠️ Personalización

### Cambiar Colores
Modifica las variables CSS en `styles.css`:
```css
/* Colores principales */
#d4af37 - Dorado principal
#f4d03f - Dorado claro
#2c1810 - Marrón oscuro
#4a2c1a - Marrón medio
```

### Modificar Contenido
- **Textos**: Edita directamente en `index.html`
- **Menú**: Agrega/modifica elementos en la sección `#menu`
- **Información de contacto**: Actualiza en la sección `#contacto`

### Agregar Redes Sociales
En el footer, modifica los enlaces:
```html
<a href="TU_ENLACE_DE_FACEBOOK" class="social-link">
    <i class="fab fa-facebook"></i>
</a>
```

## 📞 Configuración de WhatsApp

El botón flotante de WhatsApp está configurado con un número de ejemplo. Para cambiarlo:

1. Abre `index.html`
2. Busca la línea:
```html
<a href="https://wa.me/525559876543" class="whatsapp-float" target="_blank">
```
3. Reemplaza `525559876543` con tu número de WhatsApp (incluye código de país)

## 🎨 Fuentes e Iconos

- **Fuentes**: Google Fonts (Playfair Display + Open Sans)
- **Iconos**: Font Awesome 6.0
- **CDN**: Enlaces incluidos en el HTML

## 📧 Formulario de Contacto

El formulario incluye:
- ✅ Validación en tiempo real
- ✅ Mensajes de error/éxito
- ✅ Campos requeridos marcados
- ✅ Validación de email
- ✅ Limpieza automática después del envío

**Nota**: Actualmente simula el envío. Para implementar envío real, conecta con un backend o servicio como Formspree, Netlify Forms, etc.

## 🌐 Compatibilidad

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 11+
- ✅ Edge 16+
- ✅ iOS Safari 11+
- ✅ Android Chrome 60+

## 🔄 Actualizaciones Futuras

Algunas ideas para mejoras:
- Sistema de reservas online
- Integración con mapas reales (Google Maps)
- Galería de imágenes con lightbox
- Blog/noticias del restaurante
- Sistema de comentarios/reseñas
- Integración con redes sociales en tiempo real

## 📝 Licencia

Este proyecto es de uso libre. Puedes modificarlo y adaptarlo según tus necesidades.

---

**¡Disfruta de tu nueva página web para Mi Vecino! 🎉**

Para cualquier pregunta o mejora, no dudes en contactar.