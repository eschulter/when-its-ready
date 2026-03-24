# When's it ready? — PWA

A progressive web app for perfect microwave timing. Installable on any phone.

## Deploy to GitHub Pages (5 minutes)

### Step 1: Create a GitHub repo
1. Go to [github.com/new](https://github.com/new)
2. Name it `whens-it-ready` (or whatever you want)
3. Set it to **Public**
4. Click **Create repository**

### Step 2: Upload the files
1. On your new repo page, click **"uploading an existing file"** link
2. Drag the entire contents of this folder into the upload area:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icons/` folder (with both PNG files inside)
3. Click **Commit changes**

### Step 3: Enable GitHub Pages
1. Go to your repo's **Settings** tab
2. Click **Pages** in the left sidebar
3. Under "Source", select **Deploy from a branch**
4. Choose **main** branch, **/ (root)** folder
5. Click **Save**
6. Wait 1-2 minutes for deployment

### Step 4: Your app is live!
Your app will be at: `https://YOUR-USERNAME.github.io/whens-it-ready/`

### Step 5: Install on your phone
1. Open the URL on your phone's browser
2. **iPhone**: Tap the Share button → "Add to Home Screen"
3. **Android**: Tap the menu (⋮) → "Install app" or "Add to Home Screen"
4. The app now works offline and looks like a native app!

## Updating the app
Just edit the files in your GitHub repo and commit. GitHub Pages auto-deploys within a minute.

## Custom domain (optional)
1. Buy a domain (e.g. `whensitready.app` from Namecheap, Google Domains, etc.)
2. In your repo Settings → Pages, enter your custom domain
3. Add a CNAME record pointing to `YOUR-USERNAME.github.io`
4. Enable "Enforce HTTPS"

## Files
```
whens-it-ready-pwa/
├── index.html      # The full app (HTML + React via CDN)
├── manifest.json   # PWA manifest for installability
├── sw.js           # Service worker for offline support
├── icons/
│   ├── icon-192.png
│   └── icon-512.png
└── README.md       # You're reading it
```
