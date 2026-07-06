# Eniolorundalola Photography & Media Concept

Premium single-page marketing site for a Nigerian photography and media studio.

## Project Structure

```text
.
├── index.html
├── README.md
└── images/
    ├── hero.jpg
    ├── gallery-wedding-1.jpg
    ├── gallery-wedding-2.jpg
    ├── gallery-wedding-3.jpg
    ├── gallery-wedding-4.jpg
    ├── gallery-wedding-5.jpg
    ├── gallery-wedding-6.jpg
    ├── gallery-portrait-1.jpg
    ├── gallery-portrait-2.jpg
    ├── gallery-portrait-3.jpg
    ├── gallery-portrait-4.jpg
    ├── gallery-event-1.jpg
    ├── gallery-event-2.jpg
    ├── gallery-event-3.jpg
    └── gallery-event-4.jpg
```

## Preview Locally

No build step is required. Open `index.html` directly in a browser, or serve the folder with any static server:

```bash
python -m http.server 8080
```

Then visit `http://localhost:8080`.

## Deployment

### Netlify

Use these settings:

- Build command: leave blank
- Publish directory: `.`

Drag the folder into Netlify Drop, or connect the repository and use the settings above.

### GitHub Pages

Push this folder to a repository, then enable GitHub Pages from the repository settings:

- Source: deploy from a branch
- Branch: `main`
- Folder: `/ (root)`

## Notes

- This is a static site: plain HTML, CSS, and JavaScript in `index.html`.
- Tailwind CSS is loaded from the CDN.
- Google Fonts are loaded from Google-hosted CSS.
- Image paths are relative, for example `images/hero.jpg`.
- The booking form opens a pre-filled WhatsApp message instead of sending to a backend.
