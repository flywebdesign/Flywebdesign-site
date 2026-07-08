# Flynn Brothers Web Design — Agency Website

The marketing site for **flywebdesign.org**. Plain static HTML + Tailwind (CDN) —
no build step. Whatever is in this folder is what goes live.

## Files
- `index.html` — the main one-page site (hero, demo, pricing, contact)
- `plan.html` — the "Build your plan" wizard
- `demo.html` — the El Fuego demo restaurant, embedded on the home page

## How to edit
1. Open the file, make your change (or ask Claude to).
2. Commit and push:
   ```
   git add -A
   git commit -m "what you changed"
   git push
   ```
3. Vercel auto-deploys in ~30 seconds. Refresh flywebdesign.org.

## Hosting
Deployed on Vercel, connected to this GitHub repo. Custom domain: flywebdesign.org.
Do **not** change the domain's MX records — that's the Google Workspace email.
