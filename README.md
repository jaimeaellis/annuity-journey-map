# Annuity Customer Journey Map

An interactive web-based customer journey map for the **Digital First for Annuities** initiative. Built with React + Vite, deployed on GitHub Pages.

## 🔗 Live Site

> **https://YOUR-USERNAME.github.io/annuity-journey-map/**
>
> *(Replace `YOUR-USERNAME` with your GitHub username after deploying)*

## What This Is

An interactive redesign of the annuity product lifecycle journey map, covering five phases — Awareness, Research, Engagement, Usage, and Reflection — across three perspectives:

- **Ideal State** — API best practices and industry standards
- **Advisor Journey** — Key moments and pain points for financial advisors
- **Customer Journey** — The client experience and emotional arc

## Quick Start (Local Development)

```bash
# Install dependencies
npm install

# Start dev server (opens at http://localhost:5173)
npm run dev
```

## Deploy to GitHub Pages

### Option A: Automatic (recommended)
The included GitHub Actions workflow (`.github/workflows/deploy.yml`) automatically builds and deploys every time you push to `main`.

1. Create a new repo on GitHub named `annuity-journey-map`
2. Push this code to it:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/annuity-journey-map.git
   git push -u origin main
   ```
3. Go to **Settings → Pages** in your GitHub repo
4. Under **Source**, select **GitHub Actions**
5. Wait ~2 minutes for the first deploy to finish
6. Your site is live at `https://YOUR-USERNAME.github.io/annuity-journey-map/`

### Option B: Manual
```bash
npm run build
npm run deploy
```

## Tech Stack

- **React 18** — Component framework
- **Vite 6** — Build tool and dev server
- **GitHub Pages** — Free static hosting
- **GitHub Actions** — CI/CD pipeline

## Customizing Content

All journey map data lives in `src/AnnuityJourneyMap.jsx` in the `JOURNEY_DATA` object. Each phase contains touchpoints, moments, pain points, and channels organized by persona. Edit the data directly to update the content.

---

*Built for the Insured Retirement Institute (IRI)*
