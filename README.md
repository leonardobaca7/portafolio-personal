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

## 🚀 Deployment con GitHub Student Pack

Ya que tienes el **GitHub Student Pack**, puedes desplegar este portafolio gratis en varias plataformas:

### Opción 1: GitHub Pages (Recomendado)

1. Crea un repositorio en GitHub llamado `tu-usuario.github.io`
2. Sube estos archivos al repositorio
3. Tu sitio estará disponible en: `https://tu-usuario.github.io`

```bash
git init
git add .
git commit -m "Initial commit - Portfolio"
git branch -M main
git remote add origin https://github.com/tu-usuario/tu-usuario.github.io.git
git push -u origin main
```

### Opción 2: Namecheap Domain (Incluido en Student Pack)

Con el Student Pack obtienes:
- **1 año de dominio .me GRATIS** en Namecheap
- **1 año de SSL/TLS GRATIS**

**Pasos:**
1. Ve a [Namecheap Education](https://nc.me/) y reclama tu dominio gratuito
2. Registra un dominio como: `leonardo.me` o `leonardo-dev.me`
3. Conecta tu dominio a GitHub Pages:
   - En tu repositorio: Settings → Pages → Custom domain
   - Agrega tu dominio: `www.leonardo.me`
   - Crea un archivo `CNAME` en la raíz con tu dominio

### Opción 3: Vercel (Deploy instantáneo)

```bash
npm i -g vercel
vercel
```

### Opción 4: Netlify

1. Ve a [Netlify](https://netlify.com)
2. Arrastra la carpeta del proyecto
3. ¡Listo! Tu sitio estará en línea

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

- [ ] Integrar formulario de contacto funcional
- [ ] Agregar animaciones GSAP avanzadas
- [ ] Implementar blog personal
- [ ] Agregar modo Light Theme completo
- [ ] Integrar Google Analytics
- [ ] Agregar sección de certificaciones
- [ ] Sistema de i18n (ES/EN)

## 📱 Vista Previa

Para ver el sitio localmente:

1. Abre `index.html` en tu navegador
2. O usa Live Server en VS Code

## 📧 Contacto

- LinkedIn: [Tu perfil]
- GitHub: [Tu usuario]
- Email: tu@email.com

---

**Desarrollado con 💚 por Leonardo - 2025**

*¡No olvides darle ⭐ al repositorio si te gustó!*
