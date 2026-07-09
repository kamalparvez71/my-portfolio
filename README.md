# Kamal Parvez — Portfolio Site

A single-page portfolio built from your resume, styled as an API/status-page
("GET /experience", "GET /skills", etc.) to match your backend/API background.

## Files
- `index.html` — the whole site (HTML/CSS/JS, no build step, no dependencies)
- `netlify.toml` — basic Netlify config

## Deploy to Netlify (easiest: drag & drop, ~1 minute)
1. Go to https://app.netlify.com and log in (or create a free account).
2. Go to **Sites** → you'll see a box that says **"Drag and drop your site output folder here"**.
3. Drag the whole `portfolio` folder (containing `index.html` and `netlify.toml`) into that box.
4. Netlify uploads it and gives you a live URL like `https://random-name-123.netlify.app`.
5. Optional: click **Site settings → Change site name** to get a nicer URL like `kamalparvez.netlify.app`.
6. Optional: **Domain settings → Add a custom domain** if you own one (e.g. kamalparvez.dev).

## Deploy via GitHub (better if you want auto-updates later)
1. Push this folder to a new GitHub repo (e.g. `kamal-portfolio`).
2. In Netlify: **Add new site → Import an existing project → GitHub** → pick the repo.
3. Build command: leave blank. Publish directory: `.` (already set in `netlify.toml`).
4. Click **Deploy** — every future push to the repo auto-redeploys the site.

## Editing content later
Everything is in `index.html` — plain HTML, no build tools needed. Search for the
section you want to change (`id="summary"`, `id="experience"`, `id="skills"`, etc.)
and edit the text directly, then re-drag the folder into Netlify to update.
