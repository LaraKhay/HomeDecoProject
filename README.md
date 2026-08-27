# HomeDeco

A single-page marketing website for **Colram®**, an architecture and interior design studio, built as a static HTML/CSS/JS project.

## About

HomeDeco is a portfolio/brochure site showcasing an architecture and design studio that partners with clients worldwide on buildings, landscapes, interior, and digital experiences. The page walks visitors through the studio's story, project portfolio, design process, service offerings, and recent insights, ending with contact details and a newsletter signup.

## Sections

- **Header** — animated intro with background video
- **About Us** — studio introduction and mission
- **Projects** — gallery of completed architecture/interior projects (France, Denmark, Germany, Sweden, Spain, England, etc.)
- **Approach** — 4-step design process: Discovery & Inspiration, Concept & Style, Design & Detailing, Execution & Styling
- **Our Services** — company milestones and service overview
- **What We Do** — tabbed list of service categories (Architecture, Strategic Design, Interior Design, Product Design, Landscape Design, Curatorial Design, Lighting)
- **Recent Insights** — blog/article previews
- **Contact Us** — contact info, address, social links, and newsletter signup form

## Tech Stack

- **HTML5 / CSS3** — page structure and custom styling (`index.html`, `style.css`)
- **[Bootstrap 5.3](https://getbootstrap.com/)** — layout grid, navbar, tabs
- **[jQuery 3.7.1](https://jquery.com/)** — nav highlighting, scroll-based animations, tab interactions
- **[Animate.css](https://animate.style/)** — entrance/scroll animations
- **[Font Awesome](https://fontawesome.com/)** — icons
- **[Google Fonts](https://fonts.google.com/)** — Urbanist typeface

All third-party libraries are vendored locally under `vendors/` — no CDN dependency except for Google Fonts.

## Project Structure

```
HomeDecoProject/
├── index.html          # Main page markup
├── style.css           # Custom styles
├── images/             # Project photos, background videos
└── vendors/            # Locally vendored libraries
    ├── bootstrap5.3/
    ├── animate.css/
    ├── fontawesome/
    └── jquery/
```

## Getting Started

This is a static site with no build step. Simply open `index.html` in a browser, or serve it locally:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
