# 🚀 Proyecto Colaborativo - Curso Frontend y Desarrollo Web

Repositorio oficial del proyecto grupal desarrollado durante el curso oficial de **Desarrollo Web Front End (IFCD55)**. Este proyecto ha sido construido de forma colaborativa simulando un entorno de trabajo real utilizando control de versiones y metodologías ágiles.

🌐 **Demo en vivo (Netlify):** [https://frontendastrodev.netlify.app/](https://frontendastrodev.netlify.app/)
💻 **Repositorio:** [https://github.com/HEO-80/FrontendAstro](https://github.com/HEO-80/FrontendAstro)

---

## 🛠️ Tecnologías Utilizadas

Este proyecto se ha desarrollado utilizando un stack tecnológico moderno, priorizando el rendimiento y la experiencia de usuario:

* **Astro:** Un framework web diseñado para construir sitios estáticos rápidos, que por defecto envía cero JavaScript al cliente. En este proyecto, Astro actúa como la base arquitectónica, permitiéndonos integrar componentes interactivos (islas) solo cuando es estrictamente necesario, lo que optimiza drásticamente los tiempos de carga.
* **Tailwind CSS:** Un framework CSS de bajo nivel que proporciona clases de utilidad para aplicar estilos directamente en el marcado HTML. Nos ha permitido mantener un diseño coherente y responsivo en todas las páginas sin necesidad de escribir archivos CSS externos extensos.
* **GSAP (GreenSock Animation Platform):** Una biblioteca de JavaScript para crear animaciones de alto rendimiento.
* **Git & GitHub:** Control de versiones para el trabajo colaborativo de los 9 contribuidores.
* **Netlify:** Plataforma de alojamiento y despliegue continuo.

---

## 📝 Sobre el Proyecto

Este sitio web es el resultado de la aplicación práctica de los conocimientos adquiridos durante las 300 horas del curso. El desarrollo se ha estructurado de la siguiente manera:

1.  **Setup Inicial:** Configuración base del enrutamiento, barra de navegación compartida y un motor de búsqueda integrado.
2.  **Desarrollo Individual:** Cada alumno contó con su propio espacio (páginas individuales) para maquetar, diseñar e implementar funcionalidades, trabajando a través de ramas (*branches*) como `development`, `virginia`, o `feature/cursor-and-john-page`.
3.  **Integración Continua:** Resolución de conflictos y fusión (*merge*) de las aportaciones individuales mediante *Pull Requests* hacia la rama principal.

---

## ⚙️ Instalación y Uso Local

Si deseas clonar y ejecutar este proyecto en tu entorno local, sigue estos pasos:

Asegúrate de tener [Node.js](https://nodejs.org/) instalado. Desde la terminal, en la raíz del proyecto, ejecuta:

| Comando | Acción |
| :--- | :--- |
| `npm install` | Instala todas las dependencias necesarias. |
| `npm run dev` | Inicia el servidor local de desarrollo en `localhost:4321`. |
| `npm run build` | Compila el sitio para producción en la carpeta `./dist/`. |
| `npm run preview` | Previsualiza la compilación localmente antes de desplegar. |

---

## 👥 Contribuidores

Este proyecto ha salido adelante gracias al esfuerzo, talento y código de **9 desarrolladores**. Un agradecimiento especial a todos los alumnos por su dedicación y por el altísimo nivel demostrado en cada *commit*. 

*Puedes ver la lista completa de contribuidores y sus aportaciones en la [sección de Contributors de GitHub](https://github.com/HEO-80/FrontendAstro/graphs/contributors).*

---
# 🚀 Collaborative Project - Frontend and Web Development Course

Official repository for the group project developed during the **Front End Web Development (IFCD55)** official course. This project was built collaboratively, simulating a real-world work environment using version control and agile methodologies.

🌐 **Live Demo (Netlify):** [https://frontendastrodev.netlify.app/](https://frontendastrodev.netlify.app/)
💻 **Repository:** [https://github.com/HEO-80/FrontendAstro](https://github.com/HEO-80/FrontendAstro)

---

## 🛠️ Built With

This project was developed using a modern tech stack, prioritizing performance and user experience:

* **Astro:** A web framework designed to build fast static sites, which by default ships zero JavaScript to the client. In this project, Astro acts as the architectural base, allowing us to integrate interactive components (islands) only when strictly necessary, which drastically optimizes load times. You can think of it as building a solid, static house and only plugging in electricity (JavaScript) to the specific appliances (islands) that need it.
* **Tailwind CSS:** A utility-first CSS framework that provides classes to apply styles directly within the HTML markup. This allowed us to maintain a consistent and responsive design across all pages without the need to write extensive external CSS files. Think of it as having a box of pre-painted, ready-to-use Lego bricks instead of having to mold and paint each brick yourself.
* **GSAP (GreenSock Animation Platform):** A robust JavaScript library for creating high-performance animations. It provides precise control over sequences and CSS properties. It acts like a digital puppeteer, smoothly bringing the static DOM elements to life.
* **Git & GitHub:** Version control for the collaborative work of the 9 contributors.
* **Netlify:** Platform for hosting and continuous deployment.

---

## 📝 About the Project

This website is the result of the practical application of the knowledge acquired during the 300 hours of the course. The development was structured as follows:

1.  **Initial Setup:** Base configuration of the routing, shared navigation bar, and an integrated search engine.
2.  **Individual Development:** Each student had their own space (individual pages) to layout, design, and implement features, working through branches like `development`, `virginia`, or `feature/cursor-and-john-page`.
3.  **Continuous Integration:** Conflict resolution and merging of individual contributions via Pull Requests to the main branch.

---

## ⚙️ Local Installation and Usage

If you want to clone and run this project in your local environment, follow these steps:

Make sure you have [Node.js](https://nodejs.org/) installed. From your terminal, in the root of the project, run:

| Command | Action |
| :--- | :--- |
| `npm install` | Installs all necessary dependencies. |
| `npm run dev` | Starts the local development server at `localhost:4321`. |
| `npm run build` | Builds your production site to `./dist/`. |
| `npm run preview` | Previews your build locally before deploying. |

---

## 👥 Contributors

This project was made possible by the effort, talent, and code of **9 developers**. A special thanks to all the students for their dedication and the high level shown in every commit.

*You can see the full list of contributors and their inputs in the [GitHub Contributors section](https://github.com/HEO-80/FrontendAstro/graphs/contributors).*

---

## 📸 Project Gallery

*Since we couldn't take a group photo to close the course, we leave here the "picture" of our teamwork, which speaks for itself:*

![Project Screenshot](https://frontendastrodev.netlify.app/og-image.jpg)

## 📸 Galería del Proyecto

![Captura de la web FrontendAstro](https://frontendastrodev.netlify.app/og-image.jpg) 

```text
/
├── public/
│   └── favicon.svg
├── src
│   ├── assets
│   │   └── astro.svg
│   ├── components
│   │   └── Welcome.astro
│   ├── layouts
│   │   └── Layout.astro
│   └── pages
│       └── index.astro
└── package.json
```
