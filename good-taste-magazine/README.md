# Good Taste Magazine

A responsive editorial magazine website featuring food, fashion, restaurants, and culture. Built with semantic HTML, CSS, and vanilla JavaScript.

## Pages

- `index.html` — magazine homepage and featured issue.
- `stories.html` — searchable and filterable story archive.

## Features

- Responsive layouts for desktop and mobile
- Editorial typography and magazine-style layouts
- Search stories by keyword
- Filter stories by category
- Light and dark theme toggle
- Mobile navigation menu
- Local image assets and fallback images
- Accessible labels, focus states, and skip navigation

## Run locally

Open `index.html` in a modern browser, or start a local development server from this folder:

```bash
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Project structure

```text
good-taste-magazine/
├── index.html
├── stories.html
├── styles.css
├── script.js
├── assets/
│   ├── images/
│   └── fonts/
└── README.md
```

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript
- Google Fonts (with local system fallbacks)

## Notes

This is a static front-end project. The homepage and story archive are included locally; individual article detail pages and subscription processing are not part of this project.
