# 🕵️‍♂️ Reporte de Caza: Netflix (Edición Arquitectos)

Este documento detalla la investigación del stack tecnológico de **Netflix**, realizado para la asignatura de Interfaces Gráficas para la Web.

---

## 🏗️ 1. Entorno de Edición (IDE)
Aunque existe libertad de cátedra técnica, los equipos de UI de Netflix estandarizan su flujo en:
* **VS Code:** Herramienta principal para el desarrollo Frontend.
* **Extensiones Clave:** * `ESLint` y `Prettier` (Garantizan que miles de desarrolladores escriban código con el mismo estilo).
    * `Tailwind CSS IntelliSense` (Para agilizar el diseño en el editor).

## 🌐 2. Ecosistema de Navegación
Netflix no solo prueba en computadoras, su prioridad es la **eficiencia energética y de datos**:
* **Chrome Dev Edition:** Para depuración avanzada de JavaScript.
* **Webkit / Chromium:** Utilizan versiones específicas para asegurar compatibilidad con **Smart TVs** y consolas de videojuegos.
* **Herramienta de Medición:** `Lighthouse` (Google) para asegurar que el contenido cargue en menos de 2 segundos.

## 📂 3. Gestión de Versiones
Netflix es un gigante del código abierto y la colaboración:
* **Git:** Como sistema base.
* **Plataforma:** `GitHub Enterprise` para código interno y `GitHub Public` para sus proyectos de comunidad.
* **Fuente:** [Perfil oficial de Netflix en GitHub](https://github.com/Netflix)

## 🎨 4. Diseño UI/UX
Antes de escribir una sola línea de código, Netflix utiliza:
* **Figma:** Para el prototipado colaborativo.
* **Hawkins Design System:** Es su sistema de diseño propio (biblioteca de componentes) que vive dentro de Figma para que todos los botones y menús se vean iguales en cualquier dispositivo.

## 🛠️ 5. Lenguajes y Herramientas Base
La base de su arquitectura es robusta y escalable:
* **Lenguajes:** HTML5, CSS3 y **TypeScript** (utilizado para evitar errores de tipo en aplicaciones grandes).
* **Herramienta "Moderna" (2025/2026):**
    * `React`: La librería principal para sus interfaces.
    * `Next.js`: Implementado para la renderización del lado del servidor (SSR), mejorando la velocidad de carga inicial.
![camaleon](https://github.com/user-attachments/assets/28f66898-a5f5-4169-8ad4-4637d02f1f7f)

---

> **Evidencias de la Caza:**
> * *Captura de vacante "Senior Software Engineer" en Netflix Jobs donde solicitan dominio de TypeScript y Figma.*
> * *Link al Blog de Ingeniería de Netflix consultado.*
