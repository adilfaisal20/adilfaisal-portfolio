# Adil Faisal — Portfolio Site

A static personal portfolio site built with plain HTML, CSS, and JavaScript.

## Structure

```
/
├── index.html          → main page (all sections)
├── styles.css           → all styling
├── script.js             → nav toggle, scroll reveal, animated stats
├── vercel.json          → deployment config
└── assets/
    ├── headshot.jpg      → profile photo
    └── Adil_Faisal_CV.pdf → downloadable CV
```

## Deploying to Vercel

1. Push this folder to a GitHub repository.
2. Go to [vercel.com](https://vercel.com) and sign in with GitHub.
3. Click **Add New → Project**, select this repo.
4. Vercel auto-detects it as a static site — no build settings needed. Click **Deploy**.
5. Your site goes live at `yourprojectname.vercel.app`.

Every time you push a new commit to GitHub, Vercel automatically redeploys.

## Making changes later

- **Content/text**: edit `index.html` directly.
- **Colors/spacing/fonts**: edit `styles.css` (all colors are CSS variables at the top of the file — change once, applies everywhere).
- **CV file**: replace `assets/Adil_Faisal_CV.pdf` with an updated version, keeping the same filename (or update the `href` in `index.html` if you rename it).
- **Photo**: replace `assets/headshot.jpg` with a new image, same filename.

After editing, commit and push to GitHub — Vercel redeploys automatically within about a minute.
