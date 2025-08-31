# Certairis Landing Page

A single-file static site ready for GitHub Pages.

## Quick Start (Project Site)

1. Create a repo on GitHub (e.g., `certairis-site`).
2. Upload `index.html` (and these files) to the repo root.
3. Go to **Settings → Pages**:
   - **Source**: Deploy from a branch
   - **Branch**: `main` (or `master`) and root (**/**)
4. Open: `https://<your-username>.github.io/<repo-name>/`

## User Site (optional)

If you want `https://<your-username>.github.io/` (no repo suffix):
- Create a **new** repo named exactly `<your-username>.github.io`
- Upload **this same** `index.html` to that repo root.
- It will serve at the user root domain.

## Custom Domain (optional)

- Add your domain in **Settings → Pages → Custom domain** (e.g., `www.yourdomain.com`).
- Create a DNS **CNAME** record: host `www` → `<your-username>.github.io`.
- For apex (root) domain, use ALIAS/ANAME to `<your-username>.github.io` or GitHub A records:
  - 185.199.108.153
  - 185.199.109.153
  - 185.199.110.153
  - 185.199.111.153
- Enable **Enforce HTTPS** when available.

## Notes

- All assets are inline (no build step).
- Edit `index.html` to change copy, colors, or email.
