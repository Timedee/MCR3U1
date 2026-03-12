# MCR3U Quiz Prep — Quadratic Functions

Study app for Sections 3.1 & 3.2 + Mid-Chapter Review (p.170).

**50 practice questions · 35 flashcards · Study guide · Cheat sheet**

## Deploy to GitHub Pages (5 minutes)

### Step 1 — Create a GitHub repo
1. Go to github.com → click **New repository**
2. Name it `mcr3u-quiz` (or anything you want)
3. Set it to **Public**
4. Click **Create repository**

### Step 2 — Upload these files
Drag and drop the entire folder contents into the repo, OR use GitHub Desktop.

Make sure the file structure looks like this:
```
mcr3u-quiz/
├── index.html
├── package.json
├── vite.config.js
├── src/
│   ├── main.jsx
│   └── App.jsx
└── .github/
    └── workflows/
        └── deploy.yml
```

### Step 3 — Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages**
2. Under **Source**, select **GitHub Actions**
3. Click **Save**

### Step 4 — Trigger the deploy
The workflow runs automatically on every push to `main`.
Go to the **Actions** tab to watch it build (takes ~1 minute).

### Step 5 — Access your app
Your app will be live at:
```
https://YOUR-GITHUB-USERNAME.github.io/mcr3u-quiz/
```

## Local development
```bash
npm install
npm run dev
```
