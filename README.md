<<<<<<< HEAD
# Astro Starter Kit: Portfolio

```sh
npm create astro@latest -- --template portfolio
```

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/withastro/astro/tree/latest/examples/portfolio)
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/withastro/astro/tree/latest/examples/portfolio)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/withastro/astro?devcontainer_path=.devcontainer/portfolio/devcontainer.json)

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

![portfolio](https://user-images.githubusercontent.com/357379/210779178-a98f0fb7-6b1a-4068-894c-8e1403e26654.jpg)

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
=======
# Astrolify — Astro SaaS Starter

A premium SaaS landing page template built with [Astro](https://astro.build). Fully configurable from a single file, dark/light mode, CSS scroll-snap slider, and zero JS frameworks.

## Stack

- **Astro** — static-first framework with island architecture
- **TypeScript** — type-safe config and components
- **CSS custom properties** — design token system (`--ac-*`), no Tailwind dependency
- **Vanilla TS** — progressive enhancement only (slider, theme switch, accordion, tabs)

## Getting started

```bash
npm install
npm run dev
```

Open [http://localhost:4321](http://localhost:4321).

## Configuration

All content lives in one file:

```
src/config/site.config.ts
```

Edit brand, navigation, hero, stats, logo cloud, features, pricing, testimonials, FAQ, and footer sections without touching any component.

## Project structure

```
src/
├── components/       # Astro components (one per section)
├── config/
│   └── site.config.ts  # ← edit this to customize the page
├── data/
│   └── icons.ts      # SVG icon paths (ui, features, social)
├── layouts/
│   └── Layout.astro  # HTML shell, theme init, SEO meta
├── pages/
│   └── index.astro   # Page composition
├── styles/
│   └── globals.css   # Design tokens and global utilities
└── utils/            # Shared helpers
```

## Theme

The site follows the OS color scheme preference by default (`prefers-color-scheme`). Users can override it with the toggle in the header. No flash on load — the theme is applied synchronously in the `<head>` before first paint.

## Scripts

| Command | Action |
|---|---|
| `npm run dev` | Start dev server at `localhost:4321` |
| `npm run build` | Type-check and build to `./dist` |
| `npm run preview` | Preview the production build locally |

## License

MIT
>>>>>>> 57ed9ad6785388ca4040a53f769eb9692ad29022
