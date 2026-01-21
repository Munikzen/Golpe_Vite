# Golpe de Saber

Una aplicación educativa interactiva construida con React y Vite.

## Descripción

Golpe de Saber es un juego educativo que permite a los usuarios responder preguntas en diferentes temas mientras participan en un combate estratégico por equipos.

## Tecnologías

- **React** - Librería de UI
- **Vite** - Herramienta de construcción rápida
- **React Router** - Enrutamiento
- **CSS** - Estilos personalizados

## Instalación

```bash
npm install
```

## Scripts Disponibles

### `npm run dev`

Inicia el servidor de desarrollo en [http://localhost:3000](http://localhost:3000).

```bash
npm run dev
```

### `npm run build`

Construye la aplicación para producción en la carpeta `dist`.

```bash
npm run build
```

## Estructura del Proyecto

```
src/
├── App.jsx              # Componente principal
├── App.css              # Estilos principales
├── index.jsx            # Punto de entrada
├── index.css            # Estilos globales
├── img/                 # Imágenes del proyecto
└── UIComponents/        # Componentes reutilizables
    ├── Card.jsx
    ├── PlayerCard.jsx
    ├── CorrectButton.jsx
    ├── WrongButton.jsx
    ├── ShowAnswerButton.jsx
    ├── ManualButton.jsx
    ├── Credits.jsx
    ├── GenericGameMode.jsx
    └── HP_bar.jsx
```

## Características

- Juego educativo con preguntas de opción múltiple y abiertas
- Sistema de combate por equipos
- Habilidades especiales (escudo, silencio, x2 daño)
- Sistema de vida (HP) dinámico
- Interfaz responsiva
- Integración con API externa para preguntas

## Variables de Entorno

Las configuraciones específicas del servidor están definidas en `vite.config.js`.

## Deployment

El proyecto está configurado para desplegarse en `/golpe/` en producción. Esta ruta base está definida en `vite.config.js`.

Para cambiar la ruta base, modifica el valor de `base` en `vite.config.js`.

## Notas de Migración desde Create React App

Este proyecto fue migrado de Create React App a Vite. Los cambios principales incluyen:

- Actualización a extensiones `.jsx` para componentes React
- Nuevo archivo `vite.config.js` para configuración
- El archivo `index.html` se movió a la raíz del proyecto
- `index.js` renombrado a `index.jsx`
- Todas las funcionalidades se mantienen intactas

## Recursos

- [Documentación de React](https://reactjs.org/)
- [Documentación de Vite](https://vitejs.dev/)
