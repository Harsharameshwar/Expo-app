# REVA Bakery Machinery Collection

This repository contains a self-contained static website. It has no build step or runtime dependencies and can be hosted directly with GitHub Pages.

## Deploy with GitHub Pages

1. Push the `main` branch to GitHub.
2. Open the repository's **Settings** > **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and the `/ (root)` folder, then save.

GitHub will publish `index.html` at the Pages URL shown in that settings screen.

## Preview locally

From this folder, run:

```powershell
python -m http.server 8000
```

Then open <http://localhost:8000>.
