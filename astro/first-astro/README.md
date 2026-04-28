# My First Astro Project

First Astro tutorial project.

<br />

## 📋 Prerequisites

- Node.js &ge; v22.12.0

## ⚙️ Project Setup

- To create a starting project:

    ```bash
    npm create astro@latest
    ```

- Alternatively, use Astro Starter Kit: Minimal:

    ```bash
    npm create astro@latest -- --template minimal
    ```

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

## 📁 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
📁 first-astro/
├── .gitignore
├── astro.config.mjs
├── package-lock.json
├── package.json
├── README.md
├── tsconfig.json
├── 📁 .vscode/
│   ├── extensions.json
│   └── launch.json
├── 📁 public/
│   ├── favicon.ico
│   └── favicon.svg
└── 📁 src/
    └── 📁 pages/
        └── index.astro

```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

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

## 💡 What I Learned

- The global is a style element does not mean it will apply to all elements. It will only apply to **descendant** elements.

```css
/* Will only apply to elements inside this component (Astro file) */
<style is:global>
    p {
        color: gray;
    }
</style>
```
