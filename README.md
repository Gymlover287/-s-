# Alnomic AI Ecosystem Webapp

This repository now includes a static preview of the Alnomic AI ecosystem specification and product concept.

## Preview locally

Run a static server from the repository root:

```bash
python3 -m http.server 8765
```

Then open:

```text
http://127.0.0.1:8765/index.html
```

## What the preview includes

- A responsive Alnomic landing/specification page.
- A CSS-built Alnomic-style logo mark and wordmark inspired by the provided image.
- A ChatGPT-style conversation preview showing the Emotional AI and Agent AI working as one ecosystem.
- Sections for architecture, feature behavior, UI/UX design, business model, user journeys, and implementation roadmap.
- Liquid glassmorphism styling and subtle 3D motion interactions.

## Files

- `index.html` — page structure and product/specification content.
- `styles.css` — visual design system, responsive layout, brand mark, and animations.
- `script.js` — pointer-based 3D card interaction with reduced-motion support.
