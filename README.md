# StudyFlow

A responsive study workspace built with semantic HTML, modern CSS and vanilla JavaScript. No build step is required; it runs from `index.html` and deploys to GitHub Pages.

## Features
- Responsive dashboard and weekly activity visualization
- Subject tracking and progress indicators
- Task planner with completion state
- Interactive flashcards
- Notes saved locally
- 25-minute focus timer
- localStorage persistence
- Mobile navigation and reduced-motion support
- GitHub Actions deployment workflow

## Run locally
Open `index.html` or use VS Code Live Server.

## Deploy
The included GitHub Actions workflow deploys on pushes to `main`. In repository Settings → Pages, select **GitHub Actions** as the source. The live URL appears in the workflow run.

## Structure
- `index.html` — application shell
- `assets/css/main.css` — design tokens, responsive layout and components
- `assets/js/app.js` — application entry and navigation
- `assets/js/core/store.js` — local data and persistence
- `assets/js/core/views.js` — screen rendering
- `assets/js/core/ui.js` — dialogs and notifications
- `assets/js/core/timer.js` — focus timer
- `.github/workflows/pages.yml` — deployment

## Privacy and AI
Study data remains in this browser. No cloud sync or real AI provider is configured. For a production AI connection, add a server-side API and keep keys in server environment variables — never in public frontend JavaScript.

## Figma
https://www.figma.com/design/rAjBZFsMXKRDyPxEJguvIp