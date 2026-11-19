# FreeDomain Studio

A browser-based, folder-style static website builder. This is **not a domain registrar**.

## Features
- File explorer with editable `index.html`, `style.css`, and `script.js`.
- Add more project files.
- Live preview with desktop and mobile widths.
- Build checks for the static website.
- Save working files in browser local storage.
- Download individual source files or the whole project as a ZIP.
- Starter eSports-style website template.

## Run and use
Open the deployed site in a modern browser. No Node.js, Python, or local installation is required for the included HTML/CSS/JS starter project.

## Build / install / deploy
- **Build:** checks the project and refreshes its preview.
- **Install:** this starter has no external packages, so no install step is required.
- **Download:** exports a ZIP containing the website folder and its files.
- **Deploy:** the Cloudflare button opens the Pages dashboard. The builder's own site is deployed from this GitHub repository automatically on pushes to `main`.

## Current limitations
The editor saves projects in the current browser only. The Deploy button does not yet upload an individual customer's edited folder to GitHub/Cloudflare. That needs a secure GitHub authorization flow and server-side project publishing. Custom domains and customer accounts are not included yet.

## Cloudflare Pages
Repository: https://github.com/sd201826/Free-Domain
Project: https://freedomain-studio.pages.dev
Production branch: `main`; framework preset: None; build command: blank; output directory: `/`.
