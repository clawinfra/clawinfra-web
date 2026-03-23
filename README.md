# ClawInfra Website

Website for [ClawInfra](https://clawinfra.work) — open-source infrastructure for the age of autonomous AI agents.

## Stack

- [Astro](https://astro.build) (static output)
- [Tailwind CSS v3](https://tailwindcss.com)
- Node 20
- Deployed to Cloudflare Pages via GitHub Actions

## Development

```bash
npm install
npm run dev
```

Open [http://localhost:4321](http://localhost:4321).

## Build

```bash
npm run build
```

Output goes to `dist/`.

## Deploy

Pushes to `main` automatically trigger a GitHub Actions workflow that builds and deploys to Cloudflare Pages.

## Pages

- `/` — Home
- `/ecosystem` — Projects (ClawChain, EvoClaw, clawchain-sdk, clawkeyring)
- `/roadmap` — Development roadmap
- `/community` — How to contribute and community links
