# Deploying this portfolio to GitHub Pages

1. Create a new repo on GitHub named exactly: `murali5613.github.io`
   (this exact name = GitHub auto-hosts it as your personal site)
2. Upload `index.html` to the root of that repo (drag-and-drop on GitHub's
   web UI works fine, or use git).
3. Go to the repo's **Settings → Pages** and confirm the source is set to
   the `main` branch, root folder. (Usually this is automatic for a
   `username.github.io` repo.)
4. Wait 1-2 minutes, then visit `https://murali5613.github.io` — it's live.

## Updating it later
- **Featured projects**: edit the `.project` blocks directly in `index.html`
  and push the change.
- **"More on GitHub" section**: no action needed — it pulls your public
  repos live from the GitHub API every time someone visits the page.
- **Custom domain (optional)**: buy a domain (Namecheap/Porkbun), add a
  `CNAME` file to the repo with your domain name in it, and point your
  domain's DNS at GitHub Pages per GitHub's docs.
