# Culture Capital — Website

Single-page marketing site for Culture Capital LLC. Hosted on GitHub Pages at https://culturecapital.fund.

## Files

- `index.html` — the entire site (HTML + CSS + JS + embedded headshots + GSAP/Lenis libraries, all inlined)
- `og-image.png` — 1200×630 social card shown when the link is shared on Slack, iMessage, Twitter, LinkedIn
- `CNAME` — tells GitHub Pages to serve at culturecapital.fund

## Editing

Small copy changes can be made directly in the GitHub web UI: open `index.html`, click the pencil icon, edit, commit. Changes go live in ~1 minute.

For larger changes, edit locally:

```bash
git pull
# edit index.html
git commit -am "describe what changed"
git push
```

## Deploy

Pushes to `main` deploy automatically via GitHub Pages. No build step.

## Stack

- Static HTML, no framework
- GSAP + ScrollTrigger for scroll-driven animation (inlined)
- Lenis for smooth scroll (inlined)
- Anton + Newsreader + JetBrains Mono via Google Fonts
- All headshots embedded as base64 data URIs

## Outstanding

See running checklist in conversation for what still needs attention before this should be considered "done."
