# Gptmotion

A self-contained 15-second motion design showreel, built with Canvas 2D and vanilla JavaScript.

## Run locally
Open `index.html` in a modern browser. No build step, package manager, server, or external runtime dependency is required. Google Fonts are optional; system fallbacks are included.

## GitHub Pages
This repository is configured to deploy from GitHub Actions. Pushes to `main` trigger the Pages workflow. In **Settings → Pages**, set **Build and deployment → Source** to **GitHub Actions** once if it is not already selected.

After the first successful deployment, the site is available at:
https://paliparsa.github.io/Gptmotion/

## Controls
- Play / pause
- Scrub the 15-second timeline
- Restart
- Responsive 16:9 desktop and 4:5 mobile composition
- Respects the operating system's reduced-motion preference

The animation is generated live in the browser. No pre-rendered video, npm install, or server-side processing is needed.
