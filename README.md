# Jewel Padilla — Portfolio

A single-file portfolio site (`index.html`, no build step, no dependencies) hosted for free on GitHub Pages.

## Deploy to GitHub Pages (free, permanent)

1. **Create the repo.** On github.com, create a new public repository named exactly:
   `YOUR-USERNAME.github.io`
   (Using this name means your site lives at `https://YOUR-USERNAME.github.io` with no extra setup.)

2. **Push the files.** In a terminal (PowerShell works fine), from this folder:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/YOUR-USERNAME.github.io.git
   git push -u origin main
   ```

3. **Wait ~1 minute.** Visit `https://YOUR-USERNAME.github.io` — your site is live.

That's it. Because the site is plain HTML on the `main` branch of a `username.github.io` repo, GitHub Pages serves it automatically — no Actions, no settings to toggle.

## Updating the site

Edit `index.html`, then:
```bash
git add .
git commit -m "Update portfolio"
git push
```
Changes appear within a minute or two.

## Alternative: any repo name

If you'd rather use a repo with a different name (e.g. `portfolio`):
1. Push the files to that repo.
2. Go to **Settings → Pages → Source: Deploy from a branch → main / (root) → Save**.
3. Your site will be at `https://YOUR-USERNAME.github.io/portfolio/`.
