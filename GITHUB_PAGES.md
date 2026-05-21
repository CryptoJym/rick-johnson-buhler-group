# GitHub Pages Package - Buhler Group AI Visibility

This project has a static GitHub Pages-ready review site under `docs/`.

## Files

- `docs/index.html` - Buhler Group AI Search Visibility review page with embedded Gamma deck, research basis, production scan data, conclusions, caveats, and source map
- `docs/buhler-ai-search-visibility/index.html` - compatibility route that redirects back to the integrated review page
- `docs/styles.css` - New Reward branded responsive styling
- `docs/assets/` - New Reward brand assets
- `docs/.nojekyll` - tells GitHub Pages to serve the static files directly

## Route

- GitHub Pages URL: `https://cryptojym.github.io/rick-johnson-buhler-group/`
- `/` - Buhler Group AI Search Visibility Snapshot review page, embedding `https://buhler-group-ai-search-v-5cw1f8g.gamma.site/`
- `/buhler-ai-search-visibility/` - redirect/compatibility route for the prior Pages path

## Publish Settings

In GitHub, set Pages to:

- Source: deploy from a branch
- Branch: the branch that contains this project
- Folder: `/docs`

The page is static HTML/CSS and does not require a build step.

## Boundary

This is the dedicated Pages package for the Rick Johnson / Buhler Group lead. Keep internal research, production execution notes, private contact details, raw scan files, and backend diagnostics out of the public Pages repository unless a sanitized excerpt is explicitly prepared for publication.
