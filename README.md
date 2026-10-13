# HVAC Repair Phoenixville PA — Astro Site

Static Astro site for **hvacrepairphoenixvillepa.com**, optimized for Cloudflare Pages.

## Features

- Responsive, mobile-first design
- Deep blue + amber color theme
- OpenStreetMap embed pinpointing 25 Gay St, Phoenixville, PA 19460
- SEO: meta tags, canonical, JSON-LD HVACBusiness schema, sitemap, robots.txt
- Blog section powered by Markdown (Astro Content Collections)
- Fast static build for Google indexing
- Cloudflare Pages ready (static output, no adapter needed)

## Phone number

Placeholder: **(610) 555-0199** — replace across the site (search for `6105550199` and `555-0199`).

## Deploy to Cloudflare Pages

1. Push this folder to a GitHub/GitLab repo.
2. In Cloudflare Dashboard → Workers & Pages → Create → Connect to Git.
3. Build settings:
   - **Framework preset:** Astro
   - **Build command:** `npm run build`
   - **Build output directory:** `dist`
4. Add custom domain `hvacrepairphoenixvillepa.com`.
5. Submit `https://hvacrepairphoenixvillepa.com/sitemap-index.xml` in Google Search Console.

## Local development

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

Output is in `dist/`.

## Notes

- Site is fully static — ideal for Pages and SEO.
- `@astrojs/sitemap` generates `/sitemap-index.xml` at build time.
- `public/robots.txt` points crawlers to the sitemap.
- Blog posts live in `src/content/blog/*.md`.
