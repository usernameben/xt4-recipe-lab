# XT4 Recipe Lab — PWA

Fujifilm X-T4 film simulation recipe generator for Soviet/Russian vintage lenses.
Works fully offline once installed. No build step required.

## Deploy to GitHub Pages (5 minutes)

### 1. Create a GitHub repo
Go to https://github.com/new and create a new **public** repo.
Name it something like `xt4-recipe-lab`.

### 2. Upload the files
Drag and drop all four files into the repo via the GitHub web UI:
- `index.html`
- `manifest.json`
- `sw.js`
- `icon-192.png`
- `icon-512.png`

Or use git:
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/xt4-recipe-lab.git
git push -u origin main
```

### 3. Enable GitHub Pages
- Go to your repo → **Settings** → **Pages**
- Under **Source**, select `Deploy from a branch`
- Choose `main` branch, `/ (root)` folder
- Click **Save**

### 4. Done!
After ~60 seconds your app will be live at:
`https://YOUR_USERNAME.github.io/xt4-recipe-lab/`

Visit it on your iPhone in Safari → tap the Share button → **Add to Home Screen**
to install it as a PWA with offline support.

## Features
- 6 Soviet lens profiles (Helios 44-2, Helios 40-2, Jupiter-9, Industar-61, Mir-1B, Jupiter-37A)
- 6 shooting styles
- Lens-aware recipe engine (adjusts settings per optical characteristics)
- Full offline support via service worker
- Install to home screen (iOS Safari & Android Chrome)
- Copy recipe to clipboard
