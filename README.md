# Astro Starter Kit: Basics

```sh
npm create astro@latest -- --template basics
```

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

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

To learn more about the folder structure of an Astro project, refer to [our guide on project structure](https://docs.astro.build/en/basics/project-structure/).

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).

## 🔧 Cómo personalizar este portfolio

- Reemplazar la foto de perfil: coloca tu imagen (por ejemplo `mi-foto.jpg`) en la carpeta `public/` y luego edita `src/components/Welcome.astro` cambiando el atributo `src` del elemento `img` por `/mi-foto.jpg`.
- Crear la página About: añade `src/pages/about.astro` con tu biografía y enlázala (el layout ya incluye `/about`).
- Crear la página Proyectos: añade `src/pages/projects.astro` y añade tarjetas o enlaces a tus proyectos.

Siguientes pasos sugeridos:

1. Reemplaza el texto del hero en `src/components/Welcome.astro` por una frase más concreta sobre tus habilidades.
2. Añade enlaces a redes sociales en el footer o en la cabecera.
3. Opcional: integrar Tailwind o un sistema de diseño para mayor personalización.
