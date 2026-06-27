# LearnYu — Science & Knowledge Portal

An academic-style science portal with clean typography, dynamic article fetching, and Unsplash topic images.

## Features

- **5 Categories** — Physics & Space · Biology & Genetics · Neuroscience · Climate & Earth · Computing History
- **Multi-feed aggregation** — NYT Science, BBC Science, ScienceDaily, NASA, Phys.org via rss2json
- **Relevance scoring** — keyword matching ranks articles by category relevance
- **Dynamic Unsplash images** — topic-matched scientific photography per card
- **Distraction-free reader** — Nature/SA-style modal with clean Merriweather serif typography
- **Real-time search** — filters loaded articles by title/description
- **Per-tab caching** — switching tabs is instant after first load
- **Skeleton loaders** — shimmer placeholders while fetching

## Deploy to GitHub Pages

```bash
git init && git add . && git commit -m "Launch LearnYu"
git remote add origin https://github.com/YOUR_USER/learnyu.git
git push -u origin main
# Settings → Pages → Deploy from main branch root
```

## Tech Stack

- HTML5 · Tailwind CSS (CDN) · Vanilla JS
- rss2json.com (free RSS-to-JSON API, no key)
- Unsplash Source API (free, no key)
- Google Fonts (Merriweather + Inter)
