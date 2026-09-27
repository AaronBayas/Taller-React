# Asistencia Técnica | Taller de Reparación de Equipos Electrónicos

Este proyecto es una Landing Page (Página de Aterrizaje) diseñada para un taller de reparación y mantenimiento de equipos electrónicos, como computadoras de escritorio, laptops e impresoras.

Originalmente construida con HTML y CSS puro, esta versión ha sido refactorizada y migrada para utilizar el ecosistema moderno de **React** y **Vite**.

## Descripción del Proyecto

El sitio tiene como objetivo principal captar clientes locales brindando información clara y directa sobre los servicios técnicos que se ofrecen, la confianza que transmite el negocio (garantía, diagnóstico rápido, repuestos de calidad) y la facilidad para ponerse en contacto.

La interfaz de usuario destaca por ser **responsiva**, moderna y limpia, con secciones claramente identificadas:
- **Hero / Inicio**: Llama la atención inmediata con un botón de llamada a la acción.
- **Servicios**: Detalla qué repara el taller mediante tarjetas ilustrativas.
- **Nosotros**: Explica los beneficios y garantías.
- **Contacto**: Incluye información de ubicación, horarios y un formulario para solicitar servicio.

## Tecnologías Utilizadas

- **[React 18](https://react.dev/)**: Librería principal para la construcción de interfaces de usuario basadas en componentes.
- **[Vite](https://vitejs.dev/)**: Herramienta de frontend de próxima generación que proporciona un entorno de desarrollo extremadamente rápido y una construcción de producción optimizada.
- **[JavaScript (JSX)](https://developer.mozilla.org/es/docs/Web/JavaScript)**: Lógica y estructuración de componentes.
- **[Vanilla CSS3](https://developer.mozilla.org/es/docs/Web/CSS)**: Sistema de diseño utilizando variables semánticas (`:root`), Flexbox, CSS Grid y Media Queries para garantizar la adaptabilidad a dispositivos móviles.

## Estructura del Proyecto

El código fuente está modularizado en la carpeta `src`:

```text
src/
├── components/
│   └── App/
│       └── App.jsx       # Componente principal que contiene la interfaz
├── styles/
│   ├── index.css         # Estilos globales de la página y los componentes
│   └── variables.css     # Variables CSS semánticas (colores, fuentes, espacios)
└── main.jsx              # Punto de entrada de la aplicación React
```

## Instrucciones de Instalación y Ejecución

Sigue estos pasos para clonar y levantar el entorno de desarrollo en tu máquina local.

### 1. Prerrequisitos
Asegúrate de tener instalado **[Node.js](https://nodejs.org/es/)** (versión 18 o superior recomendada) y **npm**.

### 2. Clonar el repositorio y acceder a la carpeta (opcional)
Si vas a clonarlo desde GitHub:
```bash
git clone https://github.com/AaronBayas/Taller-React.git
cd Taller-React
```

### 3. Instalar las dependencias
Ejecuta el siguiente comando en la raíz del proyecto para descargar todas las librerías necesarias:
```bash
npm install
```

### 4. Ejecutar el servidor de desarrollo
Levanta el proyecto utilizando Vite:
```bash
npm run dev
```

### 5. Ver la aplicación
Abre tu navegador de preferencia y dirígete a la ruta local que te indique la terminal, por lo general es:
**http://localhost:5173/**

---
_Desarrollado como proyecto de Taller de React para Desarrollo Web._
