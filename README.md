# ML Daily Routine

A single-page app for a 56-day ML engineering plan: daily routine, reading list, coding challenge, and progress tracking. No build step, no dependencies. Progress is saved in your browser (localStorage).

## Run locally

Open `index.html` in a browser.

## Deploy with GitHub Pages

1. Create a new repository on GitHub (for example `ml-daily-routine`).
2. Add `index.html` and `README.md` to the repository root and commit.
   ```bash
   git init
   git add index.html README.md
   git commit -m "Add ML daily routine app"
   git branch -M main
   git remote add origin https://github.com/<your-username>/ml-daily-routine.git
   git push -u origin main
   ```
3. On GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose branch **main** and folder **/ (root)**, then save.
5. After a minute, the app is live at `https://<your-username>.github.io/ml-daily-routine/`.

## Customize

- Edit the `W` array in `index.html` to change topics, readings, and challenges.
- Change `N` (days) and the storage key `K` if you restructure the plan.

## Note

Progress lives in the browser you use, so it does not sync between devices. Use the same browser each day, or ask for an export/import feature.
