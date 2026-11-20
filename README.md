# Classroom Games (GitHub Pages)

Two browser games for 3rd grade, ready for GitHub Pages.

## Files

```
index.html                  Landing page with links to both games
.nojekyll                   Optional, tells GitHub to serve files as-is
rocket-pizza-math/
  index.html                Rocket Math and Pizza Fractions
storm-chaser-robot/
  index.html                Storm Chaser Robot (six cities)
```

## Publish with Option A (upload in the browser)

1. Sign in at https://github.com and click **New repository**.
   - Name: `classroom-games`
   - Visibility: **Public**
   - Click **Create repository**.
2. Click **Add file → Upload files**.
3. Drag these into the window, then click **Commit changes**:
   - `index.html`
   - `rocket-pizza-math` (the whole folder)
   - `storm-chaser-robot` (the whole folder)
   - `README.md` (optional)
   - `.nojekyll` (optional, see below)
4. Go to **Settings → Pages**.
   - Under **Build and deployment**, set Source to **Deploy from a branch**.
   - Branch: **main**, folder: **/ (root)**, then click **Save**.
5. Wait 1–2 minutes, then open:
   - Landing page: `https://YOUR-USERNAME.github.io/classroom-games/`
   - Rocket Pizza Math: `https://YOUR-USERNAME.github.io/classroom-games/rocket-pizza-math/`
   - Storm Chaser Robot: `https://YOUR-USERNAME.github.io/classroom-games/storm-chaser-robot/`

## Notes

- `.nojekyll` is optional. It is an empty file named `.nojekyll`. Some computers hide files that start with a dot, so if you can't select it, create it in GitHub with **Add file → Create new file** and leave it empty.
- Share the landing page link in Google Classroom so students get both games in one place.
- Best scores are saved in each browser, so they stay on the device where the game was played.
