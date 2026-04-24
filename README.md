# Church Hymnal Projector

A fast, bilingual (Twi & English) hymnal projection app for church services. Built to be hosted on Netlify.

## Features
- Instant search by hymn number, Twi title, or English title
- Fullscreen projection mode for TV/screen display
- Keyboard navigation in projection (← → arrow keys, Esc to close)
- Adjustable font size (A− / A+) before projecting
- Add and edit hymns directly in the browser
- All hymns saved automatically in browser localStorage

## How to Deploy on Netlify

### Option 1 — Drag and Drop (fastest)
1. Go to [netlify.com](https://netlify.com) and log in
2. Click **"Add new site"** → **"Deploy manually"**
3. Drag the entire `church-hymnal` folder onto the Netlify drop zone
4. Your site will be live in seconds with a URL like `https://your-site.netlify.app`

### Option 2 — Connect via GitHub
1. Push this folder to a GitHub repository
2. In Netlify: **"Add new site"** → **"Import an existing project"** → connect your GitHub repo
3. No build settings needed — just set publish directory to `/` (root)
4. Click **Deploy**

## Adding Your Hymns
- Click **"+ Add New Hymn"** in the sidebar to add hymns one by one
- Click **"Edit"** on any hymn to update it
- Hymns are saved in your browser's localStorage automatically

## File Structure
```
church-hymnal/
├── index.html   (the entire app — single file, no dependencies)
└── README.md
```
