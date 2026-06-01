# Hialeah Radio Club — website

Simple, static landing page: one HTML file, one stylesheet, lightweight assets.

## Customize your content

1. **Logo** — The site uses [`assets/logo.jpeg`](assets/logo.jpeg). To swap logos, replace that file or change the `<img>` and favicon paths in [`index.html`](index.html).

2. **Photos** — Drop real images into [`assets/photos/`](assets/photos/) using the **same filenames** so you do not need to edit HTML:

   | File | Suggested subject |
   |------|-------------------|
   | `hialeah-fountain.jpg` | Full-width hero background — Hialeah fountain / city landmark |
   | `hero-clubhouse.jpeg` (or `.jpg`) | First slide in the about-section carousel |
   | `Slides-1.jpg` … `Slides-6.jpg`, `Slides-7.jpeg` … `Slides-21.jpeg` | Carousel slides after `hero-clubhouse` (22 photos total) |
   | `activity-01.jpg` | Nets, meetings, on-air gatherings |
   | `activity-02.jpeg` (or `.jpg`) | Builds, soldering, antennas, test gear |
   | `activity-03.jpg` | Public outreach, fairs, demos, emcomm drills |

   The current JPEGs are **placeholders only** (generated for layout). Compress photos for web (roughly **120–200 KB** each is a good target) before publishing.

3. **Copy** — Update meeting schedule, nets, repeaters, and member call‑sign roster in [`index.html`](index.html).

## Run locally

Open `index.html` in a browser, or from this folder:

```bash
python -m http.server 8080
```

Then visit http://localhost:8080 .

## Hosting

Works on **GitHub Pages**, **Cloudflare Pages**, **Netlify**, or any static host: upload the repository root as the site root (where `index.html` lives).

## License

Club-specific content — use and adapt as appropriate for your organization.
