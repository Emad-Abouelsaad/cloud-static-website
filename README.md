# Cloud Static Website — Continuous Deployment

A responsive static website hosted on a cloud platform and deployed automatically from GitHub.
Built for the Application and Internet Services course at WSB University.

## What this project demonstrates
- **Cloud hosting** of a static website with HTTPS and CDN delivery
- **Continuous deployment**: the GitHub repository is connected to the hosting platform, so every push to `main` publishes a new version automatically (version 2.0 was released this way)
- **Responsive design** with pure HTML5 and CSS3 (gradient layout, card design, hover effects), no frameworks
- Small JavaScript interaction that confirms the live deployment and shows the load time
- Accessibility basics: `lang` attribute, viewport meta tag, live-region status message

## Tech stack
HTML5, CSS3, JavaScript, Git, GitHub, cloud static hosting / CDN

## Run locally
Open `index.html` in any browser — no build step needed.

## Deploy
1. Connect this repository to a static hosting service (e.g. Netlify, Vercel, GitHub Pages, Azure Static Web Apps).
2. Set the publish directory to the repository root.
3. Push to `main` — the site redeploys automatically.
