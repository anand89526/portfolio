# Kumar Anand Portfolio

Static portfolio site built with plain HTML, CSS, and JavaScript.

## Run locally

Because this is a static site, you can open `index.html` directly in the browser.

## Deploy on GitHub Pages

1. Create a new GitHub repository, for example `portfolio`.
2. In this project folder, initialize git if needed:

```powershell
git init
git add .
git commit -m "Initial portfolio site"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/portfolio.git
git push -u origin main
```

3. On GitHub, open the repository.
4. Go to `Settings` -> `Pages`.
5. Under `Build and deployment`, choose:
   Source: `Deploy from a branch`
6. Select:
   Branch: `main`
   Folder: `/ (root)`
7. Click `Save`.
8. Wait 1-3 minutes for GitHub Pages to publish the site.
9. Your live URL will usually be:

```text
https://YOUR-USERNAME.github.io/portfolio/
```

## Update after changes

After editing files, run:

```powershell
git add .
git commit -m "Update portfolio design"
git push
```

GitHub Pages will automatically redeploy.
