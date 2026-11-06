# scalingswarms.com

Project site for "s³: Simple Scaling of Swarms via Cooperative Multi-agent RL".
Static site: `index.html`, `assets/`, `paper.pdf`. `CNAME` points GitHub Pages at scalingswarms.com.

## Deploy (GitHub Pages)
1. Create a new GitHub repo (e.g. `KJha02/scalingswarms`) and push this folder to `main`.
2. Repo Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
3. At your domain registrar, add DNS records for `scalingswarms.com`:
   - Four `A` records for `@`: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - A `CNAME` record for `www` → `kjha02.github.io`
4. Back in Settings → Pages, confirm the custom domain and tick "Enforce HTTPS" once the certificate is issued.
