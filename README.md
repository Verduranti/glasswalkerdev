# Glass Walker Development

Business website for Glass Walker Development — data engineering, analytics, and AI app development.

**Live site:** [https://glasswalker.dev](https://glasswalker.dev)

## Tech Stack

- [Astro 5](https://astro.build) — static site generator
- [Tailwind CSS v4](https://tailwindcss.com) — styling
- [MDX](https://mdxjs.com) — blog content
- [Vercel](https://vercel.com) — hosting and deployment

## Getting Started

```bash
npm install
npm run dev
```

## Build & Deploy

```bash
npm run build
npm run preview
```

The site deploys automatically to Vercel on push to `main`. Pull requests get preview deployments.

## Project Structure

```
src/
├── components/      # Reusable UI components
├── content/blog/    # MDX blog posts
├── layouts/         # Page layouts
├── pages/           # Route pages (index, services, portfolio, about, blog, contact)
└── styles/          # Global CSS and Tailwind config
dist/                # Static HTML fallback (deployable without build step)
public/              # Static assets (favicon, images)
```

## Pages

- **Home** — Hero, services overview, tech stack, CTA
- **Services** — Data Engineering, Analytics & BI, AI App Development
- **Portfolio** — Selected project case studies
- **About** — Founder bio and values
- **Blog** — Technical writing on data and AI topics
- **Contact** — Contact form (Web3Forms) and info
