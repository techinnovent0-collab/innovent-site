# Innovent Website Refresh

A modern single-page concept for Innovent (https://www.innovent.io) highlighting IoT + RFID capabilities with rich gradients, responsive layout, and ready-to-host static assets.

## Stack
- Pure HTML + CSS (Space Grotesk typeface)
- No build tooling or dependencies
- Responsive grid + cards + metrics sections

## Structure
```
/
├── index.html   # Main landing page
└── README.md
```

## Deployment
Host via any static provider (GitHub Pages, Netlify, Vercel). Example command for GitHub Pages:
```
gh repo create <user>/innovent-site --public
cd innovent-site
rm -rf .git
git init && git add . && git commit -m "init"
git remote add origin https://github.com/<user>/innovent-site.git
git push -u origin main
```
