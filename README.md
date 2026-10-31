# EcoPassport — Modern Eco-Tech Multi-page Website

A responsive college-project website built with HTML5, CSS3 and vanilla JavaScript.

## Pages
- `welcome.html` — Welcome and onboarding
- `index.html` — Dashboard
- `diary.html` — Pollution Footprint Diary
- `passport.html` — Digital EcoPassport activities
- `progress.html` — Eco Citizen badges and progress
- `insights.html` — Suggestions and footprint breakdown
- `settings.html` — Profile, calculation factors, export and backup

## Run locally
Keep the `css` and `js` folders beside the HTML files. Open `index.html` in a modern browser. For best results, use VS Code Live Server.

## Publish on GitHub Pages
1. Create a public repository, for example `ECOPASSPORT`.
2. Upload the contents of this folder directly to the repository root (do not upload the outer folder as an extra nested folder).
3. Confirm `index.html`, `css/` and `js/` are visible at the top level.
4. Open Settings → Pages.
5. Choose Deploy from a branch, branch `main`, folder `/ (root)`, then Save.
6. Wait for the Pages deployment to finish. Open `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

## Storage and limitations
- Data is saved in browser `localStorage`; it is not a shared cloud database.
- Data does not automatically sync across devices or browsers. Use JSON backup/restore to move data.
- The emission factors and eco-points are demonstration assumptions for an academic prototype, not official scientific standards. Adjust them with your project guide's approval.
- The site has no server-side authentication. Profile information is local to the current browser.
- Print report uses the browser print dialog; choose Save as PDF to create a PDF.

## Data export
Settings offers a CSV export of diary records and a JSON backup/restore for all local data.
