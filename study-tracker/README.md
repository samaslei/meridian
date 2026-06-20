# Study Tracker

A fully client-side study tracking app. No backend required.

## Project Structure

```
study-tracker/
├── public/
│   └── index.html    ← the entire app
└── vercel.json       ← Vercel deployment config
```

## Deploy to Vercel

### Option A — Vercel CLI
```bash
npm i -g vercel
vercel
```

### Option B — Vercel Dashboard
1. Push this folder to a GitHub repo
2. Go to https://vercel.com/new
3. Import the repo — Vercel auto-detects the config
4. Click **Deploy**

No build step or environment variables needed.
