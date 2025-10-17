# EdgeVend — Under Construction (GitHub Pages)

This package contains a minimal, professional static page you can upload to a public GitHub repository and serve via GitHub Pages.

## How to deploy

1. Create a new public repository on GitHub (e.g., `edge-vend.com`).
2. Upload the two items in this package:
   - `index.html`
   - `assets/edgevend-hero.webp`
3. In GitHub: **Settings → Pages**
   - Source: **Deploy from a branch**
   - Branch: **main** / **root**
4. (Optional but recommended) Set a custom domain under **Settings → Pages → Custom domain**: `edge-vend.com`
5. Point Namecheap DNS to GitHub Pages:
   - **A** (host `@`): 185.199.108.153
   - **A** (host `@`): 185.199.109.153
   - **A** (host `@`): 185.199.110.153
   - **A** (host `@`): 185.199.111.153
   - **CNAME** (host `www`): `<your-github-username>.github.io`

## Edit contact links
- Replace the email in `mailto:` and the LinkedIn URL in the buttons inside `index.html`.