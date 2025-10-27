# BewerbungsWerk Landing Page

Static marketing site for the BewerbungsWerk service, highlighting offerings that help apprentices craft polished application materials.

## Features
- Responsive layout with a sticky header and collapsible navigation for smaller screens.
- Hero section with visual storytelling and call-to-action linking to services.
- Services grid describing the core offerings at a glance.
- About and contact sections with dynamic current-year footer.
- Lightweight footprint using only semantic HTML, modern CSS, and a sprinkle of vanilla JS.

## Project Structure
```
.
├── images/         # Logo and hero illustration assets
├── index.html      # Markup for the landing page
└── styles.css      # Visual design, layout, and responsive styling
```

## Getting Started
1. Clone or download this repository.
2. Open `index.html` directly in your browser **or** run a simple static server:
   ```bash
   cd path/to/bewerbungswerk
   python3 -m http.server 8000
   ```
3. Visit `http://localhost:8000` in your browser.

## Deployment
- Push changes to the `main` branch; the included GitHub Actions workflow publishes the site to GitHub Pages automatically.
- On first use, visit your repository settings → Pages and confirm the build and deployment source is set to "GitHub Actions".
- After the workflow completes, the live site URL is exposed in the deployment summary and under the Pages settings screen.

## Customising
- Replace assets in `images/` with brand-appropriate alternatives.
- Update copy in `index.html` to reflect new services or contact details.
- Adjust colours, typography, and layout tokens in `styles.css` under the `:root` variables.

## Notes
- No build tooling or dependencies are required.
- A license has not been provided; add one if you plan to publish the project.
