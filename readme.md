<div align="center">

# 🌐 Web_UPB - Desarrollo Web

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

*Repositorio de actividades y recursos para el módulo de Programación de Páginas Web*

---

</div>

## 📚 Índice

- [🎯 Descripción](#-descripción)
- [📂 Proyectos](#-proyectos)
- [🛠️ Herramientas](#️-herramientas)
- [🧩 Extensiones de VS Code](#-extensiones-de-vs-code)
- [📁 Estructura del Repositorio](#-estructura-del-repositorio)
- [💡 Tips y Consejos](#-tips-y-consejos)
- [🚀 Cómo Empezar](#-cómo-empezar)

---

## 🎯 Descripción

Bienvenido al repositorio del módulo de **Desarrollo Web** de la Técnica Laboral. Aquí encontrarás todas las actividades realizadas durante el curso, junto con bases y plantillas que te ayudarán si necesitas ponerte al día.

> 💡 *Este repositorio está diseñado para que puedas aprender, practicar y tener referencias claras de cada proyecto.*

---

## 📂 Proyectos

| # | Proyecto | Descripción | Ir al Proyecto |
|:-:|:---------|:------------|:--------------:|
| 01 | **Hola Mundo** | El clásico primer programa en HTML. ¡Tu primer paso en el desarrollo web! | [📄 Ver Proyecto](./proyecto01(Hola_mundo)/index.html) |
| 02 | **Prototipo E-Commerce** | Sitio web con Bootstrap 5: Navbar, Hero con carrusel y Productos | [📄 Ver Plantilla](./Cascaraindex.html) |

> ⚠️ **Nota:** El repositorio contiene la **plantilla base** (`Cascaraindex.html`) con textos genéricos y comentarios de guía. ¡Personalízala con tu propio contenido, imágenes y creatividad!

---

## 🛠️ Herramientas

### Estructura del Proyecto 02 (E-Commerce)

```
📦 Prototipo E-Commerce
├── 📄 index.html
├── 📁 img/
│   ├── 📁 Imagenes_hero/      → Imágenes del carrusel (1280 x 350 px recomendado)
│   └── 📁 Imagenes_productos/ → Imágenes de productos
```

### Componentes utilizados:

| Sección | Componente | Descripción |
|:--------|:-----------|:------------|
| **Header** | Navbar | Barra de navegación responsive con Bootstrap |
| **Main** | Hero/Carrusel | Carrusel de imágenes destacadas |
| **Main** | Productos | Sección de catálogo *(en desarrollo)* |
| **Footer** | Información | Datos de contacto y marca |

---

## 🧩 Extensiones de VS Code

Para una mejor experiencia de desarrollo, instala estas extensiones:

| Extensión | Descripción |
|:----------|:------------|
| 🏷️ **Auto Close Tag** | Cierra automáticamente las etiquetas HTML |
| ⚡ **Bootstrap 5 Quick Snippets** | Snippets rápidos para Bootstrap 5 |
| 🎨 **Color Highlight** | Muestra los colores en el código |
| 🔴 **Live Server** | Servidor local con recarga automática |
| ✨ **Prettier** | Formateador de código |
| 📁 **vscode-icons** | Iconos para archivos y carpetas |

---

## 📁 Estructura del Repositorio

```
📦 iscweb/
├── 📄 readme.md                    ← Estás aquí
├── 📄 Cascaraindex.html            ← ⭐ Plantilla base E-Commerce (¡Úsala!)
│
├── 📁 proyecto01(Hola_mundo)/
│   └── 📄 index.html               ← Hola Mundo básico
│
└── 📁 proyecto02(Prototipo_basico)/
    ├── 📄 index.html               ← (No incluido - crea el tuyo desde Cascaraindex)
    └── 📁 img/
        ├── 📁 Imagenes_hero/       ← Añade tus imágenes (1280x350 px)
        └── 📁 Imagenes_productos/  ← Añade tus imágenes de productos
```

> 💡 **¿Cómo usar la plantilla?** 
> 1. Copia `Cascaraindex.html` a la carpeta del proyecto
> 2. Renómbralo a `index.html`  
> 3. Personaliza los textos marcados con "PERSONALIZA AQUÍ"
> 4. Añade tus imágenes en las carpetas correspondientes

---

## 💡 Tips y Consejos

<details>
<summary><b>🔍 Ver cómo se ve tu página en móvil (¡Sin necesidad de celular!)</b></summary>

### Modo Responsive en el navegador

1. Abre tu página web en el navegador
2. **Click derecho** → **"Inspeccionar"** (o presiona `F12`)
3. Busca el ícono de dispositivos 📱💻 en la barra de herramientas del inspector
4. ¡Listo! Ahora puedes ver cómo se verá en diferentes dispositivos

> 💡 También puedes usar `Ctrl + Shift + M` (Windows) o `Cmd + Shift + M` (Mac) como atajo rápido

</details>

<details>
<summary><b>⚡ Usar Live Server para ver cambios en tiempo real</b></summary>

### Pasos:
1. Instala la extensión **Live Server**
2. Abre tu archivo HTML
3. Click derecho → **"Open with Live Server"**
4. Cada vez que guardes, ¡la página se actualiza sola!

</details>

<details>
<summary><b>🎨 Personalizar colores en Bootstrap</b></summary>

### Si no quieres usar los colores predeterminados:

En lugar de usar clases como `bg-primary`, puedes usar estilos inline:

```html
<nav class="navbar" style="background-color: #3290c6;">
```

O mejor aún, crear tu propia hoja de estilos CSS.

</details>

<details>
<summary><b>📐 Tamaños recomendados para imágenes</b></summary>

| Tipo de imagen | Dimensiones recomendadas |
|:---------------|:-------------------------|
| Hero/Carrusel | 1280 x 350 px |
| Productos | 300 x 300 px (cuadradas en medida de posible) |
| Logo | 150 x 50 px |
| Iconos | 32 x 32 px o 64 x 64 px |

</details>

<details>
<summary><b>🔧 Snippets útiles de Bootstrap 5</b></summary>

Con la extensión **Bootstrap 5 Quick Snippets**, escribe estos atajos:

| Atajo | Resultado |
|:------|:----------|
| `bs5-$` | Plantilla HTML completa con Bootstrap |
| `bs5-navbar-` | Barra de navegación |
| `bs5-carousel-` | Carrusel de imágenes |
| `bs5-card-` | Tarjeta de producto |

</details>

<details>
<summary><b>📝 Buenas prácticas en HTML</b></summary>

1. ✅ Siempre usa `<!DOCTYPE html>` al inicio
2. ✅ Define el idioma: `<html lang="es">`
3. ✅ Incluye meta viewport para responsive
4. ✅ Usa etiquetas semánticas: `<header>`, `<main>`, `<footer>`
5. ✅ Comenta tu código para recordar qué hace cada sección

</details>

---

## 🚀 Cómo Empezar

```bash
# 1. Clona el repositorio
git clone [URL_DEL_REPO]

# 2. Abre la carpeta en VS Code
code iscweb

# 3. Instala las extensiones recomendadas

# 4. Abre cualquier index.html con Live Server
```

---

<div align="center">

### ¿Tienes dudas? 🤔

*En caso encuentres algo que se pueda mejorar, no entiendas o sientas que los comentarios no son suficiente, ¡siempre puedes preguntarme (･.◤)! (Eso si, aveces me demoro para responder)*

---

**Hecho con mucho ❤️ -**
**Creo en ustedes muchachos! -**

</div>
