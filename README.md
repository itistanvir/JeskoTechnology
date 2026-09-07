# Jesko Technology — Website

This version is a single self-contained file: `index.html` has the logo and favicon embedded directly inside it (no separate `assets` folder needed anymore). Just upload this one file and it will work — this avoids the broken-logo issue that happens when a folder doesn't upload correctly.

## Deploy to GitHub Pages

1. Create a GitHub repository.
2. Upload `index.html` to the root of the repo (drag and drop into "Add file → Upload files", then Commit).
3. Go to **Settings → Pages**, set branch to `main`, folder `/ (root)`, and Save.
4. Your site will be live at `https://<username>.github.io/<repo-name>` within a few minutes.

## Add your own domain

1. In the repo, create a new file named exactly `CNAME` (no extension) containing just your domain, e.g.:
   ```
   jeskotechnology.com
   ```
2. At your domain provider's DNS settings, add:
   - Four **A** records (for the root domain) pointing to:
     `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - A **CNAME** record for `www` pointing to `<username>.github.io`
3. Back in **Settings → Pages**, enter your custom domain in the "Custom domain" box and Save. Enable **Enforce HTTPS** once GitHub verifies it (can take a few hours).

## About the partner logos

The Technology Partners section currently shows each partner as a styled initials tile (e.g. "MS" for Microsoft) rather than each vendor's actual trademarked logo artwork — that's intentional, since using another company's official logo file requires the original artwork. If you can get the official PNG/SVG logos from each vendor's partner portal (as an authorized partner you should have access), send them over and they can be dropped straight into the partner grid in place of the initials tiles.
