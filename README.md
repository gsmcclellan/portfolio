# Portfolio Site

Built with [Astro](https://astro.build). Clean, minimal, fast.

## Getting started

```bash
npm install
npm run dev
```

Then open http://localhost:4321

## Customizing

Before going live, update these placeholders:

| File | What to change |
|------|---------------|
| `src/components/Hero.astro` | Your name, tagline |
| `src/components/About.astro` | Your bio |
| `src/components/Projects.astro` | Your actual projects, GitHub links |
| `src/components/Skills.astro` | Your actual tech stack |
| `src/components/Contact.astro` | Your email, GitHub, LinkedIn, Twitter URLs |
| `src/components/Nav.astro` | Your name in the nav logo |
| `src/layouts/Layout.astro` | Page title and meta description |
| `astro.config.mjs` | Your production domain |
| `public/favicon.svg` | Your initial / icon |

## Deploying

The easiest options for a free deploy:

- **Vercel**: `npm i -g vercel && vercel` — done
- **Netlify**: drag-and-drop the `dist/` folder after `npm run build`
- **GitHub Pages**: push to GitHub and enable Pages with the Astro action

## Project structure

```
portfolio/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── Nav.astro
│   │   ├── Hero.astro
│   │   ├── About.astro
│   │   ├── Projects.astro
│   │   ├── Skills.astro
│   │   └── Contact.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
├── astro.config.mjs
└── package.json
```
