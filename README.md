# Yunyi Qian — Marketing Portfolio

A minimal, editorial portfolio featuring social media, performance marketing, and creator marketing projects.

## Local preview

Run `node preview.cjs`, then open http://127.0.0.1:4173.

## Website content

The static website is in `dist/`. Edit `index.html` for content and `styles.css` for presentation. Email, LinkedIn, and résumé are intentionally unavailable until real destinations are supplied.

## Vercel deployment

Import this repository into Vercel. The checked-in configuration selects the Other framework preset, skips the build step, and serves `dist/`. No environment variables or dependencies are required.

The existing `.openai/hosting.json` records the previous Sites deployment and is not needed by Vercel.
