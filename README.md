# Decision Tree PWA

A personal decision tree builder. Design trees in Build mode, step through them in Walk mode. Works offline, installable on any device.

---

## Deploy to GitHub Pages (free, ~5 minutes)

### 1. Create a GitHub repo

Go to [github.com/new](https://github.com/new) and create a new **public** repository.  
Name it anything — e.g. `decision-tree`.

### 2. Push these files

```bash
cd decision-tree-pwa
git init
git add .
git commit -m "initial"
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

### 3. Enable GitHub Pages

In your repo on GitHub:  
Settings → Pages → Source → **Deploy from a branch** → `main` / `(root)` → Save.

Your app will be live at:  
`https://YOUR_USERNAME.github.io/YOUR_REPO/`

(Takes ~1 minute to deploy after pushing.)

---

## Install as an app

**Desktop (Chrome / Edge)**  
Open the URL → look for the install icon (⊕) in the address bar → Install.  
It'll appear in your Applications folder / Start Menu like a native app.

**iPhone / iPad (Safari)**  
Open the URL in Safari → Share button → "Add to Home Screen".

**Android (Chrome)**  
Open the URL → three-dot menu → "Add to Home Screen" or "Install app".

---

## Update the app

Just edit the files and push again:

```bash
git add .
git commit -m "update"
git push
```

GitHub Pages deploys automatically. The service worker will pick up the new version on next load.

---

## Custom domain (optional)

Add a `CNAME` file containing your domain (e.g. `tree.yourdomain.com`), then point a DNS CNAME record at `YOUR_USERNAME.github.io`. GitHub Pages handles the HTTPS cert automatically.
