# Mahnoor Fatima — Portfolio

A personal portfolio site built with plain HTML, CSS and JavaScript (no build step, no framework).

## Structure
```
index.html
css/style.css
js/script.js
assets/profile.jpg
```

## Run locally
Just open `index.html` in a browser, or serve it locally:
```
npx serve .
```

## Push to GitHub
```
git init
git add .
git commit -m "Initial portfolio site"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo>.git
git push -u origin main
```

## Deploy on Vercel
1. Go to https://vercel.com/new
2. Import the GitHub repo you just pushed
3. Framework preset: **Other** (it's a static site, no build command needed)
4. Click **Deploy**

That's it — Vercel will give you a live `.vercel.app` URL, and you can add a custom domain later from the project's Settings → Domains.

## Editing content
- Bio, skills, and project text live directly in `index.html`
- Colors and fonts are set as CSS variables at the top of `css/style.css` under `:root`
- Swap `assets/profile.jpg` to update the photo (keep it roughly square for the frame)
