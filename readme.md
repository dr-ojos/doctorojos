# Dr. José Peña - Sitio Web Oftalmología

Sitio web profesional independiente para servicios oftalmológicos.

## 📁 Estructura de Archivos

```
proyecto/
├── index.html          # Página principal
├── styles.css          # Estilos CSS
└── README.md           # Este archivo
```

## 🚀 Instrucciones de Uso

### Opción 1: Ver localmente
1. Descarga ambos archivos (`index.html` y `styles.css`)
2. Colócalos en la misma carpeta
3. Abre `index.html` con tu navegador

### Opción 2: Publicar en línea (GRATIS)

#### GitHub Pages (Recomendado)
1. Crea una cuenta en [GitHub](https://github.com)
2. Crea un nuevo repositorio llamado `tu-usuario.github.io`
3. Sube los archivos
4. Tu sitio estará en: `https://tu-usuario.github.io`

#### Netlify
1. Ve a [Netlify](https://www.netlify.com)
2. Arrastra la carpeta con tus archivos
3. ¡Listo! Tendrás una URL automática

#### Vercel
1. Ve a [Vercel](https://vercel.com)
2. Importa tu proyecto desde GitHub
3. Deploy automático

## ✏️ Personalización

### Cambiar imágenes
Reemplaza los elementos con clase `.hero-image-placeholder` y `.about-image` con etiquetas `<img>`:

```html
<!-- En lugar de -->
<div class="hero-image-placeholder">Tu foto aquí</div>

<!-- Usa -->
<img src="tu-foto.jpg" alt="Dr. José Peña" style="width: 400px; height: 480px; border-radius: 20px; object-fit: cover;">
```

### Cambiar colores
En `styles.css`, busca estos valores y modifícalos:
- `#667eea` - Color principal morado/azul
- `#764ba2` - Color secundario morado
- `#2d3748` - Color de texto oscuro

### Agregar formulario de contacto
Puedes integrar servicios como:
- [Formspree](https://formspree.io) - Gratis
- [EmailJS](https://www.emailjs.com) - Gratis
- [Netlify Forms](https://www.netlify.com/products/forms/) - Gratis con Netlify

### Conectar sistema de reservas
Actualiza el enlace del botón en `index.html`:
```html
<a href="TU-LINK-DE-RESERVAS" class="btn">Reserva de horas</a>
```

## 📱 Características

- ✅ 100% Responsive (móvil, tablet, desktop)
- ✅ Sin dependencias externas
- ✅ Optimizado para SEO
- ✅ Carga rápida
- ✅ Animaciones suaves
- ✅ Fácil de mantener

## 🔧 Soporte

Para modificaciones adicionales o dudas, puedes:
- Editar directamente los archivos HTML/CSS
- Contratar un desarrollador freelance
- Usar herramientas de IA para hacer cambios

## 📄 Licencia

Código libre para uso personal y comercial.