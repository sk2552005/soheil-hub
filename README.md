# Soheil — Biomedical Entrepreneurship Hub

A one-file, walkable pixel-art portfolio site. Move with WASD/arrow keys or click
anywhere to walk there, or click a folder directly to open it.

## What's inside
- `index.html` — the entire site (HTML + CSS + JS, no build step, no dependencies to install)

Three folders:
1. **About / Contact** — bio + contact links (placeholders — see "before you go live" below)
2. **Biomedical Entrepreneurship** — dissertation, awards, what you're looking for
3. **Pastilak** — brand teaser that links out to pastilak.com

## How to put this on the internet (GitHub Pages, free)

You don't need to know git commands for this — GitHub's website can do it all.

1. Go to [github.com](https://github.com) and log in (or create a free account).
2. Click the **+** icon top-right → **New repository**.
3. Name it anything, e.g. `portfolio` or `soheil-hub`. Keep it **Public**. Click **Create repository**.
4. On the new repo page, click **uploading an existing file** (or drag-and-drop).
5. Drag in `index.html` (and `README.md` if you want). Click **Commit changes**.
6. Go to the repo's **Settings** tab → **Pages** (left sidebar).
7. Under "Build and deployment" → **Source**, choose **Deploy from a branch**.
8. Branch: `main`, folder: `/ (root)`. Click **Save**.
9. Wait ~1 minute, refresh the Pages settings screen — you'll see a green box with your live URL:
   `https://your-username.github.io/repo-name/`

That's it — that URL is live and shareable immediately. Every time you upload a new
version of `index.html` to the repo, the live site updates automatically within a minute.

## Later: your own domain
Once you buy a domain (e.g. `soheil[surname].com`), GitHub Pages supports custom domains
for free — you just add a `CNAME` file and point your domain's DNS at GitHub. We can do
that step together when you're ready; no need to touch hosting again, just DNS settings
at whichever registrar you buy from (Namecheap, GoDaddy, etc.).

## Before you go fully live
Open `index.html` in a text editor (or ask me) and swap these placeholders:
- Email address in the About room (`mailto:your.email@example.com`)
- LinkedIn URL in the About room
- CV/resume link in the About room

Everything else (dissertation details, awards, Pastilak copy) is already filled in
from what you've told me — sanity check the wording before it's public.
