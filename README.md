# Minimalist Portfolio

<img src="portfolio.png" />

Edit the `cv.json` file to create your own portfolio.

## 🚀 Project Structure

Inside of your Portfolio project, you'll see the following folders and files:

```text
/
├── public/
│   ├── assets/
│   │   └── ...
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── sections/
│   │   │   └── About.astro
│   │   │   └── Education.astro
│   │   │   └── Expiriences.astro
│   │   │   └── Hero.astro
│   │   │   └── Projects.astro
│   │   │   └── Skills.astro
│   │   └── Wrapper.astro
│   ├── data/
│   │   └── cv.json
│   ├── icons/
│   │   └── ...
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
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
