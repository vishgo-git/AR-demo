# Krishna AR Demo — Setup Instructions

## What you have
- `index.html` — your complete WebAR experience
- These instructions

---

## STEP 1 — Compile your image target (targets.mind file)

MindAR needs to "learn" your trigger image first.
This creates a `targets.mind` file — the fingerprint of your photo.

**Go to this URL:**
https://hiukim.github.io/mind-ar-js-doc/tools/compile

Steps:
1. Click "Upload Image"
2. Upload your temple photo (readlikethem.png or your actual temple photo)
3. Click "Start"
4. Wait ~10 seconds
5. Click "Export" → downloads `targets.mind`

Save this file. You need it alongside index.html.

---

## STEP 2 — Create a free GitHub account

Go to: https://github.com
Click "Sign Up" — use any email, it's free.

---

## STEP 3 — Create a new repository

1. Click the "+" icon (top right) → "New repository"
2. Name it exactly: `krishna-ar-demo`
3. Set to **Public**
4. Check "Add a README file"
5. Click "Create repository"

---

## STEP 4 — Upload your files

Inside your new repository:
1. Click "Add file" → "Upload files"
2. Upload BOTH:
   - `index.html`
   - `targets.mind`
3. Click "Commit changes"

---

## STEP 5 — Enable GitHub Pages

1. Click "Settings" (top of repo)
2. Scroll to "Pages" (left sidebar)
3. Under "Source" → select "Deploy from a branch"
4. Branch: **main** | Folder: **/ (root)**
5. Click "Save"

Wait 2 minutes. Your live URL will appear:
`https://YOUR-USERNAME.github.io/krishna-ar-demo`

---

## STEP 6 — Generate QR Code

Go to: https://qr.io or https://www.qr-code-generator.com
Paste your GitHub Pages URL.
Download the QR code.
Print it alongside your temple photo.

---

## STEP 7 — Test it

1. Open the QR on your phone
2. Allow camera access
3. Point at the temple photo
4. Watch the video appear ✨

---

## Important Notes

- Use in GOOD LIGHTING for best recognition
- Photo should be FLAT (not bent or crumpled)
- Works best on Chrome (Android) and Safari (iPhone)
- First load takes 5-8 seconds (MindAR downloads)
- After first load it's instant

---

## Your YouTube video is already embedded
URL: https://youtu.be/WZECLY-0ImM

To change it later, open index.html and find this line:
```
const YOUTUBE_URL = "https://www.youtube.com/embed/WZECLY-0ImM?autoplay=1&rel=0&modestbranding=1";
```
Replace the video ID (WZECLY-0ImM) with any YouTube video ID.
