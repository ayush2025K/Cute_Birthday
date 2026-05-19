# Cute_Birthday

A dreamy, cinematic single-file birthday website for Shreya. Includes a countdown, cinematic memories carousel, shayaris, a photo gallery, and a secret love letter with soft background music and animations.

This repository contains a static `index.html` and a `photos/` folder with images used on the site.

## Quick local preview

Open the `index.html` file in your browser:

```bash
open index.html
```

For a simple local server (optional):

```bash
# from the project root
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy to Vercel

1. Go to https://vercel.com and sign in with your GitHub account.
2. Click "New Project" → Import Git Repository → choose `ayush2025K/Cute_Birthday`.
3. For the Project Settings:
   - Framework Preset: "Other" or "Static Site"
   - Build Command: (leave blank)
   - Output Directory: `/`
4. Click Deploy. Vercel will publish the site and provide a URL.

This repository already includes a minimal `vercel.json` to help Vercel recognize the static site.

## Notes
- Replace the default music in `index.html` with your preferred MP3 if desired.
- Ensure the `photos/` folder contains your images (it already does in this repo).

Enjoy — if you'd like, I can also add a GitHub Action or a Vercel badge to the README.