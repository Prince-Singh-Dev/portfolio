# PRINCE OS

Desktop-style portfolio for Prince Kumar Singh. Static site, no build step.

## Files
- `index.html` — markup, SEO, Content-Security-Policy
- `styles.css` — Liquid Glass styling
- `app.js` — window manager and apps
- `vercel.json` — security headers (CSP, nosniff, frame protection, referrer, permissions)

Keep your existing `assets/` folder (resume.pdf, profile/profile.png, projects/*). Add `assets/projects/prepforge-ai.png`.

## Run
VS Code → Live Server on `index.html`.

## Edit content
Search `app.js` for `const ME=`, `const P=`, `const SK=`, `const EXP=`, `const ACH=`.

## Deploy
Put all four files in your repo root, then: git add . && git commit -m "PRINCE OS v2" && git push

## Shortcuts
Ctrl/Cmd+K Spotlight · Ctrl/Cmd+Shift+F Mission Control · Alt+W close · Alt+M minimize · Ctrl+Alt+←/→ snap · Alt+` next window · Space Quick Look (on a project) · Esc close overlays
