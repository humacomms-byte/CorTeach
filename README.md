# Baqai Medical University — Online & Blended Learning Portal
### In Partnership with CorTeach (Digital Collaborator)

---

## Deploy to Netlify

### Option A — Drag & Drop (Fastest)
1. Open terminal in this folder
2. Run: `npm install` then `npm run build`
3. Go to https://app.netlify.com/drop
4. Drag the `build/` folder → live instantly

### Option B — GitHub Auto-Deploy
1. Push this folder to GitHub
2. Go to https://app.netlify.com → New site → Import from Git
3. Build command: `npm run build` | Publish directory: `build`
4. Deploy — every `git push` auto-deploys

### Option C — Netlify CLI
```bash
npm install -g netlify-cli
npm install && npm run build
netlify deploy --prod --dir=build
```

---

## Run Locally
```bash
npm install
npm start
# Opens at http://localhost:3000
```

---

## Update Content
Edit `src/data.js` — courses, calendar, announcements are all there.

## Logos
- `public/bmu-logo.png` — Baqai Medical University
- `public/corteach-logo.png` — CorTeach

---

© 2026 Baqai Medical University × CorTeach
