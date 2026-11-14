# Personal site

Plain HTML and CSS, no build step.

## Put it on GitHub Pages
1. Create a repo (for example `thomas-site`) and upload everything in this folder, including `.nojekyll`.
2. Repo Settings > Pages > Build and deployment: Source "Deploy from a branch", branch `main`, folder `/ (root)`.
3. Your site appears at `https://ThomasKarabo.github.io/thomas-site/`.

## Custom domain
1. Add a file named `CNAME` in the repo root containing only your domain, e.g. `thomasmohlapo.com`.
2. At your domain registrar add DNS records:
   - `www`: CNAME to `thomaskarabo.github.io`
   - apex domain: four A records to 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
3. In Settings > Pages enter the domain and tick "Enforce HTTPS" once it's available (DNS can take a few hours).
