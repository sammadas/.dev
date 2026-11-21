# SAMMA DAS — 3D Portfolio

## Run locally
1. Put your photo at `assets/images/profile.jpg`.
2. Optional: put your CV at `assets/documents/samma-das-cv.pdf`. The CV button appears only when this file exists.
3. Open the folder with VS Code "Live Server", or run `python -m http.server 8000` and visit http://localhost:8000.

## Publish (GitHub Pages)
Upload all files and folders from inside this folder to a public repository, then enable Pages from the `main` branch, `/ (root)`.
After publishing, add your real address to `index.html` as `<link rel="canonical">`.

## Edit content
All content is in `script.js`: `SKILLS`, `PROJECTS`, `SOCIAL`, and `I18N` (Bengali and English).
- Add the live link (`url`) and real technologies (`tech`) to each project. Empty links are not shown.
- Add your GitHub URL in `SOCIAL`.

## Features
- Light and dark theme, remembered between visits.
- Live Bangladesh clock (Asia/Dhaka).
- Contact form with validation and a spam trap. The form cannot send messages by itself yet. It opens the visitor's email app with the message filled in.
- Installable as an app, with offline fallback (`manifest.json`, `sw.js`).

## Not included yet (add when you have real content)
- Blog, testimonials, visitor analytics, project detail pages, and a 404 page. These were left out so the site shows no made-up content.
