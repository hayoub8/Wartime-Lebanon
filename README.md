# Wartime Lebanon — Netlify + Decap CMS

## Deploy
1) Push this folder to a GitHub repo.
2) In Netlify: **Add new site → Import from Git** → choose your repo.
3) After deploy: **Identity → Enable Identity → Services → Enable Git Gateway**.
4) **Identity → Invite users** (your email). Login at `/admin/`.

## Editing Content
- News: `content/news.json`
- Articles: `content/articles.json`
- Media uploads go to `static/uploads`

Site reads JSON at build-time (via fetch), so publishing from CMS auto-updates.
