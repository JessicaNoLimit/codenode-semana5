# CodeNode – Semana 5 🚀

## 🌐 Demo

Proyecto desplegado en Netlify:

https://69dd7dbf7e17a100b06ac527--codenode-semana5.netlify.app/

---

## 🧾 Descripción

En esta práctica he desarrollado un portfolio básico utilizando Astro.

El proyecto está estructurado en varias páginas conectadas entre sí mediante navegación interna. Incluye una presentación personal, una sección "Sobre mí" en formato Markdown y un listado de proyectos generado dinámicamente a partir de datos reutilizables.

Además, se ha implementado una estructura más modular mediante componentes y rutas dinámicas para mejorar la organización del código.

---

## 🧩 Apartados incluidos

- **Inicio**: presentación personal breve
- **Sobre mí**: contenido en Markdown con información personal y stack tecnológico
- **Proyectos**: listado dinámico de proyectos ficticios
- **Detalle de proyecto**: página individual generada dinámicamente para cada proyecto

---

## 🛠️ Tecnologías utilizadas

- Astro
- HTML
- CSS
- JavaScript

---

## 🏗️ Estructura del proyecto

- `src/pages/` → páginas principales del sitio
- `src/pages/proyectos/[slug].astro` → rutas dinámicas de detalle
- `src/components/ProjectCard.astro` → componente reutilizable para mostrar proyectos
- `src/data/proyectos.js` → datos centralizados de los proyectos
- `src/layouts/BaseLayout.astro` → layout base para páginas Markdown
- `src/styles/global.css` → estilos globales

---

## 🎯 Objetivos de la práctica

- Aprender la estructura básica de un proyecto en Astro
- Crear múltiples páginas dentro de `src/pages`
- Implementar navegación entre páginas
- Renderizar contenido dinámico con `map()`
- Separar datos en archivos reutilizables
- Crear componentes reutilizables con props
- Implementar rutas dinámicas con `[slug]`
- Integrar Markdown dentro del proyecto

---

## 💡 Aprendizaje

Esta práctica me ha permitido entender mejor cómo funciona Astro a nivel de estructura, rutas y organización del código.

He aprendido a separar datos del componente visual, reutilizar lógica mediante componentes y generar páginas dinámicas a partir de un conjunto de datos.

También he visto cómo integrar Markdown dentro de un proyecto y aplicar un layout común para mantener la coherencia visual.

---

## ⚠️ Dificultades encontradas

Al principio me costó entender la estructura inicial de Astro y cómo funcionan las rutas dinámicas.

También tuve que reorganizar el proyecto para separar correctamente los datos, los componentes y las páginas, lo que me ayudó a comprender mejor una estructura más profesional.

---

## 🚀 Estado del proyecto

Práctica completada, funcional y desplegada.

---

## ▶️ Cómo ejecutar el proyecto

```bash
npm install
npm run dev