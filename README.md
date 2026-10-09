# PAINT-LINE-DEMO
Interactive 3D paint line demo with a monitoring dashboard, using simulated data.

## Deploy on Vercel

This is a static HTML site and does not require a build command.

1. Push the repository to GitHub.
2. In Vercel, select **Add New...** → **Project**.
3. Import `Parth-Babariya/PAINT-LINE-DEMO`.
4. Leave **Framework Preset** as **Other**.
5. Leave **Build Command** and **Output Directory** empty.
6. Select **Deploy**.

The site entrypoint is [`index.html`](./index.html). The 3D viewer loads Three.js from cdnjs, so the deployed site needs network access to that CDN.
