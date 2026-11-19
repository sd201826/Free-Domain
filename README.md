# FreeDomain Studio

A browser-based static website editor with a local multi-project library.

## Project workflow
- Create multiple independent websites using **New project**.
- Open **My websites** to see saved projects and choose **Open & edit**.
- Use **Upload project ZIP** to import a backed-up project as a separate website.
- **Download project** exports the active website folder as a ZIP.
- Each ZIP contains `project.json`, a project identity manifest listing project ID, name, entry HTML file and files. It is not an access token or password.
- Projects are saved in the current browser's local storage. Download ZIP backups to move between browsers/devices.

## Files
Each project has its own `index.html`, `style.css`, `script.js`, and any other added files.

## Build / install / deploy
Build and preview are for static HTML/CSS/JS. No package installation is needed for the starter. Deploy opens Cloudflare. Publishing each customer's individual project to its own live URL is not implemented yet; it requires secure GitHub authorization and a backend deployment workflow. Never store GitHub tokens in project ZIPs or public frontend code.

## Cloudflare Pages
Repository: https://github.com/sd201826/Free-Domain
Project: https://freedomain-studio.pages.dev
