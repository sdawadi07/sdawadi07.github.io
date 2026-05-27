# Swastika Dawadi — Personal Portfolio

Personal portfolio website for Swastika Dawadi, Computer Science senior at the University of New Mexico.

## What it covers

- About / hero section
- Work experience (timeline)
- Selected projects with GitHub links
- Honors & awards
- Leadership & activities
- Technical skills
- Certificates

## Built with

- **HTML5** — semantic structure
- **CSS3** — custom properties, CSS Grid, Flexbox, responsive layout
- **Vanilla JavaScript** — scroll-based active nav highlighting via `IntersectionObserver`
- **Google Fonts** — Bricolage Grotesque, Geist, JetBrains Mono

No build tools, frameworks, or dependencies required.

## Project structure

```
portfolio/
├── index.html    # markup and content
├── styles.css    # all styling and responsive rules
├── script.js     # active nav link on scroll
└── README.md
```

## Run locally

Just open `index.html` directly in any browser — no server needed.

If you prefer a local server (avoids any browser restrictions with file:// URLs):

```bash
# Python 3
python3 -m http.server 8080
# then open http://localhost:8080
```

## Deploy

### GitHub Pages (recommended)

1. Push this folder to a GitHub repository.
2. Go to **Settings → Pages**.
3. Set source to the `main` branch, root folder (`/`).
4. GitHub will publish the site at `https://<username>.github.io/<repo-name>/`.

### Netlify / Vercel

Drag and drop the project folder onto [netlify.com/drop](https://app.netlify.com/drop) for an instant deploy, or connect your GitHub repo for automatic deploys on every push.
