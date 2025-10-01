# GitHub Pages — Personal Site Starter

**How to deploy**

1) Create a new repo on GitHub (public is easiest).  
2) Upload these files or drag–drop the zip contents. Commit to `main`.  
3) Go to **Settings → Pages**.  
   - **Source:** Deploy from a branch  
   - **Branch:** `main` (root) → **Save**  
4) Wait ~30–60s, then open the URL shown under Pages.

**Custom domain** (optional)

- Add your domain in **Settings → Pages → Custom domain** (e.g., `about.wenhao.com`).
- Create the right DNS records at your domain registrar:
  - **A** records (apex) → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
  - **CNAME** for subdomain (e.g., `about`) → `<your-username>.github.io`
- Commit a `CNAME` file at repo root containing your domain to keep it sticky.
- Enable **Enforce HTTPS** once the certificate is issued.

**Notes**

- `.nojekyll` prevents Jekyll processing.  
- Put your images under `assets/`. Replace the placeholders.
- Edit `index.html` text and links to make it yours.
