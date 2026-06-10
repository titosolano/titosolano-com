# ts2026 — titosolano.com

Personal portfolio of Tito Solano. Astro + Sanity + Vercel.

## Stack

| Layer | Tech |
|---|---|
| Frontend | Astro 6 + TypeScript |
| Styles | Global CSS (Client-First) |
| Interactive | React islands |
| Animations | GSAP + ScrollTrigger |
| Sliders | Swiper.js |
| CMS | Sanity v5 |
| Deploy | Vercel |

## Commands

```bash
npm install
npm run dev      # localhost:4321
npm run build
git push         # auto-deploys to Vercel
```

## Env vars

Create a `.env` file at the root:

```
PUBLIC_SANITY_PROJECT_ID=3i6bh3hq
PUBLIC_SANITY_DATASET=production
```

## Sanity

- Studio: [titosolano.sanity.studio](https://titosolano.sanity.studio)
- Local: `cd ../ts2026-sanity && npm run dev`
- Schemas: `project`, `testimonial`, `faq`, `milestone`, `post`
