# Flynn Brothers Web Design — Agency Website

The marketing site for **flywebdesign.org**. Plain static HTML + Tailwind (CDN) —
no build step. Whatever is in this folder is what goes live.

## Files
- `index.html` — the main one-page site (hero, demo, pricing, contact)
- `plan.html` — the "Build your plan" wizard

## The demo
`index.html` and `plan.html` embed/link the **live** El Fuego site at
https://el-fuego-next.vercel.app (the real `el-fuego-next` Next.js project —
a separate repo). There is **no local copy of the demo here anymore** — it
used to be a static `demo.html` snapshot that silently went stale as the real
site evolved. Always point at the live URL so the marketing site automatically
shows whatever's actually deployed, with nothing to keep in sync by hand.

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
