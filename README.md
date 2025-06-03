# PrometeoRoot: Cybersecurity Portfolio

Este proyecto es un portafolio personal enfocado en ciberseguridad, desarrollado con [Astro](https://astro.build/). Incluye información sobre laboratorios, proyectos, habilidades y contacto.

## 🚀 Estructura del Proyecto

```
/
├── public/
│   └── assets/
│       └── backgrounds/   # Imágenes de fondo y recursos estáticos
├── src/
│   ├── components/        # Componentes Astro y utilidades
│   ├── content/           # Contenido en formato Markdown
│   ├── layouts/           # Layouts base para las páginas
│   ├── pages/             # Páginas principales y rutas
│   └── styles/            # Estilos globales
├── package.json
├── astro.config.mjs
└── tsconfig.json
```

- Las imágenes y recursos estáticos se encuentran en `public/assets/backgrounds/`.
- El contenido de los laboratorios está en `src/content/lab/`.
- Los componentes reutilizables están en `src/components/`.

## 🧑‍💻 Scripts útiles

| Comando             | Acción                                         |
|---------------------|------------------------------------------------|
| `npm install`       | Instala las dependencias                       |
| `npm run dev`       | Inicia el servidor de desarrollo (`localhost:4321`) |
| `npm run build`     | Genera la versión de producción en `./dist/`   |
| `npm run preview`   | Previsualiza el sitio generado                 |
| `npm run astro ...` | Ejecuta comandos CLI de Astro                  |

## 🌐 Tecnologías principales

- [Astro](https://astro.build/) (framework principal)
- [TypeScript](https://www.typescriptlang.org/)
- [CSS Custom Properties](https://developer.mozilla.org/en-US/docs/Web/CSS/--*)

## 📁 Estructura de contenido

- `src/pages/` contiene las páginas principales (`index.astro`, `about.astro`, etc.)
- `src/content/lab/` almacena laboratorios y retos de ciberseguridad en Markdown
- `src/components/` incluye iconos, navegación, footer y otros componentes reutilizables

## 📦 Recursos

- [Documentación de Astro](https://docs.astro.build)
- [Discord de Astro](https://astro.build/chat)

---

Desarrollado por PrometeoRoot. Todos los derechos reservados.
