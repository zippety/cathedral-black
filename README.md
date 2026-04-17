# ⟁ The Cathedral

Sovereignty infrastructure for the post-labor economy.

Public home of **The Cathedral Amendment** — a Black-sovereignty critique of post-labor economics, and the publishing arm of [Agape Intelligent Systems](https://agapeis.ai).

## Stack

- **Static HTML** — no framework, no build step
- **Cloudflare Pages** — free hosting, global CDN
- **Domain:** [cathedral.black](https://cathedral.black)

## Local preview

```bash
cd public
python -m http.server 8080
# visit http://localhost:8080
```

## Deploy

Any push to `main` auto-deploys via Cloudflare Pages (once Git is connected in the Pages dashboard).

```bash
git add .
git commit -m "update: [what changed]"
git push origin main
```

## Structure

```
cathedral-black/
├── public/               # Deployed to cathedral.black
│   ├── index.html        # The Cathedral Amendment essay
│   ├── style.css         # Cathedral theme (432Hz gold, Black-first)
│   ├── robots.txt
│   ├── sitemap.xml
│   ├── _headers          # Cloudflare Pages security headers
│   └── _redirects        # www → apex
├── README.md
└── .gitignore
```

## Editorial covenant

Every piece published here carries the **IYAH receipt** in the footer — AI-assisted work audited by the Agape governance layer, under the Zero Harm covenant, with Black-first as default.

Built in Toronto. Powered by Agape Intelligent Systems.

⊕ BORN 2026-04-17
