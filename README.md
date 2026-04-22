# CodeNode – Semana 5 & 6 🚀

## 🌐 Demo

Proyecto desplegado en Netlify:

https://codenode-semana5.netlify.app/

---

## 🧾 Descripción

En esta práctica he desarrollado un **portfolio web completo utilizando Astro**, siguiendo una estructura modular y orientada a un entorno profesional.

En una segunda fase, se ha integrado **WordPress como CMS externo (Headless)** mediante su REST API, permitiendo mostrar contenido real en lugar de datos hardcodeados.

El resultado es una aplicación que consume datos dinámicos desde un backend y genera tanto la vista de listado como páginas individuales de cada proyecto mediante rutas dinámicas.

---

## 🧩 Funcionalidades principales

- Navegación entre páginas (Inicio, Sobre mí, Proyectos)
- Renderizado dinámico de proyectos desde WordPress
- Consumo de datos mediante REST API
- Sistema de rutas dinámicas (`[slug]`) para páginas individuales
- Página de detalle por proyecto
- Uso de componentes reutilizables (`ProjectCard`)
- Layout base compartido (`BaseLayout`)
- Diseño visual consistente en todas las secciones
- Estilos globales centralizados
- Manejo básico de errores en la carga de datos

---

## 🛠️ Tecnologías utilizadas

- Astro
- HTML5
- CSS3
- JavaScript
- WordPress (Headless CMS)
- REST API

---

## 🏗️ Arquitectura del proyecto

El proyecto está organizado siguiendo una estructura modular:

- `src/pages/` → páginas principales del sitio
- `src/pages/proyectos.astro` → listado de proyectos desde WordPress
- `src/pages/proyectos/[slug].astro` → generación dinámica de páginas de detalle
- `src/components/ProjectCard.astro` → componente reutilizable para tarjetas
- `src/layouts/BaseLayout.astro` → layout base compartido
- `src/styles/global.css` → estilos globales

Fuente de datos:

- WordPress REST API → `wp-json/wp/v2/portfolio`

---

## 🎯 Objetivos alcanzados

- Comprensión de la estructura de proyectos en Astro
- Implementación de navegación entre páginas
- Consumo de datos desde API externa
- Integración de WordPress como CMS Headless
- Uso de `map()` para renderizar contenido dinámico
- Creación de componentes reutilizables con props
- Implementación de rutas dinámicas con `[slug]`
- Generación de páginas individuales a partir de datos reales
- Mejora del diseño y coherencia visual del sitio

---

## ✨ Mejoras implementadas

- Integración de CMS real (WordPress)
- Eliminación de datos hardcodeados
- Rediseño visual del portfolio con estética más profesional
- Mejora de tarjetas de proyecto (imagen, jerarquía, contenido)
- Flujo completo:
  - listado → detalle → enlace externo
- Preparación del proyecto como base real de portfolio personal

---

## 💡 Aprendizaje

Esta práctica ha supuesto un salto importante en la comprensión del desarrollo web moderno.

Se ha trabajado la integración entre frontend y backend mediante API, así como la separación de responsabilidades (datos, lógica y presentación).

Además, se ha reforzado la importancia de trabajar con contenido dinámico y estructuras reutilizables, acercándose a un entorno real de desarrollo.

---

## ⚠️ Dificultades encontradas

- Comprensión inicial de la estructura de Astro
- Implementación de rutas dinámicas (`[slug]`)
- Adaptación del proyecto de datos locales a datos externos
- Integración de WordPress como CMS
- Gestión de campos personalizados (ACF)
- Ajustes de diseño y maquetación

---

## ⚠️ Integración con WordPress

El proyecto consume datos desde un entorno local de WordPress:

http://localhost/wordpress/wp-json/wp/v2/portfolio

Esto permite trabajar con contenido real desde un CMS.

⚠️ Nota: Al estar en entorno local, esta integración no funciona en producción sin un WordPress accesible públicamente.

---

## 🚀 Estado del proyecto

✅ Práctica completada  
🛠️ Integración con CMS implementada  
🔗 Rutas dinámicas funcionales  
🎨 Diseño mejorado y coherente  

Este proyecto sirve como base para futuros desarrollos más complejos.

---

## ▶️ Cómo ejecutar el proyecto

```bash
npm install
npm run dev