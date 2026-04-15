# CodeNode – Semana 5 🚀

## 🌐 Demo

Proyecto desplegado en Netlify:

https://69dd7dbf7e17a100b06ac527--codenode-semana5.netlify.app/

---

## 🧾 Descripción

En esta práctica he desarrollado un **portfolio web completo utilizando Astro**, enfocado en una estructura profesional, modular y reutilizable.

El proyecto incluye varias páginas conectadas entre sí mediante navegación interna, con una identidad visual coherente y un diseño cuidado. Se ha trabajado tanto la parte técnica como la presentación, simulando un entorno real de desarrollo.

Se ha implementado una arquitectura basada en componentes, separación de datos y generación dinámica de contenido, siguiendo buenas prácticas de desarrollo web moderno.

---

## 🧩 Funcionalidades principales

- Navegación entre páginas (Inicio, Sobre mí, Proyectos)
- Renderizado dinámico de proyectos desde datos externos
- Sistema de rutas dinámicas (`[slug]`) para páginas individuales
- Uso de componentes reutilizables (`ProjectCard`)
- Layout base compartido (`BaseLayout`)
- Integración de contenido en Markdown
- Diseño visual consistente en todas las secciones
- Estilos globales centralizados

---

## 🛠️ Tecnologías utilizadas

- Astro
- HTML5
- CSS3
- JavaScript

---

## 🏗️ Arquitectura del proyecto

El proyecto está organizado siguiendo una estructura modular:

- `src/pages/` → páginas principales del sitio
- `src/pages/proyectos/[slug].astro` → generación dinámica de páginas de detalle
- `src/components/ProjectCard.astro` → componente reutilizable para tarjetas de proyecto
- `src/data/proyectos.js` → fuente de datos centralizada
- `src/layouts/BaseLayout.astro` → layout base compartido
- `src/styles/global.css` → estilos globales y sistema visual

---

## 🎯 Objetivos alcanzados

- Comprensión de la estructura de proyectos en Astro
- Implementación de navegación entre páginas
- Uso de `map()` para renderizar contenido dinámico
- Separación de lógica, datos y presentación
- Creación de componentes reutilizables con props
- Implementación de rutas dinámicas con `[slug]`
- Integración de Markdown en el flujo del proyecto
- Mejora del diseño y coherencia visual del sitio

---

## ✨ Mejoras implementadas

- Rediseño visual del portfolio con estética limpia y profesional
- Mejora de la disposición de elementos (alineación, jerarquía visual)
- Reutilización de estilos para botones y componentes
- Uso de contenedores y tarjetas para mejorar la legibilidad
- Ajustes finos de spacing, márgenes y composición
- Preparación del proyecto como base real de portfolio personal

---

## 💡 Aprendizaje

Esta práctica ha supuesto un salto importante en la comprensión del desarrollo web estructurado.

Se ha trabajado la separación de responsabilidades (datos, componentes, vistas), así como la reutilización de código y la generación dinámica de contenido.

Además, se ha reforzado la importancia del diseño y la coherencia visual como parte clave de un proyecto real.

---

## ⚠️ Dificultades encontradas

- Comprensión inicial de la estructura de Astro
- Implementación de rutas dinámicas y uso de `[slug]`
- Gestión de datos externos y su integración en componentes
- Ajustes de diseño (alineación, posicionamiento y estilos)
- Problemas de tipado en datos (arrays vs strings)

---

## 🚀 Estado del proyecto

✅ Práctica completada  
🛠️ Estructura profesional implementada  
🎨 Diseño mejorado y coherente  

Este proyecto sirve como base para futuros desarrollos más complejos.

---

## ▶️ Cómo ejecutar el proyecto

```bash
npm install
npm run dev