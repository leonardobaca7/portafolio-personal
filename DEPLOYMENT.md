# 🚀 Guía de Deployment - Portfolio Leonardo

## 📍 Estado Actual: FASE 1 - GitHub Pages

### ✅ Deployment Actual (Simple & Gratis)

**Stack:**
- HTML + CSS + JavaScript Vanilla
- GitHub Pages (Hosting gratuito)
- Dominio personalizado (.me de Namecheap)

**URL Actual:** `https://tu-usuario.github.io/portfolio`

---

## 🎯 FASE 1: Deploy con GitHub Pages (ACTUAL)

### Paso 1: Crear repositorio en GitHub

```bash
# Ya inicializado localmente, solo falta conectar a GitHub
git remote add origin https://github.com/TU-USUARIO/portfolio.git
git branch -M main
git push -u origin main
```

### Paso 2: Activar GitHub Pages

1. Ve a tu repositorio en GitHub
2. Settings → Pages
3. Source: **Deploy from branch**
4. Branch: **main** / folder: **/ (root)**
5. Save

**¡Tu sitio estará en:** `https://TU-USUARIO.github.io/portfolio`

### Paso 3: Conectar dominio personalizado (Namecheap)

**Reclamar dominio gratis (.me):**
1. Ve a [Namecheap Student Pack](https://nc.me/)
2. Registra: `leonardo.me` o `leonardo-dev.me`

**Configurar DNS:**
1. En Namecheap → Domain List → Manage → Advanced DNS
2. Agrega estos records:

```
Type    Host    Value                   TTL
A       @       185.199.108.153         Automatic
A       @       185.199.109.153         Automatic
A       @       185.199.110.153         Automatic
A       @       185.199.111.153         Automatic
CNAME   www     TU-USUARIO.github.io    Automatic
```

3. En GitHub → Settings → Pages → Custom domain: `leonardo.me`
4. Espera 10-20 minutos para propagación DNS
5. Activa "Enforce HTTPS"

---

## 🔄 FASE 2: Arquitectura Completa (FUTURO)

### Cuándo migrar:
- ✅ Cuando necesites formulario de contacto con BD
- ✅ Cuando quieras agregar blog/CMS
- ✅ Cuando necesites autenticación
- ✅ Cuando quieras aprender DevOps

### Stack planeado:

```
portfolio/
├── frontend/          # React + Vite
│   ├── src/
│   ├── public/
│   └── package.json
├── backend/           # Node.js + Express
│   ├── src/
│   │   ├── routes/
│   │   ├── controllers/
│   │   └── models/
│   ├── prisma/        # ORM
│   └── package.json
├── infrastructure/    # Docker + CI/CD
│   ├── docker/
│   │   ├── Dockerfile.frontend
│   │   └── Dockerfile.backend
│   ├── nginx/
│   └── docker-compose.yml
└── .github/
    └── workflows/
        └── deploy.yml
```

### Tecnologías a usar:

**Frontend:**
- ⚛️ React 18 + TypeScript
- ⚡ Vite (build tool)
- 🎨 Tailwind CSS
- 📊 React Query (data fetching)

**Backend:**
- 🟢 Node.js + Express
- 🔷 TypeScript
- 🗄️ PostgreSQL
- 🔺 Prisma ORM
- 🔐 JWT Authentication

**DevOps:**
- 🐳 Docker + Docker Compose
- 🌊 DigitalOcean Droplet ($200 crédito Student Pack)
- 🔄 GitHub Actions (CI/CD)
- 🌐 Nginx (reverse proxy)
- 🔒 Let's Encrypt (SSL)

### DigitalOcean Student Pack:
- **$200 en créditos** por 1 año
- Droplet recomendado: **$6/mes** (Basic)
- 1 vCPU, 1GB RAM, 25GB SSD
- Soporta ~1000 visitas/día

### Estimación de costos (con Student Pack):

| Servicio | Costo Mensual | Con Student Pack |
|----------|---------------|------------------|
| DigitalOcean Droplet | $6 | GRATIS (1 año) |
| Dominio .me | $0 | GRATIS (1 año) |
| SSL Certificate | $0 | GRATIS (Let's Encrypt) |
| **TOTAL** | **$6/mes** | **$0** durante 1 año |

Después del año: $6/mes + $10/año dominio = **$82/año** ($6.83/mes)

---

## 📋 Checklist de Migración (Para FASE 2)

### Pre-requisitos:
- [ ] Conocimientos de React
- [ ] Conocimientos de Node.js/Express
- [ ] Entender Docker básico
- [ ] Tener $200 crédito DigitalOcean activado

### Setup Backend:
- [ ] Crear carpeta `/backend`
- [ ] Instalar Express + TypeScript
- [ ] Configurar PostgreSQL
- [ ] Crear API de contacto
- [ ] Agregar validaciones (Zod)
- [ ] Implementar rate limiting

### Setup Frontend:
- [ ] Migrar HTML/CSS a React components
- [ ] Configurar Vite + TypeScript
- [ ] Integrar Tailwind CSS
- [ ] Conectar con backend API
- [ ] Agregar formulario funcional

### Setup Docker:
- [ ] Dockerfile para frontend
- [ ] Dockerfile para backend
- [ ] docker-compose.yml
- [ ] Nginx config para reverse proxy

### Setup CI/CD:
- [ ] GitHub Actions workflow
- [ ] Automated tests
- [ ] Deploy automático a DigitalOcean

### Deploy DigitalOcean:
- [ ] Crear Droplet Ubuntu
- [ ] Instalar Docker + Docker Compose
- [ ] Configurar Nginx
- [ ] Setup SSL con Let's Encrypt
- [ ] Configurar dominio DNS

---

## 🛠️ Comandos Útiles

### Git básico:
```bash
# Ver estado
git status

# Agregar cambios
git add .

# Commit
git commit -m "feat: add new feature"

# Push a GitHub
git push origin main
```

### Para cuando uses Docker (FASE 2):
```bash
# Build & run
docker-compose up --build

# Detener
docker-compose down

# Ver logs
docker-compose logs -f

# Rebuild solo backend
docker-compose up --build backend
```

---

## 📚 Recursos para aprender (FASE 2)

**Docker:**
- [Docker Tutorial - FreeCodeCamp](https://www.youtube.com/watch?v=fqMOX6JJhGo)
- [Docker Docs](https://docs.docker.com/get-started/)

**React + Node.js:**
- [Full Stack Course](https://www.youtube.com/watch?v=Oe421EPjeBE)
- [MERN Stack Tutorial](https://www.youtube.com/watch?v=7CqJlxBYj-M)

**DigitalOcean:**
- [Deploy Node.js App](https://www.digitalocean.com/community/tutorials/how-to-deploy-a-react-application-with-nginx-on-ubuntu-20-04)
- [Docker on Ubuntu](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-22-04)

---

## 🎯 Roadmap

### Q1 2026 (Ahora):
- ✅ Portfolio estático en GitHub Pages
- ✅ Dominio personalizado
- ✅ Contenido actualizado con proyectos

### Q2 2026 (Abr-Jun):
- 🔄 Migrar a React
- 🔄 Agregar backend con Express
- 🔄 Formulario de contacto funcional

### Q3 2026 (Jul-Sep):
- 🔄 Dockerizar aplicación
- 🔄 Deploy en DigitalOcean
- 🔄 CI/CD con GitHub Actions

### Q4 2026 (Oct-Dic):
- 🔄 Agregar blog/CMS
- 🔄 Sistema de autenticación
- 🔄 Analytics dashboard

---

## 📞 Soporte

**Creado por:** Leonardo Apellido  
**Fecha:** Enero 2026  
**Versión:** 1.0.0 (GitHub Pages)

---

**Nota:** Esta es tu base. Despliega AHORA y mejora después. ¡Un portafolio online vale más que un portafolio perfecto sin deploy! 🚀
