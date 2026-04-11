# Maxwell Okumu Portfolio

A polished personal portfolio website built as a static site for GitHub Pages.

This project presents Maxwell Okumu's work across software engineering, systems architecture, cybersecurity, AI-assisted workflows, and digital product delivery. The site is designed to be fast, professional, and easy to deploy without a build step.

## Live Structure

The site is made up of three core pages:

- `index.html` — landing page, profile, experience, certifications, featured projects, insights, and contact section
- `projects.html` — extended project archive with portfolio case studies
- `blog.html` — insights and LinkedIn-style content layout

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- GitHub Pages for hosting

No framework or build tooling is required. Deployment is direct from the repository.

## Project Structure

```text
/
├── index.html
├── projects.html
├── blog.html
├── 404.html
├── sitemap.xml
└── assets/
    └── images/
        ├── avatar.png
        ├── favicon.png
        ├── hero-skyline.jpg
        ├── og-pic.jpg
        ├── project-jkusaonline.png
        ├── project-league.png
        ├── project-pinehouse.png
        ├── project-reflex.png
        ├── project-staqpesa.png
        ├── project-toiletafrica.png
        ├── project-tsblog.png
        ├── project-tshome.png
        ├── project-ugandan.png
        ├── video-speaking.jpg
        ├── video-reflex.png
        ├── logo-jkuat.png
        ├── logo-kiriri.svg
        ├── logo-kra.png
        ├── logo-icta.png
        ├── logo-reflex.png
        ├── logo-trendsetters.png
        ├── logo-ibm.svg
        ├── logo-linkedin.png
        └── logo-zscaler.png
```

## Features

- Responsive multi-page portfolio layout
- Featured and full project showcase
- Local asset-backed logos and thumbnails
- Open Graph and Twitter preview images
- JSON-LD structured data on the home page
- Favicon support
- GitHub Pages ready deployment

## SEO And Social Sharing

The site includes:

- canonical URLs
- Open Graph metadata
- Twitter image metadata
- structured data on the landing page
- a dedicated social preview image at `assets/images/og-pic.jpg`

If the production domain changes, update the absolute URLs in the meta tags and schema blocks.

## Customization

### Profile content

Update text content directly in:

- `index.html`
- `projects.html`
- `blog.html`

### Contact form

The contact form uses Formspree. Replace the placeholder form endpoint in `index.html` with your real Formspree URL.

Example:

```html
https://formspree.io/f/YOUR_FORM_ID
```

### Images and logos

Portfolio assets are stored in `assets/images/`.

The current site already uses local filenames that match the HTML references. If you replace any image, keep the same filename unless you also update the corresponding HTML.

Important files:

- `avatar.png` — profile image
- `hero-skyline.jpg` — homepage hero background
- `og-pic.jpg` — social sharing image
- `favicon.png` — browser tab icon

## Running Locally

Because this is a static site, you can open the HTML files directly in a browser.

For a cleaner local preview, use a simple static server.

Example with Python:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Deployment

### GitHub Pages

1. Push the repository to GitHub.
2. Open repository settings.
3. Go to `Pages`.
4. Set the source to the main branch and root folder.
5. Save and wait for GitHub Pages to publish.

The site is intended for deployment at:

`https://maxwellokumu.github.io`

## Maintenance Notes

- Keep image filenames aligned with the HTML references.
- Prefer local assets for critical icons and branding images.
- If you add new social cards or schema, keep them consistent across all pages.
- If you change the site URL, update all canonical, Open Graph, Twitter, and JSON-LD links.

## License

This project is intended for personal portfolio use unless a separate license is added.
