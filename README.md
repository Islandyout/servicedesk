# ⚙ ServiceDesk — Offline Business Manager

An offline-first service business manager. Manage clients, jobs, invoices, and expenses — all stored on your device. No internet required after install.

---

## 📱 Install as an App (Android)

Once deployed to GitHub Pages, open the URL in **Chrome on your Android phone**, then:

1. Tap the **⋮ menu** (top right)
2. Tap **"Add to Home Screen"** or **"Install App"**
3. Tap **Install**

ServiceDesk will appear on your home screen like a native app and works fully offline.

---

## 🚀 Deploy to GitHub Pages (from your phone)

### Step 1 — Create a GitHub account
Go to [github.com](https://github.com) and sign up if you don't have an account.

### Step 2 — Create a new repository
1. Tap the **+** icon → **New repository**
2. Name it: `servicedesk` (or anything you like)
3. Set it to **Public**
4. Tick **"Add a README file"**
5. Tap **Create repository**

### Step 3 — Upload your files
1. Inside your new repo, tap **Add file → Upload files**
2. Upload ALL of these files:
   - `index.html` ← rename `servicedesk.html` to this!
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
3. Scroll down and tap **Commit changes**

### Step 4 — Enable GitHub Pages
1. Go to your repo **Settings** (top tabs)
2. Scroll to **Pages** in the left sidebar
3. Under **Source**, select **Deploy from a branch**
4. Choose branch: **main** / folder: **/ (root)**
5. Tap **Save**

### Step 5 — Get your URL
After ~1 minute, your app will be live at:
```
https://YOUR-USERNAME.github.io/servicedesk/
```

Open that URL in Chrome on your phone → Install → Done! ✅

---

## 📁 Files in this repo

| File | Purpose |
|------|---------|
| `index.html` | The entire app (HTML + CSS + JS) |
| `manifest.json` | PWA metadata — name, icons, colors |
| `sw.js` | Service worker — enables offline use |
| `icon-192.png` | App icon (home screen) |
| `icon-512.png` | App icon (splash screen) |

---

## 💾 Your data

All data is stored **on your device only** — in your browser's localStorage and IndexedDB. It is never sent to any server.

To move data to a new phone:
1. Go to **Settings → Backup & Data → Full Backup**
2. Save the `.json` file (e.g. via WhatsApp to yourself)
3. On new phone, open the app → **Settings → Restore from Backup**

---

## 🔒 Security

The 4-digit PIN is a **privacy lock**, not encryption. Data is stored unencrypted in the browser. It prevents casual access, not a determined attacker with physical device access.

---

*ServiceDesk v1.3 — Offline-First, Zero Cloud*
