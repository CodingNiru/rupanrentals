# Beach Please

A static Astro migration of the public Beach Please website for local review. The live WordPress site has not been changed and this project has not been deployed.

## Run locally

```sh
npm install
npm run dev
```

Astro serves the site at `http://localhost:4321` by default.

## Pages

- `/` — home and rental highlights
- `/gallery/` — locally stored property photos and the original video tour
- `/book-now/` — direct, Vrbo, and Airbnb booking links
- `/contact-us/` — email, phone, and social links

Photos and booking logos are stored in `public/images/`. Booking providers and the video tour remain external links.

## Build

```sh
npm run build
npm run preview
```

The static production output is written to `dist/`. No hosting or deployment configuration is included.
