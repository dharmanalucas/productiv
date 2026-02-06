# Daily System PWA

Your ADHD-friendly daily planning app. No decisions in the morning — plan tonight, execute tomorrow.

## Deploy to GitHub Pages (5 minutes)

### 1. Create a GitHub repo
- Go to [github.com/new](https://github.com/new)
- Name it `daily-system` (or whatever you want)
- Make it **Public** (required for free GitHub Pages)
- Click **Create repository**

### 2. Upload files
- On the repo page, click **"uploading an existing file"** link
- Drag in ALL 5 files from this folder:
  - `index.html`
  - `manifest.json`
  - `sw.js`
  - `icon-192.png`
  - `icon-512.png`
- Click **Commit changes**

### 3. Enable GitHub Pages
- Go to repo **Settings** → **Pages** (left sidebar)
- Under "Source", select **Deploy from a branch**
- Branch: **main**, folder: **/ (root)**
- Click **Save**
- Wait 1-2 minutes, your site will be live at:
  `https://YOUR-USERNAME.github.io/daily-system/`

### 4. Add to your phone home screen
**iPhone:**
1. Open the URL in **Safari** (must be Safari, not Chrome)
2. Tap the **Share** button (square with arrow)
3. Scroll down, tap **Add to Home Screen**
4. Name it "Daily System", tap **Add**

**Android:**
1. Open the URL in **Chrome**
2. Tap the **three dots** menu
3. Tap **Add to Home Screen** or **Install app**

### Done!
It now works like a native app — full screen, no browser bar, works offline.
Your tasks save to your phone's local storage and persist between sessions.

## Updating the task bank
Edit `index.html` and modify the `TASK_BANK` object near the top of the `<script>` section. Push to GitHub and it'll update automatically.
