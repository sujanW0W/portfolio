# Portfolio

A simple portfolio using Astro.

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```
/
├── src/
│   ├── components/
│   │    ├── Navbar.astro
│   │    ├── Footer.astro
│   │    ├── Logo.astro
│   │    └── ThemeToggle.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   ├── index.astro
│   │   ├── about.astro
│   │   └── projects/
│   │       └── index.astro
│   │       └── [slug].astro
│   └── styles/
│       ├── global.css
│       └── (component-specific styles can be co-located or here)
public/
├── favicon.svg
└── assets/
```

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
