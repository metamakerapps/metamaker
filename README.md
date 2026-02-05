# Return Tracker website

Static site for https://metamaker.in/returntracker (GitHub Pages). Contains app info, Privacy, and Terms.

## Run locally

Serve the **project root** so the path `/returntracker/` exists (same as production).

**Option A – Python (port 8000):**
```bash
cd website
python3 -m http.server 8000
```
Open http://localhost:8000/returntracker/

**Option B – npx serve (port 3000 by default):**
```bash
npx serve website -p 3000
```
Open http://localhost:3000/returntracker/

Links are relative, so nav works both locally and on GitHub Pages.

## Deploy

Push the contents of `website/` to the GitHub repo that has Pages enabled (e.g. branch `main` or `gh-pages`). Ensure **CNAME** is set to `metamaker.in` in that repo.
