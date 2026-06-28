# ZipIt — File Compressor & Zipper

A simple, privacy-first web app that helps anyone compress and zip files directly in their browser — no technical knowledge needed.

---

## What It Does

- Drag and drop files (or click to browse) — any file type works
- Compresses and zips all selected files into one ZIP file
- Shows original size vs zipped size and how much smaller it got
- Tells you if the ZIP is safe to send as an email attachment (under 25MB)
- Files **never leave your device** — everything happens in the browser

---

## How to Deploy (Step-by-Step)

### What You Need
- A free [GitHub](https://github.com) account
- A free [Netlify](https://netlify.com) account (you can sign up using your GitHub account — no separate password needed)

---

### Step 1 — Create a GitHub Repository

1. Go to [github.com](https://github.com) and log in
2. Click the **green "New"** button (top left)
3. Name your repository: `zipit` (or any name you like)
4. Make sure it is set to **Public**
5. Click **"Create repository"**

---

### Step 2 — Upload the File to GitHub

1. Inside your new repository, click **"Add file"** → **"Upload files"**
2. Drag the `index.html` file from your computer into the upload box
3. Scroll down and click **"Commit changes"**

Your file is now saved on GitHub.

---

### Step 3 — Connect Netlify to GitHub

1. Go to [netlify.com](https://netlify.com)
2. Click **"Sign up"** and choose **"Sign up with GitHub"** — this links both accounts
3. Once logged in, click **"Add new site"** → **"Import an existing project"**
4. Choose **"GitHub"** as your Git provider
5. Find and select your `zipit` repository
6. Leave all settings as they are — no changes needed
7. Click **"Deploy site"**

Netlify will build and publish your site automatically. This takes about 30 seconds.

---

### Step 4 — Get Your Public Link

1. Once deployed, Netlify gives you a link like: `https://random-name-123.netlify.app`
2. Click it to see your live app!
3. To rename the link to something nicer (e.g. `zipit.netlify.app`):
   - Go to **Site settings** → **Domain management**
   - Click **"Options"** next to your site name → **"Edit site name"**
   - Type a new name and save

Share this link with anyone — they can use the app immediately, no installation needed.

---

### Step 5 — Making Updates in the Future

Whenever you want to update the app:
1. Go to your `zipit` repository on GitHub
2. Click on `index.html`
3. Click the **pencil icon** (Edit)
4. Make your changes and click **"Commit changes"**
5. Netlify detects the change automatically and republishes within 30 seconds

---

## Privacy & Security

| | Detail |
|---|---|
| Files uploaded to a server? | **No** — files stay on the user's device |
| Files stored in a database? | **No** — nothing is saved anywhere |
| Works without internet? | **Yes** — after the first page load |
| Data protection concerns? | **None** — no personal data is processed |

This app is safe to share with members of the public without any data governance concerns.

---

## Technical Notes

- Built with plain HTML, CSS, and JavaScript — no frameworks
- Uses [JSZip](https://stuk.github.io/jszip/) for in-browser compression (DEFLATE, level 6)
- Single file — `index.html` is the entire app
- Compatible with all modern browsers (Chrome, Edge, Firefox, Safari)
- Works on desktop and mobile

---

## Future Improvements (Potential)

- [ ] Password-protect the ZIP file
- [ ] Set a maximum file size limit per file
- [ ] Add support for multiple languages
- [ ] Migrate to Isomer for `.gov.sg` hosting and IM8 compliance

---

## Questions?

If you run into any issues deploying the app, refer to:
- [Netlify Documentation](https://docs.netlify.com)
- [GitHub Documentation](https://docs.github.com)
