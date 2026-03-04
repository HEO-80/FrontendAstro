<div align="center">

# 🚀 FrontendAstro — Collaborative Web Development Project

<img src="https://img.shields.io/badge/Astro-FF5D01?style=for-the-badge&logo=astro&logoColor=white"/>
<img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"/>
<img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/GSAP-88CE02?style=for-the-badge&logo=greensock&logoColor=black"/>
<img src="https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white"/>

**🌍 [English](#-english-version) · 🇪🇸 [Español](#-versión-en-español)**

<br/>

**Proyecto grupal del curso oficial de Desarrollo Web Front End (IFCD55)**

*9 desarrolladores · 300 horas de formación · flujo real de trabajo con Git*

[![Live Demo](https://img.shields.io/badge/🌐_Ver_Demo_en_Vivo-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)](https://frontendastrodev.netlify.app/)

</div>

---

## 🇪🇸 Versión en Español

### 📝 Sobre el Proyecto

Este repositorio es el resultado del proyecto grupal del curso oficial **IFCD55 - Desarrollo Web Front End**, construido por **9 desarrolladores** trabajando en paralelo con un flujo de trabajo real: ramas, pull requests, resolución de conflictos y despliegue continuo.

El objetivo no era solo entregar una web — era **simular un entorno profesional real** desde el primer commit.

---

### ✨ Características

- ⚡ **Zero JS por defecto** — Astro envía solo el JavaScript estrictamente necesario al cliente
- 🎨 **UI consistente** — Tailwind CSS utility-first en todas las páginas
- 🎭 **Animaciones fluidas** — GSAP para secuencias de alto rendimiento
- 🔍 **Motor de búsqueda integrado** — navegación entre páginas de alumnos
- 📱 **Totalmente responsive** — diseñado para cualquier pantalla
- 🔄 **CI/CD real** — despliegue automático en Netlify desde `main`

---

### 🛠️ Tech Stack

| Tecnología | Rol en el proyecto |
|:---|:---|
| **Astro** | Framework base — SSG con arquitectura de islas |
| **Tailwind CSS** | Estilos utility-first — diseño consistente y responsive |
| **GSAP** | Animaciones de alto rendimiento en DOM |
| **TypeScript** | Tipado estático en componentes |
| **Git + GitHub** | Control de versiones para 9 contribuidores |
| **Netlify** | Hosting + despliegue continuo desde `main` |

---

### 📸 Demo

[![FrontendAstro Preview](https://frontendastrodev.netlify.app/)](https://frontendastrodev.netlify.app/)

> 🌐 **[frontendastrodev.netlify.app](https://frontendastrodev.netlify.app/)**

---

### 🔄 Flujo de Trabajo Colaborativo

El proyecto simuló un entorno de trabajo profesional real:
```
main
  └── development
        ├── virginia
        ├── feature/cursor-and-john-page
        ├── feature/alumno-3
        └── ... (una rama por alumno)
```

**Proceso:**
1. **Setup inicial** — enrutamiento base, navbar compartida y motor de búsqueda
2. **Desarrollo individual** — cada alumno trabajó en su propia rama y páginas
3. **Pull Requests** — revisión y merge hacia `development`
4. **Integración continua** — resolución de conflictos y merge final a `main`
5. **Deploy automático** — Netlify detecta cambios en `main` y despliega

---

### 🏗️ Estructura del Proyecto
```
FrontendAstro/
├── public/
│   └── favicon.svg
├── src/
│   ├── assets/             # Imágenes y recursos estáticos
│   ├── components/         # Componentes Astro reutilizables
│   ├── layouts/            # Layout base compartido
│   └── pages/              # Una página por alumno + index
├── astro.config.mjs        # Configuración Astro
├── tailwind.config.js      # Configuración Tailwind
└── package.json
```

---

### ⚙️ Instalación y Uso Local

**1. Clonar el repositorio**
```bash
git clone https://github.com/HEO-80/FrontendAstro.git
cd FrontendAstro
```

**2. Instalar dependencias**
```bash
npm install
```

**3. Servidor de desarrollo**
```bash
npm run dev
# http://localhost:4321
```

**4. Build de producción**
```bash
npm run build
npm run preview   # previsualizar antes de desplegar
```

---

### 👥 Contribuidores

Este proyecto fue posible gracias al esfuerzo de **9 desarrolladores**:

[![Contributors](https://contrib.rocks/image?repo=HEO-80/FrontendAstro)](https://github.com/HEO-80/FrontendAstro/graphs/contributors)

---

### 🧑‍💻 Profesor & Setup Inicial

**Héctor Oviedo** — Profesor del curso & Arquitecto del proyecto base

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hectorob/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/HEO-80)

---
---

## 🇬🇧 English Version

### 📝 About the Project

This repository is the result of the group project from the official **IFCD55 - Front End Web Development** course, built by **9 developers** working in parallel with a real workflow: branches, pull requests, conflict resolution and continuous deployment.

The goal wasn't just to deliver a website — it was to **simulate a real professional environment** from the first commit.

---

### ✨ Features

- ⚡ **Zero JS by default** — Astro only ships strictly necessary JavaScript to the client
- 🎨 **Consistent UI** — Tailwind CSS utility-first across all pages
- 🎭 **Smooth animations** — GSAP for high-performance sequences
- 🔍 **Integrated search engine** — navigation between student pages
- 📱 **Fully responsive** — designed for any screen size
- 🔄 **Real CI/CD** — automatic deployment on Netlify from `main`

---

### 🛠️ Tech Stack

| Technology | Role |
|:---|:---|
| **Astro** | Base framework — SSG with island architecture |
| **Tailwind CSS** | Utility-first styles — consistent responsive design |
| **GSAP** | High-performance DOM animations |
| **TypeScript** | Static typing in components |
| **Git + GitHub** | Version control for 9 contributors |
| **Netlify** | Hosting + continuous deployment from `main` |

---

### 🔄 Collaborative Workflow
```
main
  └── development
        ├── virginia
        ├── feature/cursor-and-john-page
        ├── feature/student-3
        └── ... (one branch per student)
```

**Process:**
1. **Initial setup** — base routing, shared navbar and search engine
2. **Individual development** — each student worked on their own branch and pages
3. **Pull Requests** — review and merge toward `development`
4. **Continuous integration** — conflict resolution and final merge to `main`
5. **Auto deploy** — Netlify detects changes on `main` and deploys

---

### ⚙️ Local Setup
```bash
git clone https://github.com/HEO-80/FrontendAstro.git
cd FrontendAstro
npm install
npm run dev       # http://localhost:4321
npm run build     # production build
npm run preview   # preview before deploy
```

---

### 👥 Contributors

[![Contributors](https://contrib.rocks/image?repo=HEO-80/FrontendAstro)](https://github.com/HEO-80/FrontendAstro/graphs/contributors)

---

### 🧑‍💻 Teacher & Initial Setup

**Héctor Oviedo** — Course Teacher & Project Architect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hectorob/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/HEO-80)

---

<div align="center">
  <sub>Proyecto desarrollado durante el curso IFCD55 · <strong>Héctor Oviedo</strong> · Zaragoza, España</sub>
</div>
