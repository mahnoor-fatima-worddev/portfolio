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



## Editing content
- Bio, skills, and project text live directly in `index.html`
- Colors and fonts are set as CSS variables at the top of `css/style.css` under `:root`
- Swap `assets/profile.jpg` to update the photo (keep it roughly square for the frame)
