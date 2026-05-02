# 🚌 Unibus Landing — Página de Descarga

<div align="center">

[![Astro](https://img.shields.io/badge/Astro-FF5D01?style=for-the-badge&logo=astro&logoColor=white)](https://astro.build)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/es/docs/Web/HTML)

**Landing page oficial para descargar la app Unibus — Seguimiento del transporte universitario.**

[Ver en vivo](#) · [Características](#-características) · [Instalación](#-instalación)

</div>

---

## 💡 ¿Qué es Unibus?

**Unibus** es una aplicación móvil diseñada para la comunidad universitaria que permite **seguir en tiempo real la ubicación del autobús escolar**, consultar rutas, paradas y horarios. Esta landing page es el punto de entrada para que estudiantes y personal descarguen la app.

> 🎯 **Objetivo:** Facilitar el acceso a la app durante la fase beta dentro de la universidad.

---

## ✨ Características de la Landing

### 🎨 Diseño Moderno y Responsive
- **Mockup de smartphone** con la interfaz de la app en el hero.
- **Diseño responsive** adaptado a móvil, tablet y escritorio.
- **Tipografía limpia** y espaciado profesional.

### 🌓 Modo Oscuro / Claro
- **Toggle de tema** en la barra de navegación.
- Transición suave entre modo claro y oscuro.
- Persistencia del tema seleccionado.

### 📲 Descarga Directa
- **Botón de descarga APK** para Android (instalación directa).
- Link a redes sociales (Instagram).
- Badge "Beta" para indicar la etapa del proyecto.

### ⚡ Rendimiento
- Construida con **Astro**: sitio estático ultrarrápido.
- Carga instantánea, sin dependencias pesadas.
- **Node.js >= 22** para desarrollo.

---

## 🚀 Tecnologías

| Tecnología | Uso |
|------------|-----|
| **Astro** | Framework para sitios estáticos rápidos |
| **TypeScript** | Tipado estático para componentes |
| **CSS** | Estilos personalizados sin frameworks externos |
| **SVG** | Iconos vectoriales optimizados |

---

## 📁 Estructura del Proyecto

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── assets/
│   │   └── astro.svg
│   ├── components/
│   │   └── Welcome.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
├── astro.config.mjs
└── package.json
```

---

## 🛠️ Instalación

```bash
# 1. Clonar el repositorio
git clone https://github.com/ebravo-dev/unibus-landing.git
cd unibus-landing

# 2. Instalar dependencias (Node >= 22)
npm install

# 3. Iniciar servidor de desarrollo
npm run dev

# 4. Construir para producción
npm run build
```

### Scripts disponibles

| Comando | Acción |
|---------|--------|
| `npm run dev` | Servidor local en `localhost:4321` |
| `npm run build` | Construcción estática en `./dist/` |
| `npm run preview` | Previsualizar build localmente |

---

## 📲 Sobre la App Unibus

Unibus está actualmente en fase **beta universitaria**.

- **Plataforma:** Android (APK directo)
- **Próximamente:** Play Store y App Store
- **Redes:** [@unibus2026 en Instagram](https://www.instagram.com/unibus2026/)

---

## 📄 Licencia

Proyecto universitario.  
Desarrollado por [Eder J. G. Bravo](https://github.com/ebravo-dev).

---

> *"Hecho para la comunidad universitaria."* 🎓
