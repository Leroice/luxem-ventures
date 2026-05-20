# LUXEM Ventures

Website for [LUXEM Ventures](https://luxemvc.com.au) — an Australian Family Office and early stage venture investor.

## Stack

Static HTML/CSS/JS. No framework, no build step.

- Single `index.html` — all styles and scripts inline
- Lottie Web (CDN) for scroll-scrubbed hero animation and preloader
- Akkurat typeface (local, licensed)

## Structure

```
luxem-ventures/
├── index.html
├── documents/        Lottie animation JSON
├── fonts/            Akkurat (6 variants, OTF)
└── images/           Site imagery and logos
```

## Deployment

Hosted on Cloudflare Pages. Pushes to `main` deploy automatically.

## Development

No build process. Open `index.html` in a browser or use a local server:

```bash
npx serve .
```

## Domains

- luxemvc.com.au
