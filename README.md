# SurveySparrow Retail Demo (CustomerX 2026)

Static site: `index.html` (demo) + `retail-loop.mp4` (booth video). `CNAME` is set to `retail.backyardsaas.com`.

## Publish on GitHub Pages
1. Create a public repo, e.g. `retail-demo`, and upload all files in this folder to the root.
2. Repo **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `main` / `(root)`. Save.
3. In your DNS provider for backyardsaas.com add:
   `CNAME  retail  →  <your-github-username>.github.io`
4. Back in Settings → Pages, confirm the custom domain shows `retail.backyardsaas.com`, wait for the DNS check, then tick **Enforce HTTPS**.

The video is then at https://retail.backyardsaas.com/retail-loop.mp4

## Booth TV / iPad loop
Open `/tv` (e.g. https://retail.backyardsaas.com/tv) in Safari. It plays the video muted, full screen, on an endless loop.
For kiosk mode on iPad: Share → Add to Home Screen, open it from the icon, then turn on Guided Access (Settings → Accessibility → Guided Access, triple-click the side/top button).
