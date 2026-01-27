# 🚀 Portafolio Personal - Leonardo

Portafolio profesional moderno y responsivo con diseño Dark Mode elegante estilo Matrix/Cyberpunk.

## ✨ Características

- **Single Page Application** con scroll suave
- **Diseño Responsivo** (Mobile-first)
- **Dark Mode** con toggle opcional
- **Efecto Typewriter** animado
- **Animaciones** suaves en scroll
- **Secciones principales:**
  - Hero con llamado a la acción
  - Sobre Mí
  - Skills con barras de progreso animadas
  - Portafolio con cards interactivas
  - Contacto
  - Footer con redes sociales

## 🎨 Paleta de Colores

```css
Fondo Principal: #0a192f
Fondo Secundario: #112240
Texto Claro: #ccd6f6
Texto Secundario: #8892b0
Acento Cian: #64ffda
```

## 🛠️ Tecnologías

- HTML5
- CSS3 (Flexbox & Grid)
- JavaScript Vanilla
- Font Awesome Icons
- Google Fonts (Poppins)

## 📦 Estructura de Archivos

```
Portfolio-Personal/
├── index.html
├── styles.css
└── README.md
```

## 🚀 Cómo subir tu portafolio a GitHub Pages

### Paso 1: Crear repositorio en GitHub

1. Ve a [GitHub](https://github.com/new)
2. Nombre del repositorio: `portfolio` (o el que prefieras)
3. Déjalo público
4. NO marques "Initialize with README"
5. Click en "Create repository"

### Paso 2: Conectar tu código local con GitHub

Reemplaza `TU-USUARIO` con tu usuario de GitHub:

```bash
cd Portfolio-Personal
git branch -M main
git remote add origin https://github.com/TU-USUARIO/portfolio.git
git push -u origin main
```

### Paso 3: Activar GitHub Pages

1. Ve a tu repositorio en GitHub
2. Click en **Settings** (⚙️)
3. En el menú lateral izquierdo → **Pages**
4. En **Source** selecciona: **Deploy from a branch**
5. En **Branch** selecciona: **main** → **/ (root)**
6. Click en **Save**
7. Espera 1-2 minutos

**🎉 Tu portafolio estará disponible en:**
```
https://TU-USUARIO.github.io/portfolio
```

### (Opcional) Conectar dominio personalizado

Si tienes el GitHub Student Pack, puedes obtener un dominio `.me` GRATIS por 1 año:

1. Ve a [Namecheap Education](https://nc.me/)
2. Registra: `leonardo.me` (o el nombre que prefieras)
3. En tu repo GitHub → Settings → Pages → Custom domain
4. Ingresa tu dominio y guarda
5. En Namecheap, configura los DNS apuntando a GitHub Pages

## 📝 Personalización

### Cambiar información personal:

1. **Hero Section** (líneas 47-50): Cambia tu nombre y apellido
2. **Sobre Mí** (líneas 124-141): Actualiza tu biografía
3. **Proyectos** (líneas 265-350): Reemplaza con tus proyectos reales
4. **Contacto** (líneas 392-408): Actualiza tus links y email
5. **Footer** (líneas 426): Agrega tu apellido

### Cambiar foto de perfil:

Reemplaza los placeholders:
- Línea 69: `src="https://via.placeholder.com/400x400/..."`
- Línea 155: `src="https://via.placeholder.com/350x350/..."`

Con rutas a tus imágenes reales:
```html
<img src="img/profile.jpg" alt="Leonardo">
```

### Agregar más proyectos:

Duplica el bloque `.project-card` y personaliza:
```html
<div class="project-card">
    <div class="project-image">
        <img src="tu-imagen.jpg" alt="Proyecto">
        <!-- ... -->
    </div>
    <div class="project-content">
        <p class="project-type">Tu Tipo</p>
        <h3 class="project-title">Tu Proyecto</h3>
        <p class="project-description">Tu descripción</p>
        <ul class="project-tech">
            <li>Tech 1</li>
            <li>Tech 2</li>
        </ul>
    </div>
</div>
```

## 🎯 Próximas Mejoras

- [ ] Integrar formulario de contacto con EmailJS
- [ ] Agregar más proyectos reales
- [ ] Optimizar imágenes y performance
- [ ] Agregar animaciones GSAP
- [ ] SEO optimization

---

**⭐ Si te gustó este proyecto, dale una estrella en GitHub!**


