# FreeDomain

A responsive white-theme dashboard prototype for the FreeDomain project.

## Deploy with Cloudflare Pages

1. Open Cloudflare Dashboard → **Workers & Pages** → **Create** → **Pages** → **Connect to Git**.
2. Choose the GitHub repository `sd201826/Free-Domain`.
3. Select the `main` branch.
4. Choose **None** as the framework preset.
5. Leave the build command empty and set the build output directory to `/` (repository root).
6. Save and deploy.

## Current scope

This is a frontend prototype in a single `index.html` file. It includes a responsive dashboard, sample website list, search, and a create-website modal. Demo websites are stored in the current browser's local storage.

It does **not** yet provide Google sign-in, real customer accounts, a database, real website publishing, custom domains, or email hosting. Those require a secure backend and Cloudflare configuration. Public URLs should use a username/customer handle (for example `/shachin/project-name`), never a customer's Gmail address.

No Node.js, Python, or build step is required to deploy this static prototype.
