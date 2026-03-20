# The Polymath System — PWA

Your personal Renaissance mastery system, installable as an app on any device.

---

## Files in this folder

| File | What it does |
|------|-------------|
| `index.html` | The main app |
| `manifest.json` | Tells browsers it's an installable app |
| `sw.js` | Service worker — enables offline use |
| `icon-192.png` | App icon (home screen, small) |
| `icon-512.png` | App icon (splash screen, large) |

---

## How to deploy on GitHub Pages (step by step)

### Step 1 — Create a GitHub account
If you don't have one, go to [github.com](https://github.com) and sign up. It's free.

### Step 2 — Create a new repository
1. Click the **+** button in the top right → **New repository**
2. Name it anything, e.g. `polymath`
3. Set it to **Public** (required for free GitHub Pages)
4. Click **Create repository**

### Step 3 — Upload your files
1. On your new repo page, click **uploading an existing file**
2. Drag and drop ALL files from this folder:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
3. Scroll down, click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Go to your repo's **Settings** tab
2. Scroll down to **Pages** in the left sidebar
3. Under **Source**, select **Deploy from a branch**
4. Set branch to **main**, folder to **/ (root)**
5. Click **Save**

### Step 5 — Get your URL
After ~1 minute, your app will be live at:
```
https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/
```
GitHub will show you the exact URL in the Pages settings.

---

## Installing the app on your phone

### Android (Chrome)
1. Open your URL in Chrome
2. Tap the **three dots menu** → **Add to Home screen**
3. Or wait for the automatic install banner to appear

### iPhone (Safari)
1. Open your URL in Safari (must be Safari, not Chrome)
2. Tap the **Share button** (box with arrow)
3. Scroll down → **Add to Home Screen**
4. Tap **Add**

The app will appear on your home screen and open full-screen with no browser bar.

---

## Updating the app later

When you make changes to the HTML:
1. Go to your GitHub repo
2. Click on `index.html`
3. Click the **pencil icon** to edit, or use **Upload files** to replace it
4. Commit the change — it goes live in ~1 minute

> **Note on icons:** The placeholder icons use a hexagon design matching the app's aesthetic. To replace them with custom icons, simply upload new `icon-192.png` and `icon-512.png` files of those exact sizes.
