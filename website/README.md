# Intelliquest Tech Solutions — Website

Regulated AI services website for **Intelliquest Tech Solutions**, specialising in healthcare and financial AI. Based in Cambridge, UK.

## Pages

| Page | File | Description |
|------|------|-------------|
| Homepage | `index.html` | Hero with sector performance stats, clinical & financial AI capabilities, AI innovation trends, engineering process, industry impact metrics, CTA |
| Services | `services.html` | Three engagement packages (Clinical AI Starter, Financial AI Accelerator, Regulatory MLOps Suite), detailed breakdowns of Healthcare AI, Model Governance, Financial AI, and Compliant Deployment services, plus emerging AI trends |
| About | `about.html` | Mission, values, team background, 8 technical expertise areas (Healthcare AI, Financial Risk, Compliance, Fine-Tuning, Clinical Data, MLOps, Federated AI, Strategy), approach philosophy, track record metrics, Cambridge location |
| Contact | `contact.html` | Contact form with regulated-industry interest options, engagement process steps, FAQ section, embedded Google Map of Cambridge |

## Tech Stack

- **HTML5** — semantic, accessible markup
- **CSS3** — custom properties, glassmorphism, grid, flexbox, responsive breakpoints, smooth animations
- **Fonts** — [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) (headings) + [DM Sans](https://fonts.google.com/specimen/DM+Sans) (body) via Google Fonts
- **No JavaScript frameworks** — pure static HTML/CSS (except mobile menu toggle)

## Design System

Light modern theme with purple/blue gradient accents, glassmorphism cards on white surfaces, and subtle floating animations.

| Token | Value | Usage |
|-------|-------|-------|
| `--bg` | `#f5f3f0` | Page background |
| `--fg` | `#1a1a2e` | Body text |
| `--purple` | `#6c3ce0` | Primary accent |
| `--blue` | `#2563eb` | Secondary accent |
| `--cyan` | `#0891b2` | Tertiary accent |
| `--gradient-primary` | `purple → blue → cyan` | Buttons, highlights, gradient text |

## Assets

- `Logo_intelliquest..png` — Company logo (used in navbar and footer)

## Running Locally

No build step required. Open any `.html` file directly, or serve with:

```bash
# Python
python3 -m http.server 8080

# Node
npx serve .
```

Then visit `http://localhost:8080`.

## Deployment

This is a static site — deploy to any hosting provider:

- **GitHub Pages** — push to `main`, enable Pages in repo settings (set source to root or `/docs`)
- **Netlify / Vercel** — connect repo, zero config needed
- **Replit** — import as a static site

### GitHub Pages Quick Start

```bash
git init
git add .
git commit -m "Initial commit: Intelliquest Tech Solutions website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/intelliquest-website.git
git push -u origin main
```

Then go to **Settings → Pages → Source: Deploy from branch → main / root** and save.

## Project Structure

```
website/
├── index.html              # Homepage
├── services.html           # Services page
├── about.html              # About page
├── contact.html            # Contact page
├── styles.css              # Shared stylesheet
├── Logo_intelliquest..png  # Company logo
└── README.md               # This file
```

## SEO

Each page includes optimised meta titles, descriptions, Open Graph tags, canonical URLs, and keyword-rich copy targeting regulated AI services in healthcare and financial sectors.

## Contact

**Intelliquest Tech Solutions**
Cambridge, UK
intelliquest.tech@gmail.com
